# [KDT 데이터 엔지니어링 데브코스 2차 프로젝트]

## 주제

미국 금융시장과 경제 정책 지표

## 테이블 (raw_data schema)

<img width="853" alt="스크린샷 2023-12-09 오전 10 35 53" src="https://github.com/bokyung124/AWS_Exercise/assets/53086873/d29d35a6-50ce-49f3-b3fc-34f581cf447e">

## 활용 기술

<img width="828" alt="스크린샷 2023-12-09 오전 10 35 22" src="https://github.com/bokyung124/AWS_Exercise/assets/53086873/b501b67a-401e-47bc-82f1-4dc02106f3e8">

### 프로젝트 세부 결과

대시보드로 현재 미국 금융시장에 상장된 개별 기업들이 어떠한 비중으로 산업 대분류, 소분류로 구분되는지 그리고 각자의 산업군에서 어느 정도의 영향력과 경쟁력을 갖는지 한눈에 파악할 수 있습니다. 

추가적으로 마우스 오른쪽 클릭으로 Pie 차트와 Treemap 차트에서 상세한 정보를 확인할 수 있으며 Dual Line 차트로 통화량, 연준금리, 물가, 국제유가 등의 경제지표가 개별 기업의 주가에 어떤 영향을 얼마나 끼치는지 조회할 수 있습니다.

ELT 등의 결과물을 대시보드에 바로 추가하여 변수들간의 상관관계를 확인할 수 있습니다.


## 기대 효과

1. 금융시장이 어떤 산업대분류 소분류로 구분되고 각 산업별 비중이 어떻게 되는지 어떤 기업들로 구성되어있는지 한 눈에 살펴볼 수 있습니다.        
2. 각 기업별 주가 추이를 Dual Y-axis를 이용하여 금리나 통화량 등 과의 상관관계를 한눈에 살필 수 있습니다.      
3. 다른 보조지표를 손쉽게 추가·제거해 새로운 차트를 생성할 수 있습니다.       
4. 시계열 경제 지표 데이터를 수집할 수만 있다면 연도, 월, 일별로 전처리해 기존의 Dataset에 merge하거나 JOIN하여 시각화할 수 있습니다.        

## 결과 발표 영상

<https://youtu.be/b7xPB3JyDhQ>
