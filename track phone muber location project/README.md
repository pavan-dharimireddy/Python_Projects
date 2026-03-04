# Phone Number Location Tracker

A simple Python tool to track the geographical location and service provider of a phone number using the `phonenumbers` library.

## Features

- **Geographical Location**: Determines the country or region of the phone number.
- **Carrier Information**: Identifies the service provider (carrier) associated with the number.

## Prerequisites

- Python 3.x
- `phonenumbers` library

## Installation

Install the required Python package using pip:

```bash
pip install phonenumbers
```

## Usage

1. **Set the Phone Number**:
   Open `test.py` and update the `number` variable with the phone number you want to check. Ensure the number includes the international country code (e.g., `+91` for India).

   ```python
   # test.py
   number = "+917894612336"
   ```

2. **Run the Tracker**:
   Execute the main script:

   ```bash
   python track_ph-no.main.py
   ```

## Project Structure

- `track_ph-no.main.py`: The main script that processes the number and prints location/carrier details.
- `test.py`: A configuration file used to store the input phone number.
