# 💧 AquaCheck: AI-Powered Water Contamination Risk Advisor

> Built for the **1M1B AI for Sustainability Virtual Internship (July–Sep 2026)**, in collaboration with IBM SkillsBuild & AICTE.
> **SDG 6 — Clean Water and Sanitation**

## The Problem

Millions of households rely on rainwater harvesting or stored municipal water rather than a continuous supply. Once water is stored, its safety is rarely checked — lab testing is often inaccessible, expensive, or simply not part of daily habit. Contamination risk builds quietly through factors like prolonged storage during monsoon, poor container hygiene, or surface-water sources — often with no visible warning until people fall ill.

**How might we use AI to assess water contamination risk from everyday, observable conditions, so that communities relying on stored or harvested water can access safer drinking water?**

## The Solution

AquaCheck is a two-stage AI tool that turns everyday observations into a water safety reading:

1. **Risk Classifier** — A rule-based AI model scores 8 observable factors (storage duration, container type, season, water source, clarity, odor, color, and last cleaning) and predicts a **Low / Medium / High** contamination risk level, showing exactly which factors drove the result.
2. **Retrieval-based Guidance Layer** — Inspired by Retrieval-Augmented Generation (RAG), this layer matches the triggered risk factors to relevant safety guidance from **WHO Drinking-water Guidelines**, **BIS IS 10500**, and local advisories — explaining *why* the water is risky and *what to do*, in plain language.

## AI Elements & Tools Used

- Rule-based AI classification (weighted multi-factor risk scoring)
- Retrieval-based guidance matching (RAG-inspired conditional retrieval)
- Prompt engineering (structuring plain-language guidance output)
- **IBM Bob** — used to scaffold and iterate on the prototype from natural-language logic descriptions
- HTML5, CSS3, JavaScript (prototype implementation)

## Live Demo

🔗 **[Try AquaCheck live](#)** ← replace with your GitHub Pages link

## Responsible AI Considerations

- **Fairness** — risk factors are based on observable conditions, not assumptions about any group or region
- **Transparency** — every risk level is shown with the specific factors and guidance behind it, not a black-box score
- **Ethics** — AquaCheck advises and informs; it never replaces professional lab testing for confirmed contamination
- **Privacy** — no personal or location-identifying data is collected; only water-condition inputs are used

## Impact

AquaCheck gives households, hostels, and small communities a fast, no-cost, explainable first line of defense against unsafe stored water — catching risky conditions before symptoms appear, without needing lab access. The same logic can scale to institutional water storage checks in testing-scarce regions.

## Project Team

**Krishna Dhakrey** — IIIT Manipur

---
*This is a screening aid, not a certified lab result. When in doubt, get water professionally tested.*
