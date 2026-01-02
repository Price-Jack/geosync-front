# GeoSync Frontend (Common Operating Picture UI)

A React-based frontend for **GeoSync**, a “Common Operating Picture (COP)” style web application built to support **pre-operational planning** workflows by organizing and presenting mission-relevant research data and documents in a single interface.

> **Capstone project (UCF)** — this repository contains the **frontend only**.  
> **Security note:** This public repo contains **no sensitive data**. Use mock/sample data only.

---

## What this project does

GeoSync provides a structured UI for planning-oriented research workflows, including:
- A centralized interface to view and organize planning artifacts (documents, notes, references, or mission-relevant data)
- Navigation of planning workflows through stakeholder-driven screens and components
- UI-level access controls using **authentication + role-based access concepts** (e.g., route guards / gated components), where applicable

---

## My contribution (what I personally built)

I built and iterated on the GeoSync frontend with a focus on usability and secure-by-design UI patterns:
- Implemented core page/component structure and primary user flows for the COP interface
- Implemented authentication and **role-based access concepts** in the UI (route protection + conditional rendering)
- Integrated frontend views with backend services/endpoints (when available) and refined flows based on feedback
- Delivered iterative UX/UI improvements to increase clarity and usability for stakeholders

> If you’re reviewing this repo as a recruiter/hiring manager: this project is meant to demonstrate **frontend engineering**, product iteration, and secure UI patterns in a realistic capstone setting.

---

## Tech stack

- **React** (Create React App)
- **JavaScript / HTML / CSS**
- **Node.js / npm** (local development)

> If you used a UI library (Material UI / Chakra / Bootstrap), state management (Context/Redux), or data tooling (Axios/React Query), add it here.

---

## Getting started (local development)

### Prerequisites
- **Node.js** (recommended: 16+)
- **npm** (or yarn)

### Install & run
```bash
git clone https://github.com/Price-Jack/geosync-front.git
cd geosync-front
npm install
npm start
