# 한국관광공사 OpenAPI — 전체 목록

> **Service Key**: `docs/open-api/.env` 참고  
> **Base URL**: `https://apis.data.go.kr/B551011`  
> **데이터 수집**: `fetch_all.py` — 각 API에서 10건 샘플 수집 후 `{API명}/data/result.json` 저장

---

## 목차

1. [핵심 관광정보](#1-핵심-관광정보)
2. [분석·통계 데이터](#2-분석통계-데이터)
3. [테마별 특화 정보](#3-테마별-특화-정보)
4. [다국어 관광정보](#4-다국어-관광정보)

---

## 1. 핵심 관광정보

전국 관광 콘텐츠의 기본 목록·이미지·위치 정보.

| API | 서비스 | 총 건수 | 설명 | 데이터 |
|-----|--------|--------|------|--------|
| 관광정보 국문 | KorService2 | 50,954 | 전국 관광지·숙박·음식·레포츠 등 전체 콘텐츠 | [data/README.md](관광정보_국문/data/README.md) |
| 관광사진 갤러리 | PhotoGalleryService1 | 6,119 | 관광공사 공식 사진 갤러리 (고화질) | [data/README.md](관광사진_갤러리정보/data/README.md) |
| 오디 오디오가이드 | Odii | 2,231 | 전국 관광지 음성 해설, 5개 언어 | [data/README.md](오디_오디오가이드_관광/data/README.md) |
| 관광공모전 수상작 | (별도) | 95 | 한국관광공사 공모전 입상 사진 | [data/README.md](관광공모전_수상작_정보/data/README.md) |

---

## 2. 분석·통계 데이터

방문 패턴·수요·통계 기반 데이터 — 연구·정책 수립·서비스 추천에 활용.

### 2-1. 방문 패턴 분석

| API | 서비스 | 총 건수 | 설명 | 데이터 |
|-----|--------|--------|------|--------|
| 관광지별 연관관광지 | TarRlteTarService1 | 267 | 함께 방문된 연관 관광지 순위 | [data/README.md](관광지별_연관관광지_정보/data/README.md) |
| 기초지자체 중심관광지 | LocgoHubTarService1 | 80 | 시군구별 핵심 허브 관광지 순위 | [data/README.md](기초지자체_중심관광지_정보/data/README.md) |
| 관광지 방문집중률 예측 | TatsCnctrRateService | 1,650 | 날짜별 방문 집중률 예측(%) | [data/README.md](관광지_방문집중률_예측정보/data/README.md) |

### 2-2. 관광 빅데이터

| API | 서비스 | 총 건수 | 설명 | 데이터 |
|-----|--------|--------|------|--------|
| 관광빅데이터 통계분석 | DataLabService | 1,581 | 시도별 일별·요일별·관광객 유형별 방문수 | [data/README.md](관광빅데이터_통계분석/data/README.md) |

### 2-3. 지역별 데이터랩 (데이터 적재 대기 중)

> API 키 승인 완료, 백엔드 데이터 준비 중 (totalCount=0)

| API | 서비스 | 총 건수 | 설명 | 데이터 |
|-----|--------|--------|------|--------|
| 지역별 관광자원 수요 | AreaTarResDemService | 0 | 자원 유형별 소비자 수요량 | [data/README.md](지역별_관광자원_수요/data/README.md) |
| 지역별 관광수요 강도 | AreaTarDemDsService | 0 | 시군구 관광 수요 밀도 지수 | [data/README.md](지역별_관광수요_강도/data/README.md) |
| 지역별 관광 다양성 | AreaTarDivService | 0 | 시군구 관광 콘텐츠 다양성 지수 | [data/README.md](지역별_관광_다양성/data/README.md) |

---

## 3. 테마별 특화 정보

특정 여행 테마·계층을 위한 전문 정보.

### 3-1. 자연·생태

| API | 서비스 | 총 건수 | 설명 | 데이터 |
|-----|--------|--------|------|--------|
| 생태관광 정보 | GreenTourService1 | 5 | 생태·환경 관광지 (인증 생태관광지역 포함) | [data/README.md](생태관광_정보/data/README.md) |
| 두루누비 길코스 | Durunubi | 228 | 도보·자전거 길코스 (GPX 포함) | [data/README.md](두루누비_길코스_여행정보/data/README.md) |
| 고캠핑 캠핑장 | GoCamping | 3,067 | 전국 캠핑장 위치·시설·예약 정보 | [data/README.md](고캠핑_캠핑장_여행정보/data/README.md) |

### 3-2. 특수 여행객

| API | 서비스 | 총 건수 | 설명 | 데이터 |
|-----|--------|--------|------|--------|
| 반려동물 동반여행 | KorPetTourService2 | 9,784 | 반려동물 동반 가능 관광지·숙박·음식점 | [data/README.md](반려동물_동반여행_정보/data/README.md) |
| 무장애 배리어프리 | KorWithService2 | 10,010 | 장애인·노약자 편의시설 정보 | [data/README.md](무장애_배리어프리_여행정보/data/README.md) |

### 3-3. 건강·웰니스

| API | 서비스 | 총 건수 | 설명 | 데이터 |
|-----|--------|--------|------|--------|
| 웰니스 건강휴양 | WellnessTursmService | 175 | 웰니스·힐링·요양 관광지 | [data/README.md](웰니스_건강휴양_관광정보/data/README.md) |
| 의료관광 | MdclTursmService | 337 | 외국인 의료관광 인증 병원·클리닉 | [data/README.md](의료관광_정보/data/README.md) |

### 3-4. 채용·산업

| API | 서비스 | 총 건수 | 설명 | 데이터 |
|-----|--------|--------|------|--------|
| 관광 채용정보 | tursmService | 21 | 관광업계 채용공고 (호텔·리조트·여행사 등) | [data/README.md](관광채용_정보/data/README.md) |

---

## 4. 다국어 관광정보

국문(KorService2)과 동일한 콘텐츠를 각 언어로 번역·제공. `contentid` 공유.

| API | 서비스 | 총 건수 | 언어 | 데이터 |
|-----|--------|--------|------|--------|
| 영문 | EngService2 | 15,862 | English | [data/README.md](다국어_영문_관광정보/data/README.md) |
| 일문 | JpnService2 | 15,779 | 日本語 | [data/README.md](다국어_일문_관광정보/data/README.md) |
| 중문 간체 | ChsService2 | 15,374 | 简体中文 | [data/README.md](다국어_중문간체_관광정보/data/README.md) |
| 중문 번체 | ChtService2 | 15,083 | 繁體中文 | [data/README.md](다국어_중문번체_관광정보/data/README.md) |
| 노어 | RusService2 | 2,170 | Русский | [data/README.md](다국어_노어_관광정보/data/README.md) |
| 서어 | SpnService2 | 3,106 | Español | [data/README.md](다국어_서어_관광정보/data/README.md) |
| 불어 | FreService2 | 2,185 | Français | [data/README.md](다국어_불어_관광정보/data/README.md) |
| 독어 | GerService2 | 2,095 | Deutsch | [data/README.md](다국어_독어_관광정보/data/README.md) |

---

## 데이터 수집 방법

```bash
cd docs/open-api
python3 fetch_all.py
```

- 각 API에서 10건씩 샘플을 수집해 `{API명}/data/result.json` 에 저장
- 지역별 3개 API는 현재 백엔드 데이터 미적재 상태 (총 건수 0)
- API 키: `.env` 파일 참고

---

## 공통 요청 파라미터

| 파라미터 | 값 | 설명 |
|---------|-----|------|
| `serviceKey` | (`.env` 참고) | 발급 키 (URL 인코딩 불필요 — `requests` 라이브러리 자동 처리) |
| `MobileOS` | `ETC` | OS 구분 |
| `MobileApp` | `tourism` | 앱 명칭 |
| `_type` | `json` | 응답 형식 |
| `numOfRows` | `10` | 페이지당 결과 수 |
| `pageNo` | `1` | 페이지 번호 |
