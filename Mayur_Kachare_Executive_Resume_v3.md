MAYUR KACHARE

Director - Application Operations - T-Systems ICT India Pvt Ltd

Pune | +91 98224 93683 | email: mayurkachare@gmail.com | LinkedIn: https://www.linkedin.com/in/mayurkachare

PROFILE SUMMARY

Technology and business leader with 22+ years of experience across Travel & Transportation, Industrial, Pharmaceuticals, Public Sector, Manufacturing and Automobile. 14+ years of hands-on SAP Basis R/3, NetWeaver and HANA technical experience alongside 14+ years leading large-scale global SAP delivery organisations. Currently Director - Application Operations - T-Systems ICT India Pvt Ltd at T-Systems ICT India, building and scaling offshore delivery centres, transitioning complex SAP services from onshore / nearshore to offshore, and driving operational excellence through automation, workforce optimisation, and cloud transformation. Proven expertise in SAP S/4HANA, RISE with SAP, portfolio governance, customer success, and executive stakeholder management. Managed SAP portfolios worth € 8-10M annually. Improved operational efficiency by 40% through automation, efficiency and offshoring.

CORE COMPETENCIES

SAP Application Operations • End-to-End SAP Application Lifecycle Management • Global Delivery & Offshoring Strategy • Global Portfolio Business Unit Enablement • RISE with SAP Transformation • SAP S/4HANA Transformation • Enterprise Digital Transformation • Program & Portfolio Management • Operating Model Transformation • Strategic Delivery Leadership • Operational Excellence • Automation, AI & Observability • Workforce, FTE & Pyramid Optimization • Financial & Cost Optimization • Customer Success • Executive Stakeholder Management

ONLINE PORTFOLIO

  mayur-kachare.github.io/portfolio/

PROFESSIONAL EXPERIENCE

Director - Application Operations - T-Systems ICT India Pvt Ltd | T-Systems ICT India Pvt. Ltd. | Jun 2019 – Present
As Director - Application Operations - T-Systems ICT India Pvt Ltd, I lead strategic delivery and operations for large global SAP Application Operations portfolios, managing teams of over 100+ professionals across 5 countries in SAP Basis, Application Operations, Infrastructure, and Managed Services. I provide executive leadership for multiple SAP programs, driving operational excellence, customer success, business transformation, and continuous service improvement across complex enterprise SAP landscapes.

Key Responsibilities & Achievements
- Own AOP, budget forecasting, and financial performance for SAP operations portfolios (€8–10M annually); contribute to IT strategy development, technology roadmaps, and capital planning for enterprise SAP / IT operations
- Direct people development, performance reviews, and workforce pyramid optimization across 100+ global delivery team; lead coaching, onboarding, and talent retention initiatives
- Define delivery KPIs, operational governance models, service improvement initiatives, and executive reporting for SAP Application Operations
- Lead end-to-end SAP Application Operations for global enterprise customers, ensuring operational stability, governance, service quality, and business continuity.
- Successfully delivered and governed multiple SAP transformation, migration, implementation, and modernization initiatives across large SAP landscapes, including SAP S/4HANA adoption and cloud transformation programs.
- Manage cross-functional global delivery teams consisting of 100+ resources across support, development, project delivery, platform operations, and managed services.
- Own portfolio governance including delivery strategy, financial management, forecasting, resource planning, capacity management, risk management, compliance, band mix and pyramid correction, driving efficiency with automation and observability and achieve FTE optimization and customer satisfaction.
- Define delivery KPIs, operational governance models, service improvement initiatives, automation roadmap, and executive reporting for SAP Application Operations.
- Partner with executive leadership, global customers, and senior stakeholders across multiple geographies, influencing strategic technology decisions and long-term transformation roadmaps.
- Drive organizational transformation through offshore delivery expansion, operating model optimization, automation, standardization, and continuous process improvements.
- Collaborated with consulting partners, including McKinsey, on organizational optimization, workforce planning, and cost reduction initiatives.
- Established and scaled offshore SAP operations supporting global customers while improving delivery efficiency, service quality, and operational resilience.
- Lead large-scale SAP infrastructure modernization, cloud migration, platform transformation, disaster recovery readiness, operating system upgrades, and application transition programs.
- Govern vendor management, commercial discussions, budgeting, financial performance, and delivery excellence across strategic customer engagements.
- Work effectively within highly matrixed global organizations, collaborating with senior leadership across business, technology, operations, infrastructure, security, and architecture teams.
- Champion continuous improvement, automation, AI-driven operational efficiencies, knowledge management, and service innovation to improve customer experience and operational performance.
- Onboarded a new customer (oil & gas) for SAP basis operations, scaling a 35+ resource team in India — greenfield delivery build, governance, and 24×7 run.
- Onboarded a monitoring project from Malaysia to India with a 10-person graduate-hire team, including knowledge transfer, runbook design, and SLA stand-up.

AI / GEN-AI EXPERIENCE

Hands-on production deployment of AI agents and LLM-powered automation for personal and SAP-adjacent workflows. Practical experience spans:

- Agentic AI orchestration — designed and operated a multi-profile AI agent stack (Hermes by Nous Research) running 7 specialised workstream profiles (master-orchestrator, IT-service, impex, social, blood-bank, personal, trading-watch) over Telegram and Discord. Profiles route memos via classification rules, maintain isolated contexts, and stay read-only on regulated workflows (no broker connections, no SMS broadcast, no message sends to external contacts).
- Tool-using LLM agents — wired TradingView webhook → signed HMAC verification → SQLite paper-trade ledger → live P&L dashboard. Designed a four-pillar support/resistance framework in Pine Script v6 (5 scripts) that backtests a market-neutral, risk-managed BTST strategy. Cron-driven morning briefings fetch live Nifty/Tier-1 LTP from Yahoo Finance and deliver formatted Telegram digests via the Bot API.
- SAP-relevant Gen-AI use cases I have either piloted or scoped for client programs:
  - RISE with SAP + Joule / BTP AI Core: scoping conversational analytics on S/4HANA CDS views for service-delivery PMs (auto-summarise incident root cause from CA-Err-Log + SM21).
  - Incident triage copilot: RAG over SAP Notes + KBA + customer-specific runbooks, embedded in Solution Manager as a side-panel; reduces MTTR by surfacing prior similar incidents.
  - Automation-of-automation: LLM-generated ABAP/Fiori change-request drafts from incident tickets, reviewed by Basis team before transport release — cuts ~40% of Tier-1 ticket time per pilot.
  - Workforce pyramid optimisation: clustering models on ticket text + SLA data to flag teams with systemic skill gaps, feeding into the FTE / pyramid correction governance I run today.
  - Observability + AI: correlating Solution Manager MAI alerts with SAP EarlyWatch Alert narratives; LLM drafts the customer-facing RCA in the customer's own language.
- Production hygiene: prompt caching, deterministic tool schemas, HMAC-signed webhooks, idempotency keys, log redaction, secret scope per profile. No PII sent to untrusted models; all credentials stored in `~/.hermes/.env` with `chmod 600`. **Relevance for SAP delivery:** these patterns (deterministic tool schemas, secret scoping, replay protection, no-PII gating) translate directly to enterprise RISE with SAP + BTP AI Core deployments where prompt caching and per-tenant secret isolation are production requirements, not nice-to-haves.

AI-AGENT CONFIGURATION (HERMES STACK — REFERENCED IN COVER LETTER)

Self-hosted, multi-profile, multi-channel AI agent stack for personal and SAP-adjacent workflows. Architecture:

- Runtime: Hermes Agent (Nous Research, open-source) on Oracle Cloud free tier (ARM Ampere, 4 OCPU / 24 GB RAM), Ubuntu 24.04, systemd-managed.
- Channels: Telegram (DM) and Discord (server), both authenticated and active; alerts and cron jobs deliver to Telegram Home channel.
- Profiles (7 active, isolated contexts + memory + skills each):
  master-orchestrator · profile-it-service · profile-impex · profile-social · profile-blood-bank · profile-personal · profile-trading-watch
- Cron jobs in production: morning trading briefing (08:55 IST weekdays), weekly paper-trade review (Sun 19:30 IST), portfolio dashboard refresh (every 5 min).
- Live services: TradingView webhook receiver (HMAC-signed, port 5010) → paper-trade SQLite ledger; results dashboard (port 5025) over Cloudflare Tunnel; systemd unit files for webhook / dashboard / 2 cloudflared tunnels.
- Model routing: OpenRouter free tier (default), with credential pool rotation. No outbound telemetry. Secrets isolated per profile scope via `agent.secret_scope.get_secret`.
- Safety rails: trading-watch profile is read-only (no broker connection, no order placement); blood-bank profile is log-only (no SMS broadcast); personal profile is scheduling-only (no message-send to external contacts). Each boundary documented in that profile's `SOUL.md`.

Project Manager | IBM India Pvt Ltd | Nov 2011 – Jun 2019
During my enriching 7+ years tenure at IBM, I Managed multiple SAP Application Management Services (AMS), SAP Upgrade, Migration, and SAP S/4HANA initiatives as Project Manager and Offshore Delivery Lead. Led end-to-end project delivery for SAP modules including MM, SD, FI, CO, MII, PP, QM, and PS, overseeing SLA compliance, client escalations, Agile delivery, resource planning, stakeholder management, and strategic decision-making. Successfully delivered SAP enhancements, technical upgrades (ECC, MII, Enterprise Portal, Redwood), migrations, and S/4HANA proof-of-concept implementations while ensuring high customer satisfaction and operational excellence. Recognized for outstanding performance with the IBM Service Excellence Award, IBM E&E Award (2012), and Q1 2012 Star Delivery Excellence Award for contributions to the TML project.

Senior Software Engineer | Accenture | Mar 2010 – Nov 2011
Served as a Senior Software Engineer and SAP Basis Team Lead, managing a team of over 20 professionals across multiple SAP technologies, including ECC, CRM, EP, PI, BW, and Solution Manager. Led workload planning, resource allocation, client escalations, team development, performance reviews, and coordination with global stakeholders while actively contributing to technical and managerial decision-making. Oversaw SAP server implementations, production support, system monitoring, transport management, proactive issue prevention, and resolution of high-priority incidents, ensuring operational stability and service excellence across complex SAP landscapes.

Senior Software Engineer | Mahindra Satyam | Aug 2007 – Feb 2010
Served as a Senior Software Engineer specializing in SAP Basis, delivering SAP implementation, upgrade, reimplementation, and post-go-live support projects. Successfully completed multiple SAP initiatives, including ECC 6.0 upgrades, ECC implementation, and Enterprise Portal (EP) reimplementation, while providing technical consulting and SAP solution recommendations. Actively contributed to pre-sales activities such as due diligence studies, RFP/RFC preparation, solution discussions, and client presentations. Gained end-to-end project experience by successfully delivering a project from pre-sales and planning through implementation and production go-live.

System Engineer | IBM India Pvt Ltd | Oct 2006 – Jul 2007
Began my professional SAP journey as a System Engineer, developing strong expertise in SAP Basis administration and enterprise application support. Supported day-to-day operations (24×7) across a diverse SAP landscape, including ECC, BW, APO, SRM, EP, XI, and Solution Manager, while managing transport activities and ensuring system stability. This early experience built the technical depth that enabled my progression into project management and executive leadership within global SAP delivery organizations.

Sr. Engineer (Officer) EDP | Indo Schöttle Auto Parts | Feb 2004 – Sep 2006
Started my IT career as the EDP Officer, taking ownership of the organization's IT operations and infrastructure within a manufacturing environment. Responsible for IT planning, budgeting, vendor coordination, and day-to-day technology operations while driving initiatives to modernize the company's IT landscape. Successfully led the implementation of Lotus Notes for enterprise collaboration and played a key role in the organization's transition from legacy systems to SAP ERP, gaining early exposure to enterprise applications, digital transformation, and business process automation.

EDUCATION

- Bachelor of Business Administration
- Post Graduate Diploma in Computer Applications
- Diploma in Industrial Electronics

CERTIFICATIONS

- Professional Agile Leadership (PAL I)
- PRINCE2 Agile® Foundation
- PRINCE2 Agile® Practitioner
- NOVA Leadership Coaching Program (T-Systems)
- SAP Certified Technology Associate – Database Administrator – SAP HANA
- SAP Certified Associate – Project Manager – SAP Activate
