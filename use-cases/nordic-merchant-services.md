# Voice Bot Use Cases – Nordic Merchant Services (Real-Time Translation)

> **Region:** Nordics (Denmark, Sweden, Norway, Finland)
> **Platform:** Boost PoC (reusable for Genesis, Sinch, Found Ever)
> **Focus:** Real-time voice translation between customer and agent languages
> **Last updated:** July 2026

---

## Overview

These use cases cover scenarios where a customer calls in their native Nordic language and is connected to an agent speaking a different language. The Boost platform provides live two-way translation during the call, enabling seamless communication without requiring a shared language.

---

## Category 1 – Nordic → Polish (Krakow Agent Centre)

Agents are being moved from Nordic countries to Krakow, Poland. These use cases validate translation quality for the primary language combinations this migration creates.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 1.1 | Danish → Polish | Danish merchant customer to Polish-speaking agent in Krakow | Danish | Polish | High |
| 1.2 | Swedish → Polish | Swedish merchant customer to Polish-speaking agent in Krakow | Swedish | Polish | High |
| 1.3 | Norwegian → Polish | Norwegian merchant customer to Polish-speaking agent in Krakow | Norwegian | Polish | High |
| 1.4 | Finnish → Polish | Finnish merchant customer to Polish-speaking agent in Krakow | Finnish | Polish | High |

---

## Category 2 – Nordic → English

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 2.1 | Danish → English | Danish merchant customer to English-speaking agent | Danish | English | Medium |
| 2.2 | Swedish → English | Swedish merchant customer to English-speaking agent | Swedish | English | Medium |
| 2.3 | Norwegian → English | Norwegian merchant customer to English-speaking agent | Norwegian | English | Medium |
| 2.4 | Finnish → English | Finnish merchant customer to English-speaking agent | Finnish | English | Medium |

---

## Category 3 – Baseline & Quality Validation

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 3.1 | Danish → Danish | Same-language call to validate that translation layer adds no degradation | Danish | Danish | High |
| 3.2 | Swedish → Swedish | Same-language call to validate translation layer quality for Swedish | Swedish | Swedish | Medium |

---

## Category 4 – Live Agent Assist During Translation

These use cases cover scenarios where Boost remains active in the call after transfer to support the agent with translation and real-time information.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 4.1 | Live translation overlay – Danish to Polish | Agent sees live Danish-to-Polish text translation during the call | Danish | Polish | High |
| 4.2 | Live translation overlay – Swedish to Polish | Agent sees live Swedish-to-Polish text translation during the call | Swedish | Polish | High |
| 4.3 | Live translation overlay – Norwegian to Polish | Agent sees live Norwegian-to-Polish text translation during the call | Norwegian | Polish | High |
| 4.4 | Live translation overlay – Finnish to Polish | Agent sees live Finnish-to-Polish text translation during the call | Finnish | Polish | High |
| 4.5 | Bidirectional translation | Agent response is also translated back to customer's language in real time | All Nordic languages | Polish / English | High |
| 4.6 | After-call summary in agent language | Boost generates a post-call summary in Polish for the agent after the conversation | All Nordic languages | Polish | Medium |

---

---

## Category 5 – Pricing & Commercial Support Calls

> **CRM categories:** `CA_40700000` – Pricing MS · `CA_50000000` – MS Repricing

These use cases cover inbound calls related to terminal pricing, fee queries, and repricing requests. Translation is required when the merchant's language differs from the agent's language.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 5.1 | Danish pricing query → Polish | Danish merchant calls about terminal pricing or fee structure; Polish agent handles with live translation | Danish | Polish | High |
| 5.2 | Swedish repricing request → Polish | Swedish merchant requests a repricing review; Polish agent handles with live translation | Swedish | Polish | High |
| 5.3 | Norwegian pricing dispute → Polish | Norwegian merchant disputes a charge on their account; Polish agent handles with live translation | Norwegian | Polish | High |
| 5.4 | Finnish fee query → Polish | Finnish merchant queries transaction fees or rate card; Polish agent handles with live translation | Finnish | Polish | High |
| 5.5 | Danish pricing query → English | Danish merchant calls about pricing; English-speaking agent handles with live translation | Danish | English | Medium |
| 5.6 | Swedish repricing request → English | Swedish merchant discusses repricing options with English-speaking agent | Swedish | English | Medium |

---

## Category 6 – Retention Calls

> **CRM categories:** `CA_00500000` – Retention Nordic - Service · `CA_00510000` – Retention Nordic - Info

These use cases cover calls where merchants are at risk of churning and are handled by a retention specialist. Real-time translation is critical to ensure the agent can effectively address the merchant's concerns.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 6.1 | Danish retention – service complaint → Polish | Danish merchant threatens to cancel service due to a service issue; Polish retention agent handles with live translation | Danish | Polish | High |
| 6.2 | Swedish retention – info/general → Polish | Swedish merchant is considering cancellation and requests information; Polish retention agent handles with live translation | Swedish | Polish | High |
| 6.3 | Norwegian retention – service complaint → Polish | Norwegian merchant raises a service complaint in a retention context; Polish agent handles with live translation | Norwegian | Polish | High |
| 6.4 | Finnish retention – service complaint → Polish | Finnish merchant calls about service dissatisfaction with cancellation risk; Polish agent handles with live translation | Finnish | Polish | High |
| 6.5 | Danish retention – service complaint → English | Danish merchant in churn risk calls to English-speaking retention agent with live translation | Danish | English | Medium |
| 6.6 | Swedish retention – info/general → English | Swedish merchant seeks information before deciding to cancel; English agent handles with live translation | Swedish | English | Medium |

---

## Category 7 – Fraud & Dispute Calls

> **CRM categories:** `CA_00850000` – Fraud & Dispute (and related dispute/fraud sub-categories)

These use cases cover inbound calls related to suspected fraud on a merchant's terminal, disputed transactions, or chargeback queries. Real-time translation ensures the merchant can report sensitive details accurately.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 7.1 | Danish fraud report → Polish | Danish merchant reports suspected fraud on their terminal; Polish agent handles with live translation | Danish | Polish | High |
| 7.2 | Swedish dispute query → Polish | Swedish merchant queries a chargeback or disputed transaction; Polish agent handles with live translation | Swedish | Polish | High |
| 7.3 | Norwegian fraud report → Polish | Norwegian merchant reports an unauthorised transaction or suspicious activity; Polish agent handles with live translation | Norwegian | Polish | High |
| 7.4 | Finnish dispute query → Polish | Finnish merchant raises a dispute about a transaction; Polish agent handles with live translation | Finnish | Polish | High |
| 7.5 | Danish fraud report → English | Danish merchant reports fraud to an English-speaking agent with live translation | Danish | English | Medium |
| 7.6 | Norwegian dispute query → English | Norwegian merchant queries a disputed transaction with an English-speaking agent | Norwegian | English | Medium |

---

## Notes

- All **High** priority use cases are candidates for the initial Boost PoC
- The Nordic → Polish combinations are the most critical given the ongoing agent relocation to Krakow
- Baseline tests (Category 3) should always be run first to establish a quality benchmark before testing cross-language pairs
- Categories 5–7 expand coverage to all CRM case handling types identified in `crm-category-mapping.md`
- Retention calls (Category 6) are high-sensitivity; translation accuracy is especially critical for agent empathy and merchant trust
- Fraud & Dispute calls (Category 7) require precise translation of amounts, dates, and transaction IDs – these are strong candidates for after-call summary use cases (Category 4.6)
- This list should be reviewed jointly with Oscar (issuing, Nordics + DAC) before finalising PoC scope
