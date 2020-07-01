# HUFS_TimeTable

한국외대 학생들이 시간표를 구성하는데 도움이 되고자 한다. 
학생들을 학교 홈페이지에서 강의 리스트들로 구성된 표를 보고 직접 시간표를 만들어서 대조했어야 했다. 
이러한 불편함을 해소하고자 하였고, 이 프로젝트를 진행하게 되었다. 
학생들은 더 이상 강의를 하나씩 비교할 필요 없이,
1전공과 이중전공, 학년을 입력하게 되면 조건에 맞는 모든 강의들이 시간표 형태로 볼 수 있게 하고자 한다.

## Main.py를 실행하면 된다.

* 제한사항  

  * 사용자는 최소 1개의 전공을 입력하고, 다른 학과와 구분될 수 있게 입력을 한다. 
  (예를 들어, ‘경영’이 아닌 ‘경영학전공’ 또는 ‘경영학부’로 입력한다.)

  * 시간표는 전공 과목만 보여준다.

  * 강의평은 ‘에브리타임’의 아이디, 비밀번호를 입력해야 추가할 수 있다.


  * 네트워크가 연결되어 있으며, 페이지 소스가 0.5초 이내에 로딩될 수 있는 속도여야 한다.

 ~~* 사용자의 환경에 크롬(79.0 버전)이 설치되어 있어야 한다.
  >> 크롬 버전이 다르면 해당 버전 exe는 [여기](https://chromedriver.chromium.org/downloads)서 다운받을 수 있다.~~


* 실행 예시

> 학기를 입력해주세요 (Ex 20-1 or 20-여름) : 20-1

> 1전공, 2전공을 입력해주세요 (띄어쓰기로 구분), 종료(q 입력) : ELLT학과 융복합소프트웨어전공

> 듣고 싶은 수업의 학년을 입력해주세요 (띄어쓰기로 구분) : 2 3

> 강의 평가를 추가하시겠습니까? (에브리타임 로그인 필요, y/n) : n


#### 강의 시간표가 업데이트 되었다면 이전에 생성된 txt파일을 모두 지워주세요.
