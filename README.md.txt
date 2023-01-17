git test

inha University

-git status
-git status(현재 깃이 관리하고 있는 로컬리포지토리(작업폴더)의 상태를 보여줌)
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md.txt


여기서 언트랙티드(Untracked files:) 파일즈 라는 문구는 깃이 처음보는 파일이 등장했다!

-git add README.md(md파일을 스테이지에 올림)

-git commit-m "day02 first" (현재 스테이지에 올라와 있는 md파일을 커밋)

초기 사용자 및 이메일 등록
- git config --global user.email "susung462@gmail.com"
- git config --global user.name "study"