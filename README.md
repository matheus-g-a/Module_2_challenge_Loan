# Loan Qualifier Application

This project will indentify the banks that allow the customer take the mortgage based in some criterias.

---

## Technologies

For this project we used python 3.7 and three libraries: 
Fire
Questionary
PyTest

---

## Installation Guide

To make sure that the program will work you have to install Python 3.7 or plus, and the 3 modules below:
pip install fire
pip install questionary
pip install pytest

---

## Examples

In this case we can see the final part of the code below:
def run():
    """The main function for running the script."""

    # Load the latest Bank data
    bank_data = load_bank_data()

    # Get the applicant's information
    credit_score, debt, income, loan_amount, home_value = get_applicant_info()

    # Find qualifying loans
    qualifying_loans = find_qualifying_loans(
        bank_data, credit_score, debt, income, loan_amount, home_value
    )

    # Save qualifying loans
    save_qualifying_loans(qualifying_loans)

---

## Usage

This project shoulb the executed by anaconda developer enviroment.

---

## Contributors

Developed for Matheus Araujo, using the original code from UC Berkeley Fintech Bootcamp.

---

## License

This program is allowed to public use.
