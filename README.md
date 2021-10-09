<p><img src="https://user-images.githubusercontent.com/63541271/136643672-efd9aa21-06a7-468c-9e91-6d744c2268da.png"></p>
<br>
# Gaebalance
## Description
- 신발 브랜드 "뉴발란스"의 레이아웃을 토대로, 커머스 사이트 운영에 필수적인 기능 위주로 개발
- 개발 기간 : 2021.08.02 ~ 2021.08.13
- 개발 인원 : Front-end 3명 Back-end 3명
- 프로젝트 기간이 길지 않아 전체가 아닌 일부 기능에 집중해 기획했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백엔드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

## Demo Video
https://www.youtube.com/watch?v=UrwfBuVE4Yk

## What I've done
- Django 쿼리 메소드를 이용하여 장바구니 생성 기능 구현
- 동일 상품 및 동일 옵션에 대한 장바구니 추가 시, 상품 수량 업데이트 API 구현
- HTTP Request 와 Django Request 객체를 통한 사용자별 장바구니 조회 기능 구현
- RESTful API를 사용한 장바구니 수정 및 삭제 기능 구현
- 장바구니 POST API
![carts1](https://user-images.githubusercontent.com/63541271/129475737-f10fe503-e1bf-49d4-918a-5a0edf627d97.gif)
- 장바구니 DELETE API
![carts2](https://user-images.githubusercontent.com/63541271/129475740-7c268e97-39db-40cc-9066-028e0b3fb390.gif)

## Tech Stack
- Front-End : HTML5, React, sass, JavaScript 
- Back-End : Python, Django web framework, Bcrypt, PyJWT, MySQL
- Common : AWS(RDS/EC2), RESTful API
- Communication: Slack, Trello, Goolge Docs

## Entity Relationship Diagram
- Aquery url : https://aquerytool.com/aquerymain/index/?rurl=cbfa9880-57c7-4198-9ad2-75ef87548d29&
- Aquery password : 5624k4
- ERD as below
<img width="794" alt="Gaebalance_modeling" src="https://user-images.githubusercontent.com/63541271/136644213-0da9729b-2c82-44f3-955d-3a20537009cb.png">


## Reference
- 이 프로젝트는 뉴발란스 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.

