# Payroll System Testing & Validation Project

##  Overview

This project is a payroll processing system developed as part of a group assignment. The system collects employee data, validates input, calculates payroll (including taxes and overtime), and outputs results to an Excel file.

My primary role in this project was **Testing and Debugging**, ensuring the system works correctly under both normal and error conditions.

---

##  My Role (QA / Tester)

* Designed the overall **testing strategy**
* Created **unit tests using pytest**
* Performed **integration testing** across all modules
* Conducted **manual testing with real scenarios**
* Identified and fixed bugs in validation and calculations
* Verified Excel output accuracy
* Documented all test results and debugging steps

---

## Testing Approach

### 1. Unit Testing (pytest)

* Tested individual modules such as:

  * Security Module (input validation)
  * Pay Calculation Module
* Created test cases for:

  * Valid inputs
  * Invalid hours
  * Invalid employee IDs
  * Employee not found scenarios

### 2. Integration Testing

* Tested full workflow:

  1. Data input
  2. Validation
  3. Database lookup (Excel)
  4. Payroll calculation
  5. Output generation

### 3. Manual Testing

* Ran the full program with multiple test cases
* Verified outputs in terminal
* Captured results for documentation

---

## Features Tested

* Input validation (name, ID, hours, dependents)
* Payroll calculations:

  * Regular pay
  * Overtime pay (1.5x rate)
  * State tax (5.6%)
  * Federal tax (7.9%)
  * Net pay
* Excel output generation (PayrollReport.xlsx)
* Error handling and edge cases

---

## Technologies Used

* Python
* pytest
* pandas
* openpyxl
* Excel (EmployeeTable & PayrollReport)

---

##  Test Results

| Test Case            | Result |
| -------------------- | ------ |
| Valid Employee       | PASS   |
| Invalid Hours        | PASS   |
| Invalid ID           | PASS   |
| Employee Not Found   | PASS   |
| Invalid Name         | PASS   |
| Integration Workflow | PASS   |

 All test cases passed successfully after debugging

---

##  Debugging Highlights

* Fixed environment issues (pytest not recognized)
* Installed missing dependencies (pandas, openpyxl)
* Corrected employee database inconsistencies
* Improved validation logic for names, IDs, and hours

---

##  Project Structure

```
/project-folder
│── final_project.py
│── test_payroll.py
│── EmployeeTable.xlsx
│── PayrollReport.xlsx
│── README.md
```

---

##  How to Run

### 1. Install dependencies

```bash
pip install pandas openpyxl pytest
```

### 2. Run the program

```bash
python final_project.py
```

### 3. Run tests

```bash
pytest
```

---

## 📈 Key Takeaways

* Learned real-world **QA testing practices**
* Gained experience in **automated testing with pytest**
* Improved debugging and problem-solving skills
* Worked in a team using structured development modules

---

##  Team Collaboration

Worked as part of a team where different members developed modules such as:

* Data Entry
* Security
* Pay Calculation
* Data Output

My responsibility ensured all modules worked correctly together.

---

## 📎 Author

**Ismail Babani**
QA Tester (Aspiring)

---
