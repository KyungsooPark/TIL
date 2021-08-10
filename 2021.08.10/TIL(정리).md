# 깃허브 정리



## 1. 깃허브 branch 관련 명령어

### 1) git  remote -v : 원격저장소 확인

### 2) git pull origin master : 원격저장소 master branch의 커밋들을 가져옴

### 3) git push origin master :  로컬저장소의 master branch의 커밋들을 원격저장소로 저장함

### 4) git ignore : 특정 파일이나 확장자를 git에 올리지 않음

### 5) git checkout 브랜치이름 : 브랜치 이동

### 6) git checkout -b 브랜치이름 : 브랜치 생성&이동

### 7) git branch : 모든 브랜치 확인

### 8) git branch 브랜치이름 : 브랜치 생성

### 9) git merge 브랜치이름 : 해당 브랜치를 현재 브랜치로 병합

### 10) git branch -d 브랜치이름 : 브랜치 삭제



## 2. 협업 

### 1) Shared Repository Model

- Shared Repository Model은 동일한 저장소를 공유하여 활용하는 방식
- 초대 --> 수락 --> git clone -->  함께 pull & push로 공유하며 작업

### 2) Fork & Pull Model

- Fork & Pull Model은 Repository에 Collaborator에 등록되지 않고, Pull request를 통한 협업이 가능. Github 기반의 오픈소스 참여 과정에서 쓰이는 방식
- fork --> git clone --> 작업 후 push --> Pull Request --> Merge



