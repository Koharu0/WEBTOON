# WEBTOON - 네이버 웹툰 프론트엔드

**WEBTOON - 네이버 웹툰 프론트엔드**는 사용자 프라이버시 보호에 초점을 둔 네이버 웹툰의 프론트엔드입니다.<br>

## 주요 기능

- **웹툰 검색**: 제목/작가를 입력하여 웹툰을 검색할 수 있습니다.
- **웹툰 열람**: 웹툰의 특정 회차를 선택하고, 해당 화를 열람할 수 있습니다.

## 구현체
![WEBTOON](https://github.com/user-attachments/assets/d6953f8a-7ced-4d2b-aa49-562f7596760b)
- [Web](https://breeze.cat/webtoon/) - 하단 참고
- [Web-CORS](https://breeze.cat/webtoon-cors) - 하단 참고


## 지원하지 않는 기능
- 현재 댓글 열람 기능을 지원하지 않으며, 지원 예정입니다. (1순위)
- 현재 도전 만화 검색/열람 기능을 지원하지 않으며, 지원 예정입니다. (2순위)
- 현재 로그인 관련 기능을 지원하지 않으며, 지원 예정에 없습니다.

***
## 구현체 상세 설명
Web: 현재 CORS 문제를 해결하지 않은 상태입니다. 현재 수정 계획이 없으며, Web-CORS 구현체보다 속도가 빠릅니다.<br><br>
Web-CORS: CORS 문제를 임시적으로 Proxy 서버를 사용해 해결한 구현체입니다. Web 구현체보다 속도가 느리며, 사용 전 [이곳](https://cors-anywhere.herokuapp.com/corsdemo)에서 ``Request temporary access to the demo server`` 버튼을 누르고 사용해야 합니다.

수정할 부분: iPad 제외, 모바일 컷툰 수정