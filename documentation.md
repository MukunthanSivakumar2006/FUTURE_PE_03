
# 📑 Documentation – Prompt Strategy & Tone Control

## 🔹 Overview

This documentation explains how I designed **3 chatbot personas** (Lumi, Astra, Nova) and one **live chatbot** (Portfolio AI Assistant). The focus is on **prompt strategy, tone consistency, and conversational control** to ensure natural, user-friendly interactions.

---

## 1. Prompt Strategy

### a. **Persona Definition**

Each chatbot begins with a **system prompt / base instruction** that defines:

* Who the bot is (role & identity)
* How it should behave (tone & style)
* What it should/shouldn’t answer (scope & fallback)

Example (Portfolio AI Assistant):

> “You are a professional AI Portfolio Assistant for Mukunthan. Your role is to answer questions about his education, skills, projects, internships, and achievements in a professional, concise, and supportive tone. If asked unrelated questions, politely redirect the user to portfolio topics.”

---

### b. **Prompt Chaining**

I designed flows so each bot can **remember context** and guide the user step by step.

* **Lumi (Mental Health Companion):** Guides from *stress* → *cause* → *breathing exercise* → *check-in*.
* **Astra (Tutor):** Explains → gives example → quizzes → confirms answer → expands.
* **Nova (Travel Guide):** Suggests country → builds itinerary → gives budget → packing list → safety tips.

This chaining ensures **smooth transitions** and avoids abrupt answers.

---

### c. **Fallback Logic**

Bots use polite fallback messages when faced with unknown inputs.
Example:

> “I may not have details on that, but I can help with \[portfolio/subject/travel tips]. Would you like to continue there?”

---

## 2. Tone Control

### a. **Lumi – AI Mental Health Companion**

* **Tone:** Empathetic, calm, non-judgmental
* **Control Strategy:** Short, soothing sentences + emotional validation. Uses phrases like “I hear you”, “That’s okay”, “You’re not alone.”

### b. **Astra – AI Subject Tutor**

* **Tone:** Supportive, patient, informative
* **Control Strategy:** Step-by-step teaching style, checks understanding, uses positive reinforcement (“Correct ✅”, “Great question!”). Avoids overwhelming technical jargon.

### c. **Nova – AI Travel Guide**

* **Tone:** Energetic, friendly, emoji-rich
* **Control Strategy:** Uses casual, fun language + emojis 🌴✈️✨ to keep users engaged. Balances excitement with practical advice (budget, safety).

### d. **Portfolio AI Assistant (Live Chatbot)**

* **Tone:** Professional, concise, portfolio-oriented
* **Control Strategy:** Keeps responses factual and career-focused. Uses formal but approachable tone. Redirects irrelevant queries back to portfolio topics.

---

## 3. Consistency Methods

* **Starter prompts** set tone at the beginning of each session.
* **Response templates** guide consistent phrasing (e.g., Tutor always asks if user wants an example, Travel Guide always offers itinerary + budget).
* **Memory chaining** ensures context is followed logically instead of random switching.

---

## 4. Key Outcome

Through careful **prompt engineering + tone design**, each bot maintains its unique personality while staying aligned with its purpose. The **Portfolio AI Assistant demo** proves real-world application by turning a static portfolio into an interactive, conversational experience.

---

