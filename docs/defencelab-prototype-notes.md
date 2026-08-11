# Prototype notes — what changed and what's outstanding

Companion to `defencelab-homepage-full.html`.

---

## Corrections

**Numbering.** The three moments were 01 / 02 / 02.

**Incident no longer routes to MDR.** MDR is monitoring; someone mid-incident needs a person and a response time, not a subscription to being watched. The third card and the closing CTA now go to a direct route, marked in red as the only urgent action on the page.

**"fish attack" corrected to PhishAttack**, and its real differentiator restored — phishing that defeats MFA, the one thing awareness suites can't do. The previous copy described a generic simulator, which loses the only claim that separates it from KnowBe4.

**Small fixes.** Eyebrow capitalisation made consistent; the double space in "before  attackers" removed; product names capitalised while the rest of the house style stays lowercase.

---

## Copy changes

**Service copy rewritten for non-specialists.** Names kept exactly as they were — `mdr / mxdr`, `vciso`, `devshield` — because buyers search for those terms. The plain line under each name, the description and the tags carry the explanation instead. *Posture, hardening, containment, framework mapping, behaviour analytics* are gone from reader-facing text.

**Start here / Then / Ongoing labels added** above the six services, so the claim that they connect is visible rather than asserted.

**Process steps expanded** with a plain line under each title, so the stages read as work rather than labels. Step 04 now states that monitoring and responding are two different jobs; step 05 that fixes feed back into hardening.

**"We speak the language of business" placed as a difference, not a breadth claim.** It replaces *outcome-driven, not checkbox-based* in Why teams switch — a line every competitor uses. The new cell is evidenced rather than asserted: both product one-pagers already deliver Exec and Analyst views from one dataset, and the cleared case document commits to documentation a different provider could use.

This is about *how the work is explained*, not about serving every kind of business. The page keeps its focus on growing product companies — worth guarding, because this phrasing drifts back toward "no limit approach" easily.

**Why teams switch cells balanced.** All six now carry substance from the source documents rather than five slogans and one paragraph.

**Trust block expanded** from the cleared case document — read-only client accounts, handover documentation, self-hosted data custody. All three were already true and already differentiating.

---

## Cases

**All six added, each expandable.** The collapsed card carries the situation and the outcome number; opening it reveals what that meant, what was built, what changed, and the takeaway. An open card spans the full row and reads across three columns, so nothing is read in a narrow strip. Only one opens at a time, so the grid never fragments.

Every fact is from the document marked cleared for prospects: twelve segments, 88 percent memory, 1,310 connections and 380 Mbps, 24 switches, 30-day retention, nobody disconnected.

**Tagged to match the moments above.** The shared-password case sits under *Known gaps*, whose headline uses that client's own words — a reader who recognised himself at the top of the page finds out below how it ended for someone in the same position.

**No menu item added.** Six cases fit in one block and are all there is; a menu entry makes sense for a library that grows. Worth doing instead: give each case its own URL so it can be sent in a deal thread and indexed, and link cases from the relevant service pages.

---

## Outstanding — for the team

### No case exists for the incident path

All six cleared cases are outgrown infrastructure, a compliance review, or expansion. None is about an incident.

Why that matters: by the team's own account, most clients arrive after something has gone wrong. That person is looking for one thing — evidence that whoever answers the phone has done this before. It's the only card on the page with nothing behind it.

Incident cases are genuinely harder to publish than the others. A client who was breached rarely wants it described, even anonymised, and the details that make the story convincing are often the ones that identify them.

So there are two routes, and the second is worth considering seriously:

- **Publish one anonymised case** — same treatment the six existing ones had, with the client's permission.
- **Prove the capability without a client.** Describe what the first hours look like as a process rather than a story: who is called, in what order, what gets preserved and how, what the client receives at the end of day one. Name the evidence standards used. This is weaker than a real case, but far stronger than the current nothing, and it needs nobody's permission.

### Restoration is promised nowhere

After an incident, somebody has to get the business working again: decide what comes back online and in what order, restore from backups, confirm the restored systems are actually clean, and write the account of what happened that an insurer or a regulator will ask for.

Nothing on the page offers that. The six services stop at detection and response; the five process steps end at reporting.

The odd part is that the capability is demonstrated in the cases. Case 5 is exactly this work on the preventive side — a spare firewall that was genuinely ready rather than merely present, a failure caught as a trend rather than an outage, and a known fault engineered out instead of waited out. Not one user noticed.

Question for the team: after an incident, do you get the client back into operation, or does their own IT do that while you supply the findings? Either answer is fine, but the site currently implies neither, and someone mid-incident is asking precisely this.

### 24/7 coverage and SLA-backed response

Both claims are the team's own and are left on the page exactly as written — nothing here needs confirming before it ships.

What to be aware of: neither appears in any of the source material — not in the one-pagers, not in the case document. And they're unusually easy to test. On a first call a prospect asks some version of *if this happens at two on a Saturday morning, who picks up, and how long before someone is working on it?*

If the honest answer is "we'd see it Monday", the claim doesn't just fail — it costs the credibility of everything else on the page, because it was in the first thing they read.

What makes it solid: who is on call and on what rota, which hours are actually covered, the response time you commit to in writing, and what happens when it's missed. Those four answers turn the boldest claim on the page into the strongest one.

### Compliance has services but no way in

"Entry" here means a place on the page where a particular kind of visitor recognises his own situation and knows which link is his. The three moments do that for three kinds of visitor. A fourth kind isn't represented: the one who didn't choose the timing.

That's the person whose customer sent a security questionnaire that's now holding up a signed contract. Or whose investors want evidence of controls before the round closes. Or who needs an audit for a licence application and has never been through one.

ISO 27001, SOC 2 and GDPR are all offered, so the work exists — this isn't a proposal for a new service line, only for a way in.

It's also the most commercially attractive of the four triggers, for a reason worth stating plainly: the deadline was set by someone else and can't be moved, and the budget usually already exists because the contract or the round depends on it.

Left as a question rather than built as a fourth card, in case its absence was deliberate.

### Two products appear nowhere

Both have finished one-pagers and neither is anywhere on the site:

- **MacBook Audit** — checks whether personal, unmanaged Macs are already compromised, rather than merely badly configured, with evidence that holds up to being questioned.
- **Audit Portal** — the reporting side of the physical and office assessments: findings published as a portal that shows, on the next visit, what was fixed, what stayed and what came back.

Question rather than criticism: held back on purpose, sold only through relationships, or just not on the page yet?

The second one matters twice over. Physical and office security — going to a client's offices and getting in past the front desk — is missing from the whole site, even though it's delivered work with a named methodology behind it (PTES, NIST SP 800-115, OWASP WSTG, OWASP Wireless, MITRE ATT&CK).

It's also part of what is arguably the most distinctive thing about the offering: three ways in that almost nobody else tests — the front door, the inbox, and the laptop nobody manages. Two of those three are currently invisible.

### Proof and promise come from slightly different worlds
The cases are network and infrastructure work — firewalls, segmentation, wireless, switching. The page positions to growing product companies, and half the offering is application-side: DevShield, DevSecOps, product security, application penetration testing.

Both are true, but a CTO at a product company reads six network stories and may quietly conclude that the application work is newer or thinner.

What would close it: one project in application or product security, anonymised and approved by the client for publication — the same treatment the six existing cases already went through. If no such project can be published, the alternative is to claim less on the application side rather than leave the strongest part of the site not covering it.

### Documents are out of sync

The PhishAttack one-pager lists the learner-facing LMS as still in development. It exists. Contact addresses in the one-pagers are marked `team to confirm`, and two documents give different addresses.

The risk isn't the individual errors, it's that anyone writing copy from these documents inherits them — and will either publish something that's out of date or promise something that isn't ready. It also undercuts the strongest thing about the PhishAttack one-pager: its "honest scope" section, which lists plainly what's live, what's in development and what doesn't exist. That section only carries weight while it's accurate.

Cheapest fix: one line per product from whoever owns it, saying what's live today. Not a rewrite of the one-pagers, just a note of what has changed since they were written.

---

## Placeholders in the file

**Art.** The hero mark and the geography graphic are stand-ins for the real 3D asset and map.

**Type.** Plus Jakarta Sans stands in for what looks like a paid geometric face (Sofia Pro or Gilroy). Swap in the real one.

**Footer entity details.** Registered legal name, address, company number and VAT are bracketed and need the real data. Several EU jurisdictions require these on the site itself rather than on request.

**Legal set.** Privacy policy, cookie policy with a working settings control, terms, DPA, sub-processor list, responsible disclosure and security.txt are all linked but empty. Two matter more than usual here: a DPA and sub-processor list, because PhishAttack processes employee behavioural data and MacBook Audit collects evidence from personal laptops; and a disclosure policy, because buyers expect a security vendor to have one.

Not legal advice — exact obligations depend on where the entity is registered, and a cookie banner will also be needed if analytics are added. Worth passing to whoever handles that.
