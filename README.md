<p align="center">
  <img src="assets/hero.svg" alt="Reniel Galang — Software Engineering and AI Integration. Secure, customizable, easy-to-use software tailored to business needs. Featured prototype: Yumi (YourAI), a Conversational AI Receptionist for airports, hotels, events, barangay health centers, and more." width="100%" />
</p>

## Tech Stack

| Area | Technologies and methods |
| :--- | :--- |
| **Languages** | Python · Java · C/C++ · JavaScript · TypeScript · SQL |
| **Frontend & UI Tools** | React · Vite · JavaFX · HTML · CSS |
| **Backend & Databases** | Supabase · PostgreSQL · MySQL · Firebase · REST APIs · JDBC |
| **AI Platforms** | Azure AI Foundry (Microsoft Foundry) · ElevenLabs Agents |
| **AI Integration** | Knowledge Bases · System Prompts · Speech-to-text · Text-to-speech |
| **Testing, Security & Deployment** | Playwright · Vitest · Supabase Row Level Security · Cloudflare Turnstile · Vercel WAF (Web Application Firewall) · Vercel |
| **Development Tools** | Git · GitHub · OpenAI Codex · Claude Code |
| **Embedded & IoT** | Raspberry Pi · Arduino · ESP32 · MQTT · BLE · Wi-Fi |
| **Firmware & Interfaces** | Finite-state machines · GPIO · UART · I²C · SPI · NFC · GPS |
| **Computer Vision** | OpenCV · YOLOv8 |

## Selected Projects

### 01 / CalorieCheck — Nutrition Tracker

`JavaScript / TypeScript` `Vite` `Supabase / PostgreSQL` `Turnstile` `Vercel`

[Staging demo](https://calorie-calculator-gamma-ten.vercel.app/) · [Repository](https://github.com/Reniel-Relearn/calorie-calculator)

- **Problem:** Move from one-off calorie estimates to personal food tracking with protected user records.
- **My contribution:** Defined requirements, guided AI-assisted implementation, configured authentication and database access policies, integrated Turnstile, and manually tested workflows.
- **Result:** Deployed a mobile-first staging prototype with calorie calculations, accounts, and food logs; conducted usability validation with **three users**.

### 02 / EZ Kyosk — Self-Ordering Kiosk

`React` `JavaScript` `Vite` `Vitest` `Playwright`

[Live web prototype](https://reniel-relearn.github.io/EZ-Kyosk/) · [Repository](https://github.com/Reniel-Relearn/EZ-Kyosk)

- **Problem:** Give cafés, bakeries, and restaurants a focused self-ordering experience.
- **My contribution:** Defined architecture, customer journeys, technology choices, deployment requirements, and acceptance criteria; coordinated AI-assisted implementation and manually tested ordering.
- **Result:** Helped deliver a functional prototype in **one day** and identified **two defects** that were fixed. POS hardware and payment-gateway integration remain pending.

### 03 / AFCS — Automated Fare Collection System

`Python / JavaScript` `Raspberry Pi` `NFC / GPS` `Firebase` `REST APIs`

[Repository](https://github.com/Reniel-Relearn/capstone-design-project-AFCS) · Academic capstone

- **Problem:** Connect fare calculation, authentication, location, seat allocation, hardware, and passenger/driver/admin interfaces.
- **My contribution:** Led a **five-member team**, developed embedded software, integrated hardware and cloud services, and troubleshot GPS instability through circuit, wiring, and satellite-acquisition software changes.
- **Result:** Executed tests across **21 categories** and consolidated **2,188 results**; **2,156 passed (98.54%)**.

### 04 / LaundryLink — Laundry Shop Management

`Java` `JavaFX` `JDBC` `MySQL`

[Team repository](https://github.com/stagnantwater69/LaundryLink)

- **Problem:** Keep a shared desktop application and its relational database consistent during team development.
- **My contribution:** Executed schema migrations across **eight tables and one view**, coordinated AI-assisted implementation of the Services and Prices module, and performed acceptance testing.
- **Result:** Identified an order-status usability defect and retested a teammate's correction to confirm resolution.

<details>
<summary><strong>More Projects</strong></summary>

**Applied AI & Software**

1. [Company Policy Assistant](https://github.com/Reniel-Relearn/company-policy-assistant) — Azure AI Foundry and a policy knowledge base.
2. [AI Audio Threat Detector](https://github.com/Reniel-Relearn/ai-audio-threat-detector) — Bilingual transcription, summaries, and flags for human review.
3. [Life Creation](https://github.com/Reniel-Relearn/life-creation) — Python survival game.

**Embedded Systems & IoT**

1. [ATM Banking System](https://github.com/Reniel-Relearn/atm-banking-system)
2. [PanahonCheck](https://github.com/Reniel-Relearn/panahoncheck-weather-monitoring)
3. [Smart Glass Helmet](https://github.com/Reniel-Relearn/smart-glass-helmet)
4. [Wearable Air Quality Detector](https://github.com/Reniel-Relearn/wearable-air-quality-detector)
5. [Anti-Theft Bag Alarm](https://github.com/Reniel-Relearn/anti-theft-bag-alarm)
6. [Smart Door Status Indicator](https://github.com/Reniel-Relearn/smart-door-status-indicator)
7. [Intruder Alert System](https://github.com/Reniel-Relearn/intruder-alert-system)

**Coursework**

1. [Digital Signal Processing](https://github.com/Reniel-Relearn/dsp-matplotlib-activities)
2. [Assembly Lab Exercises](https://github.com/Reniel-Relearn/assembly-lab-exercises)

</details>

## Problems I Work On & How I Build

![Workflow: define requirements, design boundaries, build with AI assistance, verify, and iterate](assets/workflow.svg)

I define specifications and acceptance criteria, review architecture and AI-assisted implementation, run reproducible checks and real-device tests, and retest fixes before acceptance.

- **Slow voice responses — Yumi:** Configured ElevenLabs, refined prompts and knowledge sources, integrated Supabase/Vercel, and tested on a SUNMI kiosk. **Result:** Observed prototype response time improved from **8–10s to 2–4s**. Used in two internal demos and two client presentations; no confirmed production client deployment.
- **Conflicting audio, video, and orders — AI Bartender:** Used structured event logs and repeated test–fix–retest cycles. **Result:** Resolved missing/incorrect videos, repeated orders, wrong drink selection, overlapping responses, and agent speech during playback in the demonstrated prototype.
- **Grounded answers and trusted operations:** Integrated a knowledge-base-grounded KPI chatbot; kept receptionist identity checks, authorization, and database operations in deterministic application logic. **Result:** KPI prototype presented; receptionist security controls and kiosk workflows tested.
- **Responsive website presentation:** Coordinated AI-assisted development and iteratively reviewed layouts and visual elements for a towing/hauling website. **Result:** Website developed; production status unverified. Client branding and public links await authorization.

**Ongoing engineering work:** Preventing voice agents from hearing their own output, testing streaming responses, refining turn-taking and interruptions, and designing provider interfaces that reduce switching effort. These remain testing priorities and design goals rather than completed results. Client identities, private repositories, and internal materials remain confidential.

## Let's Build Something Useful

[![Reniel Galang's business card — software engineering and AI integration. Email renielgalang.py@gmail.com to discuss business, investment, or collaboration opportunities.](assets/contact.svg)](mailto:renielgalang.py@gmail.com)

**[Email me](mailto:renielgalang.py@gmail.com)** · **[Connect on LinkedIn](https://www.linkedin.com/in/reniel-galang-tech-engr)**
