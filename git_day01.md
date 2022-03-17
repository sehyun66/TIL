오늘 배웠던 내용에 대한 md파일로 작성해보는 시간
mkdir 폴더명 새로운 디렉토리만들기
cd 폴더명 폴더 경로 이동
touch 파일명 파일 만들기
ls 해당 디렉토리 안의 파일들 리스트 보여줘
ls -a 숨김파일까지 전부 보여줘
ls -1 확장자 등 모든 정보 표시해서 보여줘
rm 삭제
rm -r 재귀적으로 폴더 하단 내역도 삭제해줘
rm -rf 강제로 삭제
mv 파일 있을 경우 대상파일로 이동
   파일 없을 경우 파일 이름 변경

pwd 현재위치 (절대경로 시 사용)
ctrl + l 스크롤 내리기
tab 자동완성

상대경로: .(현재), ..(상위)
절대경로: /c/Users/qkrtp/Desktop/TIL

config 정보 출력
git config --global --list

일반 폴더 -> 로컬 저장소
git init

버전상태 출력
git status

working directory 에서 staging area로

git add . (모든 파일 add)
git add [파일]

staging area에서 commit

git commit -m "메시지"
git commit 후 상단 탭 들어가서 "메시지"적고 저장후 닫기

commit 목록 출력
git log (전체 나옴 너무 길어서 q + enter 눌러서 나오기)
git log --online (한줄로 보기)
git log -p (commit 마다 차이 보기)