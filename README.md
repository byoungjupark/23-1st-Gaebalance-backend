# 23-1st-Gaebalance-backend
## 개발란스 프로젝트 소개
- 신발 브랜드 뉴발란스 클론 프로젝트
- 프로젝트 기간이 길지 않아 전체가 아닌 일부 기능에 집중해 기획했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백엔드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

### 개발 인원 및 기간
- 개발기간 : 2021/8/2 ~ 2021/8/13<br>
- 개발인원 : 프론트엔드 3명 백엔드 3명

### 프로젝트 선정이유
- 깔끔한 디자인과 필터링하는 옵션이 여러개인 점이 매력적으로 다가와 진행하게 되었습니다.

### 데모 영상/이미지
https://www.youtube.com/watch?v=UrwfBuVE4Yk
![carts1](https://user-images.githubusercontent.com/63541271/129475737-f10fe503-e1bf-49d4-918a-5a0edf627d97.gif)
![carts2](https://user-images.githubusercontent.com/63541271/129475740-7c268e97-39db-40cc-9066-028e0b3fb390.gif)


## 적용 기술 및 구현 기능
### 적용 기술
- Front-End : HTML5, React, sass, JavaScript 
- Back-End : Python, Django web framework, Bcrypt, PyJWT, MySQL
- Common : AWS(RDS/EC2), RESTful API
- Communication: Slack, Trello, Goolge Docs

### 구현 기능
회원가입 & 로그인
- email,password 정규식 사용 => 회원가입 유효성 검사
- JWT 토큰 발행
- 회원가입 데코레이터

상품 리스트 페이지
- 상품 카테고리별 필터링 적용
- 4가지 기준(종류, 색상, 사이즈, 가격대)의 하위 기준을 다중 선택 가능한 필터링
- 필터링 결과 내에서 정렬 기능 구현

상품 상세 페이지
- 이미지 슬라이드
- 사이즈 옵션 구현
- 주문 리스트및 합계 구현

장바구니 
- 생성/조회/수정/삭제 기능
- 장바구니 개별 금액 및 총 주문 금액 표시

리뷰 (Backend)
- 생성/조회/수정/삭제 기능

## Reference
- 이 프로젝트는 뉴발란스 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.

