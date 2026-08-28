<h1 align="center">Hey there, I'm Mohamed Ibrahim</h1>

<p align="center">
  <strong>AI Enthusiast & Builder</strong> · I build AI tools that sales and call center teams run on every day
</p>

<p align="center">
  <a href="https://github.com/MOHAMEDVOS"><img src="https://img.shields.io/github/followers/MOHAMEDVOS?label=Follow&style=social" alt="GitHub"></a>
</p>

---

### About Me

- I build software with AI tools to cut costs and save hours of manual work.
- Created **[VOS Tool](https://vos-tool.up.railway.app/)**, an AI call center platform. It transcribes and scores calls through a 3-layer system (2,000+ phrases, then semantic matching, then an LLM). It provisions up to 200 agents across 7 dialers in under a minute, which used to take 2 hours by hand. One click samples and scores agent calls across every dialer and writes the results into the team sheet. In production at RES-VA.
- Also built **[Texting Audit Automation](https://github.com/MOHAMEDVOS/TEXTING-AUDIT-AUTOMATION)**, an SMS audit platform. It scrapes conversations and runs a 3-tier ML system to score lead quality and catch compliance issues.
- And **[IT-Check (VOS Scanner)](https://vos-landing.vercel.app/)**, a Windows app that audits agent connections to prevent call drops. It replaced the manual AnyDesk checks, and RES-VA runs it now.

- Based in Egypt.

---

### Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="TailwindCSS">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white" alt="Groq">
  <img src="https://img.shields.io/badge/AssemblyAI-2545F6?style=for-the-badge&logo=assemblyai&logoColor=white" alt="AssemblyAI">
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" alt="Railway">
</p>

---

### Featured Projects

<table>
  <tr>
    <td width="50%">
      <h3 align="center"><a href="https://vos-tool.up.railway.app/">VOS Tool</a></h3>
      <p align="center">
        <a href="https://github.com/MOHAMEDVOS/vos-tool">
          <img src="https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo">
        </a>
      </p>
      <p>AI call center platform for Egyptian real estate. Transcribes calls with AssemblyAI, then scores them through a 3-layer system: 2,000+ phrases, semantic matching, and a Groq LLM. 80% of calls resolve in the first two layers.</p>
      <p>Bulk user creation provisions up to 200 agents across 7 ReadyMode dialers at once, in under a minute. The same job takes 1 to 2 hours by hand.</p>
      <p>AI scoring samples calls across all 7 dialers in one click, scores the agents, and appends the results to the team's Google Sheet, so nobody reviews call by call anymore.</p>
      <p>In production at RES-VA.</p>
      <p><strong>Stack:</strong> React · TypeScript · FastAPI · Python · PostgreSQL · Docker · AssemblyAI · Groq</p>
    </td>
    <td width="50%">
      <h3 align="center"><a href="https://vos-landing.vercel.app/">IT-Check (VOS Scanner)</a></h3>
      <p align="center">
        <a href="https://github.com/MOHAMEDVOS/IT-check">
          <img src="https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo">
        </a>
      </p>
      <p>A Windows app that audits agent connection stability to prevent call delays. It runs the hardware and network tests on its own, replacing manual remote checks over AnyDesk.</p>
      <p>In production at RES-VA.</p>
      <p><strong>Stack:</strong> Python · CustomTkinter · Flask</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">Texting Audit Automation</h3>
      <p align="center">
        <a href="https://github.com/MOHAMEDVOS/TEXTING-AUDIT-AUTOMATION">
          <img src="https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo">
        </a>
      </p>
      <p>An SMS audit platform. It scrapes SmarterContact over plain HTTP and GraphQL, then runs a 3-tier ML pipeline (phrase match, semantic embeddings, LLM) to score lead quality and flag compliance issues.</p>
      <p><strong>Stack:</strong> Python · httpx · Groq · FAISS · scikit-learn · PostgreSQL · Railway</p>
    </td>
    <td width="50%">
      <h3 align="center">SpecCheck (HR Tool)</h3>
      <p align="center">
        <a href="https://github.com/MOHAMEDVOS/speccheck">
          <img src="https://img.shields.io/badge/View_Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo">
        </a>
      </p>
      <p>A browser-based hardware checker for agent onboarding. Paste specs or upload a screenshot, and Tesseract.js pulls out the text and compares CPU and RAM against the minimum bar (Intel i5-6200U, 8 GB RAM). No backend.</p>
      <p>The CPU parser covers 20+ families, including Intel Core i, Ultra, Xeon and N-series, AMD Ryzen, Threadripper and FX, Apple Silicon, and Qualcomm Snapdragon.</p>
      <p>Image preprocessing (auto-crop, contrast boost, multi-pass recognition) makes the OCR reliable on Windows About screenshots.</p>
      <p><strong>Stack:</strong> Vanilla JS · Tesseract.js · HTML · CSS</p>
    </td>
  </tr>
</table>

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MOHAMEDVOS&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MOHAMEDVOS&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MOHAMEDVOS&theme=tokyonight&hide_border=true" alt="GitHub Streak">
</p>

---

<p align="center">
  <em>Mohamed Ibrahim Abdo</em>
</p>
