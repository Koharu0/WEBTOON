# 네이버 웹툰 API 정리

---

## 웹툰 검색 API

### URL
`https://comic.naver.com/api/search/all`

### 파라미터
- `keyword`: 검색할 웹툰 제목

### 예시 요청
`https://comic.naver.com/api/search/all?keyword=유미의 세포들`

---

## 웹툰 회차 목록 API

### URL
`https://comic.naver.com/api/article/list`

### 파라미터
- `titleId`: 웹툰의 고유 ID
- `page`: 페이지 번호 (한 페이지당 20회차)

### 예시 요청
`https://comic.naver.com/api/article/list?titleId=651673&page=1`

---

## 웹툰 회차 이미지 API (Parsing)

### URL
`https://comic.naver.com/webtoon/detail`

### 파라미터
- `titleId`: 웹툰의 고유 ID
- `no`: 회차 번호

### 예시 요청
`https://comic.naver.com/webtoon/detail?titleId=651673&no=1`

---

## 웹툰 요일별 목록 API

### URL
`https://comic.naver.com/api/webtoon/titlelist/weekday`

### 파라미터
- `order`: 정렬 기준
  - `user`: 인기순
  - `update`: 업데이트순
  - `view`: 조회순
  - `star`: 별점순

### 예시 요청
`https://comic.naver.com/api/webtoon/titlelist/weekday?order=view`

