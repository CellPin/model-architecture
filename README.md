# Model-Architecture

#### base_model : 논문에 나온 모델, weight는 없음.
#### base_model_pretraining : 논문에 나온 모델, weight는 논문 가중치.
#### 0816_influ_filter_model_1 : 논문에서 사용한 모델과 가중치.
#### vgg19 : vgg19 모델, weight는 없음.
#### vgg19_imagenet : vgg19 모델, weight는 imagenet.
#### resnet152 : resnet152V2 모델, weight는 없음.
#### resnet152_imagenet :resnet152V2 모델, weight는 imagenet.
#### dense201 : densenet201 모델, weight는 없음.
#### dense201_imagenet : densenet201 모델, weight는 imagenet.
#### Result :  위의 파일을 실행해본 결과물 (label이 이상해서 Accuracy, Precision, Recall이 다 같게 나오는 현상을 발견함)
#### Final_Result : 위의 문제를 개선하여 실행을 시킨 결과물 -> 100MB 용량 제한으로 h5파일은 올리지 못함.
