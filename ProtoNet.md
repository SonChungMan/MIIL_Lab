# ProtoNet
>## Practicing Markdown
>>### Abstract
>>> metric space 학습 - 각 class의 **prototype 표현까지의 거리를 계산**해서 분류 수행  
더 단순한 **inductive bias** 반영  
**simple desing decision**이지만 성능은 동일  
**zero-shot**으로의 확장  

>>### Introduction
>>> 두 가지 접근 방식  
>>> 1. Matching Network : query set를 예측하기 위해 Support set의 학습된 임베딩에 대한 attention mechanism 사용(episode 사용)
>>> 2. LSTM을 train -> 주어진 episode에서 classifier에 대한 update -> generalization
 