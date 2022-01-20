Git의 주요 개념들
▶️ merge: 한 branch에서 완성한 작업을 다른 branch에 병합하기
▶️ tag: 특정 이력을 가지는 commit에 대한 참조
▶️ pull request: 완료한 작업을 다른 사람이 리뷰하고 병합하도록 요청하기
▶️ issue: 기능에 대한 논의, 버그 추적하기
▶️ wiki: 링크들을 연결해 웹페이지 만들기
▶️ push: 내 컴퓨터 로컬에 저장되어 있던 버전 정보를 서버(git 저장소)에 올리기
▶️ pull: Git 저장소 서버로부터 내 컴퓨터 로컬로 버전 정보 전체를 가져오기



- 특정 폴더를 생성한다.
mkdir 
- 폴더 초기화 한다.
D:\project1>git init
- 클론할 디렉토리로 이동 후 
D:\project1> git clone https://github.com/ydy0710/project.git

- Git 저장소 디렉터리가 아닌 것을 확인
D:\project1\project> git status 

D:\project1\project> git log

- git 연결 상태 확인
D:\project1\project> git remote -v
origin  https://github.com/ydy0710/project.git (fetch)
origin  https://github.com/ydy0710/project.git (push)

git add

git status

git commit


// 터미널에 git 계정 정보 설정 코드 입력
$ git config --global user.name ""
$ git config --global user.email ""



