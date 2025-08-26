# 🛒 E-Commerce Sales Analysis

Bu proje, bir e-ticaret satış verisi üzerinde **uçtan uca veri analizi** yapmayı amaçlamaktadır.  
Hem **MSSQL** hem de **Python** kullanılarak veri temizleme, ETL, analiz ve müşteri segmentasyonu (RFM) çalışmaları gerçekleştirilmiştir.

---

## 🎯 Proje Amacı

- Satışların zaman içindeki değişimini incelemek
- En çok satan ürünleri ve ülke bazlı satış performansını analiz etmek
- Müşteri davranışlarını RFM yöntemi ile segmentlere ayırmak
- İş kararlarını destekleyecek somut içgörüler üretmek

---

## 📂 Veri Seti

- **Dosya:** `ecommerce_data.csv`
- **Özellikler:**
  - `InvoiceNo`: Fatura numarası
  - `StockCode`: Ürün kodu
  - `Description`: Ürün açıklaması
  - `Quantity`: Satış adedi
  - `InvoiceDate`: Satış tarihi
  - `UnitPrice`: Birim fiyat
  - `CustomerID`: Müşteri kimliği
  - `Country`: Ülke

---

## 🛠️ Kullanılan Teknolojiler

- **SQL (MSSQL)**: Veri temizleme, ETL, view oluşturma, performans analizleri
- **Python**: pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook**: Veri keşfi, görselleştirme, RFM segmentasyonu

---

## 🔍 SQL Çalışmaları

- **ETL Süreci:**
  - `stg_sales` → `sales` tablosuna veri aktarımı
  - Hesaplanan alanlar: `IsReturn`, `TotalAmount`
- **View’ler:**
  - `vw_daily_revenue`: Günlük ciro raporu
  - `vw_rfm_base`: RFM analizi için müşteri tablosu
- **Analizler:**
  - Aylık ciro (iadesiz)
  - En çok satan ürünler
  - Ülke bazlı performans

---

## 📊 Python Çalışmaları

- Veri temizleme ve EDA
- Zaman serisi analizi (günlük ve aylık satış trendleri)
- En çok satan ürünlerin analizi
- RFM segmentasyonu:
  - Sadık Müşteriler
  - Riskteki Müşteriler
  - Kaybedilmiş Müşteriler
  - Yeni Müşteriler
- Görselleştirmeler: Line chart, bar chart, pie chart

---

## 📈 Öne Çıkan Bulgular

- **UK**, toplam cironun %85’ine sahip → en güçlü pazar
- Satışlarda **mevsimsellik** gözlemlendi → özellikle yıl sonu artışlar dikkat çekici
- **Promosyon ürünleri**, en çok satanlar arasında baskın çıktı
- RFM analizi ile müşteriler segmentlere ayrıldı → CRM stratejileri için kullanılabilir

---

## 🔮 Gelecek Çalışmalar

- Zaman serisi verileri ile **satış tahminleme (forecasting)**
- Müşteri segmentlerine yönelik **öneri sistemleri**
- Makine öğrenmesi ile **müşteri davranışı modelleme**

## Proje ile ilgili görseller

![](/görseller/sql1.png)
![](/görseller/sql2.png)
![](/görseller/sql3.png)
![](/görseller/notebook1.png)
![](/görseller/notebook2.png)
![](/görseller/notebook3.png)
![](/görseller/notebook4.png)
![](/görseller/notebook5.png)
![](/görseller/notebook6.png)
![](/görseller/notebook7.png)
![](/görseller/notebook8.png)
