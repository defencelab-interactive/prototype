# Coverage self-check — spec

Replaces item 4 in the consultant's order. Also the destination for the hero button currently linking to `#`.

Eight questions. Output is a map of which phases of the cycle have an owner and which don't. Same six phases and same vocabulary as the full-cycle block.

---

## Naming

Recommended: **Coverage check** — *which parts of your security have an owner*

Avoid *health check* and *risk assessment*: both promise a diagnosis, and eight self-reported answers don't produce one. The name has to promise exactly what the tool delivers, or the result feels like a bait-and-switch.

---

## Framing shown before the first question

> Eight questions, about two minutes. We're not testing your systems — we're asking who is responsible for what. At the end you'll see which parts of the cycle have a clear owner in your company and which don't.
>
> This is a self-check based on your answers, not an audit. "I'm not sure" is a real answer and worth knowing.

---

## Questions

Each maps to one phase. Answers resolve to **owned**, **partial** or **unowned**. Every question carries an "I'm not sure" option, which resolves to unowned.

**The phase names below are internal mapping for the build. They are never shown next to the questions** — the reader answers eight plain questions about his own company and meets the phase structure for the first time on the result screen.

### 1 · Govern
**Who looks after security day to day?**
- Someone whose job it is
- Someone who does it alongside another role
- An outside company
- Nobody in particular

### 2 · Govern
**If a customer or an investor sent you a security questionnaire tomorrow, who would fill it in?**
- We've done it before and know who does it
- Someone would work it out
- We'd have to find help
- I'm not sure

### 3 · Identify
**Could you produce a list today of every system, service and account the business depends on?**
- Yes, it's maintained
- Roughly, from memory
- No
- I'm not sure

### 4 · Identify
**Do you know which outside suppliers have access to your systems or data?**
- Yes, and it's written down
- Broadly, not documented
- No
- I'm not sure

### 5 · Protect
**When someone leaves the company, how are their access rights removed?**
- From a checklist, verified afterwards
- From memory, by whoever remembers
- It varies
- I'm not sure

### 6 · Detect
**If someone were signing into your systems right now with a stolen password, how would you find out?**
- Someone monitors this and would be alerted
- We have tools that log it, nobody watches them
- We'd find out when something visibly broke
- I'm not sure

### 7 · Respond
**If you learned this afternoon that customer data had leaked, would you know who to call first — inside the company and outside it?**
- Yes, it's written down and people know it
- We'd figure it out quickly
- No
- I'm not sure

### 8 · Recover
**When did you last confirm that a backup actually restores?**
- In the last six months
- Over a year ago
- We have backups but have never tested a restore
- I'm not sure

`[Confirm question 6 and 8 wording against how the team actually talks to prospects.]`

---

## Output logic

**No score, no percentage.** The result is a count of facts: *"four of six phases have a clear owner."* A number out of a hundred implies precision that eight self-reported answers don't have.

**Per phase, one of three states:**

| State | Shown as | Condition |
|---|---|---|
| Owned | named, clear | all questions for the phase answered "owned" |
| Partial | someone does it, nobody owns it | mixed answers |
| Unowned | nobody's job | any "no" / "nobody" / "I'm not sure" |

**Where a phase has two questions** (Govern, Identify), the weaker answer sets the state.

---

## Result screen

**1 · The map.** Six phases in the same layout as the full-cycle block, each in its state. This is the whole point of the exercise and it comes first.

Above it, one self-contained line, so the map makes sense to someone who has never seen the cycle:

> Security work divides into six parts — this is the structure international standards use. Here's how your answers fall across them.

Followed, below the map, by a link onward for anyone meeting the cycle here first:

> `What each of these six involves →` — to the full-cycle section or page

**2 · One line per phase that isn't owned.** Plain language, no consequences, no scare. Format: what this means, then the first step.

Examples:

> **Detect — nobody's job.** You'd learn about a break-in when its effects became visible, which is usually days or weeks later. First step: decide who reads the alerts you already generate.

> **Recover — nobody's job.** Untested backups are common and usually fine, but the first time anyone finds out either way is during an incident. First step: restore one system to a test environment.

> **Govern — someone does it, nobody owns it.** Security decisions get made, but nobody holds the record of what was decided. This is what a customer questionnaire or an audit asks for first. First step: one written owner per area, even if it's the same person for all of them.

**3 · The honest outcome.** If five or six phases are owned:

> Most of your cycle has an owner. That's further along than most companies your size. The gap is in `[phase]`, and it's not urgent — worth a conversation when you get to it.

The tool must be able to say this. `[Confirm the team accepts a result that doesn't produce a lead.]`

**4 · CTA, matched to the outcome:**

| Result | Primary CTA |
|---|---|
| 3+ phases unowned | `Talk through what to cover first` |
| 1–2 unowned | `Ask about that phase` |
| 5–6 owned | `Compliance digest` — no sales CTA |
| Mostly "I'm not sure" | `Walk through it with someone` |

**5 · Email, after the result.** Never before.

> Want this as a document — the phases in priority order, what to ask a supplier for each, and a checklist you can hand to whoever picks it up?

---

## Rules

- Results appear before any email field. A gated result makes the word *free* in the hero button false.
- No statistics. If a comparison is ever added, it must come from a named public source `[Verizon DBIR / IBM / ENISA]` with the year, not from an internal estimate.
- No consequence language. Describe the state, not what could happen.
- Never says or implies "you have been breached" or "you are at risk."
- Answers are not stored against an email unless the person submits one. `[Confirm with the team — this belongs in the trust section too.]`

---

## Entry points and order independence

The self-check cannot assume the reader has seen the full-cycle block. The hero button sits above it, so entering cold is the likely default, not the exception.

**Known entry points:**

| Entry | What the reader knows on arrival |
|---|---|
| Hero button | Nothing about the six phases |
| Full-cycle block | The phases and the services in them |
| Shared or direct link | Nothing at all, possibly not even what the company does |
| Blog article | Varies |
| Gap card | The problem framing, not the cycle |

**Rules that keep it working in any order:**

1. **The questions carry no phase vocabulary.** They're eight plain questions about the reader's own company and work with zero prior context. Nothing to break.
2. **The cycle is explained wherever it appears first.** Both the full-cycle block and the result screen carry their own one-line explanation. Neither depends on the other having been read.
3. **The two explanations are worded differently.** A reader who sees both should not meet the same sentence twice — identical copy in two places reads as a template rather than a page written for him.
4. **The result screen links onward to the cycle**, so arriving cold ends in more context rather than less.
5. **One naming rule everywhere:** standard phase name first, plain-language line directly beneath it. Same pairing, same order, in the block and in the result. This is what makes the map recognisable in either direction.
6. **The self-check page stands alone.** Reached by direct link, it needs its own one-line statement of who Defence Lab is above the framing text. `[One sentence — to write with the hero copy.]`

**Where the self-check is not offered:** the Crisis card and the incident page. Someone in an active incident should not be handed an eight-question form.

---

## Boundary against paid work

The result names which phases have no owner. It does not say whether the owned ones are done well — that requires looking at the systems, which is the paid Identify work. The result screen should say so in one line, so the self-check leads into that service instead of appearing to replace it.

> This tells you where nobody's watching. It doesn't tell you whether what's being watched is configured correctly — that needs someone looking at the systems themselves.
