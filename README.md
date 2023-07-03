# ML2_project
3학년 2학기 머신러닝2 수업에서 진행한 최종 프로젝트로, ResNet 모델을 구현하여 이미지 예측의 정확도를 올리고자 하였다.

## Data
CIFAR10

## Model
'Deep Residual Learning for Image Recognition' 논문을 참고하여 44개의 layer로 구성되어 있는 ResNet44를 구현하였다.
### 정확도를 높이기 위해...
CNN 모델로 CIFAR10 dataset을 훈력시켰을 때, 최종 정확도는 약 63%로 그렇게 높지 않은 정확도를 보여주었다.

1. Data Normalization
2. Data Augmentation
3. Hyperparameter Tuning
4. ResNet44로 모델 변경

위의 방법으로 모델을 구현한 결과 최종 정확도가 약 87%까지 올라간 것을 확인할 수 있었다.
