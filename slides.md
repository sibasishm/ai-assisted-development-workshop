---
theme: seriph
background: https://images.unsplash.com/photo-1677442136019-21780ecad995?w=1920
title: AI-Assisted Development - Foundations & Workflows
info:
  Demystifying how we can partner with AI to improve productivity,
  moving beyond hype to practical engineering workflows.
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
lineNumbers: true
colorSchema: dark
fonts:
  sans: 'Inter'
  serif: 'Playfair Display'
  mono: 'JetBrains Mono'
---

# AI-Assisted Development

<div class="text-2xl text-gray-300 mt-4 font-light tracking-wide">
AI-Assisted Development - Foundations & Workflows
</div>

<div class="mt-16 text-lg text-gray-400/80">
Demystifying how we can partner with AI to improve productivity,<br/>
moving beyond hype to practical engineering workflows.
</div>

<div class="abs-br m-10 text-sm text-gray-500">
  <carbon:user class="inline mr-2"/>Workshop by Smohanty
</div>

<style>
h1 {
  font-size: 3.8rem !important;
  font-weight: 700 !important;
  background: linear-gradient(135deg, #06b6d4 0%, #8b5cf6 50%, #ec4899 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  letter-spacing: -0.02em;
}
</style>

<!--
For those who don't know me, I've been wrestling with CSS and JavaScript for about 7 years now. I am a massive tinkerer at heart—I'm usually the first one to npm install that shiny new JS library just to see if it breaks everything.

But lately, I've been chasing a new title. I'm trying to transition from just a 'Frontend Dev' to a 'Wanna-be Vibe Coder.' I want to get to a place where I'm coding at the speed of thought, where the friction between having an idea and seeing it on screen disappears.

That's what brings us here today. We are going to talk about AI-Assisted Development.

My goal for the next hour is simple: I want to demystify this stuff. We're going to look past the Twitter hype and focus on practical engineering workflows. This is about how we can partner with AI to improve our productivity and build cool things, without losing our minds.
-->

---
transition: fade-out
layout: two-cols
layoutClass: gap-12
class: px-8
---

# <span class="text-red-400">MYTHS</span>
<div class="text-sm text-gray-500 mb-6">The "Junior" AI Mindset</div>

<div class="space-y-5">

<div v-click class="flex items-start gap-3 p-3 bg-red-500/5 rounded-lg border border-red-500/20">
  <div class="text-xl mt-0.5">❌</div>
  <div>
    <div class="font-semibold text-base text-red-300">Just a Faster Stack Overflow</div>
    <div class="text-gray-400 text-xs mt-1">It's not just for snippet retrieval; it's for context-aware generation.</div>
  </div>
</div>

<div v-click class="flex items-start gap-3 p-3 bg-red-500/5 rounded-lg border border-red-500/20">
  <div class="text-xl mt-0.5">❌</div>
  <div>
    <div class="font-semibold text-base text-red-300">Expecting Zero-Shot Perfection</div>
    <div class="text-gray-400 text-xs mt-1">Believing AI will handle complex system architecture in one prompt without iteration.</div>
  </div>
</div>

<div v-click class="flex items-start gap-3 p-3 bg-red-500/5 rounded-lg border border-red-500/20">
  <div class="text-xl mt-0.5">❌</div>
  <div>
    <div class="font-semibold text-base text-red-300">Replacing Deep System Knowledge</div>
    <div class="text-gray-400 text-xs mt-1">You need <em>more</em> understanding to verify AI output, not less.</div>
  </div>
</div>

</div>

::right::

# <span class="text-green-400">REALITY</span>
<div class="text-sm text-gray-500 mb-6">The "Senior" AI Mindset</div>

<div class="space-y-5">

<div v-click class="flex items-start gap-3 p-3 bg-green-500/5 rounded-lg border border-green-500/20">
  <div class="text-xl mt-0.5">✅</div>
  <div>
    <div class="font-semibold text-base text-green-300">Shifting Paradigm</div>
    <div class="text-gray-400 text-xs mt-1">Moving from "Code Writer" to "Editor-in-Chief" and "System Architect."</div>
  </div>
</div>

<div v-click class="flex items-start gap-3 p-3 bg-green-500/5 rounded-lg border border-green-500/20">
  <div class="text-xl mt-0.5">✅</div>
  <div>
    <div class="font-semibold text-base text-green-300">Managing Stochastic Processes</div>
    <div class="text-gray-400 text-xs mt-1">Accepting that coding is now probabilistic, requiring rigorous review loops.</div>
  </div>
</div>

<div v-click class="flex items-start gap-3 p-3 bg-green-500/5 rounded-lg border border-green-500/20">
  <div class="text-xl mt-0.5">✅</div>
  <div>
    <div class="font-semibold text-base text-green-300">Mastering the Dual Workflow</div>
    <div class="text-gray-400 text-xs mt-1"><strong>Agentic Flow</strong> (planning from vague reqs) vs. <strong>Editor Flow</strong> (iterating on existing code).</div>
  </div>
</div>

</div>

<div v-click class="mt-6 p-3 bg-cyan-500/10 rounded-xl border border-cyan-500/30">
  <carbon:scale class="inline text-cyan-400 mr-2"/>
  <span class="text-xs text-gray-300">AI coding is experimental. What <em>works</em> today might change next month.</span>
</div>

<style>
h1 {
  font-size: 2rem !important;
}
</style>

<!--
Since we are all experienced devs here, I'm going to skip the 'AI won't replace you' speech. You know that.

What this workshop is NOT about is treating AI as just a glorified snippets extension. If you are just using it to generate regex or center a div, you are leaving 90% of the value on the table.

It's also not about magic. We aren't going to pretend that you can give a vague prompt and get a production-ready microservice zero-shot.

The reality we are focusing on today is the paradigm shift in *how* we apply our expertise. We are moving from doing all the typing to becoming architects and lead editors of AI-generated code.

Critically, this workshop is about mastering two distinct workflows:

1. **The Agentic Flow:** Where we collaborate with the AI to plan and progressively build features from vague specs.

2. **The Editor Flow:** Where we dive into existing (often human-written) code to learn it, tweak it, and fix bugs using AI assistance.

The goal is to learn how to seamlessly toggle between these two modes.
-->

---
transition: slide-up
layout: default
class: px-12
---

# The Engines: Mapping Models to Workflows

<div class="grid grid-cols-2 gap-8 mt-6">

<div v-click class="relative">
  <div class="absolute -top-2 -left-2 w-16 h-16 bg-amber-500/20 rounded-full blur-xl"></div>
  <div class="p-5 bg-gradient-to-br from-amber-500/10 to-orange-500/5 rounded-xl border border-amber-500/30 relative">
    <div class="flex items-center gap-3 mb-4">
      <div class="text-3xl">🏎️</div>
      <div>
        <div class="font-bold text-amber-300 text-lg">Editor Flow</div>
        <div class="text-xs text-gray-500">Low Latency / High Throughput</div>
      </div>
    </div>
    <div class="space-y-2 text-sm text-gray-300">
      <div class="flex items-center gap-2"><carbon:flash class="text-amber-400"/> Inline autocomplete</div>
      <div class="flex items-center gap-2"><carbon:code class="text-amber-400"/> Quick refactors</div>
      <div class="flex items-center gap-2"><carbon:help class="text-amber-400"/> Explaining functions</div>
      <div class="flex items-center gap-2"><carbon:warning-alt class="text-amber-400"/> Fixing lint errors</div>
    </div>
    <div class="mt-4 pt-3 border-t border-amber-500/20 text-xs text-gray-500">
      <strong class="text-amber-200">Models:</strong> GPT-4o Mini, Haiku, Gemini Flash
    </div>
  </div>
</div>

<div v-click class="relative">
  <div class="absolute -top-2 -right-2 w-16 h-16 bg-violet-500/20 rounded-full blur-xl"></div>
  <div class="p-5 bg-gradient-to-br from-violet-500/10 to-purple-500/5 rounded-xl border border-violet-500/30 relative">
    <div class="flex items-center gap-3 mb-4">
      <div class="text-3xl">🧠</div>
      <div>
        <div class="font-bold text-violet-300 text-lg">Agentic Flow</div>
        <div class="text-xs text-gray-500">High Compute / Reasoning Chains</div>
      </div>
    </div>
    <div class="space-y-2 text-sm text-gray-300">
      <div class="flex items-center gap-2"><carbon:ibm-cloud-pak-manta-automated-data-lineage class="text-violet-400"/> Codebase analysis</div>
      <div class="flex items-center gap-2"><carbon:diagram class="text-violet-400"/> Multi-file planning</div>
      <div class="flex items-center gap-2"><carbon:search-locate class="text-violet-400"/> Complex debugging</div>
      <div class="flex items-center gap-2"><carbon:model-alt class="text-violet-400"/> Architecture design</div>
    </div>
    <div class="mt-4 pt-3 border-t border-violet-500/20 text-xs text-gray-500">
      <strong class="text-violet-200">Models:</strong> o1, Claude Sonnet, GPT-4o
    </div>
  </div>
</div>

</div>

<div v-click class="mt-6 p-4 bg-slate-800/50 rounded-xl border border-slate-600/30">
  <div class="flex items-center gap-3 mb-2">
    <carbon:machine-learning class="text-cyan-400 text-xl"/>
    <span class="font-semibold text-gray-200">The Underlying Foundation: Stochastic Token Prediction</span>
  </div>
  <div class="text-sm text-gray-400">
    At its core: <code class="text-cyan-300 bg-cyan-500/10 px-2 py-0.5 rounded">f(context, prompt) → likely_next_token</code>
    <span class="ml-2">It doesn't "know" code; it understands statistical patterns across vast datasets.</span>
  </div>
</div>

<style>
h1 {
  background: linear-gradient(135deg, #f59e0b 0%, #8b5cf6 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 2rem !important;
}
</style>

<!--
We all know these models are just predicting the next token based on probability distribution. But as practical engineers, we need to understand *which* engine to use for *which* workflow.

If you use a massive reasoning model for simple autocomplete, you'll destroy your flow state with latency. If you use a fast, lightweight model to plan a microservice architecture, you'll get junk.

We have two main engines for our two main workflows:

For the **Editor Flow**—when you are deep in a file, tweaking functions, and need instant feedback—we rely on **Fast Inference Models**. Think of this as your L1 cache. It needs to be instant.

For the **Agentic Flow**—when we need to step back, give vague requirements, and ask for a plan—we switch to **Reasoning Models**. These models literally 'think' (generate hidden chains of thought) before they respond. They are slower and more expensive, but they can handle the cognitive load of planning a multi-file feature implementation that we can then progressively build.

Mastering AI development is knowing which engine to engage at which moment.
-->

---
layout: center
class: text-center
---

# More Slides Coming Soon...

<div class="text-gray-400 mt-4">
Add your next slides below this section
</div>

<style>
h1 {
  background: linear-gradient(135deg, #06b6d4 0%, #8b5cf6 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
