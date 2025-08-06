# Coding Test_CV

## (1) 주제 
- 이미지 데이터 학습을 위한 코드 및 결과물 정리
    - 실험을 위한 모델 코드와 학습 및 평가 코드 작성
    - 실험 결과 작성

## (2) 학습 모델
- ResNet50
- ViT-S/16

## (3) 실험 항목
- ResNet50 w/o pre-trained weights
- ViT-S/16 w/o pre-trained weights
- ResNet50 w/ pre-trained on ImageNet 1k
- ViT-S/16 w/ pre-trained on ImageNet 1k

- (Auxilarily) GradCAM 이용 결과


# Result - Figure

### 1. Metrics 
![image](https://github.com/ceginer/DSBA_coding_test_CV/blob/main/results/metrics_summary_barplot.png?raw=true)

### 2. Acc / Loss

![image](https://github.com/ceginer/DSBA_coding_test_CV/blob/main/results/acc_subplot.png?raw=true)

![image](https://github.com/ceginer/DSBA_coding_test_CV/blob/main/results/loss_subplot.png?raw=true)

### 3. GradCAM
![image](https://github.com/ceginer/DSBA_coding_test_CV/blob/main/gradcam/ResNet50_pretrained_gradcam_multi.png?raw=true)

![image](https://github.com/ceginer/DSBA_coding_test_CV/blob/main/gradcam/ResNet50_scratch_gradcam_multi.png?raw=true)

![image](https://github.com/ceginer/DSBA_coding_test_CV/blob/main/gradcam/ViT-S_pretrained_gradcam_multi.png?raw=true)

![image](https://github.com/ceginer/DSBA_coding_test_CV/blob/main/gradcam/ViT-S_scratch_gradcam_multi.png?raw=true)
