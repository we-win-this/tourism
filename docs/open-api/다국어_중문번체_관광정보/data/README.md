# 다국어 관광정보 — 중국어 번체 (繁體中文) 샘플 데이터

> 한국관광공사 ChtService2 · areaBasedList2 · 총 15,083건

## 개요

전국 관광 콘텐츠를 **중국어 번체(繁體中文)** 로 제공하는 다국어 관광정보 API.  
콘텐츠 구조는 국문(KorService2)과 동일하며, 명칭·주소·설명이 해당 언어로 번역·제공됨.

---

## 샘플 10건

| 이미지 | 명칭 | 주소 | 콘텐츠 타입 |
|--------|------|------|------------|
| <img src="http://tong.visitkorea.or.kr/cms/resource/62/3061862_image2_1.jpg" width="80"> | 석종사(충주) | 忠淸北道忠州市直洞街271-56 | 76 |
| — | 수주팔봉 | 忠淸北道忠州市乷味面 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/19/3530419_image2_1.jpg" width="80"> | 옛 군산세관 | 全北特別自治道群山市海望路244-7 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/71/2778971_image2_1.png" width="80"> | 10 Corso Como 清潭10꼬르소꼬모 청담점 | 首爾特別市江南區狎鷗亭路416 | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/48/3007148_image2_1.jpg" width="80"> | 1004博物館公園(1004 뮤지엄파크) | 全羅南道新安郡慈恩西部2街508-65 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/53/3479353_image2_1.jpg" width="80"> | 105405麻谷(105405 마곡) | 首爾特別市江西區麻谷中央路161-8 (麻谷洞) | 82 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/57/3402457_image2_1.JPG" width="80"> | 10年後空間(10y Ground)(10년후그라운드) | 光州廣域市南區楊村街1 | 82 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/48/2698148_image2_1.jpg" width="80"> | 12人座獨木舟渡口(킹카누 나루터) | 江原特別自治道春川市松岩洞684 | 75 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/21/2577221_image2_1.jpg" width="80"> | 141迷你飯店 (141미니호텔) | 慶尚北道 慶州市 元曉路 141 | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/34/2366034_image2_1.jpg" width="80"> | 168階梯(168계단) | 釜山廣域市東區瀛草街197號街9 | 76 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 콘텐츠 고유 ID (국문 ID와 동일) |
| `contenttypeid` | 콘텐츠 타입 코드 |
| `title` | 명칭 (繁體中文) |
| `addr1` / `addr2` | 주소 (繁體中文) |
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
