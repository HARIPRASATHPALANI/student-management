
# 🎓 Student Management System (Java Console App)

Welcome to the **Student Management System** – a simple yet effective **console-based Java application** that lets you perform basic operations to manage student records. Ideal for beginners who want to practice **Java fundamentals**, **OOP**, and **CLI interaction**.

---

## 📌 Project Description

This application provides a command-line interface that allows users to manage a list of students. Each student has:

- 🆔 **ID**
- 🧑 **Name**
- 🎂 **Age**

Using this tool, you can add new students, view all student records, update or delete specific student entries, and search for students by their ID.

---

## 🚀 Features

Here’s what this system can do:

- ➕ **Add Student** – Enter ID, name, and age to register a student.
- 📋 **View Students** – List all student records in the system.
- ✏️ **Update Student** – Modify the name and age of an existing student.
- ❌ **Delete Student** – Remove a student using their ID.
- 🔍 **Search Student** – Find a student by ID and view their details.
- 🔚 **Exit** – Quit the application safely.

---

## 🛠️ Technologies Used

- 💻 **Java (JDK 8+)**
- 🧠 **Object-Oriented Programming (OOP)**
- ⌨️ **Console Input/Output (CLI)**

---

## 📁 File Structure

📦 student-management-system
└── 📄 StudentManagementSystem.java

yaml
Copy
Edit

- `Student` class – holds student data and `toString()` method.
- `StudentManagementSystem` – contains logic for menu, input, and actions.

---

## ⚙️ How to Run the Project

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/student-management-system.git
   cd student-management-system
Compile the Java file

bash
Copy
Edit
javac StudentManagementSystem.java
Run the compiled program

bash
Copy
Edit
java StudentManagementSystem
🖥️ Sample CLI Interaction
pgsql
Copy
Edit
--- Student Management System ---
1. Add Student
2. View Students
3. Update Student
4. Delete Student
5. Search Student
6. Exit
Choose an option: 1
Enter ID: 101
Enter Name: Alice
Enter Age: 20
Student added successfully.
💡 Possible Enhancements
Here are some ideas for improving the system:

💾 Save/load data to/from a file

🛑 Add input validation (e.g., no negative age)

🌐 Switch to a GUI (JavaFX or Swing)

📊 Sort/filter functionality (by name or age)

🧪 Unit tests using JUnit

📃 License
This project is licensed under the MIT License.

🤝 Contributing
Contributions are welcome! Whether it's fixing bugs, adding new features, or improving the documentation, feel free to fork the repo and open a pull request.

