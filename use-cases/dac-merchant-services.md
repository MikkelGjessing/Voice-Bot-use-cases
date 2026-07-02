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

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 1.1 | Turkish → German | Turkish-speaking merchant to German-speaking agent | Turkish | German | High |
| 1.2 | Arabic → German | Arabic-speaking merchant to German-speaking agent | Arabic | German | High |
| 1.3 | Swiss French → German | Swiss French-speaking merchant to German-speaking agent | French (Swiss) | German | High |
| 1.4 | Swiss Italian → German | Swiss Italian-speaking merchant to German-speaking agent | Italian (Swiss) | German | High |
| 1.5 | Swiss German dialect → Standard German | Swiss German dialect speaker to Standard German-speaking agent | Swiss German | German | High |

---

## Category 2 – Non-German Speakers → English-Speaking Agent

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 2.1 | Turkish → English | Turkish-speaking merchant to English-speaking agent | Turkish | English | Medium |
| 2.2 | Arabic → English | Arabic-speaking merchant to English-speaking agent | Arabic | English | Medium |

---

## Category 3 – Swiss Official Languages → Native Agent

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 3.1 | Swiss French → French | Swiss French-speaking merchant to French-speaking agent | French (Swiss) | French | Medium |
| 3.2 | Swiss Italian → Italian | Swiss Italian-speaking merchant to Italian-speaking agent | Italian (Swiss) | Italian | Medium |

---

## Category 4 – German → Polish (Krakow Agent Centre)

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 4.1 | German → Polish | German-speaking merchant to Polish-speaking agent in Krakow | German | Polish | Medium |
| 4.2 | Turkish → Polish | Turkish-speaking merchant to Polish-speaking agent in Krakow | Turkish | Polish | Low |

---

## Category 5 – Baseline & Quality Validation

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 5.1 | German → German | Same-language call to validate that translation layer adds no degradation | German | German | High |
| 5.2 | Turkish → Turkish | Same-language baseline test for Turkish | Turkish | Turkish | Medium |

---

## Category 6 – Live Agent Assist During Translation

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 6.1 | Live translation overlay – Turkish to German | Agent sees live Turkish-to-German text translation during the call | Turkish | German | High |
| 6.2 | Live translation overlay – Arabic to German | Agent sees live Arabic-to-German text translation during the call | Arabic | German | High |
| 6.3 | Live translation overlay – Swiss variants to German | Agent sees live translation of Swiss French or Italian to German | French (Swiss) / Italian (Swiss) | German | High |
| 6.4 | Swiss German dialect normalisation | Swiss German dialect speech is normalised to Standard German for the agent in real time | Swiss German | German | High |
| 6.5 | Bidirectional translation | Agent response is also translated back to customer's language in real time | All DAC languages | German / English / Polish | High |
| 6.6 | After-call summary in agent language | Platform generates a post-call summary in the agent's language after the conversation | All DAC languages | German / Polish | Medium |

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
- This list should be evaluated against Genesis, Sinch, and Found Ever capabilities before finalising PoC scope
