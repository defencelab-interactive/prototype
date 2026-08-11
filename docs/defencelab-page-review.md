# Review of the homepage in progress

Six blocks: hero · trusted by / geography · three moments · core services · products carousel · why teams switch · process · trust & governance.

---

## What's already solved — and where my earlier proposals are now redundant

| Their block | Replaces |
|---|---|
| **Hero proof chips** (SLA-backed, 24/7, senior engineers only, works with your existing stack) | The proof strip I proposed. Theirs is lighter and reads better. |
| **Geography + verticals** (US, Europe · FinTech, SaaS, Healthcare, Legal) | The narrowing I argued for. Positioning is no longer "everyone". |
| **Three moments** (scaling product · known gaps · incident pressure) | The Crisis / Gap / Pressure cards. Same logic, arrived at independently. |
| **Why teams switch** | The Trust block I proposed building from scratch. Theirs is stronger — stated as differences rather than promises. *Withdrawing my version.* |
| **Trust & Governance** (least privilege, time-bound access, traceability) | The confidentiality position. Already there. |
| **Process, 5 steps** | The "how we work" block. Already there. |

The structural argument is settled: entry by situation, then services, then proof. No need to relitigate it.

---

## Their model vs the six phases — both are needed

Their process: define scope → assess & prioritise → implement & enable → monitor & respond → report & improve.

| Their step | Phase |
|---|---|
| define scope & goals · report & improve | Govern |
| assess & prioritise risk | Identify |
| implement & enable controls | Protect |
| monitor & respond | **Detect + Respond, merged** |
| — | **Recover, absent** |

These aren't competing. Their five steps describe **how an engagement runs**. The six phases describe **what has to be covered**. One answers "how do you work", the other answers "what am I missing".

Keep the process block as is. The coverage question is what the self-check answers, and it has no home on this page yet.

**Two consequences of the merge and the omission:**

- **Detect and Respond merged into one step.** Two different states of the business: one sells as a subscription, one as an urgent call-out. Someone mid-incident should not land on a monitoring step.
- **Recover is absent from the entire page** — not in the six services, not in the five steps. Case 5 is delivered evidence of exactly this work. Recovery after an incident is currently promised nowhere.

---

## Issues, by weight

### 1 · "24/7 monitored coverage" and "SLA-backed response times" are in the hero

These are the two claims that were unconfirmed through every document. They now sit in the most prominent position on the site. If on-call exists, the question is closed and the Crisis path can finally state a response time. If it's aspirational, it will be tested on the first call.

### 2 · "fish attack" is a typo, next to "phish guard"

Two products whose names differ by one letter, one of which is misspelled. From the one-pagers these are genuinely different things — one simulates phishing against employees, the other analyses inbound mail and acts on it. If they're two products, the names need to diverge further than a single letter. If they're one, one name goes.

Decided earlier: **PhishAttack**.

### 3 · PhishAttack's actual differentiator is missing

The one-pager's core claim is real adversary-in-the-middle capture that defeats MFA — the question awareness suites can't answer. The carousel copy says "simulate real phishing scenarios… not just awareness metrics", which describes every phishing simulator on the market.

This is the most expensive loss on the page: a genuinely rare capability described generically.

### 4 · Incident pressure routes to MDR/MXDR

MDR is monitoring. Someone who says *something happened and I need control now* needs a phone number and a response time, not a subscription to being watched. This is the highest-traffic entry per the team's own account of inbound.

### 5 · Compliance has services but no entry point

The navigation offers compliance, and three frameworks are delivered — ISO 27001, SOC 2, GDPR. None of the three moments is the one where an outside party sets the date: a customer's questionnaire holding up a contract, investors wanting evidence before a round closes, a licence requiring an audit.

This isn't a proposal for a new direction. The direction exists and is already sold; what's missing is the way in. Of the four triggers, this is the one with the hardest deadline and the clearest budget, because the date isn't the buyer's to move.

Worth raising as a question rather than a fourth card: was it left out deliberately, or did it fall through? Folding it into *Known gaps* is possible, but the deadline — the thing that makes it urgent — disappears in the process.

### 6 · Missing from the page entirely

- **Physical & office security assessment** — tailgating, access control, office network. Delivered work, own reporting portal, named methodology.
- **MacBook Audit** — macOS compromise assessment, forensic-grade.
- **Audit Portal** — cross-engagement deltas.

Human risk is represented (phishing, training, behaviour analytics). The front door and the unmanaged laptop are not. Those two plus the inbox are the distinctive combination — the ways in that nobody else tests.

### 7 · "Six engagements that connect" doesn't show the connection

The heading promises connection from a one-time baseline to a continuous owned function. The six cards are product lines, not a sequence, and nothing shows how one leads to the next. Either show the connection or drop the word.

---

## Small fixes

- **Numbering error:** the second and third cards under "three moments" are both `/ 02`.
- `before  attackers do` — double space.
- Eyebrow case is inconsistent: `Products`, `Process`, `Why teams switch` in sentence case, `Trust & Governance` in caps.
- Brand names in lowercase (`devshield`, `fish attack`) — house style elsewhere is lowercase, but product names usually keep their capitalisation.
- Carousel: `explore →` as a link in the tile, `explore` as a button when open. Pick one.
- Four carousel dots with no labels — the reader can't tell what's next.
- The shield at the centre of the process diagram reads as decoration. If it means something, label it.

---

## The proportion worth discussing

Four of the six content blocks are about Defence Lab — geography, why teams switch, process, trust. Two are about what the visitor gets — services and products.

For a cold visitor comparing vendors, that's a reasonable ratio. For someone mid-incident it isn't: the page asks him to read about your qualities before it tells him what to do. That's an argument for the incident path leaving the page early — a persistent phone number or a dedicated route — rather than for restructuring anything.

---

## Documents are out of sync

The PhishAttack one-pager lists the learner-facing LMS as in development; it now exists. One-pager contacts are marked `team to confirm`. Anyone writing copy from these will keep hitting this.

Cheap fix: one line per product from the team on what's live now — not a rewrite, just what has changed since the one-pagers were written.
