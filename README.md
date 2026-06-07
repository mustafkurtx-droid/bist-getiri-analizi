#  BIST Hisse Getiri Analizi (2020-2024)

##  Proje Hakkında
yfinance kütüphanesi ile çekilen 28 BIST hissesinin 2020-2024 yılları arasındaki
fiyat verisi kullanılarak risk-getiri analizi yapılmıştır.

##  Yapılan Analizler
- Yıllık getiri ve volatilite hesaplama
- Sharpe oranı ile risk/getiri dengesi
- Hisseler arası korelasyon matrisi
- Kümülatif getiri karşılaştırması

## 🏆 Öne Çıkan Bulgular
- En iyi Sharpe oranı: BIMAS (1.29) — düşük risk, istikrarlı getiri
- En yüksek getiri: SASA (%65.83) — yüksek volatilite ile birlikte
- En düşük getiri: HALKB (%19.72)
- Banka hisseleri arasında yüksek korelasyon tespit edildi (0.85+)
- BIMAS + THYAO + ASELS + FROTO kombinasyonu ideal çeşitlendirme sağlar

## 🛠️ Kullanılan Teknolojiler
| Kütüphane | Amaç |
|-----------|------|
| `yfinance` | Hisse verisi çekme |
| `pandas` | Veri manipülasyonu |
| `numpy` | Matematiksel hesaplamalar |
| `matplotlib` | Grafik oluşturma |
| `seaborn` | Korelasyon heatmap |

##  Dosya Yapısı
bist-getiri-analizi/
│
├── Proje.ipynb              # Ana analiz notebook'u
├── bist_risk_getiri.png     # Risk/Getiri scatter grafiği
├── bist_korelasyon.png      # Korelasyon matrisi
└── bist_getiri_analiz.png   # Kümülatif getiri grafiği

## ⚙️ Kurulum & Çalıştırma
```bash
pip install yfinance pandas numpy matplotlib seaborn
jupyter notebook Proje.ipynb
```

Yazar
Mustafa Kurt-Dokuz Eylül Üniversitesi  
