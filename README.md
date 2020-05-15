# git의 명령어를 정리해보자

## 순서보기
1. github에서 "git-test" 라는 repository를 만들기
2. 내 컴퓨터에서 test 폴더 밑에 git-test라는 폴더를 만든다.
	- cd git경
3. git-test 폴더에서 git을 사용할 수 있도록 초기화 한다.
	- git init
	- git remote add origin https://github.com/JeongminSung/git-test.git
4. 파일 생성 
	- vi 파일명.파일형식
5. github 레파지토리에서 볼 수 있도록 올린다.
	- git add .
	- git commit -m"커밋내용"
	- git push origin master
6. feature/readme 브랜치를 생성한다.
	- git branch "feature/readme"
7.  해당 브랜치에서 아래의 내용으로 README.md 를 만든다.
	- vi README.md
정리끗!
