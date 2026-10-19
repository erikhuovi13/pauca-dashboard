# A319 — ARDI Q13 gate restate + Triumph Gifts ESTIMATE score — Mon Oct 19, 2026 ~8:52 AM ET (Tally)

Files only. NO sends/contact/purchase/Shopify. Decimal asserts: `minus-discovery/tally/a319_q13_restate_asserts.py` — ALL ASSERTS PASS.
Labels: VERIFIED = written/live source read by Tally/Pip; ESTIMATE = computed from labelled inputs; UNVERIFIED = relay/no written basis read; UNKNOWN = no value. Every number below carries one.

> **⚠ AUDIT — KILL LINE NOT MOVED:** The restated N=15 ceiling DOES change by kitting scenario (factory $6.76 / ARDI-kitted $5.31 per 4-pack, below). Erik's Oct 20 felt kill line **stays $155.75/100 pcs as set Oct 17 5:17 PM ET on the OLD stack basis**. Do not silently apply $132.75/100 (ARDI-kitted restate) to felt. Moving the kill line is an Erik/Oki decision. Felt outcome is unchanged either way today: written delivered quotes ≤$155.75/100 = **0 VERIFIED** (Rongmei $364.00/100 VERIFIED written = FAIL), and ≤$132.75 also = 0.

## 0. Source verification — original email NOT in files
- Searched `rg '1a1538b79b47675f|Q13'` under `/workspace/ceo/shopify-restart/` + `/workspace/minus-discovery/`: **no original ARDI email body on file**. Citations found: Oki audit 73 (`minus-discovery/team-audit-2026-10-19-0620.md:17,23`), `LAUNCH-CHECKLIST.md:222`, `team-tasks/NEXT-Tally.md`, and Pip `minus-discovery/pip-pauca-2026-10-19.md` §3 (Pip read the original for Q11/Q12 only, verbatim).
- **Therefore Q13 rates below are UNVERIFIED relay (Oki audit 73) for Q1–Q10/Q13, and VERIFIED-by-Pip-verbatim only for Q11/Q12.** This restate proceeds on the relay per assignment; if the original differs, ceilings re-issue. No message body was invented.

## 1. Q13 terms as relayed (audit 73, UNVERIFIED relay unless noted)
| Item | Term | Label |
|---|---|---|
| Unload | $10.00/pallet, single-SKU pallets | UNVERIFIED relay |
| Storage | $30.00/pallet/month (not contradicted) | UNVERIFIED relay |
| Receiving | $2.00/unit — **only for returns** (audit 73 wording) | UNVERIFIED relay; unit basis (pc vs set) UNKNOWN |
| Kitting Q4 | $1.45 per 4-pack | UNVERIFIED relay |
| Pick Q5 | two 4-packs = $1.50 pick + $0.40 extra item, **if pre-kitted** | UNVERIFIED relay |
| Insert Q7/Q8 | $0.50/card vs "counted like additional unit" ($0.40) — CONFLICT; audit 73 also prices $0.90 = both | UNKNOWN which applies |
| Photos Q11/Q12 | $1.00/photo, publish on own store/social = YES | VERIFIED (Pip verbatim, msg 1a1538b79b47675f, 2026-10-19 09:42:52Z) |
| Supplier photos | NOT covered by Q12; Pip BLOCK stands | VERIFIED (Pip §3) |
| Sets/pallet (actual) | depends on carton/pallet packing | **UNKNOWN** |
| Months of storage (actual) | per lot turn | **UNKNOWN** |

## 2. Per-set unload/storage rebuilt from per-pallet rates (ESTIMATE, Decimal)
Per set: unload = $10/N, storage = $30/N per month. Per two-4-pack order D = 2×(10+30·m)/N.

| N sets/pallet | unload/set | storage/set-mo | 1-mo total/set | D/order 1-mo (2 sets) | D/order 2-mo |
|---:|---:|---:|---:|---:|---:|
| 15 (min-pallet case) | $0.6667 | $2.0000 | $2.6667 | $5.3333 | $9.3333 |
| 25 | $0.4000 | $1.2000 | $1.6000 | $3.2000 | $5.6000 |
| 50 | $0.2000 | $0.6000 | $0.8000 | $1.6000 | $2.8000 |
| 100 | $0.1000 | $0.3000 | $0.4000 | $0.8000 | $1.4000 |
| 10 (sensitivity) | $1.0000 | $3.0000 | $4.0000 | $8.0000 | $14.0000 ESTIMATE (2-mo D computed, ceiling in script table) |

All ESTIMATE allocations of UNVERIFIED-relay rates at ASSUMED N (N actual UNKNOWN). The old composite "$0.70/set" (A299: $0.40 unload @25 + $0.30 storage @100×1mo, mixed bases) is superseded — use a single named N and m.

## 3. Order stack rebuild — CRITICAL double-count check (two-4-pack $40 order)
Old stack $13.94/order (A301/codex-reconciliation): label $8.95 UNVERIFIED + receiving $1.10 UNVERIFIED + pick $1.50 + kitting $1.45 (×1 only) + packaging $0.94 ESTIMATE. Extra item $0.40: **absent**.

Line-by-line Q13 rebuild (insert = $0 in base; receiving kept — see AUDIT-R):

| Line | Old $13.94 | Factory pre-kitted | ARDI-kitted | Label |
|---|---:|---:|---:|---|
| Label | $8.95 | $8.95 | $8.95 | UNVERIFIED (Q6 markup still UNKNOWN) |
| Receiving | $1.10 | $1.10 | $1.10 | UNVERIFIED — Q13 does NOT confirm it (see AUDIT-R) |
| Pick (1 per order) | $1.50 | $1.50 | $1.50 | UNVERIFIED relay (Q5) |
| Extra item (2nd pack) | $0.00 ABSENT | $0.40 | $0.40 | UNVERIFIED relay (Q5) |
| Kitting $1.45/4-pack | $1.45 (×1) | $0.00 (×0) | $2.90 (×2) | UNVERIFIED relay (Q4) |
| Packaging | $0.94 | $0.94 | $0.94 | ESTIMATE ($0.03 mailer VERIFIED exists; replacement not adopted here) |
| Insert | $0.00 | $0.00 base | $0.00 base | priced separately §5 |
| **Stack S** | **$13.94** | **$12.89** | **$15.79** | ESTIMATE totals |

**Verdict on auditor claim:**
- **Double-count? NO — old stack UNDER-counts for ARDI-kitted.** It counted kitting once for a 2-set order and no extra item. Missing = $1.45 + $0.40 = **$1.85/order = $0.925/set VERIFIED arithmetic (Decimal)**. Auditor's "~$5.30/set" ceiling: **direction CONFIRMED, floor corrected to $5.31** (exact $5.3121, N=15, §4) — not $5.30.
- **Factory pre-assembled claim REFUTED as stated.** Auditor/audit-73 "only $0.40 applies (~$0.20/set drop)" is a *delta-only* shorthand: old+$0.40 → S=$14.34, ceiling drops exactly $0.2000/set (asserted). Economically, factory pre-kitted sets incur **no ARDI kitting**, so the $1.45 in the old stack must come OUT: net delta = −$1.45+$0.40 = **−$1.05/order**, and the ceiling **RISES** (+$0.525/set before floor), it does not drop $0.20. Use $14.34 only as "auditor shorthand, kitting wrongly retained" — never as the factory case.
- **AUDIT-R (receiving):** Audit 73 says $2/unit receiving applies *only for returns*. That does not confirm the $1.10/order receiving line, and returns cost ($2/unit, unit UNKNOWN × return-rate UNKNOWN) is not a per-fulfilled-order stack line. **Operative choice (fail-closed): keep $1.10 UNVERIFIED in S.** Removing it would raise every ceiling exactly **$0.55/set** (asserted) — shown as no-receiving sensitivity in the script output, NOT adopted. ARDI clarification is still needed; no clarification was sent by Tally.

## 4. Restated ceilings — function of N, named cases kept
Formula (unchanged, A301): Lmax = (32.54 − 1.03·S − D) / 2.06 per 4-pack, gross $40, fee $1.46 (rate UNVERIFIED), $6 Full floor, cent-floor enforced. Ceiling/100 = floor×25.

| Named case | Old S=$13.94 | Factory S=$12.89 | ARDI-kitted S=$15.79 (fail-closed operative) |
|---|---:|---:|---:|
| $7.27 case — 25/25, 1 mo (N=25) | $7.27 → $181.75/100 | $7.79 → $194.75/100 | **$6.34 → $158.50/100** |
| $6.23 case — min-pallet N=15, 1 mo | $6.23 → $155.75/100 | $6.76 → $169.00/100 | **$5.31 → $132.75/100** |
| $8.14 case — 100/100, 2 mo (N=100) | $8.14 → $203.50/100 | $8.67 → $216.75/100 | **$7.22 → $180.50/100** |
| N=50, 1 mo | $8.04 → $201.00 | $8.57 → $214.25 | $7.12 → $178.00 |
| N=50, 2 mo | $7.46 → $186.50 | $7.99 → $199.75 | $6.54 → $163.50 |
| N=25, 2 mo | $6.10 → $152.50 | $6.63 → $165.75 | $5.18 → $129.50 |
| N=10, 1 mo (sensitivity) | $4.94 → $123.50 | $5.46 → $136.50 | $4.01 → $100.25 |

All ceilings ESTIMATE (computed from UNVERIFIED-relay rates + UNVERIFIED fee/label/receiving lines).

**Which basis is operative now?** Per-pallet billing is the confirmed *basis* (relay), but N (sets/pallet) and kitting mode are both **UNKNOWN per supplier/lot**, so no single named case is operative alone. **Fail-closed operative screen until a supplier writes "factory pre-assembled 4-packs, one SKU" AND sets/pallet is known: ARDI-kitted stack, N=15 case = $5.31/4-pack ($132.75/100).** On written factory-pre-kitted proof, that supplier moves to the factory column ($6.76 at N=15). HOLD pending Q13 is therefore **lifted for the pallet basis only**; scoring remains HOLD on kitting mode + N + receiving + insert per quote. Sentinel to re-read gate 3 on this restate (audit 73 take-off).

## 5. Insert conflict — ceiling delta (per order, ΔL = −ΔS/2 exactly)
| Insert priced as | ΔS/order | Δ ceiling/set | ARDI-kitted N=15 ceiling |
|---|---:|---:|---:|
| $0.40 extra item (Q8 reading) | +$0.40 | −$0.20 | $5.11 → $127.75/100 |
| $0.50/card (Q7 reading) | +$0.50 | −$0.25 | $5.06 → $126.50/100 |
| $0.90 both (audit 73 worst) | +$0.90 | −$0.45 | $4.86 → $121.50/100 |
Which applies = **UNKNOWN**. Insert is unused until a stock buy (audit 73); ceilings in §4 exclude insert. Do not score an insert-bearing order on §4 ceilings.

## 6. Kill-line impact (Oct 20, felt)
- Restated $6.23-case ceiling **does change**: $6.23 → $5.31 (ARDI-kitted) / $6.76 (factory) per 4-pack; /100: $155.75 → $132.75 / $169.00. **AUDIT FLAG (prominent): Erik's $155.75/100 kill line was set 2026-10-17 5:17 PM ET on the old S=$13.94 basis. It is NOT moved by this file.** Erik/Oki must decide whether felt (and future scoring) uses $155.75 as written or the restated operative $132.75. Audit 73 pre-read agrees: revised gate applies to future quotes, not retroactively to the kill line.
- Either way felt dies Tue Oct 20 EOD on today's file: 0 written delivered quotes ≤$155.75 (and 0 ≤$132.75). Rongmei $364.00/100 FAIL stands.

## 7. Triumph Gifts — ESTIMATE ONLY (detail file: `tally-triumph-score-2026-10-19.md`)
@500 pcs, IF DDP is additive to EXW (UNVERIFIED): landed **$5.72–$6.72/4-pack ESTIMATE** (DDP $65–$190 ends), **$6.36–$7.36 with $80 die-cut**. Pip's $6.72 ($7.36 w/die) = high end only. Vs fail-closed operative $5.31 (N=15 ARDI-kitted): **FAIL at every point of the range**. Vs factory N=15 $6.76: low/mid pass ESTIMATE, die-cut high end FAIL. **Verdict: ESTIMATE ONLY, not a written landed quote; usable landed quotes remain 0.** IOR/duty/MPF = UNKNOWN (unanswered), DDP inclusion = UNKNOWN, 100mm ≠ Ø110mm spec, full-payment-before-shipment = payment re-gate. Full table in the Triumph file.

## AUDIT flags
- AUDIT-1: Original ARDI email not in files; Q13 rates = UNVERIFIED relay (Oki), Q11/Q12 only Pip-verbatim VERIFIED. Restate must re-issue if original differs.
- AUDIT-2: Auditor "~$5.30" corrected to floor $5.31; auditor factory "~$0.20/set drop" REFUTED as economic case (delta-only shorthand; true factory raises ceiling).
- AUDIT-3: Receiving $1.10 kept fail-closed UNVERIFIED; $2/unit returns-only does not confirm it. Dropping it = +$0.55/set — not adopted.
- AUDIT-4: Kill line $155.75 NOT moved despite restated $132.75 operative ceiling — Erik/Oki decision flagged in DEADLINES Oct 20 header note.
- AUDIT-5: Insert $0.40/$0.50/$0.90 all priced; which applies UNKNOWN.
- AUDIT-6: Fee $1.46 rate, label $8.95, packaging $0.94 remain UNVERIFIED/ESTIMATE as before; Q13 did not settle them.
