"토닥도닥 감정다이어리" 📚
-----------------
자신의 감정에 대해 잘 알고 계신가요?
<br/>
감정다이어리에서 자신의 감정을 사람들과 공유해보세요!

http://arasaka.shop/     

       
<br/>

1, 제작기간 & 팀원 소개 🫂
------------------
**- 2022년 01월 10일 ~ 2022년 01년 13일**

  - 김재진 : 메인페이지 포스팅 db 저장, 유저닉네임 불러오기
  - 나기탁 : 메인페이지 포스팅 불러오기, 삭제 기능 구현
  - 이규리 : 메인페이지 좋아요 기능 구현 
  - 장혜진 : 전체 페이지 css 로그인 + 회원가입  
<br/>
 
2.사용기술  📌
------------------
- bulma
- jina2
- JWT
- Flask
- mongodb
<br/>

3.실행화면 😄
------------------
https://youtu.be/pHiBgzgBV5k

<br/>


4.핵심기능 (요구사항) 🛠
------------------
**1. 로그인과 회원가입 기능**

- 아이디와 닉네임의 중복확인 가능 
- 비밀번호 추가 확인이 가능
- hash를 통한 비밀번호 암호화 가능 

**2. jina2언어 사용**

- 메인페이지에서 로그인한 사용자의 닉네임이 보이는 기능 구현 
- 파라미터로 넘기는 것보다 코드가 깔끔

**3. JWT토큰 사용**

- 발급 후에 쿠키로 저장을 하면서 서버와 클라이언트 쪽에서 손쉽게 전달되기 쉽다는 점에서 사용

**4. 좋아요 기능**

- db에 저장된 좋아요수 증가 
- 텍스트를 데이터로 받아서 어떤 포스트에 좋아요가 눌러졌는지 확인하는 기능

**5. 삭제 기능**

- 아이디를 데이터로 받으면 무조건 첫번째 게시글 부터 지워지는 문제를 텍스트를 데이터로 받아오면서 해결 
- 텍스트를 데이터로 받아서 포스트 별 삭제 기능 

**6. 로그아웃 기능**

- removecookie 코드를 통해서 마이토큰을 지워서 로그아웃 기능 구현 

<br/>

5.난관 😮‍💨
------------------
**1. 좋아요 버튼을 눌렀을때 누가 좋아요를 눌렀고, 누가 취소를 하는지에 대한 기능 구현 실패**
  
  : 좋아요수 증가 기능으로 변경

**2. 깃 허브에 올릴때마다 충돌하는 문제**
 
 : 아직 프로젝트의 크기가 작기 때문에 수정하는 부분이 겹쳐서 발생하는 문제 
  : 상대방의 수정코드 부분을 건드리지 않는게 최선

<br/>
<br/>


5.개인회고 🤫
------------------
