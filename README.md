 ![Three meals a day](https://user-images.githubusercontent.com/75983289/147932573-01873666-cf31-4b4c-9997-03c10e594681.png)
## 삼시세끼 : 🍖삼시세끼 뭐먹을지를 추천해주는 웹사이트🍖
[기존 프로젝트](https://github.com/pangkyu/Three-meals-a-day)를 리액트로 다시 프로젝트

## 사용 스택 🛠️
 
 <div align = center>
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> 
   <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <br/>
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/oracleDB-003545?style=for-the-badge&logo=oracleDB&logoColor=white">
 </div>

## ERD TABLE
 
 ![캡처](https://user-images.githubusercontent.com/75983289/147934341-94255a07-2554-4295-b63a-fee000774393.PNG)

 <p>DB출처 : https://www.localdata.kr/devcenter/dataDown.do?menuNo=20001 </p>
 
## 커밋 규칙 & 브랜치 규칙 

| 타입     | 설명                                                           |
| -------- | -------------------------------------------------------------- |
| Feat     | 새로운 기능 추가                                              |
| Chore    | 빌드 업무 수정, 패키지 매니저 수정                             |
| Fix      | 버그 수정                                                      |
| Style    | 스타일 관련 기능(코드 포맷팅, 세미콜론 누락, 코드 자체의 변경이 없는 경우)       |
| Refactor | 코드 리팩토링                                                  |
| Design   | css등 UI 변경                                                  |
| Comment  | 주석 추가, 변경                                                |
| Docs     | 문서 수정                                         |
| Test     | 테스트 코드 추가                                                    |
| Rename   | 파일 or 폴더명 수정하거나 옮기는 작업만 수행할 경우            |
| Remove   | 파일 삭제만 수행                                               |


|브랜치<br/> 종류  | 설명  |
|-----  |---------------  |
|  main   | 제품으로 출시될 수 있는 브랜치, 배포 릴리즈버전의 소스가 들어있는 브랜치 |
| release | 이번 출시 버전을 준비하는 브랜치 | 
| hotfix  | 출시 버전에서 발생한 버그를 수정하는 브랜치. main에서 급하게 수정해야하는 경우에는 <br/>main에서 직접 브랜치 분기 생성. 수정 후에는 main에 병합 후 배포 | 
| develop | 다음 출시 버전을 개발하는 브랜치, 개발버전의 소스가 들어있는 브랜치 | 
| feature | 기능을 개발하는 브랜치, 개발이 완료되면 develop과 병합|
