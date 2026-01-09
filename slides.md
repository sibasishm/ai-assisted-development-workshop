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
transition: slide-left
layout: default
class: px-10
---

# Addressing the Buzzwords

<div class="grid grid-cols-3 gap-6 mt-6">

<div v-click class="relative group">
  <div class="absolute inset-0 bg-gradient-to-br from-blue-500/20 to-cyan-500/10 rounded-xl blur-sm group-hover:blur-md transition-all"></div>
  <div class="relative p-5 bg-slate-900/80 rounded-xl border border-blue-500/30 h-full">
    <div class="text-4xl mb-3">🤖</div>
    <div class="font-bold text-blue-300 text-lg mb-2">Agents</div>
    <div class="text-xs text-gray-400 mb-3">An AI loop that can <em>plan</em>, <em>execute</em>, and <em>iterate</em> without you typing every step.</div>
    <div class="text-xs text-gray-500 bg-slate-800/50 p-2 rounded-lg font-mono">
      "Fix the bug" →<br/>
      <span class="text-blue-300">reads error</span> →<br/>
      <span class="text-blue-300">searches files</span> →<br/>
      <span class="text-blue-300">applies fix</span> →<br/>
      <span class="text-blue-300">runs tests</span> →<br/>
      <span class="text-blue-300">retries if failed</span>
    </div>
  </div>
</div>

<div v-click class="relative group">
  <div class="absolute inset-0 bg-gradient-to-br from-rose-500/20 to-pink-500/10 rounded-xl blur-sm group-hover:blur-md transition-all"></div>
  <div class="relative p-5 bg-slate-900/80 rounded-xl border border-rose-500/30 h-full">
    <div class="text-4xl mb-3">🌫️</div>
    <div class="font-bold text-rose-300 text-lg mb-2">Hallucinations</div>
    <div class="text-xs text-gray-400 mb-3">When the AI <strong class="text-rose-300">confidently lies</strong>.</div>
    <div class="text-xs text-gray-500 mb-2">
      <strong class="text-gray-400">Why?</strong> It's a prediction engine, not a fact engine. It predicts the <em>most likely</em> next word—which might be a fake library.
    </div>
    <div class="text-xs p-2 bg-rose-500/10 rounded-lg border border-rose-500/20">
      <strong class="text-rose-300">Defense:</strong> "Trust but Verify." Always read the code.
    </div>
  </div>
</div>

<div v-click class="relative group">
  <div class="absolute inset-0 bg-gradient-to-br from-amber-500/20 to-yellow-500/10 rounded-xl blur-sm group-hover:blur-md transition-all"></div>
  <div class="relative p-5 bg-slate-900/80 rounded-xl border border-amber-500/30 h-full">
    <div class="text-4xl mb-3">🎟️</div>
    <div class="font-bold text-amber-300 text-lg mb-2">Tokens</div>
    <div class="text-xs text-gray-400 mb-3">The <strong class="text-amber-300">currency</strong> of AI.</div>
    <div class="text-xs text-gray-500 mb-2">
      <code class="text-amber-200 bg-amber-500/10 px-1 rounded">~0.75 words = 1 token</code>
    </div>
    <div class="text-xs text-gray-500 mb-2">
      <strong class="text-gray-400">Implication:</strong> More code in context = higher cost & slower latency.
    </div>
    <div class="text-xs p-2 bg-amber-500/10 rounded-lg border border-amber-500/20">
      <carbon:currency class="inline text-amber-400 mr-1"/>
      Be economical with what you feed it.
    </div>
  </div>
</div>

</div>

<style>
h1 {
  background: linear-gradient(135deg, #3b82f6 0%, #ec4899 50%, #f59e0b 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 2rem !important;
}
</style>

<!--
Before we dive into workflows, let's demystify some buzzwords you'll hear constantly.

**Agents** - This is when AI goes beyond just answering questions. An agent is an AI loop that can plan, execute, and iterate autonomously. You say "fix the bug" and it actually reads the error, searches your files, applies a fix, runs tests, and retries if something fails. This is the "Agentic Flow" we mentioned.

**Hallucinations** - This is when the AI confidently lies to you. It might import a library that doesn't exist or call a function with the wrong signature. Why? Because it's a prediction engine, not a fact engine. It predicts what's *most likely* to come next based on patterns, not what's *true*. Your defense is simple: Trust but Verify. Always read the code it generates.

**Tokens** - Think of these as the currency of AI. Roughly 0.75 words equals 1 token. Everything has a token cost - your prompt, the context you provide, and the response. More code in context means higher cost and slower "Time to First Token." Be economical with what you feed it.
-->

---
transition: fade-out
layout: default
class: px-10
---

# Context is King

<div class="grid grid-cols-2 gap-8 mt-4">

<div>
  <div v-click class="mb-6">
    <div class="flex items-center gap-2 mb-3">
      <carbon:warning-alt class="text-red-400 text-xl"/>
      <span class="font-bold text-red-300">Garbage In, Garbage Out</span>
    </div>
    <div class="text-sm text-gray-400">The AI only knows what you tell it. It cannot read your mind.</div>
  </div>

  <div v-click class="p-4 bg-gradient-to-br from-emerald-500/10 to-teal-500/5 rounded-xl border border-emerald-500/30">
    <div class="font-bold text-emerald-300 mb-3 flex items-center gap-2">
      The Context Sandwich Strategy
    </div>
    <div class="space-y-2">
      <div class="flex items-start gap-2 text-sm">
        <span class="text-emerald-400 font-mono text-xs bg-emerald-500/20 px-2 py-0.5 rounded">1</span>
        <div><strong class="text-emerald-200">Context:</strong> <span class="text-gray-400">"I am building a React component for..."</span></div>
      </div>
      <div class="flex items-start gap-2 text-sm">
        <span class="text-emerald-400 font-mono text-xs bg-emerald-500/20 px-2 py-0.5 rounded">2</span>
        <div><strong class="text-emerald-200">Current State:</strong> <span class="text-gray-400">"Here is the relevant file <code class="text-cyan-300">@App.tsx</code>..."</span></div>
      </div>
      <div class="flex items-start gap-2 text-sm">
        <span class="text-emerald-400 font-mono text-xs bg-emerald-500/20 px-2 py-0.5 rounded">3</span>
        <div><strong class="text-emerald-200">Task:</strong> <span class="text-gray-400">"Create a button that..."</span></div>
      </div>
      <div class="flex items-start gap-2 text-sm">
        <span class="text-emerald-400 font-mono text-xs bg-emerald-500/20 px-2 py-0.5 rounded">4</span>
        <div><strong class="text-emerald-200">Constraints:</strong> <span class="text-gray-400">"Use Tailwind CSS, no external libs."</span></div>
      </div>
    </div>
  </div>
</div>

<div v-click>
  <div class="font-bold text-cyan-300 mb-3 flex items-center gap-2">
    <carbon:at class="text-xl"/>
    Reference Mechanisms (Cursor)
  </div>
  <div class="space-y-3">
    <div class="p-3 bg-slate-800/50 rounded-lg border border-slate-600/30">
      <code class="text-cyan-300 font-mono">@Files</code>
      <div class="text-xs text-gray-500 mt-1">Tag specific files to include in context</div>
    </div>
    <div class="p-3 bg-slate-800/50 rounded-lg border border-slate-600/30">
      <code class="text-violet-300 font-mono">@Docs</code>
      <div class="text-xs text-gray-500 mt-1">Tag external documentation (e.g., "Read @NextJS docs")</div>
    </div>
    <div class="p-3 bg-slate-800/50 rounded-lg border border-slate-600/30">
      <code class="text-amber-300 font-mono">@Codebase</code>
      <div class="text-xs text-gray-500 mt-1">Scan the whole project <span class="text-red-400">(use sparingly!)</span></div>
    </div>
    <div class="p-3 bg-slate-800/50 rounded-lg border border-slate-600/30">
      <code class="text-emerald-300 font-mono">@Web</code>
      <div class="text-xs text-gray-500 mt-1">Search the web for current information</div>
    </div>
  </div>
</div>

</div>

<style>
h1 {
  background: linear-gradient(135deg, #10b981 0%, #06b6d4 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 2rem !important;
}
</style>

<!--
If the AI fails, 90% of the time it's because it lacked context. Did you show it the file where the variable is defined? Did you explain what framework you're using?

The Context Sandwich strategy is simple but powerful:
1. Start with background context - what are you building?
2. Show the current state - what files are relevant?
3. Define the task clearly - what do you want it to do?
4. Set constraints - what should it NOT do?

In Cursor, you have powerful reference mechanisms with the @ symbol:
- @Files lets you tag specific files
- @Docs lets you pull in external documentation
- @Codebase scans your whole project (but use this sparingly - it's expensive in tokens)
- @Web searches the internet for current info

Master these reference mechanisms and you'll see a dramatic improvement in AI output quality.
-->

---
transition: slide-up
layout: default
class: px-10
---

# MCPs and Tool Calling
<div class="text-sm text-gray-500 -mt-2 mb-4">The "Hands" of AI</div>

<div class="grid grid-cols-2 gap-8">

<div>
  <div v-click class="mb-6">
    <div class="flex items-center gap-3 mb-3">
      <div class="text-3xl">🔧</div>
      <div class="font-bold text-orange-300 text-lg">Tool Calling</div>
    </div>
    <div class="text-sm text-gray-400 mb-3">Giving the AI <strong class="text-orange-300">"hands"</strong>. Instead of just writing text, it can execute commands.</div>
    <div class="p-3 bg-slate-800/50 rounded-lg border border-slate-600/30 font-mono text-xs space-y-1">
      <div class="text-gray-500"># AI can now run:</div>
      <div><span class="text-orange-300">grep</span> <span class="text-gray-400">"pattern" ./src</span></div>
      <div><span class="text-orange-300">ls</span> <span class="text-gray-400">-la ./components</span></div>
      <div><span class="text-orange-300">read_file</span> <span class="text-gray-400">./package.json</span></div>
      <div><span class="text-orange-300">npm</span> <span class="text-gray-400">run test</span></div>
    </div>
  </div>

  <div v-click class="p-4 bg-gradient-to-br from-violet-500/10 to-purple-500/5 rounded-xl border border-violet-500/30">
    <div class="flex items-center gap-2 mb-2">
      <carbon:plug class="text-violet-400 text-xl"/>
      <span class="font-bold text-violet-300">MCP (Model Context Protocol)</span>
    </div>
    <div class="text-sm text-gray-400">
      The <strong class="text-violet-300">"USB-C standard"</strong> for AI apps.
    </div>
    <div class="text-xs text-gray-500 mt-2">
      Allows Claude/Cursor to connect to <em>any</em> data source without custom code.
    </div>
  </div>
</div>

<div v-click class="relative">
  <div class="absolute -top-4 -right-4 w-24 h-24 bg-cyan-500/10 rounded-full blur-2xl"></div>
  <div class="relative p-5 bg-slate-900/80 rounded-xl border border-cyan-500/30">
    <div class="font-bold text-cyan-300 mb-4 flex items-center gap-2">
      <carbon:connect class="text-xl"/>
      MCP Connections
    </div>
    <div class="grid grid-cols-2 gap-3">
      <div class="p-2 bg-slate-800/50 rounded-lg text-center">
        <carbon:data-base class="text-cyan-400 text-2xl mx-auto mb-1"/>
        <div class="text-xs text-gray-400">Postgres</div>
      </div>
      <div class="p-2 bg-slate-800/50 rounded-lg text-center">
        <carbon:logo-github class="text-cyan-400 text-2xl mx-auto mb-1"/>
        <div class="text-xs text-gray-400">GitHub</div>
      </div>
      <div class="p-2 bg-slate-800/50 rounded-lg text-center">
        <carbon:logo-slack class="text-cyan-400 text-2xl mx-auto mb-1"/>
        <div class="text-xs text-gray-400">Slack</div>
      </div>
      <div class="p-2 bg-slate-800/50 rounded-lg text-center">
        <carbon:document class="text-cyan-400 text-2xl mx-auto mb-1"/>
        <div class="text-xs text-gray-400">Google Drive</div>
      </div>
      <div class="p-2 bg-slate-800/50 rounded-lg text-center">
        <carbon:task class="text-cyan-400 text-2xl mx-auto mb-1"/>
        <div class="text-xs text-gray-400">Linear</div>
      </div>
      <div class="p-2 bg-slate-800/50 rounded-lg text-center">
        <carbon:folder class="text-cyan-400 text-2xl mx-auto mb-1"/>
        <div class="text-xs text-gray-400">File System</div>
      </div>
    </div>
    <div class="mt-4 p-2 bg-emerald-500/10 rounded-lg border border-emerald-500/20 text-xs text-center">
      <carbon:bot class="inline text-emerald-400 mr-1"/>
      <span class="text-emerald-300">Chatbot</span> → <span class="text-emerald-300">Workmate</span>
    </div>
  </div>
</div>

</div>

<style>
h1 {
  background: linear-gradient(135deg, #f97316 0%, #8b5cf6 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 2rem !important;
}
</style>

<!--
This is where AI gets really powerful. Tool Calling gives the AI "hands" - it can actually DO things, not just talk about them.

Instead of saying "you should run grep to find that pattern," it can actually run grep, read the results, and act on them. This is what enables the agentic workflows we talked about earlier.

MCP - Model Context Protocol - is like the USB-C standard for AI applications. It's an open protocol that lets Claude, Cursor, and other AI tools connect to any data source without needing custom integration code.

Think about it: your AI can now query your Postgres database, check GitHub issues, read Slack messages, access Google Drive documents, or interact with Linear tickets - all through a standardized protocol.

This transforms AI from a chatbot that just generates text into a workmate that can actually interact with your development environment and tools.
-->

---
transition: fade-out
layout: default
class: px-10
---

# Tips, Tricks & Workflow Advice

<div class="grid grid-cols-2 gap-6 mt-4">

<div class="space-y-4">

<div v-click class="p-4 bg-gradient-to-br from-cyan-500/10 to-blue-500/5 rounded-xl border border-cyan-500/30">
  <div class="flex items-center gap-2 mb-2">
    <carbon:zoom-out class="text-cyan-400"/>
    <span class="font-semibold text-cyan-300">Start Broad, Then Narrow</span>
  </div>
  <div class="text-xs text-gray-400">Ask for a plan first: <em>"How should we build this?"</em></div>
  <div class="text-xs text-gray-500 mt-1">Then ask for code once you agree on the approach.</div>
</div>

<div v-click class="p-4 bg-gradient-to-br from-amber-500/10 to-orange-500/5 rounded-xl border border-amber-500/30">
  <div class="flex items-center gap-2 mb-2">
    <carbon:debug class="text-amber-400"/>
    <span class="font-semibold text-amber-300">The Logging Strategy</span>
  </div>
  <div class="text-xs text-gray-400">If AI is stuck debugging, ask it to:</div>
  <div class="text-xs text-gray-500 mt-1 font-mono bg-slate-800/50 p-2 rounded">"Add verbose logging to trace the data flow"</div>
  <div class="text-xs text-gray-500 mt-1">Run the code, paste logs back. Let it debug from real data.</div>
</div>

<div v-click class="p-4 bg-gradient-to-br from-violet-500/10 to-purple-500/5 rounded-xl border border-violet-500/30">
  <div class="flex items-center gap-2 mb-2">
    <carbon:document-configuration class="text-violet-400"/>
    <span class="font-semibold text-violet-300">.cursorrules</span>
  </div>
  <div class="text-xs text-gray-400">Define your team's coding standards in a hidden file:</div>
  <div class="text-xs text-gray-500 mt-1 font-mono bg-slate-800/50 p-2 rounded space-y-0.5">
    <div>"Always use TypeScript"</div>
    <div>"Prefer functional components"</div>
    <div>"Use Tailwind for styling"</div>
  </div>
</div>

</div>

<div class="space-y-4">

<div v-click class="p-4 bg-gradient-to-br from-rose-500/10 to-red-500/5 rounded-xl border border-rose-500/30">
  <div class="flex items-center gap-2 mb-2">
    <carbon:warning class="text-rose-400"/>
    <span class="font-semibold text-rose-300">YOLO Mode (With Caution!)</span>
  </div>
  <div class="text-xs text-gray-400">Allowing AI to run terminal commands for you.</div>
  <div class="text-xs mt-2 space-y-1">
    <div class="text-emerald-400">✓ Great for: <span class="text-gray-500">npm install, git status</span></div>
    <div class="text-rose-400">✗ Dangerous for: <span class="text-gray-500 font-mono">rm -rf</span></div>
  </div>
</div>

<div v-click class="p-4 bg-gradient-to-br from-emerald-500/10 to-teal-500/5 rounded-xl border border-emerald-500/30">
  <div class="flex items-center gap-2 mb-2">
    <carbon:renew class="text-emerald-400"/>
    <span class="font-semibold text-emerald-300">Don't Fight the Chat</span>
  </div>
  <div class="text-xs text-gray-400">If the context gets messy and AI is confused:</div>
  <div class="text-xs text-emerald-300 mt-2 font-semibold">→ Just start a new chat.</div>
  <div class="text-xs text-gray-500 mt-1">Fresh context often solves the problem.</div>
</div>

<div v-click class="p-4 bg-gradient-to-br from-pink-500/10 to-fuchsia-500/5 rounded-xl border border-pink-500/30">
  <div class="flex items-center gap-2 mb-2">
    <carbon:idea class="text-pink-400"/>
    <span class="font-semibold text-pink-300">Iterate, Don't Regenerate</span>
  </div>
  <div class="text-xs text-gray-400">If output is 80% right, ask for specific fixes.</div>
  <div class="text-xs text-gray-500 mt-1">Don't regenerate from scratch - you'll lose the good parts.</div>
</div>

</div>

</div>

<style>
h1 {
  background: linear-gradient(135deg, #06b6d4 0%, #f59e0b 50%, #ec4899 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 2rem !important;
}
</style>

<!--
Let me share some practical tips that have improved my workflow significantly:

**Start Broad, Then Narrow** - Don't immediately ask for code. Ask for a plan first. "How should we approach building this feature?" Once you agree on the architecture, then ask for implementation.

**The Logging Strategy** - When AI gets stuck debugging, don't just keep asking it to "fix it." Ask it to add verbose logging, run the code yourself, and paste the actual logs back. Real data beats guessing every time.

**.cursorrules** - This is a game-changer. Create a file in your repo root that defines your team's standards. The AI will follow these rules automatically without you having to repeat them in every prompt.

**YOLO Mode** - Cursor can run terminal commands for you. This is amazing for things like npm install or running tests. But be careful - you probably don't want it running destructive commands without review.

**Don't Fight the Chat** - If the conversation has gone off the rails and the AI seems confused, just start fresh. A new chat with clean context is often faster than trying to course-correct a messy one.

**Iterate, Don't Regenerate** - If the output is mostly right, ask for specific fixes rather than regenerating from scratch. You'll lose the good parts if you start over.
-->

---
layout: center
class: text-center px-16
---

# Key Takeaways & Q&A

<div class="grid grid-cols-3 gap-6 mt-10 text-left">

<div v-click class="p-5 bg-gradient-to-br from-cyan-500/10 to-blue-500/5 rounded-xl border border-cyan-500/30">
  <div class="text-3xl mb-3">🎲</div>
  <div class="font-bold text-cyan-300 mb-2">Probabilistic Engine</div>
  <div class="text-sm text-gray-400">AI is a prediction machine, not a fact machine. Always verify its work.</div>
</div>

<div v-click class="p-5 bg-gradient-to-br from-emerald-500/10 to-teal-500/5 rounded-xl border border-emerald-500/30">
  <div class="text-3xl mb-3">👑</div>
  <div class="font-bold text-emerald-300 mb-2">Context is King</div>
  <div class="text-sm text-gray-400">Context management is the new "prompt engineering." Master the @ symbols.</div>
</div>

<div v-click class="p-5 bg-gradient-to-br from-violet-500/10 to-purple-500/5 rounded-xl border border-violet-500/30">
  <div class="text-3xl mb-3">🧠</div>
  <div class="font-bold text-violet-300 mb-2">Team Brain</div>
  <div class="text-sm text-gray-400">We're learning together. Share your wins and failures in our dev channel.</div>
</div>

</div>

<div v-click class="mt-12 p-6 bg-slate-800/50 rounded-2xl border border-slate-600/30 inline-block">
  <div class="flex items-center gap-4">
    <carbon:chat class="text-4xl text-cyan-400"/>
    <div class="text-left">
      <div class="font-bold text-xl text-gray-200">Questions?</div>
      <div class="text-sm text-gray-500">Let's discuss your current AI usage and workflows</div>
    </div>
  </div>
</div>

<div class="abs-bl m-10 text-xs text-gray-600">
  <carbon:code class="inline mr-1"/> Built with Slidev + AI assistance
</div>

<style>
h1 {
  background: linear-gradient(135deg, #06b6d4 0%, #10b981 50%, #8b5cf6 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 2.5rem !important;
}
</style>

<!--
Let's wrap up with the key takeaways:

**First: AI is probabilistic.** It's a prediction engine, not a fact engine. This means you need to verify everything it produces. The skill isn't in trusting AI blindly—it's in knowing how to review and validate its output efficiently.

**Second: Context is King.** If I could leave you with one thing, it's this. The quality of AI output is directly proportional to the quality of context you provide. Learn the @ symbols, master the context sandwich, and be intentional about what you feed the model.

**Third: We're building a Team Brain.** None of us have this figured out completely. The landscape is changing month by month. Share your discoveries in our dev channels—both the wins and the failures. We learn faster together.

Now, I'd love to hear from you. What's your current AI workflow? What's working? What's frustrating you? Let's make this a discussion.
-->
