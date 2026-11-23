# Mohamed Abdo

I build automation that replaces repetitive manual work, mostly in Python, FastAPI and React: call and text audits, dialer setup, HR checks, reports and PC checks. I have worked at RESVA for five years, the last one as a software engineer, and the tools below run there every day. I'm based in Cairo, Egypt, and open to remote software engineering roles.

## Projects

<table>
  <tr>
    <td width="50%"><a href="https://vos-tool.up.railway.app/"><img src="assets/card-vos.png" alt="VOS, call QA platform. About 45 seconds of manual review saved per call. Python, FastAPI, AssemblyAI, Groq. Private, in production." width="100%"></a></td>
    <td width="50%"><img src="assets/card-texting.png" alt="Texting Audit, SMS audit service. 2,000 conversations audited in under 5 minutes. Python, HTTPX, FAISS, scikit-learn. Private." width="100%"></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://vos-landing.vercel.app/"><img src="assets/card-itcheck.png" alt="IT-Check, PC and network scanner. Replaces manual AnyDesk checks. Python, CustomTkinter, Flask. Private, in production." width="100%"></a></td>
    <td width="50%"><img src="assets/card-speccheck.png" alt="SpecCheck, OCR hardware checker. 2,800 benchmarked CPUs in the database. JavaScript, Tesseract.js. Private in production." width="100%"></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://github.com/MOHAMEDVOS/VOS-connect"><img src="assets/card-vosconnect.png" alt="VOS Connect, call tracking. An in-house CallRail alternative. React, TypeScript, FastAPI, PostgreSQL, Twilio. Open source. in production " width="100%"></a></td>
    <td width="50%"><a href="https://github.com/MOHAMEDVOS/Property-Lookup"><img src="assets/card-lookup.png" alt="Property Lookup, Chrome extension. Zillow and Redfin side by side. JavaScript. Open source in production." width="100%"></a></td>
  </tr>
</table>

The source for the first four is private because they run inside a company. VOS Connect and Property Lookup are open source.

<details>
<summary>What each one does</summary>

**VOS** pulls recordings from ReadyMode dialers, transcribes them with AssemblyAI, and checks whether the agent tried to keep the lead after a "no". A library of 2,000+ phrases and a semantic match settle about 80% of calls, and only the unclear ones go to a Groq LLM. It scores agents into the team's Google Sheet and creates up to 200 agent accounts across the dialers in under a minute, a job that took 1 to 2 hours by hand.

**Texting Audit Automation** reads SmarterContact conversations over REST and GraphQL with no browser, then flags compliance, attitude, professionalism and script mistakes with a local ML and rules pipeline. 20 parallel workers do the work, with no hosted AI calls and no per-conversation cost.

**IT-Check** tests an agent's PC, microphone and connection, reports to a Flask dashboard, and runs scheduled checks and updates.

**SpecCheck** reads a screenshot of a PC's specs with Tesseract.js OCR, compares the CPU against about 2,800 benchmarked chips and the RAM against the onboarding minimum, and runs in the browser with no backend.

**VOS Connect** assigns tracking numbers, routes incoming leads to clients, and shows response and conversion rates per campaign. **Property Lookup** shows the Zillow and Redfin price, beds, baths and links for an address.

</details>

## Stack

<img src="assets/stack.png" alt="Stack. Languages: Python, TypeScript, JavaScript, SQL. Backend: FastAPI, Flask, HTTPX, PostgreSQL, Docker. Frontend: React, Vite, Tailwind CSS. Services: AssemblyAI, Groq, Twilio, Railway, Git." width="100%">
