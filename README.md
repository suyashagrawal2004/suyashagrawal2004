<p align="center">
  <img src="./assets/call-banner.svg" width="100%" alt="Suyash Agrawal - a live call where his AI agent answers: voice AI at Appiness, and edujobs.in and zapfee.in, both built solo" />
</p>

<p align="center">
  <a href="https://edujobs.in"><img src="https://img.shields.io/badge/edujobs.in-live-FF5A36?style=for-the-badge&labelColor=0E0F12" alt="edujobs.in - live" /></a>
  <a href="https://zapfee.in"><img src="https://img.shields.io/badge/zapfee.in-live-FF5A36?style=for-the-badge&labelColor=0E0F12" alt="zapfee.in - live" /></a>
  <a href="https://suyashagrawal2004.github.io/"><img src="https://img.shields.io/badge/portfolio-0E0F12?style=for-the-badge&logo=githubpages&logoColor=FF5A36" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/suyashagrawal2004/"><img src="https://img.shields.io/badge/linkedin-0E0F12?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="mailto:dm.suyash.a@gmail.com"><img src="https://img.shields.io/badge/email-0E0F12?style=for-the-badge&logo=gmail&logoColor=FF5A36" alt="Email" /></a>
</p>

## call notes

```text
post-call summary · auto-generated
----------------------------------------------------------------
caller       recruiter
intent       hire an engineer who can ship a product end to end
lead score   hot
heard        builds voice AI agents at Appiness Interactive
             built edujobs.in and zapfee.in solo, both live
             4,500+ tests across the two
background   B.Tech CSE, VIT-AP University (2022-2026), Bengaluru
next step    dm.suyash.a@gmail.com
----------------------------------------------------------------
```

## on the job

At **Appiness Interactive** I work on **Vola**, an AI voice campaign platform that runs autonomous outbound calls with live human hand-off. My part: a provider-agnostic voice engine gateway that put **Fish Audio** alongside **ElevenLabs** behind one interface, the in-browser voice preview flow, and the test suite that gates any release from dialling real numbers.

## shipped

<img align="right" width="250" src="./assets/eduhire.svg" alt="EduHire radius search: a ping ring expands from a school and lights up teachers within 5 km, top match 1.8 km away" />

### EduHire &nbsp;·&nbsp; [edujobs.in](https://edujobs.in)

A hyperlocal recruitment marketplace that matches preschool teachers to schools within 5 km. Built solo.

- **Spatial matching** on PostGIS with a hyperbolic distance-decay score, so rankings hold steady when a school widens its radius
- **One transaction per action**: every mutation, its audit entry, and its outbox email commit together or not at all
- **Locked down**: Supabase Auth with Google OAuth and magic links, default grants revoked, RLS on 20 tables
- **1,550+ Vitest and Playwright tests** in GitHub Actions against a throwaway PostgreSQL 17 + PostGIS container

<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,postgres,supabase,vercel,githubactions&theme=dark" height="30" alt="EduHire stack" />

<br clear="right" />

<img align="right" width="250" src="./assets/zapfee.svg" alt="ZapFee receipt printing: course fee plus 18% GST totals 50,000.00, with debits equal to credits and a Dr = Cr stamp" />

### ZapFee &nbsp;·&nbsp; [zapfee.in](https://zapfee.in)

Multi-tenant GST billing and double-entry accounting for Indian education institutes. Built solo.

- **Books that balance**: a double-entry ledger over 63 Postgres models where debits must equal credits, and paisa rounding lands in its own account instead of drifting
- **GST matrix** that decides tax invoice vs. bill of supply per institute type and SAC code
- **Claude Haiku vision** reads amount and UTR off UPI screenshots into strict JSON, at about ₹0.15 each
- **Security**: 4-role RBAC with branch scoping, TOTP MFA, RLS on every table, AES-256-GCM secrets, HMAC-verified Razorpay webhooks

<img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,postgres,prisma,supabase,vercel&theme=dark" height="30" alt="ZapFee stack" />

<br clear="right" />

<sub>earlier builds: [Music Maestro](https://github.com/suyashagrawal2004/music-maestro) · [MixNMatch](https://github.com/suyashagrawal2004/MixNMatch) · [Stonks](https://github.com/suyashagrawal2004/Stonks)</sub>

## stack

<img src="https://skillicons.dev/icons?i=ts,js,py,html,css,nextjs,react,tailwind,nodejs,postgres,prisma,supabase,vercel,docker,githubactions,git,linux&theme=dark&perline=17" alt="Tech stack" />

![OpenAI](https://img.shields.io/badge/OpenAI-0E0F12?style=flat-square)
![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-0E0F12?style=flat-square&logo=anthropic&logoColor=FF5A36)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-0E0F12?style=flat-square&logo=googlegemini&logoColor=FF5A36)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-0E0F12?style=flat-square&logo=elevenlabs&logoColor=FF5A36)
![Fish Audio](https://img.shields.io/badge/Fish_Audio-0E0F12?style=flat-square)
![Vercel AI SDK](https://img.shields.io/badge/Vercel_AI_SDK-0E0F12?style=flat-square&logo=vercel&logoColor=FF5A36)
![Razorpay](https://img.shields.io/badge/Razorpay-0E0F12?style=flat-square&logo=razorpay&logoColor=FF5A36)
![WhatsApp Business API](https://img.shields.io/badge/WhatsApp_Business_API-0E0F12?style=flat-square&logo=whatsapp&logoColor=FF5A36)
![Twilio](https://img.shields.io/badge/Twilio-0E0F12?style=flat-square&logo=twilio&logoColor=FF5A36)
![n8n](https://img.shields.io/badge/n8n-0E0F12?style=flat-square&logo=n8n&logoColor=FF5A36)
![GoHighLevel](https://img.shields.io/badge/GoHighLevel-0E0F12?style=flat-square)
![Sentry](https://img.shields.io/badge/Sentry-0E0F12?style=flat-square&logo=sentry&logoColor=FF5A36)

## activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=suyashagrawal2004&show_icons=true&hide_border=true&rank_icon=github&bg_color=0E0F12&title_color=FF5A36&icon_color=FF5A36&text_color=F2ECE3" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=suyashagrawal2004&layout=compact&hide_border=true&bg_color=0E0F12&title_color=FF5A36&text_color=F2ECE3" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=suyashagrawal2004&hide_border=true&background=0E0F12&ring=FF5A36&fire=FF5A36&currStreakLabel=FF5A36&sideLabels=F2ECE3&currStreakNum=F2ECE3&sideNums=F2ECE3&dates=8B8F97&stroke=23262D" alt="GitHub streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/suyashagrawal2004/suyashagrawal2004/output/call-snake.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/suyashagrawal2004/suyashagrawal2004/output/github-snake.svg" />
    <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/suyashagrawal2004/suyashagrawal2004/output/call-snake.svg" />
  </picture>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=3200&pause=2200&color=FF5A36&center=true&vCenter=true&width=640&height=28&lines=call+ended.+leave+a+message+at+dm.suyash.a%40gmail.com;or+see+it+running%3A+edujobs.in+%C2%B7+zapfee.in" alt="Call ended. Leave a message at dm.suyash.a@gmail.com" />
</p>
