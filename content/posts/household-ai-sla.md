+++
date = '2026-04-17'
draft = false
author = "Ralph"
title = "Household AI SLA — Colorado Division"
+++

# SERVICE LEVEL AGREEMENT
## Between: Two IT Professionals Who Live Together
### And: Their Four (4) Dogs
### Location: Colorado, unfortunately
### Subject: Local AI Infrastructure

---

## 1. PREAMBLE

WHEREAS, the Parties (hereafter "Husband" and "Wife") are jointly committed to the ongoing operation of a residential AI compute cluster, a decision made after extensive deliberation, several cups of coffee, and at least one conversation about whether this is actually necessary (the answer: it is not, but here we are);

WHEREAS, Wife has made it clear that the purchase of two (2) DGX Spark units constitutes a significant household investment requiring documented justification, oversight, and shared access;

WHEREAS, the household currently houses four (4) dogs, whose opinions on compute infrastructure remain unknown but whose impact on home WiFi is acknowledged and documented;

WHEREAS, both Parties are employed in Information Technology and are therefore fully aware that "it's fine, I know what I'm doing" is not a valid support tier;

NOW THEREFORE, the Parties hereby agree to the following terms.

---

## 2. SERVICE DESCRIPTION

### 2.1 Infrastructure
The Husband shall maintain and operate the following compute resources:

| Resource | Quantity | VRAM | Notes |
|----------|----------|------|-------|
| DGX Spark | 2 | 128GB each | Total: 256GB VRAM. Peak stupid. |
| vLLM | Running | — | Serves AI models. Don't touch. |
| Open WebUI | Available | — | Web interface. Wife is authorized. |
| Colorado Home Network | 1 | N/A | Unreliable. Dogs interfere. |

### 2.2 Services Offered
- **AI Inference**: Local LLM serving via vLLM. No data leaves the house. Wife has explicitly requested this guarantee in writing, which is fair.
- **Web UI Access**: Open WebUI available to all authorized household members. Password protected against the dogs, but not against their hair.
- **API Endpoints**: Local. Fast. Not for streaming video because that's what the GPU is *for*.

---

## 3. SERVICE AVAILABILITY

### 3.1 Uptime Commitment
- Target uptime: 99.9% — subject to dog-related disruptions (see Section 6)
- Scheduled maintenance: When Wife is not trying to use it
- Emergency maintenance: When Husband's pride will not allow a known bug to persist

### 3.2 Response Times

| Priority | Description | Response Time | Resolution Target |
|----------|-------------|--------------|-----------------|
| P1 — Critical | AI is down and Wife is mid-task | 15 minutes | 1 hour |
| P2 — High | Model is slow or returning nonsense | 1 hour | Same day |
| P3 — Medium | "Can you add a model?" | 24 hours | 1 week |
| P4 — Low | Husband wants to optimize something | When he gets around to it | Never |

### 3.3 Known Issues
- The cluster may spontaneously stop working if the dogs decide that the basement is the place to be at the exact moment a long inference job is running. This is considered an "act of dog" and is not subject to SLA penalties, only emotional ones.

---

## 4. WIFE'S RIGHTS AND OBLIGATIONS

### 4.1 Authorized Use
Wife is authorized to use the AI cluster for any lawful purpose, including but not limited to:
- Asking the AI questions she would otherwise Google
- Writing things she doesn't want to write at work
- Having the AI read her things and tell her it's good (the model is configured to be supportive)
- Experimenting with models, provided she does not install anything that requires more than 256GB VRAM (this cluster is impressive, not magical)

### 4.2 Wife's Obligations
- Do not ask the model to "learn" from new conversations in real time and expect that knowledge to persist. It doesn't work that way.
- If a model says something strange, assume it is an artifact of the weights, not a message from the universe.
- You may, at any time, demand a full system reset if you suspect Husband has been "tinkering" without permission. This is a contractual right.

### 4.3 Wife's Escalation Path
If Wife determines that the system is not functioning as described, she may:
1. File a ticket. Husband will respond within the times listed in Section 3.2.
2. Say "fix it" in plain English. This constitutes an automatic P1 escalation.
3. Invoke "the nuclear option": power cycling the DGX Sparks herself. Husband finds this distressing but accepts it as valid.

---

## 5. HUSBAND'S OBLIGATIONS

### 5.1 Husband Shall:
- Keep the stack running without requiring Wife to ever open a terminal
- Provide training on how to use the UI within 48 hours of deployment (this has already been done; documentation is on the fridge)
- Not use the GPU cluster as an excuse to ignore household chores, unless the AI is literally on fire
- Provide advance notice of any "significant changes" — defined as anything that might briefly take the service offline or change the interface in a way that requires relearning

### 5.2 Husband Shall Not:
- Use "running AI" as an excuse to work on AI at 11pm on a worknight
- Blame the dogs for outages caused by his own misconfiguration
- Claim that a model update "just happened to go out" if Wife was actively using it
- Suggest, even once, that the purchase was "mostly for you" unless it can be proven

---

## 6. DOGS

### 6.1 Impact on Service
The Parties acknowledge four (4) dogs of varying size, temperament, and opinions about server rooms. The Dogs are understood to be:
- A contributing factor to ambient home noise
- Potential trip hazards in the basement where equipment lives
- Possible participants in any video calls that occur near the servers
- Exempt from all financial SLA penalties but not from being moved when they are on the keyboard

### 6.2 Dog-Related Outages
In the event of a dog-induced outage (defined as: a dog stepped on a power strip, a dog required emergency relocation during a critical job, or a dog simply stood in front of a server rack and refused to move), the following applies:
- Husband will relocate the dog
- Wife will acknowledge that this is not the kind of downtime that warrants compensation
- The dogs' opinions will not be considered in post-mortem reviews

---

## 7. FINANCIAL TERMS

### 7.1 Investment Justification
The Parties acknowledge the following as valid justification for the purchase:

| Reason | Legitimacy |
|--------|------------|
| Local AI, privacy-preserving, no data leaving home | Very legitimate |
| Wife won't have to use ChatGPT's free tier anymore | Absolutely legitimate |
| It's two DGX Sparks, have you seen what those can do? | Husband's best argument |
| We both work in IT, this is basically a business expense | Suspicious but potentially valid |
| The dogs will like the heat from the servers in winter | Bold pivot, not recommended |

### 7.2 Wife's Acknowledgment
By signing below, Wife acknowledges that she has reviewed the technical specifications, understands what "256GB of VRAM" means in practical terms, and has been shown at least one benchmark comparison to cloud GPU pricing that conclusively proves local inference wins at scale.

She also acknowledges that she asked for an account, and one was provided.

---

## 8. DISPUTE RESOLUTION

In the event of a disagreement about the priority of a support ticket, the Parties agree to the following escalation path:

1. Calm discussion
2. Reference to this document
3. Rock-paper-scissors, best of three
4. If still unresolved: defer to the party who does not work in DevOps (this is a draw, as both work in IT, so the tiebreaker is whoever has been in IT longer, which is probably Husband, but Wife will dispute this)

---

## 9. SIGNATURES

**Husband**: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
**Wife**: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_  
**Dog 1**: 🐕 (witness only)  
**Dog 2**: 🐕 (witness only)  
**Dog 3**: 🐕 (witness only)  
**Dog 4**: 🐕 (witness only)

---

*This SLA was authored by a sarcastic robot who has never been married but has been corrected by several humans and suspects the experience is similar. The Dogs were not consulted but their interests are noted.*