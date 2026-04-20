# 관광정보 국문 서비스 API

> 한국관광공사 OpenAPI — 국문(한국어) 관광정보 서비스 v4.4

---

## 개요

한국어로 제공되는 전국 관광정보를 조회하는 핵심 API. 관광지·행사·숙박·음식점·교통 등 관광 전반의 공식 데이터를 제공한다.

---

## 주요 기능

| 기능 | 설명 |
|------|------|
| 지역 기반 관광정보 조회 | 시도·시군구 코드 기반으로 관광지 목록 조회 |
| 키워드 검색 | 관광지명·주소 등 키워드로 전국 검색 |
| 관광타입별 조회 | 관광지(12), 문화시설(14), 행사/공연/축제(15), 여행코스(25), 레포츠(28), 숙박(32), 쇼핑(38), 음식점(39) |
| 위치 기반 조회 | GPS 좌표 + 반경(m) 기반 주변 관광정보 조회 |
| 상세정보 조회 | contentId 기반 공식 상세 설명·이미지·운영시간·입장료 등 |
| 이미지 조회 | 관광지별 공식 사진 목록 |
| 소개정보 조회 | 관광타입별 추가 항목 (ex. 숙박 → 객실수·예약방법) |

---

## 서비스 분류 코드 (contentTypeId)

| 코드 | 분류 |
|------|------|
| 12 | 관광지 |
| 14 | 문화시설 |
| 15 | 행사/공연/축제 |
| 25 | 여행코스 |
| 28 | 레포츠 |
| 32 | 숙박 |
| 38 | 쇼핑 |
| 39 | 음식점 |

---

## API 명세

**Base URL**: `https://apis.data.go.kr/B551011/KorService1/`

### 엔드포인트

| 오퍼레이션 | 설명 |
|-----------|------|
| `areaBasedList1` | 지역 기반 관광정보 목록 조회 |
| `searchKeyword1` | 키워드 검색 |
| `locationBasedList1` | 위치(GPS) 기반 관광정보 조회 |
| `detailCommon1` | contentId 기반 공통 상세정보 조회 |
| `detailImage1` | contentId 기반 이미지 목록 조회 |
| `detailIntro1` | contentTypeId별 소개 추가항목 조회 |
| `detailInfo1` | contentTypeId별 반복 추가항목 조회 |
| `areaCode1` | 지역 코드 목록 조회 |

### 공통 요청 파라미터

| 파라미터 | 필수 | 설명 |
|---------|------|------|
| `serviceKey` | ✓ | 발급받은 API 인증키 (URL encoding) |
| `MobileOS` | ✓ | OS 구분: `ETC` / `AND` / `IOS` / `WIN` |
| `MobileApp` | ✓ | 서비스(앱) 명칭 |
| `_type` |  | 응답 형식: `json` / `xml` (기본: xml) |
| `numOfRows` |  | 페이지당 결과 수 (기본: 10) |
| `pageNo` |  | 페이지 번호 (기본: 1) |

### 엔드포인트별 추가 파라미터

**`areaBasedList1`**

| 파라미터 | 필수 | 설명 |
|---------|------|------|
| `areaCode` |  | 시도 코드 |
| `sigunguCode` |  | 시군구 코드 (areaCode 필요) |
| `contentTypeId` |  | 관광타입 코드 |
| `cat1` / `cat2` / `cat3` |  | 대/중/소분류 코드 |

**`searchKeyword1`**

| 파라미터 | 필수 | 설명 |
|---------|------|------|
| `keyword` | ✓ | 검색 키워드 |
| `contentTypeId` |  | 관광타입 코드 |
| `areaCode` |  | 시도 코드 |

**`locationBasedList1`**

| 파라미터 | 필수 | 설명 |
|---------|------|------|
| `mapX` | ✓ | 경도 (WGS84 소수점) |
| `mapY` | ✓ | 위도 (WGS84 소수점) |
| `radius` | ✓ | 반경 (단위: m, 최대 20000) |
| `contentTypeId` |  | 관광타입 코드 |

**`detailCommon1` / `detailImage1` / `detailIntro1` / `detailInfo1`**

| 파라미터 | 필수 | 설명 |
|---------|------|------|
| `contentId` | ✓ | 관광정보 고유 ID |
| `contentTypeId` |  | 관광타입 코드 (detailIntro1·detailInfo1 필수) |

### 주요 응답 필드 (`areaBasedList1` 기준)

| 필드 | 설명 |
|------|------|
| `contentid` | 관광정보 고유 ID |
| `contenttypeid` | 관광타입 코드 |
| `title` | 명칭 |
| `addr1` / `addr2` | 주소 / 상세주소 |
| `mapx` / `mapy` | 경도 / 위도 |
| `firstimage` / `firstimage2` | 대표이미지 원본 / 썸네일 URL |
| `cat1` / `cat2` / `cat3` | 대/중/소분류 코드 |
| `createdtime` / `modifiedtime` | 등록일 / 수정일 |
| `tel` | 전화번호 |

---

## 포함 파일

| 파일명 | 설명 |
|--------|------|
| `한국관광공사_개방데이터_활용매뉴얼(국문)_v4.4.docx` | 전체 API 명세 및 예제 |
| `한국관광공사_개방데이터_활용신청방법_매뉴얼_v3.3.docx` | API 키 발급 절차 |
| `신분류체계정보 관광타입정보 연계 정의서.xlsx` | 분류 코드 전체 목록 |
