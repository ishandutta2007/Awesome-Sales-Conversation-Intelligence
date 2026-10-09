# Awesome-Sales-Conversation-Intelligence

# Top Sales Conversation Intelligence Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Call Transcription, Talk Analytics & Self-Hosted Revenue Intelligence*  
**Last updated: October 2026**

This repository tracks notable **commercial sales conversation intelligence platforms** and **open-source projects** that record, transcribe, and analyze sales calls to extract buyer insights, coach reps, and improve win rates — from enterprise revenue intelligence suites to self-hosted call analytics engines.

**Examples** include Salesforce Conversation Intelligence, Gong, Chorus by ZoomInfo, Clari Copilot, Salesloft Conversations, Outreach Kaia, Balto, Jiminny, Attention, and Avoma (the category leaders).

**Open-source emphasis**: Sales conversation intelligence is a rapidly growing open-source domain. **CallSense** leads with explainable lead scoring where every score component shows the exact transcript quote behind it . **GTM Superintelligence** from Attention brings 30 post-call agents with three-layer scoring (call/deal/account) grounded in MEDDPICC and SPICED methodologies . **CXMind** delivers real-time VoIP analytics with non-invasive HEP tapping and AI agent-assist Chrome extension . **Polyphon AI** provides 100% offline transcription and diarization with neural speaker separation . **Vezir** offers self-hosted team intelligence with confidential TEE-based summarization presets . **Playcall** provides open-source Gong alternative with buyer-aware scoring and custom playbook frameworks . **OpenClaw Talk Analyzer** delivers multi-source business conversation analysis . **CallHarness SDK** enables voice AI agent call analytics . **MOSS-Transcribe-Diarize** brings state-of-the-art long-form speaker-aware transcription supporting 50+ languages and 90-minute recordings . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Gong](https://www.gong.io/)**  
  **The conversation intelligence market leader** — call recording, transcription, deal risk detection, and AI-powered coaching insights. **Best for enterprise revenue teams** .

- **[Chorus by ZoomInfo](https://www.zoominfo.com/)**  
  **Conversation intelligence with ZoomInfo data** — call analytics, coaching, and CRM integration. **Best for ZoomInfo customers** .

- **[Clari Copilot](https://www.clari.com/)**  
  **Revenue intelligence with conversation analytics** — deal inspection, forecast accuracy, and coaching. **Best for revenue operations teams** .

- **[Salesloft Conversations](https://www.salesloft.com/)**  
  **Conversation intelligence within Salesloft** — call recording, transcription, and coaching. **Best for Salesloft users** .

- **[Outreach Kaia](https://www.outreach.io/)**  
  **Real-time conversation intelligence** — live call coaching, objection handling, and meeting insights. **Best for Outreach users** .

- **[Balto](https://www.balto.ai/)**  
  **Real-time AI call coaching** — live guidance for agents during calls with automated QA. **Best for contact centers** .

- **[Jiminny](https://www.jiminny.com/)**  
  **Conversation intelligence and coaching** — call recording, transcription, and revenue intelligence. **Best for mid-market sales teams** .

- **[Attention](https://www.attention.tech/)**  
  **AI-powered sales coaching and deal intelligence** — call analysis, CRM auto-fill, and 30 post-call agents. **Best for modern sales organizations** .

- **[Avoma](https://www.avoma.com/)**  
  **AI meeting assistant with conversation intelligence** — transcription, note-taking, and coaching. **Best for teams wanting meeting + revenue intelligence** .

- **[Salesforce Conversation Intelligence](https://www.salesforce.com/)**  
  **Salesforce's native conversation intelligence** — call recording, transcription, and Einstein insights. **Best for Salesforce customers** .

## Open-Source GitHub Projects

### Full Conversation Intelligence Platforms

- **[CallSense (ML-voice-lead-analysis)](https://github.com/aaron-seq/ML-voice-lead-analysis)**  
  **Self-hosted alternative to conversation-intelligence tools**, MIT licensed . **Explainable lead scoring** — 0-100 score with every weighted component shown, plus the transcript quote behind each one . **Objection detection** — 7 objection types flagged as addressed or unaddressed with playbook guidance . **Buyer intent signals** — 10 signal types mapped to BANT/MEDDIC, attributed to who said it . **Call outcome classification** — meeting booked, follow-up agreed, not interested, gatekeeper-only . **Next-best-action** — prioritised, time-boxed, with the reason it was suggested . **Deal risk flags** — no decision maker, no next step, budget unconfirmed, rep monologue, cooling sentiment . **Conversation metrics** — talk ratio, question counts, sentiment trajectory . **Pipeline analytics** — band distribution, recurring objections, team-wide coaching signals . **Requirements**: Python 3.11+, no GPU required . **Best for explainable, self-hosted lead scoring and coaching** .

- **[GTM Superintelligence (Attention)](https://github.com/attentiontech/gtm-superintelligence)**  
  **Open-source GTM intelligence and automation for any sales call**, open-source . **Three-layer scoring**: Call (coaching), Deal (MEDDPICC/SPICED-grounded win-likelihood + slip risk), Account (CSM adoption, value, churn risk) . **30 post-call agents** in categories including coaching, deal scoring, CRM sync, and account health . **Coaching inbox** — prioritized "what to improve" digest aggregated from many call reports, deterministic prioritization (frequency × impact) . **CRM auto-fill** — push call data to any CRM (Salesforce, etc.) with configurable field mapping . **Claude Code skill + subagents + slash commands** — run coaching by talking to Claude without API key . **CLI**: `gtmsi coach`, `gtmsi deal`, `gtmsi account`, `gtmsi inbox`, `gtmsi crm` . **Any recorder, any CRM** . **Best for teams wanting coaching + deal + account scoring in one framework** .

- **[CXMind](https://github.com/Sonicwell/cxmind)**  
  **Open-source real-time VoIP analytics platform with AI-powered call monitoring**, BSL 1.1 licensed (converts to Apache 2.0 on 2030-02-22) . **Non-invasive HEP tapping** — deploy alongside existing PBX with zero changes to telephony infrastructure . **Real-time call analytics** — SIP/RTP packet processing with 300+ concurrent calls on 4-core/8GB instance . **AI agent-assist Chrome extension** for live call coaching . **Admin UI** with real-time dashboards and contact center management . **Privacy-first** — Edge PCI-DSS DTMF masking with App Server PII sanitization . **Components**: Ingestion Engine (Go), Sniffer (Go), PCAP Simulator (Go), Admin UI (React), Copilot Extension (React) . **Best for contact centers wanting non-invasive real-time VoIP analytics** .

### Transcription & Diarization Engines

- **[Polyphon AI](https://pypi.org/project/polyphon-ai/)**  
  **100% offline and private transcription and diarization**, open-source . **Real-Time Streaming & Neural Diarization** — low-latency live streaming speech recognition with NVIDIA NeMo Sortformer end-to-end neural diarization . **Clean Verbatim Mode** — intelligently detects and filters vocal disfluencies with zero millisecond timing impact . **Local LLMs via llama.cpp, Ollama, or vLLM** — outputs actionable summaries, decisions, and speaker talk-time metrics . **Zero telemetry, no cloud API dependencies, no remote data leakage** — ideal for confidential meetings, medical/legal notes, and homelab setups . **Polyphon Studio** — 4-tab web workspace with synchronized media playback and word-level karaoke glow . **Best for privacy-critical transcription and diarization** .

- **[MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)**  
  **Open-source speech transcription and diarization model from OpenMOSS team**, Apache-2.0 licensed . **Unified modeling** over long-form, multi-speaker audio supporting ASR, speaker-aware transcription, speaker diarization, timestamp prediction, and compact transcript generation . **Single-pass inference** on audio recordings up to 90 minutes long . **50+ languages supported** . **Won first place in the 2nd MLC-SLM Challenge at INTERSPEECH 2026** spanning 14 languages . **Model architecture**: Whisper-style audio encoder + Qwen3-0.6B style decoder . **Output format**: Compact `[start][Sxx]text[end]` transcript . **Best for state-of-the-art long-form multi-speaker transcription** .

- **[Vezir](https://pypi.org/project/vezir/)**  
  **Self-hosted team intelligence platform for meeting transcription and analysis**, open-source . **Three summarization presets**: high-quality (Claude Sonnet), confidential (TEE-hosted model with hardware-attested enclave — prompts not visible to provider), and alternative (Kimi, cheapest) . **Privacy toggles per upload** — auto_label, sync, personal . **Server-side kill switches**: VEZIR_SKIP_SYNC=1, VEZIR_DELETE_AUDIO=1 . **Team sharing without git** — `vezir pull` downloads artifacts for meetings others recorded . **Android and desktop clients** . **Best for teams wanting confidential, self-hosted meeting intelligence** .

### Specialized Call Analytics

- **[Playcall](https://softrankings.com/products/playcall)**  
  **Open-source AI call intelligence replacing Gong**, MIT licensed . **Scores calls against your playbook** and buyer context including account, contact, and deal stage . **Identifies rep adherence** to playbook, loss reasons, and objection patterns . **Buyer-aware scoring** based on company stage, contact role, and deal context . **Supports MEDDPICC, BANT, SPIN, or custom frameworks** . **Integrates with OpenAI, Anthropic, Gemini, Mistral, Groq, Cohere, Perplexity, Together AI** . **Deploys in minutes on Vercel and Supabase** . **Best for teams wanting playbook-based call scoring** .

- **[OpenClaw Talk Analyzer](https://github.com/ZhenRobotics/openclaw-talk-analyzer)**  
  **AI-powered business conversation analysis**, open-source . **Multi-source analysis** — audio transcripts, chat logs, meeting recordings . **AI-powered insights** — Claude, GPT, or local LLMs . **Sentiment analysis** — emotional tone and engagement levels . **Action items extraction** — tasks, decisions, and commitments . **Speaker profiling** — individual speaking patterns and contribution metrics . **Strategy recommendations** — data-driven follow-up suggestions . **Export reports** — JSON, Markdown, or PDF . **Analysis types**: Meeting Summary, Sales Call, Customer Support, Negotiation Strategy, Team Dynamics, Sentiment Tracking . **Best for multi-source conversation analysis** .

- **[CallHarness SDK](https://pypi.org/project/callharness-sdk/)**  
  **Open-source call analytics for voice AI agents**, open-source . **Post-call LLM analysis** — summary, sentiment, outcome, why a call transferred or didn't complete . **Self-hosted** — transcripts stay on your own infrastructure . **Pipecat integration** — observers capture transcript turns, STT/LLM/TTS latency, interruptions, tool calls, transfers, and deterministic end_reason . **Direct ingestion** via REST API for LiveKit, custom stacks, or any pipeline . **Dashboard** shows analyzed calls . **Best for voice AI agent call analytics** .

- **[nightcall](https://pkg.go.dev/github.com/nightnoryu/nightcall)**  
  **Service for transcribing and analyzing phone calls using OpenAI Whisper and Llama**, open-source . **Automates call evaluation QA** — partially automates the work of the call evaluation QA manager who listens to recordings and evaluates sales manager performance . **Purpose**: For companies that drive sales through phone calls . **Best for automated phone call QA** .

- **[django-twilio-call](https://pypi.org/project/django-twilio-call/)**  
  **Enterprise-grade Django package for building call center applications with Twilio**, open-source . **Core functionality**: inbound/outbound calls, intelligent routing, agent management, queue management, call recording with transcription support, IVR system, real-time monitoring . **Enterprise features**: JWT authentication, rate limiting, RBAC, analytics, WebSocket support, webhook handling, Celery integration . **Production ready**: Docker, Kubernetes, Prometheus metrics . **Best for building custom call centers with Twilio** .

- **[OpDesk](https://github.com/Ibrahimgamal99/OpDesk)**  
  **Modern, real-time operator panel for Asterisk PBX systems**, open-source . **Analytics** — 12 KPI cards with period-over-period deltas, per-queue and per-agent breakdowns, 7×24 heatmap, call-level drilldown with CSV/XLSX export . **CRM integration** — push call data to any CRM with configurable field mapping . **Call recording + VAD** — full-call recording via MixMonitor with automatic post-call talk/silence analysis (Silero VAD) . **Multi-language UI** — English, Arabic (RTL), Spanish, Portuguese . **Best for Asterisk/FreePBX operators wanting real-time call analytics** .

### Additional Strong Open-Source Options

- **AI Sales Brain (top_ai_sales)** — Conversational AI sales assistant with real-time objection handling, meeting preparation, and self-evolving knowledge base (Chinese language) .
- **Redix AI** — Open-source, lightweight sales call assistant with real-time coaching, battlecards, buying signal detection, and autonomous task automation in undetectable invisible mode .
- **p3x-meet-assistant** — Live meeting transcription with OpenAI GPT-4o Transcribe, GPU speaker diarization, and 10-language support .
- **vezir** — Self-hosted team intelligence with TEE-based confidential summarization .
- **Genesys Cloud MCP Plus** — Model Context Protocol server for contact center analytics, real-time monitoring, and conversation analysis with 15 tools .
- **converse-copilot** — Live call copilot with MEDDPICC coverage rail, bridging-question cards, and post-call AI debrief .

**Frameworks for building custom sales conversation intelligence solutions**: Combine **CallSense** for explainable lead scoring and objection detection . Use **GTM Superintelligence** for three-layer scoring (call/deal/account) with 30 post-call agents . Deploy **CXMind** for non-invasive real-time VoIP analytics with AI agent-assist . Integrate **Polyphon AI** or **MOSS-Transcribe-Diarize** for private, high-accuracy transcription and diarization . Choose **Vezir** for confidential team intelligence with TEE-based summarization . Use **Playcall** for playbook-based call scoring with custom frameworks . Note that true enterprise conversation intelligence with real-time AI coaching, automated CRM sync at scale, and vendor-supported SLAs (Gong, Chorus, Clari Copilot) remains primarily commercial territory; open-source stacks provide strong transcription, diarization, scoring, and coaching foundations that require integration for complete revenue intelligence.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Sales conversation intelligence platforms handle sensitive customer conversations and may process PII. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA).
- **Call recording consent laws vary by jurisdiction** — two-party consent states (California, Illinois, etc.) require explicit consent before recording. Ensure compliance before deployment .
- **Transcription accuracy depends on audio quality** — background noise, accents, and cross-talk degrade results. Commercial platforms often provide better real-world accuracy than open-source models .
- **Explainability builds trust** — CallSense's design constraint is that "a score a rep cannot interrogate is a score they will ignore the first time it disagrees with them" . Prioritize tools that show evidence behind scores .
- **License considerations**: CallSense is MIT , GTM Superintelligence is open-source , CXMind uses BSL 1.1 (converts to Apache 2.0 on 2030-02-22) , Polyphon AI is open-source , MOSS-Transcribe-Diarize uses Apache-2.0 , Playcall is MIT , and CallHarness SDK is open-source . Verify licensing against your use case before committing.
- The open-source ecosystem provides strong transcription, diarization, scoring, and coaching foundations, but **real-time AI coaching, automated CRM sync at scale, and vendor-supported SLAs** remain primarily commercial offerings.
