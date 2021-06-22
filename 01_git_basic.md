# Git basic

git의 기초를 배워요



## Warning

1. Home 폴더를 lifo로 업그레이드 하지 않는다

2. lifo안의 폴더에서 `git init`을 하지 않는다

   (lifo안에 lifo를 두지 않는다)



## 저장소 초기화 하기

`$ git init`

저장소를 일반 디렉토리로 되돌리기

`$ rm -rf .git`

.git 폴더 강제 제거

`git status`

현재 git 상태 확인

`git log`

commit log 확인

`git commit -m 'message'`

message 추가

`git add`

변경된 파일 commit

## stage에 올리기

`git add <filename>`

현재 위치의 모든 파일을 스테이지에 올리기

`git add`

`$ git add`

## commit을 통해 스냅샷 저장하기

`git commit -m "message"`



## 현재 상태 확인하기

- 빨간색으로 표시되는 파일은 commit에 포함되지 않음
- 초록색으로 표시되는 파일은 commit에 포함됨
- 변경사항이 없는 파일은 표시되지 않음



## 커밋 로그 확인하기

`$ git log`

