# 다국어 관광정보 — 영어 (English) 샘플 데이터

> 한국관광공사 EngService2 · areaBasedList2 · 총 15,862건

## 개요

전국 관광 콘텐츠를 **영어(English)** 로 제공하는 다국어 관광정보 API.  
콘텐츠 구조는 국문(KorService2)과 동일하며, 명칭·주소·설명이 해당 언어로 번역·제공됨.

---

## 샘플 10건

| 이미지 | 명칭 | 주소 | 콘텐츠 타입 |
|--------|------|------|------------|
| — | 추암조각공원 (Chuam Sculpture Park) | 17-1 Chotdaebawi-gil, Donghae-si, Gangwon-do | 76 |
| <img src="https://tong.visitkorea.or.kr/cms/resource/71/4044971_image2_1.JPG" width="80"> | 0914 Flagship Store Dosan Park[Tax Refund Shop](0914 도산공원 플래그십 스토어) | 1F–2F, 15, Dosan-daero 45-gil, Gangnam-gu, Seoul | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/71/2778971_image2_1.png" width="80"> | 10 Corso Como Cheongdam Branch (10꼬르소꼬모 청담점) | 416, Apgujeong-ro, Gangnam-gu, Seoul | 79 |
| <img src="https://tong.visitkorea.or.kr/cms/resource/15/4018515_image2_1.jpg" width="80"> | 10 Corso Como Cheongdam Branch [Tax Refund Shop](10꼬르소꼬모 청담점) | 2F, 1F, 416, Apgujeong-ro, Gangnam-gu, Seoul | 79 |
| <img src="https://tong.visitkorea.or.kr/cms/resource/26/4018126_image2_1.jpg" width="80"> | 10 Corso Como Magazzini Garosu-gil Branch [Tax Refund Shop](10꼬르소꼬모 마가찌니 가로수길점) | 9, Apgujeong-ro 10-gil, Gangnam-gu, Seoul | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/53/3537253_image2_1.jpg" width="80"> | 100 Years Market 100 Years Night (백년시장 백년나이트) | 16 Hancheon-ro 144-gil, Gangbuk-gu, Seoul | 85 |
| <img src="https://tong.visitkorea.or.kr/cms/resource/72/4024672_image2_1.jpeg" width="80"> | 100 Years Optical [Tax Refund Shop](백년안경) | 1F, 34, Mareunnae-ro, Jung-gu, Seoul | 79 |
| <img src="https://tong.visitkorea.or.kr/cms/resource/42/4042142_image2_1.JPG" width="80"> | 1001 Optics Imdang Branch [Tax Refund Shop](일공공일안경콘택트 임당점) | 1F, 2110, Gyeonggang-ro, Gangneung-si, Gangwon-do | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/48/3007148_image2_1.jpg" width="80"> | 1004 Islands Museum Park (1004 뮤지엄파크) | 508-65 Jaeunseobu 2-gil, Jaeun-myeon, Sinan-gun, Jeollanam-do | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/53/3479353_image2_1.jpg" width="80"> | 105405 Magok  (105405 마곡) | 161-8 Magokjungang-ro, Gangseo-gu, Seoul | 82 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 콘텐츠 고유 ID (국문 ID와 동일) |
| `contenttypeid` | 콘텐츠 타입 코드 |
| `title` | 명칭 (English) |
| `addr1` / `addr2` | 주소 (English) |
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
