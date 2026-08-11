# Kompas MVP

This repository contains the Kompas MVP scaffold (Next.js + TypeScript + Tailwind CSS + Prisma + NextAuth).

Stack (defaults):
- Next.js (TypeScript)
- Tailwind CSS
- Authentication: NextAuth (GitHub + Email)
- Database: Supabase / Postgres (Prisma)
- Deployment: Vercel

Getting started (local)

1. Create a Supabase/Postgres database and set the DATABASE_URL in your environment.
2. Install:

   npm install

3. Generate Prisma client and run migrations (if any):

   npx prisma generate

4. Run the dev server:

   npm run dev

Environment variables (set in Vercel or locally)
- DATABASE_URL: postgres connection URL
- NEXTAUTH_URL: https://your-deployment-url.vercel.app
- NEXTAUTH_SECRET: super-secret
- GITHUB_ID / GITHUB_SECRET (for GitHub OAuth)

Next steps performed by Copilot:
- Scaffold initial Next.js app and API routes on branch `scaffold/initial-setup`.
- Add CI, Prisma schema, and basic pages.

License: MIT
