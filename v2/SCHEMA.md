# ceo dashboard v2 — data.json schema (v2.0)
All times ISO 8601 with offset. Every numeric block carries `source` (path/URL; null or "EXAMPLE" => numbers render red "no source") and `as_of` (older than 24h or missing => greyed "stale"). All fields optional; page degrades to "–".

## top level
- `schema_version` string "2.0"
- `example` bool — true shows yellow "example data" banner. Oki: set false.
- `generated_at` time — shown in banner; stale if >24h.
- `generated_by` string (info only)

## first_sale
- `target_date` date — counter = ceil(days from now)
- `next_gate` "po" | "stock" | "checkout"
- `gates[]`: `id`, `label`, `status` ("open"|"done"), `source`, `as_of`
- `source`, `as_of`

## scoreboard[] (one per venture)
- `venture` string; `sent`, `replies`, `yes`, `paid` ints; `source`, `as_of`

## decisions[] (only first 3 non-resolved shown)
- `id`, `question` (yes/no), `slips_if_waiting`, `deadline` time, `default_at_deadline`, `status` ("open"|"resolved" — resolved hidden), `source`, `as_of`

## cash[] (one per cap)
- `cap` name, `cap_amount` USD, `spent`, `committed` USD; `left` is computed = cap − spent − committed
- `verified` bool (false => "estimated" tag); `source` (Tally ledger), `as_of`

## blockers[]
- `text`, `owner`, `since` time, `source`, `as_of`
