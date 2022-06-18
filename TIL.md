##### 2022-06-18 

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



##### *Big Data AI Service Dev*

* ADsP 강의 
  * 1과목 / 2과목 / 3과목 & R
  * 기출문제 
  
* Python Machine Learning Pandas Data Analytics - SH, Oh

* 인공지능 기초수학 강의 / 완성코드

  


##### [Study] 자료구조와 알고리즘
* 01.알고리즘 기초

* 02.기본 자료구조와 배열

* 03.검색 알고리즘

* 04.스택과 큐

* 05.재귀 알고리즘

* 06.정렬 알고리즘
  * 06-8 힙 정렬
  * 06-9 도수 정렬
  
* 07.문자열 검색

* 08.리스트

* 09.트리 

  


##### 모두의 알고리즘 with 파이썬
* 첫째마당 / 둘째마당 / 셋째마당

  


##### 모두의 데이터 분석
* 01.기온 데이터 분석
* 02.보충수업

  


##### Big Data Analytics 


##### Multi Campus Python Programing
* 기본
* 중급(실무)
* 응용
* 강의 (Prof. Dr Will 양진욱)
  * 변수, 연산자
  * 조건문, 반복문
  * 주피터 노트북 익히기
  * 분기문, 반복문
  * 파이썬 자료구조
  * 파이썬 문자열
  * 함수와 모듈
  * 예외처리
  * 객체지향프로그래밍(상속, 오버라이딩)
  * 파일 입출력

* 완성코드-실전
  * 101.Numpy
  
  * 102.Pandas
  
  * 103.Matplotlib, seaborn, folium
  
  * 104.판다스 활용 데이터 분석
  
  * 105.기술통계
  
  * 106.???
  
  * 107.Time_series
  
  * 108.차원 축소
  
    


##### Multi Campus Python Practical Biz
* biz_01 python_basic
* biz_02 pandas
* biz_03 web crawling_basic
* biz_05 instagram_crawling



##### 바로써먹는 데이터 분석

* 1부 / 2부 / 3부 




##### 파이썬 자습 (땀!!!)
* [점프 투 파이썬](https://wikidocs.net/book/1) 
* [초보자를 위한 파이썬 300제](https://www.wikidocs.net/book/922)