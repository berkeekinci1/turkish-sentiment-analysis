# Türkçe Mağaza Yorumları Üzerine Duygu Analizi

Bu proje, Türkçe müşteri yorumlarını **olumlu / olumsuz / nötr** olarak sınıflandırmak için hazırlandı.  
Metinler üzerinde TF-IDF tabanlı bir vektörleştirme yapılıyor ve birkaç farklı makine öğrenmesi modeli deneniyor.  

## Kullanılan Modeller
- Naive Bayes  
- Lojistik Regresyon  
- Destek Vektör Makineleri (SVM)  
- Random Forest (büyük boyutlu, repoya eklenmedi)  
- Multi-Layer Perceptron (MLP, repoya eklenmedi)  

Not: Random Forest ve MLP modelleri boyut kısıtlaması nedeniyle repoya eklenmedi, fakat kod içinde yeniden eğitilebilirler.

## Dosyalar
- `turkish-sentiment-analysis.py` → Ana Python kodu  
- `magaza_yorumlari_duygu_analizi.csv` → Yorum datası  
- `NaiveBayes.pkl`, `LogReg.pkl`, `SVM.pkl` → Küçük boyutlu kaydedilmiş modeller  
- `tfidf.pkl` → Vektörizer dosyası  
