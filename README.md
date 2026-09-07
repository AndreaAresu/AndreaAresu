## Andrea Aresu

AI / ML Engineer — applied LLM systems, speech recognition, adversarial robustness
Cagliari, Italy · Open to remote, and to relocation within Europe

---

### Currently

- Building and shipping **LLM systems** that run in production: agents
  with tool calling, retrieval over real corpora, and the guardrails that decide when a model
  must not answer on its own.
- First author on **SardinianVoxes**, on deep speech recognition for Sardinian, a low-resource
  language ([SSRN preprint](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6659799)).
- Looking for a first full-time role as an AI / ML engineer.

---

### Featured

**[asr-pipeline](https://github.com/AndreaAresu/asr-pipeline)** — *Python · FastAPI · Postgres/pgvector · MCP*
Upload a recording, get a searchable transcript. Whisper transcription off a job queue, semantic
search over every transcript with pgvector, cached LLM summaries, and an MCP endpoint that hands
the same retrieval to an assistant as three tools. The retrieval is graded by hand against a fixed
query set: 15/15 top-3 hits landed in the right recording, 9/10 queries ranked
the best passage first. Live demo, no signup.

**[whatsapp-host-assistant](https://github.com/AndreaAresu/whatsapp-host-assistant)** — *Node.js · Claude · human-in-the-loop*
A WhatsApp assistant for a holiday rental that **knows when to ask a human**. It answers the safe
questions on its own and turns everything else — prices, dates, breakages — into a draft the host
approves from Telegram. Prompt caching cut input cost by ~90%; 184 offline tests run in under a
second. [Live demo](https://estaated.it/assistant/).

**[asr-attack](https://github.com/AndreaAresu/asr-attack)** — *Python · PyTorch · Hugging Face*
Computer vision has Foolbox and ART; speech recognition had no equivalent. FGSM, PGD, noise and
environmental attacks behind one consistent API across ~10 Hugging Face ASR families — Whisper,
wav2vec2, HuBERT, MMS and more — with benchmark reports in HTML and JSON. `pip install asr-attack`

---

### Background

- **BSc in Applied Computer Science & Data Analytics** — University of Cagliari, 107/110 (2025)
- **Research intern, ASR for minority languages** — University of Cagliari. Built the dataset
  pipeline for Sardinian from raw video through to model-ready speech, fine-tuned Whisper on it,
  cutting mixed-variety WER from ~52% to ~30%, and evaluated generalization and adversarial
  robustness. First author on the resulting preprint.
- **MSc in Computer Engineering, Cybersecurity & AI** — University of Cagliari, *discontinued*
  to move into industry

---

### Reach out

- LinkedIn: [andrea-aresu](https://www.linkedin.com/in/andrea-aresu-4b1483206/)
- Email: aaresu01@gmail.com
