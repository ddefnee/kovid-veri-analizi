# COVID-19 Veri Analizi

Python (Jupyter Notebook) ile hazırlanmış, dünya genelinde COVID-19 yayılımını
inceleyen bir **veri analizi ve görselleştirme** projesi. 22 Ocak 2020 – 27 Temmuz 2020
arası veriler kullanılmıştır.

## 📊 Analiz İçeriği

- Veri setinin temizlenmesi ve 187 ülke / 78 vilayet bazında inceleme
- **Plotly** ile dünya çapında yayılma, aktif vaka, iyileşen ve ölüm haritaları
- **Seaborn / Matplotlib** ile zaman içinde onaylanan vaka grafikleri
- En çok vaka/aktif vaka/ölüm/iyileşme görülen **ilk 20 ülke** sıralamaları
- En kötü ölüm oranına / en iyi iyileşme oranına sahip ülkeler
- Odaklı ülke karşılaştırması: **Çin, ABD, İtalya ve Türkiye**
- Her görselleştirmenin altında yazılı gözlem/yorum notları

## 🛠️ Teknoloji

- Python — pandas, numpy, matplotlib, seaborn, plotly

## 📁 İçerik

```
220710017_220710071.ipynb   # Analiz not defteri (ana dosya)
220710017_220710071.docx    # Proje raporu
covid_19_clean_complete.csv # Veri seti (Kaggle - "COVID-19 Clean Complete Dataset")
annotations/                # COVID-19 akciğer görüntüsü sınırlayıcı kutu (bounding box)
                             # ek veri seti (ieee8023/covid-chestxray-dataset, kaynak atıflı)
```

## 👥 Hazırlayanlar

Hasret Güler (220710017) — Defne Gödelekoğlu (220710071)

## 🚀 Çalıştırma

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
jupyter notebook 220710017_220710071.ipynb
```
