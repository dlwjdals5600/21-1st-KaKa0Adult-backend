# 21-1st-KaKa0Adult-backend

## KaKa0Adult 프로젝트 Back-end 소개

- 국내 최대소셜네트워크 카카오톡의 캐릭터를 만날 수 있는 [카카오프렌즈샵](https://store.kakaofriends.com/) 클론 프로젝트
- 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

### 개발 기간

- 개발기간 : 2021/06/07 ~ 2021/6/18


### 데모 영상

*추후 추가*

<br>

## 사용 기술 및 구현 기능


### 사용 기술 및 tools
> - Front-End : <img src="https://img.shields.io/badge/ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=React&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=React-router&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/sass-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>
> - Back-End : <img src="https://img.shields.io/badge/Python 3.8-3776AB?style=for-the-badge&logo=Python&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Django 3.2.4-092E20?style=for-the-badge&logo=Django&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Mysql 8.0-4479A1?style=for-the-badge&logo=Mysql&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/PyJWT 2.1-000000?style=for-the-badge&logo=JsonWebTokens&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Bcrypt 3.2-338000?style=for-the-badge&logo=PyJWT&logoColor=white"/>
> - ETC : <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"/>&nbsp;<img src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=Trello&logoColor=white"/>

<img width="1859" alt="스크린샷 2021-06-18 오전 7 28 39" src="https://user-images.githubusercontent.com/8219812/122530429-6cbe2700-d059-11eb-98e9-bdb8eebd4d94.png">

[AQueryTool(pw:bup04w)](https://aquerytool.com:443/aquerymain/index/?rurl=5a275d62-5fd7-44b5-ad51-f9ba875ceb01)

### 구현 기능

#### Users app

- `bcrypt`를 이용한 비밀번호 암호화
- `JWT`를 이용한 User정보 토큰발생
- 상품을 좋아요 할 수 있는 기능 및 제거
- user의 좋아요 상품리스트 제공

#### Products app
- 조건에 맞게 쿼리파라미터를 받아서 `Q객체`를 이용한 상품 필터링 및 정렬 (신상품, 인기상품, 검색, 카테고리, 캐릭터)
- 쿼리파라미터를 이용한 페이징 기능
- 한 개의 상품에 대한 상세 정보 제공

#### Orders app
- 장바구니 추가, 삭제, 업데이트 기능
- user의 장바구니에 담긴 상품리스트 제공
- 장바구니에서 결제 `transaction`을 이용한 데이터의 무결성을 유지하도록 구현

<br>

## Reference

- 이 프로젝트는 [카카오 프렌즈삽](https://store.kakaofriends.com/kr/index) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
