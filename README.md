🧪SBI-Loan-Calculator-Data-Driven-Automation  

 📌 Project Overview

This is a mini project demonstrating data-driven testing.

This project demonstrates a real-time data-driven test automation approach using Selenium with Python.

The automation script interacts with the live SBI Home Loan Calculator, reads multiple test datasets from an Excel file, performs calculations, and validates the EMI results.



 🚀 Technologies Used

* Python
 
* Selenium WebDriver
  
* OpenPyXL (Excel Handling)
  
* Excel (Test Data Source)

🎯 Objective

Automate EMI calculation validation

Implement Data-Driven Testing (DDT)

Use Excel as a test data source

Validate application results dynamically


 📂 Project Structure

├── test_loan_calculator.py

├── XLUtilities.py

├── Loan-usha.xlsx

├── Loan-usha.csv

├── README.md

🔧 Key Features

* Reads test data from Excel file

* Performs form input automation on SBI Loan Calculator

* Captures EMI result dynamically

* Compares actual vs expected EMI

* Writes test results back to Excel

* Highlights results (Pass = Green, Fail = Red)




 ▶️ How to Run

1. Install dependencies:

pip install selenium openpyxl

2. Update file path in script:


file="D:\\OneDrive\\Excel\\Loan-usha.xlsx"

3. Run the script:

python test_loan_calculator.py


🔍 Code Highlights:

 Reading Data from Excel

Sending Data to Web Application


 Validation Logic


Writing Result to Excel


⭐ Conclusion

This project simulates real-world testing by validating multiple datasets against a live application using a data-driven testing approach, making it a strong foundation for automation frameworks.

👩‍💻 Author

Usha Nazare
