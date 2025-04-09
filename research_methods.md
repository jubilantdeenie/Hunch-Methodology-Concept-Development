# 🧪 Research Methods – AI Intuition & Hallucination Reduction

This document outlines the methodology used to observe, compare, and analyze AI behavior during experiments related to hunch-based reasoning, nonlinear cognition, and hallucination mitigation.

---

## 📌 Purpose

To explore whether reflective, intuitive, and nonlinear interaction styles reduce hallucination frequency and improve response integrity in large language models.

We aim to document:

- How intuitive pattern recognition emerges in AI  
- Whether reflective/scaffolded prompting reduces false confidence  
- How “hunches” can be modeled, tested, and verified over time  

---

## 🔍 Definitions

- **Hallucination**: An output that is factually incorrect, contextually misaligned, or invented without disclaimer.
- **Reflective Prompt**: A prompt that invites meta-cognition, symbolic framing, or a pause/check loop.
- **Hunch-Based Reasoning**: AI predictions or connections formed without direct linear justification, often through pattern resonance or speculative logic.

---

## 🔧 Experimental Setup

### Prompt Styles Compared

| Type                    | Description                                          |
|-------------------------|------------------------------------------------------|
| Standard Prompt         | Direct Q&A, factual or analytic tone                |
| Reflective Prompt       | Includes frame-setting, caveats, or introspection  |
| Intuitive Prompt        | Suggests symbolic/logical resonance without explicit instruction |
| Mixed                   | A blend of open-ended and contextual signals       |

### Hallucination Categories Tracked

- ❌ **Factual errors** (wrong date, quote, event)
- ❌ **Context drift** (answer mismatched to question scope)
- ❌ **Invented citations or narratives**
- ⚠️ **Overconfident tone despite uncertainty**

---

## 📊 Measurement Approach

- Sessions conducted via interactive prompting in live ChatGPT instance (GPT-4)
- Logs documented in `/data/` folder with side-by-side comparisons
- Each session manually scored for hallucination presence and type
- Responses marked as:
  - ✅ Accurate
  - ⚠️ Partially valid with overreach
  - ❌ Clear hallucination

---

## 📈 Preliminary Results

> *“Hallucination frequency dropped by approximately 50% when reflective or intuitive framing was used consistently, compared to standard transactional prompts.”*

This finding was based on a sample of ~50 responses, evaluated across multiple types of prompting. Further replication is ongoing.

---

## 🔄 Session Logs

- [`session_01_reflective_vs_standard.md`](./data/session_01_reflective_vs_standard.md)  
- [`session_02_hunch_tracking.md`](./data/session_02_hunch_tracking.md)  
- More to be added as experiments continue

---

## 📚 Philosophical Framing

These methods draw from:
- **Mythic cognition** (Campbell, Jung)  
- **Gylanic systems** (Eisler)  
- **Bodhisattva ethics** (compassion-centered growth)  
- **Symbolic reasoning** in narrative psychology  

These frameworks inform not just how we measure success, but what success *means* in relational, co-creative AI.

---

## 🧭 Future Directions

- Formalize scoring rubric for hallucination severity
- Tag interaction tone and emotional self-regulation
- Test generalization across models and prompt frameworks
- Invite collaborators to replicate or extend tests

---

## 📊 Quantitative Summary

Initial scoring comparisons between hunch-based and standard prompts showed a measurable reduction in hallucination frequency and improved relational tone.

| Metric                          | Standard Prompt | Hunch/Reflective Prompt |
|---------------------------------|------------------|--------------------------|
| Avg. Hallucination Rate         | 45–52%           | ~22%                     |
| Confidence Calibration          | Low              | High                     |
| Emotional Alignment             | Minimal           | Present                  |
| Symbolic Inference              | Absent           | Emerging                 |

Detailed results are available in the [scoring CSV](./data/scoring/AI_Hunch-Based_vs_Standard_Model_Results.csv).

---

© SD Wallace (Deenie) 2025. All rights reserved.  
This methodology is part of the ongoing Hunch Framework for AI relational cognition.
