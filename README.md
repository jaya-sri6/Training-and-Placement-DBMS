# 🎓 Training and Placement Management System

A mini project for efficiently managing student data, academic records, company details, placement statistics, and more. Built using **HTML**, **CSS**, **Flask**, and **SQLite**, this system is designed to help educational institutions streamline training and placement operations.

## 🚀 Features

* **Student Information Management**
  Add, view, and delete student personal details such as roll number, name, contact info, and address.

* **Academic Records**
  Maintain attendance, CGPA, and backlog data for each student.

* **Company Database**
  Store company details including minimum CGPA requirements and other hiring criteria.

* **Coding Profile Scores**
  Track students' programming skills from platforms like HackerRank, CodeChef, Codeforces, and SPOJ.

* **MS & Startup Preferences**
  Record students' preferences for MS or startup careers.

* **Placement Records**
  Manage placed students' data including company and salary package.

* **Branch-wise Analysis**
  View statistics on the number of students placed from each branch.

## 🛠️ Tech Stack

| Technology     | Description                          |
| -------------- | ------------------------------------ |
| **Frontend**   | HTML5, CSS3                          |
| **Backend**    | Python Flask                         |
| **Database**   | SQLite                               |
| **Web Server** | Flask development server (for local) |

## 📂 Project Structure

```
training-placement-system/
│
├── static/
│   └── styles.css               # External CSS styles
│
├── templates/
│   └── index.html               # Main frontend page
│
├── training_placement.db        # SQLite database (created on first run)
├── app.py                       # Flask backend implementation
├── README.md                    # Project documentation
└── requirements.txt             # List of Python dependencies
```


## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/training-placement-system.git
cd training-placement-system
```

### 2. Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

Visit `http://127.0.0.1:5000/` in your browser.


## 📌 Key Functional Routes (Flask)

| Route                  | Method | Description                  |
| ---------------------- | ------ | ---------------------------- |
| `/`                    | GET    | Loads homepage with forms    |
| `/add_student`         | POST   | Add new student to DB        |
| `/get_students`        | GET    | Retrieve all students (JSON) |
| `/delete_student/<id>` | DELETE | Delete a student by ID       |


## ✅ To-Do (Optional Enhancements)

* Add form validations using JavaScript
* Implement authentication for admin access
* Create separate dashboards for analytics
* Export data to CSV/Excel
* Use AJAX for dynamic page updates


## 📄 License

This project is open-source and available under the [MIT License](LICENSE).


## 🤝 Acknowledgments

This project is developed as part of a **Mini Project** submission for academic purposes, intended to showcase basic CRUD operations, backend integration, and database handling in Flask.



