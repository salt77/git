## git-usage

### 명령어

#### 로컬 저장소 생성
    git init
#### 원격 저장소 클론
    git clone {url}
#### 로컬 저장소에서 add 하기
    git add {file} or *
#### 로컬 저장소에서 commit 하기
    git commit -m "{커밋 내용}"
#### master branch에 push 하기
    git push origin master
#### 원격 저장소 추가하기
    git remote add origin {url}
#### 원격 저장소에서 로컬 저장소로 pull 하기
    git pull
#### 두 저장소 병합 허가 옵션
    git pull –allow-unrelated-histories
#### 원격 저장소 제거
    git remote remove origin
#### 파일 삭제
    git rm {file} or git rm --cached {file}
