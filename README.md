# agricultural-water-footprint-analysis

# 💧 Agricultural Water Footprint Analysis (Suyun Bilinçli Tüketimi)

Bu proje, "Gelecek Hayalim" programı kapsamında tarımsal ürünlerin su ayak izini analiz etmek ve su kaynaklarının daha verimli kullanılmasına yönelik stratejiler geliştirmek amacıyla hazırlanmıştır.

## 📌 Proje Amacı
Tarımda su tüketimini etkileyen faktörleri (mahsul türü, sulama tipi, iklim koşulları) belirlemek ve veriye dayalı tasarruf önerileri (örn: damla sulama, malçlama) sunmaktır. 

## 🛠️ Kullanılan Teknolojiler
* **Dil:** Python
* **Kütüphaneler:** Pandas, Matplotlib, Seaborn
* **Ortam:** Google Colab / Jupyter Notebook

## 📊 Veri Seti Hakkında
Projede kullanılan `agricultural_water_footprint.csv` veri seti; mahsullerin su kullanımı, sulama türleri, iklim koşulları ve verim gibi metrikleri içeren kapsamlı bir kaynaktır. Analiz öncesi veri temizleme adımları uygulanmış ve eksik veriler işlenmiştir.

## 💡 Temel Çıkarımlar ve Analiz Sonuçları
* **Ürün Bazlı Su Tüketimi:** Bezelye (Peas) ve Brokoli gibi ürünler en yüksek su tüketimine (~14.000 m³/kg) sahipken, Üzüm (Grapes) ve Biber gibi ürünler çok daha düşük su ayak izine sahiptir.
* **Sulama Yöntemlerinin Etkisi:** Damla (Drip) sulama en düşük su kullanımını sağlarken, Vahşi (Flood) sulama su tüketimini neredeyse iki katına çıkarmaktadır (Örn: Patates).
* **İklim Faktörü:** Kurak (Arid) iklimlerde toplam su kullanımı, mavi su bağımlılığının artması sebebiyle zirveye ulaşmaktadır (~10.000 m³/kg).
* **Su Tasarrufu Pratikleri:** Etkili sulama (Efficient Irrigation) ve mahsul örtüsü (Crop Cover) gibi yöntemler su tüketimini %20-30 oranında azaltabilmektedir.

## 🚀 Öneriler
1. Çiftçilerin damla sulama sistemlerine geçişi için eğitim ve teşvik programları düzenlenmeli.
2. Tüketiciler, düşük su ayak izine sahip mahsullere yönlendirilmeli.
3. Özellikle kurak bölgelerde stratejik su kullanım politikaları ve kısıtlamaları uygulanmalı.

## ⚙️ Nasıl Çalıştırılır?
1. Repoyu bilgisayarınıza klonlayın: `git clone https://github.com/zozbe/agricultural-water-footprint-analysis.git`
2. Gerekli kütüphaneleri yükleyin: `pip install pandas matplotlib seaborn`
3. `water_footprint_analysis.ipynb` dosyasını Jupyter Notebook veya VS Code üzerinden çalıştırın.
