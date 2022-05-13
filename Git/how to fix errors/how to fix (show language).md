Repository에 올린 코드 언어가 나타나지 않는 현상 해결 방법
- .gitattributes 코드 작성

-> .gitattributes파일을 해당 프로젝트의 repository에 추가하여 <br><br>
demo/** linguist-documentation=false<br>
demo/** linguist-vendored=false<br>

를 작성한다.<br><br><br>

->프로젝트 파일들이 demo라는 폴더안에 있었던 것이 문제가 되었다.

해당 이슈를 찾아보니 demo뿐만아니라 dist, source와 같은 폴더 아래에 있는 프로젝트 파일들이 벤더 파일이나 문서로 취급해버리는 경우가 있다고 한다. 

<br>
-> <!>왜 에러가 발생하는지 추후 더 조사해야 함

참고 블로그 URL : https://doing7.tistory.com/54