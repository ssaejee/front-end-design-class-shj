# 1회차

<br>

### #의 개념
 - #=H1
 - #*2=H2
 - #*3=H3
 - #*4=H4
 - #*5=H5
 - #*6=H6

#의 개수에 따라 서체가 달라진다.

[Markdown 문법 참고 페이지](https://gist.github.com/ihoneymon/652be052a0727ad59601)
> 링크 걸기 연습! 저 페이지도 포크할 수 있나 궁금하다. >를 쓰면 설명 쓰기에 적합한  ㅣ  표시로 바뀐다. 수정이나 추가를 하면 라인 넘버?에 연두색 짧은 선이 생긴다...

![](https://i.imgur.com/NxoHnE8.png)
> 프로젝트의 파일 버전관리 및 GitHub Page를 통해 도메인을 생성하여 웹 페이지를 제작합니다.

![이미지 가져오기](https://img1.daumcdn.net/thumb/S272x320/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F995C773E5B8523E320)
> 이미지 가져오기 연습

![이미지]()
> 주소 안 넣으면 어떻게 될까?


> 아
> 이거
> 아무때나 써도
> 되는구나

<br>

<br> > 여기는 안 먹는구만... 안 먹으면 어떻게 나오는지 실험.
<br> ![이미지]() 여기는 이미지 링크가 입력되는데? 왜 >는 안 되지 아 이미지 링크 시작해 놓고 주소를 안 쓰면 엑박에 이미지라고 적혀있고 누르면 그냥 github 뜸.
<br> [링크](http://www.naver.com)  > 이것도 되는데 대신 팀장님이 말하셨던 것처럼 새탭에 열리는 건 안 됨 컨트롤 눌러야 함



<br>

### 1. GitHub 계정 생성
- github 가입하기
- 프로필 이름 실명으로 작성

<br>

### 2. GitHub.io 페이지 생성
- github desktop 설치
- 프로젝트 생성
- project repository 생성
- git page 생성 방법

<br>
<br>

### 3. 가상 저장소 동기화 설정
- 프로젝트 가상서버 생성
- git 사용자 등록
- 가상 저장소 연결할 폴더 생성
- git 사용자 등록 ([git 설치](https://coding-factory.tistory.com/245))

<br>

### 4. GitHub GUI 설치
- [github desktop 설치](https://desktop.github.com/)
> 내 컴퓨터의 폴더와 github에 있는 서버 동기화 시킬 수 있음.
- project repository 동기화

<br>

### 5. sync 파일 동기화
- 클론 (clone) - 프로젝트 가져오기
> 기존 psd 가져오기
- 커밋 (commit) - 가상서버 업데이트
> 작업한 psd 내 컴퓨터에 저장
- 푸시 (push) - 실서버 업데이트
> 작업한 psd 서버에 올리기
- 풀 (pull) - 실서버 내려받기
> 서버에 있는 다른 작업자의 psd 겸 가장 최근에 작업한 파일로 다운 받기

<br>
<br>

## 웹 디자인 시 사전 설정
> 프로젝트 진행 전 타겟 설정을 기반으로 지원 범위에 대한 사전 기획이 필요합니다.

<br>

### 1. 디바이스 지원 범위
- Mobile
> 640 *960
- Tablet
> 768 * 1024
- Desktop
> 1920 * 1080

<br>

### 2. 브라우저 지원 범위
- [Chrome](https://www.google.com/intl/ko_ALL/chrome/)
- [Firefox](https://www.mozilla.org/ko/firefox/new/)
- [IE +](https://support.microsoft.com/ko-kr/help/17621/internet-explorer-downloads)

<br>

### 3. 벤치마킹 및 컨셉의도 전달
- 사전조사
> (사이즈가 정형화 되어 있고 디자인 했을 때 깔끔한 느낌을 낼 수 있는 서점/책 관련 사이트로 결정.)
- 타겟설정
> Yes24 사이트. 현재 사이트는 보여 주려는 컨텐츠가 너무 많아 메인에 집중이 안 되고, 브랜드 아이덴티티가 컨텐츠에 가려짐.
- 컨셉도출
> 컨텐츠를 줄이고 브랜드를 보여주는 컨셉. 이용자들은 책을 구경하려고 들어오기보단 사려고 들어오기 때문에 많은 컨텐츠를 넣기보다는 많은 서점 브랜드 중에서 Yes24 만의 컨셉을 홍보 겸 표현하고 싶다. 
- 타입스케치
![웹, 태블릿, 모바일 버전 스케치](file:///C:/Users/%EC%84%9C%ED%98%9C%EC%A7%80/Downloads/%EB%85%B8%ED%8A%B8%202019.%208.%2029.%20%EC%98%A4%EC%A0%84%2019_24_02.pdf)

<br>

### [참고]
[크로스브라우징 테스트 사이트](http://iloveadaptive.com/url/)
[디바이스 사이즈 확인 사이트](http://screensiz.es/phone)
[마크다운 문법 참고 사이트](https://gist.github.com/ihoneymon/652be052a0727ad59601)

<br>

### 4. 영역 선택하기
- Drag
- Ctrl + d
- Alt + F3

### 5. github, gitlab 
> github와 gitlab은 마크다운 문법을 자동 변환 시켜서 바로 읽을 수 있게 해 준다.
> 두 가지 모두 용량 제한(유료) 있으나, 공개/비공개 리포지토리가 가능해 짐.
> github는 도메인을 하나만 정할 수 있으며 github.io가 꼭 붙는다.
> gitlab은 도메인을 여러 개 만들 수 있으며 도메인에 gitlab.io 따위가 붙지 않아 깔끔하다.