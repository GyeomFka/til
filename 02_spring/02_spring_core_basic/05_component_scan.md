### 컴포넌트 스캔 ↔ 의존관계 자동 주입 
- 편리한 의존관계 주입
- @ComponentScan 

### 탐색 위치와 기본 스캔 대상
- basePackages = "hello.core.*" 키워드 활용 → 패키지 한정
- default = 본인 패키지 하위 스캔

### 필터링 기능

### 중복 등록과 충돌 (name 이 같을 때)
- 자동 빈 등록 vs 자동 빈 등록
    - 스프링 환경에서의 오류발생
- 수동 vs 자동
    - 스프링 부트에선 오류로 알려준다.