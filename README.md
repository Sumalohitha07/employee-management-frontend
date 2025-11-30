# employee-management-frontend

# Employee Management System – Frontend  
A React-based web application designed for managing employees, attendance, departments, and overall workflow inside an organization. It contains separate login paths for **Managers** and **Employees**, with dashboards tailored for each role.

---

## 🚀 Features

### 🔐 **Authentication Workflow**
- Landing page asks user to choose:
  - **Manager Login**
  - **Employee Login**
- Role is passed as a URL query parameter:  
  `/login?role=manager`  
  `/login?role=employee`
- After login, user session is stored in **localStorage**.

---

## 👨‍💼 Manager Dashboard

Managers can:
- View **all employees**
- **Add** a new employee
- **Edit** any employee
- **Delete** an employee
- **Search** employees (by name, email, phone, dept)
- **Download data as CSV**
- Data saved in **localStorage** for persistence

---

## 🧑‍💻 Employee Dashboard

Employees can:
- View **only their own details**
- **Edit their own profile**
- Updated details persist in the browser using **localStorage**

---

## 📁 Folder Structure






link: https://drive.google.com/file/d/104spa613t2pCSXrsHhWeynU4nnabRPKi/view?usp=drive_link
