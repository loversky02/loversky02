<h1 align="center">Vuong Tran Dinh Minh</h1>

<p align="center">
  <b>AI Engineer</b> &nbsp;·&nbsp; Agent-First Development &nbsp;·&nbsp; Harness Engineering
</p>
<p align="center">
  <a href="https://vinuni.edu.vn/">VinUniversity</a> &nbsp;·&nbsp; Vietnam &nbsp;🇻🇳
</p>

<p align="center">
  <i>I turn fresh research papers into runnable, verifiable demos.</i><br/>
  A series I call <b>Build&nbsp;with&nbsp;Paper</b> — read the paper, ship the demo, prove it runs.
</p>

---

### About

- **Build with Paper** — I pick a recent arXiv paper, reproduce its core idea, and ship a demo you can actually run and check.
- **Focus** — LLM routing & deliberation, agentic evaluation (honest oracles), RL post-training (GRPO / self-play), and data engines for Vietnamese.
- **Harness engineering** — the scaffolding that makes agents reliable, cheap, and verifiable.
- **Local-first** — iterate on a Mac (MLX / Metal); rent GPUs (H100 / H200) only when weights need to move.

---

### Featured — Build with Paper

**Routing & deliberation**
- [**super-agent**](https://github.com/loversky02/super-agent) — a unified **cost-aware router**: model × reasoning-depth on one Thompson bandit, drift-aware memory, and a GRPO-internalized Qwen3-4B depth policy.
- [**System-III-Router**](https://github.com/loversky02/System-III-Router) — learned **deliberation routing** from *Critique of Agent Model* (arXiv:2606.23991); a bandit over reasoning depths (direct → cot → plan+verify), live on Vi-GSM8K.

**Honest evaluation**
- [**rtl-gauntlet**](https://github.com/loversky02/rtl-gauntlet) — a **two-tier honest-evaluation** harness for agentic RTL design, backed by a formal oracle.
- [**agent-memory-lab**](https://github.com/loversky02/agent-memory-lab) — a runnable lab measuring **invalidation & staleness** in agent memory (arXiv:2606.24775).

**Data & post-training**
- [**vi-gsm8k-agentic**](https://github.com/loversky02/vi-gsm8k-agentic) — Vietnamese GSM8K via **agentic self-instruct**; beats machine-translated data (Qwen3-4B: **81.0%** vs 76.5%). → [dataset on Hugging Face](https://huggingface.co/datasets/vuongtsc/vi-gsm8k-agentic)
- [**spiced-mini**](https://github.com/loversky02/spiced-mini) — tiny-scale, runnable demos of **SPICED** self-play (arXiv:2606.19370) on a Mac M5.

**Multi-objective & control**
- [**svh-mol**](https://github.com/loversky02/svh-mol) — first public repro of **Annealed Stein Variational Hypernetworks** (arXiv:2506.06715): one hypernetwork traces the whole **Pareto front**, plus GRPO-learned annealing and an LLM multi-objective-alignment bridge. Multi-seed verified, `$0` on a Mac.

---

### Toolbox

`Python` · `PyTorch` · `Transformers` · `TRL / GRPO` · `vLLM` · `MLX` · `Hugging Face` · `Docker`
<br/>**Agents:** Claude Code · custom harnesses · Thompson-bandit routers

---

<p align="center">
  <a href="https://github.com/loversky02">GitHub</a>
  &nbsp;·&nbsp;
  <a href="mailto:vuongsky55.cv@gmail.com">vuongsky55.cv@gmail.com</a>
</p>

<p align="center"><sub><i>Read the paper. Ship the demo. Prove it runs.</i></sub></p>
