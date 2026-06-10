Employee Management System (C++)
📌 Description

This is a simple C++ console-based program that collects and displays information about employees. It uses a struct to store employee data and a function to display the details in a formatted way.

🧾 Features
Stores employee number and compensation
Takes input for 3 employees
Displays employee details in a formatted output
Uses structure (struct) for data grouping
Uses a separate function for display

🛠️ Technologies Used
C++
iostream (standard input/output library)
📂 Program Structure
Struct Used
struct Employee {
    int empNumber;
    float compensation;
};
Function Used
void display(Employee e)

Displays employee details in a formatted style.

▶️ How to Run
Step 1: Compile the program
g++ filename.cpp -o employee
Step 2: Run the program
./employee

💻 Sample Input
Enter details for Employee 1:
Employee Number: 101
Compensation: 50000

Enter details for Employee 2:
Employee Number: 102
Compensation: 60000

Enter details for Employee 3:
Employee Number: 103
Compensation: 55000

📤 Sample Output
Employee Details:

------------------------
Employee Number: 101

Compensation: 50000$

------------------------
Employee Number: 102

Compensation: 60000$

------------------------
Employee Number: 103

Compensation: 55000$

