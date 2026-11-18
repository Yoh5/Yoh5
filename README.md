<h1 align="center">Axel AHO</h1>
<p align="center">
  <b>AI / Agent Engineer</b> — agents that act, and the evidence of what they did
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/axelaho/">LinkedIn</a> ·
  <a href="https://yoh5.github.io/my_portfolio_website/">Portfolio</a> ·
  <a href="mailto:aho.axel5@gmail.com">Email</a>
</p>

---

I build agents that decide things, and I make sure the deciding happens somewhere
I can test.

Two habits run through everything below:

- **The model observes, the code decides.** A language model is good at reading a
  situation and choosing words. It is bad at being a threshold. So the limit lives
  in code, or in the database, or in the gateway, and the model is handed the result.
- **Measure what everyone assumes, and publish the number that does not flatter.**
  Most of these repositories end in a table, and several of them report a hypothesis
  that turned out false next to the ones that held.

**Cycle Ingénieur IA & Data** @ HESTIM, Casablanca · previously **B.Sc. Software
Engineering** @ EPITECH, Benin.
🎯 **Looking for an internship in AI / Agent engineering** — agents, LLM evaluation,
AI security. Morocco, France, or remote.

### Agents you can hold to account

| Project | What it is |
|---|---|
| 🔍 **[Glass Box](https://github.com/Yoh5/glassbox)** | The flight recorder for AI agents: which decision, on what information, at what cost, and the path from an action back to the byte that caused it. Tamper-evident records, and an honest statement of what a hash chain does *not* prove. |
| 🦀 **[glassbox-verify](https://github.com/Yoh5/glassbox-verify)** | An independent verifier for Glass Box ledgers, in Rust with no dependencies, sharing no code with the Python that wrote them. Byte-identical canonical form, identical verdicts on four test ledgers. |
| 🗄️ **[Agent SQL bounded by Oracle](https://github.com/Yoh5/agent-sql-oracle)** | A text-to-SQL agent whose limits are held by the database, not the prompt: least-privilege account, row-level security (VPD) in PL/SQL, unified audit. Attacked 60 times per configuration: **0 / 60** attacks get through with both barriers, 26–31 / 60 without them. |
| 💳 **[Spend Mandate](https://github.com/Yoh5/paypal-mandat)** | A spending limit an agent cannot step past — caps, window and allowed merchants enforced by code *before* the call — plus a chained record linking the money that moved to the reasoning that moved it. *PayPal AI Hackathon.* |
| 🧾 **[Ghost Data Still Exists](https://github.com/Yoh5/ghost-data-still-exists)** | A deletion-audit agent that decides whether personal data is really gone, and reports the ceiling it cannot pass: **0.829** reached of the **0.912** the evidence allows. |

### Measurement and research

| Project | What it is |
|---|---|
| 📏 **[oracle-reach](https://github.com/Yoh5/oracle-reach)** | How much of a reference patch do a benchmark's tests actually constrain? On 129 SWE tasks: the tests *execute* 92.1 % of the added lines but *need* only 80.2 % — the rest survives being replaced by `pass`. *Kaggle Gemma 4 paper track.* |
| 🤝 **[What separates three sizes of the same model](https://github.com/Yoh5/tit-for-tat-llm)** | An LLM plays the iterated prisoner's dilemma against tit-for-tat at 30B, 120B and 550B. All three retaliate; what separates them is coming back after being punished: **0.13 / 0.87 / 1.00**, robust to four prompt variants. |
| ♟️ **[Tit-for-tat does not win](https://github.com/Yoh5/tit-for-tat)** | A tournament that measures what popular science claims about the prisoner's dilemma — and publishes the refuted hypotheses next to the results. |
| 🌡️ **[Bias Bounty — urban heat](https://github.com/Yoh5/bias-bounty-uhe)** | The only fine-grained urban-heat layer in the package is absent for 30.8 % to 62.4 % of tracts in every region, and the scorecard cannot report it as missing. |
| 🌱 **[Carbon Gate](https://github.com/Yoh5/carbon-gate)** | A CI pipeline that measures its own carbon cost and refuses to announce a saving it cannot prove. ISO/IEC 21031:2024, intervals everywhere, standard library only, 191 tests. |

### Data and security tooling

| Project | What it is |
|---|---|
| 🧹 **[Intelligent Data Cleaner](https://github.com/Yoh5/intelligent_data_cleaner)** [![tests](https://github.com/Yoh5/intelligent_data_cleaner/actions/workflows/tests.yml/badge.svg)](https://github.com/Yoh5/intelligent_data_cleaner/actions/workflows/tests.yml) | A gate before your database: each file gets a data contract for its intended use, is repaired within a budget, and is checked by a verifier that never trusts the cleaner. Says what it refused to invent. CSV, Excel and native Zeek logs (a million lines checked under contract). |
| 🚪 **[Call First](https://github.com/Yoh5/callfirst)** · [live](https://callfirst-bgtj.onrender.com/try) | Courier scams end at the front door, so does this: on the Ring doorbell already there, an unexpected visitor triggers *"call your family first"*, and the family is told when the door opens. |
| 🧪 **[ring-sandbox](https://github.com/Yoh5/ring-sandbox)** | Open pull request (#10) to a typed Python client and offline emulator for the Ring Partner API — webhooks, event history, OAuth refresh, chaos injection, pytest fixtures. |

### Voice agents

| Project | What it is |
|---|---|
| 🎙️ **[Probe](https://github.com/Yoh5/probe)** · [live](https://probe-wkiz.onrender.com) | A screening interview you cannot rehearse for: every question after the first is built from what the candidate just said. Code measures four delivery signals and picks the instruction; the model only words it. Six languages, 178 tests. *AssemblyAI.* |
| 🎧 **[Unscripted](https://github.com/Yoh5/unscripted)** · [live](https://unscripted.onrender.com) | The measurement behind Probe: notices when an answer sounds read rather than thought through. 89 % balanced accuracy on 20 labelled answers from one speaker — and the report says exactly that. *Speechmatics.* |

### Agents that do work

| Project | What it is |
|---|---|
| 🎯 **[Career Match Agent](https://github.com/Yoh5/career_match_agent)** | Sources internships from public ATS APIs, ranks them, writes a tailored CV and cover letter per offer behind an anti-fabrication gate. It prepares; the human sends. |
| 🤖 **[Tech Watch Agent](https://github.com/Yoh5/agent_veille_tech)** | Judges relevance, fetches full articles itself (SSRF-safe), synthesises trends, remembers across runs. |
| 📄 **[Tender Compliance Agent](https://github.com/Yoh5/tender-compliance-agent)** | Reads a public tender, extracts every administrative requirement, and tells you which ones your file does not meet yet. |

### On-chain

| Project | What it is |
|---|---|
| 💧 **[Runway](https://github.com/Yoh5/runway)** | **KeeperHub finalist.** A keeper that throttles Superfluid payment streams when a treasury runs short, under a bounded on-chain mandate — it can slow a stream, never redirect one. Proven on Sepolia. |
| 🔒 **[Fail Closed](https://github.com/Yoh5/fail-closed)** | Three merged pull requests to KeeperHub: a build script wiped two tracked files and exited green. Now it fails closed. |

### Web

Four demonstration sites for fictional businesses, each with its own design, in
French, English and Arabic (right-to-left), no framework:
[Dar Zellige](https://dar-zellige-demo.netlify.app) (restaurant, WhatsApp booking) ·
[Warda](https://warda-demo.netlify.app) (beauty institute, computed time slots) ·
[Mouja](https://mouja-demo.netlify.app) (sports club, weekly schedule) ·
[Silicium](https://silicium-demo.netlify.app) (repair shop, price estimator and ticket tracking).

### Production work

**Holokia Interview Agent** — an HR interview agent over WhatsApp and web, used by
recruiters: planning, self-critique, memory, an anti-cheating index and scored PDF
reports. Private client repository; happy to walk through the architecture.

### Tech

**AI / Agents** — LLM applications · agent loops (tool calling, self-critique, memory) ·
LLM evaluation · prompt-injection testing · LangGraph · OpenAI · Anthropic · Groq ·
AssemblyAI · Speechmatics
**Databases** — Oracle (SQL, PL/SQL, VPD, unified audit) · PostgreSQL · Supabase · Redis
**Backend** — Python · FastAPI · Django · Node.js · Rust · WebSockets
**Data** — Pandas · NumPy · SciPy · scikit-learn · data contracts
**Cloud / DevOps** — Docker · GitHub Actions · Render · Netlify · AWS EC2 · Linux
**Front** — React · Next.js · TypeScript · HTML/CSS (RTL) · Web Audio API
