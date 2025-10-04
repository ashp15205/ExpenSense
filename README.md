# 💰 Expense Management Software

**Coded By:** *Ashish Patil*  

> A full-stack web application built with **React + Redux** (frontend) and **PostgreSQL** (backend) to automate expense filing, approvals, and reporting within organizations.  

---

## 🚀 Overview  
In today’s digital world, organizations aim to automate most processes for **efficiency and transparency**.  
Managing employee expenses and reimbursements is a critical workflow that involves:  

- Submitting expenses with receipts.  
- Approving/rejecting by authorized personnel.  
- Tracking clients, projects, and budgets.  

This project delivers a **secure and automated expense management system** with role-based access and JWT authentication.  

---

## ✨ Features  

✅ **Authentication & Authorization**  
- JWT Auth Token login system.  
- First-time password reset with validations.  
- Secure protected routes.  

✅ **Admin Privileges**  
- Add new employees.  
- Manage projects & clients.  
- Approve/reject all expense claims.  

✅ **Employee Functions**  
- Submit expenses with attachments.  
- Edit, view, and delete filed expenses.  
- View assigned projects and summaries.  

✅ **Projects & Clients Management**  
- Create projects with team members & project manager.  
- Add clients (visible to all employees).  
- Detailed project and expense dashboards.  

✅ **Expense Approval Flow**  
- Employees → submit expenses.  
- Project Managers → approve/reject for their team.  
- Administrators → approve/reject for everyone.  

---

## 🖥️ Demonstration  

### 👨‍💼 Adding Employees (Admin Only)  
- Admin → **Admin Options → Add Employee**.  
- Enter employee details → validate → submit.  

<img width="1792" height="1037" alt="134284524-cb84f266-5317-4098-9f28-4506b2bd379b" src="https://github.com/user-attachments/assets/5e9c7f50-62b2-48e9-a8b7-f519e19cfbb6" />


---

### 🔒 Change Password  
- Mandatory on first login.  
- Validations:  
  - New password ≠ old password.  
  - New password = Confirm password.  

<img width="1792" height="1037" alt="134287005-2dfcb3a4-7c57-4f9a-9061-f3f631328771" src="https://github.com/user-attachments/assets/0ba90f5b-9ad5-419c-bf4f-f472999dc9d9" />


---

### 👥 Clients & Projects  
- Add clients and projects.  
- Assign Project Manager & team members.  
- View project dashboards and summaries.  

<img width="1792" height="1041" alt="134298814-e48f7974-0cb6-4be5-907f-5f4d8a735ec1" src="https://github.com/user-attachments/assets/394baeaf-54a6-4d91-b20d-df7d6e0cdf1b" />


---

### 📑 Expenses  
- File expenses with invoices.  
- Edit / delete expenses anytime.  
- Attachments viewable in dashboard.  

<img width="1792" height="1037" alt="134308592-ff366ac8-ccf0-4e79-b7c3-324cc4a01913" src="https://github.com/user-attachments/assets/2522463e-807e-4ec5-9f03-81d7870cb22e" />

---

### ✅ Approvals  
- Hierarchical approval system:  
  - Employees → cannot approve.  
  - Project Managers → approve team expenses.  
  - Administrators → approve all expenses.  

<img width="1792" height="1043" alt="134315047-9374f82d-ffbc-4653-9705-e8982e265245" src="https://github.com/user-attachments/assets/8f0e4231-031f-4fd0-8ed9-a18b7afc8d91" />


---

## ⚙️ Tech Stack  

- **Frontend:** React, Redux, HTML, CSS  
- **Backend:** PostgreSQL  
- **Authentication:** JWT (JSON Web Token)

---

## 📌 Future Improvements  
- Deploy to Render or Vercel   
- Add analytics dashboard for expense trends.  
- Multi-currency support.  

---
