# Stanford Nephrology Decision-Support Dashboard

This decision-support dashboard was created as part of a Stanford Medicine externship focused on improving operational workflows in outpatient nephrology clinics. The tool addresses a common yet high-risk issue: **delays in responding to critically elevated potassium levels** (e.g., K+ ≥ 6.0 mmol/L) due to unclear escalation pathways.

---

## 🔍 Background & Root Cause Analysis

The project was inspired by a real patient safety incident involving a **missed potassium alert (6.2 mmol/L)** that went unaddressed, leading to a delayed response and potential harm. Using **5 Whys analysis**, I traced the problem back to the **absence of standardized escalation protocols and accountability systems**.

### Root Cause:
> *Clinic staff lacked a clear, role-specific protocol for handling critical lab values, which led to inconsistent handoffs and delayed provider interventions.*

I supplemented this with a **text-based decision tree and MermaidJS flowchart** that mapped clinical decisions from lab result review → symptom evaluation → medical history → repeat testing → provider action → documentation and safety netting.

---

## 💡 About the Tool

This interactive dashboard transforms that decision tree into a **web-based prototype**. It allows staff to enter a patient's scenario and get **immediate, role-specific guidance** on:

- What action to take (flag, escalate, test, treat)
- When and to whom to escalate
- What to document and communicate
- Clinical safety triggers for urgent intervention

The goal: **reduce cognitive load**, **minimize delays**, and **increase standardization** in outpatient nephrology settings.

---

## 👩‍⚕️ Who It's For

- **RNs, APPs, Nephrologists, and PCCs** seeking real-time guidance
- **Clinic leadership** wanting scalable SOPs
- **Quality improvement teams** identifying workflow gaps
- **EHR integrators** prototyping CDS tools

---

## 🚀 Live Demo

🔗 [View the Dashboard Here](https://github.com/sriramprog/stanford-nephrology-dashboard)
Click on index.html file and run the code.

---

## 🧠 Why This Externship Mattered to Me

As a data analyst and aspiring healthcare technologist, I was drawn to the externship because it combined **clinical logic**, **process optimization**, and **patient safety** — three areas I care deeply about. I wanted to bridge the gap between frontline staff confusion and backend data-driven protocols, especially in high-risk situations like hyperkalemia.

This project reflects my belief that **clarity saves lives**, and that good design in healthcare isn’t about complexity — it’s about the right action at the right time.

---

## 📌 Future Improvements

- PDF chart-note generator for provider documentation  
- Audit log for response tracking and training feedback  
- Full integration with EHR alert systems (via FHIR or HL7)  
- Expanded protocols for other labs (e.g., creatinine, INR)

---

## 🛠 Technologies Used

- HTML, CSS, JavaScript (Vanilla)
- Clinical decision trees
- Stanford Medicine visual style
