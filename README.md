# 3dmc_apform_build

## History

## 22년 5월 29일
* 로그인 페이지
    * DB를 통한 로그인
* 도큐먼트 페이지
    * DOC_REG 에서 날짜 정보 로딩
* Server
    * URL 변경 : http://ec2-3-35-52-159.ap-northeast-2.compute.amazonaws.com:27510/3dmc
    * 로그인 정보 로딩 페이지
    * DOC_REG 로딩 페이지
    * 클라이언트와 연동

### 22년 5월 22일
* 로그인 페이지
    * 종료버튼
* 홈페이지
    * 유저 정보 표시
* 도큐먼트페이지
    * Dept 정보 표시
* Server
    * 테스트 접속 URL : http://ec2-13-209-41-101.ap-northeast-2.compute.amazonaws.com:27510/3dmc
    * Maria DB 세팅
    * 기본 백엔드 서버 개발
        * Unity3D에서 DB 다이렉트 접속 지원 X
    * 현재 클라이언트와 연동 X

### 22년 5월 15일
* 구조파악 및 변경
* 로그인 페이지
    * SQLite 참조 테이블 변경
    * Debug 모드 추가 (아이디, 패스워드 미체크)
* 메인 페이지
    * 부서 및 부서해당 문서정보 팝업 처리
        * SQLite를 통해 Prefabs 처리


### 22년 5월 8일
* 구조파악
* 페이지 별로 나누어진 씬을 하나의 씬의 통합
* 씬 구조 메뉴와 컨텐츠 부분으로 수정
* 로그인 페이지
    * SQLite를 통한 로그인처리

### 22년 5월 1일
* 구조파악
* 메인 페이지에서 파일 오픈 다이얼로그 구현