# Awesome-Automated-Receivables-Collections

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **pricing is inconsistent across sources**, and the open-source side has exactly one early-stage project.



## The data problems



**Kolleno's pricing is from a third-party tracker, not Kolleno's own page.** PricingSaaS lists **BusinessPay $545/user/month annual** ($650 monthly) and **Business Plus $995/user/month annual**, with no free tier . Treat as indicative—verify directly with the vendor.



**Chaser's pricing is from the Sage marketplace.** Compact **$200/month** (4 users, revenue under $5M), Core **$550/month** (unlimited users, revenue under $13M), Complete **$1,000/month** (revenue under $120M) . These are revenue-capped tiers, not per-user—an important distinction.



**Upflow has conflicting entry points.** The Sage Intacct marketplace lists **$400/month up to $3M ARR**, **$800/month up to $6M ARR**, custom above . SourceForge lists **"Free to Start"** . **These are irreconcilable**—the "free" likely refers to a trial, not a permanent tier. Mark the ARR-based pricing as the verified figure.



**Billtrust's $65/month is a SelectHub estimate, not vendor-published** . No plan detail surfaced. Mark as indicative.



**YayPay (Quadient) starts at $500/month per Software Advice** , but "No plan information available" follows immediately. Treat as a directory listing, not a rate card.



**Tesorio's pricing is entirely from Vendr benchmarks, not Tesorio.** Small-to-mid **$30K–$60K/year**, mid-market **$60K–$120K**, enterprise **$120K–$200K+**; implementation **$10K–$50K+**; negotiated outcomes **15–25% below list** . These are transaction-derived, not vendor-published.



**HighRadius is quote-only.** Pricing depends on modules, integration requirements, and complexity—no public rate card .



**Gaviti is usage-based, not per-user.** No hidden costs; unlimited workflows and users included; pricing tailored to invoice volume . No dollar figure surfaced.



**Chargebee's Smart Dunning is a feature, not a standalone collections product.** The pricing page shows **$7,188/year for up to $100K billing/month**, including Smart Dunning . It is a billing platform, not a dedicated receivables tool.



**Versapay has no pricing surfaced.** Software Advice reviews describe features and pros/cons but no figures .



## Open-source: what actually exists



**BrassLedger** is the only open-source project surfaced. It is **GPL-3.0**, cross-platform .NET, **v0.1.0-pre.6 prerelease**, with receivables support for customer invoices, statements, balances, and cash application .



**BrassLedger is in active pre-release development.** It is a full accounting system, not a dedicated collections automation platform—no dunning workflows, no automated reminders, no payment portal. **Do not present it as a replacement for Upflow or Chaser.**



**No star count surfaced.** Do not invent one.



## What I recommend



**Split into two honest categories:**



**1. Dedicated Receivables & Collections Platforms** (proprietary):

- **Upflow** — $400/mo up to $3M ARR; $800/mo up to $6M 

- **Chaser** — $200–$1,000/mo, revenue-capped tiers 

- **Kolleno** — $545/user/mo annual (third-party tracker) 

- **Gaviti** — usage-based, no per-user fee 

- **Billtrust** — from $65/mo (SelectHub estimate) 

- **YayPay** — from $500/mo (directory listing) 

- **Tesorio** — $30K–$200K+/yr (Vendr benchmarks) 

- **HighRadius** — quote-only, module-based 

- **Versapay** — pricing not surfaced 



**2. Billing Platform with Collections Feature:**

- **Chargebee** — $7,188/yr, Smart Dunning included 



**3. Open-Source (early-stage only):**

- **BrassLedger** — GPL-3.0, v0.1.0-pre.6, full accounting system with receivables module, not a collections automation tool 



**Flag the pricing model differences explicitly:** per-ARR (Upflow), revenue-capped tiers (Chaser), per-user (Kolleno), usage-based (Gaviti), and enterprise benchmarks (Tesorio) produce incomparable costs at the same invoice volume.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not present directory estimates as vendor-published pricing, claim BrassLedger replaces Upflow, or invent star counts.
