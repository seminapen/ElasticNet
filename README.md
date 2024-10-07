# ElasticNet

Bu veri seti Kaggle yarışmasında kullanılmış ve 1.115 Rossmann mağazası için geçmiş satış veri kullaılmıştır.

Projede ElasticNet modeli kullanılmış ve satış tahmini yapılmıştır. 

Veri temizleme ve ön işleme: Eksik değerlerin doldurulması, tarih sütununun dönüştürülmesi, one-hot encoding.

Özellik ölçekleme: StandardScaler ile özelliklerin ölçeklenmesi.

Hiperparametre optimizasyonu: GridSearchCV kullanılarak en iyi alpha ve l1_ratio değerlerinin bulunması.

Model performansı: R² ve Mean Squared Error (MSE) metrikleri kullanılarak değerlendirme.

Test veri setindeki mağazaların satışlarını tahmin ettikten sonra sonuçları predictions.csv dosyasına kaydedilir.

Modelin doğruluğu MSE (Mean Squared Error), R² skoru kullanılarak ölçülmüştür.
