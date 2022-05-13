Git 사용자 이름과 이메일 설정 방법
- git config --global user.name "Leaf"
- git config --global user.email "soioiz@naver.com"
<br><br>
-> 잘 저장 되었는지 확인하는 방법 : <br>
git config --list <br><br>
혹은 이름이나 이메일 단일로 확인하려면<br>
<br>이름 확인 : git config user.name
<br>이메일 확인 : git config user.email
<br><br><br>



프로젝트를 처음 Git에 올릴때
- git init

Add 하기
- git add .

-> add .은 모든 파일을 올린다는 것을 의미한다.<br> -> git add index.html 과 같이 특정 파일만 올릴 수 도 있다.<br><br><br>

히스토리 만들기
- git commit -m "first commit"
연결고리 만들기
- git remote add origin https://github.com/Leaf-github/TIL.git

Push 하기
- git push origin main


