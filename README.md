# GAN

### 1. GAN





### 2. Style Transfer

이미지의 스타일을 변화시켜주는 모델이다.

##### 활용해보기 - 우중충한 날씨를 맑은 날씨로 바꾸기
변환 시킬 이미지와 스타일 대상 이미지
<img width="1228" alt="스크린샷 2022-03-22 오전 1 10 23" src="https://user-images.githubusercontent.com/64413742/159304479-d6b18ec0-eddd-4d96-a19f-3792e7dce903.png">

결과
- 50 epoch
<img width="1228" alt="스크린샷 2022-03-22 오전 1 10 23" src="https://user-images.githubusercontent.com/64413742/159304685-6a4b53da-277c-4c70-a2ef-3461df98fffd.png">

- 100 epoch
<img width="1228" alt="스크린샷 2022-03-22 오전 1 10 23" src="https://user-images.githubusercontent.com/64413742/159304630-f16e3261-1f71-4d01-91b9-7f03e9a8989a.png">

-300 epoch
<img width="1228" alt="스크린샷 2022-03-22 오전 1 10 23" src="https://user-images.githubusercontent.com/64413742/159304772-7c314128-7fa2-4506-94f1-4c118d105a64.png">


맑은 날씨로 바뀌기 보단, 이미지 결과물이 보기에 더 안좋아진다.
- 화질이 저하되는 듯 하다.
- 하얀 하늘 배경에 rgb 색상이 자연스럽게 연결되지 못한다.
- 건물은 초록 계열로 변하는 것을 보아, 풀의 영향을 받은 것으로 추측된다.



코드 링크  https://colab.research.google.com/drive/1iWZv8tGyWmA8wx_OjdfSlI7kmJrw8jnQ#scrollTo=cnDxOCNNtIfa
