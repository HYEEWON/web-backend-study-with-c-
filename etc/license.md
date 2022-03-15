# SW 라이선스

<br>

## 정의
* SW 사용에 대한 권리, 사용 허가의 내용이 담긴 문서
* SW 자체에 대한 소유권과는 별개인 권리
* 소유권은 저작권자의 것으로 사용자는 사용에 대한 권리만 가짐
* 사용자는 사용할 수 있는 범위와 방법이 제한되어 있으며 이것을 침해할 경우, 저작권 침해가 됨
* 기업의 SAM 책임자는 SW가 어떤 조건을 제공되는 것인지를 모두 파악해야 함

> SAM(SW Asset Management): SW 구매에서부터 사후 관리까지의 전반적인 과정

<br>

## 종류

### 사용 기간에 따른 분류
#### 영구 라이선스
* 한번의 구매로 영원히 사용할 수 있음 ex) 패키지 SW
#### 기간 라이선스
* 일정 기간동안만 사용할 수 있음 ex) 볼륨 라이선스
#### 임시 라이선스

### 사용 기준에 따른 분류
#### 1인 1 PC 라이선스
* PC 1대에 1개의 SW를 설치해야 함
#### 동시 사용자 라이선스
* SW를 동시에 사용할 수 있는 사람의 수를 제한함
#### 사이트 라이선스
* PC 수나 사용자수의 제한 없이 특정 장소에서 SW를 무제한으로 사용할 수 있도록 허가

### 공급 형태에 따른 분류
#### 패키지 라이선스
* 과거에 많이 사용하던 방식
#### 볼륨 라이선스
* 라이선스 계약 방식으로 계약을 통해 라이선스 증서를 받음, 분실 시 재발급이 가능하고 패키지 라이선스에 비해 저렴
#### 번들 SW
* HW와 함께 제공되는 SW로 다른 HW에서 사용하면 안됨

### 공개 여부에 따른 분류
#### 상용 SW
* 기업이 사용하는 대부분의 SW, 비용 지불이 필요함
#### 셰어웨어
* 일정 기간 사용 후, 비용을 지불하여 구입하고 계속 사용하는 방식
#### 프리웨어
* 저작권자가 비용을 받지 않고 공개한 SW

<br>

# 오픈SW 라이선스

<br>

## 정의
### 오픈 소스의 정의를 따르는 라이선스
* 오픈 SW에 자유롭게 접근 및 이용이 가능함
* 오픈 SW를 자유롭게 수정하고 조건하에 재배포가 가능함
* 이를 위반할 경우 저작권 침해가 됨
* 오픈소스SW 개발자와 사용자 간에 이용 방법 및 조건의 범위를 명시한 계약

<br>

## 내용 구성
* 라이선스마다 차이 존재
### 저작권 관련 문구 유지
* 오픈 SW의 경우 대부분 코드 상단에 개발자의 정모, 연략처 등이 기록되어 있어 사용자가 임의로 수정하거나 삭제하면 안됨
### 제품명 중복 방지
* SW의 제품명은 상표권으로 보호를 받아 주의가 필요
### 서로 다른 라이선스 조합
* 서로 다른 라이선스로 배포된 오픈 SW를 결합하는 경우, 라이선스의 호환에 대한 확인 필요

<br>

## 종류
### BSD 라이선스
* 버클리 대학에서 제작
* 무료로 이용이 가능하고 소스 코드의 취득 및 수정 가능
* 2차 저작물의 재공개 의무가 없고 독점 SW와 결합 가능

### Apache 라이선스
* 아파치 소프트웨어 재단에서 제작
* 무료로 이용이 가능하고 소스 코드의 취득 및 수정 가능
* 2차 저작물의 재공개 의무가 없고 독점 SW와 결합 가능

### GPL
* 대부분 FSF(Free Software Foundation)에서 제작
* 무료로 이용이 가능하고 소스 코드의 취득 및 수정 가능
* 2차 저작물의 재공개 의무가 있으며 독점 SW와 결합 불가능

<br>

# SW 라이선스 침해/위반 사례
## 한글과컴퓨터의 오픈 SW 라이선스 위반 (2016)
* 아티펙스는 오픈 소스인 '고스트스크립트'를 한글과컴퓨터가 무단으로 도용했다는 문제를 제기
* GPL 라이선스와 상용 라이선스에 따라 무료로 사용하며 SW의 코드를 공개하거나 비용을 지불하여 라이선스를 구매해야 함
* 한글과컴퓨터는 해당 의무를 수행하지 않아 아티펙스가 소송 제기
* 한글과컴퓨터는 아티펙스에 205만 달러의 합의금 지불

<br>

## Skype의 오픈 SW 라이선스 위반 (2007)
* Skype가 판매하는 SMC 네트워크 VoIP 전화기는 GPL 2.0으로 배포된 소프트웨어 2개를 포함한 리눅스 운영체제를 사용
* Skype는 GPL 라이선스의 조건에 따라 소스 코드를 공개하지 않았고 GPL 라이선스 문구를 붙이지도 않음
* 저작권자인 벨테(Welte)는 소송을 제기했고, Skype는 소스 코드를 공개하고 벌금을 지불

<br>

## GNU Go(게임 이름)와 Apple 앱스토어
* Robota Softwarehouse라는 회사가 GPL로 배포되고 있는 GNU Go라는 게임을 Apple 앱스토어에 등록하면서 GPL을 따르지 않게 됨
* GPL은 이용자들에게 추가 제한을 못 하게 하지만 Apple은 해당 앱을 아이폰 OS에서만 사용하도록 제한함
* 이 결과로 Apple은 앱스토어에서 GNU Go를 삭제함