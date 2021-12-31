# 한계경쟁률 계산기

![license](https://img.shields.io/badge/license-CC--BY--NC--SA-orange)

대입 정시모집을 위한 한계경쟁률 자동 계산기 프로그램입니다.

<br/>

## 목차

파란 글씨를 누르면 해당 목차로 이동합니다.
* [1.원리](#chapter-principle)
* [2.사용법](#chapter-instruction)
* [3.많이하는 질문](#chapter-questionss)
* [4,주의사항](#chapter-precautions)
* [5.라이선스](#chapter-License)

<br/>

### 2.사용법 <a id="chapter-instruction"></a>

* 열별소개 [노란색 셀: 주기적 갱신이 필요한 셀 | 초록색 셀: 자동으로 계산되어지는 셀]

<br/>

|군별<br/>모집|대학 소재지|대학구분<br/>(라인)|대학명|계열|학과명|
|:---:|:---:|:---:|:---:|:---:|:---:|
|나군|서울 관악구|서연고|한국대학교|자연|의예|

* 군별모집: [가군: 빨간색 / 나군: 노란색 / 다군: 초록색]
* 계열: [자연: 파란색 / 인문: 초록색]

<br/>
<br/>

|진학사<br/>합격칸수|최초 정시<br/>모집인원|예상 수시<br/>이월인원|예상 정시<br/>모집인원|2022<br/>경쟁률|2021<br/>경쟁률|2020<br/>경쟁률|진학사<br/>예상경쟁률|추가합격률|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|5|28|1|29|18.89|16.6|20.26|16.08|650.43%|

* 노란색 셀 (주기적 갱신이 필요한 셀): 진학사 합격칸수, 예상 수시 이월인원 (미충원 인원), 진학사 예상경쟁률
* 초록색 셀 (자동으로 계산되어지는 셀): 예상 정시 모집인원, 추가합격률
* 진학사 합격칸수: [0 ~ 4: 빨간색 / 5 ~ 6: 노란색 / 7 ~ 9: 빨간색]

<br/>
<br/>

|내 등수|전체<br/>지원자수|등수<br/>백분위|일반<br/>한계경쟁률|실제<br/>한계경쟁률|작년경쟁률<br/>차이|진학경쟁률<br/>차이|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|643|1395|46.09%|2.17|16.28|-2.61|0.2|

* 노란색 셀 (주기적 갱신이 필요한 셀): 내 등수, 전체 지원자수
* 초록색 셀 (자동으로 계산되어지는 셀): 등수 백분위, 일반 한계경쟁률, 실제 한계경쟁률, 작년경쟁률 차이, 진학경쟁률 차이
* 작년경쟁률 차이, 진학경쟁률 차이: [ ~ -0.5 : 빨간색 / -0.5 ~ -0.2 주황색 / -0.2 ~ 0.2 노란색 / 0.2 ~ 1 연한초록색 / 1 ~ 진한초록색 ]

- 내 등수: 전체 지원자 중 나의 등수
- 전체 지원자수: 전체 지원자수
- 등수 백분위: 전체 지원자수와 내 등수로 산출한 내 백분위 위치
- 일반 한계경쟁률: 추가합격을 고려하지 않고 등수 백분위로만 산출한 한계경쟁률 (최초합격권)
- 실제 한계경쟁률: 등수 백분위와 추가합격률로 산출한 한계경쟁률 (추가합격권)
- 작년경쟁률 차이: 작년 경쟁률과 실제 한계경쟁률간의 차이
- 진학경쟁률 차이: 진학사 경쟁률과 실제 한계경쟁률간의 차이

<br/>
<br/>

|내 등수|전체<br/>지원자수|등수<br/>백분위|일반<br/>한계경쟁률|실제<br/>한계경쟁률|경쟁률간<br/>차이|작년경쟁률<br/>차이|진학경쟁률<br/>차이|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|278|604|46.03%|2.17|16.28|-2.61|0|-2.61|0.2|

* 노란색 셀 (주기적 갱신이 필요한 셀): 내 등수, 전체 지원자수
* 초록색 셀 (자동으로 계산되어지는 셀): 등수 백분위, 일반 한계경쟁률, 실제 한계경쟁률, 경쟁률간 차이, 작년경쟁률 차이, 진학경쟁률 차이
* 작년경쟁률 차이, 진학경쟁률 차이: [ ~ -0.5 : 빨간색 / -0.5 ~ -0.2 주황색 / -0.2 ~ 0.2 노란색 / 0.2 ~ 1 연한초록색 / 1 ~ 진한초록색 ]

- 내 등수: 실제 지원자 중 나의 등수
- 전체 지원자수: 실제 지원자수
- 등수 백분위: 전체 지원자수와 내 등수로 산출한 내 백분위 위치
- 일반 한계경쟁률: 추가합격을 고려하지 않고 등수 백분위로만 산출한 한계경쟁률 (최초합격권)
- 실제 한계경쟁률: 등수 백분위와 추가합격률로 산출한 한계경쟁률 (추가합격권)
- 경쟁률간 차이: 전체지원자 실제 한계경쟁률과 실제지원자 실제 한계경쟁률간의 차이
- 작년경쟁률 차이: 작년 경쟁률과 실제 한계경쟁률간의 차이
- 진학경쟁률 차이: 진학사 경쟁률과 실제 한계경쟁률간의 차이

<br/>
<br/>

|현재 경쟁률|경쟁률 차|한계 경쟁률<br/>범위|
|:---:|:---:|:---:|
|6.8|9.48|16.28 ~ 16.28|

* 초록색 셀 (자동으로 계산되어지는 셀): 보정 경쟁률, 한계 경쟁률 범위

- 현재 경쟁률: 마지막 업데이트 경쟁률
- 경쟁률 차: 현재 경쟁률과 전체 지원자 한계경쟁률의 차
- 한계 경쟁률 범위: 전체지원자 실제 한계경쟁률과 실제지원자 실제 한계경쟁률 구간

<br/>
<br/>

|2022년<br/>모집인원|2022년<br/>추가합격인원|2021년<br/>모집인원|2021년<br/>추가합격인원|2020년<br/>모집인원|2020년<br/>추가합격인원|
|:---:|:---:|:---:|:---:|:---:|:---:|
|38|289|40|254|39|218|

<br/>
<br/>

|3개년<br/>모집인원|3개년<br/>추가합격인원|평균추합률|2022년<br/>모집 - 추합|2021년<br/>모집 - 추합|2020년<br/>모집 - 추합|
|:---:|:---:|:---:|:---:|:---:|:---:|
|117|761|650.43|-251|-214|-179|

* 초록색 셀 (자동으로 계산되어지는 셀): 3개년 모집인원, 3개년 추가합격인원, 평균추합률, 2022년 모집 - 추합, 2021년 모집 - 추합, 2020년 모집 - 추합

<br/>

### 4. 주의사항 <a id="chapter-precautions"></a>

* 본 프로그램은 정시 대입을 위해 특별히 제작되었습니다.
* 본 프로그램은 의치한약수 ~ 인서울 ~ 지거국 ~ 지방사립대학등 모든 대학과 학과에 할용하 수 있습니다.
* 본 프로그램은 무료로 배포됩니다.
* 개발자는 본 프로그램을 통해 수익을 창출하지 않습니다.
* 본 프로그램을 사용하기 위해서는 진학사 합격예측 결제가 필요합니다.
* 본 프로그램은 사용자의 대입을 보장하지 않습니다.
* 진학사와 본 프로그램이 상충될경우 진학사를 우선하여 결정하십시오.
* 본 프로그램의 모든 저작권은 개발자에게 있습니다.
* 문의사항은 'h5638880@naver.com'으로 연락바랍니다.

사용자님의 합격을 기원합니다.

<br/>

### 5. 라이선스 <a id="chapter-License"></a>

ⓒ Some rights reserved,<br/>별도의 언급이 없다면 본 프로그램은 크리에이티브 커먼즈 [저작자표시-비영리-동일조건변경허락 4.0 국제 라이선스]에 따라 이용할 수 있습니다.
