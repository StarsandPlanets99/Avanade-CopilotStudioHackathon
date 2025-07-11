## What's Next? Extend This Lab with Your Own Ideas

Now that you've built an AI-powered training enrollment agent using Copilot Studio, why stop here? The skills you've learned—like using knowledge sources, adaptive cards, prompt flows, and maybe approval automation—can be applied to many other workplace scenarios.

Below are just a few ideas to inspire you for the Hackathon. Alternatively why not come up with your own hackathon idea?  
You could even ask M365 Copilot to help brainstorm it with you!  

---

🧠 **1. Internal Policy Advisor**  
**Scenario:** Employees ask questions about HR, IT, or travel policies.

- Upload PDF/Word policy docs as a knowledge source  
- Use GPT-4o for natural Q&A about benefits, expenses, leave, etc.  
- Use Adaptive Card to ask clarifying questions (e.g. employee type)  
- Use prompt flow to personalize answers or flag policy violations  
- Optional: Agent flow to send unanswered questions to HR  

🛠️ **Patterns Used:**  
Knowledge (RAG), prompt-based generation.

---

💼 **2. New Hire Equipment Request**  
**Scenario:** Managers request laptops, monitors, or phone setups for new employees.

- Adaptive Card to select equipment type and urgency  
- Prompt flow calculates cost or compatibility  
- Agent flow sends approval to IT procurement  
- Response determines confirmation message or further clarification  

🛠️ **Patterns Used:**  
Structured topic input, prompt flow logic, Agent Flow approval.

---

🧾 **3. Expense Eligibility Checker**  
**Scenario:** Employees want to check if an expense is allowed and reimbursable.

- Upload company travel/expense policy as knowledge source  
- Adaptive Card to enter expense type and amount  
- Prompt returns allowed/not allowed message based on inputs  
- Agent flow (optional) for compliance team review  

🛠️ **Patterns Used:**  
RAG, Adaptive Card entry, prompt-based rule interpretation.

---

🌍 **4. Sustainability Project Evaluator**  
**Scenario:** Staff propose green initiatives and want feedback or approval.

- Adaptive Card to enter project idea (e.g. remote work savings, waste reduction)  
- Prompt evaluates impact based on goal alignment  
- Knowledge base contains corporate sustainability goals  
- Optional approval flow to funding committee  

🛠️ **Patterns Used:**  
Prompt grading, knowledge context, approval loop.

---

📚 **5. Course Recommendation Assistant**  
**Scenario:** An agent suggests learning paths based on job role or skills gap.

- User inputs job title or skills via Adaptive Card  
- Prompt flow maps input to learning track  
- Optionally include certification exam cost, duration, etc.  
- Pulls course info from uploaded course catalog (Word or Excel)  

🛠️ **Patterns Used:**  
Structured input → dynamic output, prompt recommendation engine, document RAG.

---

💬 **6. IT Troubleshooting Guide**  
**Scenario:** Employees describe a tech problem and the agent guides troubleshooting.

- GPT-driven orchestration guides user through steps  
- Prompt selects right path based on device type and issue  
- Adaptive Cards used for yes/no or multi-step decision trees  
- Knowledge base includes helpdesk SOPs  

🛠️ **Patterns Used:**  
GPT-4o conversational branching, prompt decision flow, document-driven answers.

