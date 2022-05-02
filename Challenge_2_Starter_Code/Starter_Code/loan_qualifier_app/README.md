# Challenge 2 - Loan Qualifier Application

The loan qualifier application allows the customer to input their information and it will provide them with which loans they are qualified for based on monthly debt ratio and loan to value ratio. It will also allow them to save the qualified loans in a csv file.

---

## Technologies

This project uses the python programming language and utilizes Anaconda, Git Bash, VS Code, and Github.

---

## Installation Guide

You must install and import fire and questionary from the Pythong Packacge Index. Run the following commands in Git Bash before importing them in your code.

*pip install fire
*pip install questionary

---

## Usage

The program will take in customer information and provide the loans they qualify for.

credit_score = questionary.text("What's your credit score?").ask()
    debt = questionary.text("What's your current amount of monthly debt?").ask()
    income = questionary.text("What's your total monthly income?").ask()
    loan_amount = questionary.text("What's your desired loan amount?").ask()
    home_value = questionary.text("What's your home value?").ask()

    Loan qualification criteria is based on:
        - Credit Score
        - Loan Size
        - Debit to Income ratio (calculated)
        - Loan to Value ratio (calculated)

    Args:
        bank_data (list): A list of bank data.
        credit_score (int): The applicant's current credit score.
        debt (float): The applicant's total monthly debt payments.
        income (float): The applicant's total monthly income.
        loan (float): The total loan amount applied for.
        home_value (float): The estimated home value.

    Returns:
        A list of the banks willing to underwrite the loan.

---

## Contributors

Allyssa Carmin

---

## License

SMU Fintech Course
