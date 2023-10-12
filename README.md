$ 이후 @@@ -> @@@ 실행

git + @@@@
	config : configure = 설정
	config (--global) +
		user.name
		user.email
git init           : 디렉토리 생성
git status        : 상태 나타냄 
git add @@@ : 수정 후 stage로 다시 올리기
git add .        : 현재 디렉토리 내 모든 파일 올림
git log           : 
git branch      : 현재 어디 branch인지 확인
git branch -m master main : main branch로 변환

git commit : commit
git commit -m "@@@" : 임의의 메세지와 함께 커밋

git 이외
ls -lha : 숨겨진 파일, 디렉토리 출력

nano : txt 편집기
nano .gitignore  : nano로 편집해도 stage로 안올림. 존재 X로 취급

*.a : a 종류 파일은 전부 무시
!lib.a : a 종류 파일 중 lib 파일은 무시되지 않음
