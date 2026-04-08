# Döviz Volatilite Analizi

Bu projede USD baz alınarak EUR, GBP, JPY ve TRY para birimlerinin performansı ve volatilitesi analiz edilmiştir.

---

## 📊 Proje Özeti

- Veri Kaynağı: Frankfurter API  
- Baz Para Birimi: USD  
- Zaman Aralığı: Ocak 2024  

Analiz iki ana başlıkta yapılmıştır:

1. Zaman içerisindeki performans  
2. Günlük dalgalanma (volatilite)

---

## ⚙️ Kullanılan Teknolojiler

- Python  
- Pandas  
- Matplotlib  
- Requests (API üzerinden veri çekme)  
- REST API (Frankfurter API)

---

## 📈 Analizler

### 1. Performans Analizi (Endekslenmiş)

Her para birimi başlangıçta 100 kabul edilerek karşılaştırılmıştır.

- 100 üzeri → USD karşısında değer kazanımı  
- 100 altı → USD karşısında değer kaybı  

Bu yöntem trendi daha net görmeyi sağlar.

---

### 2. Volatilite Analizi

Volatilite, günlük yüzdesel değişimlerin standart sapması ile hesaplanmıştır.

- Yüksek değer → daha fazla dalgalanma (risk)  
- Düşük değer → daha stabil hareket  

---

## 🔍 Öne Çıkan Bulgular

- GBP ve EUR daha yüksek volatiliteye sahip  
- JPY orta seviyede dalgalanma gösteriyor  
- TRY bu dönemde daha stabil bir yapı sergiliyor  

Not:  
Trend (yükseliş/düşüş) ile volatilite (dalgalanma) farklı kavramlardır.

---

## 📂 Proje Dosyası

- `currency_volatility_analysis.ipynb` → Tüm analiz süreci ve grafikler
