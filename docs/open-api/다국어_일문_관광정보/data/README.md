# 다국어 관광정보 — 일본어 (日本語) 샘플 데이터

> 한국관광공사 JpnService2 · areaBasedList2 · 총 15,779건

## 개요

전국 관광 콘텐츠를 **일본어(日本語)** 로 제공하는 다국어 관광정보 API.  
콘텐츠 구조는 국문(KorService2)과 동일하며, 명칭·주소·설명이 해당 언어로 번역·제공됨.

---

## 샘플 10건

| 이미지 | 명칭 | 주소 | 콘텐츠 타입 |
|--------|------|------|------------|
| <img src="http://tong.visitkorea.or.kr/cms/resource/71/2778971_image2_1.png" width="80"> | 10 Corso Como 淸潭店(10꼬르소꼬모 청담점) | ソウル特別市カンナム区アプクジョンロ416 | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/48/3007148_image2_1.jpg" width="80"> | 1004ミュージアムパーク（1004 뮤지엄파크） | チョンラナム道シンアン郡チャウンソブ2ギル508-65 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/57/3402457_image2_1.JPG" width="80"> | 10年後グラウンド（10년후그라운드） | クァンジュ広域市ナム区ヤンチョンギル1 | 82 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/21/2577221_image2_1.jpg" width="80"> | 141ミニホテル（141미니호텔） | キョンサンブクト　キョンジュシ　ウォンヒョロ　141 | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/34/2366034_image2_1.jpg" width="80"> | 168階段（168계단） | プサン広域市トン区ヨンチョギル197ボンギル9 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/96/2617796_image2_1.jpg" width="80"> | 1913松汀駅市場（1913송정역시장） | クァンジュ広域市クァンサン区ソンジョンロ8ボンギル13 | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/86/2950486_image2_1.JPG" width="80"> | 2.28記念中央公園（2.28기념중앙공원） | テグ広域市チュン区トンソンロ2ギル80 | 76 |
| — | 201カンパニー (이공일컴퍼니) | ソウル特別市カンナム区トゴクロ151、2階 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/36/3499036_image2_1.jpg" width="80"> | 2025コリアアートフェスティバル（2025 대한민국 미술축제） | ソウル特別市チョンノ区テハクロ57 | 85 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/45/3526945_image2_1.png" width="80"> | 2025年APEC首脳会議記念公演「徐羅伐風流」（2025년 APEC 정상회의 기념공연 <서라벌 풍류>） | キョンサンブク道キョンジュ市ポムンロ446 | 85 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 콘텐츠 고유 ID (국문 ID와 동일) |
| `contenttypeid` | 콘텐츠 타입 코드 |
| `title` | 명칭 (日本語) |
| `addr1` / `addr2` | 주소 (日本語) |
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
