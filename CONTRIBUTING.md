# Contributing to Trestle DeFi

Thank you for your interest in contributing to the Trestle DeFi ecosystem! We are building open-source infrastructure for decentralized freelancing, Telegram mini-apps, and RWA solutions. Your help makes this ecosystem safer, faster, and more robust.

Please take a moment to review these guidelines before you begin.

---

## 🛡️ Security First (Bug Bounties)

> **CRITICAL:** Do NOT open public GitHub issues for security vulnerabilities or smart contract exploits.

If you discover a vulnerability affecting live user funds, liquidity tiers (**Vault**, **Mine LP**, or **Stake hNOBT**), or backend API keys, please report it privately:
* **Email:** security@trestle.website
* **Response Time:** We review security disclosures within 24 hours.

---

## 🚀 How to Contribute

### 1. Reporting Bugs
If you find a non-security bug in our UI, website, or testnet deployment:
* Check the existing open issues to make sure it hasn't already been reported.
* Open a new issue using our bug report structure.
* Include your environment specs (e.g., Browser version, MetaMask/Wallet provider, Node.js version).
* Provide clear, step-by-step instructions to reproduce the issue.

### 2. Feature Requests
Have an idea to optimize our three-tier token ecosystem?
* Open an issue outlining the user problem, proposed technical solution, and expected outcome.
* Tag it as a `feature-request` or `discussion`.

### 3. Submitting Pull Requests (PRs)
When you are ready to write code:

1. **Fork** the repository you want to work on.
2. **Clone** your fork locally and create a descriptive branch:
   ```bash
   git checkout -b feature/optimize-staking-gas
   # or
   git checkout -b fix/tma-ui-glitch
   ```
3. **Write clean code** that matches our styling standards (see below).
4. **Run tests** locally before pushing.
5. **Commit your changes** using clear commit messages:
   ```bash
   git commit -m "feat(contracts): optimize gas allocation for Vault distribution"
   ```
6. **Push** to your fork and submit a **Pull Request** against our `main` or `development` branch.

---

## 🛠️ Development Standards

### ⛓️ Smart Contracts (Solidity)
* **Testing:** All contract modifications must include 100% test coverage using Foundry or Hardhat.
* **Gas Optimization:** Document gas footprints in your PR if modifying the **Vault** or **Mine LP** staking logic.
* **Libraries:** Stick to standard OpenZeppelin implementations where possible.

### 💻 Frontend & UI (Next.js / Tailwind)
* **TypeScript:** Strict type checking is enforced. Do not use `any` unless absolutely necessary.
* **Mobile-First:** Ensure all layouts scale correctly for Telegram Mini-App (TMA) viewports.
* **Performance:** Keep assets lightweight to ensure snappy loading speeds over mobile data.

---

## 📜 Code of Conduct
We expect all contributors to maintain a welcoming, respectful, and professional environment across our GitHub organization, Discord, and Telegram communities. Harassment of any kind will result in repository blocks and bans.

<br/>

Thank you for helping us anchor the future of decentralized operations! 📐
