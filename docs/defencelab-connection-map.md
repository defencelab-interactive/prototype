# Site connection map — v2

Built on what's confirmed to exist: 15 service-menu items, 6 cleared cases, 3 products, physical/office red-team work.

The six phases remain the shared coordinate system. `[brackets]` = to confirm. **(new)** = doesn't exist yet.

---

## Four lines of business

The offering isn't one thing sold one way. Four distinct lines, two audiences, two commercial models.

| Line | What it is | Sold to | Model |
|---|---|---|---|
| **Network & infrastructure** | Firewalls, segmentation, wireless identity, switching, central management | End clients | Project, then ongoing |
| **Compliance readiness** | ISO 27001, SOC 2, GDPR, vCISO | End clients | Project against a deadline |
| **Entry testing** | Physical/office red-team, phishing with MFA bypass, macOS compromise assessment | End clients | Engagement, recurring |
| **Platforms** | PhishAttack, MacBook Audit, Audit Portal as licensed software | MSSPs, red-team firms, consultancies | Licence, self-hosted |

Lines 1–3 are the website's main job. Line 4 is a different audience reached mostly through relationships — it needs a home on the site, not a place in the main funnel.

---

## The positioning that comes out of this

Line 3 is the distinctive one, and it wasn't invented for the hero — it's assembled from work already being done:

- **the front door** — tailgating and physical office assessment
- **the inbox** — phishing that actually defeats MFA
- **the personal laptop** — unmanaged BYOD Macs

Three entry routes almost nobody tests, because everyone tests the network and the applications. Each has both delivered practice and an in-house tool behind it.

This is a better answer to the consultant's "ecosystem / no limit approach" brief than breadth claims: not *we do everything*, but *we test the ways in that don't get tested*.

---

## Sitemap

```
Home
│
├── Solutions                       entry by situation
│   ├── Crisis  → Incident & compromise assessment   (new)
│   ├── Gap     → Managed security                   (new)
│   └── Pressure → Audit & compliance readiness      (new)
│
├── Services                        entry by phase — replaces "Products"
│   ├── Govern     vCISO · ISO 27001 · SOC 2 · GDPR
│   ├── Identify   Security Health Check · Penetration Testing
│   │              · Physical & office assessment    (new page, existing service)
│   │              · Phishing simulation
│   │              · macOS compromise assessment
│   ├── Protect    Segmentation · wireless identity · Cloud & Infra
│   │              · DevSecOps / app-sec  [resolve overlap]
│   │              · Awareness · Managed Security Gate
│   ├── Detect     Security Operations · monitoring
│   ├── Respond    Forensics & compromise assessment  [scope TBC]
│   └── Recover    Resilience & continuity            (new page, evidenced by case 5)
│
├── Compliance                      attached to Govern
│   ├── ISO 27001 · SOC 2 · GDPR — readiness and evidence
│   └── Compliance digest
│
├── Platforms                       (new) — for MSSPs & consultancies
│   ├── PhishAttack
│   ├── MacBook Audit
│   └── Audit Portal
│
├── Coverage check                  (new) — the hero's free tool
│
├── Case studies                    tagged by entry + phases
│
├── Blog                            (new)
│
└── About us
    └── Trust & confidentiality
```

**Three changes to flag with the consultant.** `Products` disappears as a menu item — the branded tools live inside their phase for end clients, and under `Platforms` for the licence audience. `Solutions` and `Services` stay separate but get re-cut: three situations vs six phases, which is what makes the rest navigable. And `Platforms` is new, because two of the three products are sold to a different market entirely.

---

## What links to what

### Hero cards → Solutions pages

| Card | Page | Phases | Evidence available |
|---|---|---|---|
| Crisis | Incident & compromise assessment | Respond, then Recover | Forensics capability; **no cleared case** |
| Gap | Managed security | Protect + Detect | Cases 1, 2, 3, 6 |
| Pressure | Audit & compliance readiness | Govern + Identify | Case 4 |

The asymmetry is the thing to notice: the card for the confirmed demand has the least proof behind it.

### Coverage check → everywhere
Result map links each phase to its Services section. Unowned phases link to the service that would cover them.

**The coverage check does not route into Security Health Check.** That's a separate paid service with its own scope and its own entry, and the free tool must not be positioned as its lite version or its funnel — a visitor who takes the free one should not conclude he has had a version of the paid one. The two share nothing but an unfortunate name overlap, which the rename resolves.

### Full-cycle block → Services
Each hexagon links to `/services#<phase>`. Each service name inside links to its own page once it exists; plain text until then.

### Services section (per phase) → four directions
- **Up:** the phase's place in the cycle, one line
- **Sideways:** the other services in the same phase
- **To evidence:** cases tagged with this phase
- **To capability:** vendors and in-house tools used in this phase

### Cases → entry + phases
Two tags each. The six cleared cases map as: 1 → Protect/Identify/Detect · 2 → Protect · 3 → Protect/Govern · 4 → **Govern** · 5 → **Recover**/Detect · 6 → Protect/Govern.

Case 5 is the only evidence for Recover and should be linked from it directly.

### Compliance → Govern
Not a seventh phase — it's what Govern produces. The page states the readiness/independence split: preparation and evidence are Defence Lab's, the certificate or report comes from an accredited body.

### Platforms → Services, one direction only
Each platform page links back to the service it supports (PhishAttack → phishing simulation, MacBook Audit → compromise assessment, Audit Portal → physical assessment). Services pages do **not** push end clients toward licensing — different audience, and the cross-sell would confuse the main funnel.

### Trust & confidentiality → everywhere
Read-only accounts for the client's own IT and security leads · documentation written for a different provider · self-hosted, no data leaving the client's perimeter · admin access restricted to approved networks · the explicit position that leaving doesn't strand them.

Self-hosting appears in all three product one-pagers. It belongs in Trust as a named position, not as a feature bullet repeated three times.

### Standards → hero proof strip
NIST CSF 2.0 (the cycle) · PTES · NIST SP 800-115 · OWASP WSTG · OWASP Wireless · MITRE ATT&CK (assessment methodology). Checkable, and it earns the "industry standards" line the consultant wanted.

---

## Where the connection would be forced

**Services in two phases.** Awareness is Protect and Govern. Penetration testing is Identify but also tests Protect. Phishing simulation is Identify (it finds who's vulnerable) and Protect (the training closes it). One primary phase, mentioned in the others — assigning by force makes the map inaccurate.

**Solutions pages are not phase pages.** Written for a situation, in the reader's language. They point into phases; they don't reproduce them.

**One explanation of the cycle.** Lives in the full-cycle block, with a one-line version on the coverage check result. Everywhere else references it without re-teaching.

**Platforms stay out of the main funnel.** No fourth hero card. An MSSP audience reached through relationships doesn't justify diluting the message for end clients.

---

## Naming to resolve before build

| Conflict | Note |
|---|---|
| `PhishGuard` (menu) → **`PhishAttack`** | Decided: PhishAttack is the single name. The menu item gets renamed. Because the name states an offensive action, the authorised-testing frame — written rules of engagement, Awareness Mode credential blocking on by default, self-hosted data custody — belongs at the top of the page, above the capability list, not at the bottom. That's what makes the page forwardable to legal and HR. |
| `Security Health Check` (paid service) vs `free security health check` (hero button) | Name collision only — two unrelated things. The free tool becomes **Coverage check**; the paid service keeps its name and its own entry. |
| `Sec awareness` vs `Cybersecurity Awareness` | Same offering, listed twice. |
| `DevShield` / `DevSecOps Services` / `Product security` | Three overlapping app-sec entries. One thing, or three clearly differentiated. |
| `SafePresso LMS` | Appears in a one-pager, nowhere on the site. |
| `contact@` vs `sales@ [team to confirm]` | One confirmed address. |
| Languages: EN/ES (guest portal) vs EN/RU (awareness) | Which are supported as standard vs built for one client. |

---

## What doesn't exist yet

New pages: three Solutions pages, Services (six phase sections), Physical & office assessment, Recover, Platforms (three product pages), Coverage check, Blog.

Existing nav items with no destination: `Solutions`, `Compliance`, `Products`, `Vendors`. The hero's `free security health check` links to `#`.

**Minimum set for release, with every link resolving:** three Solutions pages, one Services page with six sections, Compliance, Trust, Platforms as a single page, two or three cases. Individual service pages, the coverage check and the blog follow — provided nothing links to them first.

---

## Open questions carried forward

- Incident response: is there on-call, and what's the response time? Without it the Crisis card can't state an SLA, and it's the card for the confirmed demand.
- Containment and notification in the first hour — currently the forensics capability is strong and the first hour is undocumented. GDPR's 72-hour clock is the cheapest available link between two things that already exist.
- Any cleared incident case, or any tailgating case that can be anonymised. Physical entry deanonymises more easily than a firewall config, and the write-up must give the outcome, not the method.
- App-sec evidence: none of the six cases covers DevSecOps, product security or pentesting.
- Retainer pricing. Two product one-pagers carry price anchors; the services carry none.
