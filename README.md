## git-usage

### 순서대로 정리
#### 1. git init
    git init 명령어를 사용해서 로컬저장소 설정
#### 2. git add {file} or *
    원하는파일 또는 전체파일을 Upstate 함
#### 3. git commit -m {커밋할 내용}
    파일 커밋
#### 4. git remote add {원격저장소 이름} {원격저장소 URL}
    원격저장소 설정
#### 5. git push {원격저장소 이름} {브랜치 이름}
    끝
    

### 명령어

#### 로컬 저장소 생성
    git init
#### 원격 저장소 클론
    git clone {url}
#### 로컬 저장소에서 add 하기(Stage)
    git add {file} or *
#### 로컬 저장소에서 commit 하기
    git commit -m "{커밋 내용}"
#### master branch에 push 하기
    git push origin master
#### 원격 저장소 추가하기
    git remote add origin {url}
    git remote -v로 추가한 
#### 원격 저장소에서 로컬 저장소로 pull 하기
    git pull
#### 두 저장소 병합 허가 옵션
    git pull –allow-unrelated-histories
#### 원격 저장소 제거
    git remote remove origin
#### 파일 삭제
    git rm {file} or git rm --cached {file}
#### add한 파일들 Unstage로 변경
    git reset HEAD {file}
    파일명이 없다면 모든 파일 Unstage
#### commit 취소하기
    git reset HEAD^  //commit을 취소하고 해당 파일들은 Unstaged 상태로 변경
    git reset --mixed HEAD^  //위와 동일
    git reset HEAD~2  //마지막 2개의 파일을 취소
    git reset --soft HEAD^  //commit을 취소하고 해당 파일들은 staged 상태로 보존  
    git reset --hard HEAD^  //commit을 취소하고 해당 파일들을 삭제
#### commit 메세지 변경
    git commit --amend ""
#### 복사 및 붙여넣기
    Ctrl + Insert,  Shift + Insert
