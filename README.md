<h1 align="center">Hi, I'm Axel AHO 👋</h1>
<p align="center">
  <b>AI / Agent Engineer — LLM · Automation · Cloud</b><br>
  Engineering student (AI & Data) who <b>ships production LLM agents</b>, not just notebooks.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/axelaho/">LinkedIn</a> ·
  <a href="https://yoh5.github.io/my_portfolio_website/">Portfolio</a> ·
  <a href="mailto:aho.axel5@gmail.com">Email</a>
</p>

---

🔭 I build autonomous **agents** — systems that plan, use tools, remember and self-correct — and the automation/cloud plumbing to run them in production.

Currently: **Cycle Ingénieur IA & Data** @ HESTIM (Morocco) · previously **B.Sc. Software Engineering** @ EPITECH (Benin).
🎯 **Looking for a final-year (PFE) internship in AI / Agent Engineering** — LLM applications, agent development, automation. Open to Morocco, France and remote.

### 🚀 Featured projects

Every agent below runs a **goal-directed loop with a measurable objective** and a **fail-open** design — never a prompt wrapper.

| Project | What it is | Stack |
|---|---|---|
| 🎙️ **Holokia Interview Agent** | Production AI agent that runs HR interviews over WhatsApp/web — 6 reasoning loops (planning, self-critique, memory, action-selection, learning), anti-cheating index, scored PDF reports. Live and used daily by recruiters. *(private client repo — case study on request)* | FastAPI · LangGraph · OpenAI/Groq · Supabase · Docker · Render |
| 🎯 **[Career Match Agent](https://github.com/Yoh5/career_match_agent)** [![tests](https://github.com/Yoh5/career_match_agent/actions/workflows/tests.yml/badge.svg)](https://github.com/Yoh5/career_match_agent/actions/workflows/tests.yml) | End-to-end application agent: sources internships from **public ATS APIs** (Greenhouse/Lever/Ashby) + RSS, ranks them against your target, then writes a tailored **CV (designed PDF)** and **cover letter (Word)** per offer. Two loops driven by *deterministic* objectives — ATS coverage and writing quality (language mixing, placeholders, typos) — behind an anti-fabrication gate. It prepares; the human reviews and sends. **123 tests.** | Python · FastAPI · OpenAI (tool-calling) · fpdf2 |
| 🤖 **[Tech Watch Agent](https://github.com/Yoh5/agent_veille_tech)** [![tests](https://github.com/Yoh5/agent_veille_tech/actions/workflows/tests.yml/badge.svg)](https://github.com/Yoh5/agent_veille_tech/actions/workflows/tests.yml) | Autonomous tech-watch agent: the LLM judges what matters, fetches full articles itself (SSRF-safe), synthesises trends, **remembers across runs** (topic drift) and **learns from 👍/👎 feedback**. **80 tests.** | Python · FastAPI · OpenAI/Anthropic · APScheduler |
| 🧹 **[Intelligent Data Cleaner](https://github.com/Yoh5/intelligent_data_cleaner)** [![tests](https://github.com/Yoh5/intelligent_data_cleaner/actions/workflows/tests.yml/badge.svg)](https://github.com/Yoh5/intelligent_data_cleaner/actions/workflows/tests.yml) | Agentic data cleaning: targets a **deterministic quality score** and iterates — profile → LLM picks & justifies a strategy per issue → apply → re-profile → keep the best version. Returns the cleaned file plus a standalone, AST-validated Python script. **16 tests.** | FastAPI · Next.js 14 · React 19 · Pandas · OpenAI · Docker |

### 🛠️ Tech I work with

**AI / Agents:** LLM apps · agentic loops (tool-calling, ReAct, self-critique, long-term memory) · LangGraph · OpenAI · Groq · Anthropic · RAG · prompt engineering
**Data / ML:** Python · Pandas · NumPy · scikit-learn · data profiling & cleaning
**Backend:** FastAPI · Django · Flask · Node.js · REST APIs · PostgreSQL · Supabase · Redis
**Cloud / DevOps:** Docker · CI/CD (GitHub Actions) · Render · AWS (EC2) · Linux · Nginx
**Also:** React / Next.js · TypeScript · PHP (Laravel)

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Yoh5&show_icons=true&hide_border=true&count_private=true" height="150" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yoh5&layout=compact&hide_border=true&langs_count=8" height="150" alt="Top languages"/>
</p>

> 💡 My most substantial work — the **Holokia interview agent**, in production and used daily by recruiters — lives in a private client repo. Happy to walk through its architecture on request.
