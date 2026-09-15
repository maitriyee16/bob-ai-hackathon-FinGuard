# 🚀 Fraud detection system for online banking


## 👥 Team

| **Team Name** | FinGuard |
| **Track** | [AI / DevOps / Sustainability / Open] |
| **Team Lead** | Maitriyee Radadiya — 26dcs109@charusat.edu.in |
| **Members** | Angel, Astha, Alpeshwari |


## 🎯 Fraud Detection system for online Banking

Our website Aura will solves the problem of **authorized fraud in online banking**, where genuine users are tricked into making fraudulent transactions.
It analyzes transaction behavior, customer patterns, beneficiaries, devices, and transaction context to detect suspicious activity.
This problem affects **banking customers** who may fall victim to scams, phishing, or social engineering.
It also helps **banks and financial institutions** reduce fraud losses, false alerts, and investigation efforts.


Aura addresses **authorized fraud in online banking**, where genuine customers are manipulated by scammers into approving fraudulent transactions. Its primary users are **online banking customers and financial institutions**. Customers risk losing money even when their transactions are properly authenticated, while banks struggle to distinguish genuine payments from socially engineered fraud. Aura analyzes transaction behavior and context in real time to identify suspicious activity and warn users before potential losses occur.



## 💡 Solution

We built **Aura**, an AI-powered fraud detection system that analyzes transaction behavior, customer patterns, beneficiary risk, device signals, and transaction context. It identifies suspicious authorized transactions in real time and provides timely warnings to customers and risk insights to financial institutions.


Aura uses a **context-aware AI risk engine** to evaluate each transaction against the user’s normal behavior, transaction amount, beneficiary history, device signals, timing, and recent activity. It combines rule-based detection, behavioral analysis, and risk scoring to identify unusual patterns that traditional authentication may miss. When a transaction appears suspicious, Aura provides an explainable warning or intervention instead of simply allowing or blocking it.



## ✨ Key Features

- **Feature 1:** **Real-time context-aware fraud detection using AI-powered behavioral analysis and risk scoring.**

- **Feature 2:** **Aura is an AI-powered, real-time fraud detection system that analyzes transaction behavior, user patterns, device signals, and transaction context to identify suspicious banking activity and prevent authorized fraud.**

- **Feature 3:** **Aura is a smart banking fraud detection system designed to detect suspicious transactions before they become financial losses. It analyzes transaction history, spending patterns, location, device activity, beneficiary details, and unusual behavior to generate a real-time risk score. Aura focuses especially on authorized fraud, where users are manipulated into making legitimate-looking fraudulent payments, and provides timely alerts with clear reasons for the detected risk.**


## 🛠️ Tech Stack

| **Languages** | Python, TypeScript |
| **Frameworks** | FastAPI, React.js, Flask |
| **IBM Technologies** | watsonx.ai, IBM Bob |
| **Databases** | PostgreSQL, Redis |
| **Other** | Docker, GitHub Actions |



## 📁 Repository Structure

```
├── src/                  # All source code
├── docs/                 # Written documentation
│   ├── problem-statement.md
│   ├── solution-overview.md
│   ├── architecture.md
│   └── setup-guide.md
├── demo/                 # Demo artifacts
│   ├── screenshots/      # App screenshots
│   └── demo-video-link.txt  # Link to demo video
├── presentation/         # Slide deck
└── submission.yaml       # Structured submission metadata
```


## ⚡ How to Run

> **Copy these exact steps from your [`docs/setup-guide.md`](docs/setup-guide.md)**

```bash
# 1. Clone the repo
git clone https://github.com/bob-ai-hackathon-FinGuard.git
cd [your-repo]

# 2. Install dependencies
[your install command here]

# 3. Configure environment
cp .env.example .env
# Edit .env with your values

# 4. Run the project
[your run command here]
```

---

## 🖥️ Demo

| Artifact | Link |
|---|---|
| 📹 Demo Video | [See demo/demo-video-link.txt](demo/demo-video-link.txt) |
| 🌐 Live Demo | [See demo/live-demo-url.txt](demo/live-demo-url.txt) |
| 🖼️ Screenshots | [See demo/screenshots/](demo/screenshots/) |
| 📊 Presentation | [See presentation/slides.pdf](presentation/) |


## ⚠️ Known Limitations

> Be honest — judges appreciate transparency over overclaiming.

- [Limitation 1: "Authentication is mocked — not production-ready"
- [Limitation 2: "Only tested on Chrome"
- [Limitation 3: "Feature X is scaffolded but not fully implemented"


## 🏅 What We're Most Proud Of

The strongest part of **Aura** is its ability to detect **authorized fraud**, which traditional systems can easily miss because the transaction is performed by the legitimate user. Judges should pay close attention to Aura’s **context-aware risk analysis**, which combines user behavior, transaction patterns, beneficiary details, device signals, and unusual activity to generate an explainable risk score and provide timely warnings before potential financial loss.


