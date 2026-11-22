# WebsiteEnginez — Web

Frontend for websiteenginez.com. Lovable scaffold → Cloudflare Pages.

## What it does
- Prospect pastes a URL → sends to `kjwidgetz-api.onrender.com/website/jobs`
- Shows side-by-side preview (their current site vs modernized rebuild)
- Stripe checkout → deploy to custom domain via SiteEnginez

## Stack
- Lovable scaffold, Vite + React
- Supabase Auth (project `oiiduolwnhinosmbkquz`)
- API: `/website/*` namespaced on kjwidgetz-api
- Billing: KJEmpirePayz
