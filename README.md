# 한국외국어대학교 2021년 2학기 기계학습 강의 프로젝트
Machine learning lectures. 2021. </br>
## 두피 상태 분류 프로젝트

### Data
- Link : [AI 허브. 유형별 두피 이미지](https://aihub.or.kr/aidata/30758)
</br> 

### Train
1. [VGG16](https://github.com/younghwani/ScalpProject/blob/master/scalpVGG16.ipynb)
2. [VGG16 Transfer Learning](https://github.com/younghwani/ScalpProject/blob/master/scalpVGG16Transfer.ipynb)
3. [ResNet](https://github.com/younghwani/ScalpProject/blob/master/scalpResnet.ipynb)
4. CreateML
</br>

### Preview (with. CreateML)
- alopecia (탈모)
![alopecia](https://user-images.githubusercontent.com/75962307/146967242-e39a90c9-5292-4032-a23d-0941c16bee9d.png)
탈모 이미지를 분류 -> good(두피 상태 양호), alopecia(탈모) 레이블 반환. </br>
탈모와 동시에 좋은 두피 컨디션을 갖는 경우
</br>

- sebum (피지 과다)
![sebum](https://user-images.githubusercontent.com/75962307/146967439-138c3f1e-1cbe-4c0f-82e4-51dcabc01e63.png)
피지 과다 이미지를 분류 -> sebum(피지 과다), dandruff(비듬) 레이블 반환. </br>
피지가 과다하게 분출되어 있고, 비듬이 존재하는 두피 상태임을 육안으로 확인 가능한 경우
</br>

### 향후 진행방향
- confidence 값을 활용한 알고리즘 사용을 통해 솔루션 제공
