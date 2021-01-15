# git command 

> git 기초 명령어 정리



## 설정 

### init 

- `git init` 
- 폴더를 git으로 관리하기 위해 `.git` 폴더를 생성하는 명령어 
- 최초에 한 번만 실행하면 된다. 
- 그 내부, 하위 폴더까지 git이 관리를 해준다. 



### status 

- `git status`
- 현재  git의 상태를 출력
- whether it is modified, added ... 



### log 

- `git log` 
- 현재 쌓여 있는 commit history를 출력 
- 밑에서부터 하나 하나 쌓아서 출력해준다. 



### diff 

- `git diff` 
- 마지막 commit과 지금 working directory의 상태를 비교 



### remote add

- `git remote add <nickname> <address>`
- 원격저장소 주소를 등록





## 조작

### add 

- `git add <file_name>` 
  - `<file_name>` 에 `.`을 입력하면  전체 파일이 추가된다. 
- Working directory에 있는 파일을 Staging area (INDEX) 에 올림.  
- `status`를 통해 확인 가능 



### commit

- `git commit -m "commit_message"`
  - Staging area에 올라간 파일들을 스냅샷으로 저장 
- `git commit`  
  - Without `-m` , `vi` window will be popped up 
  - Need to activate "editing" mode - `esc` if you want to finish editing 
  - `:wq` ... for writing and quitting 



### push 

- `git push <원격저장소 이름> <올릴 브랜치 이름>`
  - `git push origin master` 
- Commit history를 원격 저장소에 업로드 



















