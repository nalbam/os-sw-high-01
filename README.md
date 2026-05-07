# 프로그래머는 귀찮은 일을 그냥 두지 않는다

오산소프트웨어고등학교 1학년 특강 슬라이드.
*개발자의 기본기 — 자동화의 시작*

발표자: 유정열 (nalbam) — 당근 SRE / AWS AI Hero

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

`netlify.toml`, `vercel.json`이 모두 포함되어 있어 양쪽 모두에 배포 가능.

## 구조

```
slides.md             진입점 (페이지 임포트만 담당)
pages/                슬라이드 본문 (총 37쪽)
  01-cover.md         · 커버
  01b-about.md        · 발표자 소개
  02-introduction.md  · 도입
  03-mindset.md       · 프로그래머의 정의
  03b-intro-personal.md   · SRE / AWS Hero / 당근 소개
  03c-mindset-philosophy.md  · 5단계 사이클
  04-fundamentals.md  · 자동화의 신호
  05-case-deepracer.md    · 사례 1: DeepRacer Timer
  06-case-thermal.md      · 사례 2: 체온 알람
  07-case-vibemon.md      · 사례 3: VibeMon
  08-recap-and-your-turn.md  · 정리·과제
  09-formula-and-tips.md     · 공식·팁
  10-closing.md       · 마무리
components/           재사용 컴포넌트
  SectionLabel.vue    · 섹션 헤더 (`{currentPage} · SECTION`)
  PageFooter.vue      · 우하단 페이지 번호 (`{currentPage} / {total}`)
pages/images/         슬라이드 이미지
```

## 페이지 추가/삭제

페이지 번호와 총 페이지 수는 Slidev의 `$nav.currentPage` / `$nav.total`로 자동 계산됩니다.
페이지를 추가·삭제할 때 다른 슬라이드의 번호를 손볼 필요가 없습니다.

새 슬라이드 안에서 다음 두 컴포넌트를 사용하세요.

```vue
<SectionLabel section="FUNDAMENTALS" />   <!-- → 14 · FUNDAMENTALS -->
<SectionLabel>CASE STUDY · 01</SectionLabel>  <!-- 자유 텍스트 -->

<PageFooter />        <!-- 다크 배경용 (기본) -->
<PageFooter light />  <!-- 라이트 배경용 -->
```

## 더 알아보기

[Slidev 문서](https://sli.dev/)
