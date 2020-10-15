## Bootstrap Metodu

Türkçeye "yeniden örnekleme" ismiyle çevirilen bu yöntem, bir veri setinden belirlediğimiz tekrar sayısında, belirlediğimiz eleman sayısına sahip örnekler alarak modele ait herhangi bir istatistiğin (ortalama, güven aralığı vb.) tahmin edilmesini ve çıkarım yapılmasını sağlayan istatistiksel bir yöntemdir.

### Güven Aralığı Hesabı için Bootstrap Metodu
* Elimizdeki veriden belirlenen boyutta ve belirlenen tekrar sayısında, random bir şekilde seçilen verilerle örneklem alınır.
* Örneklem için regresyon denkleminin kesme noktası ve diğer katsayılar (ağırlıklar) hesaplanır. Alınan her yeni örneklem için bu işlem tekrarlanır.
* Bu örneklemlerin yüzdelik dilimlerinden güven aralıkları hesaplanır.

![Bootstrap Metodunun Görsel İfadesi](https://miro.medium.com/max/1103/1*iH5w0MBdiOlxDOCX6nmqqw.png)  
___

## Dataset 
* Data : Disney Movies & Box Office Success
* [Download Dataset](https://data.world/kgarrett/disney-character-success-00-16/workspace/file?filename=disney_movies_total_gross.csv)
