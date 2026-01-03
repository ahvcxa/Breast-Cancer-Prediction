\# Breast Cancer Analysis \& Prediction 🎗️



Bu proje, Meme Kanseri Wisconsin veri setini kullanarak denetimli öğrenme (supervised learning) teknikleriyle analiz ve tahmin yapmayı amaçlamaktadır. Proje kapsamında hem \*\*Regresyon\*\* (tümör yarıçapı tahmini) hem de \*\*Sınıflandırma\*\* (iyi huylu/kötü huylu teşhisi) modelleri geliştirilmiştir.



\## 👥 Proje Ekibi

\* \*\*Batuhan İNAN\*\*

\* \*\*Emir İnanç ŞEKER\*\*



\## 🎯 Proje Hedefleri

1\. \*\*Regresyon:\*\* Fiziksel özelliklere dayanarak tümör yarıçapını (`radius\_mean`) tahmin etmek.

2\. \*\*Sınıflandırma:\*\* Tümörün \*\*Malignant (Kötü Huylu)\*\* veya \*\*Benign (İyi Huylu)\*\* olup olmadığını teşhis etmek.



\## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler

\* \*\*Python\*\*

\* Pandas \& NumPy (Veri Manipülasyonu)

\* Matplotlib \& Seaborn (Veri Görselleştirme)

\* Scikit-learn (Makine Öğrenmesi Modelleri)



\## 📊 Kullanılan Modeller ve Sonuçlar



\### 1. Sınıflandırma (Classification) Sonuçları

Malignant (M) veya Benign (B) tahmini için 3 farklı algoritma karşılaştırılmıştır (5-Fold Cross-Validation ile):



| Model | Başarı Oranı (Accuracy) | Açıklama |

|-------|-------------------------|----------|

| \*\*Logistic Regression\*\* | ~94% | İyi bir temel (baseline) model. |

| \*\*Decision Tree\*\* | ~91% | Yüksek varyans gösterdi. |

| \*\*Random Forest\*\* | \*\*~96%\*\* | \*\*En iyi performans.\*\* Karmaşık özellikleri daha iyi ayırt etti. |



\### 2. Regresyon (Regression) Analizi

\* \*\*Algoritma:\*\* Linear Regression

\* \*\*Hedef:\*\* `radius\_mean` tahmini

\* \*\*Kullanılan Özellikler:\*\* Texture, Smoothness, Compactness, Concavity, Symmetry.



\## 🚀 Kurulum ve Çalıştırma



1\. Projeyi klonlayın:

&nbsp;  ```bash

&nbsp;  git clone \[https://github.com/KULLANICI\_ADIN/Breast-Cancer-Prediction.git](https://github.com/KULLANICI\_ADIN/Breast-Cancer-Prediction.git)

2\. Gerekli kütüphaneleri yükleyin:

Bash

pip install -r requirements.txt

3\. Jupyter Notebook'u çalıştırın:

Bash

jupyter notebook ML_Regression_Classification.ipynb

