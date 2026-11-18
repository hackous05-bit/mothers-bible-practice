# 어머니의 성경책 — 파트 연습 (SATB)

C.D. Tillman 작곡 · 김치곤 편곡 「어머니의 성경책」 합창 파트 연습 페이지.
빌드 과정 없는 정적 사이트(HTML 한 장 + 음원·악보 이미지)라 Vercel에 그대로 배포됩니다.

## 구성
- `index.html` — 연습 페이지 (가사·음높이 화면, 파트별 재생, 한 소절씩 따라 부르기)
- `pages/` — 악보 이미지 8쪽
- `samples/` — 피아노·합창 녹음 샘플 (FluidR3 GM 사운드폰트, MIT 라이선스)
- `audio/` — 파트별 미리 만든 음원 (내 파트 크게 / 내 파트 빼고)
- `vercel.json` — 정적 파일 캐시 설정

## 배포 (Vercel)
1. 이 저장소를 GitHub에 올립니다.
2. vercel.com → Add New → Project → 이 저장소 Import
3. Framework Preset: **Other**, Build Command: 비움, Output Directory: 비움(루트) → Deploy

파트 바로가기: `/#soprano`, `/#alto`, `/#tenor`, `/#bass`
