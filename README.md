# Blood-Pressure-Prediction

### Classification Task 
- [국민건강보험공단의 건강검진정보](https://www.data.go.kr/data/15007122/fileData.do) 데이터셋을 활용하여 기준에 따라 부여한 혈압상태(안정혈압, 고혈압, 불안정혈압)를 분류하는 과제  


### ▪️ 데이터 

- URL: https://www.data.go.kr/data/15007122/fileData.do

  <img width="926" alt="image" src="https://user-images.githubusercontent.com/114709620/225243763-ffe5dec9-b2d5-4802-acf5-39ed95ae5639.png">  
  
  
  <img width="889" alt="image" src="https://user-images.githubusercontent.com/114709620/225243841-4e65585d-a273-4670-89d8-914ae003a01f.png">  
  
  
  
  
### ▪️  라벨링    
  
- 혈압 측정값(**이완기 혈압, 수축기 혈압**)들로부터 **혈압상태** 항목 생성

      안정혈압상태: 이완기 혈압 80 미만 그리고 수축기 혈압 120 미만인 데이터
      고혈압상태: 이완기 혈압 90 이상 또는 수축기 혈압 130 이상인 데이터
      불안정혈압상태: 나머지 모든 데이터  
  
  
  <img width="864" alt="image" src="https://user-images.githubusercontent.com/114709620/225245208-e624bd92-f1c1-4cd8-ae64-1d9e5fcf83e3.png">
  
  
- 레이블 인코딩  
  
      고혈압상태 : 0
      불안정혈압상태 : 1
      안정혈압상태 : 2  
  
  
  <img width="423" alt="image" src="https://user-images.githubusercontent.com/114709620/225247326-8fd976fe-db7f-4f31-81fb-e52b0d0fcd00.png">
  
   
  <img width="974" alt="image" src="https://user-images.githubusercontent.com/114709620/225246894-fd1b5e33-ed91-49bd-ae2a-131c08127e52.png">

  


### ▪️  데이터 분석

- 결측치 및 이상치 처리 
- 민감도 분석 
- 변수 선택

코드 참고


### ▪️  모델 설계 

- Tensorflow
- PyTorch








