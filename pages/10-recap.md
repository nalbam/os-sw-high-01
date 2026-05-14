---
layout: default
---

<div class="absolute inset-0 bg-[#1A1A2E] text-white px-16 py-12 overflow-hidden">

<SectionLabel section="RECAP" />
<div class="text-3xl mt-2 mb-8 font-bold text-white">두 프로젝트의 공통점</div>

<div class="grid grid-cols-5 gap-3 mt-12">
<div class="bg-white/5 border border-[#AAB1C7]/20 p-5 rounded" v-click.fade>
<div class="text-3xl font-bold text-[#F96167] mb-2 font-mono">01</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">DISCOVER</div>
<div class="text-sm text-[#CADCFC]">사람이 반복해서 하던 일을 발견했다</div>
</div>
<div class="bg-white/5 border border-[#AAB1C7]/20 p-5 rounded" v-click.fade>
<div class="text-3xl font-bold text-[#F96167] mb-2 font-mono">02</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">START SMALL</div>
<div class="text-sm text-[#CADCFC]">아주 작은 해결부터 시작했다</div>
</div>
<div class="bg-white/5 border border-[#AAB1C7]/20 p-5 rounded" v-click.fade>
<div class="text-3xl font-bold text-[#F96167] mb-2 font-mono">03</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">USE</div>
<div class="text-sm text-[#CADCFC]">직접 써 보면서 부족한 부분을 발견했다</div>
</div>
<div class="bg-white/5 border border-[#AAB1C7]/20 p-5 rounded" v-click.fade>
<div class="text-3xl font-bold text-[#F96167] mb-2 font-mono">04</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">FIX</div>
<div class="text-sm text-[#CADCFC]">안 되는 부분을 고쳐 더 좋게 만들었다</div>
</div>
<div class="bg-white/5 border border-[#AAB1C7]/20 p-5 rounded" v-click.fade>
<div class="text-3xl font-bold text-[#F96167] mb-2 font-mono">05</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">RECORD</div>
<div class="text-sm text-[#CADCFC]">만든 것을 기록으로 남겼다</div>
</div>
</div>

<PageFooter />

</div>

<!--
**[두 프로젝트의 공통점 · 약 1분 30초]**

두 프로젝트가 다르게 생겼지만 — **똑같은 다섯 단계** 로 만들어졌어요.
아까 강연 처음에 보여드린 그 다섯 단계예요.

- **01 DISCOVER** — 사람이 반복해서 하던 일을 발견했다.
- **02 START SMALL** — 아주 작은 해결부터 시작했다.
- **03 USE** — 직접 써 보면서 부족한 부분을 발견했다.
- **04 FIX** — 안 되는 부분을 고쳐 더 좋게 만들었다.
- **05 RECORD** — 만든 것을 기록으로 남겼다.

이 다섯 단계는 — 자동차든, 카메라든 — **다 똑같이 적용됩니다**.
도메인이 달라도 흐름은 같아요.

→ 다음 슬라이드 전환: "이걸 한 줄 공식으로 정리해 볼게요."
-->

---
layout: default
---

<div class="absolute inset-0 bg-[#F7F6F3] text-[#1A1A2E] overflow-hidden">

<div class="absolute top-12 left-16 right-16">
<SectionLabel section="RECAP" />
<div class="text-3xl mt-2 font-bold text-[#1A1A2E]">좋은 프로젝트의 공식</div>
<div class="text-sm text-[#6B6E80] mt-2">5단계 중 <span class="text-[#F96167] font-semibold">01 발견 · 02 시작</span>을 한 문장으로 압축한 것입니다</div>
</div>

<div class="absolute top-32 bottom-20 left-16 right-16 flex flex-col justify-center">

<div class="grid grid-cols-8 gap-2 items-center">
<div class="col-span-2 text-center bg-white p-5 rounded shadow-sm" v-click="1">
<div class="text-3xl font-bold text-[#F96167] mb-2">불편함</div>
<div class="text-xs text-[#6B6E80] uppercase tracking-widest font-mono">Discomfort</div>
</div>
<div class="text-center text-4xl font-bold text-[#F96167]" v-click="2">+</div>
<div class="col-span-2 text-center bg-white p-5 rounded shadow-sm" v-click="2">
<div class="text-3xl font-bold text-[#F96167] mb-2">반복</div>
<div class="text-xs text-[#6B6E80] uppercase tracking-widest font-mono">Repetition</div>
</div>
<div class="text-center text-4xl font-bold text-[#F96167]" v-click="3">+</div>
<div class="col-span-2 text-center bg-white p-5 rounded shadow-sm" v-click="3">
<div class="text-3xl font-bold text-[#F96167] mb-2">작게 해결</div>
<div class="text-xs text-[#6B6E80] uppercase tracking-widest font-mono">Small fix</div>
</div>
</div>

<div class="flex justify-center my-6" v-click="4">
<div class="text-4xl font-bold text-[#1A1A2E]">=</div>
</div>

<div class="grid grid-cols-8 gap-2">
<div class="col-start-4 col-span-2 bg-[#1A1A2E] text-white py-6 rounded-lg text-center" v-click.scale="4">
<div class="text-3xl font-bold mb-2">좋은 시작</div>
<div class="text-xs text-[#FBE3E4] uppercase tracking-widest font-mono">Good start</div>
</div>
</div>

<div class="grid grid-cols-3 gap-4 mt-10">
<div class="flex items-center gap-3" v-click.fade>
<span class="text-2xl text-[#F96167]">·</span>
<span class="text-sm text-[#2A2D43]">처음부터 크게 만들지 않는다</span>
</div>
<div class="flex items-center gap-3" v-click.fade>
<span class="text-2xl text-[#F96167]">·</span>
<span class="text-sm text-[#2A2D43]">내가 이해할 수 있는 범위에서 시작한다</span>
</div>
<div class="flex items-center gap-3" v-click.fade>
<span class="text-2xl text-[#F96167]">·</span>
<span class="text-sm text-[#2A2D43]">직접 써 보며 고친다</span>
</div>
</div>

</div>

<PageFooter light />

</div>

<!--
**[좋은 프로젝트의 공식 · 약 1분 30초]**

그래서 정리하면 — 좋은 프로젝트의 공식이 나옵니다.

**불편함 + 반복 + 작게 해결 = 좋은 시작**.

새로운 거 외우지 않으셔도 돼요. 아까 5단계 중에 **01 발견 + 02 시작** — 거기를 한 문장으로 줄인 거예요.

이렇게만 기억하시면 돼요.
- 처음부터 크게 만들지 않는다.
- 내가 이해할 수 있는 범위에서 시작한다.
- 직접 써보면서 고친다.

이게 다입니다. 어려운 거 아니에요.

→ 다음 슬라이드 전환: "자, 사례 두 개로 패턴까지 봤어요. 이제 정말 — 여러분 차례입니다."
-->
