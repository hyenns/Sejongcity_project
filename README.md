# 세종시 공공 전기자전거 도입을 위한 거치대 최적 입지 선정

<img src="https://github.com/user-attachments/assets/5f9fe84d-e49d-4157-a16a-0d8c766c16f6" alt="세종시 공모전 포스터" width="500" height="700">

- 주최: 세종특별자치시
- 명칭: 제5회 세종특별자치시 빅데이터 분석 아이디어 공모전
- 수상: 본선 진출

## 공모 내용
- 데이터를 활용한 도시문제 해결, 기존 정책 개선방안 및 스마트서비스 발굴 등 빅데이터 분석 아이디어 제안

## 프로젝트 PPT
[<img width="1330" alt="세종시 발표 자료 메인" src="https://github.com/user-attachments/assets/eaa1324c-704e-40dc-8d86-13677b249d78">](https://github.com/hyenns/sejongcity_project/blob/main/%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%8C%E1%85%A6%E1%86%A8%E1%84%90%E1%85%B3_%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD.pdf)
<div align="center"> 👆🏻위 이미지를 클릭하면 프로젝트 PDF를 보실 수 있습니다.👆🏻 </div><br>

## 프로젝트 주요 내용
- 문제 정의: 세종시의 현 도시 문제가 무엇이며 어떻게 해결할 수 있을 것인가?
- 가설 설정: 도로 교통 문제가 있을 것이며 이는 공공 전기자전거의 도입으로 해결할 수 있을 것이다.
- 실험설계 및 검증: 공공데이터 포털, 세종시 교통 빅데이터분석 시스템, 국가통계포털, 뉴스 크롤링을 통해 데이터를 수집하고 직접 제작한 횡단보도 위치 데이터를 활용해 분석을 진행
    - 도로 교통 문제: 뉴스 크롤링을 통해 세종시민의 불편함을 파악하고 구간별 감속률을 구해 교통 체증 현황을 파악
    - 공공 전기자전거 도입: 공공 전기자전거 도입을 위해선 그 필요성과 방안 제안이 필요하다고 판단
        - 필요성: 출퇴근 시간의 차량 주행 속도와 자전거 이용률을 파악해 제안
        - 방안: 전기자전거의 주차 문제 해결을 위해 전기자전거의 거치대 수와 거치대 입지를 선정해 제안
- 결과:
    - 도로 교통 문제: 세종 시민의 불편함 중 검색 빈도가 높은 단어는 도로, 교통, 정체로 나타났음. 또한, 세종시의 도로의 구간별 감속률을 구해봤을 때 감속률이 높음 이상인 도로가 전체 도로의 약 79%임을 확인하였음.
    - 공공 전기자전거의 도입:
        - 필요성: 출퇴근 시간, 도로별로 시속 25km 미만으로 주행하는 구간을 구해봤을 때 세종시의 도로 중 약 53%의 구간이 이에 해당함을 확인하였음. 이는 승용차보다 전기자전거를 이용하여 이동하는 것이 더 빠르게 이동할 수 있음을 예상함.
        - 방안: 거치대 수 분석은 K-Means Clustering을 활용해 진행하였고, 거치대 입지 분석은 MCLP와 OPTICS 모델을 활용하여 진행하였음. 결론적으로 지도로 시각화를 한 후, 군집을 특정하여 해당 군집에 공공 전기자전거의 거치대를 설치하는 것이 최적 입지임을 제안하는 것에 성공하였음.
- 적용: 분석을 토대로 공공 전기자전거가 도입된다면 다음과 같은 효과를 기대할 수 있을 것임.
    - 교통 체증 완화로 시민들의 출퇴근 스트레스 감소
    - 자전거 도시, 차 없는 도시에 더 가까워지는 세종시
    - 이산화탄소 저감 및 탄소 배출량 감소



