# EggplantMarket

>배포 URL: https://eggplant-market.netlify.app</br>id: eggplant@market.com <br>pw: 123123123
<br />

## 팀원 소개
|**박재영**|**안지원**|**이보경**|**이예지**|
| :------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img width="180" height="210" alt="jyp" src="https://user-images.githubusercontent.com/121578822/249660606-75372b99-49e0-4408-bdce-4dfb6145a070.png"> | <img width="180" height="210" alt="jiwon" src="https://user-images.githubusercontent.com/121578822/249660632-b20fd129-0e96-4558-82d4-44c8c3d8f19d.png"> | <img width="180" height="210" alt="bokyung" src="https://user-images.githubusercontent.com/121578822/249660143-c577ac7b-a4bf-4345-a209-0a481b3be82b.png">|  <img width="180" height="210" alt="yeji" src="https://user-images.githubusercontent.com/121578822/249660666-8c603422-ab8b-4ed8-b520-efbc5628ba5a.png"> |
| [ GitHub ](https://github.com/jypark38) | [ GitHub ](https://github.com/jiwon903) | [ GitHub ](https://github.com/ebokyung) | [ GitHub ](https://github.com/yejilee0714)|

<br />

## 목차

1. [프로젝트 주제 및 목표](#intro)
2. [기술 스택](#technology)
3. [역할 분담](#role)
4. [작업 관리](#task)
5. [주요 기능](#mainFunction)
6. [프로젝트 구조](#tree)
7. [페이지 기능](#pageFunction)
8. [개선사항](#improvements)
9. [느낀점](#impression)
10. [리팩토링 *](#refatoring)

<br />

## <span id = "intro">1. 프로젝트 주제 및 목표<span>
### [프로젝트 설명]

- ...

### [프로젝트 목표]

- 프로젝트 목표 1 - 웹접근성 고려 (고대비테마, 키보드 접근성)
- 프로젝트 목표 2 - 코드 완성도보다는 작동을 중심,
- 프로젝트 목표 3 - 시맨틱 마크업

<br />

## <span id = "technology">2. 기술 스택<span>
<table>
<tr>
 <td align="center">사용 기술</td>
 <td>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">&nbsp 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">&nbsp 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">&nbsp 
  <img alt="SASS" src ="https://img.shields.io/badge/SASS-cc6699.svg?&style=for-the-badge&logo=Sass&logoColor=white"/>&nbsp 
 </td>
</tr>
<tr>
 <td align="center">협업</td>
 <td>
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/>&nbsp
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/>&nbsp 
    <img src="https://img.shields.io/badge/Notion-5a5d69?style=for-the-badge&logo=Notion&logoColor=white"/>&nbsp
    <img src="https://img.shields.io/badge/Discord-4263f5?style=for-the-badge&logo=Discord&logoColor=white"/>&nbsp 
    <img src="https://img.shields.io/badge/Figma-d90f42?style=for-the-badge&logo=Figma&logoColor=white"/>&nbsp  
 </td>
</tr>
<tr>
 <td align="center">IDE</td>
 <td>
    <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white"/>&nbsp
</tr>
</table>

<br />

## <span id = "role">3. 역할 분담<span>
### <<추후 추가 예정>>

### 공통 담당
- splash 페이지, 로그인 페이지, 회원가입 페이지

<br />

## <span id = "task">4. 작업 관리<span>

### [작업 관리]
- [ 🔗issues ](https://github.com/FRONTENDSCHOOL5/final-19-EggplantMarket/issues)를 사용하여 진행도와 상황을 꾸준히 공유
<img width="450" src="https://user-images.githubusercontent.com/121578822/249673691-ddf9959e-bb98-467e-a98d-1cb0831304f2.png">

### [프로젝트 기간]
- 총 개발 기간 : 2023.06.01 ~ 2023.06.27
- 프로젝트 기확 단계 : 2023.06.01 ~ 2023.06.07
- 마크업 구현 : 2023.06.08 ~ 2023.06.16
- 기능 구현 : 2023.06.17 ~ 2023.06.26
- 리팩토링 : 2023.06.23 ~ 2023.06.28

<br />

### [Git flow]
[놀고먹고십구 협업플로우.pdf](https://github.com/FRONTENDSCHOOL5/final-19-EggplantMarket/files/11902046/default.pdf)

<img width="450" src="https://user-images.githubusercontent.com/121578822/249664354-ded53ca2-78d9-46b7-8359-c0503be4350c.png">

<img width="450" src="https://github.com/FRONTENDSCHOOL5/final-19-EggplantMarket/assets/90684277/707d808d-1c19-4a61-9b4f-4489e4a5d2fb">

<br />

### [커밋 컨벤션]
- Git commit message
    - `#이슈번호 <아래컨벤션> : <커밋내용>`
```
- add : 새로운 기능 추가
- fix : 버그 수정(단순 수정 X), 충돌 해결
- docs : 문서 수정
- chore : 코드의 논리에 영향이 없는 작업. 변수명 변경 등등
- design : 마크업 및 디자인 구현, 변경
- rename : 파일 이름의 변경 or 파일의 이동
- remove : 파일의 삭제
- refactor : 리팩토링
- test : 테스트 관련 코드 추가 및 삭제 등
- comment : 필요한 주석 추가 및 변경
```
<img width="450" src="https://user-images.githubusercontent.com/121578822/249673654-77ff2d0d-7617-4bcd-b0b9-09211d2d143b.png">

<br />

### [코드 컨벤션]
- 들여쓰기 4칸
- prettier 사용하지 않음
- 시맨틱 마크업으로 작성하기
- JS : 변수 ⇒ 카멜 케이스 / 클래스 ⇒ 파스칼 케이스
- 의미 있는 변수명 사용하기, 함수명은 동사로 시작하기,  class명은 형태 + 의미 + 상태


<br />

## <span id = "mainFunction">5. 주요 기능<span>
- 로그인 / 회원가입
    - 로그인
    - 회원가입
    - 유효성 검사
    - 프로필 설정
- 피드
    - 게시글 목록 - 목록형/앨범형
- 검색
    - 유저 검색
- 게시물
    - 게시물 작성 / 수정 / 삭제
    - 댓글 게시 / 삭제
    - 이미지 업로드 / 수정
- 채팅 (마크업만 진행)
    - 채팅 리스트
    - 채팅창
- 마이 프로필
    - 로그아웃
    - 프로필 수정
    - 팔로우 / 팔로잉
- 유저 프로필
    - 팔로우 / 팔로잉
<br />
<img width= "800" src="https://user-images.githubusercontent.com/121578822/249671612-68272f12-e7e1-4f6b-bea3-a5f3dcfd4bff.png">

<br />

## <span id = "tree">6. 프로젝트 구조</span>
- assets/ : 이미지, 파비콘, 아이콘 등
	- sprites : 이미지 스프라이트만 따로 보관

- css/ : 컴파일된 scss 및 css 디렉토리
  - reset.css : 기본 리셋과 공통으로 사용되는 스타일 모음 파일

- html/ : html 디렉토리
  - component : 버튼, 헤더, 푸터 등 컴포넌트 마크업 모음 파일
  - "htmlname".html 으로 작성

- js/ : html 디렉토리의 html과 매칭되는 JS 디렉토리. 
  - common.js : 공통으로 사용되는 함수가 등록된 파일
  - modal.js : 모달 관련 js 파일
  - theme.js : 기본/고대비 테마 전환관련 js 파일
  - "htmlname".js 으로 작성

- scss/ : html 디렉토리의 html과 매칭되는 scss
  - _mixin.scss : 믹스인 모아두기
  - _variable.scss : 변수들 모아두기
  - "htmlname".scss 로 작성
    - 필요시 mixin, variable 임포트
    - ex) @import "mixin";

```bash
기본포맷
├── README.md
├── 📁 assets
│   ├── basic-profile.png
│   ├── favicon.ico
│   ├── 📁 icon 
│   ├── 📁 logo
│   ├── 📁 sprites
│   └── 📁 symbol
│   ├── og(1400x630).png
│   ├── og(800x400).png
├── 📁 css
│   ├── ...
│   ├── reset.css
│   └── splash.css
├── 📁 font
├── 📁 html
│   ├── 📁 component
│   │   ├── button.html
│   │   ├── component.html
│   │   ├── footer.html
│   │   └── header.html
│   │   └── post.html
│   ├── 404.html
│   ├── chat_list.html
│   ├── chat_room.html
│   ├── home_search.html
│   ├── home.html
│   ├── join_membership.html
│   ├── login_email.html
│   ├── login.html
│   ├── post_detail.html
│   ├── post_upload.html
│   ├── product_upload.html
│   ├── profile_follower.html
│   ├── profile_following.html
│   ├── profile_info.html
│   └── profile_modification.html
├── index.html
├── 📁 js
│   ├── chat_room.js
│   ├── common.js
│   ├── footer.js
│   ├── contrast.js
│   ├── 📁 fetch
│   │   └── fetchRefact.js
│   ├── follower.js
│   ├── following.js
│   ├── home.js
│   ├── home_search.js
│   ├── index.js
│   ├── join.js
│   ├── login_email.js
│   ├── modal.js
│   ├── postDetail.js
│   ├── postUpload.js
│   ├── productUpload.js
│   ├── profile_info.js
│   ├── profile_modification.js
│   ├── scrollFetch.js
│   └── setProfile.js
├── naver58620a79d9c9b9f251caee0753f0748c.html
├── robots.txt
└── 📁 scss
    ├── _variables.scss
    ├── _mixin.scss
    ├── 📁 components
    │   ├── button.scss
    │   ├── comment.scss
    │   ├── footer.scss
    │   ├── modal.scss
    │   ├── skip_nav.scss
    ├── 📁 pages
    │   ├── 404.scss
    │   ├── chat_list.scss
    │   ├── chat_room.scss
    │   ├── home_search.scss
    │   ├── home_withoutfollowers.scss
    │   ├── join_membership.scss
    │   ├── login_email.scss
    │   ├── login.scss
    │   ├── post_detail.scss
    │   ├── post_upload.scss
    │   ├── product.scss
    │   ├── profile_follow.scss
    │   ├── profile_info.scss
    │   ├── profile_modification.scss
    │   ├── profile_productlist.scss
    │   └── profile_view.scss
```
<br />

## <span id = "pageFunction">7. 페이지 기능</span>
### 1) 홈
| [로그인] | [회원가입] |
|:-:|:-:|
|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249665809-abbc724d-38f1-4158-b1da-26b64ed1f8fb.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249662306-e5967968-53d8-40e4-aded-2b98b447ff78.gif">|



| [채팅] | [검색] | [홈 화면] |
|:-:|:-:|:-:|
|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249662948-ff125e34-4ee2-4145-af51-98ac3f343bc6.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249662478-633851aa-ac23-4ea4-b885-d4029b9c904f.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249662437-47e5ef04-e686-4062-816c-5961a5ae65b7.gif">|

<br />

### 2) 게시글
| [게시글 업로드] | [게시글 수정] | [게시글 상세] |
|:-:|:-:|:-:|
|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249662966-d872e11d-b5e3-4407-8e3c-63878295f232.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249663151-af559480-c407-4bd5-8097-e3ad7a95f5b5.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249663004-036a38db-c469-4820-82e3-86bb88b0874b.gif">|

<br />

### 3) 상품 판매
| [상품 등록] | [상품 수정] | [상품 삭제] |
|:-:|:-:|:-:|
|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249662871-a85cc4a4-0172-4961-a937-4c1fbd63d6af.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249663036-af2a7c20-63ad-4c55-8777-2ba74969d04f.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249663121-19a078fd-f995-4810-9307-762dae15d4a2.gif">|

<br />

### 4) 프로필
| [나의 프로필] | [나의 팔로우/팔로잉 목록] | [다른 사람의 팔로우/팔로잉 목록] |
|:-:|:-:|:-:|
|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249662530-f0e857d3-2052-4048-b47d-bf3503817031.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249663065-f427e065-dc25-4bfb-861b-6aae903e73d5.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249662624-2f997b7f-fe9d-4ab9-9805-df6e317039ec.gif">|

<br />

### 5) 고대비 테마
| [고대비테마 적용] | [다시 라이트모드로] | [고대비 상품 등록] |
|:-:|:-:|:-:|
|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249663799-bd5e9eae-04de-48cd-b1f4-819c51cb2771.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249663764-3d25fd45-9519-41a8-a3e1-7a32b93f0afa.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249663840-aa9cb09f-5fc1-4175-8949-c3475792a18b.gif">|

<br />

### 6) 키보드 접근성
| [Tab으로 focus 이동] | [skip navigation] |
|:-:|:-:|
|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249664199-d94768c9-7b5b-4e01-9a58-9015a502c755.gif">|<img width="390px;" src="https://user-images.githubusercontent.com/121578822/249664245-f33f44a2-893c-4df6-bfd3-5fc27d306d40.gif">|

<br />

## <span id = "improvements">8. 개선사항</span>
- 시멘틱 마크업 추가개선
- 성능보다 구현을 중심으로 짠 코드
- 반복되는 api 통신 코드 통합
- 터치스크롤 개선
- 게시글 수정시 이미지 여러개 첨부 기능 버그
- 키보드 접근성 tab 버그 
- sass 공동작업 시간 부족해서 못함
- css 사용하듯이에서 그친 느낌 
- 이미지 최적화
- meta tag 사용

<br />

## <span id = "impression">9. 느낀점</span>
<br />

## <span id = "refatoring">10. 리팩토링</span>

[기간]

[리팩토링 목표]
