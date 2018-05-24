# 영화 평점 예측

* 몇가지 기계학습 방법을 이용한 영화 평점(감정) 예시입니다.
* 학습용, 발표용으로 제작되었습니다.


## Intro
* 사전 기반 모델
	- 각 단어가 속한 리뷰들의 평점을 평균내어 각 단어의 점수를 메겼습니다.

* 기계학습 기반 모델
	- Linear Regression, Ridge Regression, GradientBoostingRegression 등의 모델을 사용하여 예측했습니다.

* 딥러닝 기반 모델
	- CNN 기반 regression 모델
		- Convolutional Neural Networks for text classification <https://arxiv.org/pdf/1408.5882.pdf> <br/> 논문에 나온 방법을 차용했습니다.
	- RNN 기반 regression 모델
		- Bidirectional 2-layer GRU 모델 사용


## Dependency
* Anaconda python 3.5 +
* KoNLPy
* pytorch
* ujson


## Contact
실습을 위한 데이터 및 기타 문의는 rudvlf0413@naver.com으로 연락주시기 바랍니다.