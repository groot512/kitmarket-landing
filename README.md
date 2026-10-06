# 키트마켓 랜딩페이지 (Stage 4)

KIT MARKET / 키트마켓 — 진단키트 전문 + B2B 파트너 복제몰 소개용 싱글 페이지 랜딩입니다.

## 로컬에서 열기

정적 파일이므로 별도 빌드가 필요 없습니다.

```bash
# 방법 1 — 브라우저에서 직접 열기
xdg-open /workspace/kitmarket-landing/index.html
# macOS: open index.html
# Windows: start index.html

# 방법 2 — 로컬 서버 (권장: 모듈/폰트 CORS 이슈 방지)
cd /workspace/kitmarket-landing
python3 -m http.server 8080
# 브라우저에서 http://localhost:8080
```

## 구성

| 파일 | 설명 |
|------|------|
| `index.html` | 싱글 페이지 랜딩 (한국어 중심) |
| `styles.css` | 브랜드 팔레트 · 반응형 |
| `script.js` | 모바일 내비 · 스무스 스크롤 · 폼 토스트 |
| `assets/` | 로고 SVG / PNG |

## 섹션

1. Header — 로고 + 내비 (소개, 파트너몰, 제품 안내, 문의)
2. Hero — 슬로건, 가치 한 줄, CTA
3. Problem / Why now
4. Solution — 플래그십 몰 + 화이트라벨 복제몰
5. Features — 정품·허가, 용도 분리, 재고·Lot, 파트너 브랜딩
6. For partners — 복제몰 3단계
7. Trust / compliance 고지
8. Contact / waitlist (UI only)
9. Footer

## 브랜드

- 색상: navy `#12344D`, teal `#0C8A84`, P1 `#E6F4F3`, P2 `#08706B`
- 슬로건: 믿을 수 있는 진단키트, 파트너의 이름으로 / Trusted Kits. Your Brand.
- 로고: `assets/kitmarket_logo.svg` (네이비 — 밝은 배경용). 다크 섹션용 reverse는 추후.

## 배포

GitHub Pages 등 배포는 **보스 승인 후** 진행합니다. 현재는 로컬 산출물만 준비된 상태입니다.

## 관련 Notion

- 결과물: [4. 랜딩페이지](https://app.notion.com/p/3f158bed44e2814e9e1fcabdaeb0eb03)
- 브랜드 가이드: [2. 브랜드 가이드](https://app.notion.com/p/3f158bed44e2819f8e9fd327f88a1a85)
