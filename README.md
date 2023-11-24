### Django와 Vue.js를 활용한 영화 커뮤니티 웹사이트
# 무비헤엄 🌊 🏊
![무비헤엄](https://github.com/Bada35/final-pjt/assets/103430344/f6942e41-419a-40ca-a3d3-4893f9deade4)


# 기획의도
지금 이 순간에도 수 없이 쏟아지는 영화의 바다에서  
저희는 어디로 향해야 할 지 길을 잃어갑니다.  
여러 영화 추천 사이트에서 선택을 위한 추천을 받아도,  
그 추천이 너무 많아 선택하지 못하는 모순적 상황을 막기 위해.  
그리고 각자의 좋아하는 영화, OST를 가지고 개개인의 바다를 만들며  
각자의 바다에서는 그 누구보다 여러분이 주인공이 됐으면 하는 바램에서 기획하게 되었습니다.

### 🤝팀원

| 이름   | 담당 영역                                                    | Github                        |
| ------ | ------------------------------------------------------------ | ----------------------------- |
| 유영준 | - 프론트엔드(30%) / 백엔드(70%)<br />- DB 모델링, 백엔드 데이터 로직 작성, 프론트엔드 디자인 정교화 | https://github.com/hluuy |
| 서지수 | - 프론트엔드(70%) / 백엔드(30%)<br />- 백엔드 데이터를 받아와 프론트엔드 기능 구현 및 디버깅, 테스트 | https://github.com/Bada35    |

## 개발일정
![개발일정](https://github.com/Bada35/final-pjt/assets/103430344/62c96fe8-d002-4507-aab1-38ace2ce94a8)


## 요구사항
- 영화 데이터
- 영화 추천 알고리즘
- API
- 커뮤니티

## 컴포넌트
![컴포넌트](https://github.com/Bada35/final-pjt/assets/103430344/5ab41c1c-dfd7-4b72-b57f-49ba5e74a563)


## ERD
![Untitled (1)](https://github.com/Bada35/final-pjt/assets/103430344/c4dede8e-fddc-443f-80e6-c512ac2768d0)



## 최초 목표 서비스 / 실제 구현 정도
| No. | 기능 | 기능 설명 | 구현도 |
| --- | --- | --- | --- |
| 1 | 로그인, 로그아웃, 회원가입 | 사이트 로그인, 로그아웃, 회원가입 기능 | ⭐⭐⭐⭐⭐ |
| 2 | 회원정보 수정 | 비밀번호, 이메일, 좋아하는 명대사, 프로필 이미지 변경 기능 | ⭐⭐⭐⭐ |
| 3 | 마이페이지 | 마이페이지 내 유저 정보, 좋아하는 영화 목록, 팔로워, 팔로잉 수, 작성한 리뷰 목록, 방명록 | ⭐⭐⭐⭐⭐ |
| 4 | 방명록 CRUD | 방명록 작성, 수정, 삭제 | ⭐⭐⭐⭐⭐ |
| 5 | 방명록 댓글 | 특정 방명록에 대한 댓글 작성, 삭제 | ⭐⭐ |
| 6 | 팔로우/팔로워              | 특정 유저 팔로우 / 언팔로우 기능                             | ⭐⭐⭐⭐⭐  |
| 7    | 팔로우/팔로워 조회         | 특정 유저 팔로우 / 팔로워 조회                               | ⭐⭐⭐⭐⭐  |
| 8    | 영화 OST                   | 마이페이지 내 설정한 영화 OST 재생, 멈춤                     | ⭐⭐⭐⭐⭐  |
| 8    | 영화 검색                  | 영화 검색                                                    | ⭐⭐⭐⭐⭐  |
| 9    | 영화 상세 페이지           | 특정 영화의 상세 페이지                                      | ⭐⭐⭐⭐⭐  |
| 10   | 영화 추천 알고리즘         | 파도타기를 통한 영화 추천                                    | ⭐⭐⭐⭐⭐  |
| 11   | 영화 좋아요                | 특정 영화 좋아요 / 좋아요 취소                               | ⭐⭐⭐⭐⭐  |
| 12   | 영화 좋아요 조회           | movie_id를 통한 좋아요한 유저 조회 / user_id를 통한 좋아요중인 목록 조회 | ⭐⭐⭐⭐⭐  |
| 13   | 영화 리뷰CRUD              | 특정 영화에 대한 리뷰 작성, 수정, 삭제                       | ⭐⭐⭐⭐⭐  |
| 14   | 파도탄 영화 키워드         | 파도탄 영화들의 장르와 키워드를 수치화해서 제공              | ⭐⭐     |
| 15 | 파도타기 | 연속적인 추천 영화 선택을 통한 개개인별 영화 취향 계산 | ⭐⭐⭐⭐⭐ |
| 16 | 미니홈피 | 미니홈피를 통해 개인화된 공간 제공 | ⭐⭐⭐⭐ |
| 17 | 다크모드 | 다크모드 |  |

## 영화 추천 알고리즘
- 입력된 영화에 대해 5가지의 추천 영화 목록 출력해당 추천 영화 목록 중,  
  영화를 연속적으로 선택하는 과정을 통해  유저의 선호 장르를  수치화하여 제공

## 무비헤엄의 대표 기능
| No. | 구분 | 기능 설명 |
| --- | --- | --- |
| 1 | 파도타기 | 개인화된 영화 취향 제공 |
| 2 | 미니홈피 | 개인화된 공간 |

## 구현 과정에서 일어난 시행착오, 이슈 그리고 해결 방법

 - 지수
   - 깃 협업 - 정리해서 처리함 https://ssafybada.notion.site/Git-fcc085e334a74d7b8ed26437a457dae3?pvs=4
     브랜치로 나눠서 했는데 처음에만 좀 헤매었지 나중엔 서로 충돌도 안 나고 손 커밋할 필요도 없어서 좋았음
   - HomeView에 구현되어있던 SingInSingUp.vue(Login과 SignUp 버튼 & 모달)을 NavBar로 옮기면 1. 클릭해도 모달 안 닫힘 2. 오버레이 CSS 이상하게 적용 되는 문제 발생
     => 오버레이는 CSS로 z-index값을 올려주고, SinInSingUp은 App.vue에서 v-if로 렌더링함. App.vue는 처음 한번 렌더되면 라우터빼곤 안 바뀌어서 watch써서 값 변하는거 바로바로 적용시킴.
   - signup axios로 보낼때 필수값이 아닌 값을 null로 보내면 자꾸 400에러남 => 없는 값일때 아예 해당 값을 보내지 않으면 해결됨
   - userid로 띄웠던 홈페이지를 장고 api 수정하면서 nickname으로 띄우게하니까 nickname 수정해버리면 router 오류남
     => router를 user_id로 바꾸고 장고 api또한 user_id기준으로 바꾸면 해결됐을듯. 지금은 erd가 꼬이는 너무 큰 일이라 그냥 nickname 못바꾸게함
   - 회원가입 성공하면 모달 페이지 닫기 => 모달안 회원가입 성공하면 signup-success 에밋 보내기 기존에서 컴포넌트에 @signup-success="toggleSignupModal"
   
 - 영준
   - 반환되는 데이터 값 통일 : 일단 만들어야 한다는 생각에 모델을 유기적이지 못하게 만들었다. 사용할 필드를 특정하여 그것을 위주로 다시 모델링하여 해결하였다.
   - 팔로잉, 팔로워 꼬임 : 팔로잉과 팔로워 목록을 조회하는 기능을 구현하던 중, 서로 뒤바뀌며 나타나는 문제가 생겼었다. 그래서 처음부터 다시 만들었다.
   - 영화 DB 구축 : 처음에는 영화 관련된 모든 정보를 api를 통해 가져오려고 했었다. 하지만 의견을 나누다보니 비효율적이라고 판단했고, 영화의 기본 정보를 담고 있는 하나의 큰 DB를 만들게 되었다.
   - 회원 정보 수정 : 회원정보 수정에서 변경하고 싶지 않은 항목을 빈 칸으로 전달받게 되면 덮어씌어지는 현상이 발생했다. Vue와 협의하여 입력되지 않는 항목은 전달이 안되도록 하니 원하는 항목만 바꿀 수 있게 되었다.
   - Vue에 대한 이해도 부족 : vue에 대해 이해도가 부족하니 django에서 이런이런 데이터들만 사용이 될 것 같아서 반환해줬는데 사실 다른 무언가가 더 필요한 경우가 많았다. 앞으로 해결해야 할 문제라고 생각한다.

## 프로젝트를 끝 마치며,,(느낀 점, 아쉬웠던 점)

- 지수
  - 프로젝트 많이 해봤다고 생각해서 쉽게 생각했는데, 처음 해보는 Web관련 프로젝트라 그런지 생각보다 마음대로 진행되지 않았던 것 같습니다. 항상 모든 조원이 하는 분야를 대략적으로라도 아는 상태에서 역할을 맡았었는데 두 분야중 하나를 아예 모르는 중에 팀프로젝트를 진행함이 개인적으로 답답했던 것 같습니다. 
  - 처음에 분명 구현했던것인데도 나중에 기능이 많아지고 컴포넌트간 구조가 복잡해지니까 작은 것 하나 수정하는 것에도 많은 시간이 들었습니다. 다음에 같은 역할을 맡게 된다면 기능 구상과 컴포넌트간의 구조, 데이터 이동 경로를 구체적으로 확립한 이후 진행하고 싶습니다.
  - 좀 더 컴포넌트화 하고 싶었는데 prop과 emit, store 등에 익숙하지 못함에 vue파일 하나가 너무 복잡해진 것이 아쉽습니다. 배울 땐 이걸 왜 배울까 싶었던 비동기와 생명주기같은 이론들이 이래서 중요했구나 하고 깨닫는 계기가 되었습니다.
  - 기능 구현에 중점을 두다 보니 유저 개인화와 추천 알고리즘같은 프로젝트의 차별화에 힘을 못 쓴 점이 아쉬웠습니다.
- 영준
  - 사실 프로젝트가 시작되기 전부터 걱정이 많았다. "내가 프로젝트를 한다고,,?" django나 vue 둘 다 자신있는게 없었기 때문이다. 당연히 프로젝트를 진행하면서 내가 너무나도 부족하다는걸 뼈 저리게 느꼈다. 모델링부터 시작해서 데이터 반환, url 설정 등등. 팀원에게 미안할 정도로 삽질을 많이 했다. 첫 프로젝트이다 보니 몸에 힘 빡주고 의욕만 넘쳐났던 것 같다.  
  앞으로 있을 수 많은 프로젝트에서 어떻게 해야 할 지 이번 프로젝트를 통해 알 게 되었다.   
  특히 몸에 힘을 좀 빼는 것을 말이다. 나를 위해서라도, 팀원을 위해서라도. 
  그래도 '내가 좀 더 잘했더라면'이라는 아쉬움은 사라지지 않는다. 홀가분하긴 하지만 말이다.
