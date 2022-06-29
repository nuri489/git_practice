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

  > 변경된 사항을 이력에 추가함
  > git commit -m "ASD" 로 ASD라는 코멘트를 남길 수 있음

- git remote add origin 주소 : 원격 저장소의 주소를 저장함

  > 깃허브 저장소의 주소를 저장함

- git push origin master : 저장된 저장소의 주소로 변경된 사항을 전송함

- git clone 리포주소 : 해당 주소의 저장소 복사하여 가져옴
  > 저장소에 존재하는 파일들을 가져온다.
  > 새파일 열기 -> Git 리포지토리 복제 선택
  > 또는 터미널에 해당 명령어 입력

- git pull origin master : origin 저장소의 master 브랜치를 가져옴
  > clone은 초기 다운로드에 사용되고, pull은 업데이트 하는데 사용됨
  > 다른 사람과 협업을 할때 다른 사람이 해당 파일을 업데이트하면 그 업데이트 사항을 가져옴
  > ㅁㅇㅁㄴㅇ
