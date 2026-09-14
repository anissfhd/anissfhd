# Hi, I'm Aniss 👋

4th-year engineering student, **Artificial Intelligence** specialization. I build retrieval systems, AI agents and full-stack applications — and I care about the part most demos skip: measuring whether the thing actually works.

🇫🇷 [Version française](README.fr.md)

---

## 🤖 AI & Machine Learning

### [Agentic Vectorial Graph RAG](https://github.com/anissfhd/agentic-vectorial-graph-rag)
A document assistant over a 206-page scientific thesis that **decides for itself** how to answer: vector search, knowledge graph, both, or "I don't know". 7 chunking methods and 7 embedding models actually benchmarked, a Neo4j Aura graph with 66 nodes and 171 relations, and a Q-Learning agent orchestrated by LangGraph.

`Python` `LangGraph` `FAISS` `Neo4j` `Q-Learning` `FastAPI` `React`

### [Taxi Joliette Voice Agent](https://github.com/anissfhd/taxi-joliette-voice-agent)
An AI phone agent that takes taxi bookings in Québécois French. The conversation is the easy part — the hard part is **never creating the same ride twice**, solved with per-call serialization plus `request_id` idempotency, and a Zod `z.literal(true)` that makes it structurally impossible to book without explicit customer confirmation.

`TypeScript` `Twilio ConversationRelay` `OpenAI` `n8n` `Zod` `Docker`

### [Deep Learning — MLP, CNN, Seq2Seq](https://github.com/anissfhd/Projet-Deep-Learning)
Three architectures for three data topologies, with convolution and pooling **written by hand** and verified against PyTorch (max difference: 0). Shows experimentally why constant weight initialization fails — neuron symmetry — and what inductive bias actually buys you.

`PyTorch` `LeNet-5` `GRU` `Beam Search` `MNIST`

### [Air Quality — Anomaly Detection](https://github.com/anissfhd/air-quality-anomaly-detection)
A year of hourly sensor readings, and two anomaly detectors that agree on only **42%** of events. The disagreement is the finding: Z-score fires on one extreme pollutant, Isolation Forest on an unusual combination.

`pandas` `scikit-learn` `Isolation Forest` `Ridge Regression` `Jupyter`

### [Sales AI Platform — Specification](https://github.com/anissfhd/sales-ai-platform-specs)
Design work rather than code: ~68,000 words defining an autonomous multi-country B2B prospecting platform — a 13-stage company lifecycle, compliance as a hard gate, and a full vendor benchmark.

`System Design` `Product Specification` `Architecture`

---

## 💻 Software Development

### [CDHubs — Digital Products E-commerce](https://github.com/anissfhd/cdhubs-digital-products)
A storefront for selling digital goods, in three deployable pieces: a NestJS + Prisma API over 11 models, a Next.js admin console, and a bilingual French/Arabic static storefront built for shared hosting.

`NestJS` `Prisma` `PostgreSQL` `Next.js` `TypeScript`

### [Club Sport — Management Platform](https://github.com/anissfhd/club-sport-management)
Members, events, trainings, payments and notifications in one place. Payment instalments are modelled as rows rather than a flag, which is what makes "who still owes what" answerable.

`Django REST Framework` `Next.js` `JWT` `Tailwind CSS` `MySQL`

### [Azelle — Language Exchange App](https://github.com/anissfhd/azelle-android)
Android app connecting people around language exchange. A 10-step guided onboarding builds a language profile — native language, learning languages with a level for each — with progress persisted server-side so closing the app mid-signup resumes where you left off.

`Kotlin` `Jetpack Compose` `Material 3` `Supabase`

### [Chess Infinity](https://github.com/anissfhd/chess-infinity)
Flutter tournament management app for a chess club. Early prototype — an animated branded launch screen on a six-platform scaffold.

`Flutter` `Dart`

---

<sub>Every repository here documents what works, what does not, and what is still missing.</sub>
