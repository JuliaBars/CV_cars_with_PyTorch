
## Stanford Cars Classification using three models
#### 1 вариант ~ 80% точности InceptionV3
-  [ссылка на модель 1](https://github.com/JuliaBars/CV_with_Tensorflow_cats_vs_dogs/blob/main/models/1_CNN.ipynb)
#### 2 вариант ~ 84% точности EfficientNet-b1
- [ссылка на модель 2](https://github.com/JuliaBars/CV_with_Tensorflow_cats_vs_dogs/blob/main/models/2_CNN_data_augmentation.ipynb)
#### 3 вариант ~ 94.79% точности EfficientNet-b7 with Mish and Ranger
- [ссылка на модель 3](https://www.kaggle.com/code/ikhushpatel/ignite-car-classification-ikhushpatel-khush/notebook)

---
---
Все модели взяты из репозиториев других разработчиков. Ссылки на репозитории в описании каждой модели.

---

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)

---
#### 1 модель:
Author : Khush Patel (@Khush)
Model : InceptionV3
Ephoch : 75
Loss : CrossEntropyLoss
Criterion : SGD
#### Модель Khush Patel на Kaggle [ссылка](https://www.kaggle.com/code/ikhushpatel/ignite-car-classification-ikhushpatel-khush/notebook)

---
#### 2 модель:
Author: Sovit Ranjan RathSovit
Model: EfficientNet-b1
Epochs: 50
Loss: CrossEntropyLoss
Optimizer: Adam

#### Статья автора с исходным кодом [Sovit Ranjan RathSovit](https://debuggercafe.com/stanford-cars-classification-using-efficientnet-pytorch/)

---

### 3 модель:
Author: Morgan McGuire
Model: EfficientNet-b7 with Mish and Ranger
Epochs: 40
Loss: LabelSmoothingCrossEntropy
Optimizer: a combination of RAdam and Lookahead

#### Репозиторий автора [morganmcg1](https://github.com/morganmcg1/stanford-cars/blob/master/10_stanford_cars_EfficientNet_b7_Ranger_Mish_Trial.ipynb)