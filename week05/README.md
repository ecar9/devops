## 5주차
### 도커의 구성요소
- Image
- Container
- Dockerfile
- Registory


도커 이미지와 컨테이너의 차이
- 이미지는 클래스, 컨테이너는 인스턴스

### 도커명령어
- docker run -d -p `포트번호` --name `컨테이너 이름` `이미지 이름`
- docker ps `(-a)`
- docker images
- docker logs web
- docker stop `컨테이너 이름`
- docker rm -f `컨테이너 삭제` (허나 이미지는 남아 있음)

### 깃 새로운 명령어
|git stash| 커밋 안 한 디렉토리 임시 보관 후 작업 디렉토리를 정리|
|---|---|
|git stach pop| 임시 보관한 기록 다시 적용 후 성공 시 stash목록에서 제거|
|git stash apply| 임시 보관 기록 다시 적용 후 stash 목록은 유지|
