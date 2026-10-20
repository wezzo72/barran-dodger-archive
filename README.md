
# Barran Dodger Justice Portal

**Barran Dodger Legal & Ethical Trust Fund** — Public documentary archive of government records, personal testimony, and materials concerning alleged institutional wrongdoing. Documents are published for independent examination; inclusion does not itself establish that an allegation has been proven.

![Barran Dodger Justice Portal Banner](./public/brand/banner.png)

<p align="center">
  <img src="./public/brand/icon.png" alt="Barran Dodger Justice Portal Icon" width="100" />
</p>

---

## Featured First-Person Testimony

### When the Record Refused to Disappear

**A Prophetic Testimony of Faith, Endurance, Documentary Evidence and the Unfinished Search for Justice**

This first-person testimony by Dr Richard William McLean brings together his account of faith, personal endurance, dealings with institutions, documentary preservation, and continuing search for justice. It is published for public examination alongside the Barran Dodger documentary archive.

**[READ THE COMPLETE TESTIMONY — WHEN THE RECORD REFUSED TO DISAPPEAR (PDF)](https://github.com/wezzo72/barran-dodger-archive/blob/main/WHEN%20THE%20RECORD%20REFUSED%20TO%20DISAPPEAR.pdf)**

Truth does not require permission to exist. Evidence, however, must remain open to scrutiny. This archive seeks to preserve records, connect documents to the claims they may support, and allow readers to examine the underlying material independently.

The testimony expresses the author's own account and perspective. References to institutions, individuals, events, or alleged wrongdoing should be assessed against the linked source documents. Publication is not a judicial finding, a verdict, or independent proof of every statement.

---

## Architecture

The Barran Dodger Justice Portal is a web application intended to make documentary materials, personal testimony, and related records accessible for examination.

### Frontend
- Framework: Vite and React with TypeScript
- Styling: Tailwind CSS
- Icons: Lucide React
- Build tool: Vite

### Backend
- Server: Node.js and Express (`server.cjs`)
- Database: Turso
- Payment processing: Stripe, where configured

### Database Schema
- **Memberships:** Membership-related records.
- **Documents:** Metadata and references for archive materials.
- **Dossiers:** Records associated with documentary analysis.
- **Advocacy bursts:** Records associated with advocacy features.

Descriptions of the application's architecture and capabilities should be checked against the current source code and deployed service.

---

## Key Features

- **Documentary Archive Browser:** An interface for locating and examining available evidence documents.
- **Documentary Dossiers:** Organised analysis intended to help readers navigate records and propositions.
- **Membership Features:** Membership functionality where available and operational.
- **Advocacy Features:** Tools intended to support structured advocacy where implemented.

Document totals, verification counts, prices, payment features, and service availability must be confirmed against the current application before being represented as current or independently verified.

---

## Documentary Standards

This archive is intended to support transparency, preservation, and independent examination.

- Distinguish original records from personal testimony, commentary, and AI-generated analysis.
- Preserve available source links, document dates, and relevant identifying information.
- Attribute disputed claims to the person or source making them.
- Do not describe an allegation as a proven fact unless reliable evidence or an applicable official finding supports that description.
- Do not treat an AI assessment as a judicial determination or a substitute for independent expert review.
- Where cryptographic hashes or timestamps are cited, readers should verify them against the exact document and the relevant verification record.
- Make clear when a conclusion is an interpretation rather than a direct statement contained in a source document.

**The purpose of a finding aid is to help readers find and test the evidence. It is not a court, and it is not a verdict.**

---

## Getting Started

### Development

From the project directory:

1. Install dependencies:

   `npm install`

2. Start the development server:

   `npm run dev`

Alternatively, where supported by the project's configuration, start the Express server with:

   `node server.cjs`

The Express server is configured to use port 3001. Actual startup requirements depend on the current project configuration and environment.

---

## Public Archive and Related Materials

### When the Record Refused to Disappear

**[Open the complete testimony PDF](https://github.com/wezzo72/barran-dodger-archive/blob/main/WHEN%20THE%20RECORD%20REFUSED%20TO%20DISAPPEAR.pdf)**

### Rebuild Website

[https://wezzo72.github.io/barrandodger-rebuild/](https://wezzo72.github.io/barrandodger-rebuild/)

### Original Website

[https://wezzo72.github.io/Barrandodger/](https://wezzo72.github.io/Barrandodger/)

The original website is retained as a separate archive. The rebuild and associated repositories provide additional routes for accessing and preserving material.

Readers are encouraged to consult the underlying documents, follow source links, compare records, and form their own conclusions. The archive preserves material for examination; it does not claim that every disputed proposition has been independently established.

**Preserve the record. Examine the evidence. Distinguish testimony from findings. Keep the search for accountability open.**
