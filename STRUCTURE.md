# STRUCTURE — studio-sample (STUDIO NOON)

단일 페이지(`index.html`). **포트폴리오-퍼스트** + 가로 스크롤 + 필터 그리드. 스타크 에디토리얼 모노.

```
index.html
├─ <head> : 메타, 폰트(Space Grotesk + Pretendard), 인라인 CSS(모노 토큰)
├─ .topbar (고정, 로고 + 햄버거) + .navoverlay (히든 풀스크린 오버레이 내비)
├─ #hero       Hero : 대형 에디토리얼 타이틀 + 대표 포트레이트
├─ #work       Selected Work : 가로 스크롤 스트립(드래그/스와이프)
├─ #portfolio  Portfolio : 필터 탭(전체/프로필/인물/가족/바디) + 매거진 그리드 + 라이트박스
├─ #about      About : 작가·스튜디오 소개
├─ #pricing    Pricing : 촬영 패키지(프로필/인물/가족/바디) + 포함 사항
├─ #info       안내 : 촬영 진행(예약→촬영→리터칭→전달) + 안내사항(보정 컷·원본·추가 보정 등)
├─ #book       Booking : 예약·문의 폼 + 카톡/네이버
├─ #location   Location : OSM 지도 + 길찾기
├─ 모바일 하단 퀵바 (.mbar, <div>) : 전화 / 카톡 / 예약
└─ <script> : 오버레이 내비 토글, 가로스크롤 드래그, 필터, 라이트박스, 데스크탑 리빌
```

## 디자인 토큰
- 컬러: `--paper:#F5F4F2` `--ink:#141414` `--grey:#8C8C8A` `--line:#E2E1DD` `--soft:#FAFAF9`
- 타입: 디스플레이 `Space Grotesk`(Latin) + `Pretendard` 헤비(한글), 본문 `Pretendard`. `word-break:keep-all`.
- 모션: 데스크탑 스크롤 페이드(≥861px), 모바일 정적.
