# Imbalanced-Data-Handling-Techniques-in-Hate-Speech-Detection
A Study on Imbalanced Data Handling Techniques in Hate Speech Detection: Focused on Oversampling

소셜 미디어를 중심으로 온라인에서 발생하는 폭력적, 차별적 언어를 식별 및 억제하는 작업은 필수적이며, 이와 같은 혐오 표현 탐지를 위한 연구가 활발히 진행되고 있다. 하지만 혐오 표현 데이터셋의 특성상 2개 이상의 클래스를 가지는 경우, 주류 클래스인 정상 샘플에 비해 혐오표현 클래스 샘플의 수가 적은 데이터 불균형성이 나타나는 경향이 있다. 본 연구는 이를 고려해 오버 샘플링을 중심으로 혐오 표현 탐지를 위한 불균형 데이터 처리 기법을 비교한다. 다중클래스 분류를 위한 머신러닝 알고리즘 중 다항분포 나이브 베이즈, 서포트 벡터 머신이 랜덤 오버 샘플링과 SMOTE 계열 기법 적용시 큰 성능 향상을 보였으며, 딥러닝 알고리즘 중 LSTM 기반 분류기에 랜덤 오버 샘플링을 적용한 결과 주류 클래스에 대한 과적합 문제가 해결됨을 확인하였다.

Detecting and suppressing violent and discriminatory language online, especially on social media, is essential, and research in hate speech detection has been actively progressing. However, due to the nature of hate speech datasets, when there are more than two classes, data imbalance tends to occur as hate speech samples are fewer than normal samples, which dominate the dataset. This study compares imbalance data handling techniques for hate speech detection, focusing on oversampling. Among machine learning algorithms for multi-class classification, Multinomial Naive Bayes and Support Vector Machines showed significant performance improvement when random oversampling and SMOTE-based techniques were applied. For deep learning algorithms, applying random oversampling to an LSTM-based classifier effectively resolved the issue of overfitting to the majority class.

- Dataset: [HateXplain](https://github.com/hate-alert/HateXplain)
- Used Imbalanced Data Handling Techniques
  - Random Oversampling (ROS)
  - SMOTE
  - K-Means SMOTE
  - ADASYN
- Classification Algorithm
  - ML: Multinomial Naive Bayes, SVM, RandomForest, XGBoost
  - DL: LSTM 

