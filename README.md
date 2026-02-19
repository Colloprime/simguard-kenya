# 🛡 SimGuard Kenya — SIM Fraud Detection & Alert Platform

A professional anti-fraud command centre for detecting, blocking, and reporting fraudulent SIM card registrations and stolen National ID usage across Kenya.

## 🚀 Features

### Real-Time Monitoring
- **Live Registration Feed** — Every SIM registration attempt streamed in real time with risk classification
- **Live Alert Ticker** — Scrolling ticker of active fraud events across the platform
- **KPI Dashboard** — Active threats, flagged registrations, blocked attempts, and protected IDs

### Fraud Detection
- **ID Theft Detection** — Flags when a National ID is used to register a SIM without owner consent
- **SIM Swap Fraud** — Detects and blocks unauthorized SIM swap requests
- **Multi-County Registration** — Flags physically impossible same-day registrations across counties
- **Agent-Level Fraud** — Monitors agent registration velocity and patterns

### 📍 Nearby Agent Locator
- Interactive map showing all Safaricom agents near your location
- Color-coded pins: **green** (verified), **amber** (under watch), **red** (flagged/suspended)
- One-click **"Report Incident Here"** button per agent
- Flagged agents clearly marked with suspension status

### ID Watch (Owner Alerts)
- Enroll your National ID for monitoring across all Kenyan telecom operators
- Instant SMS + push alert when your ID is used to register any SIM
- Lock modes: Alert Only / OTP Approval Required / Full Block
- Covers: Safaricom, Airtel Kenya, Telkom Kenya

### Reporting System
- Submit stolen SIM / fraudulent ID use reports
- Auto-block on submission
- Case ID assigned and tracked
- CA Kenya notified on high-risk cases

### Blacklist Management
- Block National IDs, SIM numbers, and agents
- Reasons: Stolen ID, Confirmed Fraud, Court Order, CA Kenya Directive
- Shared flag across all operators

## 🗂 Project Structure

```
simguard-kenya/
├── index.html        # Main dashboard (single-file app)
└── README.md         # This file
```

## 🛠 Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript (no framework dependencies)
- **Fonts:** Outfit (UI) + JetBrains Mono (data/IDs)
- **Design:** Dark command-centre aesthetic, production-grade UI

## 🔮 Planned Integrations

- [ ] Safaricom Registration API
- [ ] IPRS (Kenya National Registration Bureau) database
- [ ] Communications Authority of Kenya (CA Kenya) live feed
- [ ] DCI Kenya fraud reporting pipeline
- [ ] Google Maps API for real agent locations
- [ ] SMS gateway (Africa's Talking / Safaricom SMS API)
- [ ] Push notifications (Firebase FCM)

## 📋 How It Works

1. When a SIM registration is attempted, it hits the SimGuard API
2. The system cross-checks the National ID against the IPRS database and blacklist
3. Risk score is calculated (0–100) based on location, frequency, agent history, and ID flags
4. If risk > threshold → auto-block + owner SMS alert
5. Case logged, CA Kenya notified if critical

## 🇰🇪 Stakeholders

- **Safaricom Kenya** — Primary operator integration
- **Communications Authority of Kenya (CA)** — Regulatory oversight
- **National Registration Bureau** — ID verification
- **DCI Kenya** — Criminal investigation referrals

## 📞 Quick Actions for Citizens

- Report stolen SIM: Use the **Report Incident** section
- Protect your ID: Use **ID Watch** enrollment
- Find nearest agent: Use **Nearby Agents** map

---

*Built to protect Kenyan citizens from SIM fraud, ID theft, and unauthorized telecoms activity.*
"# simguard-kenya" 
