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
**P = 0,6666 > 0.05 olduğu için istatistiksel olarak anlamlı fark yoktur.**

## İş Kararı
İki tasarım arasında anlamlı fark bulunamadığından yeni tasarıma geçiş önerilmez.

## Ek
- `ab_test_sonuc.pdf`
