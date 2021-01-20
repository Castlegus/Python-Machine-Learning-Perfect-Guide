# 파이썬 머신러닝 완벽 가이드

머신러닝의 바이블 같은 책으로 양대산맥인 '핸즈온 머신러닝'(일명 도마뱀 책)과 비교해보며 고민 끝에 결정한 책입니다.

홀로 공부중이었으나, 마침 활동하고 있는 대학 연합 빅데이터 동아리에서의 교재로 선정되어 정리해가며 공부하려고 합니다.

먼저 인프런에서 저자(권철민님)의 강의를 듣고 Q&A도 참고해가며 필사하면서 공부하고 있습니다. 이후 빅데이터 동아리에서의 커리큘럼이 진행되면 복습하는 식으로 수정/추가/보완할 예정입니다.

-> BITAMIN 폴더에 빅데이터 학회 활동 내용을 정리하고 있습니다.

[빅데이터 대학생 연합 동아리 BITAmin 활동 일지 (작성/제공: 비타민 기획부 김지윤)](https://cafe.naver.com/bitamin123/1685)

## 교재
![파이썬 머신러닝 완벽 가이드](https://user-images.githubusercontent.com/69614150/90767474-3f64f780-e328-11ea-8dc0-74147960f328.jpg)

## 목차 및 참고자료
### 1. 머신러닝 개요 및 사이킷런 소개
- [K-Fold 교차검증](https://velog.io/@skyepodium/K-Fold-%EA%B5%90%EC%B0%A8%EA%B2%80%EC%A6%9D): KFold에서 shuffle=True로 설정하는 것과 StratifiedKFold를 사용하는 것의 차이
- [머신러닝5. 하이퍼파라미터 튜닝 (GridSearchCV, RandomizedSearchCV)](https://blog.naver.com/dalgoon02121/222103377185): RandomizedSearchCV 적용하기

### 2. 머신러닝 평가 방법 및 이론
- [파이썬에서 ROC곡선 쉽게 그리는 방법](https://www.scikit-yb.org/en/latest/api/classifier/rocauc.html): 사이킷런에서는 ROC커브를 그리는 기능을 제공해주지 않는데, yellow brick이라는 패키지를 통해 분류모델에서 ROC커브를 쉽게 그릴 수 있습니다. from yellowbrick.classifier import ROCAUC.

### 3. 머신러닝 분류의 개요와 결정트리

### 4. 분류 모델 (KNN, SVM, 앙상블)

### 5. 앙상블

### 6. 로그변환, 오버샘플링, AutoML, 분류 
- [Pycaret 공식 문서](https://pycaret.readthedocs.io/en/latest/index.html#): 공식 문서가 아주 잘 정리되어 있습니다.

## 기타
- 저자의 강의 [파이썬 머신러닝 완벽 가이드](https://www.inflearn.com/course/%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%99%84%EB%B2%BD%EA%B0%80%EC%9D%B4%EB%93%9C)를 참고하여 공부하고 있습니다.

- [국민대학교 김남규 교수 - 10_데이터과학개론](https://www.youtube.com/playlist?list=PLg_wJlcMiuKvNOT6H0dWEDmMHtfiC8yru): 전반적인 데이터 분석의 프로세스와 머신러닝 알고리즘의 원리를 이해하기 좋은 강의입니다.

- [차원축소 - 주성분분석(PCA)과 요인분석(Factor Analysis)](https://www.youtube.com/playlist?list=PLalb9l0_6WAqC_ytofaE-Q4SPsqgT3EmJ) 파트6 차원축소에서 PCA의 이론적인 설명을 더 공부하기 위해 보충하면 좋을 강의입니다.

- [사이킷런(scikit-learn)으로 학습한 모델 저장하기](https://gaussian37.github.io/ml-sklearn-saving-model/)
