# Git-Study
깃 강의 내용 정리
---
* Git 이란?
  1. 버전 관리를 위한 툴.
  2. Git 을 이용하여 버전 간 소스 코드를 비교할 수 있음.
  3. 실행 전 단계로 돌아갈 수 있음.
 
##### - 필요한 리눅스 명령어.
##### 1. pwd : print working directory, 현재 작업중인 디렉토리 보여주기
##### 2. cd : change directory, cd ? => ? 디렉토리로 이동
##### 3. ls : list, 현재 디렉토리 내의 정보 출력.
##### 4. mkdir : 디렉토리 생성.

---
##### - Git Bash 사용. 
###### (쓰는 이유 window 터미널(기본 powershell or 명령 프롬포트) 에서는 ls가 안먹힘. git은 Linux를 만든 사람이 만들었기에 Linux기반의 명령어 사용.)
###### (즉, 윈도우에서도 리눅수 명령어를 사용할 수 있기에 git bash를 사용.)
##### 1. git init으로 저장소 등록. (이때 가능하면 사용자 이름, 폴더 이름 등은 영어로만, 폴더 이름, 파일 이름에 띄어쓰기 
##### 2. 초기 권한 설정
    git config --global user.name "사용자 이름"
    git config --global user.email 유저@이메일.com
    git config --global core.auticrlf true
###### global이 아닌 project, system등으로 사용자를 config할 수 있다.
###### Window에서는 줄바꿈이 CRLF, MAC에서는 LF로 두개가 충돌이 나기 때문에, autocrlf를 한다. ( 눈으로 보이지 않는 오류라 찾기 힘들다.)
##### 3. 
---
##### - 용어 정리.
##### 1. git pull 저장소에 있는 것들을 땡켜오는 것. (fetch + merge)
##### 2. 콜론이 있을 때, q를 누르면 비상 탈출. ( ex. 화면 상에서 문서를 볼 때 화면에 다 나오지 않으면 화살표를 통해 문서를 끝까지 볼 수 있으며, q를 누를 시 문서에서 나가짐.)
##### 3. vim : 파일을 만들거나 파일을 볼 때 사용. (ex. vim text.txt 시 text.txt가 있으면 파일을 열게 되고 없으면 파일을 생성 후 열게 된다.)
###### vim 시 입력 모드는 i(insert 약자), 명령 모드(명렁 사용 시 항상 콜론 ":" 입력 후 사용. ex :w [저장] , :q [나가기] , :wq [저장 후 나가기])는 esc 를 누르면 됨.
###### vim을 비정상적으로 종료시 해당 디렉토리에 swap파일이 생긴다.

