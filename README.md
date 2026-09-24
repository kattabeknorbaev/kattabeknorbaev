```console
$ whoami

Kattabek Norbaev — Tashkent, Uzbekistan
co-founder & lead engineer @ Tomaris AI · CTO @ Oqoo
```

Most software assumes someone else's language, someone else's bandwidth, someone else's eyesight. I build the version that assumes you're here.

Right now that mostly means **Uzbek-language AI** — collecting and cleaning training data, fine-tuning on rented GPUs, and shipping the product around it.

---

## Building now

### [Tomaris AI](https://tomaris.ai) · co-founder & lead engineer

An AI platform for the Uzbek language. I collected and cleaned the training data, fine-tuned the model on rented GPUs, and built everything around it — inference pipeline, RAG, auth, API, web app — then set up evaluations for accuracy and latency so quality moves on evidence rather than vibes. It answers only from documents the customer's team has approved, and hands off to a named operator, thread attached, when it shouldn't answer.

`llm` `fine-tuning` `rag` `evals` `next.js`

### [Oqoo](https://oqoo.ai) · CTO

An exam-prep marketplace for Central Asia — IELTS, SAT, UNT, TOEFL, AP, IB, A-Level, NUET. An operator verifies each tutor's identity, documents and real exam result; progress metrics are computed by the system so nobody can pad their own profile. Zero commission on lessons: students pay tutors directly.

`marketplace` `scheduling` `payments` `edtech`

---

## Shipped

### [Conceptaa](https://conceptaa.com) · founder

AI mind-mapping for students — paste in what you're trying to learn, get back a structure you can hold in your head. Full-stack React and TypeScript with ML-based structuring.

`react` `typescript` `ml`

### [BrailleBridge](https://braillebridge.xyz) · founder

OCR pulls the text out of a scan and returns it as Braille. Most documents that circulate here are photographs of paper, which makes them invisible to a screen reader. This closes that gap.

`ocr` `react` `accessibility`

### [Himoya](https://github.com/kattabeknorbaev/himoya-scam-detector) · creator

A browser extension that catches scams aimed at Uzbek speakers: forged verification badges, unicode homoglyphs, and the specific grammar of manufactured urgency, across 171 keyword patterns. Built after watching someone close to me come within one tap of sending $200 to a fake account.

`browser-extension` `security` `nlp`

---

## Research

**AI phishing detection for Uzbek Telegram users** — lead researcher and author.

I read through 1,000+ phishing samples looking for what the effective ones share — linguistic patterns, unicode homoglyphs, the psychology of engineered urgency — then built an NLP model that reaches **97.5% accuracy** on them, plus a policy framework for acting on it. Security research is overwhelmingly done in English, on English, and the tooling inherits that. Under-resourced language environments get the leftovers.

[Read the paper →](https://zenodo.org/records/17439674)

---

## Teaching

Co-founded **EduCam**, free A-Level tutoring for students who couldn't reach any, mostly in villages — 12 teachers, 158 students. The first version burned volunteers out, so I rebuilt the system around rotating schedules capped at four students per cycle and question-led sessions submitted in advance. Teacher retention went from 30% to 85%.

I also teach SAT at [Step12](https://step12.uz), which is the part that keeps me honest. It's hard to hide behind jargon in front of a room of teenagers.

---

## What's public here

Most of my source is private — Tomaris and Oqoo are commercial, and the earlier work is a working repo rather than a showcase. What's open:

- **[himoya-scam-detector](https://github.com/kattabeknorbaev/himoya-scam-detector)** — the scam-pattern engine
- **[tomaris-ui](https://github.com/kattabeknorbaev/tomaris-ui)** — front end for Tomaris
- **[rocklook](https://github.com/kattabeknorbaev/rocklook)** — gaze tracking with MediaPipe FaceMesh and a distance-invariant ratio algorithm
- **[aircanvas](https://github.com/kattabeknorbaev/aircanvas)** — painting in 3D space from hand landmarks

For the private work, the deployed products are the fastest route — or ask and I'll walk you through the architecture.

---

## Stack

`Python` `TypeScript` `JavaScript` `React` `Next.js` `Node`
LLM fine-tuning · RAG · evals · NLP · OCR · MediaPipe

---

## Elsewhere

[Site](https://personalweb-eight-drab.vercel.app/) · [Email](mailto:kattabeknorbayev@gmail.com) · [Telegram](https://t.me/NorbayevKattabek) · [Book 15 minutes](https://cal.com/kattabek-norbaev/15min)
