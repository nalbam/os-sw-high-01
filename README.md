# 프로그래머는 귀찮은 일을 그냥 두지 않는다

오산소프트웨어고등학교 1학년 특강 슬라이드.
*개발자의 기본기 — 자동화의 시작*

발표자: 유정열 (nalbam) — 당근 SRE / AWS AI Hero

청중·톤 가이드는 [`AUDIENCE.md`](./AUDIENCE.md)를 참고하세요.

## 실행

```bash
pnpm install
pnpm run dev      # http://localhost:3030
```

## 빌드 / 배포

```bash
pnpm run build    # → dist/
pnpm run export   # PDF 내보내기
```

`netlify.toml`, `vercel.json`, `amplify.yml`, `.github/workflows/deploy.yml`이 포함되어 Netlify·Vercel·AWS Amplify·GitHub Pages 모두에 배포 가능.

## 구조

```
slides.md                        진입점 (페이지 임포트만 담당)
pages/                           슬라이드 본문 (발표 순서대로 정렬)
  01-cover.md                    · 커버
  02-about.md                    · 발표자 소개
  03-background.md               · 당근 / AWS AI Hero 풀이
  04-opening.md                  · 강연 도입 + 손들기
  05-programmer-definition.md    · 프로그래머의 정의 + 나의 시작
  06-five-step-cycle.md          · 5단계 사이클
  07-automation-signals.md       · 자동화의 신호 + 거창하지 않아도
  08-case-deepracer.md           · 사례 1: DeepRacer Timer
  09-case-thermal.md             · 사례 2: 체온 알람
  10-recap.md                    · 두 프로젝트 공통점 + 공식
  11-your-turn.md                · 점심 분기 (24p) + 학교 자동화 예시
  12-tips.md                     · AI 사용법 + 고1 5가지 + 기록
  13-key-message.md              · 오늘 가져갈 한 문장
  14-handson.md                  · 핸즈온 (슬리도 + 라이브 + 자료실)
  15-qna.md                      · 감사 / Q&A
components/           재사용 컴포넌트
  SectionLabel.vue    · 섹션 헤더 (`{currentPage} · SECTION`)
  PageFooter.vue      · 우하단 페이지 번호 (`{currentPage} / {total}`)
  CountUp.vue         · 숫자 카운트업 애니메이션
pages/images/         슬라이드 이미지
```

## 페이지 추가/삭제

페이지 번호와 총 페이지 수는 Slidev의 `$nav.currentPage` / `$nav.total`로 자동 계산됩니다.
페이지를 추가·삭제할 때 다른 슬라이드의 번호를 손볼 필요가 없습니다.

새 슬라이드 안에서 다음 컴포넌트들을 사용하세요.

```vue
<SectionLabel section="FUNDAMENTALS" />   <!-- → 14 · FUNDAMENTALS -->
<SectionLabel>CASE STUDY · 01</SectionLabel>  <!-- 자유 텍스트 -->

<PageFooter />        <!-- 다크 배경용 (기본) -->
<PageFooter light />  <!-- 라이트 배경용 -->

<CountUp :to="4000" suffix="만명" />        <!-- 0 → 4,000만명 -->
<CountUp :to="600" prefix="+" suffix="개" />  <!-- 0 → +600개 -->
```

`CountUp` 은 `to`(필수), `duration`(기본 1500ms), `prefix`, `suffix`, `start`(기본 true) props 를 받습니다.

## 더 알아보기

[Slidev 문서](https://sli.dev/)
