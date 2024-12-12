# Kanan-Mammadli
https://m7sm4-2iaaa-aaaab-qabra-cai.raw.ic0.app/?tag=914123759

actor hesap_makinesi{
  var hucre: Int = 0;
  
  public func toplama(s: Int) : async Int{
     hucre += s;
     hucre
  };

  public func cikarma(s: Int) : async Int{
    hucre -= s;
    hucre
  };

  public func carpma(s: Int) : async Int{
    hucre *= s;
    hucre
  };

  public func bolme(s: Int) : async ?Int{
    if(s == 0){
      null
    }else{
      hucre /= s;
      ?hucre
    };
  };

  public func temizleme() : async (){
      hucre := 0;
  };

  };
