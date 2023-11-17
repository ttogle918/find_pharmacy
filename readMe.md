# 도커를 이용한 다중 컨테이너 환경 구현

- database 3306 port가 이미 사용중인 상태 ==> killtask
- local환경(개발환경)에서만 create, 운영 환경에서는 known이나 validate 옵션을 사용.
- create를 쓰면 기존 테이블을 drop하고 스키마 생성, 운영중인 테이블을 삭제할수도 있기 때문
