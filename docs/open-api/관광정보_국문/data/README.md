# 관광정보 국문 API — 샘플 데이터

> 한국관광공사 KorService2 · areaBasedList2 · 총 50,954건

## 개요

전국 관광지·숙박·음식점·레포츠 등 모든 관광 콘텐츠의 기본 목록을 국문으로 제공하는 핵심 API.

---

## 샘플 10건

| 이미지 | 명칭 | 주소 | 콘텐츠 타입 | contentId |
|--------|------|------|------------|-----------|
| — | 가가상점 | 충청남도 공주시 감영길 3 (반죽동) | 38 | 2750144 |
| — | 가가와 | 부산광역시 부산진구  중앙번영로 (6) | 39 | 2805408 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/06/3564906_image2_1.jpg" width="80"> | 가가책방 | 충청남도 공주시 당간지주길 10 (반죽동) | 14 | 2750143 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/28/3572128_image2_1.jpg" width="80"> | 가거도 | 전라남도 신안군 흑산면 가거도길 38-2 | 12 | 127480 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/50/3492550_image2_1.jpg" width="80"> | 가경 터미널시장 | 충청북도 청주시 흥덕구 가경동 | 38 | 1433504 |
| <img src="https://tong.visitkorea.or.kr/cms/resource/12/2901512_image2_1.jpg" width="80"> | 가경목장 | 경기도 안산시 상록구 감골로 173 (사동) | 39 | 2901530 |
| — | 가경식당 | 충청남도 부여군 부여읍 성왕로 286 | 39 | 1797757 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/36/3079736_image2_1.jpg" width="80"> | 가계해수욕장 | 전라남도 진도군 고군면 신비의바닷길 47 | 12 | 126273 |
| <img src="https://tong.visitkorea.or.kr/cms/resource/55/2033255_image2_1.jpg" width="80"> | 가고파 꼬부랑길 벽화마을 | 경상남도 창원시 마산합포구 성호서7길 15-8 | 12 | 2019720 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/85/2788385_image2_1.jpg" width="80"> | 가고파부치기 | 강원특별자치도 평창군 평창읍 평창시장1길 14 | 39 | 2788416 |

### 콘텐츠 타입 코드

| 코드 | 분류 |
|------|------|
| 12 | 관광지 |
| 14 | 문화시설 |
| 15 | 축제/행사 |
| 25 | 여행코스 |
| 28 | 레포츠 |
| 32 | 숙박 |
| 38 | 쇼핑 |
| 39 | 음식점 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 콘텐츠 고유 ID |
| `contenttypeid` | 콘텐츠 타입 코드 |
| `title` | 명칭 |
| `addr1` / `addr2` | 주소 |
| `firstimage` | 대표 이미지 URL |
| `mapx` / `mapy` | 경도 / 위도 |
| `areacode` / `sigungucode` | 지역 / 시군구 코드 |
| `lclsSystm1~3` | 대·중·소 분류 코드 |
