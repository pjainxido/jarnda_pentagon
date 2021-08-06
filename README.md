# Jaranda-pentagon

## Installation

```
# Yarn

$ yarn
$ yarn start
```

## 필수구현 사항

### 1. 로그인/회원가입

```
회원정보 입력사항
- 이름
- 주소 (팝업을 이용해서 입력받음)
- 신용카드 정보 (팝업을 이용해서 입력받음)
- 나이
```

### 로그인 페이지(모든 권한)

- [ ] ID, PW 입력
- [ ] 회원가입 버튼
- [ ] 로그인 버튼

### 회원가입 페이지 (default 부모님만 가입됨)

- [ ] 아이디, 비밀번호
- [ ] 이름
- [ ] 나이
- [ ] 팝업: 주소 입력 (다음 API)
- [ ] 팝업: 신용카드 입력 (포털 라이브러리)
- [ ] 회원 정보 저장 (저장을 어떻게 처리할지?)
- [ ] 가입 버튼 누르면 로그인 페이지로 redirect
- [ ] validation (아이디 중복, 비밀번호 몇 자리 이상?, 신용카드 4자리 누르면 다음자리로 이동 또는 숫자만 입력 가능하게? 이 외에도 입력값 정상인지 확인)

### 사용자 계정 페이지(로그인 후, 계정 별로 메뉴 다르게)

- [x] 계정별로 들어갈수있는 메뉴 생성
- [x] 계정별 메뉴 접속시 메뉴명 출력

### 권한 및 계정관리 페이지(관리자)

- [x] 계정 임의생성
- [x] 전체 회원 목록 (부모님, 선생님 변경가능)
- [x] 권한별로 메뉴 접근 설정
- [x] 데이터 테이블
  - 페이지네이션 : 한번에 전체 데이터 불러오는 걸로
  - 검색
- [ ] 데이터 테이블에서 팝업으로 유저추가

## 개발 인원 및 기간

### 개발기간

- 2021/8/2 ~ 2021/8/6

### 개발 인원별 구현 리스트

- 김건우

  - 권한별 메뉴관리 페이지 구현

- 구남규

- 박제인

- 김명준

- 이가은

- 조성원

- 이지열

- 허지윤

### 적용기술

- Front : React, Hook, Styled-Components,
- Back : Firebase
- Etc : Git, GitHub
