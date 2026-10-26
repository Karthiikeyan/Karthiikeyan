## Hi, I'm Karthikeyan 👋

Software engineer at **Capgemini** in Bangalore, working on AWS cloud infrastructure with **AWS CDK and
TypeScript**. Outside work I'm the founder and only engineer of **[SparkTribe](https://sparktribe.in)**, a
live placement-prep platform with **1,200+ registered learners and 200+ paid members**. I also built
**[SparkTime](https://sparktime.in)**, the publishing platform behind my writing.

I like backend problems where correctness matters: payments that are safe to process twice, access rules
that live in one place, data that never leaks by accident.

[![SparkTribe](https://img.shields.io/badge/sparktribe.in-f97316?style=flat&logo=googlechrome&logoColor=white)](https://sparktribe.in)
[![SparkTime](https://img.shields.io/badge/sparktime.in-e8743b?style=flat&logo=googlechrome&logoColor=white)](https://sparktime.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-42K%2B_followers-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/trendiikarthii)
[![YouTube](https://img.shields.io/badge/YouTube-10K_subscribers-ff0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@trendiikarthii)

---

### What I've built

#### 🔥 SparkTribe: my flagship product · [sparktribe.in](https://sparktribe.in) · [engineering case study](https://github.com/Karthiikeyan/sparktribe-case-study)

A placement-prep platform for Tamil-speaking engineering students. I started it, designed and built the
whole system, and run it in production with real users and real payments.

| | |
| --- | --- |
| **Users** | 1,200+ registered learners · 200+ paid members · 200+ students mentored |
| **Product** | 50-day DSA course taught in Tamil (50+ video lessons), daily practice with spaced revision, timed mock tests, DSA/FAANG/company-wise trackers, mentor sessions, Basic/Pro/Premium plans |
| **My role** | Founder and sole engineer: product, architecture, code, deployment, payments, support |
| **Scale of the codebase** | 51 API routes · 29 data models · 25-page admin console with permission scopes and an audit log |

**Engineering I'd talk about in an interview:**
- **Payments that are safe to process twice.** Checkout verification and Razorpay webhooks share one
  idempotent fulfilment step built on conditional single-document writes, so racing or redelivered
  events never double-grant or lose access.
- **One module decides access.** Every paid feature and payment path asks the same entitlement module;
  plan stacking, upgrades and expiry live in pure, unit-tested functions.
- **Tests against a real database.** Payment, refund, coupon and referral flows run against a throwaway
  MongoDB instance, because atomic updates and unique indexes can't be proven with mocks.

`Next.js` `TypeScript` `MongoDB` `NextAuth` `Razorpay` `Tailwind CSS` `Vercel`

> The source is private because it contains paid course material. The case study explains how it works.

#### SparkTime · [sparktime.in](https://sparktime.in) · [source code](https://github.com/Karthiikeyan/SparkTime)

My writing site, 280+ articles and five multi-part courses, running on a CMS I wrote instead of using
one. Every page is a document of an editable content type, so new sections need no code change.  
→ One SQL visibility rule behind every public read path, Postgres full-text search, owner-only admin
with OAuth + PKCE and hashed database sessions, RLS lockdown, and 700+ tests.  
`Next.js 16` `TypeScript` `PostgreSQL` `Drizzle` `Tiptap` `Vitest` `Playwright`

#### [LeetCode solutions](https://github.com/Karthiikeyan/Leetcode-Hard-Problems)

1,000+ problems solved, contest rating 1785 (top 8.7%). This repo holds 130+ of my accepted solutions,
mostly in C++, indexed by pattern, with notes on the hard ones.  
`C++` `Java` `Python` `DSA`

### Day job

On a large enterprise client account at Capgemini I write infrastructure as code: AWS CDK stacks in
TypeScript, GitLab CI/CD pipelines, and the migration of a legacy service from shared infrastructure to
dedicated per-environment compute. That code belongs to the client, so it isn't here.

### Tech I work with

**Languages:** Java · TypeScript · JavaScript · SQL · C++ · Python  
**Backend:** Spring Boot · Node.js · Next.js · REST APIs · Microservices  
**Data:** PostgreSQL · MongoDB · MySQL · Drizzle · Mongoose  
**Cloud & DevOps:** AWS (CDK, EC2, S3, Lambda, IAM, CloudFormation) · GitLab CI/CD · Vercel  

### Certifications

AWS Certified Solutions Architect – Professional · AWS Certified Developer – Associate ·
Google Cloud Professional Cloud Developer · Google Cloud Associate Cloud Engineer ·
Microsoft Certified: Azure AI Engineer Associate

### Beyond code

SparkTribe is also a community: I teach placement prep, DSA and career skills in Tamil to
42K+ people on LinkedIn and 10K on YouTube, and I give talks to engineering students. I write about
software, careers and money on [sparktime.in](https://sparktime.in).

📫 Reach me through [sparktribe.in](https://sparktribe.in), [sparktime.in/contact](https://sparktime.in/contact) or [LinkedIn](https://www.linkedin.com/in/trendiikarthii).
