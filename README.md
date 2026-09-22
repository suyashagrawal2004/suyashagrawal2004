<p align="center">
  <img src="./assets/matrix-banner.svg" width="100%" alt="Suyash Agrawal - AI Engineer, Full-Stack, SaaS Builder" />
</p>

<p align="center">
  <a href="https://github.com/suyashagrawal2004">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=00FF41&center=true&vCenter=true&width=720&height=45&lines=I+build+AI+agents+that+talk+to+real+customers;Solo-built+edujobs.in+and+zapfee.in;Next.js+%2B+Postgres+%2B+LLMs%2C+end+to+end;4%2C500%2B+tests+across+two+solo+SaaS+builds;Open+to+AI+Engineer+and+Full-Stack+roles" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://edujobs.in"><img src="https://img.shields.io/badge/edujobs.in-LIVE-00FF41?style=for-the-badge&labelColor=0D1117" alt="edujobs.in - live" /></a>
  <a href="https://zapfee.in"><img src="https://img.shields.io/badge/zapfee.in-LIVE-00FF41?style=for-the-badge&labelColor=0D1117" alt="zapfee.in - live" /></a>
  <a href="https://suyashagrawal2004.github.io/"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=githubpages&logoColor=00FF41" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/suyashagrawal2004/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logoColor=00FF41" alt="LinkedIn" /></a>
  <a href="mailto:dm.suyash.a@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=00FF41" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=suyashagrawal2004&label=profile+views&color=00ff41&style=flat-square" alt="Profile views" />
</p>

---

## `> whoami`

```yaml
name:        Suyash Agrawal
role:        AI Engineer @ Appiness Interactive (Appyverse)
base:        Bengaluru, India
education:   B.Tech CSE, VIT-AP University (2022-2026)
shipped:     [edujobs.in, zapfee.in]          # built solo, live in production
works_on:    [voice AI agents, multi-tenant SaaS, PostgreSQL]
open_to:     [AI Engineer, Full-Stack Developer]
```

## `> currently`

At **Appiness Interactive** I work on **Vola**, an AI voice campaign platform that runs autonomous outbound calls with live human hand-off. My part: a provider-agnostic voice engine gateway that put **Fish Audio** alongside **ElevenLabs** behind one interface, the in-browser voice preview flow, and the test suite that gates any release from dialling real numbers.

---

## `> shipped`

### EduHire &nbsp;·&nbsp; [edujobs.in](https://edujobs.in)

Hyperlocal recruitment marketplace matching preschool teachers to schools within 5 km. **Built solo.**

- **Spatial matching** on PostGIS with a hyperbolic distance-decay score, so rankings stay stable when a school widens its search radius
- **Transactional command pattern**: every mutation, its audit entry, and its outbox email commit in a single Postgres transaction
- **Locked-down data layer**: Supabase Auth (Google OAuth, magic link), default grants revoked, RLS enforced on 20 tables
- **1,550+ Vitest & Playwright tests** in GitHub Actions, run against an ephemeral PostgreSQL 17 + PostGIS container

<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,postgres,supabase,vercel,githubactions&theme=dark" height="34" alt="EduHire stack" />

### ZapFee &nbsp;·&nbsp; [zapfee.in](https://zapfee.in)

Multi-tenant GST billing and double-entry accounting SaaS for Indian education institutes. **Built solo.**

- **Double-entry ledger** over 63 Postgres models: debits must equal credits, and paisa rounding lands in a breakage account instead of drifting
- **GST tax matrix** that decides tax invoice vs. bill of supply per institute type and SAC code
- **Claude Haiku vision** reads amount and UTR off UPI payment screenshots into strict JSON, at roughly ₹0.15 per screenshot
- **Security**: 4-role RBAC with branch scoping, TOTP MFA, RLS on every table, AES-256-GCM secrets, HMAC-verified Razorpay webhooks

<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,postgres,prisma,supabase,vercel&theme=dark" height="34" alt="ZapFee stack" />

<sub>Earlier builds: [Music Maestro](https://github.com/suyashagrawal2004/music-maestro) · [MixNMatch](https://github.com/suyashagrawal2004/MixNMatch) · [Stonks](https://github.com/suyashagrawal2004/Stonks)</sub>

---

## `> stack`

<img src="https://skillicons.dev/icons?i=ts,js,py,html,css,nextjs,react,tailwind,nodejs,postgres,prisma,supabase,vercel,docker,githubactions,git,linux&theme=dark&perline=17" alt="Tech stack" />

**AI & voice** &nbsp;
![OpenAI](https://img.shields.io/badge/OpenAI-0D1117?style=flat-square)
![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-0D1117?style=flat-square&logo=anthropic&logoColor=00FF41)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-0D1117?style=flat-square&logo=googlegemini&logoColor=00FF41)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-0D1117?style=flat-square&logo=elevenlabs&logoColor=00FF41)
![Fish Audio](https://img.shields.io/badge/Fish_Audio-0D1117?style=flat-square)
![Vercel AI SDK](https://img.shields.io/badge/Vercel_AI_SDK-0D1117?style=flat-square&logo=vercel&logoColor=00FF41)

**Integrations** &nbsp;
![Razorpay](https://img.shields.io/badge/Razorpay-0D1117?style=flat-square&logo=razorpay&logoColor=00FF41)
![WhatsApp Business API](https://img.shields.io/badge/WhatsApp_Business_API-0D1117?style=flat-square&logo=whatsapp&logoColor=00FF41)
![Twilio](https://img.shields.io/badge/Twilio-0D1117?style=flat-square&logo=twilio&logoColor=00FF41)
![n8n](https://img.shields.io/badge/n8n-0D1117?style=flat-square&logo=n8n&logoColor=00FF41)
![GoHighLevel](https://img.shields.io/badge/GoHighLevel-0D1117?style=flat-square)
![Sentry](https://img.shields.io/badge/Sentry-0D1117?style=flat-square&logo=sentry&logoColor=00FF41)

---

## `> activity`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=suyashagrawal2004&show_icons=true&hide_border=true&rank_icon=github&bg_color=0D1117&title_color=00FF41&icon_color=00FF41&text_color=C9D1D9" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=suyashagrawal2004&layout=compact&hide_border=true&bg_color=0D1117&title_color=00FF41&text_color=C9D1D9" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=suyashagrawal2004&hide_border=true&background=0D1117&ring=00FF41&fire=00FF41&currStreakLabel=00FF41&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E&stroke=1B3A24" alt="GitHub streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/suyashagrawal2004/suyashagrawal2004/output/matrix-snake.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/suyashagrawal2004/suyashagrawal2004/output/github-snake.svg" />
    <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/suyashagrawal2004/suyashagrawal2004/output/matrix-snake.svg" />
  </picture>
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=4000&pause=2500&color=00FF41&center=true&vCenter=true&width=760&height=30&lines=%3E+building+AI+products+that+are+not+only+intelligent%2C+but+genuinely+useful_" alt="Building AI products that are not only intelligent, but genuinely useful" />
</p>
