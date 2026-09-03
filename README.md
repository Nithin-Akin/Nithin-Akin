<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,50:00C6FF,100:00F5A0&height=220&section=header&text=NITHIN%20AKIN&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20LLM%20Systems%20%7C%20Builder&descAlignY=60&descSize=18"/>

<a href="https://github.com/Nithin-Akin">
<img src="https://img.shields.io/badge/GitHub-Nithin--Akin-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/nithinsathya007/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:nithinios16@gmail.com">
<img src="https://img.shields.io/badge/Email-Say%20Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3000&pause=900&color=00F5A0&center=true&vCenter=true&width=700&lines=Building+AI+systems+that+actually+do+things.;RAG+%7C+Agents+%7C+Multimodal+AI+%7C+Backend;Build.+Break.+Understand.+Rebuild.;Currently+turning+ideas+into+working+systems." />

<br/>

<img src="https://komarev.com/ghpvc/?username=Nithin-Akin&style=flat-square&color=7F00FF"/>

</div>

---

## 🧠 `whoami`

I'm **Nithin**, a software engineering intern and student from **Bengaluru, India**, focused on **AI engineering, LLM systems, and backend development**.

I like building things where the interesting part isn't just the model — it's everything around it.

**Retrieval. Agents. Tool use. APIs. Evaluation. Failure handling. Performance.**

> **I don't just want the model to answer. I want to understand the system that makes the answer possible.**

---

<div align="center">

### `AI → SYSTEMS → SOFTWARE`

<img src="https://img.shields.io/badge/LLMs-7F00FF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/RAG-00C6FF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AI%20Agents-00F5A0?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Multimodal-AI-FF4ECD?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Backend-FFB000?style=for-the-badge"/>

</div>

---

# 🚀 What I'm Building

<table>
<tr>

<td width="50%" valign="top">

## 🤖 AI Engineering

- LLM applications
- Retrieval-Augmented Generation
- Multi-agent systems
- Agent orchestration
- Tool calling
- Embeddings
- Vector search
- Multimodal AI
- Prompt engineering
- AI evaluation

</td>

<td width="50%" valign="top">

## ⚙️ Software Engineering

- Backend systems
- REST APIs
- Data pipelines
- Automation
- Async processing
- Parallel workflows
- Caching
- Error handling
- System architecture
- Performance

</td>

</tr>
</table>

---

# 🔥 Featured Projects

<div align="center">

## 🧾 `invoice-reconciliation-agent-system`

### **Multi-Agent Invoice Intelligence**

</div>

A multi-agent system built to automate invoice processing and reconciliation using **four specialized agents**.

Instead of throwing everything into one LLM call:

```text
                         📄 INVOICE
                             │
                             ▼
                 ┌─────────────────────┐
                 │  DOCUMENT INTEL      │
                 │                     │
                 │  PDF → Data         │
                 │  OCR → Data         │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   MATCHING AGENT    │
                 │                     │
                 │ Exact → Fuzzy       │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ DISCREPANCY AGENT  │
                 │                     │
                 │ Price │ Qty │ PO   │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │  RESOLUTION AGENT  │
                 │                     │
                 │ Approve / Review    │
                 │ / Escalate          │
                 └─────────────────────┘
```

### ⚡ Highlights

| Capability | Implementation |
|---|---|
| 📄 Document extraction | `pdfplumber` |
| 👁️ OCR | `Tesseract + OpenCV` |
| 🔎 PO matching | Exact + fuzzy |
| 🧠 Decision making | Multi-agent |
| 📊 Confidence | Every stage |
| 🔍 Observability | Execution traces |
| 🛡️ Reliability | Graceful degradation |
| ⚡ Batch processing | ~5 seconds / 5 invoices |

**Stack:** `Python` `OpenCV` `Tesseract` `pdfplumber` `OCR` `Multi-Agent Systems`

<a href="https://github.com/Nithin-Akin/invoice-reconciliation-agent-system">
<img src="https://img.shields.io/badge/VIEW%20PROJECT-7F00FF?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

<div align="center">

## 🔎 `multimodal-rag-chatbot`

### **Retrieval Beyond Plain Text**

</div>

A multimodal RAG system designed around **metric-level chunking + hybrid retrieval**.

```text
             📚 DOCUMENTS
                  │
                  ▼
        ┌───────────────────┐
        │ Multimodal        │
        │ Ingestion         │
        └─────────┬─────────┘
                  │
                  ▼
        ┌───────────────────┐
        │ Metric-Level      │
        │ Chunking          │
        └─────────┬─────────┘
                  │
           ┌──────┴──────┐
           ▼             ▼
        🔵 FAISS       🟣 BM25
           │             │
           └──────┬──────┘
                  ▼
        ┌───────────────────┐
        │ Hybrid Retrieval  │
        └─────────┬─────────┘
                  ▼
               🧠 LLM
                  │
                  ▼
              💬 ANSWER
```

### ⚡ Highlights

- Metric-level table chunking
- FAISS vector retrieval
- BM25 lexical retrieval
- Hybrid search
- Multimodal document extraction
- OCR
- FastAPI backend
- Streamlit interface
- Evaluation pipeline

**Reported evaluation accuracy: 100%**

**Stack:** `Python` `FAISS` `BM25` `Sentence Transformers` `FastAPI` `Streamlit` `RAG`

<a href="https://github.com/Nithin-Akin/multimodal-rag-chatbot">
<img src="https://img.shields.io/badge/VIEW%20PROJECT-00C6FF?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

<table>
<tr>

<td width="50%" valign="top">

### 👁️ SIO Vision Care

AI / computer-vision focused web application built with a modern TypeScript frontend stack.

`TypeScript` `React` `Vite` `Tailwind`

<a href="https://github.com/Nithin-Akin/sio-vision-care">
<img src="https://img.shields.io/badge/VIEW-00F5A0?style=for-the-badge&logo=github"/>
</a>

</td>

<td width="50%" valign="top">

### 🌐 Liminal

Full-stack application experiment with a separate frontend and backend architecture.

`TypeScript` `React` `Node.js`

<a href="https://github.com/Nithin-Akin/liminal">
<img src="https://img.shields.io/badge/VIEW-FF4ECD?style=for-the-badge&logo=github"/>
</a>

</td>

</tr>
</table>

---

# 🧰 Tech Arsenal

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=python,cpp,java,js,ts,kotlin"/>

### AI / ML

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow"/>

<br/>

<img src="https://img.shields.io/badge/LLMs-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/RAG-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Agents-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Embeddings-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Vector%20Search-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Computer%20Vision-111111?style=for-the-badge"/>

### Backend / Infrastructure

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,docker,linux,git,github,postgres,mongodb"/>

<br/>

<img src="https://img.shields.io/badge/Supabase-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pinecone-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/FAISS-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Ollama-111111?style=for-the-badge"/>

</div>

---

# 🏗️ How I Think About AI Systems

A lot of AI projects stop here:

```text
USER
  ↓
PROMPT
  ↓
LLM
  ↓
ANSWER
```

I find the interesting part here:

```text
                         USER
                           │
                           ▼
                    ┌─────────────┐
                    │   INPUT     │
                    └──────┬──────┘
                           │
                           ▼
                    ┌─────────────┐
                    │ RETRIEVAL   │
                    │             │
                    │ Search      │
                    │ Rank        │
                    │ Filter      │
                    └──────┬──────┘
                           │
                           ▼
                    ┌─────────────┐
                    │ ORCHESTRATE │
                    │             │
                    │ Agents      │
                    │ Tools       │
                    │ State       │
                    └──────┬──────┘
                           │
                           ▼
                    ┌─────────────┐
                    │   MODEL     │
                    └──────┬──────┘
                           │
                           ▼
                    ┌─────────────┐
                    │ EVALUATION  │
                    │             │
                    │ Quality     │
                    │ Confidence  │
                    │ Failures    │
                    └──────┬──────┘
                           │
                           ▼
                         USER
```

> **The model is a component. The system is the product.**

---

# 🧪 Currently Exploring

<div align="center">

<img src="https://img.shields.io/badge/01%20%7C%20Retrieval-7F00FF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/02%20%7C%20Agents-00C6FF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/03%20%7C%20Reliability-00F5A0?style=for-the-badge"/>
<img src="https://img.shields.io/badge/04%20%7C%20Systems-FF4ECD?style=for-the-badge"/>

</div>

```text
RETRIEVAL
├── Embeddings
├── Vector Search
├── Hybrid Search
└── Reranking

AGENTS
├── Tool Calling
├── Orchestration
├── State
└── Multi-Agent Systems

RELIABILITY
├── Evaluation
├── Observability
├── Confidence
└── Error Recovery

SYSTEMS
├── APIs
├── Async Processing
├── Performance
└── Scalability
```

---

# 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Nithin-Akin&show_icons=true&hide_border=true&rank_icon=github&theme=radical"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nithin-Akin&layout=compact&hide_border=true&theme=radical"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Nithin-Akin&theme=radical&hide_border=true"/>

</div>

---

# 💭 Engineering Philosophy

<div align="center">

### **"Don't just use the abstraction. Understand what's underneath it."**

<br/>

**A working demo ≠ a working system.**

<br/>

**If it can fail, understand how it fails.**

<br/>

**If it makes a decision, make the decision explainable.**

<br/>

**If you can't measure it, you probably don't understand it yet.**

</div>

---

# ⚡ Outside the Terminal

<div align="center">

🏍️ **Motorcycles**  
🥊 **MMA**  
📚 **Learning things I probably didn't need to learn**  
💰 **Building toward financial freedom**  
☕ **Overthinking engineering problems**

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F5A0,50:00C6FF,100:7F00FF&height=120&section=footer"/>

### `BUILD → BREAK → UNDERSTAND → REBUILD → SHIP`

<br/>

<a href="https://github.com/Nithin-Akin">
<img src="https://img.shields.io/badge/Follow%20the%20Build-181717?style=for-the-badge&logo=github"/>
</a>

</div>
