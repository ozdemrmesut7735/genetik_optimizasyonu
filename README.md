Ad: Mesut
Soyad: Özdemir
Okul Numarası: 2312721053

Bu projede, bir lojistik firmasının nakliye rotasında yakıt tüketimi ve zaman dengesini sağlamak amacıyla kısıtlı bir optimizasyon problemi ele alınmış ve çözümde Genetik Algoritma (GA) kullanılmıştır. 

Amaç fonksiyonu:
( y = -2x_1 - 3x_2 + 0.1x_1x_2 )
şeklinde tanımlanmış olup, negatif toplam maliyetin maksimize edilmesi hedeflenmiştir. 

Burada (x_1) ortalama hızı (km/s), 
(x_2) ise araç yük kapasitesini (ton) ifade etmektedir. 

Değişkenler için (40 ≤ x_1 ≤ 100) ve (2 ≤ x_2 ≤ 10) aralıkları belirlenmiştir.

Probleme motor gücü limiti (x_1 . x_2 ≤ 700) ve minimum hız şartı (x_1 ≥ 60) olmak üzere iki kısıt eklenmiştir. 
Problemin doğrusal olmaması ve bu kısıtları içermesi nedeniyle çözüm yöntemi olarak Genetik Algoritma tercih edilmiştir.

Algoritmada karar değişkenleri reel sayılarla ifade edilmiş, ebeveyn seçimi aşamasında Rulet Tekerleği yöntemi kullanılmıştır. 
Yeni çözümler üretmek için aritmetik çaprazlama, popülasyon çeşitliliğini korumak için mutasyon operatörü uygulanmıştır. 
Kısıtlar ceza fonksiyonu ile uygunluk fonksiyonuna entegre edilmiş, en iyi çözümün korunması için elitizm yöntemi kullanılmıştır.

Algoritmada 
popülasyon büyüklüğü 50, 
nesil sayısı 100, 
çaprazlama oranı 0.8,
mutasyon oranı 0.1 olarak belirlenmiştir. 

Genetik Algoritma, verilen kısıtlar altında optimum hız ve yük dengesini başarıyla bulmuş, algoritmanın yakınsama davranışı nesillere göre en iyi uygunluk değerlerinin grafiği ile gösterilmiştir.

Kurulum ve Çalıştırma : Bu proje Python dili ile geliştirilmiştir ve Google Colab üzerinde çalışmaya uygundur.

1 .ipynb uzantılı proje dosyasını Google Colab ortamına yükleyin.

2. Kod hücrelerini sırasıyla çalıştırın.

3. Gerekli kütüphaneler (random, matplotlib, numpy) kod içerisinde otomatik tanımlıdır, ekstra kurulum gerektirmez.
