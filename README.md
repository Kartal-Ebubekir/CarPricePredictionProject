# Araba Fiyat Tahmin Projesi (TR)

Bu proje, çeşitli araba özelliklerini kullanarak ikinci el araba fiyatlarını tahmin etmeyi amaçlayan bir makine öğrenmesi modelini içermektedir. Proje kapsamında veri temizleme, keşifsel veri analizi (EDA) ve özellik mühendisliği adımları uygulanmıştır. Fiyat tahmini için Lineer Regresyon ve Ridge Regresyon modelleri karşılaştırılmış, en iyi performansı gösteren model `GridSearchCV` ile optimize edilmiştir.

Veri seti kaggle'dan alınmıştır.[Veri setine ulasmak için tıklayınız.](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
## Sonuç

Modelleme sonucunda, Ridge Regresyon modelinin test verilerinde daha düşük hata oranı (MSE) ve daha yüksek R² skoru ile daha iyi bir performans sergilediği görülmüştür.


## Gereksinimler (Requirements)

Projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:
- pandas numpy seaborn matplotlib scikit-learn

## Kullanım (Usage)

1.  Bu repoyu klonlayın veya indirin.
2.  `CarPrice_Assignment.csv` veri setinin notebook ile aynı dizinde olduğundan emin olun.
3.  `CarPricePredictionProject.ipynb` dosyasını bir Jupyter ortamında (Jupyter Notebook, VS Code vb.) açarak kodları çalıştırın.


---

# Car Price Prediction Project (EN)

This project includes a machine learning model aimed at predicting used car prices using various car features. Within the scope of the project, data cleaning, exploratory data analysis (EDA), and feature engineering steps were applied. For price prediction, Linear Regression and Ridge Regression models were compared, and the best-performing model was optimized using `GridSearchCV`.

The dataset was taken from Kaggle. [Click to access the dataset.](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
## Result

As a result of the modeling, it was observed that the Ridge Regression model performed better on the test data with a lower error rate (MSE) and a higher R² score.

## Requirements

To run the project, the following libraries must be installed:
- pandas numpy seaborn matplotlib scikit-learn

## Usage

1.  Clone or download this repo.
2.  Ensure the `CarPrice_Assignment.csv` dataset is in the same directory as the notebook.
3.  Open the `CarPricePredictionProject.ipynb` file in a Jupyter environment (Jupyter Notebook, VS Code, etc.) and run the code.

## İletişim / Contact

Ebubekir Kartal
- [GitHub](https://github.com/Kartal-Ebubekir)
- [LinkedIn](https://www.linkedin.com/in/ebubekir-kartal-645091335/)
- [Kaggle](https://www.kaggle.com/ebubekirkartal443)
