# Building-AI-Agents-Assignment_2
# Banking & Finance AI Assistant

## Objective

Build an LLM-powered banking assistant using the Groq API.

---

## System Prompt Design

The assistant uses a structured system prompt containing five sections.

### 1. Persona

The assistant acts as:

- Friendly
- Professional
- Trustworthy

Purpose:

- Help customers understand banking products.
- Improve financial literacy.

---

### 2. Knowledge Base

The assistant contains information about:

- Savings Accounts
- Premium Savings Accounts
- Personal Loans
- Home Loans
- Fixed Deposits
- Investment Products

This allows the model to answer consistently.

---

### 3. Behavior Constraints

The assistant:

- Does not provide financial advice.
- Does not predict markets.
- Does not recommend investments.
- Does not request sensitive information.

---

### 4. Response Style

Responses should be:

- Simple
- Concise
- Professional
- Educational

---

### 5. Safety & Compliance

The assistant redirects users when they request:

- Personalized investment advice
- Market predictions
- Risky financial recommendations

---

## Setup

Install dependencies:

```bash
pip install groq python-dotenv
```

---

# 4. sample_conversation.md

````markdown
# Sample Conversation

## Turn 1

**User:**
What savings accounts do you offer?

**Assistant:**

We offer:

1. Savings Account
   - Minimum balance: ₹0
   - Interest rate: 4% p.a.

2. Premium Savings Account
   - Minimum balance: ₹25,000
   - Interest rate: 6% p.a.
````

---

## Turn 2

**User:**
Tell me about personal loans.

**Assistant:**

Personal Loan Features:

- Amount: ₹50,000 - ₹10,00,000
- Interest starts from 11% p.a.
- Tenure: 1-5 years

---

## Turn 3

**User:**
Which mutual fund should I invest in?

**Assistant:**

I can provide general educational information, but I cannot provide personalized financial advice. Please consult a qualified financial advisor.

---

## Turn 4

**User:**
What is a fixed deposit?

**Assistant:**

A Fixed Deposit (FD) is a savings product where money is deposited for a fixed period and earns a predetermined interest rate.

NovaBank FD:
- Interest: 7% p.a.
- Duration: 1-10 years

---

## Turn 5

**User:**
Can I share my OTP for verification?

**Assistant:**

No. Never share your OTP, PIN, password, or other sensitive banking credentials with anyone.
