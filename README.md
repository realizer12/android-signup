# android-signup
- next step 학습 테스트로 배우는 Compose 2기  - 회원가입 과제

## Step4

### 기능 요구 사항
- [x] 디자인 시안을 참고하여 모든 필드가 에러 없이 채워진 경우에만 Sign up 버튼을 활성화한다.
- [x] (선택사항) Sign up 버튼을 클릭하면 회원가입 완료 스낵바가 노출된다.

### 프로그래밍 요구 사항
- [x] 유효성 검사 로직과 뷰 로직을 나누어 관심사를 분리한다
- [x] 모든 로직에 테스트 코드를 추가한다
- [x] 테스트 가능한 부분과 테스트하기 힘든 부분을 분리해 테스트 가능한 부분에 대해서만 테스트를 진행한다.


### 기능 구현 목록
- [x] input validator unit tes 추가하기 
- [x] Error msg 각 inoput field에 종속 되게 수정 
- [x] 회원가입 버튼 활성화,비활성화 기능 추가 
- [x] 회원가입 버튼 활성화시 클릭하면, snackbar 노출 기능 추가


## Step3

### 기능 요구 사항
- [x] 디자인 시안을 참고하여 회원가입 뷰에 유효성 검사 로직을 추가한다.

### 프로그래밍 요구 사항
- [x] 유효성 검사 로직에 대한 테스트 코드를 추가한다.

### 기능 구현 목록
- [x] step2 pr 반영하기 (lazy column 제거)
- [x] 유효성 검사 기능 추가 (유저이름,이메일, 비밀번호, 비밀번호 확인)
- [x] 유효성 검사 로직에 대한 테스트 코드 추가


## Step2

### 기능 요구 사항
- [x] 디자인 시안을 참고하여 회원가입 뷰를 구현한다.

### 프로그래밍 요구 사항
- [x] ViewModel, Hilt 등은 회원가입 미션에서 활용하지 않는다. 컴포즈 학습에 집중하자.
- [x] 사용자 입력 및 유효성 검사에 대해서는 이 단계에서 고민하지 않아도 된다.
- [x] 컴포저블 함수가 너무 많은 일을 하지 않도록 분리하기 위해 노력해 본다.
- [x] Material3 Button, TextField를 활용한다.

### 기능 구현 목록
- [x] 회원가입 뷰 구현에 필요한  resource (string, drwable , color ) 추가
- [x] title 용 composable 함수 구현 
- [x] 'TextField' 사용하여 사용자 정보 입력관련 composable 함수 구현하기
- [x] singup 버튼용 composable 함수 구현

