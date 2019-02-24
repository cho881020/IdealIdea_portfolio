# 프로젝트 및 기술 사용 목록

## Luxtype

### 개요

- 입간판 커스터마이징을 시작으로, 다양한 상품의 커스터마이징 및 제품 구매를 연결해주는 서비스입니다.

### 플랫폼

- 웹 (HTML / CSS / JS + Vue.js)

### 특이 기능 목록

- 입간판 간이 에디터
  - 텍스트를 입력하면, 화면에 바로 반영되어 간단하게 디자인을 확인할 수 있습니다.
- 장바구니 담기 및 결제
  - 에디터에서 편집된 상품을 확정지으면, 장바구니에 담깁니다.
  - 장바구니에 담긴 상품을 모아 한번에 결제합니다.
    - 결제는 [아임포트](http://www.iamport.kr) 를 활용했습니다.
- 결제 결과 전송
  - 결제가 완료된 입간판은, 제작 업체의 API를 활용하여 데이터를 전달해 생산에 들어갑니다.
- 관리자페이지
  - 상품 목록
    - 입간판 이외의 라인업을 만들기 위한 DB설계 및 기능
  - 테마 관리
    - 각 상품별 디자인 템플릿 관리 기능
  - 사용자 관리
    - 회원가입한 사용자의 기본 정보 및 활성화 상태 관리

## Wasavi

### 개요

- 택배기사와 지역주민을 연결해 택배기사의 업무 강도를 낮추고, 지역주민의 일자리를 창출하는 서비스입니다.

### 플랫폼

- Android (JAVA) - 근무자, 발주자, 시스템어드민
- iOS (Swift) - 근무자

### 특이 기능 목록

- 회원가입 및 로그인
  - 계정별 역할 부여 - 계정에 따라 근무자인지, 관리자인지, 혹은 어드민 역할도 겸하는지 알려줍니다.
- 포인트 결제
  - 발주를 하기 위해서는 포인트 결제를 해야합니다.
  - 포인트 결제는 마찬가지로 [아임포트](http://www.iamport.kr) 를 활용했습니다.
- 근무자 / 발주자 매칭
  - 업무를 맡길 택배기사님과 일을 대행해줄 지역 근무자를 매칭하는 기능입니다.
  - 초기에는 카카오택시와 비슷한 형태의 앱이었으나, 현재는 다른 방식으로 매칭 하고 있습니다.
- 근무 결과 보고
  - 앱을 이용해서 상자를 잘 배송했다는 인증을 남깁니다. 사진 첨부, 그림판을 이용한 서명 기능등을 제공합니다.



## 의연

### 개요

- 병원 - 환자 - 약국을 이어주는 플랫폼입니다. 이 중 환자분들께서 처방전을 받고 약국에 요청하는 부분을 만들었습니다.

### 플랫폼

- Web (HTML / CSS / JS) - 환자 플랫폼. 모바일/PC 별개작업
- 안드로이드 / iOS에 패킹하여, 일부 기능 (카메라 활용 등)은 네이티브 앱 코드로 작성되어있습니다.

### 특이 기능 목록

- 회원가입 및 로그인
  - 자체 로그인 (일반 로그인)
  - 소셜 로그인
    - 페이스북
    - 구글
    - 네이버
    - 카카오톡
- 하이브리드 앱
  - 처방전 이미지 암호화 및 첨부
  - GPS 좌표를  네이티브 앱에서 추출한 후, 웹으로 전달하여 처리됩니다.
    - 웹 기반으로 불러오는것보다 훨씬 정교한 위치 추적이 가능합니다.
  - 쿠키 / 네이티브 앱 동기화
    - 단순 웹 쿠키만을 활용하지 않고 네이티브 앱과 수시로 동기화 하여 다양한 소셜 로그인을 안정적으로 진행합니다.



## 9watt

### 개요

- 전기세를 절약하는 방법을 기술적인 방법으로 제공하는 플랫폼 입니다.

### 플랫폼

- Web (HTML / CSS / JS)
- Server - Node.js, Spring

### 특이 기능 목록

- 웹사이트 크롤링
  - 전력 사용량 데이터를 받아오기 위한 크롤링 작업
    - 많은 양의 데이터를 동시에 크롤링 하기 위한 처리가 있었습니다.
- 차트 표현
  - 웹 차트를 활용해 전력량 및 절약 가능 금액 등을 차트로 표기합니다.







