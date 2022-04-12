# GongGuGongBae

### 프로젝트 설계
#### 요구사항 (계속 추가 예정..)
* 회원을 가입, 조회할 수 있다
* 회원은 공구팟/공배팟(이하 팟)을 열 수 있다 
* 회원은 팟에 참가의사를 표시, 철회할 수 있다
* 회원은 위치 기반 정책을 통해 팟을 조회할 수 있다
	- 위치기반 정책은 현재 회원의 위치에서 반경 300m안에서 "수령장소"로 등록된 팟을 보여준다 (미정)
	- 위치기반 정책을 사용하지 않고 전체 팟을 조회할 수 있도록 할 수도 있다 (미정)
* 팟이 구성되면 참가의사를 표시한 회원들에게 알림이 뜬다
* 데이터는 Firebase Database 혹은 MySQL 사용해 저장할 수 있다 (미정)

#### 도메인 설계
* 회원
* 팟(파티)
* 위치
* 아이템
