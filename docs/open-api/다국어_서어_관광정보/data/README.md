# 다국어 관광정보 — 스페인어 (Español) 샘플 데이터

> 한국관광공사 SpnService2 · areaBasedList2 · 총 3,106건

## 개요

전국 관광 콘텐츠를 **스페인어(Español)** 로 제공하는 다국어 관광정보 API.  
콘텐츠 구조는 국문(KorService2)과 동일하며, 명칭·주소·설명이 해당 언어로 번역·제공됨.

---

## 샘플 10건

| 이미지 | 명칭 | 주소 | 콘텐츠 타입 |
|--------|------|------|------------|
| <img src="http://tong.visitkorea.or.kr/cms/resource/53/3479353_image2_1.jpg" width="80"> | 105405 Magok (105405 마곡) | Magokjungang-ro 161-8, Gangseo-gu, Seúl | 82 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/21/2577221_image2_1.jpg" width="80"> | 141MINIHOTEL/ 141미니호텔 | 141, Wonhyo-ro, Gyeongju-si, Gyeongsangbuk-do | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/48/3066148_image2_1.jpg" width="80"> | 2521 (이오이일) | 5-19, Omokdae-gil, Wansan-gu, Jeonju-si, Jeonbuk-do | 80 |
| — | 365 Safe Town (365세이프타운) | Pyeonghwa-gil 15, Taebaek-si, Gangwon-do. | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/24/2706124_image2_1.jpg" width="80"> | 3917 Majung / 3917 마중 | 42-16, Hyanggyo-gil, Naju-si, Jeollanam-do | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/86/2526386_image2_1.jpg" width="80"> | 63 Square (63스퀘어) | 63-ro 36, Yeongdeungpo-gu, Seúl. | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/38/3484538_image2_1.jpg" width="80"> | Aank Air Hotel Gaebong (아늑에어 호텔 개봉점) | 38-12, Nambusunhwan-ro 95-gil, Guro-gu, Seoul | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/03/3484303_image2_1.jpg" width="80"> | Aank Air Hotel Gapyeong (아늑에어 호텔 가평점) | 6, Jojonghuimang-ro 5beon-gil, Jojong-myeon, Gapyeong-gun, Gyeonggi-do | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/89/3484389_image2_1.jpg" width="80"> | Aank Hotel & Spa Jongno Unni Branch (아늑호텔 앤 스파 종로운니점) | 89, Donhwamun-ro 11ga-gil, Jongno-gu, Seoul | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/68/3484168_image2_1.jpg" width="80"> | Aank Hotel & Spa Pyeongtaek (아늑호텔 앤 스파 평택점) | 446, Songtan-ro, Pyeongtaek-si, Gyeonggi-do | 80 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 콘텐츠 고유 ID (국문 ID와 동일) |
| `contenttypeid` | 콘텐츠 타입 코드 |
| `title` | 명칭 (Español) |
| `addr1` / `addr2` | 주소 (Español) |
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
