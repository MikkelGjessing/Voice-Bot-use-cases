# Voice Bot Use Cases – DAC Merchant Services

> **Region:** DAC (Germany, Austria, Switzerland)
> **Platform:** Boost PoC (reusable for Genesis, Sinch, Found Ever)
> **Note:** Boost is not currently part of the DAC merchant services platform. Use cases documented here for future platform evaluation (Genesis, Sinch, Found Ever).
> **Last updated:** July 2026

---

## Category 1 – Smart Switchboard (Intent Routing)

| # | Use Case | Description | Language | Priority |
|---|----------|-------------|----------|----------|
| 1.1 | Intent routing – general merchant enquiry | Customer calls and explains issue; voice bot routes to correct queue | German | High |
| 1.2 | Error transfer elimination – terminal queue | Customer intending terminal support routed directly without hitting wrong queue | German | High |
| 1.3 | Error transfer elimination – e-com queue | Customer intending e-com support routed directly | German | High |
| 1.4 | Error transfer elimination – acquiring queue | Customer intending acquiring support routed directly | German | Medium |
| 1.5 | SMS self-service link delivery | After routing, SMS with relevant self-service links sent to caller | German | High |
| 1.6 | Killer question filtering – new vs. existing merchant | Voice bot distinguishes onboarding calls from support calls | German | Medium |
| 1.7 | Out-of-hours routing | Outside business hours, voice bot handles routing and deflects to self-service | German | Medium |

---

## Category 2 – Terminal Error Code Handling

| # | Use Case | Description | Language | Priority |
|---|----------|-------------|----------|----------|
| 2.1 | Error code lookup – customer reads code | Customer reads terminal error code; voice bot provides resolution steps | German | High |
| 2.2 | Error code lookup – DTMF fallback | Customer inputs error code via keypad if speech recognition fails | German | High |
| 2.3 | Common error code self-resolution | Voice bot resolves top 10 most frequent terminal error codes | German | High |
| 2.4 | Terminal activation guidance | Voice bot walks new merchant through terminal activation steps | German | High |
| 2.5 | Error code escalation to agent | If error code unknown or complex, voice bot transfers with context pre-filled | German | Medium |
| 2.6 | Terminal reboot guidance | Voice bot guides customer through terminal restart steps | German | Medium |
| 2.7 | Terminal connectivity troubleshooting | Voice bot walks customer through connectivity checks | German | Medium |

---

## Category 3 – Real-Time Voice Translation (Multilingual DAC)

The DAC region has a large population of non-German native speakers. These use cases address multilingual support needs.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 3.1 | Turkish → German | Turkish-speaking merchant to German-speaking agent | Turkish | German | High |
| 3.2 | Arabic → German | Arabic-speaking merchant to German-speaking agent | Arabic | German | High |
| 3.3 | Turkish → English | Turkish-speaking merchant to English-speaking agent | Turkish | English | Medium |
| 3.4 | Arabic → English | Arabic-speaking merchant to English-speaking agent | Arabic | English | Medium |
| 3.5 | Swiss German → Standard German | Swiss German dialect speaker to Standard German agent | Swiss German | German | High |
| 3.6 | French (Swiss) → German | Swiss French speaker to German-speaking agent | French (Swiss) | German | High |
| 3.7 | Italian (Swiss) → German | Swiss Italian speaker to German-speaking agent | Italian (Swiss) | German | High |
| 3.8 | French (Swiss) → French | Swiss French speaker to French-speaking agent | French (Swiss) | French | Medium |
| 3.9 | Italian (Swiss) → Italian | Swiss Italian speaker to Italian-speaking agent | Italian (Swiss) | Italian | Medium |
| 3.10 | German → Polish | German-speaking customer to Polish-speaking agent in Krakow | German | Polish | Medium |
| 3.11 | German → German | Same-language baseline test to validate translation layer quality | German | German | High |

---

## Category 4 – Live Agent Assist (In-Call AI Support)

| # | Use Case | Description | Language | Priority |
|---|----------|-------------|----------|----------|
| 4.1 | Real-time translation overlay for agent | Agent sees live translation of what customer is saying | Turkish / Arabic / Swiss variants | High |
| 4.2 | Knowledge article suggestion during call | Platform suggests relevant knowledge articles to agent based on conversation | German | Medium |
| 4.3 | After-call work automation | Platform generates call summary for agent at end of conversation | German / Polish | Medium |
| 4.4 | Dialect normalisation | Swiss German dialect speech normalised to Standard German for agent | Swiss German | High |

---

## Category 5 – Full Voice Bot Automation (Self-Service)

| # | Use Case | Description | Language | Priority |
|---|----------|-------------|----------|----------|
| 5.1 | Terminal activation guidance | Voice bot walks new merchant through terminal activation steps | German | High |
| 5.2 | Settlement enquiry | Voice bot answers questions about settlement timing and amounts | German | Medium |
| 5.3 | Chargeback status enquiry | Voice bot provides status on open chargebacks | German | Medium |
| 5.4 | Statement / invoice enquiry | Voice bot directs merchant to portal or sends self-service link | German | Medium |
| 5.5 | Contract / fee enquiry | Voice bot answers common questions about fees and contract terms | German | Low |
| 5.6 | Fraud alert handling | Voice bot confirms fraud alert and routes to specialist queue | German / Turkish | Medium |

---

## Platform Notes for DAC

| Platform | DAC Availability | Notes |
|----------|-----------------|-------|
| **Boost** | ❌ Not available | Use cases documented for other platforms |
| **Genesis** | ✅ Available | Primary platform for DAC; terminal activation use case already planned |
| **Sinch** | 🔍 To evaluate | Overlap with Genesis; real-time translation and speech analytics offered |
| **Found Ever** | 🔍 To evaluate | Offered free of charge for 3 years; no phone system integration required; may be limited for knowledge article answering |

---

## Notes

- Turkish and Arabic use cases are driven by large non-German-speaking merchant populations in Germany
- Swiss variant use cases cover three official languages: German (Swiss dialect), French, and Italian
- Terminal activation use case for DAC is already identified as a priority by operations
- This list should be evaluated against Found Ever and Genesis capabilities before finalising PoC scope
