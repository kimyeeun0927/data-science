## **음성 기반 감정 예측 (ML)**

- 문제 정의: 짧은 음성 녹음으로 사람의 감정을 예측하는 ML 모델 개발
- 사용 기술:
    - 음성 특성 추출: openSMILE or Librosa (MFCC, pitch, energy 등)
    - 텍스트 토큰화: MeCab -> Tfidvectorizer
    - 모델: SVM, Random Forest, XGBoost, CatBoost 등 + 성능 비교
- 데이터셋:
    - [감정 분류를 위한 대화 음성 데이터셋] by 카이스트 인공지능 연구소: https://aihub.or.kr/aihubdata/data/view.do?dataSetSn=263
- 장점:
    - 비교적 가볍고 명확한 ML 적용 가능
    - 전처리모델 학습평가까지 프로젝트 흐름이 뚜렷함
- 평가: F1-score, confusion matrix, ROC-AUC 등 ML 지표 활용
