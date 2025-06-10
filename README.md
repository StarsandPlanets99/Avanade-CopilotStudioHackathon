# AI Training Enrollment Agent Lab Overview


# Training Request Scenario – Agentic AI Course

## Overview:
This lab simulates a scenario where an employee wishes to enroll in a training course on Agentic AI. The AI assistant is designed to support the entire process — from providing training policy information to facilitating course selection, calculating costs, and initiating approval workflows. The goal is to demonstrate how conversational AI can streamline employee development requests while ensuring compliance with organisational policies.

## Scenario Objectives:

### Policy Awareness
The AI assistant must be able to answer questions regarding:

- Eligibility for training
- The process for requesting training
- Reimbursement of exam or certification fees
- Whether time off is provided for training participation

### Course Discovery & Cost Calculation
The AI assistant should:

- Present available Agentic AI training courses
- Provide up-to-date pricing information, including:
  - Standard course fees
  - Real-time calculations for discounts or bundled offers
- Offer course prerequisites or certification track info if applicable

### Automated Approval Workflow
The assistant will:

- Collect the user's email and training course selection
- Automatically calculate the cost of the course
- Trigger an approval request via email or workflow to the user's manager
- Include all relevant booking details (course name, cost, requester info)

## Expected Outcomes:

- A conversational AI experience that helps employees make informed training decisions
- Automated calculation logic that ensures cost transparency
- A streamlined approval process that reduces manual intervention
- A scalable model that can be adapted for other training topics or HR workflows


## Key Capabilities You’ll Learn
| Feature / Pattern                      | What You'll Learn & Do                                                      |
|---------------------------------------|------------------------------------------------------------------------------|
| **Knowledge Q&A (RAG)**               | Upload a Word doc and enable generative answers for training policy queries |
| **System Variables**                  | Auto-capture the user’s email with `User.Email`                             |
| **Topics with Adaptive Cards**        | Collect structured input using choice sets inside a conversation            |
| **Prompt Engineering**                | Use prompt flows to dynamically calculate course cost                       |
| **Variable Management**               | Store and use topic-level and prompt-level variables                        |
| **Agent Flows (optional)**         | Trigger an approval flow and handle responses in the agent                  |
| **GPT-4o Orchestration**              | Let the agent guide conversations using natural language understanding      |
| **End-to-end testing**                | Preview and test the agent in Copilot Studio’s built-in chat simulator      |
---
