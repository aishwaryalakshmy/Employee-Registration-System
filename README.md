# 🧑‍💼 Employee Registration System

A desktop-based employee registration system built using **Python (Tkinter GUI)** and **MySQL (phpMyAdmin)**. It allows users to **Add**, **Search**, **Update**, **Delete**, and **View** employee details in an easy-to-use graphical interface.

---

## 🚀 Features

- 📝 Add new employee records
- 🔍 Search employee by any field
- ✏️ Update existing employee information
- ❌ Delete selected employee
- 🔄 Reset (clear) all records from the database
- 📋 View all employees in a table format
- 🪟 Interactive Tkinter GUI
- 🗂️ MySQL database integration

---

## 🛠️ Technologies Used

| Component       | Technology     |
|----------------|----------------|
| Language        | Python 3.x     |
| GUI Library     | Tkinter, ttk   |
| Database        | MySQL          |
| DB Interface    | PyMySQL        |
| IDE             | VS Code        |

---

## 📐 Database Schema

Database: `students_db`  
Table: `students`

```sql
CREATE TABLE `students` (
  `STUDID`   VARCHAR(200) NOT NULL,
  `FNAME`    VARCHAR(200) NOT NULL,
  `LNAME`    VARCHAR(200) NOT NULL,
  `ADDRESS`  VARCHAR(200) NOT NULL,
  `PHONE`    VARCHAR(200) NOT NULL,
  PRIMARY KEY (`STUDID`)
);
````

---

## 📸 GUI Preview

> ![App Screenshot](![Screenshot (110)](https://github.com/user-attachments/assets/8eb070d5-3e3c-4ee1-a886-55274318a760)
)
> *(Replace this with your actual screenshot image in the repo)*

---

## 📦 Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/employee-registration-system.git
   cd employee-registration-system
   ```

2. **Install dependencies**

   ```bash
   pip install pymysql
   ```

3. **Set up MySQL database**

   * Open `phpMyAdmin`
   * Create database `students_db`
   * Run the SQL schema provided above to create the `students` table.

4. **Run the application**

   ```bash
   python app.py
   ```

---

## 🎯 Usage Instructions

* Fill in employee details and click **Add**
* Use **Search** to look up an employee
* Select a row and click **Select** to edit
* Modify data and click **Update**
* Click **Delete** to remove a record
* Use **Reset** to clear all records

---

## 📁 Project Structure

```
employee-registration-system/
│
├── app.py                 # Main application code
├── requirements.txt       # Python dependencies
├── screenshots/
│   └── screenshot.png     # GUI screenshot (optional)
└── README.md              # Project documentation
```

---

## ✨ Future Improvements

* Add login/authentication for secure access
* Input validation (e.g., phone number format)
* Export/Import employee data (CSV/PDF)
* Search filters (by field)
* Enhanced UI design

---

## 🧑‍💻 Author

**Aishwarya Lakshmy KS**
BSc Computer Science – 2nd Year
Sakthi Sugars Ltd – Project Intern
📧 [aishwaryalakshmy26@gmail.com](mailto:aishwaryalakshmy26@gmail.com)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

```
