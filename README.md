# 🎓 University Course Registration System (C Project)

A **C-based University Course Registration System** that allows students to **search, add, remove, and manage courses** efficiently.  
The system also supports **undo/redo operations**, **conflict checking**, and **credit limit validation**, making it both practical and educational.

---

## 📘 Features

✅ **Add & Remove Courses**
- Register or remove courses using their course code.  
- Prevents exceeding the maximum allowed credits (default: 14).  

✅ **Undo / Redo System**
- Supports **undo** for the last add/remove action.  
- Supports **redo** for undone operations.  

✅ **Course Conflict Detection**
- Detects **day/time clashes** automatically.  

✅ **Course Search**
- Search by **course code** or **course title**.  

✅ **View Options**
- Display all available courses.  
- View **registered courses**.  
- View **suggested courses** by semester.  

✅ **Data Structures Used**
- **Linked List** → For managing registered courses.  
- **Stack** → For undo/redo operation tracking.  

---

## 🧠 Concepts Demonstrated
- Structs and Typedefs  
- Linked Lists  
- Stack Implementation  
- String Manipulation  
- Function Modularization  
- Dynamic Memory Allocation (`malloc`, `free`)  
- Defensive Programming (overflow checks, validation)

---

## 🛠️ How to Compile and Run

### **Using GCC**
```bash
gcc main.c -o course_system
./course_system
```

### **Using Code::Blocks or Dev-C++**
1. Create a new console project.  
2. Copy the code into `main.c`.  
3. Build and run the project.

---

## 🧾 Example Usage

```
Welcome to the University Course Registration System!

1. View All Courses
2. Search Course by Code
3. Search Course by Title
4. Add a Course
5. Remove a Course
6. Undo Last Action
7. Redo Last Action
8. View Registered Courses
9. View Suggested Courses by Semester
10. Exit
```

---

## 🧩 Sample Output

```
Course CSE161 (Programming Language I) added successfully on Monday at 10:00 AM - 11:30 AM.
Course CSE162 (Programming Language I Lab) added successfully on Wednesday at 2:00 PM - 4:00 PM.
Undo: Course CSE162 removed.
Redo: Course CSE162 added.
```

---

## 📂 Project Structure

```
📁 CourseRegistrationSystem
├── main.c                # Main program source code
├── README.md             # Project documentation
└── (optional) course.txt # Future extension for file saving
```

---

## ⚙️ Constants
| Constant | Description |
|-----------|-------------|
| `MAX_CREDITS` | Maximum credits a student can register (default: 14) |
| `MAX` | Maximum stack size for undo/redo operations (default: 50) |

---

## 🚀 Future Improvements
- 🔹 Add file I/O for saving registered courses  
- 🔹 Implement student login with authentication  
- 🔹 Create a graphical or terminal UI menu  
- 🔹 Add prerequisite checking for advanced courses  

---

## 👨‍💻 Author
**Mohammodullah Al Mahin**  
🎓 BSc in Computer Science & Engineering  
🏛️ Southeast University  

🌐 [GitHub Profile](https://github.com/mahinexe)

---

## 📜 License
This project is released under the **MIT License** — free to use, modify, and distribute.
