Name: SHASHANK  
Company: CODTECH IT SOLUTIONS PVT.LTD  
ID: CT4CPP3337  
Domain: C++ PROGRAMMING  
Duration: June 25th to July 25th, 2024  
Mentor: Neelam Harish  

# CODTECH-Task2
###Student Management System

---

#### Objectives
The main objective of the Student Management System is to efficiently manage student information, including personal details, academic performance, and grades. This system allows for adding, editing, displaying, and deleting student records, while also providing functionality to calculate and update grades based on student marks.

---

#### Key Activities
1. **Initialization**: Load student records from a file upon system startup.
2. **Adding Students**: Add new student records with personal details and marks.
3. **Editing Details**: Update existing student personal details and marks.
4. **Deleting Students**: Remove student records from the system.
5. **Displaying Records**: Display all students or individual student records.
6. **Grade Calculation**: Automatically calculate and update student grades based on their marks.
7. **File Operations**: Save updated records to a file upon exiting the system.

---

#### Technology Used
1. **Programming Language**: C++
2. **File Handling**: Using C++ standard libraries (`fstream`, `iostream`) for reading and writing student data to files.
3. **Data Structures**: `vector` for storing lists of students and their marks.
4. **String Manipulation**: `string`, `sstream` for handling and parsing text data.

---

#### Key Insights
1. **Modular Design**: The system is divided into classes (`Student` and `StudentManagementSystem`) which encapsulate related functionalities, promoting code reuse and maintainability.
2. **Data Persistence**: Utilizes file I/O to maintain student records across sessions, ensuring data is not lost when the program exits.
3. **Input Validation**: Implements basic input validation to ensure valid user inputs for student records and marks.
4. **Grade Calculation Logic**: The system has a robust method for calculating grades based on average marks and also accounts for failure cases.
5. **User Interface**: Provides a simple text-based menu interface for user interaction, making the system easy to navigate and use.
