# 마크다운 정리



## 1. 마크다운이란?

### - 텍스트 기반의 마크업 언어



## 2. 마크다운의 특징

### 1) text를 HTML로 변환

### 2) 오픈소스의 공식 문서를 작성

### 3) 개인 프로젝트 소개서로 활용



## 3. 마크다운 문법

### 1) Heading : 문서의 제목이나 소제목으로 사용

#### - # 의 개수에 따라 글자크기 조절가능 

### 2) List

#### - Odered List : 순서 (O)

#### - Unordered List : 순서 (X)

### 3) Fenced Code Block : 코드 블록은 backtic 3개를 활용하여 작성

#### - 코드 블록 안에 특정 단어를 명시하면 Syntax Highlighting 적용 가능

``` python
if True
	print(Hello, world!)
```

### 4) Link : url을 통해 링크를 작성

### 5) 이미지 :  url을 통해 이미지 사용

### 6) Table(표)

### 7) text 강조 - 굵게, 기울임

### 8) 수평선 : ***. ---, ___



## 4. Markdown 작성 시 사용 프로그램

### - https://typora.io/ 에서 다운받아 설치



# CLI 정리

## 1. CLI란?

- CLI, 커맨드 라인 인터페이스) 또는 명령어 인터페이스는 가상 터미널 또는 텍스트
  터미널을 통해 사용자와 컴퓨터가 상호 작용하는 방식을 뜻한다.



## 2. 디렉토리 관리

• pwd (print working directory) : 현재 디렉토리 출력

• cd (change directory) : 디렉토리 이동
• . : 현재 디렉토리, .. : 상위 디렉토리
• ls (list) : 목록
• mkdir (make directory) : 디렉토리 생성
• touch : 파일의 날짜와 시간을 수정(0바이트 빈파일 생성)



# Git 기초

## 기본 명령어

### 1. $ git init

- 특정 폴더를 git 저장소(repository)를 만들어 git으로 관리

### 2. $ git add file이름

- working directory상의 변경 내용을 staging area에 추가하기 위해 사용

### 3.$ git commit –m ‘<커밋메시지>’

- staged 상태의 파일들을 커밋을 통해 버전으로 기록

### 4. $ git status

- Git 저장소에 있는 파일의 상태를 확인하기 위하여 활용

### 5. $ git log

- 현재 저장소에 기록된 커밋을 조회



# 원격저장소 활용하기

## 1. 분산버전관리시스템

- 분산버전관리시스템은 원격 저장소(remote repository)를 통하여 협업하고,
  모든 히스토리를 클라이언트들이 공유
- 

## 2. 원격저장소 설정 명령어

### 1) remote 확인 : $ git remote -v

### 2) remote 추가 : $ git remote add <이름> [url]

### 3) remote 삭제 : $ git remote rm <이름>

### 4) remote url 변경 : $ git remote set-url <이름> [url]

### 5) remote 이름 변경 : $ git remote rename <이름> <새이름>

### 6) $ git clone <원격저장소주소>

### 7) $ git push <원격저장소이름> <브랜치이름>

### 8) $ git pull <원격저장소이름> <브랜치이름>

