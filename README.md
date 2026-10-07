<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:EE5308,100:DE3D9E&text=Dhyey%20Tandel&fontColor=F4F0E9&fontSize=56&fontAlignY=36&desc=Backend%20%C2%B7%20Distributed%20Systems%20%C2%B7%20Applied%20ML&descAlignY=58&descSize=18&animation=fadeIn" alt="Dhyey Tandel"/>
</p>

<p align="center">
  <a href="https://dhyeytandel.in">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=EE5308&center=true&vCenter=true&width=640&lines=Software+Engineer+%C2%B7+Backend+%26+Distributed+Systems;Ex-SWE+Intern+%40+Schneider+Electric;B.Tech+CSE+%40+MIT+Bengaluru+'27;Open+to+SDE+roles+for+2027" alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <a href="https://dhyeytandel.in"><img src="https://img.shields.io/badge/Portfolio-dhyeytandel.in-17140F?style=for-the-badge&logo=googlechrome&logoColor=EE5308" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/dhyey-tandel"><img src="https://img.shields.io/badge/LinkedIn-dhyey--tandel-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:dhyeytandel2005@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-EE5308?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Cloud Practitioner"/>
</p>

<br/>

<table>
<tr>
<td width="58%" valign="top">

### 👋 About me

I like building the parts of a system that have to keep working when things go wrong: commit logs that survive torn writes, transport that survives packet loss, route planners that repair themselves when someone cancels.

Most of my repos are built from first principles and ship with the tests and benchmarks to back up what the README says.

🎯 **Open to** SDE, backend and ML engineering roles for 2027<br/>
📍 Bengaluru, India

</td>
<td width="42%" valign="top">

### 💼 Experience

**Schneider Electric**<br/>
<sub>Software Engineering Intern · May to Jul 2025</sub>

- **40M items/week** ingested into Azure, automated
- Reporting queries: **1 week → 12 hours**
- **40 API endpoints** tested, **20+ bugs** caught pre-release

</td>
</tr>
</table>

## 🚀 Featured work

<table>
<tr>
<td width="50%" valign="top">

#### ⚡ [FluxMQ](https://github.com/DhyeyTandel/FluxMQ)
Distributed message queue built from scratch: commit log, consumer groups, leader/follower replication.

**170,000+ msgs/sec** (425x) at **8.2 ms p99**, zero acknowledged-message loss when brokers are killed mid-stream.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/asyncio-17140F?style=flat-square"/> <img src="https://img.shields.io/badge/Hypothesis-17140F?style=flat-square"/>

</td>
<td width="50%" valign="top">

#### 🦅 [Kestrel](https://github.com/DhyeyTandel/kestrel)
OpenAI-compatible LLM inference server for Apple Silicon: Rust router over a Python MLX worker, binary IPC on a unix socket.

Admission control cuts **p99 time-to-first-token 2.6x** under overload; IPC overhead measured at **0.32% of a decode step**.

<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/MLX-17140F?style=flat-square&logo=apple&logoColor=white"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🚖 [Cabal](https://github.com/DhyeyTandel/Cabal)
Employee transport planner solving a heterogeneous-fleet vehicle routing problem with ride-time limits.

Heuristics **benchmarked against optimal**; repairs plans on cancellations without reshuffling everyone.

<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>

</td>
<td width="50%" valign="top">

#### 🌐 [MiniNET](https://github.com/DhyeyTandel/MiniNET)
Network stack simulator: Go-Back-N transport and Bellman-Ford routing over a deterministic lossy link.

Byte-identical transfers at **20% data + 10% ACK loss**; 3-hop topology converges in **2.12 s**.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/asyncio-17140F?style=flat-square"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📈 [NSE Arena](https://github.com/DhyeyTandel/NSE_ARENA)
Real-time paper-trading competitions on live NSE data, with seasonal leaderboards.

Custom **PineScript-lite engine** and **Gemini-powered agents** that trade alongside users.

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>

</td>
<td width="50%" valign="top">

#### ♿ [Accessible Components](https://github.com/DhyeyTandel/a11y-hard-parts)
Eleven ARIA patterns people get wrong: focus traps, comboboxes, live regions, sliders.

Zero dependencies, **187 browser-run tests**, VoiceOver-verified. [Live demo →](https://dhyeytandel.github.io/a11y-hard-parts/)

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/WCAG%202.2-17140F?style=flat-square"/>

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it is | Stack |
| --- | --- | --- |
| [AI Shield](https://github.com/DhyeyTandel/AI-Shield) | ML intrusion detection and prevention on live packet capture, trained on CICIDS2017 | scikit-learn, Flask, Scapy |
| [Resume Screener](https://github.com/DhyeyTandel/Resume_Screener) | Human-in-the-loop resume screening with prompt-injection detection and an append-only audit log | FastAPI, React, Ollama |
| [Claude Usage Tracker](https://github.com/DhyeyTandel/Claude_Usage_Tracker) | Menu-bar widget for Claude Code limits and Anthropic API spend, with encrypted key storage | Electron, TypeScript |
| [AutoAssess](https://github.com/DhyeyTandel/autoassess) | Vehicle-damage segmentation and severity grading for insurance claims | YOLOv8-seg, PyTorch |
| [Cisco Demand Forecasting](https://github.com/DhyeyTandel/Cisco-Demand-Forecasting) | Ensemble model for product-demand forecasting | XGBoost, pandas |

</details>

## 🧰 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,java,ts,js,c,rust,spring,fastapi,flask,nodejs&theme=dark&perline=10" alt="Languages and frameworks"/><br/>
  <img src="https://skillicons.dev/icons?i=react,postgres,redis,mongodb,mysql,docker,aws,azure,githubactions,pytorch,sklearn&theme=dark&perline=11" alt="Data, infra and ML"/>
</p>

## 📊 GitHub activity

<p align="center">
  <img src="./profile-summary-card-output/github_dark/0-profile-details.svg" width="100%" alt="Contribution overview"/>
</p>
<p align="center">
  <img src="./profile-summary-card-output/github_dark/1-repos-per-language.svg" width="49%" alt="Repos per language"/>
  <img src="./profile-summary-card-output/github_dark/2-most-commit-language.svg" width="49%" alt="Most committed languages"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=DhyeyTandel&theme=dark&hide_border=true&background=17140F&ring=EE5308&fire=EE5308&currStreakLabel=EE5308&sideLabels=F4F0E9&dates=A89E90&currStreakNum=F4F0E9&sideNums=F4F0E9" width="80%" alt="Contribution streak"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DhyeyTandel/DhyeyTandel/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DhyeyTandel/DhyeyTandel/output/github-snake.svg"/>
    <img src="https://raw.githubusercontent.com/DhyeyTandel/DhyeyTandel/output/github-snake.svg" alt="Contribution snake"/>
  </picture>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:DE3D9E,100:EE5308&section=footer" alt=""/>
</p>
