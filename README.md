# Owning Your Agent prt 2 — Local Agent with Hermes on a Single RTX 3090; pushing the absolute limits

**Status:** 🚧 Coming Soon — Research in Development

## What this is

Module 2 of the **Owning Your Agent** trilogy. After [Module 1](https://github.com/zacangemi/owning-your-agent) explored what's possible with **dual** RTX 3090s, Module 2 takes the same agentic stack and asks the next obvious question: **can it run on one card?**

Most people own one consumer GPU, not two. So Module 2 pushes a single RTX 3090 to its absolute limits — same Hermes Agent, same daily-driver goal, half the hardware. Same surface area, sharper constraint problem.

## Research focus

- Maximum capable model that fits cleanly on a single 24 GB RTX 3090
- Quantization strategy that preserves tool-calling accuracy under tighter VRAM constraints
- Context window optimization with one card instead of two
- Performance ceiling: how much agentic work can a single consumer GPU actually do?

## What you'll find here when this ships

- `DECISIONS.md` — every architectural choice with one-line reasoning
- `METHODOLOGY.md` — reproducible methodology
- `LIMITATIONS.md` — honest limitations
- Benchmark results and analysis
- Launch configs for the single-GPU setup

## Companion to

- 📖 **Module 1 (shipped):** [Owning Your Agent — Local Agentic Work with Hermes on Dual RTX 3090s](https://blog.zacharycangemi.com/2026/05/20/owning-your-agent-part-1-local-agentic-work-with-hermes-on-dual-rtx-3090s/)
- 📂 **Module 1 repo:** [zacangemi/owning-your-agent](https://github.com/zacangemi/owning-your-agent)
- 📚 **Series prelude:** [Year of the Fire Horse, Year of the Agent](https://blog.zacharycangemi.com/2026/05/18/year-of-the-fire-horse-year-of-the-agent-a-prelude-to-my-agentic-research/)

---

*Part of [Project Arrival](https://zacharycangemi.com), my journey from Senior Data Scientist to AI research engineer.*
