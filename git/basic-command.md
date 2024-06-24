# Git command 

> git 기본 명령어 정리

## init
- 현재 위치에 `.git` 폴더를 생성 

``` bash
$ git init
```
## add
- Working directory => Staging area로 업로드 하는 과정 
- 여기서 . 이 의미하는 것은 현재 내 위치의 모든 파일과 폴더를 의미함
``` bash
$ git add .
```

## status
- 현재 git 상태 확인 
``` bash
$ git status
```

## commit
- staging area에 올라간 내용을 스냅샷 찍기
  - `m` 옵션을 통해 커밋메세지를 바로 입력 가능 

```bash
$ git commit -m "first commit(변화사항 기록)"
```

## remote add
- 원격저장소의 주소를 저장하는 명령어 

``` bash
$ git add {remote_name} {remote_url}
```

## push
- 원격저장소로 브랜치를 업로드 하는 명령어
```bash
git push origin master
git push {remote_name} {branch_name}
```