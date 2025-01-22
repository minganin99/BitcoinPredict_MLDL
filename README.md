# <img src="https://github.com/user-attachments/assets/8d7528fe-effd-4eec-bf4d-35ace2bc1be7" alt="코인임티" width="50"> 비트코인 가격 추세 예측?
1. [개요](#1-project-overview-프로젝트-개요)
2. [팀원 소개](#2-team-members)
3. [기술 스택](#3-technology-stack-기술-스택)
4. [사용 데이터](#4-data-set-사용-데이터)
5. [프로젝트 과정](#5-project-flow-프로젝트-과정)
6. [결론](#6-conclusion-결론)
7. [부록](#7-부록)
<br/>

# 1. Project Overview (프로젝트 개요)
  최근 암호화폐 시장은 급격한 성장과 함께 높은 변동성이라는 특징을 보이며 투자자들의 큰 관심을 받고 있다. 특히 비트코인은 최초의 암호화폐로서 시장에 큰 영향력을 행사하지만, 예측하기 어려운 가격 변동은 투자 결정에 어려움을 야기한다. 따라서, 시장 참여자들의 불확실성을 줄이고 합리적인 의사결정을 지원하기 위해 신뢰성 높은 비트코인 가격 예측 모델에 대한 필요성이 강조되고 있다. 
  
  머신러닝과 딥러닝 기술의 잠재력을 최대한 활용하여 비트코인 가격 방향 예측 모델의 정확도를 높이는 것을 목표로 한다. 다양한 거래소 또는 데이터 제공 플랫폼에서 API를 통해 제공되는 가격 데이터, 거래량, 기술 지표 등의 시장 데이터를 활용하여 기존 연구의 한계를 극복하고자 한다. 더불어, 다양한 피처 선택 방법을 적용하여 불필요한 변수를 제거하고 모델의 일반화 성능을 향상시키는 데 집중할 것이다. 궁극적으로 본 프로젝트는 실제 투자 환경에 적용 가능한 효율적인 예측 모델을 개발하고, 이를 기반으로 한 거래 전략의 수익성을 평가하여 실질적인 투자 가치를 창출하는 것을 목표로 한다.

<br/>
<br/>

# 2. Team Members
### 2.1 Team Members (팀원 및 팀 소개)
| 박훈석 | 정민관 | 신영섭 | 이현 |
|:------:|:------:|:------:|:------:|
| <img src="https://github.com/user-attachments/assets/6b673df2-d21e-4762-aaed-688ae70d9556" alt="박훈석" width="150"> | <img src="https://github.com/user-attachments/assets/9a3b5276-200a-42ed-a9f7-5012c68bd04a" alt="정민관" width="150"> | <img src="https://github.com/user-attachments/assets/c547ab1e-164a-407b-a275-97e40947bde4" alt="신영섭" width="150"> | <img src="https://github.com/user-attachments/assets/7961490e-8726-49e5-8409-c2519060887b" alt="이현" width="150"> |
| 팀장 | 팀원 | 팀원 | 팀원 |
| [GitHub]() | [GitHub](https://github.com/minganin99) | [GitHub](https://github.com/yerin1028) | [GitHub](https://github.com/hyun9396) |

### 2.2 Tasks & Responsibilities (작업 및 역할 분담)
|  |  |  |
|-----------------|-----------------|-----------------|
| 박훈석    |  <img src="https://github.com/user-attachments/assets/6b673df2-d21e-4762-aaed-688ae70d9556" alt="박훈석" width="100"> | <ul><li>프로젝트 계획 및 관리</li><li>도메인 분석</li></ul>     |
| 정민관   |  <img src="https://github.com/user-attachments/assets/9a3b5276-200a-42ed-a9f7-5012c68bd04a" alt="정민관" width="100">| <ul><li>업비트 API 연동 및 관리</li><li>데이터베이스 관리</li><li>데이터 분석 및 전처리</li><li>머신러닝, 딥러닝 모델링</li></ul> |
| 신영섭   |  <img src="https://github.com/user-attachments/assets/c547ab1e-164a-407b-a275-97e40947bde4" alt="신영섭" width="100">    |<ul><li>데이터 수집</li><li>데이터 분석 및 전처리</li><li>머신러닝 모델링</li></ul>  |
| 이현    |  <img src="https://github.com/user-attachments/assets/7961490e-8726-49e5-8409-c2519060887b" alt="이현" width="100">    | <ul><li>데이터 수집</li><li>데이터 분석 및 전처리</li><li>딥러닝 모델링</li></ul>    |

<br/>
<br/>

# 3. Technology Stack (기술 스택)
## 3.1 Language and Framework
|  |  |
|-----------------|-----------------|
| Python    |   <img src="https://github.com/user-attachments/assets/e25dd8d8-be57-47d6-8131-3357dfd1d719" alt="HTML5" width="50">| 
| PyTorch   |   <img src="https://github.com/user-attachments/assets/5a7068bb-4f75-4b1d-9649-5b93e6625527" alt="Javascript" width="50"> | 
| Tensorflow   |   <img src="https://github.com/user-attachments/assets/66f2326b-d692-4946-8991-37eb0cda9669" alt="Javascript" width="50"> | 
| Scikit-Learn   |   <img src="https://github.com/user-attachments/assets/673ed644-4871-4932-85f3-ae964f136e19" alt="Javascript" width="50"> | 
| VSCode    |   <img src="https://github.com/user-attachments/assets/25efc7be-2959-4523-9803-33df9933687d" alt="CSS3" width="50">|


<br/>

## 3.2 Data
|  |  |  |
|-----------------|-----------------|-----------------|
| SQLite |  <img src="https://github.com/user-attachments/assets/bb49ecba-eebf-415d-b2c9-5e7d36a88bc4" alt="React" width="50"> | 데이터베이스    |
| Pandas |  <img src="https://github.com/user-attachments/assets/3d9d4475-4214-4249-a669-298a8223c1f6" alt="React" width="50"> | 데이터 분석    |
| Pyupbit |  <img src="https://github.com/user-attachments/assets/e140a473-bbd9-4a90-9e9e-ed07374c2870" alt="StyledComponents" width="50">| api를 통한 업비트 데이터 수집   |
| Matplotlib |  <img src="https://github.com/user-attachments/assets/a2374cc7-2bb3-4f5f-9e81-6aea29b7c4cd" alt="MUI" width="50">    | 데이터 시각화 |
| Seaborn |  <img src="https://github.com/user-attachments/assets/6d600bdf-80bd-4d6f-85b9-1eceba0d89ab" alt="DayJs" width="50">    | 데이터 시각화   |

<br/>

## 3.3 Cooperation
|  |  |
|-----------------|-----------------|
| Git    |  <img src="https://github.com/user-attachments/assets/483abc38-ed4d-487c-b43a-3963b33430e6" alt="git" width="50">    |
| Discord    |  <img src="https://github.com/user-attachments/assets/e4ab1aee-4a83-4435-8ebf-822cef26d1dc" alt="git kraken" width="50">    |
| Notion    |  <img src="https://github.com/user-attachments/assets/34141eb9-deca-416a-a83f-ff9543cc2f9a" alt="Notion" width="50">    |

<br/>


# 4. Data Set (사용 데이터)
upbit에서 제공하는 비트코인에 관한 일별 데이터 수집
- 날짜 및 시간
- 시가
- 종가
- 최고가
- 최저가
- 거래량

위의 기본 변수를 사용하여 기술적 파생변수 생성
- Moving Average(MA)
- Bollinger Band
- Moving Average Convergence Divergence(MACD)
- Relative Strength Index(RSI)
- Stochastic Oscillator


<br/>
<br/>

# 5. Project Flow (프로젝트 과정)
### 5.1 데이터 수집
- pyupbit를 활용한 비트코인 시장 데이터 수집
- 수집한 데이터 sqlite의 데이터베이스에 저장
  
### 5.2 변수 선택
- 독립변수는 기본 변수와 기본 변수를 활용한 기술 파생 변수 생성
- 종속변수는 다음날의 종가가 상승할지 하락할지 이진분류

### 5.3 데이터 전처리
- 이동 평균을 사용하기 때문에 앞쪽 데이터는 결측치 발생(삭제)
- StandardScaler로 수치형 변수 정규화
- 학습 및 테스트 데이터와 검증용 데이터를 따로 분리

### 5.4 ML 모델링
- Logistic Regression
- Ensemble Mean
- XGBoost
- RandomForest
- Support Vector Machine

### 5.5 DL 모델링
- DNN
- RNN
- LSTM
- Bidirectional RNN

### 5.6 모델 평가 및 비교
- 정확도
- 정밀도
- 재현율
- F1-Score
- 혼동행렬

# 6. Conclusion (결론)
- 머신러닝 모델은 성능 정확도가 0.5~0.6사이에 존재
- 딥러닝 모델은 성능 정확도가 DNN이 0.7~0.8 정도로 성능이 좋음
- 나머지 딥러닝 모델은 머신러닝 모델과 비슷함

### 6.1 왜 시계열 데이터인데 RNN이나 LSTM이 아닌 DNN이 성능이 좋았을 까??
- 비트코인의 특징이 오히려 DNN의 학습에 좋은 결과로 작용
- 비트코인의 특징은 거래시간이 자유롭고 규제도 자유롭고 변동성도 높음
- 비정상성이고 노이즈에 더 잘 적응할 수 있는 DNN이 성능이 훨씬 잘 나오게 됨
  
### 6.2 실제 투자에 적용
- 2025년 1월 1일부터 실제 예측을 적용
- 75%의 정확도를 보임
- 홀드전략으로 투자를 했다면 원금의 4% 수익률
<img width="311" alt="image" src="https://github.com/user-attachments/assets/8c2e413c-76c7-4aff-844c-393fe9857054" />

# 7. 부록
- CUDA를 사용하여 GPU와 연결하여 딥러닝 학습
- 참고 논문: 서유범, 황창하, Predicting Bitcoin Market Trend with Deep Learning Models, Quantitave Bio-Science, 2018.05.25

<br/>
<br/>

