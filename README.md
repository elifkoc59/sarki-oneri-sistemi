# sarki-oneri-sistemi
Şarkı sözlerine dayalı öneri sistemi (Doğal Dil İşleme Ödevi)

# 🎵 Şarkı Öneri Sistemi

Bu proje, **Doğal Dil İşleme** (NLP) dersi kapsamında geliştirilmiş bir şarkı öneri sistemidir.  
Projenin amacı, şarkı adları üzerinden öneriler yapabilen bir yapay zekâ modelini metin tabanlı veri kullanarak geliştirmektir.

## 📂 Proje Yapısı
sarki-oneri-sistemi/
├── data/
│ ├── cleaned_lemmatized.csv
│ └── cleaned_stemmed.csv
├── tfidf/
│ ├── tfidf_lemmatized.csv
│ └── tfidf_stemmed.csv
├── models/
│ ├── (Word2Vec model dosyaları)
├── notebook/
│ └── sarkionerisistemi.ipynb
├── README.md
└── requirements.txt


## ⚙️ Kurulum

```bash
pip install -r requirements.txt
Nasıl Çalıştırılır
notebook/sarkionerisistemi.ipynb dosyasını açın.

Adımları takip ederek:

Veriyi yükleyin

Temizleyin (stopword removal, stemming/lemmatization)

TF-IDF ve Word2Vec uygulayın

Benzer şarkıları önerin

Model çıktıları data/, tfidf/, models/ klasörlerinde yer alır.

📚 Kullanılan Veri Seti
Kaggle - 380,000+ Lyrics from MetroLyrics

Format: CSV, İngilizce şarkı sözleri

Kullanım amacı: Şarkı sözlerinden öneri yapılması

🧪 Kullanılan Kütüphaneler
pandas

nltk

gensim

matplotlib

scikit-learn

spacy

