<a href="https://hamzashabbir.dev">
  <img src="https://raw.githubusercontent.com/hamza-dev-tech/hamza-dev-tech/main/assets/banner.svg" alt="Malik Hamza Shabbir — AI Engineer and Full-Stack Developer" width="100%" />
</a>

<p align="center">
  <a href="https://hamzashabbir.dev"><img src="https://img.shields.io/badge/Portfolio-hamzashabbir.dev-00ff99?style=for-the-badge&labelColor=1c1c22" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/hamza-dev-tech/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1c1c22" alt="LinkedIn" /></a>
  <a href="mailto:hamzadevtech01@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1c1c22" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=hamza-dev-tech&label=Profile%20views&color=00ff99&style=for-the-badge" alt="Profile views" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3200&pause=900&color=00FF99&center=true&vCenter=true&width=760&lines=Agentic+AI+systems+that+run+in+production;RAG+pipelines+on+real+customer+data;Next.js+and+React+Native%2C+shipped+end+to+end;I+publish+the+numbers%2C+not+just+the+claims" alt="What I do" />
</p>

---

## About

I build AI products on my own, from the first idea to the day they go live, and
then I keep them running.

Most of what I ship is the unglamorous half of AI: the retrieval that has to
find the right chunk, the agent that has to refuse when it does not know, the
publish gate that stops a model outage from writing nonsense to a customer's
Google profile. I have learned most of what I know from things that broke in
production rather than from documentation.

I write about that too, including the times I got it wrong.

- **Now** — agentic SEO automation, autonomous review replies, and an open
  benchmark for agent memory systems
- **Stack** — Next.js, React Native, Node, Python, Postgres, MySQL, vector
  search, LangGraph, cloud
- **Based in** Pakistan, working with teams in Sweden, the US, the Philippines
  and the UK
- **Open to** contract work, and to being sent a system you want measured

---

## Open source worth your time

<table>
<tr>
<td width="55%" valign="top">

### [agent-memory-bench](https://github.com/hamza-dev-tech/agent-memory-bench)

An honest benchmark for AI agent memory: **Mem0, Zep, Letta, LangMem and
GoodMem** on the same 419-turn conversation, graded only on what each one
retrieves rather than what it can generate.

Vendors publish 80-93% on LoCoMo. Measured under one fixed, published method,
the best scored **57.6%**. Every number recomputes from the per-probe log in
the repo.

It also includes 28 adversarial probes where refusing is the correct answer,
because a memory system that always says something confidently is a liability.

<a href="https://hamzashabbir.dev/article/agent-memory-mem0-vs-letta-vs-zep-vs-langmem-benchmark-2026"><img src="https://img.shields.io/badge/Read%20the%20write--up-00ff99?style=flat-square&labelColor=1c1c22" alt="Write-up" /></a>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white&labelColor=1c1c22" alt="Python" />

</td>
<td width="45%" valign="top">

| System | Recall | Refused |
|---|---:|---:|
| GoodMem (tuned) | **57.6%** | 82.1% |
| GoodMem | 53.3% | 92.9% |
| Letta | 52.2% | 92.9% |
| Mem0 | 50.0% | 92.9% |
| LangMem | 45.7% | 85.7% |
| Zep | 37.0% | 92.9% |

<sub>One conversation, 120 probes, `gpt-4o-mini` at temperature 0, top 10 retrieved for every system.</sub>

</td>
</tr>
</table>

---

## Products I have shipped

| Product | What it does | Live |
|---|---|---|
| **Jorge Castro AI** | Agentic content and SEO automation, brand visibility tracking across LLMs | [jorgecastro.ai](https://jorgecastro.ai) |
| **Responsly** | Autonomous Google review replies in the business's own voice and the customer's language | [responsly.ai](https://responsly.ai) |
| **Skimming** | Multi-tenant RAG workspace for bulk video and document understanding | [skimming.ai](https://skimming.ai) |
| **FindUrLawyer** | Legal marketplace for the Philippines, matching clients to lawyers | [findurlawyer.com](https://www.findurlawyer.com) |
| **Saleslights** | AI sales video platform with avatar generation | [saleslights.com](https://saleslights.com) |
| **Video Funker** | AI sales video SaaS | [videofunker.ai](https://videofunker.ai) |
| **Soor Exchange** | Shariah-compliant crypto trading app, React Native | [Play Store](https://play.google.com/store/apps/details?id=com.soorx) |
| **Outreach Engine** | Cold email at scale: sourcing, AI-written openers, 30 mailboxes, reply classification | private |

<sub>Seventeen shipped products in total. The rest are on <a href="https://hamzashabbir.dev/work">hamzashabbir.dev/work</a>.</sub>

---

## What I build for clients

<table>
<tr>
<td valign="top" width="33%">

**AI in your product**
- RAG chatbots over your own docs
- Agents and workflow automation
- Adding AI features to an existing app
- AI search visibility (GEO / AEO)

</td>
<td valign="top" width="33%">

**Growth systems**
- Cold email infrastructure at scale
- Google reviews and reputation automation
- AI avatar video and content pipelines

</td>
<td valign="top" width="33%">

**Product engineering**
- MVPs, idea to launch in weeks
- Next.js and React web apps
- React Native mobile apps

</td>
</tr>
</table>

---

## Tools I actually reach for

<p>
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,js,nodejs,python,fastapi,tailwind&theme=dark" alt="Frontend and backend" /><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,docker,gcp,azure,vercel&theme=dark" alt="Data and infrastructure" /><br/>
  <img src="https://skillicons.dev/icons?i=git,github,linux,nginx,figma,expo&theme=dark" alt="Tooling" />
</p>

<sub>Plus the ones without a nice icon: LangGraph, LangChain, Qdrant, pgvector, Playwright, Cloud Tasks, Smartlead, and more model APIs than I would like to admit.</sub>

---

## Some numbers

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=hamza-dev-tech&show_icons=true&hide_border=true&bg_color=1c1c22&title_color=00ff99&text_color=c9cbd3&icon_color=00ff99&include_all_commits=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hamza-dev-tech&layout=compact&hide_border=true&bg_color=1c1c22&title_color=00ff99&text_color=c9cbd3&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hamza-dev-tech&hide_border=true&background=1c1c22&ring=00ff99&fire=00ff99&currStreakLabel=00ff99&sideLabels=c9cbd3&dates=7f8492&stroke=2a2a33" alt="Contribution streak" />
</p>

---

## Writing

I publish what I learn from production, including the failures.

- [**I benchmarked 5 AI agent memory systems. The best scored 57.6%.**](https://hamzashabbir.dev/article/agent-memory-mem0-vs-letta-vs-zep-vs-langmem-benchmark-2026) — including a correction to a benchmark I previously published without running
- [**Our LLM fallback worked perfectly. That was the problem.**](https://hamzashabbir.dev/article/llm-fallback-fail-closed-ai-publishing-postmortem-2026) — a fallback that published generic English replies to Swedish businesses for days while every dashboard stayed green

More at [hamzashabbir.dev/article](https://hamzashabbir.dev/article).

---

<div align="center">

### Working on something like this?

I take on a small number of contracts at a time. If you are adding AI to a
product, or choosing between memory and retrieval systems with real money on
the line, I am easy to reach.

<a href="https://hamzashabbir.dev/contact"><img src="https://img.shields.io/badge/Start%20a%20conversation-00ff99?style=for-the-badge&labelColor=1c1c22" alt="Contact" /></a>
<a href="mailto:hamzadevtech01@gmail.com"><img src="https://img.shields.io/badge/hamzadevtech01@gmail.com-1c1c22?style=for-the-badge&logo=gmail&logoColor=00ff99" alt="Email" /></a>

<sub>And if <a href="https://github.com/hamza-dev-tech/agent-memory-bench">agent-memory-bench</a> is useful to you, a star helps the next person find a number they can check rather than one they have to take on faith.</sub>

</div>
