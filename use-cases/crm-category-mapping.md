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
| Nordics | `CA_51010000` / `CA_52010000` – Service Account Management | Live agent-assist / bidirectional translation flows (`Category 4` in Nordics, `Category 6` in DAC) | ✅ Covered |
| Nordics + DAC | Quality/baseline operational categories (same-language handling patterns) | Baseline validation sections (`Category 3` Nordics, `Category 5` DAC) | ✅ Covered |
| Nordics | `CA_40700000` – Pricing MS · `CA_50000000` – MS Repricing | Pricing & Commercial Support Calls (`Category 5` Nordics) | ✅ Covered |
| Nordics | `CA_00500000` – Retention Nordic - Service · `CA_00510000` – Retention Nordic - Info | Retention Calls (`Category 6` Nordics) | ✅ Covered |
| Nordics | `CA_00850000` – Fraud & Dispute | Fraud & Dispute Calls (`Category 7` Nordics) | ✅ Covered |
| DAC | `CA_DE51000000` / `CA_AT51000000` / `CA_CH51000000` – DE/AT/CH Sales Support - Technical Support | DAC technical support translation scenarios (`Categories 1–4` DAC) | ✅ Covered |
| DAC | `CA_DE51010000` / `CA_AT51010000` – Service Account Management | Live agent-assist / bidirectional translation flows (`Category 6` DAC) | ✅ Covered |
| DAC | `CA_40700000` – Pricing MS · `CA_50000000` – MS Repricing | Pricing & Commercial Support Calls (`Category 7` DAC) | ✅ Covered |
| DAC | Retention – Service · Retention – Info (DAC equivalent) | Retention Calls (`Category 8` DAC) | ✅ Covered |
| DAC | `CA_00850000` – Fraud & Dispute (DAC sub-categories) | Fraud & Dispute Calls (`Category 9` DAC) | ✅ Covered |

## 2) Coverage summary by case handling type

| Case handling type | CRM category examples | Nordic coverage | DAC coverage |
|---|---|---|---|
| Technical Support | `CA_51000000`–`CA_54000000` | ✅ Categories 1–2 | ✅ Categories 1–4 |
| Service Account Management | `CA_51010000`, `CA_52010000` | ✅ Category 4 | ✅ Category 6 |
| Baseline / Quality Validation | Operational baseline | ✅ Category 3 | ✅ Category 5 |
| Pricing & Commercial | `CA_40700000`, `CA_50000000` | ✅ Category 5 | ✅ Category 7 |
| Retention | `CA_00500000`, `CA_00510000` | ✅ Category 6 | ✅ Category 8 |
| Fraud & Dispute | `CA_00850000` | ✅ Category 7 | ✅ Category 9 |

## 3) Regional conclusion

- **Nordics:** All CRM case handling categories (Technical Support, Account Management, Baseline, Pricing, Retention, Fraud & Dispute) now have dedicated translation use cases in the repository.
- **DAC:** All CRM case handling categories now have dedicated translation use cases covering DE/AT/CH merchants and the full set of non-German speaker language combinations (Turkish, Arabic, Swiss variants). CRM category tags have been added to each category in `dac-merchant-services.md`.
- **Full traceability achieved:** Every CRM case handling type from `Lisa.xlsx` maps to at least one use case in the repository for both regions.
