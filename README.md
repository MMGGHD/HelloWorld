# Git 명령어

## Git 사용자 등록하기

- git config --global user.name "MMGGDH"
- git config --global user.email "tldmseogus@naver.com"

## Git 시작하기

- git init (폴더 관리)
- git add . (변경 사항)
- git commit -m "최초 커밋"

## Github 연결하고 업로드하기

- git remote add origin 주소
- git push origin master

## 다시 업로드하기

- 소스코드 변경
- git add .
- git commit -m "(변경내용)"
- git push origin master

## 잘안될때 해결법
- git remote -v (연결 주소를 확인)
- git remote rm origin (연결주소를 삭제)
- 이후 다시 연결하기