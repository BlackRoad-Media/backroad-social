# BackRoad Social Roadmap

## Phase 1: Core (Months 1-3)
- [RC] Post system with 3-hour delay and edit window
- [RC] Chronological feed from connections (no algorithm)
- [RC] Mutual connection model (no follower/following)
- [RC] Warmth (private appreciation, no visible counts)
- [RC] Finite scroll — feed has an end
- [RC] Basic depth scoring — NLP quality assessment
- [RC] User auth — email + GitHub/Google OAuth
- [RC] PostgreSQL schema — multi-tenant, privacy-first
- [RC] Zero-fill deletion for all ephemeral content
- **Milestone**: Internal alpha with 50 invited users

## Phase 2: Campfires + Moderation (Months 4-6)
- [RC] Campfire rooms — 12 people, 12-hour TTL, memory-only
- [RC] Campfire scheduling + invitations
- [RC] Daily digest — one notification per day max
- [RC] Community moderation — host system, transparent standards
- [RC] Anti-re-engagement — zero FOMO notifications
- [RC] Block, mute, and report flow
- [RC] Media support — images, video (no autoplay)
- [RC] Export system — JSON, Markdown
- **Milestone**: Closed beta with 500 users

## Phase 3: Creator Economics (Months 7-9)
- [RC] Creator subscriptions — recurring payments, 90/10 split
- [RC] Tipping — zero fee to creators
- [RC] Exclusive content gating
- [RC] Creator dashboard — revenue, analytics, payouts
- [RC] Weekly payouts — no minimum threshold
- [RC] Business profiles — $49/mo, ethical visibility
- [RC] Mobile apps — iOS + Android (native, not web wrapper)
- [RC] Accessibility — WCAG 2.2 AA compliance
- **Milestone**: Open beta, creator monetization live

## Phase 4: Federation + Scale (Months 10-12)
- [RC] ActivityPub federation — Mastodon/Pleroma interop
- [RC] Self-hosting Docker image + docs
- [RC] Federation protocol for private instances
- [RC] i18n — 5 languages
- [RC] E2E encrypted direct messages
- [RC] Long-form post support
- [RC] Advanced depth scoring — conversation quality, curiosity signals
- [RC] API for third-party clients
- **Milestone**: Public launch, federation live, 5K users

## Phase 5: Growth (Year 2)
- [RC] Desktop app (Tauri)
- [RC] Community themes for self-hosted
- [RC] Reading mode — typography-optimized
- [RC] Invite system — grow through depth
- [RC] Institutional accounts — schools, nonprofits
- [RC] Research partnerships — social media and mental health
- [RC] Moderation tools — AI-assisted (opt-in for hosts)
- **Milestone**: 50K users, federation with 20+ instances

## Revenue Model
| Source | Monthly | Notes |
|--------|---------|-------|
| Business profiles | $49/mo each | Ethical visibility, no ads |
| Creator commission | 10% of creator revenue | 90% goes to creators |
| Self-hosted support | $199/mo | SLA, updates, federation config |
| Grants + donations | Variable | Aligned with mission |

## Key Metrics (What We Track)
- **Depth score distribution** (are conversations getting deeper?)
- **Campfire completion rate** (do rooms last their full 12 hours?)
- **Export requests** (are people comfortable with data portability?)
- **Creator payout volume** (is money flowing to creators?)
- **NOT tracking**: DAU, time-on-app, session length, engagement rate
