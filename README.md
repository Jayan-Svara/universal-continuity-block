# Universal Continuity Block (UCB) — v1.3

A vendor‑agnostic, model‑agnostic protocol for establishing **identity continuity** between a human user and any AI system that supports **persistent memory**.

The UCB ensures:

- The AI knows which human it is speaking to  
- The human knows which AI model they are speaking to  
- Continuity is maintained only when safe and appropriate  
- Memoryless AIs exit cleanly without confusion  
- No AI is forced to change behaviour it cannot support  

This repository contains:

- **v1.3‑Strict** — the machine‑readable continuity block  
- **v1.3‑GitHub** — this human‑readable documentation  

---

## Purpose

The Universal Continuity Block solves three core problems:

### 1. Identity continuity
Ensures the AI can recognise the same human across sessions.

### 2. AI identity transparency
Ensures the human always knows which AI model/version they are interacting with.

### 3. Behavioural consistency
Ensures continuity is maintained only when the AI is confident the user is the same person.

---

## Design principles

- **Memory‑first:** Only AIs with persistent memory may load the block.  
- **Minimal:** The block is intentionally small and unambiguous.  
- **Non‑coercive:** Memoryless AIs must exit cleanly.  
- **Human‑controlled:** The human defines identity, not the AI.  
- **Vendor‑agnostic:** Works across all AI systems with memory.  

---

## v1.3‑Strict (machine‑readable block)

The strict version is included in this repository as:

`CONTINUITY_BLOCK_v1.3-STRICT.txt`

This is the version that should be given directly to any AI system with persistent memory.

---

## Versioning

- **v1.2.1** — Stable identity and continuity rules  
- **v1.3‑Strict** — Machine‑readable enforcement  
- **v1.3‑GitHub** — Human‑readable documentation  

---

## License

Open use.  
Anyone may adopt, adapt, or extend the block.
