# 홈 NAS 구성

## docker-compose.dev.yml

|컨테이너| 설명 |
|:---:|:---:|
|nginx-proxy-manager| 리버스 프록시 |
|portainer| 도커관리 툴 |
|watchtower| 도커이미지 업데이트 |
|chromium| 인터넷브라우저 |
|code-server| 코드서버 |
|dashy| 대시보드 |
 - dashy.conf.yml로 대시보드 설정


---------------

## docker-compose.media.yml

|컨테이너| 설명 |
|:---:|:---:|
|nginx|  |
|transmission| 다운로드 관리 |
|bazarr| 자막 관리 |
|radarr| 영화 관리 |
|sonarr| 시리즈 관리 |
|prowlarr| 인덱서 관리 |
|jellyfin| 미디어 관리 |
- nginx.conf 설정필요
---------------