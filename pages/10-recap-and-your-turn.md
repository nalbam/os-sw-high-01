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
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">FIX</div>
<div class="text-sm text-[#CADCFC]">잘 안 되는 부분을 고쳤다</div>
</div>
<div class="bg-white/5 border border-[#AAB1C7]/20 p-5 rounded" v-click.fade>
<div class="text-3xl font-bold text-[#F96167] mb-2 font-mono">04</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">USE</div>
<div class="text-sm text-[#CADCFC]">직접 써 보고 더 좋게 만들었다</div>
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
- **03 FIX** — 잘 안 되는 부분을 고쳤다.
- **04 USE** — 직접 써보고 더 좋게 만들었다.
- **05 RECORD** — 만든 것을 기록으로 남겼다.

이 다섯 단계는 — 자동차든, 카메라든 — **다 똑같이 적용됩니다**.
도메인이 달라도 흐름은 같아요.
-->

---
layout: default
---

<div class="absolute inset-0 bg-[#F7F6F3] text-[#1A1A2E] overflow-hidden">

<div class="absolute top-12 left-16 right-16">
<SectionLabel section="RECAP" />
<div class="text-3xl mt-2 font-bold text-[#1A1A2E]">좋은 프로젝트의 공식</div>
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

외우진 마시고요, 이렇게만 기억하시면 돼요.
- 처음부터 크게 만들지 않는다.
- 내가 이해할 수 있는 범위에서 시작한다.
- 직접 써보면서 고친다.

이게 다입니다. 어려운 거 아니에요.
-->

---
layout: default
---

<div class="absolute inset-0 bg-[#1A1A2E] text-white overflow-hidden">

<img src="./images/image2.png" class="absolute inset-0 w-full h-full object-cover opacity-25" />

<div class="absolute inset-0 bg-gradient-to-r from-[#1A1A2E]/95 via-[#1A1A2E]/85 to-[#1A1A2E]/60"></div>

<div class="absolute inset-0 px-16 py-12 flex flex-col justify-center">

<SectionLabel section="YOUR TURN" class="mb-8" />

<div class="text-5xl leading-tight font-semibold text-[#CADCFC] mb-12">이제 — <span class="text-[#F96167]">여러분 차례</span>입니다</div>

<div class="text-6xl leading-tight font-bold text-white">학교에서<br/><span class="text-[#F96167]">자동화할 수 있는</span><br/>일을 찾아 봅시다</div>

</div>

<PageFooter />

</div>

<!--
**[24페이지 · 4교시 끝 / 5교시 시작 공유 페이지]**

이 페이지에서 4교시를 마치고, 점심 후 5교시를 같은 페이지로 다시 시작합니다.

— 4교시 마무리 (약 30초) —
오전 시간은 여기까지예요. 두 사례 보면서 **다섯 단계** 가 똑같이 반복된 거 — 보셨죠.
그래서 이제 **여러분 차례** 입니다.
점심 잘 드시고 — 오후에 와서 **같이 만들어 봅시다**.
(점심 먹는 동안: "내가 학교에서 매일 불편한 거 한 가지" — 한 번만 생각해 보세요.)

🍱 — 점심 식사 — 🍱

— 5교시 재시작 (약 30초) —
다시 만났네요. 점심 맛있게 드셨어요?
오전에 봤던 다섯 단계 — **발견 → 시작 → 체험 → 수정 → 기록**. 그게 오후의 출발선이에요.
이제 진짜 **여러분 차례** 입니다.
학교에서 자동화할 수 있는 일을 — 같이 한번 떠올려 볼까요?
-->

---
layout: default
---

<div class="absolute inset-0 bg-[#F7F6F3] text-[#1A1A2E] px-16 py-12 overflow-hidden">

<SectionLabel section="YOUR TURN" />
<div class="text-3xl mt-2 mb-8 font-bold text-[#1A1A2E]">학교에서 떠올려 볼 수 있는 자동화</div>

<div class="grid grid-cols-5 gap-3 mt-10">
<div class="bg-white p-5 rounded shadow-sm border-t-4 border-[#F96167]" v-click.fade>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">DEADLINE</div>
<div class="text-base font-semibold text-[#1A1A2E] mb-2">수행평가 마감 알림</div>
<div class="text-xs text-[#6B6E80]">"마감일 자주 놓쳐요"</div>
</div>
<div class="bg-white p-5 rounded shadow-sm border-t-4 border-[#F96167]" v-click.fade>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">DUTY</div>
<div class="text-base font-semibold text-[#1A1A2E] mb-2">청소 당번 알림</div>
<div class="text-xs text-[#6B6E80]">"내 차례 자꾸 잊어요"</div>
</div>
<div class="bg-white p-5 rounded shadow-sm border-t-4 border-[#F96167]" v-click.fade>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">SCHEDULE</div>
<div class="text-base font-semibold text-[#1A1A2E] mb-2">학원·방과후 시간</div>
<div class="text-xs text-[#6B6E80]">"오늘 어디 가야 하지?"</div>
</div>
<div class="bg-white p-5 rounded shadow-sm border-t-4 border-[#F96167]" v-click.fade>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">STUDY</div>
<div class="text-base font-semibold text-[#1A1A2E] mb-2">매일 복습·과제 체크</div>
<div class="text-xs text-[#6B6E80]">"오늘 뭐 해야 하지?"</div>
</div>
<div class="bg-white p-5 rounded shadow-sm border-t-4 border-[#F96167]" v-click.fade>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">NOTICE</div>
<div class="text-base font-semibold text-[#1A1A2E] mb-2">단톡방·공지 챙기기</div>
<div class="text-xs text-[#6B6E80]">"공지 놓치면 큰일"</div>
</div>
</div>

<div class="mt-12 p-5 bg-[#1A1A2E] text-white rounded-lg text-center" v-click.scale>
<div class="text-base">정답은 없습니다 <span class="text-[#F96167] font-semibold">내가 자주 불편한 것</span>을 찾는 것이 먼저입니다</div>
</div>

<PageFooter light />

</div>

<!--
**[학교에서 떠올려볼 수 있는 자동화 · 약 1분]**

예시예요. 아까 손들기에서 봤던 다섯 가지를 그대로 자동화 후보로 옮겨봤어요.

- **DEADLINE** — 수행평가 마감 알림. "마감일 자주 놓쳐요"
- **DUTY** — 청소 당번 알림. "내 차례 자꾸 잊어요"
- **SCHEDULE** — 학원·방과후 시간. "오늘 어디 가야 하지?"
- **STUDY** — 매일 복습·과제 체크. "오늘 뭐 해야 하지?"
- **NOTICE** — 단톡방·공지 챙기기. "공지 놓치면 큰일"

정답은 없어요. **내가 자주 불편한 것** 을 찾는 게 먼저입니다.
다른 사람이 안 불편해도 — 내가 매일 불편하면 그게 좋은 출발점이에요.
-->
