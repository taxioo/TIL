# GIT HUB

- rlt

## DO NOT

1. 홈 폴더를 리포로 만들기
2. 리포안에 리포 만들기
3. github 계정명은 가능하면, 대문자 없이 깔끔하기 지을것

## git pracite

git을 직접 사용해 봅시다!

## 저장소 초기화 하기

```
$ git init
```



## 저장소를 일반 디렉토리로 되돌리기

```
$ rm -rf .git
```



### STAGE에 올리기(Staging)

특정 파일만 스테이지에 올리기

```
$ git add <filename>
```

현재 위치의 모든 파일을 스테이지에 올리기

```
$ git add .
```

### commit을 통해 스냅샷 저장하기

```
$ git commit -m "MESSAGE"
```

### 현재 상태 확인하기

```
$ git status
```

- 빨간색으로 표시되는 파일은 commit 에 포함되지 않음
- 초록색으로 표시되는 파일은 commit에 포함 됨
- 변경사항이 없는 파일은 표시되지 않음

### 커밋 로그 확인하기

```
$ git log
$ git log --oneline
```



- `git rm --cached file name`스테이지에서 내리기
- `git add` <file name> CCTV에 파일을 추가
- `git commit -m 'file name'` CCTV에 사진 찍음
- `git status`  현재 상태

- `ctrl+L`화면을 위로 올림
- `git check out 로그번호` 도르마무ㄱㄷㄴ새

## git의 기초

**working directory(working tree)**

- 분장실  = git add

**stage**

- 촬영장 = git commit -m

**commits**

- 결과물 모음



## Email

- Gmail => github 가입 =>