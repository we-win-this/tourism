# 다국어 관광정보 — 러시아어 (Русский) 샘플 데이터

> 한국관광공사 RusService2 · areaBasedList2 · 총 2,170건

## 개요

전국 관광 콘텐츠를 **러시아어(Русский)** 로 제공하는 다국어 관광정보 API.  
콘텐츠 구조는 국문(KorService2)과 동일하며, 명칭·주소·설명이 해당 언어로 번역·제공됨.

---

## 샘플 10건

| 이미지 | 명칭 | 주소 | 콘텐츠 타입 |
|--------|------|------|------------|
| <img src="http://tong.visitkorea.or.kr/cms/resource/53/3479353_image2_1.jpg" width="80"> | 105405 Magok  (105405 마곡) | 161-8 Magokjungang-ro, Gangseo-gu, Seoul | 82 |
| — | 2-й пассажирский терминал международного аэропорта Инчхон (인천국제공항 제2여객터미널) | 446 , Je2terminal-daero, Jung-gu, Incheon | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/48/3066148_image2_1.jpg" width="80"> | 2521 (이오이일) | 5-19 Omokdae-gil, Wansan-gu, Jeonju-si, Jeonbuk-do | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/86/2526386_image2_1.jpg" width="80"> | 63 Square (63스퀘어) | 36, 63-ro, Yeongdeungpo-gu, Seoul | 76 |
| — | "Хэгван 1897" (해관1897) | 10 Haean-ro 177beon-gil, Mokpo-si, Jeollanam-do | 82 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/16/3483616_image2_1.jpg" width="80"> | Aank Hotel, The Hyoosik, в Инчхоне, филиал в районе Куволь (더휴식 아늑호텔 인천구월점) | 15 Yesul-ro 204beon-gil, Namdong-gu, Incheon | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/29/3483429_image2_1.jpg" width="80"> | Aank Hotel, The Hyoosik, в Инчхоне, филиал в районе Пупхён (더휴식 아늑호텔 인천 부평점) | 18-8 Gyeongwon-daero 1417beon-gil, Bupyeong-gu, Incheon | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/32/3483732_image2_1.jpg" width="80"> | Aank Hotel, The Hyoosik, в Сувоне, филиал в районе Инге (더휴식 아늑호텔 수원 인계점) | 29 Ingye-ro 94beon-gil, Paldal-gu, Suwon-si, Gyeonggi-do | 80 |
| — | Airman Ко., Лтд.  ((주)에어맨) | г. Инчхон, окр. Чун-гу, ул. Конхан-ро 272, пассажирский терминал 1, 2-й этаж, пом. № 1032 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/32/2539932_image2_1.jpg" width="80"> | Alpaca World (알파카월드) | 146-155, Deokjaebat-gil, Hongcheon-gun, Gangwon-do | 76 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 콘텐츠 고유 ID (국문 ID와 동일) |
| `contenttypeid` | 콘텐츠 타입 코드 |
| `title` | 명칭 (Русский) |
| `addr1` / `addr2` | 주소 (Русский) |
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
