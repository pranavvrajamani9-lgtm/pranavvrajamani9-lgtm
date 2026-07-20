# Pranavv Rajamani

### Full-Stack Developer · Product Engineer · Founder

I lead product design and implementation across web, mobile, data, and go-to-market workflows. I focus on systems that must be understandable to nontechnical operators while remaining rigorous about tenancy, privacy, failure handling, and operational correctness.

## Engineering focus

- TypeScript across Next.js and React Native/Expo applications
- Supabase/Postgres data models, row-level security, role-aware workflows, and auditability
- Production-oriented API design: idempotency, validation, bounded retries, provider reconciliation, and fail-closed behavior
- Automated quality gates with Playwright, TypeScript, linting, accessibility checks, and deployment preflights
- End-to-end product ownership from discovery through implementation, instrumentation, launch planning, and sales enablement

## Delivery discipline

I build beyond the interface. The systems below are designed around explicit access boundaries, deterministic state changes, recoverable failure modes, and repeatable validation—not just happy-path demos.

- Tenant-scoped data access, role-aware permissions, and protected administrative actions
- Input validation, idempotency, audit trails, and reconciliation for external-provider workflows
- Automated browser/mobile checks, static analysis, production builds, and deployment-readiness gates
- Clear separation between local/demo behavior and production-only credentials, billing, and provider actions

## Representative engineering evidence

- **Program Command Center:** a multi-tenant release with ordered database migrations, rollback fixtures, append-only evidence, tenant safety checks, and a 453-test Playwright verification suite.
- **Hoop Nest:** mobile end-to-end flows for director, coach, parent, team, event, attendance, feed, and chat workflows, alongside protected organization/team access boundaries.
- **SignalDesk:** source-integrity, quota, recovery, and provider-outage checks that preserve uncertainty instead of fabricating research output.
- **Outreach Research Engine:** a 100-test browser suite covering evidence gates, import/export safety, static-output integrity, and security headers.
- **Dial AI:** CI-backed lint/build validation, local demo fallbacks, server-side integration boundaries, and a reviewed maintenance workflow for dependency updates.

## Selected systems

### Hoop Nest — mobile operations platform

A mobile product for youth sports organizations and families, covering identity, organization/team access, onboarding, event workflows, attendance, communication, and parent-facing operations.

**Technical scope:** React Native, Expo, TypeScript, Supabase, role-aware access controls, mobile end-to-end test flows.

### Hoop Nest Program Command Center — acquisition and conversion platform

A multi-tenant operating system for program growth: campaign setup, attribution, parent signup, lead normalization, conversion evidence, reporting, creative approval, and controlled provider integrations.

**Technical scope:** Next.js, TypeScript, Supabase/Postgres, row-level security, append-only evidence, idempotent mutations, Playwright, Vercel, and guarded Meta/Resend integration boundaries.

### SignalDesk — evidence-first research workspace

A research workspace for public-company analysis that preserves source provenance, uncertainty, counterarguments, and scenario assumptions rather than presenting unsupported investment conclusions.

**Technical scope:** Next.js, TypeScript, source-integrity controls, quota-aware provider handling, security headers, and research-data quality gates.

### Outreach Research Engine — verified outreach preparation

A source-backed workflow for discovering companies, reviewing public evidence, enforcing outreach-readiness criteria, and producing structured discovery-call drafts without promoting unverified information to send-ready status.

**Technical scope:** Cloudflare Workers, JavaScript, Playwright, static-build verification, CSP/security headers, import sanitization, and browser-storage resilience.

### Dial AI — sales conversation coaching

An AI-assisted practice environment for improving cold-call structure, sales communication, and conversation review.

**Technical scope:** AI product design, sales enablement workflows, and conversational feedback systems.

## Working principles

- Model the real workflow before automating it.
- Keep privileged actions explicit, traceable, and reversible where possible.
- Treat external-provider failures as states to reconcile, not reasons to blindly retry.
- Use tests and operational checks as part of product design, not as an afterthought.
- Build systems that help operators make informed decisions instead of hiding uncertainty.

## Portfolio note

The underlying products remain private by design. This profile documents their engineering scope without publishing client data, credentials, internal operating procedures, or proprietary source code. Technical walkthroughs and demos are available on request.
