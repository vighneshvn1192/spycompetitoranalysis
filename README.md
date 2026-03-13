# 🕵️ Spy Competitor AI

> **Automated competitor intelligence powered by AI — monitor, detect, and act on competitor changes before anyone else does.**

---

## What Is This?

**Spy Competitor AI** is a competitor intelligence dashboard that helps founders, marketers, and product managers stay ahead of their competition — automatically.

Instead of manually checking competitor websites every week (and missing changes anyway), Spy Competitor AI watches them for you and uses AI to explain *what changed*, *why it matters*, and *what you should do about it*.

---

## Key Features

- **🔭 Discover Competitors** — Describe your product and AI maps your full competitive landscape: direct, indirect, replacement, and emerging threats
- **🎯 Track Multiple Competitors** — Monitor any number of competitor websites simultaneously
- **📡 Page-Level Monitoring** — Watch specific pages: Homepage, Pricing, Features, Blog
- **⚡ Change Detection** — Automatically detects updates to competitor content
- **💡 AI Insight Reports** — Every detected change gets a structured AI analysis:
  - What changed
  - Strategic meaning
  - What the competitor is likely planning
  - Recommended action for your business
- **📋 Reports Dashboard** — Full history of all detected changes and their analysis status
- **📱 Responsive Design** — Works on desktop, tablet, and mobile
- **🔒 Privacy-First Architecture** — Zero server, zero tracking, zero data collection

---

## Who Is This For?

| Role | Use Case |
|---|---|
| **Startup Founders** | Stay ahead of pricing and product moves before they affect your growth |
| **Product Managers** | Know what features competitors are shipping before your customers ask |
| **Marketers** | Catch messaging shifts and respond before they steal your positioning |
| **Sales Teams** | Turn competitor pricing changes into live deal opportunities |
| **Investors / Analysts** | Track strategic direction through product and pricing signals |

---

## Getting Started

### Requirements

- A modern web browser (Chrome, Firefox, Safari, Edge)
- An [Anthropic API key](https://console.anthropic.com) for AI-powered analysis *(optional — the app works in demo mode without one)*

### Running the App

This is a **single-file application** — no installation, no build step, no server required.

1. Download `spy-competitor-ai.html`
2. Open it in any web browser
3. *(Optional)* Paste your Anthropic API key in the bar at the top to enable real AI analysis
4. Add your first competitor and start monitoring

That's it.

---

## How to Use

### Step 1 — Discover Your Competitors

Navigate to **Discover** in the sidebar. Describe your product, your audience, and what problem you solve. AI surfaces your direct competitors, indirect alternatives, replacement options, and emerging threats — with a one-click **Monitor** button on each.

### Step 2 — Add Competitors Manually

Click **＋ Add Competitor** from anywhere in the app. Enter the competitor's name, website URL, and select which pages to monitor.

### Step 3 — Detect Changes

On any competitor's detail page, click **🔍 Scan Now** to check for updates. Detected changes appear in the timeline instantly.

### Step 4 — Generate AI Insights

Click **✨ Generate AI Insight** on any detected change. The AI produces a structured report covering the change, its strategic meaning, what it signals about the competitor's direction, and what action you should take.

### Step 5 — Review in Dashboard

The **Insights** page shows all AI-generated reports across all competitors, filterable by competitor and change type. The **Reports** page shows the complete change log.

---

## AI Analysis Output

Each insight follows a consistent four-part structure:

```
What changed       — Precise description of the detected change
Strategic meaning  — What this means for the competitor's positioning
Their strategy     — What competitive move this signals
Recommended action — What your company should do in response
```

---

## Privacy & Data

### Our Commitment

Spy Competitor AI is built with a **privacy-first architecture**. We do not collect, store, or transmit any personal data — by design, not just by policy.

### What Data the App Collects

| Data | Collected? | Where It Goes |
|---|---|---|
| Your name or email | ❌ No | — |
| Your API key | ❌ No server | Memory only, cleared on tab close |
| Competitors you add | ❌ No server | Memory only, cleared on tab close |
| Usage analytics | ❌ No | — |
| Cookies or trackers | ❌ No | — |
| IP address or device info | ❌ No | — |

### Your Anthropic API Key

- Your API key is entered directly in your browser and used **only** to make calls to Anthropic's API on your behalf
- It is **never** sent to any server we operate
- It is stored in memory only and is permanently deleted when you close or refresh the tab
- We recommend using a key with usage limits set in your [Anthropic console](https://console.anthropic.com)

### Data Persistence

All data — competitors, changes, insights — exists **only in your browser's memory** for the current session. Closing or refreshing the tab permanently deletes everything. There is no account system, no cloud sync, and no database.

### Competitor Monitoring Ethics

This tool monitors **publicly visible web pages only** — the same pages any person could visit in a browser. This is standard, legal competitive intelligence practice. You must:

- Only monitor public-facing pages (not login-protected content)
- Respect the `robots.txt` and terms of service of websites you monitor
- Not use this tool to collect personal data about individuals
- Comply with applicable laws in your jurisdiction

### GDPR / CCPA

Because the app collects no personal data and operates entirely client-side, it falls outside the scope of GDPR and CCPA data controller obligations in its current form. If you extend this tool with a backend or user accounts, a full legal review will be required.

### Children's Privacy

This tool is not directed at or designed for use by anyone under the age of 18.

---

## Tech Stack

- **Frontend** — Vanilla HTML, CSS, JavaScript (zero dependencies, zero build tools)
- **AI** — Anthropic Claude API (claude-sonnet model)
- **Storage** — In-memory only (browser session, no persistence)

---

## Roadmap

- [ ] Persistent storage (local or cloud, opt-in only)
- [ ] Real website scraping and diffing engine
- [ ] Email / Slack notifications on change detection
- [ ] Scheduled automatic scans
- [ ] Competitor comparison side-by-side view
- [ ] Export reports to PDF / CSV
- [ ] Team collaboration support

---

## Contributing

Contributions, ideas, and bug reports are welcome. Please open an issue before submitting a pull request so we can discuss the change first.

---

## License

MIT License — free to use, modify, and distribute with attribution.

---

## Disclaimer

This tool is intended for legitimate competitive research using publicly available information only. Always respect the terms of service of any website you monitor. AI-generated insights are strategic suggestions and should be reviewed by a human before acting on them. The authors accept no liability for misuse of this tool.

---

*Built with ❤️ and Claude AI*
