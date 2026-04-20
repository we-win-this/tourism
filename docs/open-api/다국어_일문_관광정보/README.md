# 다국어 일문 관광정보 API

> 한국관광공사 OpenAPI — 일문(日本語) 관광정보 서비스 v4.4

---

## 개요

**일본어(日本語)** 로 제공되는 전국 관광정보 서비스. 국문 API와 동일한 기능 구조를 일본어로 제공한다.

---

## API 명세

**Base URL**: `https://apis.data.go.kr/B551011/JpnService1/`

국문 API(`KorService1`)와 동일한 오퍼레이션 구조를 사용하며, 응답 데이터가 일본어로 제공된다.

### 엔드포인트

| 오퍼레이션 | 설명 |
|-----------|------|
| `areaBasedList1` | 지역 기반 관광정보 목록 조회 |
| `searchKeyword1` | 키워드 검색 |
| `locationBasedList1` | 위치(GPS) 기반 관광정보 조회 |
| `detailCommon1` | contentId 기반 공통 상세정보 조회 |
| `detailImage1` | contentId 기반 이미지 목록 조회 |
| `detailIntro1` | contentTypeId별 소개 추가항목 조회 |
| `areaCode1` | 지역 코드 목록 조회 |

파라미터 상세 및 응답 필드는 [관광정보_국문 API 명세](../관광정보_국문/README.md#api-명세) 참고.

---

## 포함 파일

| 파일명 | 설명 |
|--------|------|
| `한국관광공사_개방데이터_활용매뉴얼(일문)_v4.4.docx` | 전체 API 명세 및 예제 |
| `한국관광공사_개방데이터_활용신청방법_매뉴얼_v3.3.docx` | API 키 발급 절차 |
| `신분류체계정보 관광타입정보 연계 정의서.xlsx` | 분류 코드 목록 |
