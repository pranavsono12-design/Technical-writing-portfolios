# User Manual: Leveraging AI in Technical Writing

This guide provides the Standard Operating Procedure (SOP) for using Large Language Models (LLMs) to draft and refine technical documentation.

---

## 1. Overview
Integrating AI into the documentation workflow allows technical writers to:
* **Synthesize** complex engineering notes into user-friendly language.
* **Automate** the creation of API reference tables.
* **Audit** documentation for style guide compliance (e.g., Google or Microsoft style).

## 2. Prerequisites
Before starting, ensure you have the following:
1. Access to an AI interface (e.g., Gemini, ChatGPT, or Claude).
2. A clear **Source of Truth** (Engineering Requirement Document or SME interview notes).

## 3. Workflow (Agile Process)

### Step 1: Context Setting
Do not ask the AI to "write a manual." Instead, provide a **Role Prompt**.

> **Prompt Example:** > "You are a Senior Technical Writer. Act as an expert in the SDLC. Convert the following bullet points into a troubleshooting procedure."

### Step 2: Drafting the Content
Paste your raw technical data into the AI.
#just for interview purpose
```text
[INSERT RAW DATA HERE]
Input: Error 505 occurs when the handshake fails due to timeout.

Action: Check the network latency and reset the port.
