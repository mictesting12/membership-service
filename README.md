# Membership Service

The Membership Service issues member records (`membership.json`) and manages onboarding flows.

## Features
- REST API: /signup, /verify, /status/:id
- Issues JWTs + optional Soulbound Token (SBT)
- Dispatches PRs to `registry/` repo with new entries
- Deployable on Cloud Run

## Setup
1. Clone repo
2. cp .env.example .env
3. npm install
4. npm run dev
