# Dacon_AI_Competition  

*데이콘 AI 경진대회 참여한 경험을 기록합니다.*  🤓


  
  
- BiLSTM을 이용한 영화 리뷰 감성 분류(~20220121)  
  - keras를 이용한 Bidirectional LSTM 신경망을 사용.
  - train set과 val set을 8:2로 구성하여 학습.
  - optimizer는 Adam, early stop, scheduler, drop out을 적용하여 파라미터 튜닝 시도.  
  (레이블 간 데이터간 균형된 상태로 오버샘플링은 큰 의미가 없었음)
  - train acc 98.72%, val acc 84.65% 을 기록.  
  - 오버피팅의 가능성이 있어 추후 오버피팅을 줄이기 위한 시도를 추가할 예정.
  - ref.https://dacon.io/competitions/official/235864/overview/description
