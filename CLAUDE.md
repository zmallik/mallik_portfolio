I want to build a modern, professional portfolio website for a Senior Backend Engineer. 
Here is my full resume context:

NAME: Mallikarjun Gajji
TITLE: Senior Backend Engineer | Distributed Systems & Platform Engineering
LOCATION: Bangalore, India
EMAIL: g.mallik.dev@gmail.com
LINKEDIN: linkedin.com/in/themallik
GITHUB: github.com/zmallik

SUMMARY:
Backend engineer with 11 years of experience building high-throughput distributed 
systems and SaaS platforms. Owns a revenue-critical pipeline processing 10K+ regulated 
submissions per month, reduced production incidents by 95%, led cross-team monolith to 
microservices decomposition, and designed an org-wide platform adopted by multiple 
product teams.

SKILLS:
- Languages: Java (primary), Go, Python, SQL, Bash
- Backend: Spring Boot, gRPC, REST, Flask, JUnit, Mockito, event-driven architectures
- Distributed Systems: Kafka, Redis, Elasticsearch, microservices, idempotent workflows
- Data Stores: MySQL, MongoDB, DynamoDB
- Cloud & Infra: AWS (Lambda, EC2, S3, SQS), GCP, Kubernetes, Docker, Jenkins
- Observability: Structured logging, distributed tracing, metrics/alerting, RCA
- Leadership: Design reviews, architecture decision records, mentorship & hiring

EXPERIENCE:
1. Tekion Corp - Senior Software Engineer (Jan 2021 - Present)
   - Technical owner of revenue-critical reporting platform (10K+ monthly submissions)
   - 95% reduction in critical production incidents
   - Led monolith-to-microservices decomposition across multiple teams
   - Designed org-wide PDF generation service (AWS Lambda + Typst + Kafka)
   - Mentor for senior and mid-level engineers

2. Tekion Corp - Software Engineer (Oct 2019 - Dec 2020)
   - Built reporting module with Excel export and parameterized queries
   - Shipped Release Notes / Knowledge Base platform

3. Honestbee - Software Engineer (Jul 2018 - May 2019)
   - Designed payroll computation service ingesting delivery telemetry streams
   - Integrated Stripe and CyberSource payment gateways

4. Iamplus Electronics - Software Engineer (Sep 2015 - Jul 2018)
   - Built voice-enabled conversational services on third-party APIs
   - Introduced caching layers reducing end-to-end latency

EDUCATION: B.Tech, Mathematics & Computing — IIT Guwahati (2011–2015)

KEY METRICS:
- 95% reduction in production incidents
- 10K+ monthly regulated submissions handled
- 80% automated test coverage achieved
- Multiple product teams adopted my platform designs

---

BUILD REQUIREMENTS:

Tech stack: React + Tailwind CSS (single HTML file if possible for simplicity, 
or React with Vite)

Design: Dark theme, minimal and elegant, feels like a senior engineer built it — 
NOT a generic template. Think: clean typography, subtle animations, 
terminal/code aesthetic accents.

Sections to include:
1. Hero — Name, title, one-liner summary, links to GitHub/LinkedIn/Email, 
   and a "Download Resume" button
2. About — 3-4 sentence professional bio written in first person
3. Impact Numbers — Animated counters: 11 years exp, 95% incidents reduced, 
   10K+ submissions/month, 80% test coverage
4. Skills — Grouped by category with icons or tags (Languages, Backend, 
   Distributed Systems, Cloud, Data Stores)
5. Experience — Timeline layout, each role with company, dates, 
   and 3 bullet points of impact
6. Projects / Technical Highlights — Cards for: 
   (a) Revenue-Critical Reporting Platform, 
   (b) Monolith-to-Microservices Migration, 
   (c) Org-wide PDF Generation Service
7. Education — IIT Guwahati, B.Tech Math & Computing
8. Contact — Email link, LinkedIn, GitHub

Extra polish:
- Smooth scroll navigation
- Mobile responsive
- Subtle hover effects on cards
- A small terminal-style blinking cursor on the hero section tagline
- Meta tags for SEO (name, description, og:title)

After building, also tell me how to deploy it to Vercel for free.