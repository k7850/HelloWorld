# Git 명령어

## Git 로컬 컴퓨터에 사용자 등록하기
- git init
- git config --global user.name "k7850"
- git config --global user.email "k79357850@gmail.com"

## Git 시작하기

- git init
- git add .
- git commit -m "최초 커밋"

## Github 업로드하기

- git remote add origin 주소
- git push origin main

## 다시 업로드 법

- 소스코드 변경
- git add .
- git commit -m "변경내용적고"
- git push origin master

## 잘안될때 해결법

- git remote -v     (연결주소확인)
- git remote rm origin     (연결주소삭제, 하고 다시주소연결부터)