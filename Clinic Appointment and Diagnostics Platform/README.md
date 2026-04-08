# 🏥 Clinic Management System – ER Diagram

## 📌 About the Assignment

This project is a database design for a **Clinic Appointment & Diagnostics Platform**.

The goal was to design a clean and scalable ER diagram that can handle:

* doctor and patient management
* appointment booking
* consultations (actual visits)
* diagnostic tests and reports
* payments

This is not a hospital-level system, but a focused clinic workflow.

---

## 🧠 Key Design Thinking

While designing this system, I focused on modeling **real-world clinic flow** instead of just creating tables.

### 🔹 Appointment vs Consultation

* **Appointment** = booking
* **Consultation** = actual doctor visit
* Not all appointments result in consultations (no-shows)

---

### 🔹 Tests belong to Consultation

* Diagnostic tests are prescribed **after doctor interaction**
* So tests are linked to **consultation**, not appointment

---

### 🔹 Reports linkage

* Reports are generated for **prescribed tests**
* Each report is linked back to:

  * consultation
  * patient
  * doctor (indirectly)

---

### 🔹 Relationships handled properly

* One patient → many appointments
* One doctor → many patients
* One consultation → multiple tests
* One test → one report (optional)

---



## 🎯 Questions This Design Solves

This ERD supports:

* Who are the doctors and their specialties?
* Which patient booked which appointment?
* What is the appointment status?
* Did the appointment result in a consultation?
* What tests were prescribed?
* What reports were generated?
* Can a patient have multiple visits? ✅
* Can a doctor attend multiple patients? ✅
* Can a consultation have multiple tests? ✅

---


## 🚀 Learnings

This assignment helped me understand:

* the importance of separating **booking vs actual visit**
* how to design **real-world relationships**
* how to avoid common mistakes in DB design
* how to think beyond just tables and focus on system flow

---



