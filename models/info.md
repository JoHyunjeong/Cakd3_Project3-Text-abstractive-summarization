ET5 모델  

- text abstractive summarization을 위한 fine-tuning
  
- train data : AI허브 문서요약 텍스트(뉴스 텍스트)
  
  
ET5 모델에 train_data 60000개씩 epochs 8로 추가학습  
1. train_data 60000 epochs 8
2. train_data 120000 epochs 8
3. train_data 180000 epochs 8
4. train_data 240000 epochs 8
  
train_data 240000개 epochs 8 모델에 train_data 30000개 epochs 8로 추가학습  
5. train_data 270000 epochs 8  
  
train_data 270000 epochs 8 모델에 train_data 270000개 epochs4로 추가학습  
6. train_data 270000 epochs 12  
  
train_data 270000 epochs 12 모델에 train_data 20000개 epochs12로 추가학습  
7.train_data 290000 epochs 12  
  
train_data 270000 epochs 8 모델에 train_data 20000개 epochs8로 추가학습  
8. train_data 290000 epochs 8  
  
  
google colab pro plus 사용  
runtime이 최대 24시간이므로  
여건상 시간에 맞춰 데이터를 분할하여 학습 후 모델을 저장하고, 저장한 모델에 추가학습 하는 방식으로 진행  
추후 한번에 학습한 모델과, 추가학습한 모델을 비교해 볼 예정  
