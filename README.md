# EMPLOYEE MANAGEMENT SYSTEM:

- **The Employee Management System is a C++ console application that helps in managing employee records efficiently. It provides functionalities for adding, displaying, modifying, searching, and deleting employee data. Additionally, the system includes a basic login mechanism to ensure secure access.**

  # DEVELOPERS INFORMATION:
  ### TEAM LEADER:
    - #### ANKIT KUMAR YADAV
    - 

## FEATURES:
### User Authentication: 
  - **Register a new user with a name and password.**
  - **Login with a username and password to access the system.**

- ### Employee Record Management:
  - **Add New Employee**: Insert a new employee's details, including name, ID, designation, age, salary, and experience.
  - **Display Employees**: View all employee records stored in the system.
  - **Modify Employee**: Update details of an existing employee based on their ID.
  - **Search Employee**: Search for an employee by their ID and view their details.
  - **Delete Employee**: Remove an employee's record from the system based on their ID.

- **Persistent Data Storage**: Employee records are stored in a text file (`Employee_Record.txt`), ensuring data persists between sessions.

## Getting Started:

### Prerequisites:

- **C++ Compiler**: Make sure you have a C++ compiler installed (e.g., GCC, Clang).
- **Windows OS**: The application uses some Windows-specific headers (`windows.h`, `conio.h`), so it is best suited for Windows systems.

## Installation:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your_username/EmployeeManagementSystem.git
   cd EmployeeManagementSystem
- **Compile the code:**
g++ EmployeeManagementSystem.cpp -o EmployeeManagementSystem

- **Run the executable:**
./EmployeeManagementSystem
## USAGE:
- **On launching the application, you will be prompted to either register a new user or login with existing credentials.**

- **After logging in, the main menu offers the following options:**

**1. Enter New Record: Add a new employee to the system.**
**2. Display Record: Display all employee records.**
**3. Modify Record: Modify details of an existing employee.**
**4. Search Record: Search and display a specific employee's record by ID.**
**5. Delete Record: Delete an employee's record from the system.**
**6. Exit: Exit the application.**
## FILE STRUCTURE:
- **EmployeeManagementSystem.cpp:** The main source code file containing the implementation of all features.
- **Employee_Record.txt:** The file where employee records are stored.
- **Ep_data.txt:** The file where user registration details (username and password) are stored.
