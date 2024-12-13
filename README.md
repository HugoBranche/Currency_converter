# Currency Converter

## Overview
The Currency Converter is a Python-based command-line tool that allows users to perform currency-related operations such as listing available currencies, fetching real-time exchange rates, and converting amounts between different currencies. It uses the Free Currency Converter API to provide accurate and up-to-date information.

---

## Features
- **List Currencies**: Displays a list of available currencies, their codes, and symbols.
- **Fetch Exchange Rate**: Provides the exchange rate between two currencies.
- **Convert Amounts**: Converts a specified amount from one currency to another using real-time exchange rates.
- **User-Friendly CLI**: Simple and intuitive command-line interface.

---

## Prerequisites
To run this project, ensure you have the following installed:
- Python 3.7 or later
- An active internet connection



---

## Usage
1. Run the program:
   ```bash
   python currency_converter.py
   ```

2. Follow the on-screen instructions to:
   - List available currencies
   - Get exchange rates
   - Convert amounts

### Example Commands:
- **List Currencies**:
  Enter `list` to see all available currencies.

- **Convert Amounts**:
  1. Enter `convert`.
  2. Input the base currency code (e.g., `USD`).
  3. Enter the amount (e.g., `100`).
  4. Enter the target currency code (e.g., `KSH`).

- **Fetch Exchange Rate**:
  1. Enter `rate`.
  2. Input the base currency code (e.g., `USD`).
  3. Input the target currency code (e.g., `JPY`).

---

## API Details
This project uses the [Free Currency Converter API](https://free.currencyconverterapi.com/) to fetch real-time currency data. Ensure you have a valid API key and update the `API_KEY` variable in the script.

---

## Acknowledgments
- **API Provider**: Free Currency Converter API for providing reliable exchange rate data.
- Python community for open-source libraries that made this project possible.

---

## Author
[Hugo Branche]  
[hugobranche0@gmail.com]  
(https://github.com/HugoBranche)

