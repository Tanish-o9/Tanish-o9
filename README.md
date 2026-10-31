<div align="center">

<img src="./assets/header.svg" width="100%" alt="Tanish Kumar - AI Engineer"/>

<a href="https://github.com/Tanish-o9"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=800&color=8B5CF6&center=true&vCenter=true&width=900&lines=Making+LLMs+faster%2C+smaller+and+cheaper+to+run;vLLM+%C2%B7+PagedAttention+%C2%B7+KV+Cache+%C2%B7+Quantization+%C2%B7+LoRA;Building+autonomous+agents+with+LangGraph+%26+RAG;Open+to+AI+Engineer+Internships+%F0%9F%9F%A2" alt="typing intro"/></a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0F172A)](https://www.linkedin.com/in/tanish-kumar-61553b385/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0F172A)](https://leetcode.com/u/Tanish_Kumar_123/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0F172A)](mailto:tanishrajput673@gmail.com)
![Profile views](https://komarev.com/ghpvc/?username=Tanish-o9&style=for-the-badge&color=8B5CF6&labelColor=0F172A&label=VIEWS)

</div>

---

### ⚡ `boot.log`

```text
[ OK ] Loading profile ............ Tanish Kumar
[ OK ] Mounting education ......... B.Tech CSE @ AKGEC (AKTU) · CGPA 8.50
[ OK ] Starting community ......... Cloud Computing Cell (CCC), AKGEC
[ OK ] Syncing DSA ................ 130+ LeetCode problems solved
[ OK ] Cleaning data .............. dedup · PII detection · decontamination
[ OK ] Optimizing models .......... Quantization · LoRA · KV cache · Distillation
[ OK ] Serving at scale ........... FastAPI · vLLM · continuous batching
[ OK ] Spawning agents ............ LangChain · LangGraph · RAG · MCP
[ >> ] Status ..................... 🟢 OPEN TO AI ENGINEER INTERNSHIPS
```

---

### 👨‍💻 `whoami.py`

```python
from dataclasses import dataclass, field

@dataclass
class Tanish:
    role: str      = "AI Engineer (Intern-ready)"
    education: str = "B.Tech CSE @ AKGEC (AKTU) | CGPA 8.50"
    community: str = "Cloud Computing Cell (CCC), AKGEC"
    dsa: str       = "130+ LeetCode problems solved"
    focus: list    = field(default_factory=lambda: [
        "LLM Inference Optimization", "LLM Data Engineering",
        "Agentic AI", "RAG", "Multi-Agent Systems"
    ])
    mission: str   = "Make LLMs faster, smaller and cheaper, then build agents on top"
    status: str    = "🟢 Open to AI Engineer Internships"

    def ship(self, idea):
        return self.clean_data() | self.finetune() | self.optimize() | self.serve() | self.build_agents()

print(Tanish().status)   # >>> 🟢 Open to AI Engineer Internships
```

---

### 🧬 `pipeline.mmd`

Every pinned project below is one stage of the same idea: take an **LLM from raw data to a fast, cheap, production-ready service**.

```mermaid
flowchart LR
    A[🧹 LLM-Data-Engine<br/>validate · dedup · filter<br/>PII · decontaminate · synthetic] --> B[🎓 Knowledge-Distillation-Lab<br/>+ LoRA fine-tuning]
    B --> C[⚡ QUANTORA<br/>quantization · LoRA<br/>memory + latency profiling]
    C --> D[🧠 KV-Cache-Memory-Optimizer<br/>GPU memory vs latency<br/>vs output consistency]
    D --> E[🚀 High-Throughput-LLM-Serving<br/>FastAPI + vLLM<br/>continuous batching]
    E --> F[🤖 Agentic-Ai<br/>agents · RAG · tools]
    style A fill:#312E81,color:#fff
    style C fill:#6D28D9,color:#fff
    style E fill:#065F46,color:#fff
    style F fill:#1E293B,color:#fff
```

---

### 📌 `gh repo list --pinned`

```bash
$ gh repo list Tanish-o9 --pinned
QUANTORA                      ⚡  LLM benchmarking + optimization platform
High-Throughput-LLM-Serving   🚀  FastAPI + vLLM serving stack, benchmarked 1-64 users
KV-Cache-Memory-Optimizer     🧠  KV cache memory vs latency vs consistency
LLM-Data-Engine               🧹  end-to-end LLM data pipeline + LoRA fine-tuning
Knowledge-Distillation-Lab    🎓  BERT-base (110M) -> DistilBERT (66M)
Agentic-Ai                    🤖  LangChain · LangGraph · RAG · tool-using agents
```

<div align="center">

<a href="https://github.com/Tanish-o9/QUANTORA"><img src="./assets/cards/quantora.svg" alt="QUANTORA" width="49%"/></a>
<a href="https://github.com/Tanish-o9/High-Throughput-LLM-Serving"><img src="./assets/cards/high-throughput-llm-serving.svg" alt="High-Throughput-LLM-Serving" width="49%"/></a>

<a href="https://github.com/Tanish-o9/KV-Cache-Memory-Optimizer"><img src="./assets/cards/kv-cache-memory-optimizer.svg" alt="KV-Cache-Memory-Optimizer" width="49%"/></a>
<a href="https://github.com/Tanish-o9/LLM-Data-Engine"><img src="./assets/cards/llm-data-engine.svg" alt="LLM-Data-Engine" width="49%"/></a>

<a href="https://github.com/Tanish-o9/Knowledge-Distillation-Lab"><img src="./assets/cards/knowledge-distillation-lab.svg" alt="Knowledge-Distillation-Lab" width="49%"/></a>
<a href="https://github.com/Tanish-o9/Agentic-Ai"><img src="./assets/cards/agentic-ai.svg" alt="Agentic-Ai" width="49%"/></a>

</div>

#### 🔍 `inspect(projects)`

```python
projects = {
    "QUANTORA": {
        "idea":  "open-source LLM benchmarking and optimization platform",
        "how":   "measure, analyze and improve inference efficiency",
        "stack": ["quantization", "LoRA", "KV cache optimization",
                  "memory profiling", "latency analysis"],
        "lang":  "Python",
    },
    "High-Throughput-LLM-Serving": {
        "idea":  "FastAPI LLM serving stack",
        "bench": "naive Hugging Face baseline vs vLLM under 1-64 concurrent users",
        "uses":  ["FastAPI", "vLLM", "continuous batching", "PagedAttention"],
        "lang":  "Python",
    },
    "KV-Cache-Memory-Optimizer": {
        "idea":  "evaluate KV cache optimization techniques",
        "measures": ["GPU memory savings", "inference latency overhead",
                     "output consistency"],
        "sweep": "across context lengths and batch sizes",
        "lang":  "Python",
    },
    "LLM-Data-Engine": {
        "idea":  "end-to-end LLM data engineering pipeline",
        "has":   ["dataset validation", "deduplication", "quality filtering",
                  "PII detection", "data decontamination",
                  "synthetic data generation", "LoRA fine-tuning"],
        "lang":  "Python",
    },
    "Knowledge-Distillation-Lab": {
        "idea":  "distill BERT-base teacher (110M) into DistilBERT student (66M)",
        "task":  "6-class emotion classification",
        "lang":  "Python",
    },
    "Agentic-Ai": {
        "idea":  "collection of agentic AI projects",
        "stack": ["LangChain", "LangGraph", "LLMs", "RAG",
                  "vector DBs", "tool-using agents"],
        "lang":  "Python",
    },
}
```

<details>
<summary><b>🔬 Architecture peek: inside the projects</b> (click to expand)</summary>

<br/>

**🚀 High-Throughput-LLM-Serving**

```mermaid
flowchart LR
    U([👥 1 to 64 concurrent users]) --> API{{🌐 FastAPI}}
    API --> N[🐢 Naive HF baseline]
    API --> V[⚡ vLLM<br/>continuous batching<br/>PagedAttention]
    N --> M{{📊 Throughput · Latency}}
    V --> M
    style API fill:#312E81,color:#fff
    style V fill:#065F46,color:#fff
```

**🧹 LLM-Data-Engine**

```mermaid
flowchart LR
    R([📦 Raw Data]) --> V1[✅ Validate]
    V1 --> D1[♻️ Deduplicate]
    D1 --> Q1[🎯 Quality Filter]
    Q1 --> P1[🔒 PII Detection]
    P1 --> C1[🧪 Decontaminate]
    C1 --> S1[🪄 Synthetic Data]
    S1 --> L1([🎛️ LoRA Fine-Tuning])
    style R fill:#1E293B,color:#fff
    style L1 fill:#065F46,color:#fff
```

**🧠 KV-Cache-Memory-Optimizer**

```mermaid
flowchart LR
    K([🗄️ KV Cache Techniques]) --> X{{🧪 Sweep: context length × batch size}}
    X --> G[📉 GPU Memory Savings]
    X --> T[⏱️ Latency Overhead]
    X --> O[🎯 Output Consistency]
    style X fill:#312E81,color:#fff
```

**🎓 Knowledge-Distillation-Lab**

```mermaid
flowchart LR
    T([👨‍🏫 BERT-base Teacher<br/>110M params]) -->|distill| S([🎓 DistilBERT Student<br/>66M params])
    D[(😀 6-class Emotion Data)] --> T
    D --> S
    S --> E{{📊 Compare: params · latency · accuracy}}
    style T fill:#312E81,color:#fff
    style S fill:#065F46,color:#fff
```

</details>

#### 🗂️ `also_built.py`

```python
also_built = {
    "LLM-Memory-Optimizer":        "FP16 / INT8 / INT4 profiling: VRAM, TPS, TTFT, WikiText-2 perplexity drift",
    "Lora-FineTuning-Lab":         "full fine-tuning vs LoRA on DistilBERT, rank + target-module ablations",
    "LangChain-with-LLM-Gateway":  "agents, tools, streaming, structured outputs, middleware, human-in-the-loop",
    "College-Times":               "AKGEC campus platform: real-time chat, news, events, gamification",
    "CineForge-AI":                "multi-agent AI film production platform",
    "Make-My-Trip":                "AI-first travel platform, LangGraph assistant, LLM router with failover",
    "Crash-Guard":                 "two-wheeler crash detection + emergency response",
    "Leetcode-Solution":           "DSA solutions, clean & efficient",
}
```

<div align="center">

[![LLM-Memory-Optimizer](https://img.shields.io/badge/LLM--Memory--Optimizer-0F172A?style=for-the-badge&logo=github)](https://github.com/Tanish-o9/LLM-Memory-Optimizer)
[![Lora-FineTuning-Lab](https://img.shields.io/badge/Lora--FineTuning--Lab-0F172A?style=for-the-badge&logo=github)](https://github.com/Tanish-o9/Lora-FineTuning-Lab)
[![LangChain-with-LLM-Gateway](https://img.shields.io/badge/LangChain--with--LLM--Gateway-0F172A?style=for-the-badge&logo=github)](https://github.com/Tanish-o9/LangChain-with-LLM-Gateway)
[![College-Times](https://img.shields.io/badge/College--Times-0F172A?style=for-the-badge&logo=github)](https://github.com/Tanish-o9/College-Times)
[![CineForge-AI](https://img.shields.io/badge/CineForge--AI-0F172A?style=for-the-badge&logo=github)](https://github.com/Tanish-o9/CineForge-AI)
[![Make-My-Trip](https://img.shields.io/badge/Make--My--Trip-0F172A?style=for-the-badge&logo=github)](https://github.com/Tanish-o9/Make-My-Trip)
[![Crash-Guard](https://img.shields.io/badge/Crash--Guard-0F172A?style=for-the-badge&logo=github)](https://github.com/Tanish-o9/Crash-Guard)
[![Leetcode-Solution](https://img.shields.io/badge/Leetcode--Solution-0F172A?style=for-the-badge&logo=github)](https://github.com/Tanish-o9/Leetcode-Solution)

</div>

---

### 🛠️ `stack.yaml`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,c,cpp,js,ts,react,html,css,fastapi,django&theme=dark" alt="languages and web"/>
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,firebase,docker,githubactions,pytorch,sklearn,git,vscode&theme=dark" alt="data and devops"/>

</div>

```yaml
llm_inference:      [vLLM, PagedAttention, Continuous Batching, KV Cache Optimization, Quantization (FP16/INT8/INT4), Latency + Memory Profiling]
llm_data_eng:       [Dataset Validation, Deduplication, Quality Filtering, PII Detection, Decontamination, Synthetic Data]
model_training:     [LoRA, Knowledge Distillation, Fine-Tuning, Benchmarking]
agentic_ai:         [LangChain, LangGraph, Multi-Agent Systems, RAG, AI Memory, Tool Calling, MCP, LLM Orchestration, LLM Gateways]
ai_engineering:     [Python, LLMs, Prompt Engineering, AI Workflows, AI Applications]
ml_dl:              [Machine Learning, Deep Learning, NLP, Scikit-Learn, PyTorch, Computer Vision]
vector_search:      [FAISS, ChromaDB, RAG Search]
backend:            [FastAPI, Django, JWT]
database:           [PostgreSQL, MongoDB, Redis, Firebase]
frontend:           [HTML, CSS, JavaScript, React]
devops_cloud:       [Docker, GitHub Actions, n8n]
languages:          [Python, C, C++, JavaScript, TypeScript]
```

---

### 🎯 `roadmap.py`

```python
roadmap = {
    "Agentic AI & Multi-Agent Systems":   "████████░░ 80%",
    "LLM Orchestration & AI Memory":      "███████░░░ 70%",
    "RAG & Vector Search":                "███████░░░ 70%",
    "DSA (Arrays · Trees · Graphs · DP)": "██████░░░░ 60%",
}

for skill, progress in roadmap.items():
    print(f"{skill:<36} {progress}")
```

📚 **Daily practice** → [**LeetCode**](https://leetcode.com/u/Tanish_Kumar_123/) · [**DSA Repository**](https://github.com/Tanish-o9/Leetcode-Solution)

---

### 📊 `stats.log`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Tanish-o9&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" height="165" alt="stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tanish-o9&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="top languages"/>
<br/>
<img src="https://streak-stats.demolab.com?user=Tanish-o9&theme=tokyonight&hide_border=true" alt="streak"/>

</div>

---

### 🤝 `contact.sh`

```bash
$ whoami
Tanish Kumar — AI Engineer (LLM Systems · Agentic AI · RAG)

$ cat looking_for.txt
AI Engineer internships: LLM inference and serving, data pipelines, agentic systems, RAG.

$ ./connect.sh
📫 Email     → tanishrajput673@gmail.com
💼 LinkedIn  → linkedin.com/in/tanish-kumar-61553b385
🧩 LeetCode  → leetcode.com/u/Tanish_Kumar_123
```

<div align="center">

```python
while True:
    clean(); finetune(); optimize(); serve(); ship()   # ⚡ Faster LLMs. Smarter Agents. Production-ready AI.
```

<img src="./assets/footer.svg" width="100%" alt="footer"/>

</div>
