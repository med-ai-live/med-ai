# Med-AI · Global Health OS
## Project Dossier — Current Status, Roadmap and Projections

**Author / Owner:** Thiago Schuber — Founder · *Father of Lis and Nina*
**Contact:** hello@med-ai.live
**Domain:** med-ai.live
**Generated on:** June 2, 2026

> **Honesty note:** the financial figures in this document are **illustrative scenarios** based on **assumptions to be validated** with real customers — they are **not** revenue guarantees. What is fact today is in the "What is already live" section, verifiable in production.

---

## 1. Purpose

Med-AI was born to be the **digital infrastructure of healthcare** — reducing medical error, providing patient safety, and connecting patients, doctors and the health system. More than a product, it is the construction of **lasting value**: a solid company, with real impact on people's lives, and a legacy that makes sense for the long term — including securing a better future for my daughters, **Lis and Nina**.

---

## 2. Timeline

| Milestone | Date |
|---|---|
| Concept / stack definition | May 2026 |
| First version live (med-ai.live) | June 1, 2026 |
| Clinical core + specialized modules | June 1–2, 2026 |
| This dossier | June 2, 2026 |

**Infra:** own server (Ubuntu), PostgreSQL, NestJS, Nginx, HTTPS. Running alongside pixnacional365 without conflict. Code versioned in a private repository (GitHub).

---

## 3. What is already LIVE (in production, verifiable)

**Clinical core**
- Patient registration (CPF validation, history, lifestyle habits)
- Medical record: triage with vital signs + BMI, encounter, **history**, **automatic SOAP**
- **Structured prescription** (quantity, frequency, duration, instructions) + medication autocomplete + voice dictation
- **Safety alert engine** (deterministic, auditable): allergies, cross-class allergy, drug interactions, pregnancy contraindications, duplication, diagnosis–conduct divergence — **blocks finalization** until reviewed
- **Catalogs**: laboratory, SUS (SIGTAP), imaging (CEDIP)
- **Labs platform**: result ingestion + **automatic flagging of abnormal values** (e.g., high CRP, anemia)
- **Calculators**: BMI, Cockcroft-Gault, CHA₂DS₂-VASc, Wells, Glasgow, **pediatric dosing (mg/kg, mL, max dose)**
- **Patient 360° panel** (Digital Twin-lite)

**Specialized modules**
- **Prenatal** (automatic GA/EDD, obstetric history, serologies)
- **Gynecology / Climacteric** (menopause, symptoms, bone health)
- **Neonatology** (automatic classification of prematurity/birth weight/APGAR, screenings, vitals with alerts, IV fluids)
- **Vaccination** record (doses, age)

**Platform & operations**
- **Telemedicine** (video), **Scheduling** (correct timezone), **Wearables** (real time), **Health Wallet** (documents)
- **Private support AI**: explains exams, suggests conduct — always "review and sign". Runs on the project's own infrastructure (privacy-first), provider-abstracted; offered via Med Credits in the commercial model
- **Med Credits** (internal economy): purchase via **Pix**, spent on services/AI/API
- **API Platform** (keys + quota) for partners
- **Document generator** (prescription, medical certificate, referral, exam requests, report)
- **Multilingual website** (PT/EN/ES), admin panel with **metrics dashboard**
- **Doctor self-registration** (with admin approval)

**Compliance**
- Consent (LGPD), **audit trail**, role-based access control, patient data protected by login

---

## 4. Next steps (short term)

- Clinical-grade AI engine for the commercial phase (privacy-first)
- Pix **webhook** → automatic credit (in finalization)
- WHO/Fenton growth curves (z-score/percentile) — pediatrics/neonatology
- Full well-child care (puericultura), expanded autocomplete, server-side voice transcription (Whisper)

---

## 5. Roadmap (phases)

| Phase | Horizon | Focus |
|---|---|---|
| **1 — Core** | done | Records, support AI, safety, specialized modules |
| **2 — Adoption** | 30–90 days | Real doctors using it, feedback, clinical-grade AI engine, onboarding |
| **3 — Network** | 90–180 days | Partners (labs, pharmacies), public API, marketplace |
| **4 — Scale** | 180–365 days | Health plans, B2G, expansion; evaluate Health Economy |
| **5 — International** | 365 days+ | Multi-country; tokenization **only** with legal structure |

---

## 6. Revenue models

| Model | How it generates revenue |
|---|---|
| **B2B** | Subscription per doctor/clinic (monthly) |
| **B2B2C** | Clinic/doctor uses it and offers services to patients (credits, telemedicine) |
| **B2G** | Contracts with municipalities/health departments (license + SUS integration) |
| **Marketplace** | Commission on partner pharmacies/labs |
| **Med Credits / AI / API** | AI consumption, credits and partner API calls |

---

## 7. Revenue projection — SCENARIOS (assumptions to validate)

> Base assumption: B2B subscription ~**R$ 149/doctor/month**. Figures are **illustrative**, for discussion — to be validated with real sales.

**B2B revenue (year 1)**
| Scenario | Paying doctors | Approx. annual revenue |
|---|---|---|
| Conservative | 50 | ~R$ 89k |
| Base | 300 | ~R$ 536k |
| Optimistic | 1,000 | ~R$ 1.79M |

**Other streams (to be added, per contracts):** marketplace (commission), Med Credits/AI, and **B2G** (public contracts tend to be higher value but with longer cycles — handle case by case).

**Honest read:** the bottleneck is not technology (already live) — it is **adoption and contracts**. A realistic projection depends on: (1) doctors paying, (2) signed partners, (3) eventual public contracts.

---

## 8. Risks & compliance

- **LGPD:** health data is sensitive — consent, encryption and audit from day one (implemented).
- **ANVISA (SaMD):** the decision-support layer may qualify as a medical device — to be handled **before** large-scale clinical use.
- **CFM:** telemedicine follows its own rules.
- **Tokenization:** only with legal counsel (securities). Today the economy runs on **Med Credits** (utility).

---

## 9. Conclusion

The technological foundation — usually the most expensive and time-consuming part — **already exists and is live**. The next chapter is about **adoption, partnerships and commercial validation**. With honest execution and a focus on real patient impact, Med-AI has the fundamentals to become a relevant health infrastructure — and a solid, lasting company.

---

**Thiago Schuber**
Founder — Med-AI · med-ai.live
*Father of Lis and Nina*
June 2, 2026

*Working document. Projections are illustrative scenarios, not guarantees.*
