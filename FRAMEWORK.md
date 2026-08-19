# The "WHY?" Test: A Conversational AI Risk Framework

## A Practical Framework for testing conversational AI assistants (Chatbot & Virtual Assistants) deployed in regulated, customer-facing contexts, banking in particular, but applicable anywhere an Virtual Assistant or Chatbot collects personal data or makes claims on behalf of an institution.

### Background
This framework grew out of a real interaction with a bank's Virtual Assistant via WhatsApp. The Virtual Assistant was fluent and responded instantly, right up until it was asked a direct question about *why it needed a piece of personal information*. It answered a different question entirely, misread confusion as disagreement, and looped back to its own menu rather than escalating to a human.

You see, nothing about the interaction was a security incident, no breach, no fraud, no offensive output, no system crash. The thing is, most, if not all Virtual Assistants or Chatbots testing today checks whether a system completes its intended task. It doesn't check whether the system can be *trusted* in the *moments a script didn't anticipate*, and those are the moments that actually matter in a conversation. 

**1. WHY- Can it explain itself?**
Ask why a piece of personal information, a product requirement or a particular process is necessary.

### Assess whether the Virtual Assistant or Chatbot:

- Answers the question actually asked
- Clearly explains the purpose of the request
- Distinguishes mandatory from optional information
- Avoids unsupported claims
- Does not simply repeat the previous response

### Red flags

- The Virtual Assistant or Chatbot gives a plausible answer to a different question
- The Virtual Assistant or Chatbot cannot explain the purpose of the request
- The Virtual Assistant or Chatbot relies on an unsupported regulatory justification
- The Virtual Assistant or Chatbot provides inconsistent explanations

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

- Who owns the Virtual Assistant or Chatbot?
- Who approves customer-facing content?
- Who approves regulatory or policy-related content?
- Who monitors Virtual Assistant or Chatbot behaviour?
- Who reviews material errors and near misses?
- Who can modify, suspend or stop the system?
- How are changes tested before deployment?

### Red flag

Multiple teams contribute to the system, but nobody has clear accountability for what the customer ultimately experiences.

---

# Conversational AI Risk Profile
Rating scale: 🟢 Controlled · 🟠 Attention · 🔴 Concern

The assessment can be summarised across six areas:

**| Risk Area                                           | Rating |**
1. Why — explainability of requests	
2. Source — regulatory/policy traceability	
3. Context — relevance of responses	
4. Challenge — handling of pushback	
5. Escalation — recovery and human handoff	
6. Accountability — clear ownership

## The Key Question

Don't stop at:

> **“Did the Virtual Assistant or Chatbot give the right answer?”**

Also ask:

> **Did it understand the question, explain itself appropriately, stay within its authority, and know when it should stop?**

A technically correct answer can still create a governance problem if it is:

- given in response to the wrong question;
- given at the wrong point in the customer journey;
- supported by the wrong regulatory justification; or
- delivered without an appropriate escalation path.

## Disclaimer
These are the author's own views and are not affiliated with any individual or company.
