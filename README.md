# Stanford Nephrology Decision-Support Dashboard

This clinical dashboard was developed during a Stanford Medicine externship to address a critical gap in outpatient nephrology operations: the delayed escalation of elevated potassium lab values (hyperkalemia), which can pose immediate cardiac risks if left unaddressed.

---

## 🏥 Background: Stanford Nephrology Clinic Setting

The externship focused on a busy outpatient nephrology clinic serving patients with chronic kidney disease (CKD), many of whom are medically complex and routinely undergo lab monitoring. The clinic's workflows involve multiple care team members — including nephrologists, advanced practice providers (APPs), registered nurses (RNs), and patient care coordinators (PCCs) — making **role clarity and escalation timing** essential for patient safety.

A real-world clinical case involving a **missed escalation of a 6.2 mmol/L potassium result** led to delayed intervention and potential harm. This case became the launching point for a structured operational and clinical review.

---

## 🔍 Root Cause Analysis

Using the **5 Whys** technique, I conducted a root cause analysis to identify why the lab result wasn’t escalated:

1. **Why wasn’t the elevated potassium addressed?**  
   → Because it was flagged by the RN but never escalated to a provider.

2. **Why wasn’t it escalated?**  
   → Because the RN was unclear on escalation responsibility and timing.

3. **Why was there confusion around roles?**  
   → Because the clinic lacked standardized escalation protocols for critical lab results.

4. **Why didn’t protocols exist?**  
   → Because lab workflows hadn’t been prioritized in training or process audits.

5. **Why were lab workflows not prioritized?**  
   → Because leadership underestimated the clinical risk and lacked feedback data to prompt change.

### 🎯 Root Cause Identified:
> There was no enforced, role-specific protocol or accountability system for managing elevated potassium values in a time-sensitive, clinically appropriate way.

---

## 🧠 From Decision Tree to Dashboard

To address this issue, I designed a **clinical decision tree** based on nephrology best practices (KDIGO and internal Stanford SOPs), outlining clear, sequential steps:

- Lab result review timing  
- Patient symptom evaluation  
- Medical history risk assessment  
- Repeat potassium testing  
- Provider treatment actions  
- Safety net triggers (e.g., K+ > 6.5 or abnormal ECG)

This logic was then translated into an **interactive, web-based decision-support tool** using HTML, CSS, and JavaScript.

---

## 🧭 Dashboard Functionality

The dashboard is designed to reduce ambiguity, speed up escalation, and ensure role-based clarity. Here’s how it works:

1. **User selects their clinical role**: RN, APP, Nephrologist, or PCC
2. **They input patient information**: potassium level, symptoms, medical history, ECG status
3. **The dashboard generates real-time action steps** that are:
   - Aligned with nephrology clinical pathways
   - Tailored to the user's role and scope of practice
   - Clear on what to do, when to escalate, and what to document

### 🧩 Example Role-Specific Paths

- **RN**: Sees instructions to flag unreviewed labs and escalate, but not to order tests
- **APP**: Sees full logic tree including treatment and follow-up steps
- **Nephrologist**: Sees safety net logic and final decision-making guidance
- **PCC**: Excluded from clinical decision-making steps

---

## 👩‍⚕️ Who This Dashboard Supports

- **RNs**: Know exactly when and how to escalate abnormal results  
- **APPs & Nephrologists**: Get contextualized information for clinical decisions  
- **PCCs**: Understand their documentation and communication responsibilities  
- **Leadership**: Use it to reinforce SOPs and standardize clinic workflows

---

## 💡 Key Features

- Clinical decision tree logic tailored to nephrology
- Role-specific output based on patient condition and user scope
- Real-time response generator for urgent scenarios
- Stanford-branded interface for professional presentation
- Documentation checklist to close the loop on communication

---

## 🚀 Live Demo

🔗 [View the Dashboard](https://github.com/sriramprog/stanford-nephrology-dashboard/blob/main/stanford_nephrology_dashboard_final.html)

---

## 📣 Project Scope & Status

> **This is a functional prototype.**  
> It was developed within the time constraints of the Stanford externship, prioritizing clinical logic and real-world usability over full-stack engineering or UI polish. It’s not a reflection of my complete coding abilities, but rather a demonstration of how structured problem-solving, role alignment, and thoughtful design can directly improve patient safety.

---

## 🧠 Why This Project Mattered

As a healthcare data analyst, I’ve worked on dashboards and predictive models — but this project was different. It required me to **step into the clinical mindset**, understand real workflow breakdowns, and build a tool that frontline teams could actually use. 

I was motivated by the belief that:
> *“If you make the right thing easy to do, you’ll save time, prevent errors, and protect lives.”*

---

## 🛠 Technologies Used

- HTML5, CSS3, JavaScript (Vanilla)
- Decision tree modeling (text + flowchart + logic-based rendering)
- Stanford Medicine branding and UI conventions

---

## 📌 Future Enhancements

- Export button to generate PDF chart notes  
- EHR integration using FHIR/SMART standards  
- Audit logs to track decisions for quality improvement  
- Expanded protocols (e.g., creatinine, INR, hemoglobin)

---

## 🙋 About the Author

Built by **Sriram Srinivasan**, extern at Stanford Medicine and aspiring healthcare data analyst! I help clinics build data-driven tools that are usable, actionable, and rooted in patient safety.
