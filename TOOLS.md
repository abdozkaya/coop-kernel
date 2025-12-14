# 🛠️ Technical Infrastructure & Tools Guide

To run the Co-op Kernel protocol, you don't need a building, but you need correctly configured digital tools. This document explains the "Software Cooperative Tech Stack" and how to configure it to support our principles of transparency and efficiency.

### Phase 1: Communication Infrastructure (Virtual Office)
This is where the culture lives.
* **Recommended Tool:** Discord (Free & Easy Role Management)
* **Configuration:** It is recommended to set up your server with this channel structure:
    * `#announcements` (Official news, read-only for most)
    * `#general` (Daily chat)
    * `#governance` (For management discussions and voting links)
    * `#dev-backend` / `#dev-frontend` (Technical discussions)
    * `#finance-log` (Where the Open Collective bot automatically posts expenses)

### Phase 2: Production & Scoring Pipeline (The Factory)
Where labor is measured and code is produced.
* **Recommended Tool:** GitHub Projects & Issues
* **Workflow:**
    1.  **Open Issue:** Define the task.
    2.  **Score It:** Maintainers assign labels like `score:1`, `score:1.5`.
    3.  **Develop:** Member assigns themselves, codes, and submits a PR.
    4.  **Approve:** Code is merged and Issue is closed.
    * *Note: The payout calculator only considers "Closed" issues with "Score Labels".*

### Phase 3: Decision Making Mechanism (The Assembly)
Use the right tool to keep democracy from becoming chaos.
* **Small Decisions (GitHub Discussions):** Use this for technical choices or minor process changes. Run quick "Polls" to execute the "Lazy Consensus" process.
* **Major Decisions (Loomio):** Use Loomio for Constitution amendments, large budget expenses, or member expulsion. It officially records discussion and votes (Yes/No/Abstain/Block).

### Phase 4: Financial Management (The Open Vault)
For transparent money management.

* **Option A: Fiscal Host (Open Collective) - *Recommended for Fiat***
    * **Why:** Provides a "Fiscal Host" service so you don't have to incorporate a company.
    * **Income:** Clients pay here, get invoices from here.
    * **Expense:** Members submit "Expenses" to claim their payouts.
    * **Transparency:** Everyone sees money in/out instantly.

* **Option B: Crypto Treasury (Gnosis Safe) - *Recommended for Web3***
    * **Why:** To manage assets without a single point of failure.
    * **Setup:** Create a Gnosis Safe (Multi-sig) wallet on your preferred chain (Ethereum/Polygon/etc.).
    * **Signers:** Assign at least 3 trusted "Core Members" as signers. Set the threshold to 2/3 (or similar) for any transaction execution.
    * **Transparency:** Share the wallet address in the repo so anyone can audit holdings on Etherscan.

### Phase 5: Payout Automation (The Calculator)
To perform month-end reconciliations without errors.
* **Tool:** `admin/dashboard.html` (Included in this repo)
* **Setup:**
    1.  Go to your repo's "Settings > Pages".
    2.  Select `main` or `master` branch as "Source".
    3.  Bookmark the generated website link (e.g., `https://ourcoop.github.io/meta/admin/dashboard.html`).
    4.  At the end of the month, visit this page to see exactly who gets paid what with one click.

### Phase 6: Security & Password Management
For the safety of shared accounts.
* **Recommended Tool:** Bitwarden (Open Source Password Manager)
* **Usage:** Never share Twitter, LinkedIn, or server passwords in plain text on Discord. Create an "Organization" on Bitwarden and share credentials securely.