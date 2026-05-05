# 웰니스 건강휴양 관광정보 API 샘플 데이터

명상·치유·온천·한방 등 건강·휴양 특화 시설 (10건 / 전체 175건)

## 시설 목록

| 사진 | 시설명 | 주소 | 전화번호 |
|:---:|:---|:---|:---|
| <a href="http://tong.visitkorea.or.kr/cms/resource/54/2994054_image2_1.jpg"><img src="http://tong.visitkorea.or.kr/cms/resource/54/2994054_image3_1.jpg" width="120" alt="가곡유황온천&스파"></a> | **가곡유황온천&스파** | 강원특별자치도 삼척시 가곡면 가곡천로 1510 | 033-572-1800 |
| <a href="https://tong.visitkorea.or.kr/cms/resource/83/3414283_image2_1.jpg"><img src="https://tong.visitkorea.or.kr/cms/resource/83/3414283_image3_1.jpg" width="120" alt="가조 백두산천지온천"></a> | **가조 백두산천지온천** | 경상남도 거창군 가조면 온천길 161 | - |
| <a href="http://tong.visitkorea.or.kr/cms/resource/98/3401698_image2_1.JPG"><img src="http://tong.visitkorea.or.kr/cms/resource/98/3401698_image3_1.JPG" width="120" alt="강변스파랜드"></a> | **강변스파랜드** | 서울특별시 광진구 구의강변로 45 (구의동) | - |
| <a href="http://tong.visitkorea.or.kr/cms/resource/77/3040477_image2_1.jpg"><img src="http://tong.visitkorea.or.kr/cms/resource/77/3040477_image3_1.jpg" width="120" alt="강화해수랜드"></a> | **강화해수랜드** | 인천광역시 강화군 길상면 해안남로 13-12 | - |
| <a href="https://tong.visitkorea.or.kr/cms/resource/00/3516400_image2_1.jpg"><img src="https://tong.visitkorea.or.kr/cms/resource/00/3516400_image3_1.jpg" width="120" alt="거제도해수보양온천"></a> | **거제도해수보양온천** | 경상남도 거제시 수양로 507 | - |
| <a href="http://tong.visitkorea.or.kr/cms/resource/36/3038536_image2_1.jpg"><img src="http://tong.visitkorea.or.kr/cms/resource/36/3038536_image3_1.jpg" width="120" alt="공주 환경성 건강 센터"></a> | **공주 환경성 건강 센터** | 충청남도 공주시 수원지공원길 131-21 (금학동) | - |
| <a href="https://tong.visitkorea.or.kr/cms/resource/90/3519690_image2_1.jpg"><img src="https://tong.visitkorea.or.kr/cms/resource/90/3519690_image3_1.jpg" width="120" alt="국립김천치유의숲"></a> | **국립김천치유의숲** | 경상북도 김천시 증산면 수도길 1237-89 | 054-435-3412~4 |
| <a href="https://tong.visitkorea.or.kr/cms/resource/12/3490812_image2_1.jpg"><img src="https://tong.visitkorea.or.kr/cms/resource/12/3490812_image3_1.jpg" width="120" alt="국립대관령치유의숲"></a> | **국립대관령치유의숲** | 강원특별자치도 강릉시 성산면 대관령옛길 127-42 | 033-642-8382 |
| <a href="http://tong.visitkorea.or.kr/cms/resource/82/3574582_image2_1.JPG"><img src="http://tong.visitkorea.or.kr/cms/resource/82/3574582_image3_1.JPG" width="120" alt="국립대운산치유의숲"></a> | **국립대운산치유의숲** | 울산광역시 울주군 온양읍 대운상대길 225-92 | - |
| <a href="https://tong.visitkorea.or.kr/cms/resource/82/3501782_image2_1.jpg"><img src="https://tong.visitkorea.or.kr/cms/resource/82/3501782_image3_1.jpg" width="120" alt="국립양평치유의숲"></a> | **국립양평치유의숲** | 경기도 양평군 양동면 황거길 262-10 | 031-8079-7944 |

## 웰니스 유형

| 유형 코드 | 설명 |
|:---:|:---|
| 01 | 자연 치유 (삼림욕, 해수 치유) |
| 02 | 온천·스파 |
| 03 | 한방 치유 |
| 04 | 마음 치유 (명상, 요가, 템플스테이) |
| 05 | 운동·레포츠 (헬스 리조트) |

## 주요 특징

- **전체:** 175건 / 서비스: `WellnessTursmService`
- **필수 파라미터:** `langDivCd=0` (국문)
- **제공 정보:** 시설명, 주소, GPS, 전화번호, 웰니스 테마 코드, 이미지
