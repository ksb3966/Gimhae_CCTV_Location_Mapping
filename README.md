# Gimhae_CCTV_Location_Mapping
# 시민 안전을 위한 CCTV 사각지대 해소 방안

## Overview
김해시는 경상남도 내 강력범죄 비율이 가장 높은 도시이다. 
인구 1만명당 5대 강력 범죄 발생 건수는 105.3건으로 전국 84건에 대비 20% 높은 수치를 보이고 있는데, 
각종 사건 사고로부터 안전한 도시를 조성하고 시민의 안전한 생활을 보장하기 위해 CCTV의 최적의 위치 선정 연구를 진행했다.
데이터를 활용해, 합리적인 CCTV 설치위치를 50개소 제안하고, 그 근거를 확인해보는 것이 이번 연구의 주제이다. 

## 분석 방법
분석 방법은 AHP 분석 기법을 활용했다. 
이는 복잡한 문제를 계층화하여 주요 요인과 세부 요인들로 분해해 각 요인들에 대한 일 대 일 비교를 통해 생성된 데이터를 기반으로 상대적 중요도를 산출하는 방법이다.
먼저 요인을 기준으로 감시요인 > 범죄요인 > 상권요인 > 안전 및 보안시설요인 > 주택 및 입지요인 > 인구요인 순으로 중요도를 기존 연구를 바탕으로 산출했고, 각 요인들의 세부지표들의 요인내 중요도를 산출해 두 값을 곱함을 통해 세부지표 중요도를 산출할 수 있다. 

## Code In Colab
https://colab.research.google.com/drive/1QZkuzZvUIue7OOiZtdSfEqyGBMq9dla4
