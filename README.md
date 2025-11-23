# file-gq
파일 공유와 전송을 보다 간단하게

# Original by 잠신고 공학 동아리 RoDeLa
[RoDeLa Github](https://github.com/jsrodela)

## 서버 설정
   [PRODUCTION.md](PRODUCTION.md)

## 파일 구조
- fileapp : 파일 공유와 관련된 모든 것들 
- main : 최상위 프로젝트

  - urls.py : 특정 주소로 들어왔을 때 실행할 함수 설정
  - views.py : 사용자의 요청을 처리하여 HTML 파일을 반환하는 함수
  - templates / HTML.html : views.py에서 반환될 HTML 파일
  - static / 파일 : HTML에서 불러올 CSS & JavaScript 코드, 혹은 이미지 파일 등

## 링크 구조
- `/` : 메인 페이지
- `/send` : 보내기
- `/send_result` : 보내기 결과, 보낸 후 QR코드랑 숫자 표시하는 페이지
- `/receive` : 받기
  
## Requirements
ubuntu, python3

## 수정 기록
[RoDeLa 시절 수정 기록](https://github.com/jsrodela/file-gq/blob/main/README.md)

- 25/11/23 로델라 리포지토리에서 포크, 더 많은 설정을 settings.json 으로 분리
