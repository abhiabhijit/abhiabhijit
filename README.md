# Hi, I'm Abhijit 👋

**Founder, [Ring Zero Security](https://ringzerosecurity.com)** — runtime security for AI agents.

## The problem I'm solving

AI agents now run on real machines with a developer's full access — reading files, launching processes, opening network connections — and no security tool can answer the basic question: *what is this specific agent allowed to do?*

Guardrails read words; the damage is always an action. EDR watches and alerts *after* it ran. I enforce the action itself, in the OS kernel, before it happens.

## What I'm building

**Ring Zero** — per-agent, deny-by-default policy enforced below the agent, where a prompt can't talk its way around it:

- **Linux:** eBPF/LSM enforcement module — working today
- **Windows:** pure-Rust driver plus user-mode service — in build
- **Policy model:** one policy per AI — which files, which programs, which connections
- **Telemetry:** every allow and deny ships to Splunk, Sentinel or Elastic — your SIEM, not ours

The thesis: instructions guide behaviour, but only independent runtime controls contain actual effects. Credential ≠ authority.

## Background

- 🛡️ **Windows kernel engineer** — Norton NIS, WFP (Windows Filtering Platform); kernel code shipped on 20M+ endpoints; drivers through WHQL
- 🏢 **Ex-NortonLifeLock** — enterprise endpoint security
- 🎓 **Stanford** — Advanced Cyber Security Program
- 🚀 **DraperU** founder program

## Tech arsenal

- **Systems:** Rust · C · eBPF · Windows drivers (WFP / minifilter) · LSM
- **Backend & tooling:** TypeScript · Python · tokio · axum
- **Design principles:** deny-by-default · least privilege · kernel-first enforcement

## Selected work

- 🔒 **Ring Zero engine** — the flagship enforcement codebase (private repo; public writeup on the way)
- 🛡️ **LLM-Guardrails** — experiments in guardrailing LLM tool-use
- 📌 More in the pinned repositories below

## Currently

- Building the Windows enforcement module in pure Rust
- Running CISO conversations on agent security — working toward 20 calls and 2 design partners
- Writing about kernel-level agent containment

## Stats

![Abhijit's GitHub stats](https://github-readme-stats.vercel.app/api?username=abhiabhijit&show_icons=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=abhiabhijit&layout=compact)

## Reach me

- 📧 abhijitastlar@gmail.com
- 𝕏 [@cyb3r_batman](https://x.com/cyb3r_batman)
- 🌐 [ringzerosecurity.com](https://ringzerosecurity.com)

---

*If you arrived here from my work on AI agent security — welcome. The kernel is the last layer an agent can't argue with.*
