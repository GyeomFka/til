### enum의 장점
- 상수 대비 가독성이 뛰어남
- 기본 함수 제공
  - name, ordinal, values 기본 유틸성 함수 
  - IDE도움이 뛰어남
- 내부적으로 final변수로 하나만 선언, instance 변수 자체가 유일성을 보장하기 때문에 Application상에서 == 비교가 가능하다.
- 유일성 보장 == thread safe
- 필드 및 메서드 -> 확장성 용이
  - 기존 상수 선언 -> 자료형이 확장이 힘듬 


### 주의점
- 배포시 문제가 발생할 수 있음
- 다른 시스템과 연계시 문제가 발생할 수 있음