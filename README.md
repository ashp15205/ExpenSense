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

### 🔑 Login Page  
- Email format validation.  
- Alerts for invalid credentials.  
- Redirects to **Home Page** on success.  

![Login](https://user-images.githubusercontent.com/39689610/134283484-079f6b2d-b04b-4970-a49f-74d42c43ee76.png)  

---

### 👨‍💼 Adding Employees (Admin Only)  
- Admin → **Admin Options → Add Employee**.  
- Enter employee details → validate → submit.  

![Add Employee](https://user-images.githubusercontent.com/39689610/134284524-cb84f266-5317-4098-9f28-4506b2bd379b.png)  

---

### 🔒 Change Password  
- Mandatory on first login.  
- Validations:  
  - New password ≠ old password.  
  - New password = Confirm password.  

![Change Password](https://user-images.githubusercontent.com/39689610/134287005-2dfcb3a4-7c57-4f9a-9061-f3f631328771.png)  

---

### 👥 Clients & Projects  
- Add clients and projects.  
- Assign Project Manager & team members.  
- View project dashboards and summaries.  

![Projects](https://user-images.githubusercontent.com/39689610/134298814-e48f7974-0cb6-4be5-907f-5f4d8a735ec1.png)  

---

### 📑 Expenses  
- File expenses with invoices.  
- Edit / delete expenses anytime.  
- Attachments viewable in dashboard.  

![Expenses](https://user-images.githubusercontent.com/39689610/134308592-ff366ac8-ccf0-4e79-b7c3-324cc4a01913.png)  

---

### ✅ Approvals  
- Hierarchical approval system:  
  - Employees → cannot approve.  
  - Project Managers → approve team expenses.  
  - Administrators → approve all expenses.  

![Approvals](https://user-images.githubusercontent.com/39689610/134315047-9374f82d-ffbc-4653-9705-e8982e265245.png)  

---

### 👨‍💻 Employees List  
- View all employees and their roles.  

![Employees](https://user-images.githubusercontent.com/39689610/134306610-3ffb0faa-fb4f-4980-9db5-297264f3acc2.png)  

---

### 🚪 Logout  
- Secure logout option available in navbar.  

![Logout](https://user-images.githubusercontent.com/39689610/134325677-c85c12e3-1aff-48f3-b8b0-55e7ced7e688.png)  

---

## ⚙️ Tech Stack  

- **Frontend:** React, Redux, HTML, CSS  
- **Backend:** PostgreSQL  
- **Authentication:** JWT (JSON Web Token)  
- **Hosting:** (Previously on Heroku – alternatives to be explored)  

---

## 📌 Future Improvements  
- Deploy to Render / Vercel / Railway (Heroku free plan discontinued).  
- Add analytics dashboard for expense trends.  
- Multi-currency support.  

---
