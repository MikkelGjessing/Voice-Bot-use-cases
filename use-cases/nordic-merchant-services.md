# Voice Bot Use Cases – Nordic Merchant Services

> **Region:** Nordics (Denmark, Sweden, Norway, Finland)
> **Platform:** Boost PoC (reusable for Genesis, Sinch, Found Ever)
> **Last updated:** July 2026

---

## Category 1 – Smart Switchboard (Intent Routing)

These use cases extend the current "glorified switchboard" model by expanding intent recognition and reducing error transfers.

| # | Use Case | Description | Language | Priority |
|---|----------|-------------|----------|----------|
| 1.1 | Intent routing – general merchant enquiry | Customer calls and explains their issue in one or two sentences; voice bot routes to correct queue | Danish / Swedish / Norwegian / Finnish | High |
| 1.2 | Error transfer elimination – e-com queue | Customer intending e-com support is routed directly without hitting wrong queue first | Danish | High |
| 1.3 | Error transfer elimination – terminal queue | Customer intending terminal support is routed directly | Danish / Swedish / Norwegian | High |
| 1.4 | Error transfer elimination – acquiring queue | Customer intending acquiring support is routed directly | Danish / Swedish | Medium |
| 1.5 | SMS self-service link delivery | After routing, an SMS with relevant self-service links is sent to the caller's number | All Nordic languages | High |
| 1.6 | Killer question filtering – e-com vs. terminal | Voice bot asks a single qualifying question to distinguish e-com from terminal customers | Danish | High |
| 1.7 | Killer question filtering – new vs. existing merchant | Voice bot distinguishes onboarding calls from support calls | Danish / Swedish | Medium |
| 1.8 | Out-of-hours routing | Outside business hours, voice bot handles routing and deflects to self-service | All Nordic languages | Medium |

---

## Category 2 – Terminal Error Code Handling

Short, closed-loop conversations around terminal error codes with minimal customer input required.

| # | Use Case | Description | Language | Priority |
|---|----------|-------------|----------|----------|
| 2.1 | Error code lookup – customer reads code | Customer reads out a terminal error code; voice bot provides resolution steps | Danish | High |
| 2.2 | Error code lookup – DTMF fallback | Customer inputs error code via keypad if speech recognition fails | All Nordic languages | High |
| 2.3 | Common error code self-resolution | Voice bot resolves top 10 most frequent terminal error codes without agent transfer | Danish / Swedish | High |
| 2.4 | Error code escalation to agent | If error code is unknown or complex, voice bot transfers with context pre-filled | All Nordic languages | Medium |
| 2.5 | Terminal reboot guidance | Voice bot guides customer through terminal restart steps | Danish / Norwegian | Medium |
| 2.6 | Terminal connectivity troubleshooting | Voice bot walks customer through basic connectivity checks (cable, SIM, WiFi) | Danish / Swedish | Medium |
| 2.7 | Receipt printer error guidance | Voice bot handles common printer error codes | Danish | Low |

---

## Category 3 – Real-Time Voice Translation (Nordic → Agent Language)

Customer speaks in their native Nordic language; agent speaks in another language. Boost provides live translation in both directions.

| # | Use Case | Description | Customer Language | Agent Language | Priority |
|---|----------|-------------|-------------------|----------------|----------|
| 3.1 | Danish → Polish | Danish merchant customer to Polish-speaking agent in Krakow | Danish | Polish | High |
| 3.2 | Swedish → Polish | Swedish merchant customer to Polish-speaking agent in Krakow | Swedish | Polish | High |
| 3.3 | Norwegian → Polish | Norwegian merchant customer to Polish-speaking agent in Krakow | Norwegian | Polish | High |
| 3.4 | Finnish → Polish | Finnish merchant customer to Polish-speaking agent in Krakow | Finnish | Polish | High |
| 3.5 | Danish → English | Danish customer to English-speaking agent | Danish | English | Medium |
| 3.6 | Swedish → English | Swedish customer to English-speaking agent | Swedish | English | Medium |
| 3.7 | Norwegian → English | Norwegian customer to English-speaking agent | Norwegian | English | Medium |
| 3.8 | Finnish → English | Finnish customer to English-speaking agent | Finnish | English | Medium |
| 3.9 | Danish → Danish | Same-language baseline test to validate translation layer quality | Danish | Danish | High |

---

## Category 4 – Live Agent Assist (In-Call AI Support)

Boost stays active during the agent conversation to assist with translation, suggested answers, or knowledge article lookups.

| # | Use Case | Description | Language | Priority |
|---|----------|-------------|----------|----------|
| 4.1 | Real-time translation overlay for agent | Agent sees live translation of what customer is saying during the call | Danish / Swedish / Norwegian / Finnish | High |
| 4.2 | Knowledge article suggestion during call | Boost suggests relevant knowledge articles to the agent based on conversation content | Danish | Medium |
| 4.3 | After-call work automation | Boost generates a call summary for the agent at end of conversation | Danish / Polish | Medium |
| 4.4 | Sentiment detection alert | Boost alerts agent if customer sentiment becomes strongly negative | Danish | Low |

---

## Category 5 – Full Voice Bot Automation (Self-Service)

Voice bot handles the entire conversation without agent involvement, answering questions from knowledge articles.

| # | Use Case | Description | Language | Priority |
|---|----------|-------------|----------|----------|
| 5.1 | Terminal activation guidance | Voice bot walks new merchant through terminal activation steps | Danish / Swedish | High |
| 5.2 | Settlement enquiry | Voice bot answers questions about settlement timing and amounts | Danish | Medium |
| 5.3 | Chargeback status enquiry | Voice bot provides status update on open chargebacks | Danish / Swedish | Medium |
| 5.4 | Statement / invoice enquiry | Voice bot directs merchant to correct portal or sends self-service link | Danish | Medium |
| 5.5 | Contract / fee enquiry | Voice bot answers common questions about fees and contract terms | Danish | Low |
| 5.6 | New terminal order | Voice bot captures terminal order details and confirms submission | Danish | Low |
| 5.7 | Fraud alert handling | Voice bot confirms fraud alert and routes to specialist queue | Danish / Swedish / Norwegian | Medium |

---

## Notes

- All use cases marked **High** priority are candidates for Phase 1 PoC testing with Boost
- Use cases in Category 3 are the primary interest for Oscar (issuing, Nordics + DAC)
- Categories 1 and 2 are the strongest candidates for an initial closed-loop test given existing switchboard infrastructure
- This list should be reviewed jointly with Oscar's issuing team before finalising PoC scope
