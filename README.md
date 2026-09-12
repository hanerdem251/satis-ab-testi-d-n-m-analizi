# E-Ticaret A/B Testi - Dönüşüm Oranı Analizi

## Veri Seti
- **A Grubu - Eski Tasarım**: 699.974 kullanıcı, 105.626 satın alma
- **B Grubu - Yeni Tasarım**: 300.026 kullanıcı, 45.173 satın alma
- **Toplam**: 1.000.000 kullanıcı, 150.799 satın alma

## İstatistiksel Test Sonuçları
- **A Dönüşüm Oranı**: %15,09
- **B Dönüşüm Oranı**: %15,06
- **Gözlenen Fark**: %0,03
- **Kullanılan Test**: 2 Oranlı Z Testi
- **Anlamlılık Seviyesi**: α = 0.05
- **P DEĞERİ**: 0,6666

## Sonuç
$p = 0.6666 > 0.05$  olduğu için A ve B gruplarının dönüşüm oranları arasında 'İstatistiksel' olarak anlamlı bir fark yoktur.


## İş Kararı
Yeni tasarımın (B grubu) dönüşüm oranında anlamlı bir artış sağlanmadığı tespit edilmiştir. Geliştirme, uygulama ve olası risk maliyetleri göz önüne alınarak
yeni Tasarıma geçiş önerilmez ; mevcut tasarım (A grubu) ile devam edilmelidir.

- `ab_test_sonuc.pdf`
