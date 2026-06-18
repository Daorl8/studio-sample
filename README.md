# studio-sample

STUDIO NOON · 정오 — 서울 성수 프로필·인물 사진 스튜디오 샘플 (이피웹 포트폴리오).

- **목적:** 포트폴리오 다양화 — `샘플_다양성_매트릭스.md` ② 셀 점유: **포트폴리오-퍼스트 · 가로 스크롤 Selected Work · 필터형 그리드+라이트박스 · 히든 오버레이 내비 · 럭셔리 에디토리얼**.
- **팔레트:** 스타크 에디토리얼 **모노** — 쿨 페이퍼화이트 `#F5F4F2` + 잉크 `#141414` + 그레이. *사진이 색, 사이트는 흑백 갤러리 프레임.* (베이지·다크와 다른 또 다른 패밀리)
- **타입:** Latin 그로테스크(Space Grotesk) + 본문 Pretendard — 기존 세리프 샘플과 차별.
- **스택:** 정적 HTML/CSS/JS(단일 `index.html`). 빌드 없음.
- **호스팅:** Cloudflare Workers(무료·상업 허용). 배포 후 `/.git/config` 404 확인.
- **배포 주소(예정):** `studio-sample.lgt3232.workers.dev`

## 안전장치 (LESSONS §11·13·14)
고정바=`<div>` / `100svh` / blur 미사용 / 스크롤 rAF+passive / 모바일 리빌 off / `word-break:keep-all` / Formspree action 교체 / `.assetsignore` / OSM 지도.

## 미설정(납품 전)
Formspree form ID, 실제 촬영 사진, 연락처·주소·좌표, 가격·패키지.
