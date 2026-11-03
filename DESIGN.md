# DESIGN.md - 웹사이트 디자인 레퍼런스

실제 사이트에서 computed style로 추출한 값 (2026-11-03 기준). 근사치이니 참고용.

## 요약 비교

| 사이트 | 분위기 | 주 폰트 | 포인트 컬러 | 배경 | 라운드 |
|---|---|---|---|---|---|
| Toss (토스) | 깔끔, 큰 타이포, 한국 핀테크 | Toss Product Sans | 블루 계열 + #1C1F25 | 흰색 / 어두운 섹션 #1C1F25 | 12 / 40px |
| Apple KR | 미니멀, 여백, 제품 중심 | SF Pro KR | #0071E3 (버튼), #2997FF (링크) | #FFFFFF, #F5F5F7, #000 | pill 980px, 5px |
| Stripe | 그라디언트, 가벼운 weight | sohne-var (300) | #533AFD, #7F7DFC | #FFF, #F8FAFD, #E5EDF5 | 4 / 6 / 8px |
| Linear | 다크 모드, 정제된 SaaS | Inter Variable | 블루 #6EAEFF 계열 | #08090A, #0F1011 | 6 / 8 / 12 / pill |
| Notion | 따뜻한 화이트, 에디토리얼 | NotionInter + Lyon Text | #0075DE | #FFF, #F9F9F8 | 4 / 8 / 12px |
| Daangn (당근) | 다크, 친근 | -apple-system | #FF6600 | #000, #16171B, #1D2025, #2B2E35 | 4~16, pill |

## Toss
- Font: Toss Product Sans OTF
- Text: #000, #333840 (본문), #FFF (다크 섹션), 다크 배경 #1C1F25
- Hero h2: 80px / 700 / line-height 96px
- Body: 16px / 400 / 25.6px / letter-spacing -0.32px (한글 자간 살짝 좁힘)
- Radius: 12px, 40px
- 특징: 큰 숫자/문구, 많은 여백, 타이트한 자간

## Apple (KR)
- Font: SF Pro KR / SF Pro Text
- Text: #1D1D1F, rgba(0,0,0,.56) 보조, 다크에서 #E8E8ED
- BG: #FFFFFF, #F5F5F7, #000000, nav rgba(29,29,31,.8) + blur
- Accent: #0071E3 버튼, #2997FF 링크
- Headline: 34~56px / 600, 본문 큰 사이즈 28px / 400 / 35px
- Radius: pill 980px 버튼, 5px
- 특징: 풀블리드 섹션 교차(흰/회/검), 제품 이미지 중심

## Stripe
- Font: sohne-var, weight 300 (얇고 고급스러움)
- Text: #061B31 (heading), #50617A, #64748D
- Accent: #533AFD, #7F7DFC / BG: #FFF, #F8FAFD, #E5EDF5
- h1: 48px / 300 / 55.2px / -0.96px, h2: 32px / 300 / -0.64px
- Radius: 4~8px
- 특징: 그라디언트 배경, 작은 radius, 가벼운 굵기

## Linear
- Font: Inter Variable, Berkeley Mono (코드)
- Text: #F7F8F8, #D0D6E0, #8A8F98, #62666D
- BG: #08090A (body), #0F1011 (카드), 보더 rgba(255,255,255,.02~)
- h1: 64px / 510 / 64px / -1.408px, h2: 48px / 510 / -1.056px, body 15px / 24px
- Radius: 6/8/12px, pill 9999px
- 특징: 다크, 미세한 보더/글로우, 음수 자간

## Notion
- Font: NotionInter, Lyon Text (세리프 포인트)
- Text: rgba(0,0,0,.9), 보조 #A39E98
- BG: #FFF, #F9F9F8 / Accent: #0075DE
- h1: 96px / 600 / -4.6px, h2: 54px / 700 / -1.88px
- Radius: 4/8/12px
- 특징: 따뜻한 뉴트럴, 큰 타이틀, 일러스트

## Daangn (당근)
- Font: -apple-system, Helvetica Neue
- Text: #F3F4F5, #DCDEE3, #B0B3BA, #868B94
- BG: #000, #16171B, #1D2025, #2B2E35 / Accent: #FF6600
- Button: #FF6600, 흰 글씨, radius 8px, padding 8px 14px
- Radius: 4/8/12/16px, pill
- 특징: 다크 + 오렌지 포인트, 친근한 라운드

## 공통 디자인 인사이트
1. 헤드라인은 크게(48~96px), 자간은 음수(-0.02em 내외)
2. 색은 뉴트럴 + 포인트 1개
3. radius는 사이트 안에서 2~3개만 사용
4. 섹션 간 여백 크게, 배경색 교차로 리듬감
5. 한글 사이트(토스, 당근)는 본문 자간을 살짝 좁히고 line-height 1.5~1.6
