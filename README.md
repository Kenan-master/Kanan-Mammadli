# Kanan-Mammadli
https://m7sm4-2iaaa-aaaab-qabra-cai.raw.ic0.app/?tag=914123759

//hesap makinesi 
//değışkenler(let => immutable , var => mutable)
//operatörler
//async methods
//if condition

//canister => akıllı sözleşme



actor hesap_makinesi{
  var hucre: Int = 0;
  //toplama
  //fonksiyon
  public func toplama(s: Int) : async Int{
     hucre += s;
     hucre
     //Debug.print(debug_show (hucre));)
  };
  //çıkarma
  public func cikarma(s: Int) : async Int{
    hucre -= s;
    hucre
  };
  //çarpma
  public func carpma(s: Int) : async Int{
    hucre *= s;
    hucre
  };
  //bölne
  public func bolme(s: Int) : async ?Int{
    if(s == 0){
      null
    }else{
      hucre /= s;
      ?hucre
    };
  };
  //temizle
  public func temizleme() : async (){
      hucre := 0;
  };

  };
