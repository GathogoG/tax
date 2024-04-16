
# calculateNetSalary

A simple JavaScript function to calculate the net salary based on the basic salary and benefits, considering tax rates and deductions.

## Usage

To use this function, you can follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/GathogoG/tax/edit/main/README.md
 
## Instructions

 1. Navigate to the directory:

     ```bash
    cd calculateNetSalary

 2. Install Dependacies:

    ```bash
    npm install readline-sync

 3.Run the script:
 
    node calculateNetSalary.js

 4. Follow the prompts to enter the basic salary and benefits.

# Function Description
### The function calculateNetSalary takes two parameters:

basicSalary: The basic salary of the employee.
benefits: Any additional benefits or allowances.
It returns an object containing the following properties:

'Gross Salary': The total salary before deductions.
'Payee (Tax)': The amount deducted for income tax.
'NHIF Deductions': The amount deducted for NHIF (National Hospital Insurance Fund).
'NSSF Deductions': The amount deducted for NSSF (National Social Security Fund).
'Net Salary': The final net salary after deductions.


 # Example
   
    const result = calculateNetSalary(50000, 10000);
    console.log(result);

 # This will output;


 {
    'Gross Salary': 60000.00,
    'Payee (Tax)': 9000.00,
    'NHIF Deductions': 1500.00,
    'NSSF Deductions': 3600.00,
    'Net Salary': 46000.00
};

 # License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
