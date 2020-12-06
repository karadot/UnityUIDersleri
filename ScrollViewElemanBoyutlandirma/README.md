# ScrollView Eleman Boyutlandirma
Bu basit script ile yatay(horizontal) veya dikey(vertical) vertical olarak kullandığınız ScrollView bileşenlerinde, objelerin merkeze olan mesafelerine göre 
boyutlandırılması sağlanmaktadır. AnimatorCurve ile istenilen değer verilebilmektedir. Mesafe direkt kullanılmıyor, bunun yerine bir Scrollview objesinin genişliğine göre 
oranı ele alınıyor. Bu sayede görünür alan içerisinde en uzak mesafeye göre boyutlandırma değeri oluşturuluyor.
## Kullanım

1. Sahneye "UI>ScrollView" ile scrollview ekleyin.
1. Yatay veya dikey kaydırma için:
      1. ScroolView içerisinde  "vertical" veya "horizontal" özelliklerinden sadece 1 tanesi aktif olsun.
      2. Content objesine "Content Size Filter" ekleyin ve kaydırma tipine göre seçim yapın.
	  2. Content objesin dikey için "Vertical Layout Group", yatay için "Horizontal Layout Group" ekleyin. 
1. ScrolView objesi altında bulunan "Content" isimli objeye scripti atayın.
1. "Content" isimli objeye dönüp bileşenimiz içerisine "Scroll Parent" alanına ScrollView objesini atayın.
1. "Boyutlandirma Orani" adlı değişkene tıklayın. Bir panel açılacak. Yatayda verilen değer, dikeyde de alacağımız değer vardır. Yani yatayda 0 iken merkezde, yatayda 1 iken en uzaktayız. 
Bu durumlarda ve aralarında boyut ne olsun istiyorsanız bunu belirtin.

## Örnek Animation Curve Değerleri ve Sonuçları

| Örnek 1|Örnek 2 	|
|	---	|	---	|
| <img src="https://raw.githubusercontent.com/karadot/UnityUIDersleri/main/ScrollViewElemanBoyutlandirma/ornek1.gif" height="300px" /> 	|   <img src="https://raw.githubusercontent.com/karadot/UnityUIDersleri/main/ScrollViewElemanBoyutlandirma/ornek2.gif" height="300px" />	|
