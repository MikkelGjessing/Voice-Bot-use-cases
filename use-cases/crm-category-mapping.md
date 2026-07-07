# CRM Category Match – Nets Merchant Services (All Regions)

> **Source:** `Lisa.xlsx` (sheet `ZZSR_SPP`)
> **Repository references:**
> - `use-cases/nordic-merchant-services.md`
> - `use-cases/dac-merchant-services.md`

## 1) CRM categories that map to existing use cases

| Region | CRM category (Lisa.xlsx) | Match in repository | Match status |
|---|---|---|---|
| Nordics | `CA_51000000` – DK Sales Support - Technical Support | Nordic translation scenarios for Danish customers (`Category 1`, `Category 2`, `Category 4`) | ✅ Covered |
| Nordics | `CA_52000000` – SE Sales Support - Technical Support | Nordic translation scenarios for Swedish customers (`Category 1`, `Category 2`, `Category 4`) | ✅ Covered |
| Nordics | `CA_53000000` – FI Sales Support - Technical Support | Nordic translation scenarios for Finnish customers (`Category 1`, `Category 2`, `Category 4`) | ✅ Covered |
| Nordics | `CA_54000000` – NO Sales support - Technical Support | Nordic translation scenarios for Norwegian customers (`Category 1`, `Category 2`, `Category 4`) | ✅ Covered |
| Nordics | `CA_51010000` / `CA_52010000` – Service Account Management | Live agent-assist / bidirectional translation flows (`Category 4` in Nordics, `Category 6` in DAC) | 🟨 Partially covered |
| Nordics + DAC | Quality/baseline operational categories (same-language handling patterns) | Baseline validation sections (`Category 3` Nordics, `Category 5` DAC) | ✅ Covered |

## 2) CRM categories with no direct use-case coverage yet

| Scope | CRM category examples (Lisa.xlsx) | Gap vs repository |
|---|---|---|
| Merchant commercial flows | `CA_40700000` – Pricing MS, `CA_50000000` – MS Repricing, `CA_00500000` – Retention Nordic - Service, `CA_00510000` – Retention Nordic - Info | Current repository focuses on language translation scenarios, not pricing/retention process flows |
| Risk/dispute flows | `CA_00850000` – Fraud & Dispute (and related dispute/fraud categories) | No dedicated fraud/dispute translation use-case groups in current markdowns |
| DAC CRM taxonomy | No top-level categories explicitly tagged for `DE`, `AT`, or `CH` in `Lisa.xlsx` | DAC use-case document exists, but CRM taxonomy alignment appears missing and should be added in CRM source data |

## 3) Regional conclusion

- **Nordics:** Most technical-support translation use cases are already represented in the repository.
- **DAC:** Voice translation use cases are defined in the repository, but explicit DAC CRM category coverage is not visible in the attached CRM extract.
- **Next step:** Add DAC-tagged CRM categories (DE/AT/CH, Turkish/Arabic/Swiss variants) and merchant pricing/retention/fraud translation scenarios if full CRM-to-use-case traceability is required.
