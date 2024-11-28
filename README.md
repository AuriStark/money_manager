## About this project

# Money Manager Web Application

## **Project Overview**
This is a web-based expense tracker application designed to help users manage their personal finances. It provides functionality to record expenses, set budgets, track recurring payments, and generate financial reports. The application is built using **Django** for the backend and **Vue.js** for the user interface.

---

## **Features**
1. **User Management**:
   - Registration and Login (JWT-based authentication) : JSON Web Token (JWT)
   - Profile management (currency preference, monthly budget).
2. **Expense Tracking**:
   - Record expenses with categories and notes.
   - View expense history.
3. **Budgeting**:
   - Set budgets for specific categories.
   - Monitor remaining budget in real-time.
   ------- ?? Monitor remaining budget in real-time. 
4. **Recurring Payments**:
   - Define and manage recurring expenses.
   - Automated reminders for upcoming recurring payments.
5. **Reports and Analytics**:
   - Visualize expenses with charts and graphs.
   - Export reports in CSV/Excel format.
6. **Multi-Currency Support**:
   - Convert expenses dynamically based on preferred currency.
7. **Modern UI/UX**:
   - Intuitive and responsive design for desktop.
   - Intuitive and responsive design.

---

## **Tech Stack**

- Frontend: Vue.js
- Backend: Python (Django/Flask)
- Database: MongoDB 
- Testing: Selenium for UI testing, Postman for API testing
- CI/CD: Jenkins or CircleCI, Azure DevOps or GitHub Actions
- Use Node.js (with libraries like Socket.IO) for real-time features such as notifications, chats, or live updates.


### **Backend**:
- **Framework**: Django (Python)
- **Database**: SQLite (default, switchable to PostgreSQL/MySQL)
- **Authentication**: Django Rest Framework (DRF) with JWT tokens

### **Frontend**:
- **Framework**: Vue.js (Optional: React/Angular)
- **Styling**: Tailwind CSS or Bootstrap
- **Charting Library**: Chart.js via vue-chartjs

### **Other Tools**:
- **API Documentation**: DRF Swagger/OpenAPI
- **Version Control**: Git

---

## **Installation**

### **1. Clone the Repository**


---

## **Run**

```bash
npm install 

..... xxx 

```
---

## **API Documentation**
The API is documented using Django Rest Framework’s Swagger. Access the documentation at:

[To Swagger API](http://127.0.0.1:8000/api/docs/)

---


------------------- 
## TODO

- [ ] Design
- [ ] Mockups
- [ ] Development
- [ ] Unit testing
- [ ] QA
- [ ] Stage
- [ ] Beta Testing
- [ ] Production


- [ ] CI/CD - YAML files for automated testing
- [ ] Write API unit tests
- [ ] Initialize Docker Container 
- [ ] Create Jenkins Ui tests
- [ ] Deploy the app to cloud platforms like Azure.
- [ ] <!-- Integrate Kubernetes?? -->

---

## **Folder Structure** 
expense-tracker/
│
├── backend/
│   ├── expense_tracker/    # Main Django project folder
│   ├── expenses/           # Expense tracking app
│   ├── users/              # User management app
│   ├── recurring/          # Recurring expense management app
│   ├── templates/          # Django templates
│   └── static/             # Static files (CSS, JS)
│
├── frontend/
│   ├── src/                # Vue.js source files
│   ├── public/             # Public assets
│   └── package.json        # Frontend dependencies
│
├── requirements.txt        # Backend dependencies
├── README.md               # Documentation
└── .gitignore              # Files to ignore in Git

