# Software Engineering Assignment: SDLC Model Selection

**Course:** B.Tech Computer Science & Engineering  
**Semester:** VI  
**Topic:** SDLC Model Selection Analysis  

---

## 1️⃣ Introduction
**Project Selected:** ATM (Automated Teller Machine) Software System  

An ATM Software System is a mission-critical application responsible for handling financial transactions, verifying user identity (via PIN and Card), and communicating with the central banking server. Because it involves physical hardware integration and sensitive financial data, the system requires extreme precision, high security, and zero tolerance for errors in the core transaction logic.

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
| **Agile** | Low | Agile relies on continuous feedback and evolving requirements. You cannot release a "Minimum Viable Product" for an ATM; it must be fully functional and secure from day one. |
| **Spiral** | Medium | While good for risk management, the Spiral model is highly complex and expensive. For a system with well-understood requirements, the overhead of constant risk cycles is unnecessary. |

---

## 5️⃣ Diagram
The Waterfall Model follows a linear, sequential flow. Each phase must be completed before the next begins.

```mermaid
graph TD
    A[Requirement Analysis] --> B[System Design]
    B --> C[Implementation / Coding]
    C --> D[Testing / Verification]
    D --> E[Deployment]
    E --> F[Maintenance]
    
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style F fill:#bbf,stroke:#333,stroke-width:2px
---

## 6️⃣ Conclusion
For an **ATM Software System**, where reliability, security, and precision are more important than speed-to-market or flexibility, the **Waterfall Model** is the superior choice. Its structured approach ensures that all financial logic is thoroughly vetted, documented, and tested, minimizing the risk of failure in a live environment.
