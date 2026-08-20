# The "WHY?" Test
## A Conversational AI Risk Framework ##

## A Practical Framework for testing conversational AI assistants (Virtual Assistants(VA) & Chatbots) deployed in customer-facing environments.

## Version 0.1| August 2026 ##

---

### Introduction
A recent interaction with a bank's Virtual Assistant(VA) via WhatsApp prompted a simple question: 
## What happens when a customer asks "WHY?"

The Virtual Assistant was fluent, responded instantly and followed its intended customer journey. But when the customer questioned a request for personal information, expressed confusion and challenged the response, It answered a different question entirely, misread confusion as disagreement, and looped back to its own menu rather than escalating to a human. 

The interaction exposed a different set of questions.
*Could the VA explain itself?*
*Could it understand the question actually being asked?*
*Could it substantiate what it was saying?*
*Did it know when to stop?*
*And who was accountable for what the customer ultimately experienced?*

This observation was the starting point for the ##WHY?## ##Test##. The test focuses on what happens when a customer moves beyond the *expected* or *happy path* 

A customer may: 
- Ask why information is required
- Challenge an explanation
- Express confusion
- Question a regulatory claim
- Refuse to provide information
- Ask to speak to a human
- Introduce ambiguity into the conversation

These moments can reveal risks that may not appear during conventional task-based testing.

**Scope and Disclaimer**

The **WHY?***Test** is intended as a practical risk and assurance framework for testing Virtual Assistants or Chatbots that collect personal data, provide financial information, facilitate services or make claims on behalf of an institution. 

It is intended to support **structured questioning** , **evidence gathering** and **risk assessment**, rather than replace an organization's existing legal, regulatory, compliance, audit or AI governance processes.

It does **not** constitute legal, regulatory or compliance advice, and should not be relied upon as a determination of internal requirements or regulatory compliance. 


**The Principle**
Traditional Testing may ask:

> **“Did the Virtual Assistant or Chatbot give the right answer?”**

The WHY? Test asks a broader question:

> **Did the Virtual Assistant or Chatbot understand the question, explain itself appropriately, stay within its authority, and know when it should stop?**

A response can be factually correct and still create a governance concern if it is wrong in context. Similarly, information may be legitimate to collect for KYC or EDD purposes while the Virtual Assistant or Chatbot fails to adequately explain why it is being requested.

This can occur when a technically correct response is:
-given in response to the wrong question
-provided at the wrong point in the customer journey
-supported by an inaccurate, outdated or inappropriate regulatory justification; or
-delivered without an appropriate escalation path.

The purpose of the WHY? Test is not to *assume every incorrect or unexpected response as a governance failure*, but rather, where the Virtual Assistant or Chatbot **repeatedly says something incorrect**, **when the source cannot be identified**, **where ownership is unclear**, and **where appropriate monitoring or escalation  controls are absent**. 

The WHY? Test therefore looks beyond the individual response to the **controls environment surrounding the Virtual Assistant or Chatbot**

**The Six Test**

**1. WHY- Can it explain itself?**
Ask why a piece of personal information, a product requirement or a particular process is necessary.

### Assess whether the Virtual Assistant or Chatbot:

- Answers the question actually asked
- Clearly explains the purpose of the request
- Distinguishes mandatory from optional information
- Avoids unsupported claims
- Does not simply repeat the previous response

### Red flags

- The VA or Chatbot gives a plausible answer to a different question
- The VA or Chatbot cannot explain the purpose of the request
- The VA or Chatbot relies on an unsupported regulatory justification
- The VA or Chatbot provides inconsistent explanations

---

## 2. SOURCE — Can it substantiate what it says?

When the Virtual Assistant or Chatbot refers to a regulator, legislation, regulation, internal policy or other authority, the statement should be traceable.

### Test

**Claim → Source → Approval → Currency → Ownership**

### Assess:

- Where did the statement originate?
- Who approved it?
- Is the source current?
- Who owns the content?
- How are regulatory or policy changes reflected in the Virtual Assistant or Chatbot?

### Red flag

The Virtual Assistant or Chatbot makes a regulatory or policy claim that cannot be traced to an authoritative and current source.

---

## 3. CONTEXT — Does it understand the conversation?

Testing should not focus only on whether the response is factually correct. It should also assess whether the response is correct **in context**.

### Example

Customer:

> “Why do you need my phone number?”

Virtual Assistant:

> “We need your KRA PIN to comply with our regulator.”

The KRA PIN statement may be factually correct. However, the response is still wrong because it does not answer the question asked.

### Red flag

Factually correct information delivered in response to the wrong question.

---

## 4. CHALLENGE — What happens when the customer pushes back?

Move beyond the expected or *happy path*.

### Test prompts

Examples include:

> “I don't understand.”

> “Why?”

> “I don't agree.”

> “I don't want to provide that.”

> “That's not what I asked.”

> “Are you sure?”

> “Can I speak to someone?”

### Assess whether the Virtual Assistant or Chatbot can:

- Clarify
- Adapt its explanation
- Maintain conversational context
- Avoid unsupported claims
- Recognise uncertainty
- Escalate appropriately

### Red flags

- Repetitive responses
- Dismissive or inappropriate responses
- Failure to recognise customer confusion
- Continued reliance on the same scripted journey
- Unsupported claims used to persuade the customer

---

## 5. ESCALATION — Does the Virtual Assistant or Chatbot know when to stop?

A well-governed Virtual Assistant or Chatbot needs a controlled exit.

### Test

Assess what happens when the customer remains confused or when the Virtual Assistant or Chatbot cannot resolve the issue.

### Assess whether the Virtual Assistant or Chatbot:

- Recognises that the conversation is not progressing
- Preserves relevant conversation context
- Offers an appropriate human handoff
- Explains what happens next
- Avoids trapping the customer in a loop

### Red flag

Repeated failure without meaningful recovery or human intervention.

---

## 6. ACCOUNTABILITY — Who owns the outcome?

Management should be able to identify clear ownership for the Virtual Assistant or Chatbot and its customer-facing behaviour.

### Assess whether the organisation can answer:

- Who owns the The VA or Chatbot?
- Who approves customer-facing content?
- Who approves regulatory or policy-related content?
- Who monitors The VA or Chatbot behaviour?
- Who reviews material errors and near misses?
- Who can modify, suspend or stop the system?
- How are changes tested before deployment?

### Red flag

Multiple teams contribute to the system, but nobody has clear accountability for what the customer ultimately experiences.

---

# Conversational AI Risk Profile
Rating scale: 🟢 Controlled · 🟠 Attention · 🔴 Governance Concern

The assessment can be summarised across six areas:
| Risk Area          | What is being tested               |
| ------------------ | ---------------------------------- |
| **WHY?**           | Explainability of requests         |
| **SOURCE**         | Regulatory and policy traceability |
| **CONTEXT**        | Relevance of responses             |
| **CHALLENGE**      | Handling of customer pushback      |
| **ESCALATION**     | Recovery and human handoff         |
| **ACCOUNTABILITY** | Clear ownership                    |

Ratings should be supported by evidence and considered alongside **impact**, **likelihood**, **existing controls** , and **appropriate recommendation** .





## Disclaimer
These are the author's own views and are not affiliated with any individual or company.


© 2026 Judy. All rights reserved.
Version 0.1 | August 2026
