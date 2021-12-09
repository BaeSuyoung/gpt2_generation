# 연구학점제  
## 주제  
- ROCStories 데이터셋을 사용한 GPT2 문장 생성  

## 연구 기간  
- 2021.9.1~2021.12.10  

## Abstraction  
- 본 연구는 사전 훈련된 GPT2 모델을 사용해서 Text Generation을 구현해 생성된 문장이 원래 문법, 의미, 반복성 등에서 얼마나 정확성을 보이는지 실험하는 연구입니다. 모델은 gpt2 Hggingface pre-train 모델을 사용했고, 데이터셋은 ROCstories dataset을 사용해서 모델에 대한 fine-tunning을 진행했습니다. 실험은 총 두가지를 진행했습니다. 첫번째는 gpt2 모델 학습 시 batch size, epoch, learning rate를 조정하면서 perplexity 가 가장 낮은 hyperparameter를 찾는 실험과, 학습된 모델을 사용해서 문장을 생성할 때 top p값과 temperature를 조정하면서 bleu, rouge 평가시 가장 좋은 결과가 나오는 hyperparameter를 찾는 실험을 진행했습니다.  

## 파일 구성  
1. 데이터셋  
  - train_dataset.csv  
  - test_dataset.csv  
  - valid_dataset.csv  
  - new_dataset.cvs  
  - final_test_dataset.csv  
  - ROCStories_winter2017 - ROCStories_winter2017.csv  
2. 코드  
  - gpt2.ipynb  
3. 실험 최종 보고서  
  - 최종 보고서_2018312958배수영.hwp  
  - 발표 보고서_2018312958배수영.hwp  
  - 연구학점제 ppt.pdf  
