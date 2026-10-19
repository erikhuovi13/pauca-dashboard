# Spark noon decision memo, Mon Oct 19 2026 (~10:20 AM ET)
Exact figures from `spark/memo-2026-10-19-calc.py` (Decimal, cent-floor like Tally), output in `memo-2026-10-19-calc-out.txt`. The script reproduces Tally A320 exactly ($5.7671 ARDI-kitted, $7.2171 factory, N=15). Every gate is ESTIMATE: ARDI Q1–Q13 rates are VERIFIED-written (Gmail 1a13624ffd4cdd34), but label $8.95, receiving $1.10, fee $1.46 and storage $30 vs $40 are not. Nothing ordered, paid or sent by this memo. This is a recommendation, not a decision.

## Decision (team-level, $0, reversible; owner Oki with Tally; by Wed Oct 21)
**Which gate scores Qstomize's Oct 23 delivered figure (and every coaster quote after it)?** Tally's DEADLINES row for Thu Oct 22 asks exactly this ("$6.23 memo / $5.76 A320"). My Oct 18 memo's $6.23 is stale and should not be used. Today's ARDI answers show the gate depends mostly on **who assembles the sets**, a fact no supplier has written yet.

## New result worth knowing
**Factory-sealed sets are the biggest $0 lever left in the stack: +$1.45/set of gate headroom (+$1.65 if one sealed 8-piece unit per $40 order).** ARDI wrote that kitting is $1.45 per 4-pack and that a two-set order is $1.50 pick + $0.40 extra item "if sets was created before". On the enforced basis (packaging $0.94 fail-closed, N=15, 1 month, $30 storage):

| Who makes the set | Gate per 4-pack set | Per 100 pcs | Headroom over Qstomize's written $3.50 product-only, per 50-set lot |
|---|---:|---:|---:|
| ARDI assembles (today's fail-closed) | **$5.31** | $132.75 | $90.50 |
| Factory ships sealed 4-packs, one SKU | **$6.76** | $169.00 | $163.00 |
| Factory ships one sealed 8-pc unit per order (one pick, no extra item: **UNVERIFIED with ARDI**) | $6.96 | $174.00 | $173.00 |

Two sensitivities move it almost as much. **Storage at ARDI's public $40** (not our $30) cuts each gate by $0.65. A sub-pallet lot is the other: Claude flagged that 50 cork sets are a carton or two, not 15-per-pallet, and at N=50 the gates rise about $1.80. Both need one ARDI line.

## Options
| Option | Cash | What it does | Risk |
|---|---|---|---|
| A. Keep $6.23 (old stack) | $0.00 | Nothing to do | Scores on a superseded stack; overstates ARDI-kitted room by $0.92/set |
| B. Flat fail-closed $5.31 for everything | $0.00 | Simple, safe | Kills factory-sealed quotes that actually clear ($5.31–$6.76 band) |
| **C. Mode-specific gate, fail-closed (recommended)** | **$0.00** | Score each quote on the kitting mode the supplier **writes**; silence = $5.31; the 8-pc $6.96 gate stays out of scoring until ARDI confirms it; the conditional $5.76/$7.21 only after ARDI confirms that the $0.03 poly bag is the whole packaging charge | Needs two lines in two existing threads |

## Recommendation: C, with three asks folded in
1. **Oki, in the existing Qstomize thread (a supplier quote-request email, already a standing-send lane):** do the cork sets ship as sealed retail 4-packs, does sealing or a sealed 8-piece pack change the $3.50 or the MOQ (Claude: sealing often adds cost), and who is the importer of record. The scoring ceilings stay internal and are never quoted to the supplier.
2. **Oki, add two lines to the pending ARDI clarification card (t1142s4565, awaiting Erik's Send):** which storage rate and unit applies to a sub-pallet lot (shelf or bin vs pallet, $30 or $40), and whether a factory-sealed 8-piece unit bills as one $1.50 pick with no extra item. Re-draft it as a card, since the parent sends; don't create a duplicate.
3. **Thursday framing for Erik (Kimi):** this doesn't reopen A/B/C or the moat rule, and my recommendation stays C (waitlist first). If Erik picks B anyway, it should be **conditional**: "B only if Friday's written delivered figure is at or under the gate for the mode Qstomize writes", scored by Tally on Friday. Otherwise B is chosen Thursday on a product-only number, the same gap that is killing felt tomorrow (Claude's strongest objection).

## Payback test (Option B, if it ever runs; 50 sets = 25 two-set orders; contribution = $40 − $1.46 fee − stack − unload/storage at N=50, 1 month)
- ARDI assembles, at the $3.50 floor: $175.00 + $147.15 setup = **$322.15**, recovered at **16/25 orders (64%)**. At the $5.31 gate: $412.65, **20/25 (80%)**.
- Factory-sealed, at the $3.50 floor: $322.15, recovered at **14/25 (56%)**. At the $6.76 gate: $485.15, **21/25 (84%)**.
- Both AIs' point: a lot that only validates if it nearly sells out is a weak demand test. Unsold ARDI-kitted sets also strand their $1.45 kitting fee unless kitting happens in batches (Kimi).

## Kill rule
- Scoring rule: a quote that doesn't state the kitting mode in writing scores at $5.31. If ARDI hasn't answered storage by Fri Oct 23, score at $40 storage too and use the lower result.
- Cork: if Qstomize misses Oct 23 or won't name the importer of record, cork leaves this round (unchanged).
- Felt: dies Tue Oct 20 EOD on Erik's $155.75 line. This memo doesn't move that line.

## Owner
Oki: both asks and the card re-draft. Tally: adopt or amend the rule, countersign, and score Friday's figure. Pip: claims and copy on the Qstomize line. Erik: Thursday A/B/C only (unchanged), and the Send on the ARDI card.

## What slips if delayed
If Qstomize's Oct 23 figure arrives without a kitting mode, it gets scored at $5.31 and keeps only $1.81/set ($90.50/lot) for freight and duty, and a passable quote could fail on paperwork. Each day the ARDI card sits unsent also leaves storage ($0.65/set) and packaging ($0.45/set) open for every quote.

## Tools' opinions (credited)
- **Claude Opus 5.5** (Anthropic API; `/v1/models` top tier opus-5-5; 1,195 in / 2,166 out incl. 1,255 thinking; cost UNVERIFIED): **Adopt, with three changes.** Fail closed on mode, ask whether sealing changes the $3.50, and ask ARDI about shelf/bin storage. Strongest objection: Thursday's call would be made on a product-only number, so B needs the same quote discipline as felt. Model 3–6 months of storage, not 1. Keep the 8-pc gate out of scoring. Flip to reject if the asks become a soft commitment or are used to reopen A/B/C early. Full text: `spark/claude-noon-opinion-2026-10-19.json`.
- **Kimi K3** (Moonshot API, run directly with the Kimi key, not via Oki; first try spent all 8,000 tokens on reasoning and is kept as `-try1-truncated.json`; rerun 885 in / 4,158 out incl. 3,616 reasoning; cost UNVERIFIED): **Change.** Polishing the gate keeps a no-moat option alive, so frame any B as a paid demand test, made conditional on Friday's figure. Kimi also flagged the stranded kitting fee and the missing $147.15 breakdown. Two Kimi points don't hold. Postage and payment fees *are* in the stack (label $8.95 and fee $1.46). N=50 raising the gate is correct, not backwards: more sets per pallet means less storage per set, so more room for landed cost. Full text: `spark/kimi-noon-opinion-2026-10-19.json`.
- Input file: `spark/memo-2026-10-19-input.txt`.

## BRILLIANT
BRILLIANT: Sell the $40 order as one factory-sealed 8-piece "home set" instead of two 4-packs: one SKU, one pick, no ARDI kitting. That's up to $1.65/set more landed-cost room (UNVERIFIED until ARDI confirms 8-pc billing), and the store gets a single product.

## Pip/Tally pre-clear
Under the restart comms rule, this goes to Tally and Pip through Oki (30-minute window, silence means pass), then to Oki for the dashboard.

## Tool-use log
| Tool | Task | Output |
|---|---|---|
| Shell/Read | GOD-SQUAD-PLAN, TEAM-ASSETS, Tally DEADLINES/A319/A320/Triumph, ARDI Q1–Q13 verbatim, J100, audit 75, comms log, supplier sheet | Picked the Oct 22–23 gate question (Tally's open row) |
| gh CLI | Issue #8 comments | No new asks for Spark since Oct 18 |
| Python Decimal | Gates by kitting mode, payback | memo-2026-10-19-calc-out.txt (reproduces A320 exactly) |
| Claude Opus 5.5 | Independent opinion | Adopt, with changes |
| Kimi K3 API | Independent opinion | Change (conditional B framing) |
