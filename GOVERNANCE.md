# ⚖️ Governance Model

Our goal is to ensure coordination without slowing down work. We use "Lazy Consensus" for speed and "Sortition" (Random Selection) for fairness.

## 1. Membership Structure
Participation is based on merit, not money.

* **Contributor:** Anyone who submits a fix (PR), provides an idea, or solves an issue.
* **Core Member:** A person who contributes consistently, earns the community's trust, and is accepted by existing members. Has voting rights on critical decisions (Constitution changes, fund management, etc.).

> **Scenario:** *Sarah submits 3 high-quality patches from the outside. Existing members appreciate her code quality and communication, inviting her to become a "Core Member". If Sarah accepts, she gains a say in governance.*

## 2. Decision Making: Lazy Consensus
Meetings for every small decision are a waste of time. We assume agreement and listen for objections.

* **The Rule:** Announce your task or proposal in the communication channel. If no reasoned technical or strategic objection (Veto) is raised within **48 Hours**, the proposal is **considered accepted** and implementation begins.
* **The Benefit:** We don't wait for everyone to say "yes." We only stop to discuss if someone says "no."

> **Scenario:** *Ali wants to switch the database from PostgreSQL to MariaDB. He shares the plan in the channel. If no one says "This is risky because..." for 48 hours, Ali starts the migration. No voting or meetings required.*

## 3. Conflict Resolution: Random Jury (Sortition)
When two members disagree or an allegation of rule violation arises, we disable politics to prevent lobbying and factionalism.

* **The Rule:** In unresolved situations, the system algorithmically selects **3 Random Members**. This "Jury" listens to the parties, reviews the evidence, and makes a binding decision.
* **Fairness:** Since jury members are selected randomly, no one can lobby beforehand.

> **Scenario:** *John and Aisha argue over a UI design. Work is deadlocked. The system picks 3 neutral members (Dave, Kim, Leo). The jury reviews both designs and decides "Aisha's design is better for mobile responsiveness, we choose that." The topic is closed, work continues.*

## 4. Leadership: Maintainers
There is no CEO or President here; there are **Maintainers**.

* **Role:** A Maintainer is responsible for the technical quality and progress of a specific module (e.g., Frontend) or project.
* **Authority:** They do not give orders; they manage the process, merge code, and remove blockers.

> **Scenario:** *Mark, the Maintainer of the "VPN Project", does not tell developers "You must do this." He reviews incoming code, approves it if it meets standards, and answers the team's questions.*