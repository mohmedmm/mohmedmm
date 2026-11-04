<div align="center">

# Mohammed Alshyakh
### Systems & Machine Learning Engineer • Open Source Contributor
**Tripoli, Libya • [nbox.ly](https://nbox.ly) • [alshaykh@nbox.ly](mailto:alshaykh@nbox.ly)**

[![GitHub](https://img.shields.io/badge/GitHub-mohmedmm-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mohmedmm)
[![Platform](https://img.shields.io/badge/Platform-nbox.ly-6366F1?style=flat-square&logo=google-chrome&logoColor=white)](https://nbox.ly)
[![Email](https://img.shields.io/badge/Email-alshaykh%40nbox.ly-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:alshaykh@nbox.ly)
[![Profile Views](https://hits.sh/github.com/mohmedmm.svg?style=flat-square&label=Profile+Views&color=007ec6)](https://hits.sh/github.com/mohmedmm/)

<p align="center">
  <em>Systems and software engineer contributing upstream fixes and runtime enhancements to foundational machine learning libraries, distributed inference engines, and developer tooling.</em>
</p>

</div>

---

## 🚢 Merged Upstream Contributions

Direct code contributions merged into industry-standard open source repositories:

| Organization / Project | Area | Merged Pull Request & Scope | Status |
| :--- | :--- | :--- | :---: |
| **Google** (`google-gemini/cookbook`) | `AI Framework & Dev Platform` | [**#1445**](https://github.com/google-gemini/cookbook/pull/1445): Preserve multiline strings with magic-like syntax in nblint<br/>[**#1436**](https://github.com/google-gemini/cookbook/pull/1436): Exclude fenced code blocks from markdown anchor extraction | [![Merged](https://img.shields.io/badge/PR_%231445-Merged-8957e5?style=flat-square&logo=google&logoColor=white)](https://github.com/google-gemini/cookbook/pull/1445)<br/>[![Merged](https://img.shields.io/badge/PR_%231436-Merged-8957e5?style=flat-square&logo=google&logoColor=white)](https://github.com/google-gemini/cookbook/pull/1436) |
| **Tenstorrent** (`tt-metal`) | `Silicon Kernels & Math Ops` | [**#55598**](https://github.com/tenstorrent/tt-metal/pull/55598): Prevent non-finite NaN in Moreh `norm_backward` for zero-norm slices | [![Merged](https://img.shields.io/badge/PR_%2355598-Merged-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/tenstorrent/tt-metal/pull/55598) |
| **Qdrant** (`fastembed`) | `Vector Embedding Runtime` | [**#717**](https://github.com/qdrant/fastembed/pull/717): Normalize dynamic tokenizer padding for ONNX embedding pipelines *(co-author)* | [![Merged](https://img.shields.io/badge/PR_%23717-Merged-8957e5?style=flat-square&logo=git&logoColor=white)](https://github.com/qdrant/fastembed/pull/717) |

---

## 🔍 Active Upstream Pull Requests & In-Review

Contributions addressing edge-case exceptions, runtime routing, and CLI features across foundational ecosystems:

| Organization / Project | Component | Contribution Details | Status |
| :--- | :--- | :--- | :---: |
| **OpenAI** (`openai/tiktoken`) | `BPE Tokenizer Runtime` | [**#631**](https://github.com/openai/tiktoken/pull/631): Normalize `KeyError` payloads across all public decode helpers for negative, out-of-range, and overflowing ranks | [![In Review](https://img.shields.io/badge/PR_%23631-In_Review-238636?style=flat-square&logo=openai&logoColor=white)](https://github.com/openai/tiktoken/pull/631) |
| **LibreChat** (`LibreChat-AI/LibreChat`) | `Full-Stack AI Architecture` | [**#17748**](https://github.com/LibreChat-AI/LibreChat/pull/17748): Route first-party GPT-6 Sol and Luna agents with tools to Responses API | [![Open PR](https://img.shields.io/badge/PR_%2317748-Open-238636?style=flat-square&logo=github&logoColor=white)](https://github.com/LibreChat-AI/LibreChat/pull/17748) |
| **Google** (`google/etils`) | `Python Core Utilities` | [**#849**](https://github.com/google/etils/pull/849): Ensure case-insensitive hash consistency across Python versions in `StrEnum` | [![Open PR](https://img.shields.io/badge/PR_%23849-Open-238636?style=flat-square&logo=google&logoColor=white)](https://github.com/google/etils/pull/849) |
| **Google** (`google/langextract`) | `Information Extraction` | [**#604**](https://github.com/google/langextract/pull/604): Anchor code fences to prevent improper splits on nested backticks | [![Open PR](https://img.shields.io/badge/PR_%23604-Open-238636?style=flat-square&logo=google&logoColor=white)](https://github.com/google/langextract/pull/604) |
| **JAX** (`jax-ml/jax`) | `Numerical & Tensor Ops` | [**#42242**](https://github.com/jax-ml/jax/pull/42242): Pad empty arrays with fill_value under vmap/jit transforms | [![Open PR](https://img.shields.io/badge/PR_%2342242-Open-238636?style=flat-square&logo=google&logoColor=white)](https://github.com/jax-ml/jax/pull/42242) |
| **Tenstorrent** (`tt-metal`) | `Silicon Kernels & Math Ops` | [**#55590**](https://github.com/tenstorrent/tt-metal/pull/55590): SFPU Chebyshev polynomial bridge for lgamma precision (<4 ULP)<br/>[**#55651**](https://github.com/tenstorrent/tt-metal/pull/55651): Route row-major gather to RmSingleRowSingleCore<br/>[**#61500**](https://github.com/tenstorrent/tt-metal/pull/61500): Credit alternate route in multicast all-gather on even rings | [![Approved](https://img.shields.io/badge/PR_%2355590-Approved-238636?style=flat-square&logo=git&logoColor=white)](https://github.com/tenstorrent/tt-metal/pull/55590)<br/>[![2 Active](https://img.shields.io/badge/2_PRs-Active-238636?style=flat-square&logo=github&logoColor=white)](https://github.com/tenstorrent/tt-metal/pulls?q=is%3Apr+author%3Amohmedmm) |
| **vLLM** (`vllm-project/vllm`) | `Distributed LLM Serving` | [**#59445**](https://github.com/vllm-project/vllm/pull/59445): Restrict cache path resolution to designated directory<br/>[**#60649**](https://github.com/vllm-project/vllm/pull/60649): Parse boolean filter arguments in benchmark sweep CLI | [![2 Active](https://img.shields.io/badge/2_PRs-Active-238636?style=flat-square&logo=github&logoColor=white)](https://github.com/vllm-project/vllm/pulls?q=is%3Apr+author%3Amohmedmm) |
| **Hugging Face** (`transformers`) | `ML Framework` | [**#48549**](https://github.com/huggingface/transformers/pull/48549): Support dict-typed dataclass fields in HfArgumentParser CLI | [![Open PR](https://img.shields.io/badge/PR_%2348549-Open-238636?style=flat-square&logo=huggingface&logoColor=white)](https://github.com/huggingface/transformers/pull/48549) |
| **Qdrant** (`qdrant/qdrant`) | `Vector Database Engine` | [**#10775**](https://github.com/qdrant/qdrant/pull/10775): Correct non-positive distance calculation in binary quantization for L1/L2 | [![Open PR](https://img.shields.io/badge/PR_%2310775-Open-238636?style=flat-square&logo=github&logoColor=white)](https://github.com/qdrant/qdrant/pull/10775) |
| **LiteLLM** (`BerriAI/litellm`) | `AI Gateway & Proxy` | [**#47191**](https://github.com/BerriAI/litellm/pull/47191): Validate provider completion payloads<br/>[**#40282**](https://github.com/BerriAI/litellm/pull/40282): Preserve reasoning tokens in stream chunk builder<br/>[**#41603**](https://github.com/BerriAI/litellm/pull/41603): Resolve model_group_alias in Vertex live config extraction | [![3 Active](https://img.shields.io/badge/3_PRs-Active-238636?style=flat-square&logo=github&logoColor=white)](https://github.com/BerriAI/litellm/pulls?q=is%3Apr+author%3Amohmedmm) |

---

## 🚀 Featured Engineering Projects

<div align="center">

| Project | Tech Stack | Highlights |
| :--- | :--- | :--- |
| [**system-design-pro**](https://github.com/mohmedmm/system-design-pro) | `Architecture` `Distributed Systems` `CLI` `Agent Skill` | **Distributed Architecture Engine & Capacity Calculator**: Comprehensive system design blueprints across 28 domains, automated estimation tools, RFC templates, and universal agent skills for Cursor, Claude Code, and Antigravity. |
| [**nbox**](https://github.com/mohmedmm/nbox) | `C++` `PyTorch` `ONNX Runtime` `CUDA` | **Neural Video Enhancer & Real-Time Upscaler**: GPU-accelerated video enhancement pipeline designed for low-latency upscaling and frame restoration without saturating host CPU resources. |
| [**gemma-vf-agent**](https://github.com/mohmedmm/gemma-vf-agent) | `Python` `Gemma 4` `Pytest` `AST` | **Verification-First Agentic Harness**: Deterministic code synthesis and bug-hunting framework that enforces test-driven validation, AST parsing, and regression verification before landing code edits. |
| [**Libya_ID**](https://github.com/mohmedmm/Libya_ID) | `Python` `FastAPI` `PostgreSQL` | **Carrier Directory Indexing Architecture**: Architecture specification and prototype lookup engine designed for high-throughput mobile number identification and structured query responses. |
| **Card SMS Gateway** *(Enterprise Service)* | `TypeScript` `Node.js` `Redis` `PostgreSQL` | **Resilient Verification Gateway**: Multi-provider SMS dispatch infrastructure with automatic failover, sliding-window rate limiting, and idempotent delivery tracking. |

</div>

---

## 🛠️ Technical Competency & Tooling

```
Core Languages       : Python (Advanced, Systems & Tooling), TypeScript / JavaScript, C++, Rust (Basics), SQL, Bash
ML Runtimes & Math   : PyTorch, JAX, Hugging Face Transformers, ONNX Runtime, tiktoken (BPE), Vector Search (Qdrant)
Systems & Backend    : FastAPI, Node.js (Express), PostgreSQL, Redis, REST APIs, JSON-RPC, Distributed Systems Design
Engineering Tooling  : Git, Linux, Docker, GitHub Actions CI/CD, Pytest, Jest, GDB, Valgrind
```

---

## 💡 Engineering Philosophy

- **Zero Synthetic Bloat**: No superficial abstractions, unnecessary try/except wrappers, or cosmetic reformatting. Code changes must be minimal, focused, and directly address root causes.
- **Idiomatic Alignment**: Strictly adhere to upstream codebase patterns, typing standards, and existing helper architectures.
- **Test-Driven Correctness**: Every bugfix or feature must be verified with focused unit and regression tests covering edge-case inputs, type conversions, and boundary conditions.

---

## 📊 GitHub Analytics

<table align="center" style="border: none; border-collapse: collapse; margin: auto;">
  <tr style="border: none;">
    <td align="center" valign="middle" style="border: none; padding: 6px;">
      <a href="https://github.com/mohmedmm">
        <img src="https://github-readme-stats.vercel.app/api?username=mohmedmm&show_icons=true&show=reviews&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&cache_seconds=1800" width="385" alt="Mohammed's GitHub Stats" />
      </a>
    </td>
    <td align="center" valign="middle" style="border: none; padding: 6px;">
      <a href="https://github.com/mohmedmm">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=mohmedmm&theme=tokyonight&hide_border=true" width="385" alt="Mohammed's GitHub Streak" />
      </a>
    </td>
  </tr>
</table>

---

## 📬 Contact & Links

- 🌐 **Platform:** [nbox.ly](https://nbox.ly)
- 💼 **GitHub:** [@mohmedmm](https://github.com/mohmedmm)
- 📧 **Email:** [alshaykh@nbox.ly](mailto:alshaykh@nbox.ly)
- 📍 **Location:** Tripoli, Libya
