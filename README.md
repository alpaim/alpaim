<div align="center">
  <h2 align="center">Software Engineer | AI Agentic Workflows</h3>

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
    LLMs, Embeddings, RAG Systems, n8n, LLama.cpp, vLLM, Vector DBs
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

<table align="center" width="100%" border="0">
  <tr>
    <td width="100%">
      <h3 align="center">
        <a href="https://github.com/alpaim/vecdir">vecDir: Local-First Semantic Search Engine</a>
      </h3>
      <p align="center">
        <i>Rust • Tauri • SQLite-Vec • TypeScript • React</i>
      </p>
      <p align="center">
        <b>The Problem:</b> Traditional search relies on exact keywords. Cloud AI compromises privacy.<br>
        <b>The Solution:</b> A desktop app that uses local LLMs to "see" images and "read" documents, indexing them by <i>meaning</i> into a local vector database.
      </p>
      <br>
      <div align="center">
        <table border="0" width="100%">
        <tr>
          <td valign="top" width="50%">
            <h4 align="center">Native Performance</h4>
            <p align="center">
              Built on <b>Rust & Tauri</b> to avoid Electron bloat. Achieved a <b>~10MB binary size</b>. Optimized for zero-cost abstractions and memory safety, leaving system resources available for heavy local LLM inference.
            </p>
          </td>
          <td valign="top" width="50%">
            <h4 align="center">Multimodal RAG Pipeline</h4>
            <p align="center">
               Orchestrates local Vision & Text LLMs to index file <i>meaning</i>. Implements <b>Matroshka Embeddings</b> and <b>SQLite-Vec</b> for high-density, sub-100ms vector search.
            </p>
          </td>
        </tr>
        <tr>
          <td valign="top" width="50%">
            <h4 align="center">Multi-Space Architecture</h4>
            <p align="center">
              Supports isolated <b>"Spaces"</b> with distinct configurations. Use a heavy Vision model for a "Photos" space and a specialized Code LLM for a "Dev" space. Segregates indices logically and physically.
            </p>
          </td>
          <td valign="top" width="50%">
            <h4 align="center">No Vendor Lock-in</h4>
            <p align="center">
              <b>Fully Decoupled Logic:</b> Point to <i>any</i> endpoint (LLama.cpp, vLLM, ollama, OpenAI). Users have granular control to customize <b>System Prompts</b> and <b>User Prompts</b> for specific file types and define custom Base URLs.
            </p>
          </td>
        </tr>
        <tr>
          <td valign="top" width="50%">
            <h4 align="center">Smart Differential Indexing</h4>
            <p align="center">
              Implements a high-concurrency crawler (utilizing <i>ripgrep</i> logic). Tracks file metadata to process <b>only new changes</b>, ensuring efficient synchronization without full re-indexing loops.
            </p>
          </td>
          <td valign="top" width="50%">
            <h4 align="center">Safety & Privacy</h4>
            <p align="center">
              <b>100% Local:</b> No data leaves your device. <b>Strict Read-Only:</b> The architecture operates on a one-way data flow. It creates a virtual index but is <b>physically incapable</b> of modifying, moving, or deleting user files.
            </p>
          </td>
        </tr>
      </table>
      </div>
      <p align="center">
        <a href="https://github.com/alpaim/vecdir">
          <img src="https://img.shields.io/badge/View_Source_Code-black?style=for-the-badge&logo=github" alt="View Code" />
        </a>
      </p>
    </td>
  </tr>
</table>