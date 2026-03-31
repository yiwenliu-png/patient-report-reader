# Patient Report Reader
### AI-powered tool to help patients understand medical reports

Built from first-hand research into the patient-clinician information gap — 
a problem identified during a market strategy engagement with Syndiag, 
an AI diagnostic startup in Turin, Italy.

---

## The problem

Patients routinely receive medical reports — blood tests, imaging results, 
discharge summaries — written in clinical language they cannot understand. 
This creates anxiety, leads to unnecessary follow-up consultations, and 
erodes trust in the diagnostic process.

During B2B market research involving 300+ survey responses and qualitative 
interviews with clinicians across the Italian healthcare system, a consistent 
pattern emerged: **diagnostic uncertainty at the patient level creates 
downstream inefficiencies at the institutional level.**

This tool is a direct response to that insight.

---

## What it does

- Accepts medical report text (blood panels, imaging summaries, discharge notes)
- Returns a plain-language explanation of key findings
- Generates a structured list of questions the patient can bring to their doctor
- Supports Chinese and English (addressing the needs of patients navigating 
  foreign healthcare systems)

---

## Background & motivation

This project grew out of a consulting engagement with 
[Syndiag](https://syndiag.com), an AI healthcare company developing 
diagnostic decision-support tools for clinicians in Italy.

As part of the strategy team, I conducted:
- B2B market segmentation across public hospitals, private clinics, and 
  regional health systems
- Dual B2C–B2B analysis showing how patient-side confusion translates into 
  institutional demand for AI solutions
- Value proposition and positioning work framing AI as a decision-critical 
  support tool

The patient report website was developed as a prototype to test whether 
clear communication at the patient level could reduce the "second opinion 
seeking" behaviour identified in our research.

---

## Tech stack

- Built with [Manus](https://manus.im) AI development platform
- Frontend: HTML / CSS / JavaScript
- AI integration: Anthropic Claude API *(in development)*
- Deployment: web-based, mobile-accessible

---

## Roadmap

- [x] Core UI for report input and plain-language output
- [x] Bilingual support (Chinese / English)
- [ ] Anthropic Claude API integration for AI-powered explanations
- [ ] Structured "questions for your doctor" output module
- [ ] User testing with patients from the Syndiag research cohort
- [ ] PDF upload support

---

## Context

This tool sits at the intersection of three areas I'm actively researching:

1. **AI in clinical decision support** — how diagnostic tools affect 
   clinician behaviour and patient outcomes
2. **Health information asymmetry** — why patients struggle to engage 
   meaningfully with their own medical data  
3. **Cross-cultural healthcare navigation** — the specific challenges 
   faced by patients receiving care in a second language

---

## About

Developed by Yiwen Liu — ESCP Business School (BsC, 
Class of 2027). Previously: market strategy at Syndiag, marketing intern 
at Boston Scientific, overseas market role at Informa Markets.

Interested in digital health entrepreneurship and the commercialisation 
of AI diagnostic tools in European healthcare markets.

[LinkedIn](https://linkedin.com/in/yiwenliu) · 
[Email](mailto:yiwenliu1020@gmail.com)
