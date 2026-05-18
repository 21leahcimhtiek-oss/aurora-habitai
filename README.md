# HabitForge AI

> Build life-changing habits with AI coaching

## Features
- AI habit coaching
- Streak tracking
- Daily check-ins
- Progress analytics
- Smart reminders

## Stack
- Next.js 14 (App Router) + TypeScript
- Tailwind CSS
- OpenAI GPT-4o-mini
- Stripe Subscriptions
- Vercel deployment

## Quick Start

```bash
npm install
cp .env.example .env.local
# Fill in API keys
npm run dev
```

## Environment Variables
Copy `.env.example` to `.env.local` and configure:
- `NEXT_PUBLIC_APP_NAME`
- `NEXT_PUBLIC_APP_URL`
- `OPENAI_API_KEY`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `STRIPE_PRICE_PRO_MONTHLY`
- `STRIPE_PRICE_PRO_YEARLY`
- `DATABASE_URL`

## Pricing
| Plan | Price |
|------|-------|
| Free | $0/mo |
| Pro  | $9/mo or $79/yr |

## Deployment
1. Push your changes to GitHub.
2. Import the repository into Vercel.
3. Add all variables from `.env.example` in Vercel project settings.
4. Confirm build command is `npm run build`.
5. Deploy and verify application health.

## License
MIT (c) 2026 Aurora Rayes LLC

## Aurora Ecosystem Positioning
This repository is part of the Aurora ecosystem of focused AI products, aligned to shared reliability and product-quality standards.

## No-Key-First Experience
Aurora products prioritize a no-key-first onboarding path so users can start with core functionality before adding external API keys or credentials.

