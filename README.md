# 💬 Tweet Duygu Analizi (NLP Projesi)

Bu proje, tweet metinlerini analiz ederek olumlu ya da olumsuz olduklarını tahmin eden bir **doğal dil işleme (NLP)** ve **makine öğrenmesi** projesidir.  
Kaggle üzerinden alınan Sentiment140 veri seti kullanılmıştır.

---

## 🎯 Projenin Amacı

- Tweet metinlerini temizleyip işlemek  
- Metinleri sayısal verilere dönüştürmek (TF-IDF)  
- Lojistik regresyon modeliyle eğitmek  
- Test verisi üzerinde duygu tahmini yapmak  
- Doğruluk, f1-score gibi başarı metriklerini hesaplamak

---

## 📁 Kullanılan Veri Seti

- **Kaynak:** [Sentiment140 - Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)  
- **Veri içeriği:** 1.6 milyon tweet  
- **Kullanılan sütunlar:**
  - `target`: 0 = Negatif, 4 = Pozitif  
  - `text`: Tweet metni

Etiketler ikili sınıflama için 0 (Negatif) ve 1 (Pozitif) olarak yeniden düzenlenmiştir.

---

## 🛠️ Kullanılan Teknolojiler

- Python 3  
- pandas, numpy  
- nltk (doğal dil işleme)  
- scikit-learn (makine öğrenmesi)  
- TfidfVectorizer  
- LogisticRegression

---

## 📊 Örnek Çıktılar
Tweet: "i love this so much!"
Gerçek Duygu: Pozitif
Tahmin: Pozitif ✅

Tweet: "terrible experience, never again."
Gerçek Duygu: Negatif
Tahmin: Pozitif ❌

---

## ▶️ Projeyi Çalıştırmak İçin

1. Gerekli kütüphaneleri kur:
```pip install pandas scikit-learn nltk```
2. training.1600000.processed.noemoticon.csv dosyasını proje klasörüne yerleştir.

3. Python dosyasını ya da Jupyter defterini çalıştır.
