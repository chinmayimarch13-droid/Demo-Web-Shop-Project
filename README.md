# Demo-Web-Shop-Project
# Demo Web Shop - Product Search Automation Testing

## Project Description
This project automates the Product Search functionality of the Demo Web Shop website using Selenium and Python.

Website Used:
https://demowebshop.tricentis.com/

The purpose of this project is to validate product search functionality through automation testing and improve testing skills using real-world scenarios.

## Features Tested
- Valid Product Search
- Invalid Product Search
- Empty Search Validation
- Product Result Verification
- Search Functionality Testing

## Test Scenarios

### Valid Search
Search for existing product:
- Desktop
- Computer

Expected Result:
Relevant products should be displayed.

### Invalid Search
Search for:
- xyz123

Expected Result:
No matching products found.

### Empty Search
Click search without entering text.

Expected Result:
System handles empty search properly.


## Project Structure

DemoWebShop_Project/
│
├── tests/
│   └── test_search.py
├── reports/
├── requirements.txt
├── README.md

## Installation

Install Selenium:

bash
pip install selenium

Or install all dependencies:

pip install -r requirements.txt

## How to Run

Run Python file:

```bash
python test_search.py


Or using pytest:

```bash
pytest

## Sample Automation Flow

1. Open Demo Web Shop
2. Locate search box
3. Enter product name
4. Click search
5. Validate search results
6. Close browser

## Tools Used
- Python
- Selenium
- Pytest
- ChromeDriver
- GitHub
