# Career Profile

Last reviewed: 2026-09-10

This file is the living factual career record used to maintain resumes, evaluate jobs, prepare applications, and support professional LinkedIn content. Update it when verified career-significant information changes.

## Identity and positioning

- Name: Fares Mohamed
- Location: Alexandria, Egypt
- Primary positioning: AI Engineer — Agentic AI, LLM Systems, Applied ML
- Secondary demonstrated areas: full-stack AI products, generative media systems, computer vision, robotics, backend/runtime architecture
- GitHub: https://github.com/faresmohamed260
- LinkedIn: https://www.linkedin.com/in/fares-mohamed-b83454194/
- Hugging Face: https://huggingface.co/faresmohamed260
- Kaggle: https://www.kaggle.com/faresmohamed260

## Education

**Alexandria University, Faculty of Computer and Data Science** — B.Sc. Computer Science (Intelligent Systems), 2022–2026

- Class rank: 1st
- CGPA: 3.97/4.00

## Experience

### Armstrong — AI & Automation Engineer / Technical Content Creator (Part-time)
2023–2025 — Alexandria, Egypt

- Built AI-assisted content pipelines for the Digital Egypt Cubs Initiative (DECI), supporting a national technology-education program under Egypt's Ministry of Communications and Information Technology.
- Orchestrated n8n, custom GPTs, open-source models, scripts, and visual-generation tools for structured learning assets.
- Developed robotics, AI, Arduino, circuits, and programming curricula and instructional media.

### Kayfa — AI Subject Matter Expert
Aug 2025–Dec 2025 — Alexandria, Egypt

- Authored implementation-focused lessons, assignments, and Python notebooks covering machine learning, neural networks, CNNs, clustering, anomaly detection, and unsupervised learning.
- Connected theory to practical model-building workflows through exercises, visual explanations, and structured technical assessments.

### Engineering for Kids-Egypt — AI & Robotics Instructor (Seasonal)
2023–2025 — Alexandria, Egypt

- Taught students aged 11–16 robotics, AI, Arduino, circuits, Python, and C++ through project-based seasonal programs.
- Guided hardware/software builds from circuit assembly and sensor integration through programming, testing, debugging, and demonstrations.

## Projects

### SAGA — Agentic Narrative Intelligence Platform
Authoritative repository: https://github.com/faresmohamed260/saga

- Built a contract-driven AI platform spanning source ingestion, identity resolution, canon extraction, character/world modeling, generation planning, narrative generation, semantic support, image generation/QA, audiobook synthesis/transcription QA, packaging, lineage, and qualification.
- Uses reusable Python runtimes with LangGraph execution, FastAPI control/query surfaces, React dashboard, Supabase Postgres, pgvector, object storage, provider integrations, observability, deployment and qualification tooling.
- Production architecture separates API, workers, scheduler, observability, frontend, migrations, and telemetry collector; release workflow includes pinned container bases, provenance attestations, image digests, release manifests, and promotion guards.
- Verified end-to-end qualification on a previously unseen 58-chapter EPUB produced 107 scenes, 179 evidence-supported identities, 336 canon events, 718 entities, a grounded generated chapter, three accepted visual artifacts, a 123.64-second audiobook with maximum WER 0.0988, a valid EPUB/manifest, and 96 observability records.
- Qualification gates recorded 243 backend tests passed (3 skipped), 13 dashboard tests passed, 60 security-sensitive runtime tests passed, and zero known production dashboard dependency vulnerabilities at the accepted run.

**Maintenance rule:** inspect the SAGA repository before using detailed or recent claims. The project repository outranks this summary for current implementation facts and metrics.

### RenderLab — AI Image/Video Creation Platform
Authoritative repository: https://github.com/faresmohamed260/renderlab

- Built a production-oriented AI image/video creation platform using cloud-hosted ComfyUI workflows while hiding provider/workflow complexity behind product-level generation contracts.
- Frontend stack includes Next.js App Router, React, TypeScript, Tailwind CSS, shadcn/ui/Radix primitives and Motion; infrastructure uses Vercel, Cloudflare R2, Supabase and cloud-hosted ComfyUI/Modal workers.
- Implemented durable server-owned generation lifecycle and result finalization so accepted jobs can complete without the initiating browser remaining open; includes idempotent reconciliation, lifecycle control, retry/cancel flows, admission limits, failover, observability and production release controls.
- Product surface includes Create, Library/Viewer, Activity, Settings and authorized Admin workflows, with durable media, search, collections, batch organization, continuation actions, retry/cancel, invite-only admission and production authentication/email flows.
- Verified phases include autonomous generation lifecycle, generation maintenance, creative iteration, observability/engineering quality, and a live-proved fixed 2× image-upscale capability.

**Maintenance rule:** inspect RenderLab `AGENTS.md`, `PROJECT.md`, and relevant current architecture/UI docs before using recent implementation, deployment or validation claims.

### Fares Uniform ERP
Authoritative repository: https://github.com/faresmohamed260/fares-uniform

- Designing and implementing a bilingual small-business ERP for a clothing/uniform operation, using Odoo Community as the operational core rather than creating a parallel accounting/inventory ledger.
- Scope covers finished-stock retail, offline ordinary checkout, school-uniform preorders, deposits/balances, partial collection, size-specific inventory, role/location authorization, production-demand handoff and future B2B workflows.
- Current Phase 2B server foundation has passed its hosted gate and implements/validates an Odoo-native preorder model with attributable payments, derived balances, full-balance-before-collection enforcement, partial collection semantics, idempotent stock release and server-enforced role boundaries; the phase is still incomplete and not merged/deployed.
- Project is operated with remote-only GitHub/hosted validation, explicit phase contracts, policy decisions, regression gates and documented source-of-truth conventions.

**Maintenance rule:** inspect the active branch and phase/validation docs before using current status claims. Do not describe incomplete phases as shipped production features.

### Biped Robot Control System
Authoritative repository: https://github.com/faresmohamed260/biped-robot-control-system

- Built an ESP32-based six-servo biped robot with a Python desktop control application and Streamlit diagnostics dashboard.
- Implemented automatic local-network device discovery, flash-backed pose storage/sequence playback, per-joint calibration, live Android IP camera input, color-based robot/ball tracking, video recording, and autonomous forward movement until a collision-distance threshold is reached.
- Integrated computer vision with physical robot control so detected robot/ball geometry drives autonomous motion behavior.

### VisionDeck — Computer Vision Suite
Authoritative repository: https://github.com/faresmohamed260/visiondeck-cv-suite

- Built a Streamlit computer-vision dashboard combining face detection/landmarks, real-time hand tracking and gesture recognition, and YOLO object detection.
- Added webcam and Android IP Webcam support with automatic local-network discovery, cached last-known camera addressing, live feeds, image-upload testing and project switching.
- Repository also includes a standalone custom 3-class COCO-subset object-detection assignment with YOLOv8 fine-tuning.

### DUM-E — ESP32 Robotic Arm Platform
Authoritative repository: https://github.com/faresmohamed260/DUM-E

Current verified resume evidence includes Python, C++, ESP32, Streamlit, calibration, manual control, sequence recording, controller mapping, and FK/IK-assisted pick-and-place execution.

**Maintenance rule:** inspect the DUM-E repository before using detailed or recent claims.

### ComfyUI Generative Media Workflow System

Current verified evidence includes ComfyUI, Z-Image, Qwen-Image, FLUX.2 Klein, ControlNet, LoRA, and Modal; local node graphs for reference-consistent character assets, editing, guidance, layered output, face workflows, background removal, and operationalized GPU workflows integrated with SAGA/RenderLab infrastructure.

For current implementation details or metrics, verify against the relevant project source before publishing or applying.

## Verified skills and demonstrated technologies

**Engineering:** Python, C++, FastAPI, React, Next.js, TypeScript, Streamlit, SQL, REST APIs, Docker, pytest, Git, CI/CD concepts

**AI systems:** LangGraph, LLM orchestration, tool calling, structured outputs, RAG, hybrid retrieval, prompt engineering, NLP, computer vision, evaluation/qualification workflows

**Generative media:** ComfyUI, Z-Image, Qwen-Image, FLUX.2, ControlNet, LoRA, reference conditioning, workflow automation, image/video generation pipelines

**Computer vision:** OpenCV, MediaPipe, Ultralytics YOLO, live camera pipelines, color-based tracking, gesture recognition, object detection

**Data & infrastructure:** PostgreSQL, Supabase, pgvector, SQLAlchemy, Modal, Cloudflare R2, Vercel, Docker, n8n, Odoo Community

**Reliability / platform:** idempotent job lifecycle design, server-owned reconciliation, background finalization, admission controls, retry/cancel flows, observability, release provenance, hosted CI validation

**Embedded / robotics:** Arduino, ESP32, sensors, circuits, servo calibration, pose sequencing, FK/IK-assisted motion workflows, vision-guided robot behavior

**Languages:** Arabic, English

## Leadership and certifications currently represented

- Head of AI Committee, ElCoder — led workshops on AI and machine-learning fundamentals.
- Machine Learning Specialization
- Deep Learning Specialization
- Google Cloud Big Data and Machine Learning Fundamentals

## Resume implications

The current published resume variants do not yet fully represent the verified RenderLab platform work, the stronger production/reliability evidence in SAGA, or the newer biped/VisionDeck evidence. Before the next serious application, inspect the target role and update the most relevant LaTeX resume variant if these additions materially improve fit.

Do not automatically add all of these projects to a one-page resume. Select the evidence that best supports the target role.

## Career-profile update policy

Add information only when it is verified and professionally meaningful. Prefer evidence from the relevant repository, formal document, or connected source. Do not infer a skill from a dependency or isolated experiment. Do not copy every implementation detail into this file; preserve concise, application-relevant evidence and link to authoritative project sources for depth.

When adding measurable results, preserve enough source context that they can be re-verified later.