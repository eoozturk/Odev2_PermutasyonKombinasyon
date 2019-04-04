![CoLab](https://colab.research.google.com/assets/colab-badge.svg) [Link](https://colab.research.google.com/drive/1PGqyzuPBcYfdRK9C8_aJgtg62Jg8Dtf5)

# Permütasyon ve Kombinasyon
Permütasyon ve Kombinasyon ile ilgili Soru ve Çözümü

## Soru 1: Permütasyon

BERBERKERTENKELE kelimesindeki harfler yer değiştirilerek anlamlı veya anlamsız 16 harfden oluşan kelimeler oluşturulacaktır. Oluşturulacak olan bu kelimelerin E ile başlayıp R ile bitme olasılığı kaçtır?

### Çözüm:

İstenilen Durum: P(A)= 14! / (2!*5!*2!*2!)= 90810720

Örnek Uzay: P(B)= 16! / (2!*6!*3!*2!)= 1210809600

Olasılık Sonucu: P(A)/P(B)= 0.075

### Açıklama:

Tekrarlı Permütasyon = N! / n1!n2!n3!....nn!

Kelimelerin E harfi ile başlayıp R ile bitme durumu bu iki harfin çıkarılıp kalan 14 harfin tekrarlı permütasyonu ile  14!/2!x5!x2!x2! şeklinde hesaplanır. Daha sonra örnek uzay tüm harfleri kapsayacak şekilde 16!/2!x6!x3!x2! olarak hesaplanır. Soruda istenilen olasılık sonucu istenilen durumun (Kelimelerin E ile başlayıp R ile bitmesi) örnek uzaya bölünmesi ile bulunur.

## Soru 2: Kombinasyon

5 mühendis 4 teknisyen arasından oluşturulacak 4 kişilik bir araştırma ekibinde tek sayıda teknisyen bulunması istenmektedir. Buna göre bu araştırma ekibi kaç farklı şekilde oluşturulabilir?

### Çözüm:

Durum 1:  Bir teknisyenin bulunması:

  C(4,1)xC(5,3)= 4x10= 40

Durum 2:  Üç teknisyenin bulunması:
  
  C(4,3)xC(5,1)= 4x5= 20
  
Tüm Sonuç:

  40+20= 60 farklı şekilde oluşturulabilir.
  
### Açıklama:

C(n,r)= n! / r! * (n-r)!

Araştırma ekibinde tek sayıda teknisyenin bulunması istendiği için ekipteki teknisyen sayısı 1 veya 3 olabilir. Ekipte 1 teknisyenin bulunması durumu  C(4,1)xC(5,3) kombinasyonu ile hesaplanır. Ekipte 3 teknisyenin bulunması durumu ise C(4,3)xC(5,1) kombinasyonu ile hesaplanır. Tüm durum bu iki durumun sonuçlarının toplanması ile bulunur.
