# neo-bank · Banking money path

Learn track for **Technical PM**: how a neobank / fintech banking product is assembled (not “open a bank charter from zero”).

Built as a bridge from [pam-wallet](https://github.com/saturoM/pam-wallet) (iGaming PAM money path).

## How we learn

1. **Whole system first** — see [`overview.png`](overview.png) (zones 1–11).
2. **Zoom a zone** — deepen one numbered block or one money flow.
3. **Short open exercises** — only after the picture for that zone is clear.
4. Close the module when you can explain it to another PM.

## Modules

| # | Topic | File |
|---|---|---|
| 01 | Available ≠ ledger · holds | [`01_available_vs_ledger.md`](01_available_vs_ledger.md) |
| 02 | Auth / clear / settle / return | [`02_payment_statuses.md`](02_payment_statuses.md) |
| 03 | SEPA SCT / Instant | [`03_sepa_rails.md`](03_sepa_rails.md) |
| 04 | Card issuing | [`04_cards_issuing.md`](04_cards_issuing.md) |
| 05 | BaaS vs license | [`05_baas_vs_license.md`](05_baas_vs_license.md) |
| 06 | KYB / AML as product | [`06_kyb_aml_product.md`](06_kyb_aml_product.md) |

Exercises: [`exercises/`](exercises/) · Syllabus: [`syllabus.json`](syllabus.json)

## Ownership legend (overview)

- **You (fintech):** zones 2–5 — API, gates, ledger/holds, status map  
- **Partner BaaS / bank:** zones 6–9 — IBAN, payments engine, card issuer, KYC vendor  
- **External rails:** zones 10–11 — SEPA, card schemes  

Current focus: whole-system map → then zoom zones.
