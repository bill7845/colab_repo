# < DACON - 따릉이 수요예측 모델링 >

<br>

#### 모델링 목적
* 주어진 데이터(2017년 4월 1일부터, 5월 31일까지 시간별로 서울시 따릉이 대여수와 기상상황 데이터)를 바탕으로 1시간 후의 따릉이 대여수 예측

---

<br>

#### 데이터 명세
  * id : 고유 아이디
  * hour : 시간
  * hour_bef_temperature : 한 시간 전 온도
  * hour_bef_precipitation : 한 시간 전 강수여부
  * hour_bef_windspeed : 한 시간 전 바람세기
  * hour_bef_humidity : 한 시간 전 습도
  * hour_bef_visibility : 한 시간 전 시야
  * hour_bef_ozone : 한 시간 전 오존 농도
  * hour_bef_pm10 : 한 시간 전 미세먼지 농도
  * hour_bef_pm2.5 : 한 시간 전 초미세먼지 농도
  * hour_bef_count : 한 시간 전 대여량
  
  * 데이터 출처 : https://dacon.io/competitions/open/235576/data/
<br>
