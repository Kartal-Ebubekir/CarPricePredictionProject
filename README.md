# Araba Fiyat Tahmin Projesi

Bu proje, çeşitli araba özelliklerini kullanarak ikinci el araba fiyatlarını tahmin etmeyi amaçlayan bir makine öğrenmesi modelini içermektedir. Proje kapsamında veri temizleme, keşifsel veri analizi (EDA) ve özellik mühendisliği adımları uygulanmıştır. Fiyat tahmini için Lineer Regresyon ve Ridge Regresyon modelleri karşılaştırılmış, en iyi performansı gösteren model `GridSearchCV` ile optimize edilmiştir.

## Sonuç

Modelleme sonucunda, Ridge Regresyon modelinin test verilerinde daha düşük hata oranı (MSE) ve daha yüksek R² skoru ile daha iyi bir performans sergilediği görülmüştür.


## Gereksinimler (Requirements)

Projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:

```
pandas
numpy
seaborn
matplotlib
scikit-learn
```


## Kullanım (Usage)

1.  Bu repoyu klonlayın veya indirin.
2.  `CarPrice_Assignment.csv` veri setinin notebook ile aynı dizinde olduğundan emin olun.
3.  `CarPricePredictionProject.ipynb` dosyasını bir Jupyter ortamında (Jupyter Notebook, VS Code vb.) açarak kodları çalıştırın.

## İletişim

Ebubekir Kartal
- [GitHub](https://github.com/Kartal-Ebubekir)
- [LinkedIn](https://www.linkedin.com/in/ebubekir-kartal-645091335/)
