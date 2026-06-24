# final-dev-2.-b-t # Word2Vec Metin Benzerliği ve Analiz Projesi

Bu proje, Doğal Dil İşleme (NLP) dersi kapsamında; `lemmatized` ve `stemmed` veri setleri üzerinde 16 farklı Word2Vec modelinin eğitilmesi, karşılaştırılması ve metin benzerliklerinin analiz edilmesi amacıyla geliştirilmiştir.

## Proje İçeriği
- **Veri Ön İşleme:** Metin temizleme, lemmatization ve stemming süreçleri.
- **Model Eğitimi:** Gensim kütüphanesi kullanılarak 16 farklı konfigürasyonda (CBOW ve Skip-gram) Word2Vec modellerinin eğitimi.
- **Benzerlik Analizi:** Kosinüs Benzerliği (Cosine Similarity) ile metin benzerliklerinin hesaplanması.
- **Doğrulama:** Jaccard Katsayısı kullanılarak modellerin sıralama tutarlılığının ısı haritası (Heatmap) ile görselleştirilmesi.

## Kullanılan Teknolojiler
- Python 3.14
- Pandas, NumPy
- Scikit-learn, Gensim
- Seaborn, Matplotlib

## Dosya Yapısı
- `Untitled8.ipynb`: Projenin tüm kodlarını ve analiz süreçlerini içeren Jupyter Notebook.
- `objective_evaluation.csv`: Kosinüs benzerliği sonuçlarını içeren tablo.
- `jaccard_heatmap.png`: Modellerin sıralama tutarlılığını gösteren görsel.
- `Final_Raporu.pdf`: Projenin detaylı akademik değerlendirmesini içeren rapor.

## Kurulum ve Çalıştırma
Projeyi çalıştırmak için gerekli kütüphaneleri şu komutla yükleyebilirsiniz:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn gensim
