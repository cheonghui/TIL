## Git - Github 연결

- User

​	내 컴퓨터의 git과  github 계정을 연결 (최초 1회 진행)

​	`git config --global user.name '이름'`

​	`git config --global user.email '이메일 ID'`

- 확인하기

​	`git config --global user.name` 

​	`git config --global user.email` 

---

​	`git init` git 시작

​	`git remote add origin <url> `  repository에 연결

​	↳ `git remote`  



​	`touch README.md`  마크다운 파일을 생성

​	↳ `ls`  파일이 잘 만들어졌는지 확인

​	`git add .`  모든 파일 staging area에 올리기

​	`git add <file_name>`  파일 staging area에 올리기

​	↳ `git status` 파일이 잘 올라갔는지 확인

​	`git commit -m '<commit message>'`  변경사항 남기기

​	↳ `git log --oneline`  commit 기록을 간단하게 볼 수 있음

​	`git push origin master`  github에 보내기

---





