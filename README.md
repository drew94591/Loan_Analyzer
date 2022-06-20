# Loan Analyzer Application
Loan officers need a way to determine if a loan applicant is credit worthy. This application searches through a provided list of loans defined within the daily_rate_sheet.csv file and determines if there are any qualifying loans based upon an applicant's credit score, debt to income ratio, loan to value ratio, and maximum loan amount.  The qualifying loans are then provided as output to the qualifying_loans.csv file for the loan officers to review. 

---

## Technologies

This application leverages python 3.7 with the following libraries and packages:

* [csv](https://docs.python.org/3/library/csv.html) - For reading and writing to csv files

* [path](https://docs.python.org/3/library/pathlib.html) - Used to define file path

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To use the loan analyzer application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with the following prompts.

![Loan Qualifier Prompts](Images/loan_qalifier.png)

---

## Contributors

Brought to you by [Drew Herrera](https://www.linkedin.com/in/andrewjherrera).

---

## License

MIT
