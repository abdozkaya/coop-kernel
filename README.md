# 🌍 Co-op Kernel: Open Source Software Cooperative Core

**Co-op Kernel** is a framework for independent developers to unite and create value on a collective foundation. It is a transparent, modular, and democratic **software cooperative core.**

This structure fills the gap between the rigid hierarchies of traditional corporations and the unstructured nature of volunteer projects. It provides a ready-to-use **operating system** for managing labor, voting rights, and revenue, independent of legal status.

## 🎯 Why Start a Software Cooperative with Co-op Kernel?

Software teams often fall apart not due to technical issues, but due to "human" issues (unfair distribution, unclear governance). Co-op Kernel solves these problems with mathematical and democratic rules.

### 1. A Democratic, Fair, and Free System
Here, there are no bosses; there are protocols.
* **Voting Rights (1 Person = 1 Vote):** Those who contribute labor govern, not those who provide capital. Whether you are a founder or a new member, your vote carries equal weight in critical decisions.
* **Contributor vs. Member Balance:** Anyone can contribute ("Contributor"), but those who consistently commit labor and earn trust ("Core Member") gain a say in governance. This protects meritocracy.
* **Freedom (Right to Fork):** The system's ultimate guarantee is the right to leave. If the community becomes corrupt, a minority group is free to copy the project and the rules (Fork) and go their own way. No one is locked in.

### 2. Algorithmic Fairness (Formula-Based Earnings)
Value distribution is based on open formulas, not subjective opinions or negotiation skills.
* **The Logic:** `Time Spent` x `Complexity Factor` = `Your Share`.
* **The Result:** Regardless of seniority, you receive a share of the project's revenue equal to the actual value you produced. It is transparent and non-negotiable.

### 3. Fluid Governance (Progress Without Meetings)
Bureaucracy must not stop production.
* **Lazy Consensus:** You don't need permission. Announce what you are going to do; if no technical objection is raised within 48 hours, it is considered approved. We reward coding, not debating.

---

## 🚀 Step-by-Step: Build Your Software Cooperative Now

Follow these steps to establish your own democratic software community using this framework.

### Phase 1: Establish the Headquarters (Organization)
You don't need a physical office, but you need a digital HQ.
1.  **Create a GitHub Organization:** Open a free GitHub Organization (e.g., `github.com/OurCoop`).
2.  **Use This Template:** Click the green **"Use this template"** button in this repository.
3.  **Select Owner:** Choose your newly created Organization.
4.  **Name the Repository:**
    * **Pro Tip:** Name this repository **`.github`**.
    * *Why?* In GitHub, the `.github` repository is special. Its `README.md` (your Manifesto) will automatically be displayed on your Organization's public profile page!
    * *Alternative:* Name it `governance` or `meta`.

### Phase 2: Ratify the Constitution
Customize the rules to fit your team's needs.
1.  **Sign the Manifesto:** Read `MANIFESTO.md`. Founding members should add their names to the bottom via a Pull Request to make their first commitment.
2.  **Adjust Economics:** Open `ECONOMICS.md`.
    * Are the complexity multipliers (e.g., Backend 1.5x) suitable?
    * Is the Reserve Fund rate (20%) sufficient? If not, edit and `Commit`.

### Phase 3: Activate the Tools
Set up the technical infrastructure for transparency.
1.  **Communication:** Set up a Discord server and add the invite link to this README.
2.  **Finance:** Open an Open Collective page (for fiat) or a Gnosis Safe wallet (for crypto). Add the links to this repo.
3.  **Admin Dashboard:** Go to `Settings > Pages` in this repository. Enable **GitHub Pages** (Source: `main` branch). You now have a live payout calculator website at `https://[YourOrg].github.io/.github/admin/dashboard.html`.

### Phase 4: Create Workspaces (Product Repos)
Now that the government is set, build the factories.
1.  **Create New Repositories:** Create separate repositories inside your organization for your actual software projects (e.g., `vpn-app`, `accounting-lib`).
2.  **Set Up Labels:** In these new project repos, create the scoring labels (e.g., `score:1`, `score:1.5`) as defined in your constitution.
3.  **Start Coding:** Open issues in these project repos, assign scores, and start developing.
4.  **Payday:** At the end of the month, use the **Admin Dashboard** (from Phase 3) to calculate payouts for each project repository separately.

> *"Congratulations! You now have a software cooperative with no boss, clear rules, and fair revenue sharing."*

---

## 📦 Core Contents

This repository contains all the logic required for your cooperative:

* **📜 [MANIFESTO.md](MANIFESTO.md):** Ethical foundation and shared values.
* **⚖️ [GOVERNANCE.md](GOVERNANCE.md):** Decision making, voting, and jury processes.
* **📊 [ECONOMICS.md](ECONOMICS.md):** Revenue sharing formulas and multipliers.
* **🛡️ [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md):** Professional work and safety standards.
* **🛠️ [TOOLS.md](TOOLS.md):** Recommended collaboration tools guide.
* **💻 [Admin Dashboard](admin/dashboard.html):** Automated payout calculator.