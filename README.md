### 일반 ###
1.로컬 저장소 생성 후 만들고 싶은 곳에 git을 실행 후 아래의 명령어를 입력한다.

`git init`<br>

2.README.md 파일생성

`touch README.md`<br>
`git status를 입력해 변동사항을 확인한다.`<br>
`git add . 추가된 모든 파일을 등록한다`<br>
`git commit -m ""  ""메시지와 함께 커밋을 한다.`<br>

3.온라인 저장소 생성

`git remote add origin https://github.com/"아이디"/로컬저장소.git`<br>

4.README.md파일 온라인 저장소에 업로드

`git push -u origin main`<br>

### github에서 내려 받기 ###
`git pull origin main`

### clone과 pull 차이 ###
-clone : 로컬에 저장소가 없는 경우. 저장소 자체를 복사
-pull : 로컬에 연결된 저장소 있는 경우. 저장소 안에 있는 파일 내려받기

### 충돌(rejacted,conflict)시 해결 방법 ###
__충돌 이유__<br>
하나의 문서가 온라인과 로컬에 각 각 수정이 일어났기 때문

__해결__<br>
1.에러 메시지 확인 후 git pull을 이용해 전 버전으로 복구한다.<br>
2.복구 후 직접 내용을 추가한 후 commit을 한다<br>
3.git push -u origin main 을 입력해 오류가 안뜨면 성공.

## clone 과 pull ##
- clone : 로컬에 저장소가 없는 경우. 저장소 자체를 복사
- pull : 로컬에 연결된 저장소 있는 경우. 저장소 안에 있는 파일 내려받기

* rejected 오류 발생시 일단 git pull로 전 버전을 다운받고 해결한다.

## pull request
- 포크로 가져온 repository를 수정 및 원작자에게 수정 반영하는 과정
- 로컬에서 커밋 후 push
- 포크한 github repository의 pull requests 탭으로 이동
- new pull request 버튼 클릭
- 수정된 내용 확인 후 create pull request 버튼 클릭
- 커밋 메시지 작성 혹은 확인 후 create pull request클릭
- 전송이 되면 원작자의 repository pull requests 탭에서 확인 가능

## pull request Check
- pull request 버튼클릭
- 내용 검토
- 수정된 내용을 나의 github repository 반영하려면 Merge pull request 클릭

## HTML 이란? ##
- 콘텐츠의 구조를 정의하는 마크업 언어이다.

- 여는 태그 <p> (Opening tag): 이것은 요소의 이름으로 구성되고 (여기에서는 p), 여닫는 꺾쇠괄호로 감싸집니다. 이것은 요소가 시작되는 곳, 또는 효과를 시작하는 곳

- 닫는 태그 </p> (Closing tag): 이것은 여는 태그와 같지만, 요소의 이름 앞에 전방향 슬래시가 포함된다는 점이 다릅니다.

![1](https://github.com/wkd6262/home/assets/142865132/d5c2d7e5-135d-4c71-a2af-0a2f8018bc7e)