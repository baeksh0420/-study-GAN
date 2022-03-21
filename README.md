# GAN

### 1. GAN





### 2. Style Transfer

이미지의 스타일을 변화시켜주는 모델이다.

##### 활용해보기 - 우중충한 날씨를 맑은 날씨로 바꾸기
변환 시킬 이미지와 스타일 대상 이미지
<img width="756" alt="image" src="https://user-images.githubusercontent.com/64413742/159305197-4221e4db-1946-435a-bf39-6b4a4e2843a1.png">

결과
- 50 epoch
<img width="371" alt="image" src="https://user-images.githubusercontent.com/64413742/159305044-77719802-5d74-4962-895b-4abe47c570fa.png">

- 100 epoch
<img width="371" alt="image" src="https://user-images.githubusercontent.com/64413742/159305109-a5c27e56-9ccd-4a0c-b75c-c836dc20f592.png">

- 300 epoch
<img width="371" alt="image" src="https://user-images.githubusercontent.com/64413742/159304952-da2ba9ce-6dc5-4326-84a5-379dbc4d82cf.png">


맑은 날씨로 바뀌기 보단, 이미지 결과물이 보기에 더 안좋아진다.
- 화질이 저하되는 듯 하다.
- 하얀 하늘 배경에 rgb 색상이 자연스럽게 연결되지 못한다.
- 건물은 초록 계열로 변하는 것을 보아, 풀의 영향을 받은 것으로 추측된다.



코드 링크  https://colab.research.google.com/drive/1iWZv8tGyWmA8wx_OjdfSlI7kmJrw8jnQ#scrollTo=cnDxOCNNtIfa
