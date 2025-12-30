<div align="center">
  <h2 align="center">Software Engineer</h3>

  <p align="center">
    Building high-performance, privacy-first AI tools and scalable web infrastructure.<br>
  </p>
</div>

---
<h3 align="center">Engineering Stack</h3>
<h4 align="center"><i>I have experience in</i></h3>

<div align="center">
  <p>
    <b>Languages</b><br>
    TypeScript, JavaScript, Python, Rust, Golang, SQL
  </p>
  <p>
    <b>Frontend</b><br>
    React, Next.js, SolidJS, Tauri 
  </p>
  <p>
    <b>AI & Automation</b><br>
    LLMs, Embeddings, RAG Systems, n8n, LLama.cpp, vLLM
  </p>
  <p>
    <b>Databases & MQ</b><br>
    PostgreSQL, MySQL, SQLite, Redis, BullMQ, Qdrant
  </p>
  <p>
    <b>DevOps</b><br>
    Linux, Docker, Git, GitHub Actions 
  </p>
</div>

---

<div align="center">
  <h3><b>Selected Work</b></h3>
</div>
<div align="center">
  <h3>
    <a href="https://github.com/alpaim/vecdir">vecDir: Local-First Semantic Search Engine</a>
  </h3>
  <p>
    <i>Rust • Tauri • SQLite-Vec • TypeScript • React</i>
  </p>

  
  <a href="https://github.com/alpaim/vecdir">
      <img src="https://raw.githubusercontent.com/alpaim/vecdir/main/public/vecdir-banner.png" alt="View Code" width="100%" />
  </a>
  

  <h3>
    "Semantic search for your local files - running 100% offline and private"
  </h3>
  
  <p>
    A privacy-obsessed desktop search engine that uses <b>Local LLMs</b> to "read" your documents and "see" your images, indexing them into a <b>Vector Database</b> by <i>meaning</i>, not just keywords. 
    <br>
    <b>Zero Data Leaves YOUR Device. ~10MB Binary. Blazing Fast.</b>
  </p>
</div>

<br>

#### Native Performance
Built on **Rust & Tauri** (v2) to avoid Electron bloat. Achieved a **~10MB binary size**. Optimized for zero-cost abstractions and memory safety, leaving system resources available for heavy local LLM inference.

#### Multimodal RAG Pipeline
Orchestrates local Vision & Text LLMs to index file *meaning*. Implements **Matroshka Embeddings** and **SQLite-Vec** for high-density, sub-100ms vector search.

#### Multi-Space Architecture
Supports isolated **"Spaces"** with distinct configurations. Use a heavy Vision model for a "Photos" space and a specialized Code LLM for a "Dev" space. Segregates indices logically and physically.

#### No Vendor Lock-in
**Fully Decoupled Logic:** Point to *any* endpoint (LLama.cpp, vLLM, Ollama, OpenAI). Users have granular control to customize **System Prompts** for specific file types and define custom Base URLs.

#### Smart Differential Indexing
Implements a high-concurrency crawler (utilizing *ripgrep* logic). Tracks file metadata to process **only new changes**, ensuring efficient synchronization without full re-indexing loops.

#### Safety & Privacy
**100% Local:** No data leaves your device. **Strict Read-Only:** The architecture operates on a one-way data flow. It creates a virtual index but is **physically incapable** of modifying, moving, or deleting user files.

<br>

<div align="center">
  <a href="https://github.com/alpaim/vecdir">
    <img src="https://img.shields.io/badge/View_Source_Code-black?style=for-the-badge&logo=github" alt="View Code" />
  </a>
</div>
