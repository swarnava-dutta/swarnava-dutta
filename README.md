<!--
  GITHUB PROFILE README
  Save as README.md in the SwarnavaDutta/SwarnavaDutta repository.

  Uses GitHub-supported Markdown, HTML tables, and Mermaid.
  Badges and typing animation require external image services.
  Core content remains readable if those services are unavailable.
-->

<!-- HERO HEADER -->

<div align="center">
<!-- HERO BANNER -->

<div align="center">

<br />

<sub><b>E N G I N E E R I N G &nbsp; I N T E L L I G E N C E</b></sub>

<br />

<a href="https://swarnava.dev">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&amp;weight=800&amp;size=64&amp;duration=2500&amp;pause=20000&amp;color=22D3EE&amp;background=0D1117&amp;center=true&amp;vCenter=true&amp;repeat=true&amp;width=1200&amp;height=180&amp;lines=SWARNAVA+DUTTA" width="100%" alt="SWARNAVA DUTTA" />
</a>

### LEAD AI ENGINEER
**Agentic Systems &nbsp; / &nbsp; Enterprise RAG &nbsp; / &nbsp; Production LLMOps**

<br />

**From MVP to production**

<br />
━━━━━━━━━━━━━━━━━━ &nbsp; ✦ &nbsp; ━━━━━━━━━━━━━━━━━━

<br />
<br />
<a href="https://swarnava.dev">
  <img src="https://img.shields.io/badge/EXPLORE_MY_WORK-0891B2?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white" alt="Explore my work" />
</a>
&nbsp;
<a href="https://www.linkedin.com/in/swarnava-dutta/">
  <img src="https://img.shields.io/badge/CONNECT_ON_LINKEDIN-1D4ED8?style=for-the-badge" alt="Connect on LinkedIn" />
</a>
&nbsp;
<a href="mailto:swarnava.dev@gmail.com?subject=AI%20Engineering%20Collaboration">
  <img src="https://img.shields.io/badge/LET%27S_BUILD_TOGETHER-7C3AED?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Let's build together — email Swarnava" />
</a>

<br />
<br />

━━━━━━━━━━━━━━━━━━ &nbsp; ✦ &nbsp; ━━━━━━━━━━━━━━━━━━

</div>


<a href="https://swarnava.dev">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=22&amp;duration=3000&amp;pause=1200&amp;color=22D3EE&amp;center=true&amp;vCenter=true&amp;width=850&amp;height=60&amp;lines=Intelligence+is+the+starting+point.;Reliable+execution+is+the+product.;Building+AI+systems+beyond+the+demo." width="100%" alt="Building AI systems beyond the demo." />
</a>


<br />

I build AI systems that **retrieve with context, act within boundaries,**  
and **deliver outcomes you can evaluate.**
<br />
<br />

<sub>
  <a href="#-the-engineer-behind-the-systems">ABOUT</a>
  &nbsp; / &nbsp;
  <a href="#-where-i-build">FOCUS</a>
  &nbsp; / &nbsp;
  <a href="#-architecture-in-motion">ARCHITECTURE</a>
  &nbsp; / &nbsp;
  <a href="#-the-toolkit">STACK</a>
  &nbsp; / &nbsp;
  <a href="#-lets-build-something-that-matters">CONNECT</a>
</sub>

</div>

<br />

---

## 🧠 The Engineer Behind the Systems

<table>
<tr>
<td width="60%" valign="top">

### Intelligence meets engineering.

I'm **Swarnava Dutta**, a **Lead AI Engineer** working at the intersection of agentic AI, enterprise knowledge systems, and cloud-native infrastructure.

I design applications that don't just generate answers—they **retrieve the right context, use tools within clear boundaries, and expose the signals needed to evaluate their behavior**.

My approach combines practical model integration with the fundamentals: clean interfaces, explicit state, robust evaluation, and resilient deployment.

**Less unnecessary complexity. More dependable execution.**

</td>
<td width="40%" valign="top">

### ⚡ At a Glance

**BUILD**  
Agents · RAG · AI platforms

**OPERATE**  
Cloud-native services · LLMOps

**OPTIMIZE**  
Quality · Latency · Cost

**PRIORITIZE**  
Clarity · Control · Observability

**CONNECT**  
[https://swarnava.dev](https://swarnava.dev)  
[swarnava.dev@gmail.com](mailto:swarnava.dev@gmail.com)

</td>
</tr>
</table>

<br />

## 🎯 Where I Build

<table>
<tr>
<td width="33%" valign="top">

### 🤖
### Agentic Systems

**Autonomy, with boundaries.**

Stateful workflows that connect models to tools, memory, and business processes—with explicit execution limits and approval points.

<br />

`LangGraph` `MCP`  
`Tool Calling` `Checkpoints`

</td>
<td width="33%" valign="top">

### 🔎
### Enterprise RAG

**Context that earns its place.**

Retrieval pipelines that combine hybrid search, access-aware filtering, and reranking to support grounded, relevant answers.

<br />

`Hybrid Search` `Reranking`  
`Vector Stores` `Citations`

</td>
<td width="33%" valign="top">

### ☁️
### Production LLMOps

**Built to run. Built to inspect.**

Evaluation, tracing, inference optimization, and cloud-native delivery that turn AI capabilities into maintainable services.

<br />

`LangSmith` `OpenTelemetry`  
`Docker` `AKS`

</td>
</tr>
</table>

<br />

<div align="center">

> **A powerful model is a component. A reliable AI product is an engineered system.**

</div>

<br />

## 🏗️ Architecture in Motion

**One clear request path. Explicit control points. Visibility throughout.**

```mermaid
flowchart TB
    CLIENT(["Client Application"])

    subgraph ACCESS["01 / ACCESS"]
        API["API Gateway"]
        POLICY["Identity · Rate Limits · Input Validation"]
        API --> POLICY
    end

    subgraph CONTROL["02 / ORCHESTRATION"]
        ROUTER["Stateful Workflow<br/>Routing · Memory · Execution Budget"]
    end

    subgraph EXECUTION["03 / CONTEXT & ACTION"]
        RETRIEVAL["Retrieval Pipeline<br/>Hybrid Search · Filters · Reranking"]
        TOOLS["Tool Gateway<br/>MCP · Permissions · Approvals"]
    end

    subgraph RESPONSE["04 / GENERATION & DELIVERY"]
        MODEL["LLM Inference<br/>Grounded Context · Structured Output"]
        VALIDATE["Response Validation<br/>Schema · Citations · Policy"]
        MODEL --> VALIDATE
    end

    OUTPUT(["Validated Response"])

    CLIENT --> API
    POLICY --> ROUTER
    ROUTER --> RETRIEVAL
    ROUTER --> TOOLS
    RETRIEVAL --> MODEL
    TOOLS --> MODEL
    VALIDATE --> OUTPUT

    classDef endpoint fill:#0F172A,stroke:#94A3B8,color:#F8FAFC,stroke-width:2px;
    classDef access fill:#172554,stroke:#60A5FA,color:#EFF6FF,stroke-width:1px;
    classDef orchestration fill:#083344,stroke:#22D3EE,color:#ECFEFF,stroke-width:2px;
    classDef execution fill:#2E1065,stroke:#A78BFA,color:#F5F3FF,stroke-width:1px;
    classDef response fill:#052E16,stroke:#4ADE80,color:#F0FDF4,stroke-width:1px;

    class CLIENT,OUTPUT endpoint;
    class API,POLICY access;
    class ROUTER orchestration;
    class RETRIEVAL,TOOLS execution;
    class MODEL,VALIDATE response;

    style ACCESS fill:#0B1220,stroke:#334155,color:#93C5FD
    style CONTROL fill:#0B1220,stroke:#334155,color:#67E8F9
    style EXECUTION fill:#0B1220,stroke:#334155,color:#C4B5FD
    style RESPONSE fill:#0B1220,stroke:#334155,color:#86EFAC
```

<br />

| 🔐 Secure by Design | 📡 Observable by Default | 🧪 Evaluated Continuously |
| :--- | :--- | :--- |
| Identity-aware retrieval | End-to-end request traces | Retrieval and answer quality |
| Least-privilege tool access | Token, latency, and cost tracking | Representative regression cases |
| Scoped memory and retention | Tool outcomes and failure signals | Human-reviewed assessments |

<br />

## 🛠️ The Toolkit

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,fastapi,azure,docker,kubernetes&amp;theme=dark&amp;perline=6" width="360" alt="Python, PyTorch, FastAPI, Azure, Docker, Kubernetes" />

<br />

<img src="https://skillicons.dev/icons?i=redis,kafka,postgres,git,linux,bash&amp;theme=dark&amp;perline=6" width="360" alt="Redis, Kafka, PostgreSQL, Git, Linux, Bash" />

</div>

<br />

| Layer | Technologies & Practices |
| :--- | :--- |
| **🤖 Agentic Orchestration** | `LangGraph` `LangChain` `LlamaIndex` `CrewAI` `MCP` |
| **🧠 Models & Adaptation** | `PyTorch` `Transformers` `PEFT` `LoRA / QLoRA` `Prompt Engineering` |
| **⚡ Inference & Serving** | `Azure OpenAI` `Claude` `vLLM` `Ollama` |
| **🔎 Retrieval & Search** | `Azure AI Search` `Pinecone` `Qdrant` `BM25 + Dense` `Cohere Rerank` |
| **☁️ Cloud & Infrastructure** | `Azure AI Foundry` `AKS` `Docker` `AWS` `Terraform` |
| **📡 Evaluation & Observability** | `LangSmith` `Ragas` `Arize Phoenix` `OpenTelemetry` `Prometheus` `Grafana` |
| **🗄️ Backend & Data** | `FastAPI` `PostgreSQL` `Redis` `Kafka` `PySpark` `Databricks` `Delta Lake` |

<details open>
<summary><b>🔬 Under the hood — engineering practices</b></summary>

### Agentic Workflows
- Explicit state transitions and checkpointed execution.
- Schema-defined tool interfaces with scoped permissions.
- Timeouts, bounded retries, and execution budgets.
- Human approval for sensitive or high-impact actions.

### Retrieval Pipelines
- Structure-aware chunking and metadata enrichment.
- Dense and sparse retrieval with relevance-based reranking.
- Access-aware context assembly and citation support.
- Separate evaluation of retrieval quality and generation quality.

### Production Operations
- Automated regression checks before deployment.
- Tracing across retrieval, inference, and tool execution.
- Monitoring for latency, token consumption, cost, and failures.
- Containerized services and reproducible infrastructure.

</details>

<br />

## 🧭 The Engineering Standard

<table>
<tr>
<td width="50%" valign="top">

### 01 / Production Is the Product

A demo proves possibility. Production demands concurrency handling, failure recovery, rate-limit awareness, and predictable operational behavior.

</td>
<td width="50%" valign="top">

### 02 / Evidence Before Optimization

Establish quality baselines before tuning prompts, models, or infrastructure. Measure the outcome—not just the sophistication of the implementation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 03 / Simplicity Is a Strength

Not every problem needs an agent. Prefer a focused pipeline or deterministic code when it delivers the right result with fewer moving parts.

</td>
<td width="50%" valign="top">

### 04 / Boundaries Build Trust

Authorization, validation, sandboxing, and human oversight belong in the architecture—not in the backlog after launch.

</td>
</tr>
</table>

<br />

## 📐 Signals That Matter

**What I measure to understand whether an AI system is actually working.**

| | Dimension | Key Signals |
| :---: | :--- | :--- |
| 🎯 | **Answer Quality** | Groundedness · Citation correctness · Task completion |
| 🔎 | **Retrieval Quality** | Context precision · Context recall · Ranking relevance |
| ⚡ | **Performance** | Time to first token · End-to-end latency · Throughput |
| 🛡️ | **Reliability** | Tool success rate · Timeout rate · Recovery behavior |
| 💰 | **Efficiency** | Tokens per task · Cost per successful request · Cache hit rate |
| 🔐 | **Control** | Authorization enforcement · Policy violations · Approval coverage |

<br />

---

## 🤝 Let's Build Something That Matters

<div align="center">

### Your next AI system deserves more than a great demo.

Whether you're designing an enterprise assistant, connecting agents to real workflows,  
or taking an AI platform into production—**let's talk architecture.**

<br />

<table>
<tr>
<td align="center" width="33%">
  <b>🏢 Enterprise AI</b>
  <br />
  <sub>Trusted knowledge. Grounded answers.</sub>
</td>
<td align="center" width="33%">
  <b>🤖 Agentic Workflows</b>
  <br />
  <sub>Useful tools. Controlled execution.</sub>
</td>
<td align="center" width="33%">
  <b>☁️ Production Platforms</b>
  <br />
  <sub>Measurable quality. Reliable delivery.</sub>
</td>
</tr>
</table>

<br />

<a href="mailto:swarnava.dev@gmail.com?subject=AI%20Engineering%20Collaboration">
  <img src="https://img.shields.io/badge/LET%27S_BUILD-SOMETHING_GREAT-22D3EE?style=for-the-badge&amp;logo=gmail&amp;logoColor=22D3EE&amp;labelColor=0F172A" alt="Let's build something great — email Swarnava" />
</a>

<br />
<br />

<a href="https://swarnava.dev">
  <img src="https://img.shields.io/badge/EXPLORE_MY_WORK-164E63?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white" alt="Explore my work" />
</a>
&nbsp;
<a href="https://www.linkedin.com/in/swarnava-dutta/">
  <img src="https://img.shields.io/badge/MESSAGE_ON_LINKEDIN-1E3A8A?style=for-the-badge" alt="Message on LinkedIn" />
</a>
&nbsp;
<a href="https://x.com/Swarnava_Duttaa">
  <img src="https://img.shields.io/badge/FOLLOW_ON_X-18181B?style=for-the-badge&amp;logo=x&amp;logoColor=white" alt="Follow on X" />
</a>

<br />
<br />

**[https://swarnava.dev](https://swarnava.dev)**  
[swarnava.dev@gmail.com](mailto:swarnava.dev@gmail.com)

</div>

<br />

---

<div align="center">

**Build with intent. Evaluate with evidence. Operate with confidence.**

<sub>Swarnava Dutta · Lead AI Engineer</sub>

</div>
