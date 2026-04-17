# ServiceNow-AI-Command-Center

# 🚀 ServiceNow AI Command Center (AICC)

## 🧠 Overview

This project demonstrates how ServiceNow can be extended beyond traditional workflows into an **AI-driven automation platform**.

The system captures signals from enterprise modules, processes them through an AI engine, generates insights, executes actions, and visualizes performance.

---

## 🏗️ Architecture

AI Signal → AI Decision → AI Action → AI Action Log → Dashboard

- **AI Signal**: Captures events across modules (ITSM, HRSD, CSM)
- **AI Decision**: Applies AI logic for decision-making
- **AI Action**: Executes system updates
- **AI Action Log**: Maintains audit trail

---

## ⚙️ Key Features

### 🔹 AI Signal Table
Captures incoming events from multiple modules:
- ITSM (Incidents)
- HRSD (Employee Requests)
- CSM (Customer Cases)

---

### 🔹 AI Decision Engine (Script Include)
- Evaluates priority and signal type  
- Determines action (Escalate / Notify / Auto-resolve)  
- Assigns confidence score  

---

### 🔹 🤖 GenAI Insight Layer
- Generates contextual explanations for each decision  
- Simulates LLM (Large Language Model) behavior  

**Example:**
> AI Insight: This appears to be a critical issue impacting business operations. Immediate attention is recommended.

---

### 🔹 AI Action Execution
- Automatically performs actions such as:
  - Escalation  
  - Routing  
  - Auto-resolution  

---

### 🔹 AI Action Log
- Tracks execution status  
- Maintains audit and traceability  

---

### 🔹 📊 AI Dashboard (Platform Analytics)

Real-time visualization of:

- Total AI signals processed  
- Decision distribution (Escalate / Notify / Auto-resolve)  
- Action execution success rate  
- Escalation vs Auto-resolution %  

---

## 🔍 Use Cases

### 🖥️ ITSM
Server outage → Auto escalation  

### 👩‍💼 HRSD
Payroll issue → Smart routing  

### 🎧 CSM
Customer payment issue → Automated handling  

Decision: Escalate
Reason: Critical priority requires immediate escalation
AI Insight: This appears to be a critical issue impacting business operations...
Action: Assigned to IT Support Team
Status: Success
---

## 🧪 Sample Output

---

## 🛠️ Tech Stack

- ServiceNow (Yokohama PDI)  
- Script Includes  
- Business Rules  
- GlideRecord  
- Custom Tables  
- Platform Analytics Dashboards  

---

## 📸 Screenshots

### 🔹 AI Decision
![AI Decision](Screenshots/itsm-incident-escalation.png)

---

### 🔹 AI Action Log
![AI Action](Screenshots/ai-action-execution-log.png)

---

### 🔹 📊 AI Dashboard
![Dashboard](Screenshots/ai-dashboard.png)

---

## 💡 Key Highlights

- ✅ End-to-end AI pipeline in ServiceNow  
- ✅ GenAI (LLM simulation) integration  
- ✅ Multi-module coverage (ITSM, HRSD, CSM)  
- ✅ Real-time analytics dashboard  
- ✅ Business-level insights (automation vs escalation %)  

---

## 🎯 Key Learnings

- AI in enterprise systems is about **decision pipelines**, not just models  
- Explainability (GenAI insights) improves trust  
- Dashboards convert automation into **business intelligence**  
- ServiceNow can act as an **AI orchestration platform**  

---

## 🚀 Future Enhancements

- Real LLM integration (OpenAI / Now Assist)  
- Predictive AI models  
- Multi-agent AI system  
- Advanced analytics and alerting  

---

## 🔗 GitHub Repository

👉 https://github.com/SrikanthMadabhushi/ServiceNow-AI-Command-Center

---

## 👨‍💻 Author

**Srikanth Madabhushi**  
🔗 https://SrikanthMadabhushi.github.io  
