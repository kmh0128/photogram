마리아 db 설치
====

마리아 db란?
===

마리아db란 MySQL이 oracle로 인수되어 넘어가진 후에 라이센스에 대한 불확실성을 해결하기 위해 나온 관계형 데이터베이스이다.

설치
===

https://mariadb.org/

위 링크로가서 다운로드 클릭후 버전을 선택해서 다운을 해줍니다.

자신은 강의와 같은 10.5버전으로 다운을 했습니다.

![강의와 같은 10 5 버전](https://github.com/kmh0128/photogram/assets/100178951/c762b65d-fca3-49dd-85c0-663274ed12cf)

인스톨된 파일을 다운해주고

![다운로드](https://github.com/kmh0128/photogram/assets/100178951/4a3f575f-da7f-4e15-aac8-540c51c26f77)

![다운로드 (1)](https://github.com/kmh0128/photogram/assets/100178951/7113f25f-8105-4a82-b5c3-89cff045f08c)

![다운로드 (2)](https://github.com/kmh0128/photogram/assets/100178951/cd8d5bf6-37a0-41c0-83a8-ec1494470cdf)

동의를 해주면서 next를 눌러 진행해주고,

![마리아db 3307](https://github.com/kmh0128/photogram/assets/100178951/1bad6851-ea7e-431b-92e4-b94956968231)



저는 이전에 했던 쇼핑몰 프로젝트의 책에서 MySQL을 사용해서 거기서 사용했던 기본 포트번호 3306과 마리아db의 기본 포트번호가 같기 때문에

3307로 변경을 해주었습니다.

1-> Modify password for database user root

root 계정에 대한 비밀번호를 설정합니다.(꼭 기억해야됩니다.)

2 -> Enable access from remote machines for 'root' user

원격으로 MariaDB 'root' 계정 접근에 대한 설정

(이 문단에 대한 예 데스크탑에서 window 서버를 켜놓고 mar 노트북으로 접속 가능)

3 -> User UTF8 as default server's Charater set

서버 기본 문자열 인코딩을 UTF8로 설정합니다.


확인
==

이제 확인을 위해 작업관리자로 들어가서 서비스 탭 클릭후 mariadb를 찾아주면 실행되고 있는지 나옵니다.

![마리아 db 실행중](https://github.com/kmh0128/photogram/assets/100178951/50339415-7f5e-4e97-bec1-6faf59682efc)

그리고 실행 파일인 HeidiSQL 을 확인

![heeeee](https://github.com/kmh0128/photogram/assets/100178951/4b93be37-d8eb-45f6-8add-61700a8bafad)





강의 자료: 이지업 클래스 인스타그램 강의 -> https://easyupclass.e-itwill.com/course/course_view.jsp?id=27&rtype=0&ch=course

마리아db 다운 설정 영어 참고 자료 -> https://parkjh7764.tistory.com/123
