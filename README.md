<!-- ① Header banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f172a,100:166534&height=170&section=header&text=Lucas%20Lam&fontSize=52&fontColor=ffffff&fontAlignY=42&desc=Associate%20Technical%20Product%20Owner%20%40%20Fun%20AI&descSize=18&descAlignY=70&animation=fadeIn" width="100%"/>
</p>

<!-- ② Animated typing line -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=22C55E&center=true&vCenter=true&width=640&lines=I+scope+AI+agents.+Then+I+build+them.;LLM+reasons+%E2%86%92+code+decides+what's+allowed.;No+agent+ships+without+an+eval+that+can+fail+it." alt="typing"/>
</p>

<!-- ③ Contact badges (flat-square, not for-the-badge) -->
<p align="center">
  <a href="https://www.linkedin.com/in/ltthinh111/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:ltthinh111@gmail.com"><img src="https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Based_in-Ho_Chi_Minh_City-22c55e?style=flat-square"/>
  <img src="https://img.shields.io/badge/Clients-SG_·_JP_·_VN-0f172a?style=flat-square"/>
</p>

---

<!-- ④ Code-block "about me" -->
```python
class LucasLam:
    role    = "Associate Technical Product Owner"
    company = "Functional AI Partners (Fun AI) — Singapore · B2B AI agents"
    focus   = ["LLM agents", "Voice AI", "RAG", "Agent evaluation"]

    def how_i_work(self):
        return [
            "Turn a vague client ask into a scoped MVP",
            "Let the LLM reason; let deterministic code decide what's allowed",
            "No agent ships without an eval that can fail it",
        ]

    fun_fact = "Same birthday as Freddie Mercury 🎤"
```

<!-- ⑤ GitHub-native alert block -->
> [!TIP]
> **Building now:** *Order Rescue*, an adaptive delivery-recovery agent for the **Sea × OpenAI Codex Hackathon** → [sea-hackathon](https://github.com/ThinhLam-git/sea-hackathon)

---

## 🔁 How I ship an AI agent

<!-- ⑥ Mermaid diagram — rendered natively by GitHub, no external service -->
```mermaid
flowchart LR
    A([Client ask]) --> B[Scope MVP<br/>+ acceptance criteria]
    B --> C[Spec-driven build<br/>with AI coding agents]
    C --> D{Eval harness<br/>passes?}
    D -- no --> C
    D -- yes --> E[Policy gate<br/>+ guardrails]
    E --> F([Ship & measure])
    F -. feedback .-> B
```

---

## 🛠 Things I've shipped

<!-- ⑦ Collapsible project cards -->
<details open>
<summary><b>📞 Voice Agent QA Harness</b> — a fake caller that tests a real voice agent</summary>
<br/>

A production Japanese phone agent scored **4.13/10** in manual UAT, and the score couldn't be reproduced. I built *"Mai-san"*, a synthetic caller who phones the agent, holds a realistic conversation, and scores every call automatically.

| Scenarios | Offline tests | Real test calls | Judge |
|:---:|:---:|:---:|:---:|
| **34** | **770+** | **250+** | LLM median-of-3 |

`Python` `ElevenLabs` `Vapi` `WebSockets` `LLM-as-judge`
</details>

<details>
<summary><b>💬 Enterprise AI Assistant</b> — chat, RAG and document generation for a Japanese enterprise</summary>
<br/>

- Streaming answers (SSE) with web search and image generation
- RAG over PDF, Word, Excel, PowerPoint and scanned files (pgvector + OCR)
- Generates Excel/PowerPoint files from schema-validated tool calls, with retry
- Per-user rate limits and a cost/token ledger for every call

`FastAPI` `Postgres + pgvector` `MinIO` `Docker` `Nginx`
</details>

<details>
<summary><b>🎓 AI Course Generator</b> — slides in, narrated e-learning course out</summary>
<br/>

- A 6-stage LangGraph pipeline turns PDFs, slides and URLs into Japanese courses with quizzes and narrated video
- **My part:** the course viewer, the media pipeline and the CI/CD deploy (Cloudflare Tunnel, self-hosted runner, rollback)

`LangGraph` `Next.js` `n8n` `ffmpeg` `GitHub Actions`
</details>

---

## 🧰 Toolbox

<!-- ⑧ Skill icons, split by layer -->
<table align="center">
  <tr>
    <td align="center"><b>Build</b></td>
    <td><img src="https://skillicons.dev/icons?i=python,fastapi,ts,react,nextjs,nodejs&perline=6"/></td>
  </tr>
  <tr>
    <td align="center"><b>Data</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,supabase,firebase&perline=6"/></td>
  </tr>
  <tr>
    <td align="center"><b>Ship</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,githubactions,cloudflare,nginx&perline=6"/></td>
  </tr>
  <tr>
    <td align="center"><b>AI</b></td>
    <td>
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
      <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
      <img src="https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white"/>
      <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white"/>
      <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Product</b></td>
    <td>
      <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white"/>
      <img src="https://img.shields.io/badge/Sprint_planning-555?style=flat-square"/>
      <img src="https://img.shields.io/badge/UAT_design-555?style=flat-square"/>
      <img src="https://img.shields.io/badge/Spec--driven_dev-555?style=flat-square"/>
    </td>
  </tr>
</table>

---

## 📊 Activity

<!-- ⑨ Contribution activity graph -->
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ThinhLam-git&bg_color=00000000&color=22c55e&line=22c55e&point=ffffff&area=true&area_color=22c55e&hide_border=true" width="100%"/>
</p>

<!-- ⑩ Stats + top languages side by side -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ThinhLam-git&show_icons=true&count_private=true&theme=transparent&hide_border=true&title_color=22c55e&icon_color=22c55e" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ThinhLam-git&layout=compact&theme=transparent&hide_border=true&title_color=22c55e" height="160"/>
</p>

<!-- ⑪ Trophies -->
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ThinhLam-git&theme=onestar&no-frame=true&no-bg=true&margin-w=6&column=7"/>
</p>

<!-- ⑫ Footer banner + visitor counter -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ThinhLam-git&label=profile%20views&color=22c55e&style=flat-square"/>
</p>
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:22c55e,100:0f172a&height=60&section=footer&text=Thanks%20for%20stopping%20by&fontSize=18&fontColor=ffffff" width="100%"/>
</p>
