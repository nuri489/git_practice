# Git Practice

---
### 배운 명령어들

- mkdir : 폴더 생성

- cd : 이하의 디렉토리로 이동

- touch : 파일 생성

- git init : 저장소 만들기

  > 해당 디렉토리에 저장소를 만든다.

- git add : 현재 상태 추적

  > 파일의 변경사항을 추적 함
  > git add . 로 해당 디렉토리의 모든 파일의 상태를 추적함

- git commit  : 현재 상태 저장

  >- 변경된 사항을 이력에 추가함
  >- git commit -m "ASD" 로 ASD라는 코멘트를 남길 수 있음

- git remote add origin 주소 : 원격 저장소의 주소를 저장함

  >-  깃허브 저장소의 주소를 저장함
  >-  git pull에서 사용될 주소

- git push origin master : 저장된 저장소의 주소로 변경된 사항을 전송함

- git clone 리포주소 : 해당 주소의 저장소 복사하여 가져옴
  >-   저장소에 존재하는 파일들을 가져온다.
  >-   새파일 열기 -> Git 리포지토리 복제 선택
  >-   또는 터미널에 해당 명령어 입력

- git pull origin master : origin 저장소의 master 브랜치를 가져옴
  > - clone은 초기 다운로드에 사용되고, pull은 업데이트 하는데 사용됨
  > - 다른 사람과 협업을 할때 다른 사람이 해당 파일을 업데이트하면 그 업데이트 사항을 가져옴
  > ㅁㅇㅁㄴㅇ

- git diff : 커밋과 브랜치 사이의 다른점을 보여줌
  >- 

- .gitignore : Git 버전 관리에서 제외할 목록을 지정
  >- .git 폴더와 같은 경로에 폴더를 만듬
  >- 그 폴더 안에 공유하지 않을 파일을 넣음
  >- gitignore.io 사이트를 이용 할 수 있음

- git rm -r --cached . : 현재 리포지토리의 캐시를 모두 삭제함
  >- 이미 존재하는 파일에 대한 추적을 삭제함
  >- git add . 를 통해 .gitignore 에 써넣은 목록을 제외한 모든 파일들을 다시 추적하게 함

- git branch A : A라는 브랜치 생성함
  >- 위험부담이 있는 작업이 있을 때 새로운 브렌치를 만들어서 마스터와 구별된 작업을 수행하고 
  >- git log --oneline 에서 HEAD -> master 는 

- git switch A : A로 head를 이동함?
  >- A에서 작성한 내용은 B라는 브랜치에선 보이지 않음
  >- 단 마스터에서 작성한 내용은 A,B 상관없이 보임
  >- git switch -c B 로 B라는 브랜치 생성과 동시에 B로 헤드를 이동 가능함