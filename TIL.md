##### ***1 Day, 1 Commit!***

##### ***Study Together, Share Together !***



##### 2022-06-19 google colab 코딩을 github로 옮기기 정리

``` 1.구글 드라이브 접속
1.Google Drive 접속 
2.Google colab 파일열기
3.메뉴중 파일 > GitHub에 사본저장 선택
4.colaboratory에서 GitHub에 승인을 기다리고 있습니다. 메시지 표시
5.GitHub 인증
6.GitHub 저장소(repository;레파지토리)와 브랜치(branch),파일경로가 표시되고, 변경사항 설정 메시지를 입력 commit하고 확인
7.GitHub에서 지정한 저장소에 코드파일이 추가되었음을 확인 - End -
```



##### 2022-06-18 git study 

``` git study $ git --version
$ git config --list
$ git config user.name
$ git config user.email 
$ git config --global core.autocrlf true
$ git reference 
$ mkdir work
$ cd work
$ ls -al
$ git init # .git 생성
$ open .git # 깃 레퍼지터리 기본적으로 master branch 가 생성됨 
$ rm -rf .git # 삭제하면 더이상 깃이 아님 
$ ls -al # 조회 
$ git status 
$ git config --global alias.st status
$ git st # 단축키 설정 이용
$ git config --h # 명령어..확인 가능       ```
```

```git 구조
git 구조
* working directory
* staging area
* .git directory
```

```$ remote pull / push 
$ remote pull / push
$ untracked / tracked 
$ unmodified / modified 
$ echo hello world! > a.txt
$ open .
$ ls
$ git status # git의 상태 조회 untracked files 가 표시되면
$ git add file.xxx # tacking 됨. 이후 commit 가능 
$ git add *.txt # tracking 됨. 이후 commit 가능 
$ git add a.txt b.txt # 여러가지 작성 가능
$ git rm --cached *  
staging area에서 working directory로 untracked 상태로 돌아온다.
$ git add * 모든 파일.. 
$ git add . 모든 파일.. 미묘한 차이 
$ echo *.log > .gitignore
$ ls -al # 보면... 확인가능하다 
$ git status 를 자세히 보자.. 
$ git diff working directory에 있는 내용만 보인다. 
$ git diff --staged # staging area에 있는 내용만 보인다.
$ git diff --cashed # staging area에 있는 내용만 보인다.
$ git difftool # vc로 working directory 버전 내용이 확인가능하다. 
$ git difftool --staged # vc로 staging area 버전 내용이 확인가능하다. ```
```

```.gitconfig 파일에서 설정 
[diff] 
	tool = vscode
[difftool "vscode"]
	cmd = code --wait --diff $LOCAL $REMOTE vscode 에서 볼 수 있다. 
```

```$ git commit -m 'second commit'  # 버전 생성 
$ git commit -m 'second commit' # 버전생성 커밋
$ git log  # 로그 확인 가능하다.
$ git commit -am # 모든 파일 커밋...```
```



##### *Big Data AI Service Development*

* ADsP   
* Python Machine Learning Pandas Data Analytics - SH, Oh
* 인공지능 기초수학 강의 / 완성코드
* [Study] 자료구조와 알고리즘

* 모두의 알고리즘 with 파이썬


* 모두의 데이터 분석

* Multi Campus Python Programing

* 바로써먹는 데이터 분석
* [점프 투 파이썬](https://wikidocs.net/book/1) 

* [초보자를 위한 파이썬 300제](https://www.wikidocs.net/book/922)