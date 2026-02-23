# AI Sales Agent Tool Comparison

## Overview

Six tools evaluated across 11 criteria for an AI Sales Agent that qualifies inbound website leads, handles objections, collects data, and hands off to sales via HubSpot CRM.

| Tool | Score | Rank | Fit Profile |
|------|-------|------|-------------|
| **[Fin.ai](http://fin.ai) (Intercom)** | 81.9% | #3 | 3🟢 8🟡 0🟠 0🔴 |
| **Botpress** | 79.1% | #4 | 2🟢 9🟡 0🟠 0🔴 |
| **HubSpot (Breeze)** | 82.2% | #2 | 3🟢 7🟡 1🟠 0🔴 |
| **Yellow.ai** | 82.6% | #1 | 4🟢 5🟡 1🟠 1🔴 |
| **Tidio (Lyro AI)** | 72.4% | #5 | 2🟢 8🟡 1🟠 0🔴 |
| **ElevenLabs** | 68.8% | #6 | 0🟢 1🟡 5🟠 5🔴 |

---

## 1. Conversational AI

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ✓ Best AI engine (Fin AI Engine, custom LLMs) · ✓ Natural multi-turn, 45+ languages · ✓ AI-driven simulations for testing | ✓ Visual flow builder + Autonomous LLM engine · ✓ Best fit for sales qualification logic · ✓ Drag-and-drop nodes with conditional branching | ✓ Trains on HubSpot KB, blogs, 1000+ pages · ✓ CRM context available in conversations | ⭐ **STRONGEST** · ✓ Multi-LLM orchestration (15+ LLMs) · ✓ Drag-and-drop builder with dynamic workflows · ✓ Conditional logic with contextual routing | ✓ Lyro AI (Claude-powered) + Flows builder · ✓ Flows handles scripted paths, Lyro handles open-ended | 👎 **WEAKEST** · ✓ Best-in-class voice AI · ✓ Natural spoken conversation quality |
| **Weaknesses** | ✗ Support-first — sales qualification needs custom setup · ✗ No visual flow builder | ✗ Steeper learning curve than widget tools · ✗ Requires more manual configuration | ✗ AI still maturing vs Fin.ai · ✗ Less control over conversation flow logic | ✗ Requires sales call to access · ✗ Overkill for SMB volume | ✗ Less sophisticated AI than Fin.ai/Yellow.ai · ✗ No case study recommendation logic | ✗ Voice-first — text chat secondary · ✗ No visual flow builder · ✗ Weak sales qualification features |
| **FIT FOR OUR CASE** | 🟡 Can work — customize support-first AI for sales flows | 🟢 Works well — built for custom qualification logic | 🟡 Can work — accept less control over conversation branching | 🟢 Works well — but enterprise pricing is impractical | 🟡 Can work — combine Lyro + Flows to compensate for simpler AI | 🔴 Inefficient — voice-first, weak text chat qualification |

---

## 2. Knowledge / RAG

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ✓ Proprietary retrieval + reranker models · ✓ PDFs, help center, websites supported · ✓ Auto-generated Custom Answers | ✓ Strong built-in RAG with one-click indexing · ✓ RAG Safety shows data chunk sources · ✓ KB Agent auto-updates from URLs | ✓ Native HubSpot KB + 1000+ web pages · ✓ Knowledge Base Agent finds gaps automatically · ✓ Blog and PDF support | ⭐ **STRONGEST** · ✓ Agentic RAG with auto-sync (hourly/daily) · ✓ Semantic + entity-based search · ✓ Context-aware chunking with metadata | ✓ 4 source methods (URLs, Q&A, CSV, history) · ✓ Historical conversation learning (unique) · ✓ Shopify product RAG best-in-class | 👎 **WEAKEST** · ✓ Supports URLs, files, plain text for KB · ✓ Custom API actions for dynamic data |
| **Weaknesses** | ✗ No explicit source priority hierarchy · ✗ No scheduled auto-sync for KB updates | ✗ Source priority needs manual config · ✗ Less polished retrieval than Fin.ai | ✗ Limited to HubSpot ecosystem sources · ✗ KB Agent is separate product | ✗ Complex initial setup · ✗ Requires sales engagement to configure | ✗ Max 60 priority pages · ✗ No source priority hierarchy · ✗ Manual URL re-sync only | ✗ No auto-sync or scheduled refresh · ✗ Basic compared to dedicated RAG tools |
| **FIT FOR OUR CASE** | 🟡 Can work — manually maintain KB (no auto-sync) | 🟡 Can work — manually configure source priorities | 🟡 Can work — keep all content within HubSpot ecosystem | 🟢 Works well — agentic RAG with auto-sync | 🟡 Can work — stay within 60-page limit and manual re-sync | 🟠 Partial — sacrifice auto-sync and advanced retrieval |

---

## 3. Guardrails & Control

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ✓ Custom Guidance controls tone/behavior · ✓ Validation layer checks accuracy · ✓ Full audit logs, AI-driven insights | ✓ Policy Agent (YAML/JSON guardrail rules) · ✓ Brand Safety + RAG Safety framework · ✓ Human handoff via configurable triggers | ✓ Breeze Studio guardrails & brand voice · ✓ Approval flows for responses · ✓ Full HubSpot audit trail | ⭐ **STRONGEST** · ✓ SOC 2, HIPAA, GDPR, ISO certified · ✓ PII masking at data layer · ✓ Responsible AI built-in | ✓ Lyro answers ONLY from KB (anti-hallucination) · ✓ Keyword-based escalation triggers · ✓ Auto-escalation on low confidence | 👎 **WEAKEST** · ✓ System prompt controls behavior · ✓ Overrides for specific responses |
| **Weaknesses** | ✗ No dataset-driven batch testing · ✗ No native 'mark bad response' feedback loop | ✗ Requires technical setup for policies · ✗ No SOC 2/HIPAA | ✗ Less granular than Fin.ai Guidance · ✗ Guardrails still basic vs specialized tools | ✗ Premium pricing for compliance features · ✗ Complex guardrail configuration | ✗ Basic topic controls · ✗ No SOC 2/HIPAA · ✗ No batch testing | ✗ Basic guardrails only · ✗ No compliance certifications for chat · ✗ Limited escalation options |
| **FIT FOR OUR CASE** | 🟡 Can work — accept no batch testing for guardrail validation | 🟡 Can work — need technical skills for YAML/JSON policy setup | 🟡 Can work — accept basic guardrails vs specialized tools | 🟢 Works well — SOC 2, HIPAA, GDPR built-in | 🟡 Can work — rely on KB-only answers as primary guardrail | 🟠 Partial — sacrifice topic boundaries and compliance |

---

## 4. Memory & Context

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ✓ Intercom user profiles & attributes · ✓ Conversation history accessible | ✓ Bot Tables for structured data storage · ✓ Variables persist across conversation · ✓ Can store qualification scores | ⭐ **STRONGEST** · ✓ CRM IS the memory (all 5/5 scores) · ✓ Contact records persist across sessions · ✓ Lifecycle stages track qualification | ✓ User360 unified customer view · ✓ CDP integration for personalization · ✓ Cross-channel memory | ✓ Contact profiles with custom fields · ✓ Cookie-based visitor tracking · ✓ +HubSpot Workflows as memory layer — lifecycle stages + properties track qualification (free with HubSpot) | 👎 **WEAKEST** · ✓ Conversation logs via API · ✓ Can track variables in conversation |
| **Weaknesses** | ✗ Cross-session memory still on roadmap · ✗ No native funnel stage tracking | ✗ Cross-session requires custom setup · ✗ No native CRM-like memory | ✗ Tied to HubSpot — no standalone use | ✗ Full depth only on premium tiers · ✗ Requires proper CDP setup | ✗ Native cross-session AI memory limited · ✗ Relies on HubSpot for funnel tracking | ✗ No persistent user profiles · ✗ No cross-session memory · ✗ No CRM-like contact records |
| **FIT FOR OUR CASE** | 🟡 Can work — use Intercom attributes as cross-session workaround | 🟡 Can work — build cross-session logic with Bot Tables | 🟢 Works well — CRM IS the memory | 🟡 Can work — need premium tier for full User360 | 🟡 Can work — HubSpot Workflows as memory layer for funnel tracking (free) | 🔴 Inefficient — no persistent profiles or memory |

---

## 5. Website UX

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ⭐ **STRONGEST** · ✓ Intercom Messenger — best-in-class widget · ✓ Fully customizable, mobile-responsive · ✓ Supports reactive + proactive modes | ✓ Webchat widget + WhatsApp, Slack, etc. · ✓ Custom frontend possible via API · ✓ Embeddable on any page | ✓ Standard HubSpot chat widget · ✓ Mobile-responsive, branding removable · ✓ Seamless on HubSpot-hosted pages | ✓ Excellent widget: animations, custom fonts · ✓ Native mobile SDK (iOS/Android) · ✓ 35+ channels supported | ✓ Lightweight, mobile-responsive widget · ✓ Contextual flow triggers per page · ✓ Easy to install (copy-paste code) | 👎 **WEAKEST** · ✓ Embeddable voice + text widget · ✓ Custom frontend via API possible |
| **Weaknesses** | ✗ Widget-only (no inline page embed) · ✗ Intercom branding on lower tiers | ✗ Widget less polished than Intercom · ✗ More setup for advanced customization | ✗ Widget less advanced than Intercom · ✗ Limited customization options | ✗ Full customization on premium tiers only · ✗ Many options to configure | ✗ Basic widget design vs Intercom · ✗ Less branding customization | ✗ Voice-optimized, not chat-optimized · ✗ Less mature web chat UX |
| **FIT FOR OUR CASE** | 🟢 Works well — best-in-class Messenger widget | 🟡 Can work — more setup effort for polished widget | 🟡 Can work — accept limited widget customization | 🟡 Can work — need premium tier for full customization | 🟡 Can work — accept basic design vs Intercom | 🟠 Partial — sacrifice chat-optimized UX (voice-first) |

---

## 6. Integrations

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ✓ HubSpot native app exists · ✓ Slack, 450+ apps in ecosystem · ✓ +Zapier/Make: deeper HubSpot sync — auto-create contacts, log conversations ($20-70/mo) | ✓ HubSpot connector in marketplace · ✓ Slack, WhatsApp native · ✓ Zapier/Make as fallback · ✓ API-first for custom integrations | ⭐ **STRONGEST** · ✓ EVERYTHING is native HubSpot · ✓ Zero middleware needed · ✓ CRM, email, meetings, Slack, workflows | ✓ 150+ native integrations · ✓ HubSpot Sales+Service Hub supported · ✓ No middleware needed for most tools | ✓ HubSpot contact sync available · ✓ Shopify BEST-IN-CLASS · ✓ WordPress, email integrations | 👎 **WEAKEST** · ✓ API for custom connections · ✓ Make/Zapier compatible |
| **Weaknesses** | ✗ 'Fin for HubSpot' is PAUSED · ✗ Basic native sync, Zapier fills the gap · ✗ Zendesk/Salesforce prioritized natively | ✗ Some integrations need middleware · ✗ Less native depth than HubSpot/Intercom | ✗ Shallow outside HubSpot ecosystem · ✗ Limited third-party integrations | ✗ Premium tiers required for some connectors · ✗ May need sales team to enable | ✗ Slack only via Zapier · ✗ Less native integration depth | ✗ No native HubSpot integration · ✗ No native Slack · ✗ Must build all integrations |
| **FIT FOR OUR CASE** | 🟡 Can work — Zapier/Make bridges HubSpot gap ($20-70/mo) | 🟡 Can work — use Zapier for some connections | 🟢 Works well — everything native HubSpot | 🟡 Can work — need premium tier for some connectors | 🟡 Can work — need Zapier for Slack and deeper integrations | 🔴 Inefficient — no native HubSpot or Slack |

---

## 7. Analytics

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ✓ AI-powered Insights dashboard · ✓ CX Score (5x more than CSAT) · ✓ Topics Explorer auto-groups conversations · ✓ Resolution rate tracking | ✓ Conversation analytics + event debugger · ✓ See AI decision logic step-by-step · ✓ Flow drop-off tracking | ✓ Native HubSpot reporting · ✓ Lifecycle stage transitions · ✓ Deal creation tracking · ✓ ROI attribution possible | ⭐ **STRONGEST** · ✓ AI topic clusters + sentiment analysis · ✓ Custom dashboards · ✓ AI vs human performance comparison | ✓ Visitor tracking, basic analytics · ✓ Unanswered Questions log (valuable) · ✓ Lyro performance dashboard | 👎 **WEAKEST** · ✓ Conversation logs and transcripts · ✓ Usage analytics via API |
| **Weaknesses** | ✗ Qualification-specific analytics limited · ✗ Custom reporting needs Advanced plan | ✗ AI reasoning hidden in production mode · ✗ Less polished dashboard than Fin.ai | ✗ AI-specific analytics still basic · ✗ Topic clustering not available | ✗ Full analytics on premium tiers · ✗ Complex to set up custom reports | ✗ No topic clustering · ✗ No AI-powered insights · ✗ Basic compared to leaders | ✗ No real-time monitoring UI · ✗ No inbox experience · ✗ Post-conversation review only |
| **FIT FOR OUR CASE** | 🟡 Can work — need Advanced plan for custom reporting | 🟡 Can work — accept less polished dashboard | 🟡 Can work — accept basic AI-specific analytics | 🟢 Works well — AI topic clusters + sentiment | 🟡 Can work — supplement with manual Unanswered Questions analysis | 🔴 Inefficient — no real-time monitoring, API-only |

---

## 8. Operational

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ✓ 14-day free trial (unlimited resolutions) · ✓ Setup in under 1 hour · ✓ Excellent documentation · ✓ Mature platform (10+ years) | ✓ Free tier to start prototyping · ✓ Large community, good docs · ✓ Open-source roots give transparency | ✓ No new platform — native HubSpot · ✓ Team already knows the UI · ✓ Good documentation | ✓ Free plan (100 MTU, 5K convos) · ✓ Best documentation depth · ✓ Dedicated support team | ⭐ **STRONGEST** · ✓ Setup in minutes — easiest in matrix · ✓ Visual Flows + Lyro combo · ✓ Best for non-technical users · ✓ Good onboarding tutorials | 👎 **WEAKEST** · ✓ Free tier to experiment · ✓ Unique voice AI capability |
| **Weaknesses** | ✗ Intercom platform adds complexity · ✗ Support-first — needs sales customization | ✗ Steeper learning curve · ✗ 1-2 weeks to working prototype · ✗ AI Spend can be unpredictable | ✗ Credit system still unpredictable · ✗ AI features still evolving · ✗ Breeze Agent is newest product | ✗ Must call sales — no self-serve · ✗ Months-long implementation · ✗ Sales cycle is slow | ✗ AI less sophisticated than top tier · ✗ Add-on pricing can be confusing · ✗ May outgrow it at scale | ✗ Voice setup more complex than chat · ✗ Limited non-voice documentation · ✗ Small chatbot community |
| **FIT FOR OUR CASE** | 🟡 Can work — manage two platforms (Intercom + HubSpot) | 🟡 Can work — need 1-2 weeks and technical skills | 🟡 Can work — accept evolving AI and credit unpredictability | 🟠 Partial — sacrifice quick setup (months-long sales cycle) | 🟢 Works well — easiest setup, best for non-technical | 🟠 Partial — sacrifice chat docs and community support |

---

## 9. Testing

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ⭐ **STRONGEST** · ✓ Batch testing (50+ questions at once) · ✓ AI simulations before going live · ✓ Rate answers Good/Acceptable/Poor · ✓ Recommendations to fix issues | ✓ Real-time emulator · ✓ Event debugger (AI logic step-by-step) · ✓ Can test in sandbox · ✓ +Langfuse: adds batch eval, LLM-as-judge, trace observability (free or $29/mo) | ✓ Preview mode — free, no credits used · ✓ Response review before publishing · ✓ HubSpot workflow testing | ✓ Auto-generates test cases from docs · ✓ Simulates scenarios + edge cases · ✓ AI Copilot for debugging | ✓ Playground for testing before live · ✓ Unanswered Questions log for gap analysis | 👎 **WEAKEST** · ✓ Dashboard conversation review |
| **Weaknesses** | ✗ Live testing charges per resolution · ✗ No A/B testing of flows | ✗ No native batch testing (Langfuse fills this gap) · ✗ No A/B testing | ✗ No batch testing · ✗ No A/B testing · ✗ Basic preview only | ✗ Only available on premium tiers · ✗ Complex setup for full testing | ✗ No batch testing · ✗ No A/B testing · ✗ No dataset-driven evaluation | ✗ Minimal testing infrastructure · ✗ No simulation or sandbox |
| **FIT FOR OUR CASE** | 🟢 Works well — batch testing + AI simulations | 🟢 Works well — native emulator + Langfuse adds batch eval ($0-29/mo) | 🟡 Can work — accept basic preview-only testing | 🟡 Can work — need premium access for full test suite | 🟠 Partial — sacrifice batch testing and dataset evaluation | 🔴 Inefficient — minimal testing tools |

---

## 10. Cost

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ✓ $0.99/resolution, LLM costs included · ✓ $29/mo platform + resolution fees · ✓ Hard spending caps prevent surprises | ✓ Most cost-effective AI chatbot · ✓ Free tier for prototyping · ✓ ~$150-250/mo at 500 leads | 👎 **WEAKEST** · ✓ LLM included in credit pricing · ✓ No separate AI billing line item | ✓ Free plan exists (limited volume) | ⭐ **STRONGEST** · ✓ ~$200/mo at 500 leads · ✓ Cheapest full-featured chatbot · ✓ 50 free Lyro conversations/month | ✓ Free tier for initial testing |
| **Weaknesses** | ✗ $280-530/mo at 500 leads · ✗ $530-1,020/mo at 1,000 leads · ✗ Costs scale linearly with volume | ✗ AI Spend adds to base plan · ✗ LLM costs variable month-to-month · ✗ Hard to predict exact monthly total | ✗ ~€570/mo at 500 leads (priciest) · ✗ Credit consumption unpredictable · ✗ Must buy Service Hub Pro minimum | ✗ No public pricing available · ✗ Contracts negotiated per deal · ✗ Estimated $1,000+/mo minimum | ✗ Add-on tier pricing can confuse · ✗ Scales less predictably past 1,000 | ✗ ~$200-400/mo at 500 leads · ✗ Voice features cost extra · ✗ Less transparent than chat-only tools |
| **FIT FOR OUR CASE** | 🟡 Can work — budget for linear scaling at 1,000+ leads | 🟡 Can work — monitor variable AI spend monthly | 🟠 Partial — sacrifice budget efficiency (most expensive) | 🔴 Inefficient — enterprise pricing, $1,000+/mo minimum | 🟢 Works well — best value full-featured chatbot | 🟡 Can work — accept voice premium pricing |

---

## 11. Market

| | Fin.ai (Intercom) | Botpress | HubSpot (Breeze) | Yellow.ai | Tidio (Lyro AI) | ElevenLabs |
|---|---|---|---|---|---|---|
| **Strengths** | ✓ G2 4.5/5 (3,500+ reviews) · ✓ 650K+ websites · ✓ 40+ person AI team · ✓ Market leader in AI support | ✓ 750K+ agents built · ✓ $40M funding, Series B 2025 · ✓ Clients: Kia, EA, Shell · ✓ Large open-source community | ⭐ **STRONGEST** · ✓ NYSE-listed, $2B+ revenue · ✓ Unmatched company stability · ✓ Largest ecosystem in CRM | ✓ Gartner 2025 Challenger · ✓ $102M+ raised · ✓ 1,100+ enterprise customers | ✓ 300K+ websites · ✓ G2 4.5/5, Capterra 4.7/5 · ✓ Founded 2013, mature & profitable | 👎 **WEAKEST** · ✓ Leader in AI voice technology · ✓ $125M+ funding · ✓ Iconic brand in AI audio |
| **Weaknesses** | ✗ Primarily support tool, not sales · ✗ Expensive at scale | ✗ Smaller than Intercom/HubSpot · ✗ Less mainstream recognition | ✗ AI agent is newest product · ✗ Fewer AI-specific reviews | ✗ SMB-unfriendly positioning · ✗ Less community content than leaders | ✗ Smaller than Intercom · ✗ Less AI-specific reputation | ✗ New to chatbot space · ✗ Small user base for chat use case |
| **FIT FOR OUR CASE** | 🟢 Works well — market leader, 3,500+ reviews | 🟡 Can work — accept smaller ecosystem than leaders | 🟢 Works well — NYSE-listed, $2B+ revenue | 🟡 Can work — accept enterprise-focused community | 🟡 Can work — accept smaller AI-specific reputation | 🟠 Partial — sacrifice chatbot community (voice-focused) |

---

## Verdict

| Tool | Verdict | Best For | Key Risk | Fit Profile |
|------|---------|----------|----------|-------------|
| **Fin.ai (Intercom)** | **Best AI brain** | Teams who prioritize AI quality and testing, and can manage Intercom + Zapier alongside HubSpot | Two platforms to manage (Intercom + HubSpot). $29/mo platform + $0.99/resolution + $20-70/mo Zapier | 3🟢 8🟡 0🟠 0🔴 |
| **Botpress** | **Most flexible builder for sales qualification** | Technical teams who want full control over qualification logic, flows, and data routing to HubSpot | Steeper learning curve, 1-2 weeks to prototype. AI spend can be unpredictable | 2🟢 9🟡 0🟠 0🔴 |
| **HubSpot (Breeze)** | **Zero-friction CRM integration, premium price** | HubSpot-committed teams who value native integration over AI sophistication and don't mind paying more | Most expensive option (~€570/mo). AI is still maturing. Credit system unpredictable | 3🟢 7🟡 1🟠 0🔴 |
| **Yellow.ai** | **Best overall capabilities, wrong price tier** | Enterprise teams with $1,000+/mo budget and patience for months-long implementation | No self-serve. Months-long sales cycle. Enterprise pricing kills SMB viability | 4🟢 5🟡 1🟠 1🔴 |
| **Tidio (Lyro AI)** | **Fastest to launch, best value** | Non-technical teams who need a working chatbot this week at lowest cost, using HubSpot as the memory/CRM layer | AI less sophisticated. May outgrow it at scale. Testing remains limited (no Langfuse option) | 2🟢 8🟡 1🟠 0🔴 |
| **ElevenLabs** | **Wrong tool for this job** | Teams who need voice-first AI (phone support, voice assistants) — not text-based web chat | No native HubSpot. No persistent memory. Minimal testing. Voice-first architecture mismatched to text chat use case | 0🟢 1🟡 5🟠 5🔴 |

---

## Tools Evaluated & Ruled Out (not scored)

*Agent.ai (marketplace, not chatbot) • Make.com (workflow automation, not chatbot) • Ada.cx (enterprise pricing $30K+/yr) • Salesforce Agentforce (requires Salesforce CRM, $2K+/mo) • Reply.io (outbound sales, not inbound chat) • Appy Pie (too shallow) • Conversica (enterprise $1.5K+/mo, outbound-focused) • Crisp (too basic for AI qualification) • Latitude (developer framework, not chatbot)*

---

## Legend

| Symbol | Meaning |
|--------|---------|
| ⭐ **STRONGEST** | Best in category |
| 👎 **WEAKEST** | Worst in category |
| 🟢 Works well | 90%+ match |
| 🟡 Can work out | 70-89% match |
| 🟠 Partial fit | 50-69% match |
| 🔴 Inefficient | <50% match |
