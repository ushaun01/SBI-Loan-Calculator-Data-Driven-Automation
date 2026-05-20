🧪 SBI Loan Calculator Data-Driven Automation Project

📌 Project Overview

This project demonstrates a real-time **Data-Driven Test Automation Framework** using Python and Selenium WebDriver.

The automation script interacts with the live SBI Home Loan Calculator application, reads multiple datasets from an Excel file, performs EMI calculations, validates generated results, and writes execution status back into Excel.

The project showcases practical implementation of:

- Selenium Automation
  
- Data-Driven Testing (DDT)
  
- Excel Handling using OpenPyXL
  
- Dynamic Result Validation

---

🚀 Technologies Used

- Python
- 
- Selenium WebDriver
- 
- OpenPyXL
- 
- Excel
- 
- CSV

---

🎯 Project Objectives

- Automate EMI calculation validation
  
- Implement Data-Driven Testing approach
  
- Read test data from Excel sheets
  
- Validate actual vs expected EMI values
  
- Store execution results back into Excel

---

 📂 Project Structure

```bash
SBI-Loan-Calculator-Data-Driven-Automation/
│
├── test_loan_calculator.py
├── XLUtilities.py
├── Loan-usha.xlsx
├── Loan-usha.csv
├── README.md
```

---

🔧 Key Features

✔ Reads multiple test datasets from Excel

✔ Automates SBI Loan Calculator using Selenium

✔ Performs EMI calculation validation

✔ Compares Actual EMI vs Expected EMI

✔ Writes Pass/Fail results into Excel

✔ Highlights results:

- Green → Pass
  
- Red → Fail

✔ Supports reusable Excel utility functions

---

 ▶️ How to Run the Project

1️⃣ Install Required Packages

```bash
pip install selenium openpyxl
```

---

2️⃣ Update Excel File Path

Modify the Excel file path inside the script:

```python
file="D:\\OneDrive\\Excel\\Loan-usha.xlsx"
```

---

3️⃣ Execute the Script

```bash
python test_loan_calculator.py
```

---

🔍 Functional Workflow

📥 Read Data from Excel

The framework reads:

- Loan Amount
  
- Interest Rate
  
- Loan Tenure
  
- Expected EMI

from Excel sheets dynamically.

---
 🌐 Perform Web Automation

The script:

- Launches browser
  
- Opens SBI Loan Calculator
  
- Enters loan details
  
- Calculates EMI

---

 ✅ Validation Logic

- Captures Actual EMI from application

- Compares with Expected EMI from Excel
  
- Marks test result as Pass or Fail

---

### 📝 Write Results to Excel

Execution results are automatically updated into Excel sheets with color formatting.

---

⭐ Project Outcome

This project provides hands-on experience in implementing a real-world **Data-Driven Testing Framework** using Selenium and Python.

It demonstrates practical automation skills including:

- Test data management
  
- Dynamic validation
  
- Excel integration
  
- Reusable utility methods

---
👩‍💻 Author

### Usha Nazare

- Mechanical Engineering Graduate
  
- QA Automation Enthusiast
  
- Skilled in Selenium, Python, PyTest, API Testing, and Data-Driven Frameworks
