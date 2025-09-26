# GAA — Genesis Agent Algebra

This repository defines the **Genesis Agent Algebra (GAA)**, part of the **Genesis v2 project**.

---

## 📌 Context — Genesis v2

Genesis v2 is an open framework for **AI-native memory**, designed to be:
- Deterministic  
- Auditable  
- Privacy-first (consent by design)  
- Compatible with GDPR / AI Act  

Core layers:
- **L — Language (GMQL)**  
- **E — Engine (LifeDB)**  
- **R — Rosetta (consent & privacy)**  
- **D — Drivers (SQL/NoSQL/Vector connectors)**  

On top of these, **GAA** specializes the algebra for agents.

---

## 📑 About GAA

- **Scope:** specialization of GGA for **AI agents**  
- **Operators (v0.1):** GGA ∪ {RECALL, SUMMARY, CHECK, PIPE, PAR, SET, GET}  
- **Closed-loop operator (Γ):** (y_t, Σ_{t+1}) = Γ(Σ_t, P)  
- **Translation Law:** every GAA program compiles to a GMQL sequence  
- **Use cases:** generic agent recall, summarization, policy-guarded writes  

---

## 📂 Repository contents

- `GAA_WHITEPAPER_v0_1.md` — public whitepaper (v0.1)  
- `specs/` — detailed specification and ASCII diagrams  
- `src/` — reference Python skeleton (intents & agent ops)  
- `tests/` — minimal pytest suite  
- `.github/workflows/` — CI workflow (pytest)  

---

## 🔗 Related repositories

- [Genesis-v2](https://github.com/drazenco/Genesis-v2) — main project  
- [GGA](https://github.com/drazenco/GGA) — general algebra  
- [Genesis-algebra](https://github.com/drazenco/Genesis-algebra) — umbrella overview  

---

## 🚀 Status

- **Version:** v0.1 (public draft)  
- **License:** MIT

⚠️ Developer Preview — Not Production Ready
