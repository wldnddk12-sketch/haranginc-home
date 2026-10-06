# 하랑아이앤씨 회사 홈페이지

- 공개 주소: https://www.haranginc.co.kr (haranginc.com → 자동 이동)
- 호스팅: Cloudflare Pages (이 저장소의 main 브랜치에 올리면 자동 배포)
- 빌드 과정 없음. 정적 HTML 한 페이지.

## 파일 구조
- `index.html` — 홈페이지 전체 (스타일·스크립트 포함)
- `assets/harang-symbol.png` — 로고 심볼 (회사소개서에서 추출, 원본 색 #1969BC)
- `assets/harang-wordmark.png` — HARANG 글자 로고
- `assets/favicon.png` — 브라우저 탭 아이콘

## 섹션 (index.html 안의 id)
`#about` 회사 소개 · `#services` 사업 분야 · `#why` 선택 이유 · `#process` 채용·관리 · `#network` 지사 · `#clients` 고객사 (스크립트의 CLIENTS 배열) · `#contact` 문의

## 아직 채워야 할 정보 (index.html에서 class="todo" 로 표시)
- 본사 상세 주소, 대표 이메일, 상담 시간
- 사업자등록번호, 근로자파견 허가번호
- 지사 목록 확정 (소개서: 용인·오산·평택·천안·청주 / 광고 보고에는 아산 있음)

## 공개 전 체크
- `<meta name="robots" content="noindex">` 삭제
- class="todo" 남아 있지 않은지 확인

## 수정 원칙
- 회사소개서에 있는 사실만 사용. "1등" 같은 최상급 표현은 근거 없으면 쓰지 않음.
- 고객사 로고는 동의받은 곳만 사용 (현재는 이름만 표시).
