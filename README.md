# 📚 College Management System (CMS Portal)

A **C++ console-based project** developed as part of the **COMP-112L: Data Structures & Algorithms Lab**.  
The system implements **OOP concepts, data structures, and file handling** to manage **Admin, Teacher, and Student dashboards** for a university/college.

---

## 📝 Executive Summary
This project provides a **College Management System** that allows different stakeholders (Admin, Teachers, Students) to access, manage, and update records.  
- The **Admin Dashboard** provides full control: add, delete, update, and view records.  
- The **Teacher Dashboard** allows teachers to view/update attendance, salary, and exam data.  
- The **Student Dashboard** allows students to view personal details, exam data, fee records, attendance, and more.  

Each dashboard is designed to **simulate a real-world university portal** using **C++ (OOP + DSA)** and persistent **file storage**.

---

## 📖 Introduction
A **management system** is a crucial part of any educational institute.  
The **College Management System (CMS)** project provides digital solutions for handling:
- Student details, attendance, fee records, and results.  
- Teacher records, attendance, and salary.  
- Admin functions to manage all data.  

Students can also:
- View timetables, roll number slips, academic calendar, and course evaluation forms.  
- Check their fee structure and course status (completed/pending/repeated).  

Teachers can:
- Upload and update results (assignments, quizzes, midterms, final exams).  
- Mark student attendance.  
- Access detailed student profiles.

---

## 🎯 Motivations and Challenges
- The **traditional/manual system** was slow, inefficient, and error-prone.  
- Retrieving or updating records consumed a lot of time.  
- Storing large amounts of data was problematic.  

💡 **Solution**: Develop a **College Management System in C++** that provides:  
- Fast and accurate access to records.  
- Efficient data storage.  
- Easy modification and retrieval of information.

---

## 🎯 Goals & Objectives
### Goals
- Provide a better and modern management system compared to the manual/old system.  
- Digitize student, teacher, and admin interactions with quick access to academic and administrative records.  

### Objectives
- Add, modify, search, and delete records of students, teachers, and staff.  
- Store attendance, salary, and exam data.  
- Manage student fees and academic details.  
- Provide timetables, rules/regulations, and calendars.  
- Ensure role-based dashboards for Admin, Teacher, and Student.  

---

## 🛠 Project Plan
The project is organized into different **subsystems**:
- **Login System** → Separate login for Admin, Teacher, Student.  
- **Admin System** → Full control of teacher & student data.  
- **Teacher System** → Manage attendance, exam results, and personal info.  
- **Student System** → Access fee details, results, attendance, and course info.  
- **Exam System** → Record and update student assessments.  

---

## 👥 User Classes
- **Admin (Management):** Full control of the system.  
- **Teachers:** Update results and attendance; manage course-related data.  
- **Students:** Access academic and financial records; limited update rights (personal info only).  
- **General Users:** View information such as admission criteria and rules.  

---

## ⚙️ System Features
- 🔑 **Account Creation & Login** for Admin, Teachers, Students.  
- 📝 **Update Records** (role-specific).  
- 👀 **View Details** (attendance, fees, results, salary, academic info).  
- 📊 **Exam Management System**.  
- 📅 **Academic Calendar & Timetable**.  
- 📂 **Persistent Storage** via text files (`student.txt`, `teacher.txt`, `Marks.txt`, `Admin_logs.txt`).  

---


## 🗂 Project Structure
/DS_PROJECT
│── /uni_managment

│ ├── projectt.cpp # Main source code

│ ├── student.txt # Student records

│ ├── teacher.txt # Teacher records

│ ├── Marks.txt # Marks data

│ ├── Admin_logs.txt # Admin login history

│ ├── uni_managment.vcxproj # Visual Studio project file

│ └── uni_managment.sln # Solution file
│
├── /Debug # Debug build files

├── /Release # Release build files

└── /x64/Debug # 64-bit debug build files

---

---

## ⚙️ How to Run
1. Clone this repository:
   git clone https://github.com/your-username/College-Management-System-DSA.git

Open the solution in Visual Studio (uni_managment.sln).

Build the project (Debug/Release).

Run the executable:
./DS_PROJECT/uni_managment/projectt.exe


## 📊 System Features (Modules)
1. **Login System** – Admin, teacher, and student login.  
2. **Admin Module** – Manage all records and operations.  
3. **Teacher Module** – Manage results and attendance.  
4. **Student Module** – View personal info, fee details, results, etc.  
5. **Exam Management System** – Manage exam records and schedules.  
6. **Fee Management System** – Track fee packages and dues.  

---

## 📑 Deliverables
- Source code implementing the system.  
- Project report with objectives, background, design, and implementation.  
- Lab/documentation files with supporting diagrams.

---

## 🚀 Technologies Used
- **C++** (Data Structures & Algorithms)  
- File Handling (for persistent storage)  
- Object-Oriented Programming concepts  

---

## 📌 Future Enhancements
- Web-based interface for easier access.  
- Database integration (MySQL/PostgreSQL).  
- Automated notifications (email/SMS).  

---

## 👥 Group Members
- **Ahmed Raza (Project Lead & Developer)**  

---

## 📝 Conclusion
This project successfully demonstrates how **DSA concepts** (arrays, linked lists, file handling, classes, etc.) can be applied in real-world applications. It provides a **scalable and efficient** solution for managing a college system while being easy to use for students, teachers, and administrators.
