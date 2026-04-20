# 관광사진 갤러리정보 API

> 한국관광공사 OpenAPI — 관광사진 서비스 v4.2

---

## 개요

전국 관광지의 공식 사진을 제공하는 갤러리 서비스. 한국관광공사가 직접 촬영·수집한 고품질 관광 사진을 조회할 수 있다.

---

## 주요 기능

| 기능 | 설명 |
|------|------|
| 관광지별 사진 조회 | contentId 기반 해당 관광지 공식 사진 목록 |
| 지역별 사진 조회 | 시도·시군구 기준 지역 관광 사진 |
| 계절·테마별 조회 | 봄꽃·단풍·설경·야경 등 테마 필터 |
| 이미지 URL 제공 | 원본·썸네일 URL 직접 제공 |

---

## 제공 정보

- 사진 제목, 촬영 위치, 촬영 날짜
- 원본 이미지 URL (고해상도)
- 썸네일 URL
- 저작권 정보

---

## API 명세

**Base URL**: `https://apis.data.go.kr/B551011/GalService1/`

### 엔드포인트

| 오퍼레이션 | 설명 |
|-----------|------|
| `galleryList1` | 관광사진 목록 조회 |

### 요청 파라미터

| 파라미터 | 필수 | 설명 |
|---------|------|------|
| `serviceKey` | ✓ | 발급받은 API 인증키 (URL encoding) |
| `MobileOS` | ✓ | OS 구분: `ETC` / `AND` / `IOS` / `WIN` |
| `MobileApp` | ✓ | 서비스(앱) 명칭 |
| `_type` |  | 응답 형식: `json` / `xml` (기본: xml) |
| `numOfRows` |  | 페이지당 결과 수 |
| `pageNo` |  | 페이지 번호 |
| `areaCode` |  | 시도 코드 |
| `sigunguCode` |  | 시군구 코드 |
| `contentId` |  | 관광지 고유 ID |
| `galPhotographyMonth` |  | 촬영 월 (01~12) |

### 주요 응답 필드

| 필드 | 설명 |
|------|------|
| `contentid` | 관련 관광지 ID |
| `galTitle` | 사진 제목 |
| `galPhotographyLocation` | 촬영 위치명 |
| `galPhotographyMonth` | 촬영 월 |
| `galCreatedtime` | 등록일 |
| `galWebImageUrl` | 원본 이미지 URL (고해상도) |
| `galSearchImageUrl` | 썸네일 URL |

---

## 포함 파일

| 파일명 | 설명 |
|--------|------|
| `한국관광공사_개방데이터_활용매뉴얼(관광사진)_v4.2.docx` | 전체 API 명세 및 예제 |
| `한국관광공사_개방데이터_활용신청방법_매뉴얼_v3.3.docx` | API 키 발급 절차 |
