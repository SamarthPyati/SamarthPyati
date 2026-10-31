# Hi, I'm Samarth 👋

AI and systems engineer. I build LLM agents and computer vision systems in Python, and write the fast bits in C and Rust. I like measuring things: most of my projects ship with an evaluation, not just a demo.

Currently Software Engineering Intern at **[Signoff.Today](https://signoff.today)**. CS undergrad at RV University, Bengaluru.

[Email](mailto:samarthpyati@gmail.com) · [LinkedIn](https://www.linkedin.com/in/samarth-pyati) · [Codeforces](https://codeforces.com/profile/samarthpyati) · [LeetCode](https://leetcode.com/u/samarthpyati/) · [Resume](./SamarthPyatiResume.pdf)

### Experience

- **Agentic RAG at KPMG**: multimodal document search over large enterprise corpora. Made indexing ~20× faster and answers ~25% more relevant.
- **SaaS backend at Qalaa**: sole developer of a multi-tenant platform (~49K LOC, 308 REST endpoints) whose billing ledger reconciles to zero errors.
- **Sports CV at Visist AI**: court detection, player/shuttle tracking (YOLOv8) and pose estimation for badminton footage, up to ~98% detection accuracy.
- **ML pipelines at Jio**: ~10× inference speedup on large sequential datasets through profiling and parallelism.

### AI & ML projects

| Project | What it does | Built with |
| --- | --- | --- |
| [Open Source Scout](https://github.com/SamarthPyati/Open-Source-Scout) · [live](https://open-source-scout.up.railway.app/) | Multi-agent assistant for first-time contributors: ranks good first issues, finds the relevant code, drafts the fix plan and PR | LangGraph, FastAPI, React, Postgres |
| [Unspoken](https://github.com/SamarthPyati/Unspoken) | LLM agents that pass their KV cache to each other instead of text. Cut output tokens and latency by 75% on GSM8K, at a cost of 7.3 accuracy points | PyTorch, Transformers, Qwen2.5 |
| [CV-Dial](https://github.com/SamarthPyati/CV-Dial) | Reads analog gauges from a phone photo. Perspective correction keeps error under ~1% of full scale at steep angles, vs ~4% without it | YOLO pose, OpenCV, ResNet-18 |
| [Skylark-BI](https://github.com/SamarthPyati/Skylark-BI) · [live](https://skylark-bi.streamlit.app/) | Conversational BI agent over live monday.com boards. The LLM never does the arithmetic: deterministic tools compute, and 19 data-quality checks flag caveats | LLM tool use, Pandas, Streamlit |
| [AYUR-SANKET](https://github.com/SamarthPyati/namaste-icd11-fhir-bridge) | FHIR R4 microservice mapping Indian traditional-medicine codes (NAMASTE) to WHO ICD-11, built for Smart India Hackathon 2025 | FastAPI, Redis, SvelteKit |
| [DocClassifier](https://github.com/SamarthPyati/doc-classifier) | RAG chat over mixed document corpora (PDF, Office, EPUB…) with pluggable LLMs and embeddings | LangChain, ChromaDB, Streamlit |
| [MoleculeGNN](https://github.com/SamarthPyati/MoleculeGNN) | Predicts toxicity and solubility from molecular graph structure | PyTorch Geometric, RDKit |
| [leaf-music-classifier](https://github.com/SamarthPyati/leaf-music-classifier) | Genre classification from raw audio with a learnable frontend (LEAF) and a 2D CNN | PyTorch, torchaudio |

### Systems projects

| Project | What it does | Built with |
| --- | --- | --- |
| [DocSense](https://github.com/SamarthPyati/DocSense) | Local BM25 search engine with incremental re-indexing: 2–5 ms queries over 50k docs, single binary | Rust |
| [seam-carving](https://github.com/SamarthPyati/seam-carving) | Content-aware image resizing with a vectorized DP seam solver | C, OpenMP |
| [sp_arena](https://github.com/SamarthPyati/sp_arena) | Thread-safe arena allocator with scoped temp arenas, verified leak-free with Valgrind | C |
| [spda](https://github.com/SamarthPyati/spda) | Type-generic dynamic array with a zero-overhead typed API | C |
| [RPCraft](https://github.com/SamarthPyati/RPCraft) | RPC framework on raw TCP, plus live eavesdropping, replay and MITM attacks and the AES-CTR + HMAC version that stops them | Python, sockets |

Also: a [Lox interpreter](https://github.com/SamarthPyati/loxi), a [text editor](https://github.com/SamarthPyati/Grive) and [cellular automata](https://github.com/SamarthPyati/cellular-automata) in C, [arbitrary-precision integers](https://github.com/SamarthPyati/bigint) in C++, and my [competitive programming toolkit](https://github.com/SamarthPyati/cp-toolkit).

### Tools

- **Languages:** Python · C · C++ · Rust · SQL · TypeScript
- **AI/ML:** PyTorch · Transformers · LangGraph · LangChain · LoRA/PEFT · OpenCV · YOLO
- **Systems & backend:** Linux · OpenMP · CUDA · FastAPI · PostgreSQL · Redis · Docker

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SamarthPyati&layout=compact&theme=transparent&hide_border=true&langs_count=6" alt="Top languages" height="150" />
