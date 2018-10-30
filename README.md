# git 명령어 
## 설정과 초기화 
> `전역 사용자명/ 이메일 구성하기`
* > git config--global user.name 
* > git config--global user.email 
> `전역 설정 정보 조회`
* > git config--global--list
> `저장소별 설정 정보 조회`
* > git config--list
> `Git의 출력결과 색상 활성화하기`
* > git config --global color.ui "auto"
> `새로운 저장소 초기화 하기`
* > mkdir/path/newDir
* > cd/path/newDir
* > git init
> `저장소 복제하기`
* > git clone <저장소 url>
> `새로운 원격 저장소 추가하기`
* > git remote add<원격 저장소><저장소 url>
# 마크다운 문법
## 제목 Headers
* > #으로 시작하는 텍스트 <br> #은 하나부터 여섯개까지 쓸 수 있고, <br> #이 늘어날대마다 제목이 수준은 내려간다.
* > -,=을 이용하여 h1.h2를 쓸 수 있다.
## 인용 Blockquotes
* > (>)으로 시작하는 텍스트
## 코드 블럭 Code Blocks
* > (```)또는(~~~) 코드 첫 줄과 마지막줄에 Block quote(`)또는 물결(~) 3개 삽입
## 인라인 코드 Inline Code Blocks
* > (`(Back qutoe)로 감싸진 텍스트
## 강조 Emphasis
* > 기울여 쓰기(italic) : (*) 또는 (_)로 감싼 텍스트 <br> 굵게쓰게(bold) : (**) 또는 (__) 로 감싼 텍스트
## 수평선 Horizontal Rules
* > (-) 또는 (*) 또는 (_) 을 3개 이상 작성 (단, (-)을 사용할 경우 header로 인식할 수 있으니 전 라인은 비워두어야 한다.)
## 리스트 Lists
* > `순서 있는 리스트 Ordered Lists`
* > No. 숫자다음 온점을 찍는다.(적힌 숫자랑 상관없이 순서대로 번호가 매겨진다.)
