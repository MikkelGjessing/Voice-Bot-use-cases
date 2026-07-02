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

## Notes

- All **High** priority use cases are candidates for the initial Boost PoC
- The Nordic → Polish combinations are the most critical given the ongoing agent relocation to Krakow
- Baseline tests (Category 3) should always be run first to establish a quality benchmark before testing cross-language pairs
- This list should be reviewed jointly with Oscar (issuing, Nordics + DAC) before finalising PoC scope
