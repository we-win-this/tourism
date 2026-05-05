# 다국어 관광정보 — 독일어 (Deutsch) 샘플 데이터

> 한국관광공사 GerService2 · areaBasedList2 · 총 2,095건

## 개요

전국 관광 콘텐츠를 **독일어(Deutsch)** 로 제공하는 다국어 관광정보 API.  
콘텐츠 구조는 국문(KorService2)과 동일하며, 명칭·주소·설명이 해당 언어로 번역·제공됨.

---

## 샘플 10건

| 이미지 | 명칭 | 주소 | 콘텐츠 타입 |
|--------|------|------|------------|
| <img src="http://tong.visitkorea.or.kr/cms/resource/34/2366034_image2_1.jpg" width="80"> | 168-Treppe (168계단) | 9, Yeongcho-gil 197beon-gil, Dong-gu, Busan | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/96/2617796_image2_1.jpg" width="80"> | 1913 Songjeong Station Markt (1913송정역시장) | 13, Songjeong-ro 8beon-gil, Gwangsan-gu, Gwangju | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/65/657165_image2_1.jpg" width="80"> | 2. Invasionstunnel (Cheorwon) (제2땅굴(철원)) | 1825, Taebong-ro, Cheorwon-gun, Gangwon-do | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/48/3066148_image2_1.jpg" width="80"> | 2521 (이오이일) | 5-19, Omokdae-gil, Wansan-gu, Jeonju-si, Jeonbuk-do | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/22/2617822_image2_1.jpg" width="80"> | 3. Invasionstunnel (제 3땅굴) | 210-358, Je3ttanggul-ro, Paju-si, Gyeonggi-do | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/35/2657535_image2_1.jpg" width="80"> | 4. Invasionstunnel (제4땅굴) | Ihyeon-ri, Haean-myeon, Yanggu-gun, Gangwon-do | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/44/1806044_image2_1.jpg" width="80"> | 4.3 Friedenspark Jeju (제주4·3평화공원) | 430, Myeongnim-ro, Jeju-si, Jeju-do | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/91/2947291_image2_1.jpg" width="80"> | 5-Tage-Markt Goseong (고성5일시장 (4, 9일)) | 93, Goseongojo-ro, Seongsan-eup, Seogwipo-si, Jeju-do | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/50/3477250_image2_1.jpg" width="80"> | 5-Tage-Markt Jungmun (중문향토오일시장) | 12, Cheonjeyeon-ro 188beon-gil, Seogwipo-si, Jeju-do | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/49/3404749_image2_1.JPG" width="80"> | 5-Tage-Markt Maseok (마석 5일장(3, 8일)) | 26, Maseok-ro 17beon-gil, Hwado-eup, Namyangju-si, Gyeonggi-do | 79 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 콘텐츠 고유 ID (국문 ID와 동일) |
| `contenttypeid` | 콘텐츠 타입 코드 |
| `title` | 명칭 (Deutsch) |
| `addr1` / `addr2` | 주소 (Deutsch) |
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
