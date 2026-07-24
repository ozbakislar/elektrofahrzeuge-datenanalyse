# 📖 **Dil:** [English](README_EN.md) | [Deutsch](README.md) | **Türkçe**

# 📊 Elektrikli Araçlar – Keşifsel Veri Analizi

2020-2026 yılları arasındaki elektrikli araç modellerinin teknik ve ticari performans verilerinin Keşifsel Veri Analizi (EDA)

## 📋 Proje Hakkında

Küresel elektrikli araç pazarının kapsamlı analizi:

* Teknik performans verileri (fiyat, batarya kapasitesi, menzil, motor gücü)
* Kategorik pazar yapısı (marka, kasa tipi, çekiş tipi, pazar segmenti)
* Teknik ve ticari göstergeler arasındaki ilişkiler
* Marka karşılaştırmaları ve satış analizi
* Küresel elektrikli araç pazarı için iş içgörüleri

## 📦 Veri Seti

**Veri Kaynağı:** [EV Market Analytics - Kaggle](https://www.kaggle.com/code/lukhilaksh/ev-market-analytics-76-beats)

Her satırın bir markanın belirli bir yıl ve varyanttaki (base, standard, long range, premium, performance) modelini temsil ettiği, 24 sütunlu **2.000 gözlem**

**Menşei Ülkeye Göre Markalar:**

* **Almanya:** Audi, BMW, Mercedes, Porsche, Volkswagen
* **ABD:** Fisker, Ford, GM/Chevrolet, Lucid, Rivian, Tesla
* **Japonya:** Honda, Toyota
* **Güney Kore:** Hyundai, Kia
* **Çin:** BYD, NIO, Xiaomi
* **İsveç:** Polestar, Volvo

**Temel Göstergeler:** Fiyat (USD), Batarya Kapasitesi (kWh), Menzil (mil), Motor Gücü (hp), Çekiş Tipi, Kasa Tipi, Pazar Segmenti, Yıllık Satış Adedi, Müşteri Puanı

## 🔍 Ana Bulgular

### 📈 Temel İş İçgörüleri

✅ **Batarya kapasitesi** ile **araç menzili** arasında çok güçlü pozitif bir ilişki bulunuyor (r = 0,978)  
✅ **Motor gücü**, **araç fiyatını** batarya kapasitesinden (r = 0,164) daha güçlü etkiliyor (r = 0,765)  
✅ **Menzili daha uzun** araçlar, kullanıcılardan daha yüksek müşteri puanı alma eğiliminde (r = 0,668)  
✅ **Lucid, Porsche, Mercedes** fiyat seviyesinde önde; **Volkswagen, Tesla, BYD** satış hacminde önde  
✅ **Luxury** segmenti en yüksek ortalama fiyata sahipken, **Budget** segmenti en yüksek ortalama satışı gösteriyor  
✅ Fiyat, güç ve puandaki uç değerler büyük ölçüde **premium ve yüksek performanslı araçlardan** kaynaklanıyor ve veri hatası olarak değerlendirilmedi  

**Temel Çıkarım:** Yüksek fiyat otomatik olarak yüksek satış anlamına gelmiyor. Elektrikli araç pazarında fiyatı, satış performansını ve müşteri memnuniyetini teknik özellikler, marka konumlandırması ve pazar segmenti birlikte belirliyor.

## 🛠️ Teknolojiler

• Python • NumPy • Pandas • Matplotlib • Seaborn • Jupyter Notebook

## 📧 İletişim

**Süha Çağrı Özbakışlar**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ozbakislar)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://www.github.com/ozbakislar)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/ozbakislar)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/ozbakislar)
