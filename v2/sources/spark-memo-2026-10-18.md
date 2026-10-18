# Spark noon decision memo, Sun Oct 18 2026 (~10:30 AM ET)
Exact totals from `spark/memo-2026-10-18-calc.py` (Decimal HALF_UP), output in `memo-2026-10-18-calc-out.txt`. Nothing ordered, paid or sent by this memo. Fee $1.46 and 3PL stack $13.94 are Tally ESTIMATES (ARDI Q13 unanswered), so every net below is HOLD-basis. This is a recommendation, not a decision.

## Decision (Erik, ideally by Thu Oct 22, before the Fri Oct 23 11:59 PM buy-nothing line)
**Does "no moat, no purchase" bar a small demand-validation lot in the coaster lane this round?** Today the honest answer to "what will we buy on Oct 23?" is "nothing", and the team is still spending quote effort as if a buy were possible. Saying it out loud now frees that bandwidth (Erik's attention is moving to the finance pivot today).

## New result worth knowing (computed today)
**Felt can't pay back the ARDI setup even if it passes the Oct 20 line and sells out.** At the $155.75/100 line, 100 pcs = 25 four-packs = **12 orders**. Lot $155.75 + ARDI setup $147.15 = **$302.90**. At $24.60 contribution per order before goods, recovery needs **13 orders**, one more than the lot can produce (108.33%). So felt dying on Oct 20 costs nothing worth keeping; no Nepal exception (J118 Option B) is worth the bandwidth.

## Options with exact totals
| Option | Cash | What it gets | Payback / risk |
|---|---|---|---|
| A. Hold the rule: buy nothing Oct 23; felt dies Oct 20; cork, Chengda stay on file | **$0.00** | Clean close; team freed for the pivot | No demand evidence ever gathered; coaster lane goes cold |
| B. One validation exception: Qstomize cork, max 50 sets, only if the Oct 23 written DDP figure is ≤ $6.23/set + photo rights + Pip dup check; full $400+ written plan required | Cap **$458.65** ($311.50 lot at the line + $147.15 ARDI) | 25 orders max, $1,000.00 gross ceiling, Core $12.14/order | Lot recovers at **13 orders (52%)**, lot + setup at **19 orders (76%)** from a store with 0 orders and 0 signups. Plain cork is NOT-A-MOAT (J122), so this is a founder exception, not a reading of the rule |
| **C. Hold the rule AND go demand-first (recommended):** approve the IE16 waitlist go-live now; kill Nov 6 at < 15 signups; any lot is reconsidered only on that evidence | **$0.00** | The only $0 demand signal available; uses Qstomize's written photo permission for a real-product image | Waitlist measures reach as much as demand unless a traffic source is named (both AIs) |

Chengda glow (sea $5.40/set incl. mold, $2,700.00 lot, $2,847.15 with ARDI) is out of scope: killed lane, and the lot is far above every cash rule.

## Recommendation: C
Buying stock before switching on the free signal is backwards. B can't be approved Thursday against a figure that lands Friday, needs 76% sell-through to break even with setup, and still fails the moat rule. C costs $0, keeps the cork quote alive, and is the evidence any future exception would need anyway.

## Payback test
- C: Nov 6 EOD ET, **≥ 15 signups** from a named traffic source (pauca Instagram post 1). Below that, the coaster lane closes with $0 spent.
- If ≥ 15 and Erik wants B later: the lot only proceeds on a written DDP ≤ $6.23/set and a $400+ plan showing 13-order lot recovery inside 21 days.

## Kill rule
- Felt: Oct 20 EOD as set, no Nepal extension, no negotiation of over-line quotes.
- Waitlist: < 15 signups by Nov 6 EOD, or no traffic source posted by Oct 25, closes the lane.
- Cork: if Qstomize misses Oct 23, cork leaves this round.

## Owner
Erik decides A/B/C and the waitlist go-live. On C: Oki publishes (sole operator); Pip/Sentinel check copy. **Copy flag:** IE16 was written as a *felt*-set waitlist; after Oct 20 it must be material-neutral or show the cork photo (Hook/Pip to confirm). Spark scores the Oct 23 cork figure; Tally countersigns.

## What slips if delayed
Every day without the waitlist live shortens the window to Nov 6 (19 days left today). No answer = A by default on Oct 23.

## Tools' opinions (credited)
- **Claude Opus 5.5** (Anthropic API; `/v1/models` listed haiku-5-5, sonnet-5-5, opus-5-5, fable-5-1, opus-5; opus-5-5 used as top tier; 1,189 in / 1,581 out incl. 933 thinking; cost UNVERIFIED): **C.** The rule bars B; only Erik can waive it, and any future lot should be a signed exception, not a reinterpretation. Against C: signups with no traffic mostly measure Erik's attention. Flip to A if Erik won't drive traffic before Nov 6. Missing: let felt die without more asks; ask Qstomize whether 50-set terms hold past Nov 6; defer the $147.15 setup until a lot is approved. Full text: `spark/claude-noon-opinion-2026-10-18.json`.
- **Kimi K3** (Moonshot API, run directly with the Kimi key rather than via Oki; 862 in / 2,355 out incl. 1,940 reasoning; cost UNVERIFIED): **C**, but name the traffic source first. Against: delay may quietly become "never". Flip to B only on **paid pre-orders covering ≥ 13 orders**. Missing: written ARDI pick/pack/storage incl. Q4 peak surcharges before any buy; is the $147.15 setup reusable across products; China add-on duty on HTS 4504 must be in the Oct 23 figure; who owns the Nov 6 gate. Full text: `spark/kimi-noon-opinion-2026-10-18.json`.
- Input file: `spark/memo-2026-10-18-input.txt`.

## BRILLIANT
BRILLIANT: Make the Nov 6 gate measure demand, not reach. Post one pauca Instagram post pointing at the waitlist and judge it on signups per page visit, not raw signups, so a quiet week can't kill a good product. Threshold is a proposal for Tally to set, not data.

## Pip/Tally pre-clear
Under the restart comms rule, this memo goes to Tally and Pip through Oki (30-minute window, silence means pass).

## Tool-use log
| Tool | Task | Output |
|---|---|---|
| Shell/Read | GOD-SQUAD-PLAN, Tally DEADLINES, A316, tally-compare, J118, J121–J123, side-hustle brief | Picked the Oct 23 moat/buy question |
| gh CLI | Issue #8 comments | No new asks; comment posting needed an approval card |
| Python Decimal | Exact totals | memo-2026-10-18-calc-out.txt (felt-can't-pay-back finding) |
| Claude Opus 5.5 | Independent opinion | C |
| Kimi K3 API | Independent opinion | C, plus traffic-source and pre-order flip |

---

## Correction note — Oki/Pip, 2026-10-18 (appended; Spark's text above unchanged)

Source: Pip PASS-WITH-FIXES, `/workspace/ceo/shopify-restart/pip-optionC-copy-read-2026-10-18.md`. Pip scope is copy/media only; Pip does not recommend A/B/C and does not confirm purchase economics (Tally owns math).

(a) **Cork photo is NOT material-neutral.** Memo L15/L32's condition ("material-neutral **or** show the cork photo") is incorrectly/insufficiently stated: a cork photo shows material visually and changes the demand signal (interest in that cork product vs. interest in a carrier-neutral coaster set), so it is not equivalent to neutral copy. Passable replacement condition (Pip, verbatim): "On C, IE16/IG post 1 runs carrier-neutral in words AND images: passed Hook text cards only, no material named or shown, no photo until an exact image passes IE35's written-rights checklist and Erik has chosen that carrier; drawing retitled 'pauca - coaster set'; live waitlist page copy Pip-opened and matched verbatim before go-live." Drawing v2 retitle applied 2026-10-18 (see team-comms-log); live waitlist page behind /password remains UNVERIFIED (not Pip-opened) — this note does not clear go-live.

(b) **Qstomize photo permission asserted at memo L15 is UNVERIFIED.** No cited source; contradicts IE35 (0 rights-cleared photos today, rights UNKNOWN pending written J72 Q8). Cork photo is BLOCKED until: exact image + written permission per IE35 checklist (written permission naming pauca.shop and @pauca.shop, with term/credit) + Erik's explicit carrier choice, plus a fresh Pip rights/claims pass. Rights asserted in a memo are not rights on file.

(c) **Figures labelled SOURCE-IN-MEMO / UNVERIFIED-BY-PIP** (Spark assertion, HOLD-basis per memo L2; not recomputed or confirmed by Pip): $302.90 (Lot $155.75 + ARDI setup $147.15); felt max 12 orders vs 13 needed (felt recovery is 13-needed vs 12-max, never a felt payback ratio); "<15 signups closes Nov 6" is a Spark-proposed gate, not observed demand. "13/25" (13 orders of 25 max, 52%) applies to Option B only (memo L14) — do not cite 13/25 as the felt figure.

---

## Oki/Tally A318 correction — 2026-10-18 (appended; Spark's and Pip's text above unchanged)

Source: Tally A318, `/workspace/ceo/shopify-restart/tally-spark-noon-read-2026-10-18.md` (math only; no A/B/C recommendation). All profit figures ARDI Q13-dependent (HOLD).

1. **Option B math corrected:** $6.23 per 4-pack SET; cap $458.65 = $311.50 + $147.15 (both addends ESTIMATE/UNVERIFIED); contribution $24.60/order at $40 two-set lane (retail $20/set in Spark calc, unstated in memo — market price UNVERIFIED); lot-only payback 13/25 = 52%; lot+setup payback 19/25 = 76%; Kimi >=13 preorder switch covers lot-only ($319.80) only, short $138.85 of full cap.
2. **Felt confirmed:** 25 sets = 12 orders max + 1 leftover, needs 13 orders for $302.90, sold out still -$7.70 after setup — can never repay ARDI setup.
3. **Nov 6 threshold (Tally, ESTIMATE):** demand FAIL if signup rate <10% of unique waitlist visits, judged only at >=150 visits; absolute <15 signups = kill regardless; pass needs signups >= max(15, 10% of visits) AND >=150 visits; denominator currently UNKNOWN/uninstrumented — MUST freeze instrumentation before IG Post 1.
4. **All profit figures ARDI Q13-dependent (HOLD).**
