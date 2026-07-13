# Voice Bot Use Cases – DAC Merchant Services (Real-Time Translation)

> **Region:** DAC (Germany, Austria, Switzerland)
> **Platform:** Boost PoC (reusable for Genesis, Sinch, Found Ever)
> **Focus:** Real-time voice translation between customer and agent languages
> **Last updated:** July 2026

---

## Overview

The DAC region has a large population of non-German native speakers, particularly Turkish and Arabic speakers in Germany, as well as three official languages across Switzerland (German, French, Italian). These use cases cover scenarios where a customer calls in their native language and is connected to an agent speaking a different language, with Boost providing live two-way translation during the call.

---

## Category 1 – Non-German Speakers → German-Speaking Agent

> **CRM categories (DAC):** `CA_DE51000000` – DE Sales Support - Technical Support · `CA_AT51000000` – AT Sales Support - Technical Support · `CA_CH51000000` – CH Sales Support - Technical Support

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 1.1 | Turkish → German | Turkish-speaking merchant to German-speaking agent | Turkish | German | High |
| 1.2 | Arabic → German | Arabic-speaking merchant to German-speaking agent | Arabic | German | High |
| 1.3 | Swiss French → German | Swiss French-speaking merchant to German-speaking agent | French (Swiss) | German | High |
| 1.4 | Swiss Italian → German | Swiss Italian-speaking merchant to German-speaking agent | Italian (Swiss) | German | High |
| 1.5 | Swiss German dialect → Standard German | Swiss German dialect speaker to Standard German-speaking agent | Swiss German | German | High |

---

## Category 2 – Non-German Speakers → English-Speaking Agent

> **CRM categories (DAC):** `CA_DE51000000` / `CA_AT51000000` / `CA_CH51000000` – Technical Support (English routing)

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 2.1 | Turkish → English | Turkish-speaking merchant to English-speaking agent | Turkish | English | Medium |
| 2.2 | Arabic → English | Arabic-speaking merchant to English-speaking agent | Arabic | English | Medium |

---

## Category 3 – Swiss Official Languages → Native Agent

> **CRM categories (DAC):** `CA_CH51000000` – CH Sales Support - Technical Support (native language routing)

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 3.1 | Swiss French → French | Swiss French-speaking merchant to French-speaking agent | French (Swiss) | French | Medium |
| 3.2 | Swiss Italian → Italian | Swiss Italian-speaking merchant to Italian-speaking agent | Italian (Swiss) | Italian | Medium |

---

## Category 4 – German → Polish (Krakow Agent Centre)

> **CRM categories (DAC):** `CA_DE51000000` / `CA_AT51000000` – Technical Support (Krakow routing)

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 4.1 | German → Polish | German-speaking merchant to Polish-speaking agent in Krakow | German | Polish | Medium |
| 4.2 | Turkish → Polish | Turkish-speaking merchant to Polish-speaking agent in Krakow | Turkish | Polish | Low |

---

## Category 5 – Baseline & Quality Validation

> **CRM categories (DAC):** Operational baseline – applies across all DAC CRM categories

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 5.1 | German → German | Same-language call to validate that translation layer adds no degradation | German | German | High |
| 5.2 | Turkish → Turkish | Same-language baseline test for Turkish | Turkish | Turkish | Medium |

---

## Category 6 – Live Agent Assist During Translation

> **CRM categories (DAC):** `CA_DE51010000` / `CA_AT51010000` – Service Account Management

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 6.1 | Live translation overlay – Turkish to German | Agent sees live Turkish-to-German text translation during the call | Turkish | German | High |
| 6.2 | Live translation overlay – Arabic to German | Agent sees live Arabic-to-German text translation during the call | Arabic | German | High |
| 6.3 | Live translation overlay – Swiss variants to German | Agent sees live translation of Swiss French or Italian to German | French (Swiss) / Italian (Swiss) | German | High |
| 6.4 | Swiss German dialect normalisation | Swiss German dialect speech is normalised to Standard German for the agent in real time | Swiss German | German | High |
| 6.5 | Bidirectional translation | Agent response is also translated back to customer's language in real time | All DAC languages | German / English / Polish | High |
| 6.6 | After-call summary in agent language | Platform generates a post-call summary in the agent's language after the conversation | All DAC languages | German / Polish | Medium |

---

## Category 7 – Pricing & Commercial Support Calls

> **CRM categories (DAC):** `CA_40700000` – Pricing MS · `CA_50000000` – MS Repricing

These use cases cover inbound calls related to terminal pricing, fee queries, and repricing requests from DAC merchants. Real-time translation is required where the merchant's language differs from the agent's language.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 7.1 | Turkish pricing query → German | Turkish-speaking merchant calls about terminal fees or pricing; German-speaking agent handles with live translation | Turkish | German | High |
| 7.2 | Arabic pricing query → German | Arabic-speaking merchant queries pricing or rates; German-speaking agent handles with live translation | Arabic | German | High |
| 7.3 | Swiss French repricing request → German | Swiss French-speaking merchant requests a repricing review; German agent handles with live translation | French (Swiss) | German | High |
| 7.4 | Swiss Italian pricing dispute → German | Swiss Italian-speaking merchant disputes fees; German agent handles with live translation | Italian (Swiss) | German | High |
| 7.5 | German pricing query → Polish | German-speaking merchant calls about pricing; Polish Krakow agent handles with live translation | German | Polish | Medium |
| 7.6 | Turkish pricing query → English | Turkish-speaking merchant discusses pricing with English-speaking agent | Turkish | English | Medium |
| 7.7 | Arabic repricing request → English | Arabic-speaking merchant requests repricing with English-speaking agent | Arabic | English | Medium |

---

## Category 8 – Retention Calls

> **CRM categories (DAC):** Retention – Service · Retention – Info (DAC equivalent of `CA_00500000` / `CA_00510000`)

These use cases cover calls where DAC merchants are at churn risk. Real-time translation is critical to ensure the retention agent can address merchant concerns effectively and empathetically.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 8.1 | Turkish retention – service complaint → German | Turkish-speaking merchant threatens to cancel service; German retention agent handles with live translation | Turkish | German | High |
| 8.2 | Arabic retention – service complaint → German | Arabic-speaking merchant raises a service complaint in a retention context; German agent handles with live translation | Arabic | German | High |
| 8.3 | Swiss French retention – info/general → German | Swiss French-speaking merchant requests information before deciding to cancel; German agent handles with live translation | French (Swiss) | German | High |
| 8.4 | Swiss Italian retention – service complaint → German | Swiss Italian-speaking merchant at churn risk; German agent handles with live translation | Italian (Swiss) | German | High |
| 8.5 | German retention – service complaint → Polish | German-speaking merchant at churn risk calls to Krakow; Polish agent handles with live translation | German | Polish | Medium |
| 8.6 | Turkish retention – info/general → English | Turkish-speaking merchant seeks general information before deciding to cancel; English agent handles | Turkish | English | Medium |
| 8.7 | Arabic retention – service complaint → English | Arabic-speaking merchant in churn risk; English-speaking retention agent handles with live translation | Arabic | English | Medium |

---

## Category 9 – Fraud & Dispute Calls

> **CRM categories (DAC):** `CA_00850000` – Fraud & Dispute (and related DAC dispute/fraud sub-categories)

These use cases cover inbound calls related to suspected fraud on merchant terminals, disputed transactions, and chargeback queries. Accurate real-time translation of amounts, dates, and transaction identifiers is essential.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 9.1 | Turkish fraud report → German | Turkish-speaking merchant reports suspected fraud on their terminal; German agent handles with live translation | Turkish | German | High |
| 9.2 | Arabic dispute query → German | Arabic-speaking merchant disputes a transaction; German agent handles with live translation | Arabic | German | High |
| 9.3 | Swiss French fraud report → German | Swiss French-speaking merchant reports an unauthorised transaction; German agent handles with live translation | French (Swiss) | German | High |
| 9.4 | Swiss Italian dispute query → German | Swiss Italian-speaking merchant queries a chargeback; German agent handles with live translation | Italian (Swiss) | German | High |
| 9.5 | Swiss German dialect fraud report → Standard German | Swiss German dialect-speaking merchant reports fraud; agent receives Standard German live translation | Swiss German | German | High |
| 9.6 | German fraud report → Polish | German-speaking merchant reports suspected fraud; Polish Krakow agent handles with live translation | German | Polish | Medium |
| 9.7 | Turkish dispute query → English | Turkish-speaking merchant disputes a transaction with an English-speaking agent | Turkish | English | Medium |
| 9.8 | Arabic fraud report → English | Arabic-speaking merchant reports fraud to an English-speaking agent | Arabic | English | Medium |

---

## Platform Notes for DAC

| Platform | DAC Availability | Notes |
|----------|-----------------|-------|
| **Boost** | ❌ Not currently available | Use cases documented for evaluation with other platforms |
| **Genesis** | ✅ Available | Primary platform for DAC |
| **Sinch** | 🔍 To evaluate | Real-time translation and speech analytics offered |
| **Found Ever** | 🔍 To evaluate | Offered free of charge for 3 years; no phone system integration required |

---

## Notes

- Turkish and Arabic use cases are driven by large non-German-speaking merchant populations in Germany
- Swiss variant use cases cover three official languages: Swiss German dialect, French, and Italian
- Baseline tests (Category 5) should always be run first to establish a quality benchmark
- Categories 7–9 expand coverage to all CRM case handling types identified in `crm-category-mapping.md`
- Retention calls (Category 8) are high-sensitivity; translation accuracy is especially critical for agent empathy and merchant trust
- Fraud & Dispute calls (Category 9) require precise translation of amounts, dates, and transaction IDs – after-call summary (Category 6.6) is strongly recommended for these call types
- This list should be evaluated against Genesis, Sinch, and Found Ever capabilities before finalising PoC scope
