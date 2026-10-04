# Career Profile

Last reviewed: 2026-10-04

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

- Building a web-first, invite-only narrative-intelligence platform that reverse-engineers books and series into evidence-linked characters, dialogue, events, relationships, state, time and later canon-aware retrieval/generation.
- Active v2 architecture uses private source ingestion, durable jobs/leases/runs, Supabase/Postgres control-plane state, Backblaze B2 object storage, owner-scoped access and outbound-only local analysis workers.
- Designed a subscription-free textual-analysis strategy: deterministic structure first, lightweight local literary NLP second, specialized local models for ambiguity and bounded local generative reasoning only when evidence still requires judgment.
- Current measured evidence includes deterministic quote detection at 0.8563 F1, a BookNLP event-trigger challenger at 0.7791 F1, strict participant/qualifier/relationship/timeline/life-state candidate contracts and persistent BookNLP stdio execution with exact semantic equality and lower repeated-run latency.
- The project has a production-domain closed-beta surface, but the v2 product is not yet operational end to end: required application APIs and additional qualification tests remain incomplete. Do not present experimental challengers as adopted production defaults or historical v1 capabilities as current v2 implementation.

**Maintenance rule:** inspect the SAGA repository, active phase contract and recent merged/open PRs before using detailed claims. The project repository outranks this summary for current implementation facts and metrics.

### RenderLab — AI Image/Video Creation Platform
Authoritative repository: https://github.com/faresmohamed260/renderlab
Production domain: https://renderlab.faresuniform.uk

- Built a production-domain, invite-only AI image/video creation workspace over cloud-hosted ComfyUI/Modal workers while hiding workflow/provider complexity behind product-level contracts.
- Next.js/React/TypeScript application spans Create, Library/Viewer, Activity, Settings and fresh-authorized Admin surfaces; infrastructure uses Supabase, PostgreSQL/RLS, Cloudflare R2 and Vercel.
- Implemented browser-independent generation reconciliation and durable finalization, retry/cancel/run-again flows, admission limits, failover, sanitized failures, durable uploads/media organization and continuation actions.
- Delivered closed-beta identity/admission, branded transactional email, profile/preferences, password/session controls, MFA, secure email change, data export/deletion and operator observability with owner-scoped authorization.
- Production qualification uses exact-head CI, real browser journeys, fixture cleanup/non-interference, release manifests, explicit custom-domain cutover and rollback anchors.
- Draft PR #313 proposes MiniMax H3 video support but is blocked on Modal payment/spend limits; it is not merged, deployed or a current production capability.

**Maintenance rule:** inspect RenderLab AGENTS.md, PROJECT.md, architecture/UI docs and recent PRs before using implementation, deployment or validation claims.

### Fares Uniform — Experimental ERP and Public Website
Authoritative repository: https://github.com/faresmohamed260/fares-uniform
Current public staging: https://fares-uniform.vercel.app

- Building an experimental bilingual system for a real family uniform business, with two independent delivery tracks: an Odoo Community operational ERP and a Next.js public catalog/showcase.
- ERP scope covers finished-stock variants/sizes, offline POS, school-uniform preorders, deposits/balances, partial collection, returns/exchanges, production-demand handoff, business-client orders, roles/locations and operational reporting.
- Phases 0–8 are integrated; isolated staging Gate C is accepted with 149 Odoo tests, repeatable seven-addon upgrades, 8/8 public browser journeys, real POS-sync UAT, session/attachment continuity, WebSocket replay, cron locking, backup/restore and scheduled observability.
- Public-site Phase 10 is active on draft PR #8 with engineering-green V2 content/API, R2 publication, contextual enquiry, canonical EN/AR routes, accessibility/reduced-motion, SEO/cache resilience and protected visual-review previews.
- ERP production, public-site cutover, real-client publication and migration of real business data remain separately gated and NO-GO. Do not present the experimental system as a released SaaS product.

**Maintenance rule:** inspect the active branch, PROJECT.md, PROJECT_TRACKS.md, phase/validation docs and recent PRs. Keep public-site and ERP progress separate.

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

- Public resume variants should say **ranked first / top of class** but omit the numerical CGPA.
- All current role-specific variants should include SAGA, RenderLab and Fares Uniform with emphasis appropriate to the target role.
- Present RenderLab as a production-domain closed beta; present SAGA v2 as an advanced but incomplete rebuild; present Fares Uniform as an experimental family-business system with separate ERP and public-site tracks.
- Do not promote draft, blocked, experimental or unmerged capabilities to shipped production work.
- Inspect the target role and the authoritative repositories before every serious application.

Do not automatically add all of these projects to a one-page resume. Select the evidence that best supports the target role.

## Career-profile update policy

Add information only when it is verified and professionally meaningful. Prefer evidence from the relevant repository, formal document, or connected source. Do not infer a skill from a dependency or isolated experiment. Do not copy every implementation detail into this file; preserve concise, application-relevant evidence and link to authoritative project sources for depth.

When adding measurable results, preserve enough source context that they can be re-verified later.