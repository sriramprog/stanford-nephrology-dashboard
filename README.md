# Stanford Nephrology Decision-Support Dashboard

This clinical dashboard was developed during a Stanford Medicine externship to address a critical gap in outpatient nephrology operations: the delayed escalation of **elevated potassium lab values** (hyperkalemia), which can pose immediate cardiac risks if left unaddressed.

---

## 🏥 Background: Stanford Nephrology Clinic Setting

The externship focused on a busy outpatient nephrology clinic serving patients with chronic kidney disease (CKD), many of whom are medically complex and routinely undergo lab monitoring. The clinic's workflows involve multiple care team members — including nephrologists, advanced practice providers (APPs), registered nurses (RNs), and patient care coordinators (PCCs) — making **role clarity and escalation timing** essential for safety.

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
> *There was no enforced, role-specific protocol or accountability system for managing elevated potassium values in a time-sensitive, clinically appropriate way.*

---

## 🧠 From Decision Tree to Dashboard

To address this, I constructed a clinical **decision tree** based on nephrology guidelines (including KDIGO and internal Stanford protocols), outlining steps from:

1. **Lab result review timing**
2. **Patient symptom evaluation**
3. **Medical history risk assessment**
4. **Repeat lab testing and thresholds**
5. **Provider intervention**
6. **Safety net triggers** (e.g., K+ > 6.5 mmol/L or abnormal ECG)

I then translated this decision logic into an **interactive web-based tool** using HTML, CSS, and JavaScript to help staff instantly determine what action to take, when to escalate, and how to document their actions.

---

## 👩‍⚕️ Who This Dashboard Supports

- **RNs**: Know exactly when and how to escalate abnormal results
- **APPs & Nephrologists**: Get summarized context and next steps
- **PCCs**: Understand workflow handoffs
- **Leadership**: Standardize protocols across teams

---

## 💡 Key Features

- Clinical decision tree logic tailored to nephrology
- Role-specific guidance based on patient condition
- Stanford-branded interface for professional presentation
- Real-time response logic for urgent labs
- Clear documentation checklist

---

## 🚀 Live Demo

🔗 [View the Dashboard](https://github.com/sriramprog/stanford-nephrology-dashboard)

---

## 📣 Project Scope & Status

> **This is a work in progress.**  
> The dashboard represents a functional prototype built within the time and scope of the Stanford externship. It focuses on clinical logic, escalation clarity, and decision support — not UI polish or full-scale engineering. As such, it’s not a reflection of my full coding ability, but rather a demonstration of how structured problem-solving, root cause analysis, and thoughtful design can directly support patient safety in a clinical setting.

---

## 🧠 Why This Project Mattered

As a healthcare data analyst, I’ve worked on predictive models and operational dashboards — but this externship pushed me into **clinical logic design**. I was inspired by how a single missed lab result could cascade into patient harm, and how simple, clear interfaces can empower staff to make faster, safer decisions. 

This dashboard isn’t just a tech demo — it’s a reflection of my belief that:
> *“If you make the right thing easy to do, you’ll save time, prevent errors, and protect lives.”*

---

## 🛠 Technologies Used

- HTML5, CSS3, JavaScript (Vanilla)
- Decision tree modeling (text + MermaidJS + prototype logic)
- Stanford visual identity (color, branding)

---

## 📌 Future Enhancements

- PDF chart-note generator  
- EHR integration using FHIR/SMART  
- Audit log of decisions made for QI tracking  
- Expanded protocols for other labs (e.g., creatinine, phosphorus)
