# Slumber | Sleep Science + Coaching Platform

Slumber is an AI-powered sleep optimization platform designed for deep analytical rest tracking and coaching. Part of the Orcinos ecosystem.

## Features
- **Sleep Logger:** Log bedtime, wake time, quality, and notes.
- **Sleep Score:** Weekly average efficiency gauge (Oura/Whoop style).
- **AI Sleep Coach:** GPT-4o-mini integration for personalized sleep architecture analysis.
- **Sleep Library:** 20 evidence-based sleep science articles.
- **Sound Library:** 8 curated ambient soundscapes with real audio feeds.
- **Goals & Reports:** Target bedtime tracking and weekly trend analysis.

## Tech Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript.
- **Backend:** Supabase (Auth + Database).
- **AI:** OpenAI API (GPT-4o-mini).
- **Design:** Midnight-mode UI system with Inter typography.

## Setup
1. **Supabase:** Run `schema.sql` in your Supabase SQL editor.
2. **Environment:** Set `SLUMBER_SUPABASE_URL`, `SLUMBER_SUPABASE_KEY`, and `SLUMBER_OPENAI_KEY` in `localStorage` or inject them into `shared/app.js`.
3. **Payments:** Payment stack is configured for PayPal, Crypto (ERC-20), and Payoneer. No Stripe integration.

## Payments
- **ERC-20 Wallet:** `0xcef857e82c306b3d0f2db080e7794f4bb376049e`
- **Pro Tier:** $6.99/mo

---
*Built for the Priscion Web3 Empire by Orcinos.*
