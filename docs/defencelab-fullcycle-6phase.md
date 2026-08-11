# Full-cycle security management — block spec

Six phases, aligned to NIST CSF 2.0. Replaces the current four-column static block.

`[brackets]` = to confirm with the team before publication.

---

## Intro copy

Placed above the cycle.

> Security work usually arrives in pieces. One company tests your systems and sends a report. Another sells you a tool and a licence. A third appears when something has already gone wrong. Each piece is fine on its own, but the space between them belongs to nobody — and that's where problems sit unnoticed.
>
> Full-cycle means one team stays with you through all of it. We find out what you have and where it's weak, fix it, watch it continuously, and handle it when something does happen. What we learn then goes back into how you're protected next. It's a loop that keeps running, not a project with a delivery date.
>
> The cycle isn't something we invented — it's the structure international security standards use. What we add is that all six parts of it are ours to run, not split between four suppliers.
>
> You don't have to start at the beginning. Most companies come to us in the middle — during an incident, or a month before an audit — and we pick up from wherever that is.

**Coverage line, under the cycle:**

> We cover every phase of the cycle. Where the work calls for specialist tooling or a certified auditor, we bring in the vendor or partner and stay accountable for the result.
>
> `[Confirm: which phases involve partners, and at what level.]`

**Standards line, small, near the cycle:**

> Our service structure follows the NIST Cybersecurity Framework 2.0. `[Confirm before publishing.]`

---

## The six phases

Phase names follow NIST CSF 2.0. Plain-language subtitles sit beneath each name for readers who don't know the framework.

### Govern
*Who owns security, and how you prove it*

Security policy and documentation · risk assessment and register · control ownership and accountability · compliance framework mapping · third-party and vendor risk governance · board and auditor reporting · security awareness programme

### Identify
*What you have, and where it's weak*

Asset and attack-surface inventory · vulnerability assessment · penetration testing · security posture and gap assessment · compliance readiness assessment · third-party risk review

### Protect
*Closing the gaps and keeping them closed*

Hardening and configuration baselines · identity and privileged access · endpoint and email protection · network segmentation · patch and vulnerability management · backup and recovery design · secure development and code review · security training

### Detect
*Someone watching, continuously*

Log collection and SIEM · continuous monitoring `[coverage hours]` · EDR/XDR management · threat hunting · anomaly and AI-assisted detection · alert triage · threat intelligence

### Respond
*When something happens*

Incident response retainer · containment and forensics · malware analysis · regulatory and customer notification support · tabletop exercises and IR planning

### Recover
*Getting back to work, and not repeating it*

Business continuity and disaster recovery planning · backup validation and restore testing · system and service restoration · post-incident review and reporting · control improvements fed back into Protect

`[Confirm per service: in-house / partner / not offered.]`

---

## Vendor layer

Each phase names the vendor technologies you operate in it. Doubles as the destination for the `Vendors` nav item.

`[Which vendors, in which phases, at which partner level.]`

---

## Presentation options

### Option 1 — Canonical loop

Govern at the centre, the other five as a ring around it, matching NIST's own diagram. Clicking a phase opens its service list and vendor set.

Entry tags on the ring: **Crisis → Respond** · **Gap → Protect + Detect** · **Pressure → Govern + Identify**

Needs: nothing beyond the service lists above.

### Option 2 — Depth control

Each phase carries a three-level control: *advisory* / *co-managed* / *fully managed*. The reader sets the depth he wants per phase and sees what that includes. The assembled scope can be sent through a form.

Needs: what each of the three levels means at your end, per phase.

### Option 3 — Entry-path walkthrough

The reader picks Crisis, Gap or Pressure. The cycle animates his route: where he enters, what happens in the first days, what continues after.

Needs: typical first-week sequence for each entry path.

**Recommended:** Option 1 for release, Option 2 layered on once the depth levels are defined. Option 3 if the release date is at risk.

---

## Behaviour

- Default state shows all six phases and the full service breadth. Nothing important sits behind a click.
- Content must differ meaningfully between states, otherwise use a plain list instead.
- Mobile: vertical stack, control pinned above. The ring does not survive a phone screen.
- Service names with a destination page link to it. The rest stay as plain text until pages exist.
