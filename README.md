# 🚀 Skillera — AI-Powered Career & Skill Navigator on ICP

Skillera is a decentralized AI-powered platform tackling youth unemployment, skill mismatch, and lack of guidance by offering smart career recommendations, personalized skill pathways, mental health support, and policy-level insights for institutions — all while ensuring user privacy on the Internet Computer. 🌍🧠📊

---

## 🧠 Key Problem

-💼 Youth Unemployment Crisis
Millions of students graduate each year without clear career direction or employable skills, leading to rising joblessness.
-🧠 Skill Mismatch
Learners often pursue courses that don’t align with market demand, resulting in wasted potential and unemployability.
-🧭 Lack of Career Guidance Tools
There’s a serious shortage of accessible, AI-driven tools that offer personalized career mentoring based on data.
-📉 No Real-time Institutional Insights
Governments and universities lack systems to track evolving skill gaps or guide youth policy decisions effectively.
-🫥 Mental Burnout & Demotivation
Students face anxiety and demotivation due to unclear futures and peer pressure, with no personalized support.
-🛡 Centralized Data Exploitation
Most platforms store personal data on centralized servers, risking privacy and trust.

---

## ✨ Features added

-🧠 End-to-end ICP dApp using Motoko + JS frontend
-🎨 Beautifully designed UI with motivational UX elements
-🛠 Canister-based backend managing user routing and data flow
-🧭 Seamless user journey from questions → skill map → insights
-📋 Modular questionnaire system for profiling skills and interests
-🧩 Skill inference engine structured with smart prompt logic
-🤖 Placeholder functions for AI Mentor, Skill Gap Analysis, and Job Forecasting (AI not yet integrated)
-🚀 Fully working local deployment with dfx and proper dfx.json setup
-🔐 Privacy-first system — no third-party data sharing
-💅 UX polish + light motivational nudges to retain user engagemen

---

## 🛠 Future Updates & Features

-🤖 Integration of real AI models into Mentor, Skill Gap & Forecast tools
-🌐 Mainnet deployment on the Internet Computer
-📊 Smart admin analytics dashboard for institutions & policymakers
-📚 ML-powered recommendation engine for deeper skill matching
-🧑‍🎓 University/government portal for unemployment mapping + curriculum recommendations
-🧘 AI-powered mental health & motivation assistant
-🪪 NFT-based verifiable skill certificates
-🔗 Web3 login + decentralized user profile storage
-📱 Fully mobile-responsive, PWA-ready UI
-🏆 Gamified journey with progress tracking and reward

---

## 🧰 Tech Stack

| Layer | Tools |
|-------|-------|
| Backend | **Motoko**, DFINITY Canisters |
| Frontend | HTML, CSS, Vanilla JavaScript, Bootstrap |
| Dev Tools | DFX, Vite, ICP SDK |
| Hosting | Localhost (currently), planned for Mainnet |

---

## 🛠️ Setup Instructions

Make sure you have [DFINITY SDK](https://internetcomputer.org/docs/current/developer-docs/sdk-guide/install/) installed.

```bash
# Clone the repository
git clone https://github.com/Shwetuu28/Skillera.git
cd Skillera

# Start local IC replica
dfx start --background

# Deploy canisters
dfx deploy

# Launch frontend in browser
xdg-open "http://127.0.0.1:4943/?canisterId=$(dfx canister id frontend)"

```

## Canister ID 

# Local:
http://uxrrr-q7777-77774-qaaaq-cai.localhost:4943/

# Mainnet:
Coming soon

---

