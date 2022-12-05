# git
git 명령어에 대해 알아보자

기본적인 명령어

--새로운 파일을 추가

git add <파일>

--존재하는 파일을 스테이징하고 커밋하기

git commit -m “<메시지>”

--파일의 일부를 스테이징하기

git add -p [<파일> [<파일> [기타 파일들…]]]

--add 명령에서 Git 대화 모드를 사용하여 파일 추가하기

git add -i

--수정되고 추적되는 파일의 변경 사항 스테이징하기

git add -u [<경로> [<경로>]]

--수정되고 추적되는 모든 파일의 변경 사항 커밋하기

git commit -m “<메시지>” -a

--작업 트리의 변경 사항 돌려놓기

git checkout HEAD <파일> [<파일>]

--커밋되지 않고 스테이징된 변경 사항 재설정하기

git reset HEAD <파일> [<파일>]

--마지막 커밋 고치기

git commit -m “<메시지>” - -amend

--이전 커밋을 수정하고 커밋 메시지를 재사용하기

git commit -C HEAD - -amend

새로운 저장소 초기화하기

mkdir /path/newDir

cd /path/newDir

git init

저장소 복제하기

git clone <저장소 url>

새로운 원격 저장소 추가하기

git remote add <원격 저장소> <저장소 url>
