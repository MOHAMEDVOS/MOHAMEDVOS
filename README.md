<h1 align="center">Mohamed Abdo</h1>

<p align="center">
  Software engineer in Cairo, Egypt<br>
  Open to remote software engineering roles
</p>

I build automation that replaces manual call and text QA, mostly in Python, FastAPI and React. I have worked at RESVA for five years, the last one as a software engineer, and the tools below run there every day.

### Projects

**[VOS](https://vos-tool.up.railway.app/)** is a call QA platform. It pulls recordings from ReadyMode dialers, transcribes them with AssemblyAI, and checks whether the agent tried to keep the lead after a "no". A library of 2,000+ phrases and a semantic match settle about 80% of calls, and only the unclear ones go to a Groq LLM. It replaced about 45 seconds of manual review per call, scores agents into the team's Google Sheet, and creates up to 200 agent accounts across the dialers in under a minute, a job that took 1 to 2 hours by hand.
*Python, FastAPI, React, TypeScript, PostgreSQL, Docker, AssemblyAI, Groq*

**Texting Audit Automation** reads SmarterContact conversations over REST and GraphQL with no browser, then flags compliance, attitude, professionalism and script mistakes with a local ML and rules pipeline. 20 parallel workers audit about 2,000 conversations in under 5 minutes, with no hosted AI calls and no per-conversation cost.
*Python, HTTPX, FAISS, scikit-learn*

**[IT-Check](https://vos-landing.vercel.app/)** is a Windows app that tests an agent's PC, microphone and connection, reports to a Flask dashboard, and runs scheduled checks and updates. It replaced manual remote checks over AnyDesk.
*Python, CustomTkinter, Flask*

**SpecCheck** reads a screenshot of a PC's specs with Tesseract.js OCR and compares the CPU against a database of about 2,800 benchmarked chips and the RAM against the onboarding minimum. It runs in the browser with no backend.
*JavaScript, Tesseract.js*

The source for these four is private because they run inside a company.

### Open source

**[VOS Connect](https://github.com/MOHAMEDVOS/VOS-connect)** tracks calls and texts for mail campaigns. It assigns tracking numbers, routes incoming leads to clients, and shows response and conversion rates per campaign. I built it as an in-house replacement for CallRail, which was unavailable in Egypt.
*React, TypeScript, FastAPI, PostgreSQL, Twilio*

**[Property Lookup](https://github.com/MOHAMEDVOS/Property-Lookup)** is a Chrome extension. Give it an address and it shows the Zillow and Redfin price, beds, baths and links side by side.
*JavaScript*

### Tech stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" alt="Railway">
  <img src="https://img.shields.io/badge/AssemblyAI-2545F6?style=for-the-badge&logo=assemblyai&logoColor=white" alt="AssemblyAI">
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white" alt="Groq">
</p>

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=MOHAMEDVOS&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MOHAMEDVOS&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" height="165">
</p>
