# 다국어 관광정보 — 중국어 간체 (简体中文) 샘플 데이터

> 한국관광공사 ChsService2 · areaBasedList2 · 총 15,374건

## 개요

전국 관광 콘텐츠를 **중국어 간체(简体中文)** 로 제공하는 다국어 관광정보 API.  
콘텐츠 구조는 국문(KorService2)과 동일하며, 명칭·주소·설명이 해당 언어로 번역·제공됨.

---

## 샘플 10건

| 이미지 | 명칭 | 주소 | 콘텐츠 타입 |
|--------|------|------|------------|
| <img src="http://tong.visitkorea.or.kr/cms/resource/15/3570215_image2_1.jpg" width="80"> | 모던샤브하우스 광화문D타워점（Modern火锅店光化门D塔店） | 首尔特别市钟路区钟路3街17号（清进洞） | 82 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/37/3498037_image2_1.jpg" width="80"> | 스테이지35 성수 | 首尔特别市城东区演武场街35 (圣水洞2街) | 79 |
| — | 오리요리의 거리 | 광주광역시 북구 경양로 125 | 76 |
| — | 인천항 크루즈터미널 | 仁川广域市延寿区国际港湾大路438 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/59/2733659_image2_1.jpg" width="80"> | 평창 백룡동굴(平昌白龙洞窟) | 江原道平昌郡美滩面Munhui街 63 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/71/2778971_image2_1.png" width="80"> | 10 CORSO COMO清潭店(10꼬르소꼬모 청담점) | 首尔特别市江南区狎鸥亭路416 | 79 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/48/3007148_image2_1.jpg" width="80"> | 1004博物馆公园（1004 뮤지엄파크） | 全罗南道新安郡慈恩西部2街508-65 | 76 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/53/3479353_image2_1.jpg" width="80"> | 105405麻谷(105405 마곡) | 首尔特别市江西区麻谷中央路161-8 (麻谷洞) | 82 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/21/2577221_image2_1.jpg" width="80"> | 141迷你酒店（141미니호텔） | 庆尚北道 庆州市 元晓路 141 | 80 |
| <img src="http://tong.visitkorea.or.kr/cms/resource/86/2950486_image2_1.JPG" width="80"> | 2.28纪念中央公园（2.28기념중앙공원） | 大邱中区东城路2街80 | 76 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 콘텐츠 고유 ID (국문 ID와 동일) |
| `contenttypeid` | 콘텐츠 타입 코드 |
| `title` | 명칭 (简体中文) |
| `addr1` / `addr2` | 주소 (简体中文) |
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
