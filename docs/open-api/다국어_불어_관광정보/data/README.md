# 다국어 관광정보 — 프랑스어 (Français) 샘플 데이터

> 한국관광공사 FreService2 · areaBasedList2 · 총 2,185건

## 개요

전국 관광 콘텐츠를 **프랑스어(Français)** 로 제공하는 다국어 관광정보 API.  
콘텐츠 구조는 국문(KorService2)과 동일하며, 명칭·주소·설명이 해당 언어로 번역·제공됨.

---

## 샘플 10건

| 이미지 | 명칭 | 주소 | 콘텐츠 타입 |
|--------|------|------|------------|
| <img src="http://tong.visitkorea.or.kr/cms/resource/90/2625390_image2_1.jpg" width="80"> | 경주 버드파크 | Gyeongsangbuk-do, Gyeongju-si, Bomun-ro 74-14 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/62/3535062_image2_1.jpg" width="80"> | 세종마을 음식문화거리 | 24, Jahamun-ro 1-gil, Jongno-gu, Séoul (Chebu-dong) | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/80/1591380_image2_1.jpg" width="80"> | 여주온천 | 864, Gangmun-ro, Yeoju-si, Gyeonggi-do, Corée du Sud | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/53/3479353_image2_1.jpg" width="80"> | 105405 Magok(105405 마곡) | 161-8 Magok Jungang-ro(Magok-dong), Gangseo-gu, Séoul | 82 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/21/2577221_image2_1.jpg" width="80"> | 141MINIHOTEL / 141미니호텔 | 141, Wonhyo-ro, Gyeongju-si, Gyeongsangbuk-do | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/83/2950683_image2_1.jpg" width="80"> | 365 Safetown (365세이프타운) | 15, Pyeonghwa-gil, Taebaek-si, Gangwon-do (강원도 태백시 평화길 15) | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/24/2706124_image2_1.jpg" width="80"> | 3917 Majung / 3917 마중 | 42-16, Hyanggyo-gil, Naju-si, Jeollanam-do | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/86/2526386_image2_1.jpg" width="80"> | 63 Square (63스퀘어) | 50, 63-ro, Yeongdeungpo-gu, Seoul-si | 76 |
| — | Aayang Gichatgil (아양기찻길) | Daegu, Donggu, Haedong-ro 82 | 76 |
| — | Aboretum Solhyang à Gangneung  (강릉 솔향수목원) | 156, Sumokwon-gil, Gujeong-myeon, Gangneung-si, Gangwon | 76 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 콘텐츠 고유 ID (국문 ID와 동일) |
| `contenttypeid` | 콘텐츠 타입 코드 |
| `title` | 명칭 (Français) |
| `addr1` / `addr2` | 주소 (Français) |
| `firstimage` | 대표 이미지 URL |
| `mapx` / `mapy` | 경도 / 위도 |
| `areacode` / `sigungucode` | 지역 / 시군구 코드 |

### 콘텐츠 타입 코드

| 코드 | 분류 |
|------|------|
| 12 | Tourist Attraction |
| 14 | Cultural Facility |
| 15 | Festival / Event |
| 25 | Travel Course |
| 28 | Leisure & Sports |
| 32 | Accommodation |
| 38 | Shopping |
| 39 | Restaurant |

> 국문 `contentid` 와 1:1 매핑되므로 상세 정보 조회 시 동일 ID를 사용할 수 있습니다.
