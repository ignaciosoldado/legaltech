# legaltech
A collection of sums of legal codes in an accessible, versioned format. It promotes legal transparency and the development of legaltech solutions through open access to structured legal regulations.

# 📚 EU & Spanish Data Ethics — Regulatory Reference Library

> A structured reference library covering the core legal framework for data ethics professionals operating in Spain and the European Union. Each file provides an in-depth breakdown of one regulation: scope, key definitions, obligations, rights, enforcement, sanctions, and intersections with adjacent law.

---

## 🗂️ Contents

| # | File | Regulation | Language | Jurisdiction |
|---|------|-----------|----------|-------------|
| 01 | [GDPR.md](./01-GDPR.md) | General Data Protection Regulation (EU 2016/679) | 🇬🇧 English | 🇪🇺 EU |
| 02 | [LOPDGDD.md](./02-LOPDGDD.md) | Ley Orgánica de Protección de Datos y Garantía de los Derechos Digitales (LO 3/2018) | 🇪🇸 Español | 🇪🇸 Spain |
| 03 | [AI-Act.md](./03-AI-Act.md) | Artificial Intelligence Act (EU 2024/1689) | 🇬🇧 English | 🇪🇺 EU |
| 04 | [DGA.md](./04-DGA.md) | Data Governance Act (EU 2022/868) | 🇬🇧 English | 🇪🇺 EU |
| 05 | [Data-Act.md](./05-Data-Act.md) | Data Act (EU 2023/2854) | 🇬🇧 English | 🇪🇺 EU |
| 06 | [DSA.md](./06-DSA.md) | Digital Services Act (EU 2022/2065) | 🇬🇧 English | 🇪🇺 EU |
| 07 | [DMA.md](./07-DMA.md) | Digital Markets Act (EU 2022/1925) | 🇬🇧 English | 🇪🇺 EU |

---

## 🧭 Thematic Map

### Privacy and Personal Data
- **GDPR** → the foundational regulation; principles, rights, lawful bases, accountability
- **LOPDGDD** → Spanish adaptation; digital rights in the workplace; age of consent; AEPD

### Artificial Intelligence
- **AI Act** → risk-based classification; prohibited practices; high-risk obligations; GPAI models

### Data Governance and Sharing
- **DGA** → trusted data intermediaries; public sector data reuse; data altruism
- **Data Act** → IoT data access rights; B2B and B2G data sharing; switching; interoperability

### Digital Markets and Platforms
- **DSA** → platform accountability; illegal content; algorithmic transparency; systemic risk
- **DMA** → gatekeeper obligations; self-preferencing; data combination; interoperability

---

## 🔗 Regulatory Interactions

```
GDPR ──────────────────────────────────────────────────────────────────────┐
  │  Personal data processed by AI → AI Act Art. 10                        │
  │  Consent for data combination → DMA Art. 5(2)                          │
  │  Targeting rules → DSA Art. 26                                          │
  └──────────────────────────────────────────────────────────────────────── ┘

AI Act ──── High-risk AI in platforms → DSA systemic risk assessments
       ──── GPAI training data → Data Act / DGA access mechanisms
       ──── Gatekeeper AI (search, recommenders) → DMA Art. 6(5)

DGA ──── Data spaces governance backbone → Data Act access rights layer
    ──── Altruism consent form → GDPR lawful basis complement

DSA + DMA ── "Twin package" for large platforms (same designated companies)
```

---

## 📅 Application Timeline

| Regulation | Fully Applicable |
|-----------|-----------------|
| GDPR | May 2018 |
| LOPDGDD | December 2018 |
| DGA | September 2023 |
| DMA | May 2023 |
| DSA | February 2024 |
| Data Act | September 2025 |
| AI Act (prohibited practices) | February 2025 |
| AI Act (high-risk + GPAI) | August 2026 |
| AI Act (full) | August 2027 |

---

## 🏛️ Key Supervisory Authorities

| Authority | Role |
|-----------|------|
| **AEPD** (Spain) | Data protection; GDPR & LOPDGDD enforcement |
| **CNMC** (Spain) | Digital Services Coordinator (DSA) |
| **AESIA** (Spain) | AI supervision (in constitution) |
| **EDPB** | Coordination of EU data protection authorities |
| **EU AI Office** | GPAI supervision; AI Act coordination |
| **European Commission** | DMA enforcement; VLOP/VLOSE supervision (DSA) |

---

## 📖 How to Use This Library

Each file follows a consistent structure:
- **Header**: full regulation name, reference, entry into force date
- **Summary**: one-paragraph executive overview
- **Table of contents**: with anchor links
- **Sections**: scope → definitions → obligations → rights → enforcement → sanctions → ethics commentary
- **Regulatory interactions table**: cross-references to adjacent law
- **Official resources**: links to EUR-Lex, Commission pages and national authorities

Files are designed to be read independently or as a set. The GDPR and LOPDGDD are best read together. The AI Act pairs naturally with the GDPR (personal data in AI) and with the DSA/DMA (AI deployed in platforms).

---

*Last updated: June 2026 · For professional training and reference use in data ethics*
