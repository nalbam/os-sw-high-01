---
layout: default
transition: slide-up
---

<div class="absolute inset-0 bg-[#1A1A2E] text-white overflow-hidden">

<img src="./images/image7.png" class="absolute inset-0 w-full h-full object-cover opacity-25" />

<div class="absolute inset-0 bg-gradient-to-r from-[#1A1A2E]/95 via-[#1A1A2E]/85 to-[#1A1A2E]/60"></div>

<div class="absolute inset-0 px-16 py-12">

<SectionLabel class="mb-8">CASE STUDY · 02</SectionLabel>

<div class="grid grid-cols-2 gap-12 items-center h-full pb-16">

<div class="flex flex-col justify-center">

<div class="text-7xl leading-tight font-bold text-white">체온 알람<br/><span class="text-[#F96167]">서비스</span></div>

<div class="text-2xl text-[#CADCFC] mt-8 leading-snug">사람이 계속 보고 있던 화면을<br/><strong class="text-white">컴퓨터가 보게</strong> 만들기</div>

</div>

<div class="flex justify-center items-center">
<div class="rounded-2xl overflow-hidden shadow-2xl border-4 border-[#F96167]/30 max-w-md">
<img src="./images/doorman.jpg" class="w-full h-auto" />
</div>
</div>

</div>

</div>

<PageFooter />

</div>

<!--
**[사례 2 · 커버 · 약 30초]**

두 번째 — **체온 알람 서비스** 입니다.

이건 코로나 시기에 만든 거예요.
**열화상카메라로 체온을 재고, 일반 카메라로 안면인식을 해서,
정해둔 온도를 넘으면 알림을 보내는** 시스템이에요.

한 줄로 정리하면 — **사람이 계속 보고 있던 화면을, 컴퓨터가 보게 만든 이야기**.
-->

---
layout: default
---

<div class="absolute inset-0 bg-[#F7F6F3] text-[#1A1A2E] px-16 py-12 overflow-hidden">

<SectionLabel section="CASE STUDY 02" />
<div class="text-3xl mt-2 mb-8 font-bold text-[#1A1A2E]">문제는 여기에도 있었습니다</div>

<div class="text-3xl leading-snug font-semibold text-[#2A2D43] mt-10 mb-4">누군가가 계속 옆에 서서<br/><span class="text-[#F96167]">화면을 보고 있어야</span> 했다</div>

<div class="text-sm text-[#6B6E80] mb-12">사람이 계속 지켜봐야 하는 일은 — 좋은 자동화 후보입니다</div>

<div class="grid grid-cols-3 gap-6 mt-8">
<div class="bg-white p-6 rounded shadow-sm border-t-4 border-[#F96167]" v-click.fade>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">BEYOND HARDWARE</div>
<div class="text-base text-[#2A2D43]">열화상 카메라(체온이 색으로 보이는 카메라)만 있다고 끝이 아니다</div>
</div>
<div class="bg-white p-6 rounded shadow-sm border-t-4 border-[#F96167]" v-click.fade>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">RESPONSE TIME</div>
<div class="text-base text-[#2A2D43]">이상이 생긴 상황을 빨리 알려줘야 한다</div>
</div>
<div class="bg-white p-6 rounded shadow-sm border-t-4 border-[#F96167]" v-click.fade>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-3">RECORDS</div>
<div class="text-base text-[#2A2D43]">기록도 남아야 나중에 확인할 수 있다</div>
</div>
</div>

<PageFooter light />

</div>

<!--
**[문제는 여기에도 있었습니다 · 약 1분]**

문제는 이거였어요. 어디 건물 들어가면 입구에 열화상 카메라 있던 거 기억나세요?
체온이 색깔로 보이는 카메라요.

그 카메라 옆에 — **사람이 한 명 계속 서서 화면을 봐야 했어요**.
누가 열이 있나 없나 보려고요.

사람이 계속 지켜봐야 하는 일 — 이게 좋은 자동화 후보예요.
카메라만 있다고 끝나는 게 아니거든요.
이상이 생기면 빨리 알려줘야 하고, 기록도 남아야 합니다.
-->

---
layout: default
---

<div class="absolute inset-0 bg-[#1A1A2E] text-white px-16 py-12 overflow-hidden">

<SectionLabel section="CASE STUDY 02" />
<div class="text-3xl mt-2 mb-8 font-bold text-white">아이디어는 이렇게 흘러갑니다</div>

<div class="grid grid-cols-7 gap-2 items-center mt-16">

<div class="col-span-1 text-center" v-click="1">
<div class="w-20 h-20 mx-auto rounded-full bg-[#F96167] text-white flex items-center justify-center text-2xl font-bold font-mono mb-3">01</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-2">DETECT</div>
<div class="text-sm text-[#CADCFC]">열화상카메라로<br/>체온을 본다</div>
</div>

<div class="text-center text-3xl text-[#F96167]" v-click="2">→</div>

<div class="col-span-1 text-center" v-click="2">
<div class="w-20 h-20 mx-auto rounded-full bg-[#F96167] text-white flex items-center justify-center text-2xl font-bold font-mono mb-3">02</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-2">PROCESS</div>
<div class="text-sm text-[#CADCFC]">안면인식 +<br/>온도 비교</div>
</div>

<div class="text-center text-3xl text-[#F96167]" v-click="3">→</div>

<div class="col-span-1 text-center" v-click="3">
<div class="w-20 h-20 mx-auto rounded-full bg-[#F96167] text-white flex items-center justify-center text-2xl font-bold font-mono mb-3">03</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-2">STORE</div>
<div class="text-sm text-[#CADCFC]">기록을<br/>서버에 남긴다</div>
</div>

<div class="text-center text-3xl text-[#F96167]" v-click="4">→</div>

<div class="col-span-1 text-center" v-click="4">
<div class="w-20 h-20 mx-auto rounded-full bg-[#F96167] text-white flex items-center justify-center text-2xl font-bold font-mono mb-3">04</div>
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-2">NOTIFY</div>
<div class="text-sm text-[#CADCFC]">온도 초과 시<br/>메신저 알림</div>
</div>

</div>

<div class="mt-12 grid grid-cols-2 gap-4">
<div class="bg-white/5 border-l-4 border-[#F96167] p-4 rounded">
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-2">왜 라즈베리파이?</div>
<div class="text-sm text-[#CADCFC]"><strong class="text-white">열화상 카메라 + 일반 카메라</strong> 둘 다 연결하려고요</div>
</div>
<div class="bg-white/5 border-l-4 border-[#F96167] p-4 rounded">
<div class="text-xs uppercase tracking-widest text-[#F96167] font-mono mb-2">열화상 카메라</div>
<div class="text-sm text-[#CADCFC]"><strong class="text-white">FLIR Lepton 3.5</strong> — 사람 체온을 또렷이 볼 수 있는 열화상 센서</div>
</div>
</div>

<div class="mt-6 text-center text-lg text-[#CADCFC]">핵심은 기술의 이름이 아니라 — <span class="text-[#F96167] font-semibold">흐름</span>입니다</div>

<PageFooter />

</div>

<!--
**[아이디어는 이렇게 흘러갑니다 · 약 1분]**

그래서 흐름을 이렇게 만들었어요.

- **01 DETECT** — 열화상카메라로 체온을, 일반 카메라로 얼굴을 본다.
- **02 PROCESS** — 작은 컴퓨터가 안면인식을 하고, 정해둔 온도와 비교한다.
- **03 STORE** — 누가 언제 어떤 체온이었는지 서버에 기록한다.
- **04 NOTIFY** — 온도를 넘으면 메신저로 바로 알려준다.

라즈베리파이(작은 컴퓨터)를 쓴 이유는 — **열화상 카메라랑 일반 카메라, 둘 다 연결**해야 했거든요.

열화상 카메라는 — **FLIR Lepton 3.5**. 사람 체온을 또렷하게 볼 수 있는 센서예요.

핵심은 — **기술의 이름** 이 아니에요. **흐름** 입니다.
무엇을 감지해서, 어디에 저장하고, 누구한테 어떻게 알릴지 —
이 흐름만 머릿속에 그려지면, 어떤 도구로 만들지는 그 다음 문제예요.
-->

---
layout: default
---

<div class="absolute inset-0 bg-[#F7F6F3] text-[#1A1A2E] px-16 py-12 overflow-hidden">

<SectionLabel section="CASE STUDY 02" />
<div class="text-3xl mt-2 mb-8 font-bold text-[#1A1A2E]">이 프로젝트에서 배운 것</div>

<div class="text-4xl leading-tight font-bold text-[#1A1A2E] mt-12 mb-12">자동화는 <span class="text-[#F96167]">"사람이 계속 지켜보는 일"</span>을<br/>줄여 줍니다</div>

<div class="space-y-5 mt-10">
<div class="flex items-center gap-4" v-click.fade>
<span class="text-2xl text-[#F96167] font-bold">→</span>
<span class="text-lg text-[#2A2D43]">센서 + 코드 + 알림이 연결되면 — 유용해진다</span>
</div>
<div class="flex items-center gap-4" v-click.fade>
<span class="text-2xl text-[#F96167] font-bold">→</span>
<span class="text-lg text-[#2A2D43]">문제 해결은 한 가지 기술이 아니라 — 여러 조각의 연결이다</span>
</div>
<div class="flex items-center gap-4" v-click.fade>
<span class="text-2xl text-[#F96167] font-bold">→</span>
<span class="text-lg text-[#2A2D43]">사람을 편하게 하는 것이 — 좋은 개발이다</span>
</div>
</div>

<PageFooter light />

</div>

<!--
**[배운 것 · 약 1분]**

여기서 배운 거 — 자동화는 **'사람이 계속 지켜보는 일'을 줄여 준다**.

- 센서 + 코드 + 알림이 연결되면 갑자기 유용해진다.
- 문제 해결은 한 가지 기술이 아니라 — **여러 조각의 연결** 이다.
- 사람을 편하게 하는 게 — 좋은 개발이다.

→ 다음 슬라이드 전환: "마지막 세 번째 사례. 이건 제가 지금도 매일 쓰고 있는 도구예요."
-->
