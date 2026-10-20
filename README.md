Barran Dodger Legal & Ethical Trust Fund — Public documentary archive of government records, personal testimony, and materials concerning alleged institutional wrongdoing. Documents are published for independent examination; inclusion does not itself establish that an allegation has been proven.# Barran Dodger Justice Portal

![Barran Dodger Justice Portal Banner](./public/brand/banner.png)

Featured First-Person Testimony

When the Record Refused to Disappear

A Prophetic Testimony of Faith, Endurance, Documentary Evidence and the Unfinished Search for Justice

This first-person testimony by Dr Richard William McLean brings together his account of faith, personal endurance, dealings with institutions, and continuing search for justice. It is published for public examination alongside the documentary archive.

Read the complete testimony (PDF)

Readers are invited to examine the linked primary-source documents and consider their context. The testimony records the author’s perspective; publication does not constitute a judicial finding or independently establish the truth of every allegation.

Cryptographic hashes and timestamp proofs, where provided, should be checked against the exact file version they identify.

<p align="center">
  <img src="./public/brand/icon.png" alt="Barran Dodger Justice Portal Icon" width="100" />
</p>

Featured First-Person Testimony

When the Record Refused to Disappear

A Prophetic Testimony of Faith, Endurance, Documentary Evidence and the Unfinished Search for Justice

This first-person testimony by Dr Richard William McLean brings together his account of faith, personal endurance, dealings with institutions, and continuing search for justice. It is published for public examination alongside the documentary archive.

Read the complete testimony (PDF)

Readers are invited to examine the linked primary-source documents and consider their context. The testimony records the author’s perspective; publication does not constitute a judicial finding or independently establish the truth of every allegation.

Cryptographic hashes and timestamp proofs, where provided, should be checked against the exact file version they identify.

## Architecture

The Barran Dodger Justice Portal is a web application designed to productize Dr. McLean's forensic archive.

### Frontend
- **Framework:** Vite + React (TypeScript)
- **Styling:** Tailwind CSS v4
- **Components:** Lucide React icons, professional forensic dark theme.
- **Build Tool:** Vite

### Backend
- **Server:** Node.js Express (`server.cjs`)
- **Database:** Turso (via `team-db` CLI)
- **Payment Processing:** Stripe (Subscription and One-time payments)
- **Schema:**
  - `memberships`: Tracks user subscription tiers (Bronze, Silver, Gold).
  - `documents`: Stores metadata for the 788+ blockchain-verified forensic documents.
  - `dossiers`: Tracks AI-generated forensic reports requested by users.
  - `advocacy_bursts`: Records sponsored transmissions of "Truth Packages".

### Key Features
- **Forensic Archive Browser:** Searchable interface for 52+ blockchain-verified evidence documents.
- **AI Forensic Dossiers:** On-demand synthesis of evidence for specific agencies or incidents ($49.00/report).
- **Justice Memberships:** Tiered access (starting at $15/mo) to exclusive updates and advocacy tools.
- **Automated Advocacy Bursts:** Sponsored "Truth Packages" sent to media, parliament, and oversight bodies ($25.00/burst).

## Getting Started

### Development
1. Navigate to `/home/team/shared/portal`
2. Run `npm install`
3. Run `npm run dev` (Vite) or `node server.cjs` (Express + Production Build)

The Express server binds to port `3001` and serves both the API and the production build.
