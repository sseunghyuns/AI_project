# AI_project Repository
#### The code records I studied in the AI competition.

---

## classification folder

### 1. dog-vs-cat.ipynb

![catdog](https://user-images.githubusercontent.com/63924704/119216688-1a4c2200-bb10-11eb-9542-177457fb78ce.png)

* 개와 고양이를 분류하는 이미지 분류 대회입니다.
* `EfficientB1` 모델을 사용하였습니다. 옵티마이저는 `Adam`을 사용했습니다.
* `EarlyStopping`, `ReduceLRonPlateau` 적용했습니다.

---

### 2. national-data-science-bowl.ipynb

![bowl_image](https://user-images.githubusercontent.com/63924704/119217005-3b157700-bb12-11eb-80d5-3c3d32d2b5b1.png)

* 121개의 플랑크톤 종을 구분하는 이미지 분류 대회입니다.
* `EfficientB1` 모델을 사용하였습니다. 옵티마이저는 `Adam`을 사용했습니다.
* `EarlyStopping`, `ReduceLRonPlateau` 적용했습니다.
* 5번의 교차검증으로 학습된 5개의 모델을 `soft voting` 했습니다.

---

## detection folder

### 1. vinbigdata-train.ipynb

![vinbigdata-train_11_0](https://user-images.githubusercontent.com/63924704/119217159-31404380-bb13-11eb-8075-86ba0b6b28cc.png)

* Chest X-ray 흉부 데이터에서 기형을 탐지하는 대회입니다.
* `EfficientDet` 모델을 사용하였습니다. 옵티마이저는 `AdamW`을 사용했습니다.
* `ReduceLROnPlateau`을 적용했습니다.

If `"Sorry, something went wrong. Reload?"` sign appears, go to the link below and paste the url.

https://nbviewer.jupyter.org/
