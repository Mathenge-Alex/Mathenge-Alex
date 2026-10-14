# Alex Maina

**Software engineer · Nairobi, Kenya**

I design, build and run production software for Kenyan businesses: workshops, lenders, audit firms and
schools. I take a system from the first conversation with the client to the day it runs their operations, and
I stay with it after: hosting, security, backups, monitoring and support. You can find my work at
[ilexdigital.com](https://ilexdigital.com).

## What I build

| System | What it does |
|---|---|
| **Fundibase** | Workshop, store and fleet management for garages and truck-body builders. It covers job cards with live progress, an append-only stock ledger across sites, tool tracking, materials planning and purchasing. Labour costing, invoicing, M-Pesa reconciliation, fleet contracts and client SMS/WhatsApp are optional modules. Several garages share each server, each fully isolated, and one command-line tool runs them all |
| **Auditrix** | Practice management for audit and accounting firms: a job board, a review pipeline, a hash-chained audit trail, multi-tenant data isolation and verified incremental backups |
| **Farm credit platform** | Loan management for a licensed lender: interest accrual, repayments, role-based access, a full audit trail, health monitoring with alerts, and nightly off-site backups. Built to Kenyan compliance requirements |
| **Octobook** | Booking, scheduling and follow-up for professionals. Multi-tenant SaaS with a schema per subscriber |
| **BIOS** | School attendance from ZKTeco biometric devices, with SMS to parents |
| **ilex-deploy** | Internal platform: one-command test deployments of any project to a shared server (Docker, Caddy), with guard rails that keep production systems out of reach |

The code for client systems and products is private. I'm happy to give a walkthrough or a live demo.

## How I work

- **Production first.** Everything I ship has:
  - automated tests on SQLite and PostgreSQL;
  - deployment checks;
  - two-factor sign-in;
  - an audit log that cannot be edited;
  - verified nightly backups with an off-site copy;
  - health monitoring.
- **Measured, not guessed.** I load-test against a year of simulated data before advising on hosting, and I
  keep the numbers.
- **Kenya-first.** M-Pesa (Daraja: STK push, C2B, statement reconciliation), SMS and WhatsApp
  notifications, KRA details on documents, and the Data Protection Act 2019.
- **Owned end to end.** Every system comes with clear documentation, an operator runbook, and contracts and
  SLAs that say what the client can rely on.

## Stack

**Backend:** Python, Django, Django REST Framework, PostgreSQL, Celery/Redis when it earns its place.
**Frontend:** HTMX, Tailwind CSS, JavaScript/TypeScript, React where a rich client is needed.
**Infrastructure:** Linux (Ubuntu), nginx, gunicorn, systemd, Docker, Caddy, Let's Encrypt, fail2ban, Bash.
**Integrations:**
- M-Pesa Daraja;
- Africa's Talking (SMS);
- WhatsApp Business;
- ZKTeco biometric devices;
- SMTP;
- PDF and Excel generation.

## Contact

[ilexdigital.com](https://ilexdigital.com) · [LinkedIn](https://www.linkedin.com/in/alex-m-maina/) ·
[X / Twitter](https://x.com/MainaAlexM) · [arxmaina@gmail.com](mailto:arxmaina@gmail.com)

Open to building systems for businesses that need software they can depend on.
