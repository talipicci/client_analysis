# Client Analysis

# Fictitious Data Generator

This Python script generates fictitious data for a database and saves it to a CSV file. The generated data includes full names, dates of birth, and monthly incomes.

## Requirements

- Python 3.x
- pandas
- Faker

You can install the required packages using pip:
```bash
pip install pandas faker
```
## Usage

1. Clone the repository:
```bash
git clone https://github.com/talipicci/client_analysis.git
```

2. Navigate to the project directory:
```bash
cd fictitious-data-generator
```

3. Run the script:
```bash
python generate_data.py
```

## Explanation

- The script generates fictitious data for a database with 100,000 rows.
- It uses the Faker library to generate random full names.
- Dates of birth are randomly generated between January 1, 1950, and January 1, 2006.
- Monthly incomes are randomly generated between $500.00 and $15,000.00.

## File Structure

- `generate_data.py`: Python script for generating fictitious data.
- `fictitious.csv`: Generated CSV file containing fictitious data.

## Code Explanation

- The script imports necessary libraries: pandas, Faker, and datetime.
- It defines functions to generate random dates of birth and monthly incomes.
- The data is generated and written to a CSV file using pandas DataFrame.
- Additional columns like 'Income Category' and 'Age' can be calculated based on generated data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

