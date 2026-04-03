[TR]
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
[ENG]
 NBA Player Scoring Analysis: Stratified vs. Simple Random Sampling

This project investigates the efficiency of different sampling methodologies in estimating the average Points Per Game (PPG) for NBA players during the 2023-2024 season.

Methodology
The study compares two primary statistical approaches:
* Stratified Random Sampling (SRS): Players were grouped into 3 natural strata based on their positions (**Guard, Forward, Center**). **Neyman Allocation** was applied to minimize variance by accounting for the higher variability in the Guard stratum.
* Simple Random Sampling (SRS): Used as a baseline to evaluate the relative gain in precision.

Key Statistical Insights
* Sample Size (n): 107 players.
* Variance (Stratified): 0.1943
* Variance (Simple): 0.54
* Conclusion: Stratified sampling yielded a significantly lower variance, proving that accounting for player positions provides a more reliable estimation of league-wide scoring trends.

 Files
* `NBA_Sampling_Report.pdf`: Full academic report including formulas and derivations.
* `Data_Calculations.R`: R scripts used for sampling and variance estimation.

---
**Author:** Büşra Sarı  
*Statistics Student | Hacettepe University*
