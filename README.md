# 🌍 Pollution Detection System

A web-based **Pollution Detection System** built using **Flask, Python, MySQL, HTML, CSS, and JavaScript**. The system helps users monitor Air Quality Index (AQI), store pollution records, analyze pollution data, and generate downloadable reports through an interactive dashboard.

---

## 📌 Features

- 🔐 User Registration & Login Authentication
- 📊 Interactive Dashboard
- 🌫️ Air Quality Index (AQI) Monitoring
- ➕ Add Pollution Records
- 📋 View and Manage Records
- 📈 Analytics Dashboard
- 📄 Report Generation
- 📥 Export Reports (PDF, Excel, CSV)
- 🖨️ Print Reports
- 🗄️ MySQL Database Integration
- 📱 Responsive User Interface

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Database
- MySQL

### Tools
- VS Code
- XAMPP
- phpMyAdmin
- Git
- GitHub

---

## 📂 Project Structure

```
Pollution-Detection-System/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── analytics.html
│   ├── reports.html
│   ├── records.html
│   └── add_record.html
│
├── app.py
├── database.sql
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Pollution-Detection-System.git
```

### 2. Navigate to Project

```bash
cd Pollution-Detection-System
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure MySQL

- Start XAMPP
- Open phpMyAdmin
- Create a database

```
pollution_db
```

- Import the SQL file.

### 7. Run the Project

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000/
```

---

## 📊 Modules

### User Authentication
- Secure Login
- User Registration
- Session Management

### Dashboard
- Displays pollution statistics
- AQI summary
- Navigation to all modules

### Pollution Records
- Add pollution data
- Update records
- Delete records
- Search records

### Analytics
- Pollution trends
- AQI comparison
- Data visualization

### Reports
- Generate pollution reports
- Download PDF
- Export Excel
- Export CSV
- Print reports

---

## 🗃️ Database

Database Name

```
pollution_db
```

Main Tables

- users
- pollution_records

---

## 🚀 Future Enhancements

- Live AQI using Government APIs
- Weather Forecast Integration
- Email Report Generation
- SMS Alerts
- Machine Learning-Based Pollution Prediction
- Interactive Maps
- Mobile Application
- Real-Time Sensor Integration
- AI-Based Pollution Analysis

---

## 📸 Screenshots

Add screenshots here.

```
screenshots/
├── login.png
├── dashboard.png
├── analytics.png
├── reports.png
└── records.png
```

---

## 📈 Project Workflow

```
User Login
      │
      ▼
 Dashboard
      │
      ▼
 Add/View Pollution Records
      │
      ▼
 Database (MySQL)
      │
      ▼
 Analytics
      │
      ▼
 Reports
      │
      ▼
 Export PDF / Excel / CSV
```

---

## 🎯 Objectives

- Monitor air pollution efficiently.
- Store pollution records securely.
- Analyze pollution trends.
- Generate detailed reports.
- Provide an easy-to-use dashboard.
- Improve environmental awareness.

---

## 📚 Learning Outcomes

- Flask Web Development
- Python Programming
- MySQL Database Management
- CRUD Operations
- REST API Integration
- Data Analysis
- Report Generation
- Responsive Web Design

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📄 License

This project is developed for educational purposes.

---

## 👨‍💻 Author

**Hariom Gupta**

GitHub: https://github.com/coderxninja1661

---

⭐ If you found this project helpful, don't forget to **Star** the repository.
