# Git이란?

분산 버전 관리 시스템

git != github

git 설치

vscode 설치

git은 **명령어**를 통해서 사용

GUI CUI (Graphic user Interaface)

powershell - 리눅스  유닉스 사용을 위해서

---

현재 위치의 폴더, 파일 목록 보기 ls-

현재 위치 이동하기 cd <path>

상위폴더로 이동하기 cd..

하위폴더로 이동하기 cd <파일이름>

폴더 생성하기 mkdir <name>

파일 생성하기 touch <name> "ㅁ"

삭제하기 

rm <name> 파일 삭제하기

rm -r <name> 폴더 삭제하기 



git 기본기

RacingGround 프로젝트 생성

Repository 특정 디렉토리를 버전 관리하는 **저장소**

**git init 명령어로 로컬 저장소를 생성해요**

racingground폴더에서 git bash 열어준다.

git init 입력

**.git 숨김폴더는 git으로 버전관리가 가능한 파일로 변함**

특정 버전으로 남긴다. => "커밋(commit) 한다."

> 3가지 영역으로 있다.  
>
> 1.Working Directory
>
> 내가 작업하고 있는 실제 디렉토리;
>
> untracked- git으로 부터 감시되고 있지 않음
>
> ->git add시 Staging Area로 넘어감
>
> 2.Staging Area
>
> 커밋으로 남기고 싶은, 특정 버전으로 관리하고 싶은 파일이 있는 곳;
>
> staged상태로 존재
>
> ->git commit시 Repository로 넘어감
>
> 3.Repository
>
> 커밋들이 저장되는 곳;
>
> committed상태로 존재 여기서 수정하면 또 modified 상태로 Working Directory로 이동한다.

git add - Staging Area로 넘어간다.

**git commit -m "commit_message" -  commit 상태에 대한 부연 설명** 
최대한 자세하고 나중에 알아보기 쉽게 메세지를 남겨놓는게 좋다!!!!!



**git add. -추적 되지 않은 모든 파일과 추적하고 있는 파일 중
				 수정 된 파일을 모두 Staging Area에 올려요.**

\*질문: 그럼 항상 git init한 디렉토리=로컬 저장소에 있는 모든 파일을
add 해줘야 하는 건가요?
=> 아닙니다. 보안상 중요한 내용들은 git으로 관리하지 않는 것이 좋다. 저장에 용이한 파일들만 저장한다.

git config --global user.email "이메일주소"

git config --global use.name "github아이디"

$ git commit -m "commit01"
[master (root-commit) 3aa7e48] commit01 =>  3aa7e48는 고유주소다.
 2 files changed, 5 insertions(+) => 2개의 파일에 5줄이 추가되었다.
 create mode 100644 BasicCar.py
 create mode 100644 README.md

code . +> VSC 바로 실행됨 단, 해당 위치에 있을때

1.바탕화면에 edu_git_commit 폴더를 만들고 git 저장소를 생성해주세요.

2.해당 폴더 안에 a.txt라는 텍스트 파일을 만들고 "add a.txt"라는 커밋메세지로 커밋을 만들어주세요

3.이번에는 b.txt.라는 텍스트 파일을 만들고, "add b.txt" 라는 커밋 메세지로 커밋을 만들어주세요.

4.a.txt파일을 수정하고 "update a.txt"라는 커밋 메세지로 커밋을 만들어 주세요.

BasicCar.py 수정

**git diff {} {}**

> commit serial의 앞에 4자리만 입력해도 됨!

**git log**

git hub같은 것을 Remote repository라고 한다.

집에서 그냥 쓰는 것은 Local Repository이다.

**git remote add origin 주소**

**git push -u origin master**

**git clone {remote_repo}**

**git push origin master**

**git pull origin master**

-![pexels-eberhard-grossgasteiger-443446](images/Git%EC%9D%B4%EB%9E%80/pexels-eberhard-grossgasteiger-443446.jpg)