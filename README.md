# 미디어허브 랜딩 샘플 (10/29 내부 수정 반영)

미디어허브 언론홍보 랜딩페이지(benews-pr-landing)에 10/29 내부 수정사항을 반영한 **샘플 페이지**입니다.
빌드 과정 없는 정적 HTML 한 장(`index.html`)이라 Vercel에 그대로 배포됩니다.

## 반영 내용
- 2p 왜 미디어허브: "대행사가 아닙니다. 언론사입니다."
- 3p 응답·전문성: "'답이 늦다' '전문성이 없다' 걱정 마세요."
- 6p 숫자: 고객만족도 98% / 재계약률 97% / 1:1 전담기자 배정 / 24시간 당일 송출
- 7p Our Service: 홍보기사 / 지면기사 / 보도자료 배포 / 브랜드대상
- 신규 띠배너: 프리랜서 기자모집 / 언론사 창간 모집
- 8p 기사 유형: 브랜드대상 탭 추가
- 문의폼 관심 상품 7개

페이지 상단 "수정된 부분 표시" 버튼으로 바뀐 섹션을 확인할 수 있습니다. 분홍 라벨은 아직 확인이 필요한 항목입니다.

## Vercel 배포
1. Vercel → Add New → Project → 이 저장소(`allpass-web/mediahub`) Import
2. Framework Preset: **Other**, Build Command·Output Directory는 비워 둠
3. Deploy

## 주의
- 샘플 전용 페이지입니다. 문의폼은 실제로 접수되지 않습니다.
- 검색엔진 노출을 막아 두었습니다 (`robots: noindex`).
- 실제 서비스 코드는 `allpass-web/benews-pr-landing` 저장소에 있습니다.
