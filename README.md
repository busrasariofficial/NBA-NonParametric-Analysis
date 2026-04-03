 NBA Oyuncu Performanslarının Parametrik Olmayan İstatistiksel Yöntemlerle İncelenmesi

Bu proje, NBA'de forma giyen oyuncuların (Alperen Şengün, Furkan Korkmaz vb.) ve takımların performans verilerini, verilerin normal dağılım varsayımını karşılamadığı durumlarda kullanılan Parametrik Olmayan (Non-Parametric) testlerle analiz eder.

 Araştırma Soruları ve Kapsam
Çalışma kapsamında aşağıdaki istatistiksel sorulara yanıt aranmıştır:
* Konum Testleri: Alperen Şengün'ün sayı krallığındaki konumu medyan değerler üzerinden nasıl değişiyor? (Wilcoxon, Sign Test)
* Grup Karşılaştırmaları: Oyuncuların performansları arasında istatistiksel olarak anlamlı bir fark var mı? (Mann-Whitney U, Kruskal-Wallis)
* Eğilim Analizi: Boston Celtics gibi takımların kazanma sayılarında zaman içinde anlamlı bir trend var mı? (Mann-Kendall Eğilim Testi)

 Kullanılan Yöntemler
Veri setinin normallik testleri (Shapiro-Wilk) yapılmış ve parametrik testlerin (T-testi, ANOVA) varsayımları sağlanmadığı için şu yöntemler uygulanmıştır:
* Tek Örneklem Testleri: İşaret Testi (Sign Test), Wilcoxon İşaretli Sıralar Testi.
* Bağımsız Gruplar: Mann-Whitney U Testi.
* K-Örneklem: Kruskal-Wallis Testi.
* Trend Analizi: Mann-Kendall Testi (Özellikle galibiyet sayıları analizi için).

#Öne Çıkan Bulgular
* Alperen Şengün Analizi:Oyuncunun belirli bir skor barajını aşma eğilimi istatistiksel olarak test edilmiştir.
* Trend Analizi: Boston Celtics'in son 10 sezondaki galibiyet sayılarında negatif bir Tau katsayısı ($\tau = -0.48$) gözlenmiş, ancak bu eğilim $p=0.0509$ değeri ile sınırda kalarak istatistiksel olarak anlamlı bulunmamıştır.

 Dosyalar
* [Akademik Rapor (PDF)](./NBA%20OYUNCU%20PERFORMANSLARININ%20PARAMETRIK%20OLMAYAN%20YÖNTEMLERLE%20İNCELENMESI.pdf) - Detaylı test sonuçları, SPSS çıktıları ve yorumlar.

---
Hazırlayan: Büşra Sarı  
Hacettepe Üniversitesi - İstatistik Bölümü
