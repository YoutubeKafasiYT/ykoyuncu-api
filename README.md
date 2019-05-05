Şuanlık Olan Apiler;

Döviz

Örnekler

    Bu örnekte nasıl Döviz Listesini alacağınız gösterilmiş.
    
       (async () => {
      const YKOyuncu = require('ykoyuncu-api');

      const Doviz = new YKOyuncu();
	
      const res = await Doviz.DovizListesi();
	
      console.log(res);
      })();
      
      
      
    Bu örnekte nasıl Döviz Bilgilerini alacağınız gösterilmiş.

     (async () => {
     const YKOyuncu = require('ykoyuncu-api');
    
     const Doviz = new YKOyuncu();
		
     const res = await Doviz.getKur("USD");

     console.log(res);
    })();
      
      
      
      Bu örnekte nasıl Dövizlerin Güncellendiği Tarihi alacağınız gösterilmiş.


     (async () => {
	const YKOyuncu = require('ykoyuncu-api');

        const Doviz = new YKOyuncu();

        const res = await Doviz.guncelTarih();
	console.log(res);
    })();

