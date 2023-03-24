### ✈️ 소개
한영 기계번역
    
### 🛠 기능 요약
 한국어를 영어로 기계번역

### 👩‍💻 멤버 구성
- 임수경(팀장)
- 남현수
- 정해아

### 📌 기술
- python tensorflow

### 📌 주요 기능 
- 수경님 모델: train model
             encoder: embedding층 -> lstm층 2개 쌓음 
             decodere: embedding층 -> lstm층 2개 쌓음 ->attention -> dense Softmax
             adam 옵티마이저와 sparse_categorical_crossentropy 손실함
             model fit
             inference model
             
             
- 현수님 모델:
             
             
             
- 해아님 모델 :train model
             latent_dim=64 
             encoder: embedding층 -> lstm층
             decodere: embedding층 -> lstm층  ->attention -> dense Softmax
             rmsprop 옵티마이저와 sparse_categorical_crossentropy 손실 함수
             model fit
             inference model
             
### 📌 문제 해결!
