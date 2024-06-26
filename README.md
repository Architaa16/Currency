# Currency Converter

This is a simple Python program that converts currency from one denomination to another using exchange rates fetched from an online API.

## Requirements

- Python 3.x
- `requests` library

## Installation

1. Ensure you have Python 3 installed. If not, you can download it from [here](https://www.python.org/downloads/).
2. Install the `requests` library if you don't have it already. You can install it using pip:
    ```sh
    pip install requests
    ```

## Usage

1. Clone the repository or download the script.
2. Run the script using Python:
    ```sh
    python currency_converter.py
    ```

## How It Works

1. The script fetches the latest exchange rates from the API `https://api.exchangerate-api.com/v4/latest/USD`.
2. It prompts the user to enter the amount, the currency to convert from, and the currency to convert to.
3. It performs the conversion and displays the result.

## Example

```sh
Enter the amount: 400
Enter the currency you want to convert from (e.g., USD, INR): USD
Enter the currency you want to convert to (e.g., INR): INR
400.0 USD is equal to 33380.00 INR

