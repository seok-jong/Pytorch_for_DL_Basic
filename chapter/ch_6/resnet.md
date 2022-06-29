# ResNet paper Review

## Abstract

ResNet은 신경망이 깊어질수록 학습하기 어려웠던 이전의 모델들에 대해서 해결책을 제시한 모델이다.  
ResNet은 152층의 깊이까지 구현할 수 있으며, 이는 VGG보다 8배 깊으면서도 더 낮은 복잡도를 가지고 있다.

## Introduction

신경망의 깊이를 깊게하는 것은 classification에서의 성능뿐만 아니라 관련 여러 분야에서의 성능을 높힐수 있었다.  
하지만 신경망의 깊이를 지나치게 깊게할경우 훈련과정에서 정확도가 포화하거나 급격하게 저하되는 현상이 있었고 이는 train dataset에 대한 overfitting이 아니며 training에 큰 error를 발생시켰다.

이 논문은 이러한 문제에 대한 해결책을 제시하였으며 그것을 이용한 모델(ResNet)을 제시한다.
