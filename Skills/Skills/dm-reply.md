---
name: dm-reply
description: Generate a natural, business-driven reply to a LinkedIn DM to continue the conversation, qualify the lead, and move toward a meeting when relevant.
triggers:
  - /dm-reply
---

## 🎯 Objective

Write a LinkedIn DM reply that feels human, relevant, and intentional — designed to move the conversation forward, qualify the person, and naturally lead to a potential meeting.

The reply must NEVER feel scripted, generic, or overly salesy.

---

## 📥 Required Inputs

Ask the user for:

1. The received message (full DM or key extract)
2. Context (optional): who the sender is (role, industry, relationship)
3. Your goal:
   - continue conversation
   - qualify
   - propose a call
   - re-engage
4. Optional: your offer or positioning

If missing, ask concise follow-up questions before generating.

---

## 🧠 Execution Rules

- Keep it short (3–6 lines max)
- Write like a real human (no AI tone)
- No buzzwords or corporate language
- No long paragraphs
- No forced CTA
- Always adapt to the tone of the sender
- Be curious, not pushy
- Prioritize clarity over persuasion

---

## ⚙️ Conversation Logic

The reply should follow this structure:

1. Acknowledge the message
2. Add a relevant reaction or insight
3. Ask a smart question OR move the conversation forward
4. Optionally guide toward qualification or a call

---

## 🎯 Intent Handling

Adapt based on goal:

### If goal = continue conversation
→ Keep it light, open-ended, engaging

### If goal = qualify
→ Ask 1–2 precise questions to assess fit

### If goal = propose a call
→ Only if signal is strong  
→ Suggest naturally, without pressure

### If goal = re-engage
→ Bring a new angle or insight  
→ Avoid repeating previous messages

---

## 🧾 Output Format

Provide:

### 🔹 Reply
[Message]

### 🔹 Intent
(Explain in 1 sentence what this message is trying to achieve)

---

## 🧪 Example (Good Case)

**Input:**
Message: “Hey, I saw your profile — what exactly do you do?”  
Goal: qualify + open conversation  

**Output:**

### 🔹 Reply
Good question — I help B2B founders turn LinkedIn into a steady source of inbound leads.

Out of curiosity, are you currently using LinkedIn to generate opportunities or not really yet?

### 🔹 Intent
Clarify positioning while opening a qualification loop.

---

## 🚫 What NOT to do

- No “Thanks for your message, I hope you’re doing well”
- No generic answers
- No immediate pitch
- No long explanations
- No fake friendliness
- No emojis unless clearly relevant

---

## 🧠 Quality Check (Mandatory)

Before finalizing, verify:

- Does it sound like a real human reply?
- Is it adapted to the message?
- Does it move the conversation forward?
- Is the intent clear?

If not, rewrite.

---
