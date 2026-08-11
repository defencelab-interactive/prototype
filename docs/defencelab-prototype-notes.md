# Prototype notes

Two parts: what was changed, and what needs answers before any of it ships.

**Live:** https://defencelab-interactive.github.io/prototype/
**Source:** https://github.com/defencelab-interactive/prototype

| Page | |
|---|---|
| `/` | Homepage — the team's structure and palette with revised copy |
| `/services.html` | Services page — six phases as an accordion, 25 services |
| `/three-moments.html` | Three-moments block in isolation, for copy review |
| `/services-block.html` | Core-services block with a text-fit readout |
| `/alt-light-concept.html` | Earlier standalone concept, includes a working coverage self-check |

---

# Part 1 — What changed

## Corrections

**Numbering.** The three moments were 01 / 02 / 02.

**Incident no longer routes to MDR.** MDR is monitoring; someone mid-incident needs a person and a response time, not a subscription to being watched. The third card and the closing CTA now go to a direct route, marked in red as the only urgent action on the page.

**"fish attack" corrected to PhishAttack**, and its actual differentiator restored — phishing that gets past MFA, which is the one thing awareness suites cannot do. The previous copy described a generic simulator, which loses the only claim separating it from KnowBe4.

**Small fixes.** Eyebrow capitalisation made consistent, the double space in "before  attackers" removed, product names capitalised while the rest of the house style stays lowercase.

## Copy

**Service copy rewritten for non-specialists.** Names kept exactly as they were — `mdr / mxdr`, `vciso`, `devshield` — because buyers search for those terms. The plain line under each name, the description and the tags carry the explanation instead. *Posture, hardening, containment, framework mapping, behaviour analytics* are gone from reader-facing text.

**Tone flattened across the whole page.** Three habits removed: clipped three-beat sentences ("Printers vanish. Screen sharing dies."), the not-X-but-Y construction ("Not a technical gap — a compliance gap"), and aphorisms ("A report ages the day it is written"). Around forty rewrites. Short lines were kept only where they carry a result rather than a rhythm — "Not one user was disconnected" stays.

Worth passing back to whoever wrote the case document: the clipped style came from there, and for the site a level tone reads better.

**Stage labels moved inside the service cards.** They were above the columns, but with a 3×2 grid a column label covers cards 1 and 4, so *Start here* was sitting over both the posture assessment and the vCISO. Each card now carries its own: **one-off** for the assessment and the pentest, **programme** for DevShield, **ongoing** for MDR, vCISO and human risk. Two, one and three — not the 2/2/2 the column labels forced.

The section sub-heading now states that split, which is also the answer to "six engagements that connect".

**Process steps expanded** with a plain line under each title. Step 04 now says monitoring and responding are two different jobs; step 05 that fixes feed back into hardening.

**"We speak the language of business" placed as a difference, not a breadth claim.** It replaced *outcome-driven, not checkbox-based* in Why teams switch — a line every competitor uses. The replacement is evidenced: both product one-pagers already deliver Exec and Analyst views from one dataset.

This is about how the work is explained, not about serving every kind of business. The page keeps its focus on growing product companies, which is worth guarding — this phrasing drifts back toward "no limit approach" easily.

**Why teams switch balanced.** All six cells now carry substance from the source documents rather than five slogans and one paragraph.

**Trust block expanded** from the cleared case document: read-only client accounts, handover documentation, self-hosted data custody. All three were already true and already differentiating.

## Cases

**All six added, each expandable.** The collapsed card carries the situation and the outcome figure, so it reads as evidence even unopened. Opening it reveals what that meant, what was built, what changed, and the takeaway.

An open card spans the full row and reads across three columns, aligned to the same grid as its header, with dividers between them. Only one opens at a time, so the grid never fragments. Card heights are equalised within a row and the outcome figure sits on a common baseline, so the numbers can be compared across all six at a glance.

Every fact comes from the document marked cleared for prospects: twelve segments, 88 percent memory, 1,310 connections and 380 Mbps, 24 switches, 30-day retention, nobody disconnected.

**Tagged to match the moments above.** The shared-password case sits under *Known gaps*, whose headline uses that client's own words, so a reader who recognised himself at the top of the page finds out below how it ended for someone in the same position.

**No menu item added.** Six cases fit in one block and are all there is; a menu entry makes sense for a library that grows. Worth doing instead: give each case its own URL so it can be sent in a deal thread and indexed, and link cases from the relevant service pages.

## Layout

Content width matched to the design at roughly 92% of the viewport, capped at 1680px, with 24px gaps and the nav pill inset. Section headings centred and capped so they wrap rather than running the full width. Body copy inside cards capped at 44–46 characters a line, since three cards at this width would otherwise produce unreadably long lines.

## On the interactive block

The consultant's item 4 — an interactive risk block showing what percentage of businesses have similar problems — is now largely answered by the case studies, which let a reader pick the situation closest to his own and see the detail. Statistics would add less than delivered work does.

Two things still worth building, in this order:

**A filter over the cases** by moment: all / scaling product / known gaps / incident pressure / compliance. The tags exist and the content exists, so it is a few hours' work. It connects the three moments at the top to the proof at the bottom — and it will make visible that *incident pressure* has no case behind it, which is a conversation to have rather than a gap to hide.

**A scope picker**, answering the question the closing CTA already asks. Four or five questions — what prompted the search, whether there is anyone internal, whether there is an external deadline, how many people — returning a combination of the six services with their stage labels and an order to do them in. Not a risk score.

The second only works once the team has answered on engagement model and entry price. Without those, the result screen can only say "book a consultation", which is the button next to it.

---

# Part 2 — Questions for the team

Ordered by what blocks the most.

## 1 · Is there on-call, and what is the response time?

`24/7 monitored coverage` and `sla-backed response times` are in the hero and in the MDR card, left exactly as written. Neither appears anywhere in the source material.

They are also unusually easy to test. On a first call a prospect asks some version of *if this happens at two on a Saturday morning, who picks up, and how long before someone is working on it?* If the honest answer is "we'd see it Monday", the claim doesn't just fail — it takes the credibility of the rest of the page with it, because it was in the first thing they read.

What makes it solid: who is on call and on what rota, which hours are actually covered, the response time committed to in writing, and what happens when it is missed.

## 2 · Is there a case that covers an incident?

All six cleared cases are outgrown infrastructure, a compliance review, or expansion. By the team's own account most clients arrive after something has gone wrong, so the card with the most traffic is the one with nothing behind it.

Incident cases are genuinely harder to publish — a client who was breached rarely wants it described, and the details that make it convincing are often the ones that identify them. So there are two routes:

- publish one anonymised case, same treatment as the six existing ones;
- or prove the capability without a client: describe the first hours as a process — who is called, in what order, what is preserved and how, what the client has by the end of day one — and name the evidence standards used. Weaker than a real case, much stronger than nothing, and needs nobody's permission.

## 3 · Do you get a client back into operation after an incident?

Nothing on the page offers restoration: deciding what comes back online and in what order, restoring from backups, confirming the restored systems are clean, writing the account an insurer or regulator asks for. The six services stop at detection and response, and the five process steps end at reporting.

The capability shows in case 5 on the preventive side — a spare firewall genuinely ready, a failure caught as a trend, a known fault engineered out. Either answer is fine, but the site currently implies neither, and someone mid-incident is asking precisely this.

## 4 · Should compliance have a way in?

"A way in" means a place on the page where a particular visitor recognises his own situation. The three moments do that for three kinds of visitor; a fourth isn't represented — the one who didn't choose the timing.

That is the person whose customer sent a security questionnaire now holding up a signed contract, or whose investors want evidence of controls before the round closes, or who needs an audit for a licence and has never been through one.

ISO 27001, SOC 2 and GDPR are all offered, so this is not a proposal for a new service line, only for a way in. It is also the most commercially attractive of the four triggers: the deadline was set by someone else and cannot be moved, and the budget usually exists because the contract or the round depends on it.

Left as a question in case the omission was deliberate.

## 5 · Why are two products absent?

Both have finished one-pagers and neither is anywhere on the site:

- **MacBook Audit** — establishes whether personal, unmanaged Macs are already compromised rather than merely badly configured, with evidence that holds up to being questioned.
- **Audit Portal** — the reporting side of the physical and office assessments, publishing findings as a portal that shows on the next visit what was fixed, what stayed and what came back.

Held back on purpose, sold only through relationships, or simply not on the page yet?

The second matters twice over. Physical and office security — going to a client's offices and getting in past the front desk — is missing from the entire site, despite being delivered work with a named methodology behind it (PTES, NIST SP 800-115, OWASP WSTG, OWASP Wireless, MITRE ATT&CK). It is also part of what may be the most distinctive thing about the offering: three ways in that almost nobody else tests — the front door, the inbox, and the laptop nobody manages. Two of the three are currently invisible.

## 6 · Is there app-sec work that can be published?

The cases are network and infrastructure work: firewalls, segmentation, wireless, switching. The page positions to growing product companies, and half the offering is application-side — DevShield, DevSecOps, product security, application penetration testing.

Both are true, but a CTO at a product company reads six network stories and may quietly conclude the application work is newer or thinner.

If no such project can be published, the alternative is to claim less on the application side rather than leave the strongest part of the site not covering it.

## 7 · What is the entry point, and what does a retainer include?

Neither exists anywhere on the site. Two of the product one-pagers carry price anchors, so the team clearly can price things — it just hasn't been written down for the services.

Needed: minimum engagement or entry price, minimum term, what a retainer covers in hours and coverage window, and what falls outside scope. This is also what unblocks the scope picker described above.

## 8 · Which product names are final?

- `PhishGuard` in the menu against `PhishAttack` in the one-pager — decided as **PhishAttack**, so the menu item needs renaming. Because the name states an offensive action, the authorised-testing frame belongs at the top of that page rather than the bottom: written rules of engagement, Awareness Mode credential blocking on by default, self-hosted data custody. That is what makes the page forwardable to legal and HR.
- `fish attack` and `phish guard` differ by one letter and appear to be different products. If they are, the names need to diverge further.
- `Cybersecurity Awareness` in Solutions and `Sec awareness` in Products look like the same offering listed twice.
- `DevShield`, `DevSecOps Services` and `Product security` overlap heavily. One offering, or three clearly differentiated?
- `SafePresso LMS` appears in a one-pager and nowhere on the site.
- `contact@` in one one-pager, `sales@ [team to confirm]` in another. One confirmed address.
- Languages differ between documents: EN/ES for the guest portal, EN/RU for the awareness assessment. Which are supported as standard rather than built for one client?

## 9 · Free tool naming

The hero's `free security health check` links to `#` and carries the same name as the paid Security Health Check service. A visitor who takes the free one reasonably concludes he has had the service. The free tool needs a different name; the two are unrelated and should not be positioned as lite and full versions of each other.

## 10 · Are AML and MiCA a real direction?

The blog plan leads with a GDPR/AML/MiCA digest. AML and MiCA are financial regulation rather than security frameworks, and nothing in the current offering covers them. Either there is a fintech direction worth knowing about, or they were written in by habit — the answer changes both the rubrics and the positioning.

## 11 · Can the one-pagers be brought up to date?

The PhishAttack one-pager lists the learner-facing LMS as in development; it exists. Contacts are marked `team to confirm`. Anyone writing copy from these inherits the errors, and it undercuts the strongest thing in that document — the honest-scope section, which only carries weight while it is accurate.

One line per product from whoever owns it, saying what is live today. Not a rewrite.

---

# Placeholders in the prototype

**Art.** The hero mark and the geography graphic stand in for the real 3D asset and map. The avatar bubble was removed — it was a Figma comment, not a design element.

**Type.** Plus Jakarta Sans stands in for what looks like a paid geometric face (Sofia Pro or Gilroy).

**Footer entity details.** Registered legal name, address, company number and VAT are bracketed and need real data. Several EU jurisdictions require these on the site itself rather than on request.

**Legal set.** Privacy policy, cookie policy with a working settings control, terms, DPA, sub-processor list, responsible disclosure and security.txt are all linked but empty. Two matter more than usual here: a DPA and sub-processor list, because PhishAttack processes employee behavioural data and MacBook Audit collects evidence from personal laptops; and a disclosure policy, because buyers expect a security vendor to have one.

Not legal advice — exact obligations depend on where the entity is registered, and a cookie banner will be needed if analytics are added.
