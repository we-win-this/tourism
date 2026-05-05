# 관광 채용정보 API — 샘플 데이터

> 한국관광공사 tursmService · empmnInfoList · 총 21건

## 개요

한국관광공사 **관광인재개발원(academy.visitkorea.or.kr)** 에서 수집·관리하는 관광 분야 채용 공고.  
호텔·리조트·여행사·테마파크 등 관광 업계 일자리 정보를 제공.

---

## 샘플 10건

| 기업 로고 | 기업명 | 공고 제목 | 근무지 | 연봉/급여 | 경력 | 접수 마감 |
|----------|-------|----------|--------|----------|------|----------|
| <img src="https://academy.visitkorea.or.kr/cmm/fms/FileDown.do?atchFileId=20260420095821879531&fileSn=0" width="50"> | 해강개발 주식회사 강화리조트 | ★강화씨사이드리조트 곤돌라 유지보수 직원 모집... | 인천광역시 강화군 길상면 장흥로 217 | 26,000,000원 (연봉제) | 경력 | 채용 시 마감 |
| <img src="https://academy.visitkorea.or.kr/cmm/fms/FileDown.do?atchFileId=20260420095821879531&fileSn=0" width="50"> | 해강개발 주식회사 강화리조트 | 강화SEASIDE리조트(강화루지) 바리스타 정직원 채용... | 인천광역시 강화군 길상면 장흥로 217 | 26,000,000원 (연봉제) | 신입+경력 | 채용 시 마감 |
| <img src="https://academy.visitkorea.or.kr/cmm/fms/FileDown.do?atchFileId=20260423143036953446&fileSn=0" width="50"> | 주식회사 지씨에스 | [GS그룹] 엘리시안FS 청평인재개발원 식음서비스 채용... | 경기도 가평군 설악면 용문천길 251-56 | 0원 (—) | 경력 | 채용 시 마감 |
| <img src="https://academy.visitkorea.or.kr/cmm/fms/FileDown.do?atchFileId=20260421134050076461&fileSn=0" width="50"> | 주식회사 여행공방 | 여행공방 여행사 신입 및 경력직 채용... | 서울특별시 동작구 노량진로 151 (노량진동) | 0원 (—) | 신입+경력 | 채용 시 마감 |
| <img src="https://academy.visitkorea.or.kr/cmm/fms/FileDown.do?atchFileId=20260420095821879531&fileSn=0" width="50"> | 해강개발 주식회사 강화리조트 | [해강개발(주) 강화리조트] 환경미화 담당 직원 채용... | 인천광역시 강화군 길상면 장흥로 217 | 26,000,000원 (연봉제) | 신입+경력 | 채용 시 마감 |
| <img src="https://academy.visitkorea.or.kr/cmm/fms/FileDown.do?atchFileId=20260414112559128336&fileSn=0" width="50"> | (재)동해문화관광재단 | (재공고) 2026년 제1회 (재)동해문화관광재단 직원... | 강원특별자치도 동해시 도째비길 29 (묵호진동) | 0원 (—) | 신입+경력 | 20260504 |
| <img src="https://academy.visitkorea.or.kr/cmm/fms/FileDown.do?atchFileId=20250702101126045769&fileSn=0" width="50"> | 무브 | 수행기사 (임원, vip 컨시어지), 골프장, 공항이동... | 서울특별시 성동구 성수일로 10 (성수동1가) | 0원 (—) | 신입+경력 | 채용 시 마감 |
| <img src="https://academy.visitkorea.or.kr/cmm/fms/FileDown.do?atchFileId=20260403142037077665&fileSn=0" width="50"> | 주식회사 멥스인터내셔널코리아 | MICE 행사 운영 Account Manager 채용... | 서울특별시 강서구 마곡중앙4로 22 (마곡동) | 0원 (—) | 신입+경력 | 채용 시 마감 |
| <img src="https://academy.visitkorea.or.kr/cmm/fms/FileDown.do?atchFileId=20260331160715698742&fileSn=0" width="50"> | 쇼콜라트래블 | ?? 프랑스 여행사 OP 채용... | 부산광역시 남구 용주로 36 (용호동,데시앙 해링턴 플레이스 파크시티) | 2,160,000원 (월급제) | 신입+경력 | 채용 시 마감 |
| — | (주) 여행자클럽 | 여행 기획. 여행상담. 홈페이지 관리... | 서울특별시 종로구 필운대로 116 (신교동) | 2,400,000원 (월급제) | 경력 | 채용 시 마감 |

### 코드 체계

**급여 형태 (salStleCd)**

| 코드 | 설명 |
|------|------|
| JC0601 | 연봉제 |
| JC0602 | 월급제 |
| JC0603 | 시급제 |
| JC0604 | 일급제 |

**경력 구분 (crrDivCd)**

| 코드 | 설명 |
|------|------|
| JC0101 | 신입 |
| JC0102 | 경력 |
| JC0103 | 신입+경력 |

### 주요 필드

| 필드 | 설명 |
|------|------|
| `empmnInfoNo` | 채용공고 번호 |
| `corpoNm` | 기업명 |
| `corpoLogoFileUrl` | 기업 로고 URL |
| `empmnTtl` | 공고 제목 |
| `wrkpAdres` | 근무지 주소 |
| `wageAmt` | 급여 금액 |
| `salStleCd` | 급여 형태 |
| `rcptDdlnDe` | 접수 마감일 |
| `ordtmEmpmnYn` | 상시 채용 여부 (Y/N) |
