# 의료관광 정보 API — 샘플 데이터

> 한국관광공사 MdclTursmService · areaBasedList · 총 337건
> 언어: 영어 (langDivCd=ENG)

## 개요

국내 **의료관광 인증 병원·클리닉** 정보를 제공하는 API.  
미용·성형·검진·한방 등 외국인 환자를 유치하는 의료기관 목록.

---

## 샘플 10건

| 이미지 | 기관명 | 주소 | 전화 | 언어 |
|--------|--------|------|------|------|
| — | 1stbutton Rhinoplasty clinic (첫단추의원) | (12th Floor, Cheongho Building), 483 Gangnam-daero, Seocho-gu, Seoul | — | ENG |
| — | 201Company (이공일컴퍼니) | 2F, 151 Dogok-ro, Gangnam-gu, Seoul | — | ENG |
| — | 21 Century Hospital (서울21세기병원) | 39 Seochojungang-ro, Seocho-gu, Seoul | — | ENG |
| — | 365mc (365엠씨(mc)병원) | 126 Seochojungang-ro, Seocho-gu, Seoul | — | ENG |
| — | AB Plastic Surgery (에이비성형외과) | (2nd-4th Floors, BLOCK77), 17 Seocho-daero 77-gil, Seocho-gu, Seoul | — | ENG |
| — | Aimeigroup (아이메이그룹) | (B2, B1, 1st, 2nd Floors), 49 Gangnam-daero 110-gil, Gangnam-gu, Seoul | — | ENG |
| — | Ain Hospital (의료법인 아인의료재단 아인병원) | 372 Gyeongin-ro, Michuhol-gu, Incheon | — | ENG |
| — | Airman Inc. ((주)에어맨) | (#1032, 2nd Floor, Terminal 1), 272 Gonghang-ro, Jung-gu, Incheon | — | ENG |
| — | Allforskin Dermatology Clinic (올포스킨피부과) | 4th Floor, Dongwon Building, 26 Dongseong-ro 5-gil, Jung-gu, Daegu | — | ENG |
| — | Andong Hospital (안동병원) | 11 Angsil-ro, Andong-si, Gyeongsangbuk-do | — | ENG |

### 언어 구분 코드 (langDivCd)

| 코드 | 언어 |
|------|------|
| KOR | 한국어 |
| ENG | 영어 |
| JPN | 일본어 |
| CHS | 중국어 간체 |
| CHT | 중국어 번체 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `contentId` | 콘텐츠 고유 ID |
| `title` | 기관명 |
| `baseAddr` | 기본 주소 |
| `detailAddr` | 상세 주소 |
| `tel` | 연락처 |
| `mapX` / `mapY` | 경도 / 위도 |
| `orgImage` | 원본 이미지 URL |
| `thumbImage` | 썸네일 이미지 URL |
| `langDivCd` | 언어 구분 코드 |
| `lDongRegnCd` | 법정동 시도 코드 |
| `lDongSignguCd` | 법정동 시군구 코드 |
