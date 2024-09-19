# 설치과정
1. git 프로그램을 Download하고 설치(default).
2. git을 설정하기 위한 workspace 폴더 생성.
3. gitHub 사이트에 접속하여 회원가입 및 로그인 진행.
4. 우측상단 "new Repository" 클릭.
    -내용을 입력하고 생성.
5. worksapce 폴더 내에서 "git Bash" 실행
6. 초기 설정
    : git  config --list (내용확인)
    : git config --global user.name "kdh.LP"
    : git config --global user.email "wh...@gmail.com"
    *Git은 commit 할 때마다, 이 정보를 사용
     (한 번 커밋한 뒤, 정보 변경 불가능)
7. 초기화
    - git init