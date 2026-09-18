<h1 align="center">Axel AHO</h1>
<p align="center">
  <b>AI / Agent Engineer</b> — LLM agents, and the plumbing that keeps them honest
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/axelaho/">LinkedIn</a> ·
  <a href="https://yoh5.github.io/my_portfolio_website/">Portfolio</a> ·
  <a href="mailto:aho.axel5@gmail.com">Email</a>
</p>

---

I build agents that decide things, and I try very hard to make sure the deciding
happens somewhere I can test.

The pattern in most of what is below: **the model observes, the code decides.**
A language model is good at reading a situation and at choosing words. It is bad
at being a threshold. So the judgement lives in ordinary code with a number
attached to it, the model is handed the result, and the reasoning is written down
where a user can check it. That is also why these repositories have test suites
in them — every rule that matters has been broken on purpose to confirm its test
fails.

**Cycle Ingénieur IA & Data** @ HESTIM, Casablanca · previously **B.Sc. Software
Engineering** @ EPITECH, Benin.
🎯 **Looking for a final-year (PFE) internship in AI / Agent engineering** —
LLM applications, agent development, automation. Morocco, France, or remote.

### Voice agents

| Project | What it is |
|---|---|
| 🎙️ **[Probe](https://github.com/Yoh5/probe)** · [live](https://probe-wkiz.onrender.com) | A screening interview you cannot rehearse for. One question is written in advance; every question after it is built out of what the candidate just said. After each answer, code measures four signals of *delivery* against the same candidate a minute earlier and hands the interviewer one instruction — the language model never sees the numbers and never chooses the instruction, only the wording. The report shows that whole chain, checkable against the transcript. Six languages, 178 tests. *AssemblyAI Voice Agent API + Realtime Streaming, on two parallel connections.* |
| 🎧 **[Unscripted](https://github.com/Yoh5/unscripted)** · [live](https://unscripted.onrender.com) | The measurement behind Probe, on its own: a spoken interview that notices when an answer sounds read rather than thought through. Four signals — written-leaning vocabulary, disfluencies, run-on clauses, stretches without a pause — each relative to the speaker's own warm-up. 89% balanced accuracy holding out one session at a time, on 20 labelled answers from one speaker, and the report says exactly that on every page. *Speechmatics real-time STT.* |

### Agents that do work

| Project | What it is |
|---|---|
| 🎯 **[Career Match Agent](https://github.com/Yoh5/career_match_agent)** [![tests](https://github.com/Yoh5/career_match_agent/actions/workflows/tests.yml/badge.svg)](https://github.com/Yoh5/career_match_agent/actions/workflows/tests.yml) | Sources internships from public ATS APIs (Greenhouse, Lever, Ashby) and RSS, ranks them against a target, then writes a tailored CV and cover letter per offer. Two loops driven by deterministic objectives — ATS coverage, and writing quality measured as language mixing, placeholders and typos — behind an anti-fabrication gate. It prepares; the human sends. **123 tests.** |
| 🤖 **[Tech Watch Agent](https://github.com/Yoh5/agent_veille_tech)** [![tests](https://github.com/Yoh5/agent_veille_tech/actions/workflows/tests.yml/badge.svg)](https://github.com/Yoh5/agent_veille_tech/actions/workflows/tests.yml) | The LLM judges what matters, fetches the full articles itself (SSRF-safe), synthesises trends, remembers across runs, and learns from 👍/👎. **80 tests.** |
| 🧹 **[Intelligent Data Cleaner](https://github.com/Yoh5/intelligent_data_cleaner)** [![tests](https://github.com/Yoh5/intelligent_data_cleaner/actions/workflows/tests.yml/badge.svg)](https://github.com/Yoh5/intelligent_data_cleaner/actions/workflows/tests.yml) | Targets a deterministic quality score and iterates: profile → the LLM picks and justifies a strategy per issue → apply → re-profile → keep the best version. Returns the cleaned file and a standalone, AST-validated Python script. **16 tests.** |
| 📄 **[Tender Compliance Agent](https://github.com/Yoh5/tender-compliance-agent)** | Public bids get rejected on paperwork before anyone reads the offer. This one reads the tender, extracts every administrative requirement, and tells you which ones your file does not meet yet. |

### On-chain

| Project | What it is |
|---|---|
| 💧 **[Runway](https://github.com/Yoh5/runway)** | A keeper that decides which Superfluid payment streams to throttle when a treasury runs short, and executes through KeeperHub under a bounded on-chain mandate — it can slow a stream, never redirect one. Proven on Sepolia. |
| 🔒 **[Fail Closed](https://github.com/Yoh5/fail-closed)** | Three merged pull requests to KeeperHub: a build script was wiping two tracked files and exiting green. Now it fails closed. Small, but the kind of bug that eats an afternoon of someone else's week. |

### Production work

**Holokia Interview Agent** — an HR interview agent running over WhatsApp and web,
used daily by recruiters: planning, self-critique, memory, action selection, an
anti-cheating index, and scored PDF reports. Private client repository; happy to
walk through the architecture.

### Tech

**AI / Agents** — LLM applications · agentic loops (tool calling, self-critique,
long-term memory) · LangGraph · OpenAI · Anthropic · Groq · AssemblyAI ·
Speechmatics · RAG
**Backend** — Python · FastAPI · Django · Flask · Node.js · PostgreSQL ·
Supabase · Redis · WebSockets
**Data** — Pandas · NumPy · scikit-learn · feature engineering · profiling
**Cloud / DevOps** — Docker · GitHub Actions · Render · AWS EC2 · Linux · Nginx
**Front** — React · Next.js · TypeScript · Web Audio API

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Yoh5&show_icons=true&hide_border=true&count_private=true" height="150" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yoh5&layout=compact&hide_border=true&langs_count=8" height="150" alt="Top languages"/>
</p>
