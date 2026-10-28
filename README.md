IBM HR Analytics: Çalışan Ayrılma ve Performans Analizi (Employee Attrition)
Bu projede, IBM'in açık kaynaklı HR Analytics veri seti kullanılarak çalışanların şirketten ayrılma (Attrition) nedenleri Microsoft Excel yardımıyla detaylı bir şekilde analiz edilmiş ve görselleştirilmiştir.

🎯 Projenin Amacı
Şirket içi sirkülasyonu (turnover) anlamlandırmak, maliyetleri düşürmek ve çalışan bağlılığını zora sokan kritik faktörleri tespit etmek amacıyla şu 4 temel hipotez incelenmiştir:

Maaş seviyesi işten ayrılma kararında ne kadar etkili?

Fazla mesai (OverTime) çalışan sirkülasyonunu nasıl tetikliyor?

Hangi departmanlarda çalışan ayrılma oranları daha yoğun?

İş tatmini (Job Satisfaction) seviyesi istifa eğilimleriyle nasıl bir ilişki gösteriyor?

🛠️ Kullanılan Araçlar ve Yöntemler
Araç: Microsoft Excel (Veri Temizleme, Pivot Table, Pivot Chart)

Veri Hazırlama: Ham CSV verileri "Veri Al" sihirbazı ve doğru ayırıcılar (virgül) kullanılarak sütunlarına ayrılmış ve analize hazır hale getirilmiştir.

Analiz Yöntemleri: Özet Tablo (Pivot Table) gruplamaları, Ortalama hesaplamaları ve Satır Toplamı Yüzdeleri (% of Row Total).

📈 Temel Bulgular ve İçgörüler
1. Maaş Analizi (Monthly Income vs. Attrition)
Şirkette kalan çalışanların ortalama maaşı ~6.832 $ iken, ayrılanların ortalama maaşı ~4.787 $ seviyesindedir.

İçgörü: Düşük gelir politikasının çalışan sirkülasyonu üzerinde doğrudan ve tetikleyici bir etkisi olduğu kanıtlanmıştır.

2. Fazla Mesai Analizi (OverTime vs. Attrition)
Fazla mesai yapan çalışanların şirketten ayrılma oranlarında belirgin ve yüksek bir artış gözlemlenmiştir.

İçgörü: İş-yaşam dengesinin bozulması, çalışan bağlılığını zayıflatan en büyük operasyonel risklerden biridir.

3. Departman Bazlı Analiz (Department vs. Attrition)
Farklı departmanlardaki ayrılma oranları yüzde kırılımlarıyla incelenmiş, operasyonel yükün yoğun olduğu birimlerde sirkülasyonun arttığı tespit edilmiştir.

4. İş Tatmini Analizi (Job Satisfaction vs. Attrition)
Düşük iş tatmini seviyesine sahip çalışanların istifa eğilimlerinin, tatmin seviyesi yüksek olanlara kıyasla ciddi ölçüde fazla olduğu görselleştirilmiştir.

📁 Proje Dosya Yapısı
Plaintext
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv  # Ham veri seti
├── charts/
│   ├── maas_analizi.png                      # Maaş analizi grafiği
│   ├── fazla_mesai_analizi.png               # Fazla mesai grafiği
│   ├── departman_analizi.png                 # Departman analizi grafiği
│   └── is_tatmini_analizi.png                # İş tatmini analizi grafiği
├── IK_Analiz_Raporu.xlsx                     # Tüm pivot tablo ve grafiklerin yer aldığı Excel dosyası
└── README.md                                 # Proje dokümantasyonu
