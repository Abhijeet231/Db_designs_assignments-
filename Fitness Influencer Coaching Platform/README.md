# 🏋️ Fitness Influencer Coaching Platform – DB Design

This project represents a database design (ERD) for an online fitness coaching platform where trainers/influencers manage clients, sell plans, and track progress.

---

## 📌 Overview

The platform is designed to support:

- Trainers managing multiple clients
- Clients subscribing to different fitness plans
- Scheduling consultations and live sessions
- Tracking client progress through regular check-ins
- Handling payments and subscriptions

---

## 🧠 Key Concepts

- One trainer can coach many clients
- A client can purchase multiple plans over time
- Multiple clients can enroll in the same plan
- Sessions and check-ins are treated as separate entities
- Progress tracking is independent of user data

---

## 🗂️ Entities Included

- **User** (base entity with roles: trainer, client)
- **Client**
- **Trainer**
- **Plan**
- **Subscription** (tracks plan purchases)
- **Session** (consultations / live classes)
- **CheckIn** (progress tracking)
- **TrainerFeedback**
- **Payment**

---


## ⚙️ Features Modeled

- Subscription lifecycle (start/end dates, status)
- Structured coaching programs
- Session scheduling system
- Weekly progress tracking (check-ins)
- Trainer feedback system
- Payment tracking

---

## 🛠️ Tech / Tools

- ER Diagram Tool: Eraser
- Design Type: Relational Database (ERD)

---

## 📈 Learning Outcome

This project helped me understand:
- Real-world database modeling
- Handling many-to-many relationships using junction tables
- Separating concerns (sessions vs plans vs progress)
- Designing scalable systems

---

## 🤝 Feedback

This is my first database design project, so feedback, suggestions, and improvements are highly welcome!