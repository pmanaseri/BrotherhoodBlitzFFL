<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/ca3cabb7-7963-4326-91db-f0f798660986" />



# 🏈 BrotherhoodBlitzFFL

**Brotherhood Blitz FFL** is your commissioner grade fantasy football control center - one place to track teams, rivals, trades, drafts, rosters, and all the chaos in between.

This repo powers the league backend/frontend (and all the admin workflows) for the **Brotherhood Blitz Fantasy Football League**.

---

## 📌 TL;DR

- Structured around **areas**:
  - Team & Rival Card  
  - Banner  
  - Profile Drip  
  - Salary Report  
  - Trade Block  
  - Transactions  
  - Draftboard  
  - Rostercard  
  - General/Missing
- Every area has:
  - **Issue labels** (bug, enhancement, docs, etc.)
  - **Issue templates** (pre-labeled, structured forms)
  - **Project views** (Boards & tables per area + global Bugs)

This isn’t a “dump issues wherever” repo — it’s built to keep the chaos under control.

---

## 🧠 Concept

BrotherhoodBlitzFFL is designed for:

- **League admins/commissioner tools**  
- **UI/UX for league members** (cards, banners, profile drip, draftboards, etc.)
- **Tracking work like a real software project** — not a random Google Sheet

You get:

- Clean breakdown by feature area  
- Built-in triage flow (Status, Priority, Estimate)  
- Project views grouped by **Status** and filtered by **labels**

---

## 🧩 Feature Areas

Each area has its own label set and templates.

### 🧾 Team & Rival Card

Visual + data treatment for:

- Team cards
- Rival matchups
- Head-to-head storylines

Labels: `Team & Rival Card: bug`, `Team & Rival Card: enhancement`, etc.  
Use when the issue touches team/rival views or logic.

---

### 🎌 Banner

League and team banners:

- Hero sections, page headers, announcements, visuals

Labels: `Banner: bug`, `Banner: enhancement`, etc.

---

### 💧 Profile Drip

Profile cosmetics and flex:

- Avatars, themes, custom visuals, drip elements

Labels: `Profile Drip: bug`, `Profile Drip: enhancement`, etc.

---

### 💰 Salary Report

Cap / contract / value views:

- Salary breakdowns
- Cap hits
- Value summaries

Labels: `Salary Report: bug`, `Salary Report: enhancement`, etc.

---

### 🔁 Trade Block

Player trading + availability:

- Trade block UI
- Trade logic hooks
- Visibility rules

Labels: `Trade Block: bug`, `Trade Block: enhancement`, etc.

---

### 📜 Transactions

Movement log:

- Adds/drops
- Trades
- Waivers
- Any league transaction feeds

Labels: `Transactions: bug`, `Transactions: enhancement`, etc.

---

### 🧮 Draftboard

Draft-day tools:

- Draftboard UI
- Pick order / timers
- On-the-clock behavior

Labels: `Draftboard: bug`, `Draftboard: enhancement`, etc.

---

### 🧾 Rostercard

Roster representations:

- Per-team roster UI
- Depth charts
- Player slots / statuses

Labels: `Rostercard: bug`, `Rostercard: enhancement`, etc.

---

### 🧩 General/Missing

Catch-all area:

- Cross-cutting changes
- Global config
- Stuff that doesn’t clearly belong anywhere else

Labels: `General/Missing: bug`, `General/Missing: enhancement`, etc.

---

## 🏷️ Label System

Every area has the same label types:

- `X: bug` – something is broken
- `X: enhancement` – improve or add functionality
- `X: documentation` – docs missing/wrong
- `X: duplicate` – same as another issue
- `X: help wanted` – needs extra hands
- `X: invalid` – not reproducible / not an issue
- `X: question` – asks for clarification
- `X: wontfix` – intentionally not doing this

Where **X** is one of:

- `Team & Rival Card`
- `Banner`
- `Profile Drip`
- `Salary Report`
- `Trade Block`
- `Transactions`
- `Draftboard`
- `Rostercard`
- `General/Missing`

There are also **issue templates** for:

- Bug vs Enhancement  
- Per-area (Team & Rival, Banner, Profile Drip, etc.)

Using the correct template auto-applies the **right labels**.

---

## 🗂️ Project Board Workflow

Project: **“Brotherhood Blitz FFL”** on GitHub Projects.

### 🔄 Auto-add

- New issues from this repo are **auto-added** to the project.
- Defaults (via workflows):
  - `Status: Backlog`
  - Priority & Estimate are then set during triage.

### 👀 Views

Core views (examples):

- **Prioritized backlog** – table of everything, with:
  - `Status`, `Priority`, `Estimate`, `Labels`
- **Status board** – Kanban grouped by `Status`
- **Bugs** – anything with `*: bug` labels
- **Per-area boards**:
  - `Team & Rival Card`
  - `Banner`
  - `Profile Drip`
  - `Salary Report`
  - `Trade Block`
  - `Transactions`
  - `Draftboard`
  - `Rostercard`
  - `General/Missing`

Each area view filters by its area labels, e.g.:

```text
label:"Banner: bug",
"Banner: enhancement",
"Banner: question"
```
