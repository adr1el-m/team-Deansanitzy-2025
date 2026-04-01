![Kita-kita Banner](img/Banner.jpg)

# 🏦 Kita-kita - AI Banking Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](package.json)
[![Node.js](https://img.shields.io/badge/Node.js-%3E%3D20.19.2-green.svg)](https://nodejs.org/)

### Kita-kita: Your AI Financial Co-pilot

![Landing Page](img/LandingPage.jpg)

## The Challenge: Financial Empowerment for Every Filipino

In the Philippines, millions lack access to personalized financial guidance, making it difficult to manage debt, optimize cash flow, and build long-term wealth. Kita-kita was born out of a need to bridge this gap, providing a sophisticated yet accessible AI-powered financial co-pilot tailored to the unique economic landscape of the Philippines.

---

## Table of Contents
1. [Our Solution: Key Features](#our-solution-key-features)
2. [How We Built It: Tech Stack](#how-we-built-it-tech-stack)
3. [Run it Yourself: Quick Start](#run-it-yourself-quick-start)
4. [The Team Behind Kita-kita](#the-team-behind-kita-kita)

---

## Our Solution: Key Features

- **🤖 AI Financial Agents**: A suite of intelligent assistants designed to tackle specific financial goals:
    -   **Debt Demolisher**: Creates a personalized, automated debt-elimination plan.
    -   **Cashflow Optimizer**: Analyzes spending habits and identifies opportunities to save.
    -   **Wealth Builder**: Provides long-term investment guidance with a focus on the Philippine market.

- **💰 Unified Financial Hub**:
    -   Manage all your bank accounts and e-wallets in one place.
    -   Track transactions, categorize spending, and monitor recurring subscriptions seamlessly.

- **📊 Advanced Analytics & Forecasting**:
    -   Visualize your financial health with real-time charts and dashboards.
    -   Leverage AI-powered predictions to anticipate future expenses and make informed decisions.

---

## How We Built It: Tech Stack

| Category       | Technologies                               |
| -------------- | ------------------------------------------ |
| **Frontend**   | `HTML5`, `CSS3`, `JavaScript (ES6+)`       |
| **Backend**    | `Node.js`, `Express.js`                    |
| **Database**   | `Firebase Firestore`                       |
| **AI**         | `Llama 3 (running locally)`                |
| **Platform**   | `Firebase (Auth, Hosting)`                 |
| **Libraries**  | `Chart.js`, `Helmet`, `Express Rate Limit` |
| **Dev Tools**  | `Jest`, `Nodemon`, `Sentry`                |

---

## Run it Yourself: Quick Start

### Prerequisites
-   A modern web browser (Chrome, Firefox, Safari, etc.)
-   [Node.js](https://nodejs.org/en) (v20.19.2 or higher)
-   [npm](https://www.npmjs.com/) (v10.0.0 or higher)

### Installation & Launch
1.  **Clone the repository**: `git clone https://github.com/Deansanitzy/team-Deansanitzy-2025-main.git`
2.  **Navigate to the project**: `cd team-Deansanitzy-2025-main`
3.  **Install dependencies**: `npm install`
4.  **Run the application**: `npm start`
5.  **Access the app** at `http://localhost:3000`.

---

## The Team Behind Kita-kita

| Member                  | Role                                         |
| ----------------------- | -------------------------------------------- |
| **Adriel Magalona**     | Lead Developer & Financial Systems Architect |
| **James Rafael Mendiola** | Full Stack Developer & AI Integration Specialist |
| **Jude Vincent Puti**   | Frontend Developer & UI/UX Designer        |

---

**Built with ❤️ by Team Deansanitzy**

![Team Members](img/TeamMembers.png)

## Additional Notes

- Production credentials and API keys should be loaded from environment variables only.
- For backend hardening and checks, use the scripts in `scripts/` and the commands in `package.json`.
- Security and attribution details are in [LICENSE.md](LICENSE.md).

## Known Security Baseline

- Current `npm audit` baseline is 8 low-severity advisories, with 0 critical, 0 high, and 0 moderate.
- The remaining low advisories are transitive dependencies in the Firebase Admin ecosystem and are currently upstream-limited.
- Downgrading to `firebase-admin@10.3.0` removes those low advisories but introduces higher-risk advisories (critical/high), so it is intentionally avoided.
- Keep `firebase-admin` at the latest published version and rerun `npm run security-scan` after dependency updates.

## Support

- Email: dagsmagalona@gmail.com
- Issues: Open a GitHub issue in this repository
