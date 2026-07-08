<!--
  GITHUB PROFILE README for Ashish Sharma
  Place this file as README.md in the special repo:  github.com/AI-ash/AI-ash
  All images are shields.io badges or the typing SVG / activity graph, which render
  reliably. No capsule-render / skillicons / github-readme-stats (those kept failing).
-->

<div align="center">

# Ashish Sharma
### AI Architect &nbsp;·&nbsp; Full-Stack Developer

<a href="https://iamashish.live">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=2FB673&center=true&vCenter=true&width=680&lines=I+build+AI+systems%2C+not+just+use+them;RAG+%7C+Agents+%7C+Voice+AI+%7C+Streaming+APIs;Production-grade+LLM+apps%2C+not+demos;FastAPI+%2B+LangChain+%2B+Next.js+%2B+Vector+Search" alt="Typing SVG" />
</a>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-iamashish.live-2FB673?style=for-the-badge&logo=vercel&logoColor=white)](https://iamashish.live)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ashish-sharma-ai)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/_Ashish_AI_)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ai.ashishsharma@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=AI-ash&style=for-the-badge&color=2FB673&label=PROFILE+VIEWS)

</div>

---

## 🧠 About

I'm an **AI Product Engineer and Full-Stack Developer** based in Delhi, India. I design and ship **AI systems end to end**, from retrieval and vector search to agent orchestration, streaming backends, and the automation that makes them useful in production. Not prompts glued to a UI, real pipelines that hold up long after the demo is over.

Right now I build production AI at **KW Group** and lead engineering as **Co-Founder & CTO at pyTan**. My work spans recruitment automation, learning platforms, voice assistants, and internal tooling that removes real, repetitive work. I care about latency, reliability, and shipping things people actually use.

```python
class AshishSharma:
    role      = "AI Product Engineer & Full-Stack Developer"
    based_in  = "Delhi, India"
    building  = ["voice AI", "RAG pipelines", "AI agents", "streaming APIs"]
    stack     = ["Python", "FastAPI", "LangChain", "Next.js", "TypeScript"]
    llms      = ["Groq (LLaMA-3)", "OpenAI", "Gemini", "Cohere"]
    databases = ["PostgreSQL", "Supabase", "Pinecone", "pgvector", "Redis"]
    mindset   = "learning by doing, ideas into real usable products"
    open_to   = "AI engineering & full-stack roles, collaborations"
```

---

## 🎯 What I Build

| | |
| :-- | :-- |
| 🤖 **LLM Applications** | Production apps on OpenAI, Groq, and Gemini with function calling and structured outputs |
| 🔍 **RAG & Vector Search** | Retrieval pipelines over Pinecone / pgvector with embeddings and semantic search |
| 🧩 **AI Agents & Automation** | Tool-calling agents that automate real, repetitive business workflows |
| 🗣️ **Voice AI** | Wake-word assistants with speech recognition and real-time streaming |
| ⚙️ **Backend & APIs** | Async FastAPI services, REST APIs, Server-Sent Events, system design |
| 🏗️ **Full-Stack Products** | Next.js front ends wired to AI backends, auth, payments, and CI/CD |

---

## 🧩 How I Build

The same architecture behind Jarvis, FloatChat, and the AI ATS I shipped at KW Group: retrieval, agents, and a streaming backend.

```python
from fastapi import FastAPI
from langchain.agents import create_agent

app = FastAPI()
agent = create_agent(model="llama-3.3-70b", tools=[search, retrieve])

@app.post("/chat")
async def chat(q: Query):
    ctx = store.similarity_search(q.text, k=6)      # RAG retrieval
    async for token in agent.astream(q.text, ctx):  # tool-calling agent
        yield token                                 # real-time SSE stream
```

`Ingest → Embed → Vector store → Retrieve → Generate → Stream`

---

## ⚡ Impact

- 🤖 Built an **AI-powered ATS** that screens **100 CVs in 2-3 minutes**, cutting recruiter screening time by **over 95%**
- 📈 Launched a **CRM-integrated website** that lifted **qualified leads by 30%** with full SEO / Answer Engine Optimization
- 🎓 Shipped **KW Skills**, a company-wide LMS adopted across the organization
- 🗣️ **Jarvis** voice assistant reached **12 GitHub stars** (FastAPI + Groq LLaMA 3.3, real-time SSE)
- 🧩 Design and deploy backend REST APIs and AI automation powering multiple production web apps

---

## 💼 Experience

**AI Product Engineer (Sr. Executive)** · KW Group, Noida &nbsp;`Mar 2026 - Present`
> Built the HR Portal AI ATS, the KW Homes site + CRM automation, KW Skills LMS, and internal AI tooling and REST APIs across the company's web apps.

**Co-Founder & CTO** · pyTan &nbsp;`Jan 2026 - Present`
> Lead technical architecture of AI products and backend systems; ship scalable REST APIs integrating LLM generation, automation, and structured extraction.

**Technical Lead** · Tech-A-Thon, ARSD College &nbsp;`Sep 2025 - Mar 2026`
> Led the college technical fest and a 10-member team; built the society website and a live competition portal.

**Software Development Intern** · Codeunia &nbsp;`Jul 2025 - Aug 2025`
> Developed Jarvis, a full-stack AI voice assistant (FastAPI, Groq LLaMA 3.3) with wake-word activation and real-time SSE streaming.

---

## 🚀 Featured Builds

| Project | What it is | Stack |
| :-- | :-- | :-- |
| **[Jarvis](https://github.com/AI-ash/Jarvis-FullStack-AI-Virtual-Assistant)** ⭐ | Full-stack AI voice assistant: wake-word, real-time SSE streaming, agent-style automation | `FastAPI` `Groq LLaMA 3.3` `SSE` |
| **[FloatChat](https://github.com/AI-ash/FloatChat)** | RAG system to query ARGO ocean-float data in natural language | `Pinecone` `Cohere` `FastAPI` `PostGIS` `Docker` |
| **[Home-AIth](https://github.com/AI-ash/Home-AIth)** | AI rental-trust platform with compatibility matching and fraud checks | `Gemini` `pgvector` `Next.js` `Stripe` |
| **[NomadAI](https://github.com/AI-ash/NomadAI)** | GenAI travel planner: itineraries from constraints via LLMs + structured outputs | `LLMs` `Next.js` `TypeScript` |
| **[AlterEgo](https://github.com/AI-ash/AlterEgo)** | Adaptive AI companion with conversational memory and custom personalities | `LangChain` `Groq` `Streamlit` |
| **[KWG Media Dashboard](https://github.com/it6-ash/KWG_media_dashboard)** | KW Group internal media & marketing analytics tooling | `Python` `Analytics` |

---

## 🔬 More Projects &nbsp;<sub>(live demos)</sub>

- 🌫️ **[Goofy Air Defender](https://goofy-air-defender.vercel.app)** — real-time AQI visualizer on a map, live data from the WAQI API
- ✍️ **[ForgeAI](https://forge-ai-article.vercel.app)** — AI article generator with a long-form writing pipeline `TypeScript`
- 📡 **[Aero Monitor](https://aero-monitor.vercel.app)** — live monitoring dashboard `JavaScript`
- 🎪 **[Tech-A-Thon](https://tech-a-thon-steel.vercel.app)** — official college tech-fest site and competition portal `TypeScript`

<sub>Personal open-source lives at **[@AI-ash](https://github.com/AI-ash)** · work builds at **[@it6-ash](https://github.com/it6-ash)** · [see all repositories →](https://github.com/AI-ash?tab=repositories)</sub>

---

## 🛠️ Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**AI & LLM**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=groq&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Cohere](https://img.shields.io/badge/Cohere-39594D?style=flat-square&logo=cohere&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-2FB673?style=flat-square)
![AI Agents](https://img.shields.io/badge/AI%20Agents-38A2B8?style=flat-square)

**Data, Cloud & Tools**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![Followers](https://img.shields.io/github/followers/AI-ash?style=for-the-badge&logo=github&logoColor=white&color=2FB673&labelColor=161b22)
![Repositories](https://img.shields.io/badge/Public%20Repos-17-38A2B8?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22)
![Focus](https://img.shields.io/badge/Focus-AI%20%2B%20Full--Stack-8957e5?style=for-the-badge&labelColor=161b22)

</div>

**⌨️ Most used languages** <sub>(by bytes, across public repos)</sub>

```text
TypeScript   ██████████████░░░░░░░░░░░░   58.0 %
Python       ███████░░░░░░░░░░░░░░░░░░░░   28.6 %
HTML         █▍░░░░░░░░░░░░░░░░░░░░░░░░░    5.7 %
JavaScript   ▉░░░░░░░░░░░░░░░░░░░░░░░░░░    3.5 %
CSS          ▌░░░░░░░░░░░░░░░░░░░░░░░░░░    2.4 %
```

<div align="center">

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=AI-ash&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=2FB673&line=38A2B8&point=ffffff&area=true" alt="contribution activity" />

</div>

---

## 🎓 Education & Certifications

- 🎓 **B.Sc. Physical Science with Computer Science** — University of Delhi (ARSD College) · `2023 - 2027`
- 📜 **Microsoft** — Generative AI &nbsp;·&nbsp; **IBM** — Generative AI for Software Developers
- 📜 **LangChain** — LLM Applications &nbsp;·&nbsp; **freeCodeCamp** — Python and Data Analysis

---

## 🌱 Currently

- 🔭 Building production AI products at **KW Group** and **pyTan**
- 🧠 Going deeper on **agentic AI**, evaluation, and reliable LLM systems at scale
- 🤝 Open to **AI engineering & full-stack roles**, freelance, and collaborations
- 💡 Philosophy: *learn by doing, ship real products, not demos*

---

<div align="center">

## 🤝 Let's build something intelligent

If you're working on AI products, automation, or anything worth shipping, let's talk.

[![Portfolio](https://img.shields.io/badge/iamashish.live-2FB673?style=for-the-badge&logo=vercel&logoColor=white)](https://iamashish.live)
[![Email](https://img.shields.io/badge/Say%20Hi-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ai.ashishsharma@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ashish-sharma-ai)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black)](https://www.buymeacoffee.com/ai_ash)

<sub>💬 "Coding is not just a skill, it's an adventure. Every bug is a mystery, every fix a victory."</sub>

</div>

<!--
  OPTIONAL: contribution snake animation.
  1. Add .github/workflows/snake.yml (content in snake-workflow.yml) to the AI-ash/AI-ash repo, run the Action once.
  2. Then uncomment the image below:
  ![snake](https://raw.githubusercontent.com/AI-ash/AI-ash/output/snake.svg)
-->
