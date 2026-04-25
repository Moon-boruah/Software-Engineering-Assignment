# Software Engineering Assignment: SDLC Model Selection

**Course:** B.Tech Computer Science & Engineering  
**Semester:** VI  
**Topic:** SDLC Model Selection Analysis  

---

## 1️⃣ Introduction
**Project Selected:** ATM (Automated Teller Machine) Software System  

An **ATM Software System** is a mission-critical financial application that acts as a secure gateway between a bank’s central database and its customers. The system is responsible for managing real-time transactions such as cash withdrawals, balance inquiries, and fund transfers. 

Technically, it involves a complex interplay between **hardware components** (card readers, cash dispensers, and thermal printers) and **secure network protocols**. Because it handles physical currency and sensitive user data (PINs/Card details), the system requires extreme precision, high-level encryption, and a zero-tolerance policy for logic errors or security vulnerabilities.

---

## 2️⃣ Selected SDLC Model
**Model Name:** Waterfall Model

---

## 3️⃣ Justification
The Waterfall Model is the most appropriate choice for an ATM System due to the following reasons:

* **Requirement Stability:** The core requirements of an ATM (Withdrawal, Balance Inquiry, PIN change) are well-defined and haven't changed significantly in decades. This stability suits the linear approach of Waterfall.
* **High Security & Compliance:** ATMs must follow strict banking regulations and security protocols. Waterfall’s "Quality Gates" at the end of each phase ensure that security requirements are fully documented and verified before a single line of code is written.
* **Low Risk of Requirement Churn:** Since the system involves hardware-software integration, frequent changes (typical of Agile) can be costly and physically difficult to implement across thousands of machines.
* **Disciplined Documentation:** In banking systems, traceability is vital. Waterfall produces comprehensive documentation for every phase, which is essential for future audits and maintenance.
* **Predictable Deliverables:** Each phase has specific deliverables and a review process, ensuring that the critical "Requirements" and "Design" phases are 100% complete before moving to "Development."

---

## 4️⃣ Comparison with Other Models

| Model | Suitability | Reasoning |
| :--- | :--- | :--- |
| **Agile Model** | **Low** | Agile relies on continuous feedback and evolving requirements. In an ATM system, you cannot release a "Minimum Viable Product" that only partially handles money; it must be 100% functional and secure from day one. |
| **V-Model** | **High (Alternative)** | While excellent for validation and verification, the Waterfall approach is often preferred for initial builds to ensure the hardware-software design is completely frozen before testing resources are allocated. |
| **Spiral Model** | **Medium** | The Spiral model is risk-driven and highly expensive. Since ATM requirements are standardized and well-understood globally, the overhead of constant, repetitive risk analysis cycles is unnecessary. |
---

## 5️⃣ Diagram
The Waterfall Model follows a linear, sequential flow. Each phase must be completed before the next begins.

<img width="1920" height="1080" alt="waterfall1" src="https://github.com/user-attachments/assets/169b5ca5-2fbf-4edb-bb18-b7402ebbd304" />


---
## 6️⃣ Conclusion
For an **ATM Software System**, where reliability, security, and precision are more important than speed-to-market or flexibility, the **Waterfall Model** is the superior choice. Its structured approach ensures that all financial logic is thoroughly vetted, documented, and tested, minimizing the risk of failure in a live environment.

