<h1 align="center">Dhyey Tandel</h1>

<p align="center">
  <b>Software Engineer · Backend &amp; Distributed Systems · Applied ML</b><br/>
  B.Tech CSE @ Manipal Institute of Technology, Bengaluru (2027) · Ex-SWE Intern @ Schneider Electric
</p>

<p align="center">
  <a href="https://dhyeytandel.in"><img src="https://img.shields.io/badge/Portfolio-dhyeytandel.in-111111?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/dhyey-tandel"><img src="https://img.shields.io/badge/LinkedIn-dhyey--tandel-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:dhyeytandel2005@gmail.com"><img src="https://img.shields.io/badge/Email-dhyeytandel2005%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS Certified Cloud Practitioner"/>
</p>

I like building the parts of a system that have to keep working when things go wrong: commit logs that survive torn writes, transport that survives packet loss, route planners that repair themselves when someone cancels. Most of my repos are built from first principles and come with the tests and benchmarks to back up what the README says.

**Open to:** SDE / backend / ML engineering internships and new-grad roles for 2027.

---

## 💼 Experience

**Schneider Electric** · Software Engineering Intern · May 2025 to Jul 2025
- Automated cloud ingestion of ~**40M inventory items/week** into Azure, replacing a manual cross-team process.
- Cut asset-lifecycle reporting queries from about a week to **12 hours** through query rewrites and indexing.
- Wrote test suites for **40 API endpoints**, catching **20+ integration bugs** before release.

---

## 🛠️ Featured work

### [FluxMQ](https://github.com/DhyeyTandel/FluxMQ) · distributed message queue from scratch
`Python` `asyncio` `TCP` `Hypothesis`
- Partitioned append-only commit log, consumer groups with rebalancing, leader/follower replication with ISR tracking.
- Custom binary wire protocol with pipelining and batching: **400 → 170,000+ msgs/sec (425x)** at **8.2 ms p99**.
- `acks=all` with automatic leader failover; chaos tests kill live brokers mid-stream with **zero acknowledged-message loss**.

### [Cabal](https://github.com/DhyeyTandel/Cabal) · employee transport planner
`Java 17` `Spring Boot` `PostgreSQL` `Flyway` `OSRM`
- REST service solving a heterogeneous-fleet capacitated vehicle routing problem with ride-time limits.
- Pipeline of classic heuristics benchmarked against optimal; repairs plans on late bookings and cancellations without reshuffling everyone.

### [MiniNET](https://github.com/DhyeyTandel/MiniNET) · network protocol simulator
`Python` `asyncio`
- Go-Back-N reliable transport and Bellman-Ford distance-vector routing (poison reverse) over a deterministic lossy link layer.
- Byte-identical 50 KB transfers across a 3-hop path at **20% data loss + 10% ACK loss**; topology converges in **2.12 s**.

### [NSE Arena](https://github.com/DhyeyTandel/NSE_ARENA) · real-time paper-trading competitions
`FastAPI` `React` `PostgreSQL` `Redis Pub/Sub` `WebSockets` `Docker`
- Live NSE market data streamed over WebSockets, seasonal leaderboards with multi-factor trader scoring.
- A custom PineScript-lite engine (SMA, EMA, RSI, MACD, Bollinger) and Gemini-powered agents that trade alongside users.

### [AI Shield](https://github.com/DhyeyTandel/AI-Shield) · ML intrusion detection and prevention
`Python` `scikit-learn` `Scapy` `Flask`
- Live packet capture, classifiers trained on CICIDS2017, automatic blocking of flagged hosts, and a real-time dashboard.

### [Accessible Components](https://github.com/DhyeyTandel/a11y-hard-parts) · the ARIA patterns people get wrong
`JavaScript` `WCAG 2.2` · [live demo](https://dhyeytandel.github.io/a11y-hard-parts/)
- Eleven zero-dependency components (focus traps, comboboxes, live regions, sliders) with **187 browser-run tests**, verified with VoiceOver.

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it is | Stack |
| --- | --- | --- |
| [Resume Screener](https://github.com/DhyeyTandel/Resume_Screener) | Human-in-the-loop resume screening with prompt-injection detection and an append-only audit log | FastAPI, React, Ollama |
| [Claude Usage Tracker](https://github.com/DhyeyTandel/Claude_Usage_Tracker) | Menu-bar widget for Claude Code limits and Anthropic API spend, with encrypted key storage | Electron, TypeScript |
| [AutoAssess](https://github.com/DhyeyTandel/autoassess) | Vehicle-damage segmentation and severity grading for insurance claims | YOLOv8-seg, PyTorch |
| [Cisco Demand Forecasting](https://github.com/DhyeyTandel/Cisco-Demand-Forecasting) | Ensemble model for product-demand forecasting | XGBoost, pandas |

</details>

---

## 🧰 Tech stack

- **Languages:** Python · Java · TypeScript · JavaScript · C · SQL
- **Backend:** FastAPI · Spring Boot · Flask · Node.js · asyncio · REST · WebSockets
- **Data & infra:** PostgreSQL · Redis · MongoDB · MySQL · Docker · AWS (Lambda, S3, API Gateway, SAM) · Azure · GitHub Actions
- **ML:** scikit-learn · XGBoost · PyTorch · YOLOv8

<p align="left">
  <img src="https://skillicons.dev/icons?i=py,java,ts,js,c,spring,fastapi,flask,nodejs,react,postgres,redis,mongodb,docker,aws,azure,githubactions,pytorch,sklearn&theme=dark&perline=10" alt="Tech stack icons"/>
</p>
