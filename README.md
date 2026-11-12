# 빅데이터분석 02분반 - [과제3] 특성 공학(Feature Engineering) 파이프라인 구현 및 성능 비교 실험

## 데이터셋 다운로드

본 프로젝트에서는 Kaggle의 **Titanic - Machine Learning from Disaster** 데이터셋을 사용하였습니다.

- 데이터 출처: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- 사용 파일: `train.csv`
- 데이터 크기: 891행 × 12열
- 타겟 변수: `Survived` (0: 사망, 1: 생존)

### 다운로드 방법

1. 위 Kaggle 데이터셋 링크에 접속합니다.
2. Kaggle 계정으로 로그인합니다.
3. **Data** 페이지에서 **Download All → Download as zip**을 선택합니다.
4. 다운로드한 ZIP 파일의 압축을 해제합니다.
5. 압축 해제 후 `train.csv` 파일을 준비합니다.

### Google Colab 실행 방법

1. `feature_engineering_assignment.ipynb` 파일을 Google Colab에서 엽니다.
2. 첫 번째 코드 셀을 실행합니다.
3. 파일 업로드 창이 나타나면 다운로드한 `train.csv`를 선택합니다.
4. 이후 코드 셀을 순서대로 실행하면 데이터 분석 및 머신러닝 실험 결과를 확인할 수 있습니다.

※ 데이터셋 원본 파일은 GitHub 저장소에 포함하지 않았으므로 별도로 다운로드해야 합니다.
