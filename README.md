# JMBG Validator

## What is JMBG?

The Jedinstveni Matični Broj Građana (JMBG) is a unique identification number assigned to citizens in the former Yugoslav republics, including Bosnia and Herzegovina, Montenegro, Croatia, North Macedonia, Serbia, and Slovenia. It is similar to social security numbers or national identification numbers in other countries.

### Structure of JMBG

The JMBG consists of 13 digits formatted as `DDMMGGGRRBBBK`, where:

- **DD**: Day of birth (01-31)
- **MM**: Month of birth (01-12)
- **GGG**: Last three digits of the year of birth (e.g., for 1984, it is 984)
- **RR**: Region code indicating the place of birth or registration
- **BBB**: Unique number indicating gender (000-499 for males, 500-999 for females)
- **K**: Control digit calculated from the previous 12 digits

### Region Codes

The region code (RR) specifies the political region of birth. Here are some examples:

- **10-19**: Bosnia and Herzegovina
- **20-29**: Montenegro
- **30-39**: Croatia
- **41-49**: North Macedonia
- **50-59**: Slovenia
- **70-79**: Central Serbia
- **80-89**: Vojvodina
- **90-99**: Kosovo and Metohija

## About this App

This web application validates JMBG numbers. It checks if the JMBG follows the correct format and calculates the control digit to ensure validity. Additionally, it extracts and displays information from the JMBG, such as the date of birth, gender, and region of birth.

### Features

- **Input Validation**: Ensures the JMBG is exactly 13 digits long and follows the correct format.
- **Date Validation**: Checks if the date of birth is valid.
- **Checksum Validation**: Calculates the control digit to verify the JMBG.
- **Information Extraction**: Displays the date of birth, gender, and region of birth based on the JMBG.

### How to Use

1. Enter a JMBG number in the input field.
2. Click the "Validate" button.
3. The app will display whether the JMBG is valid or invalid.
4. If valid, additional details about the JMBG will be displayed.

### Privacy Note

The JMBG you provide to this form will NOT be saved anywhere nor will it be used or displayed to other parties. If you are still skeptical, enter 13 random digits to play with the application.

## Example

- **Input**: `0101984500036`
- **Output**:
  - **Valid JMBG**
  - **Date of Birth**: 01-01-1984
  - **Gender**: Male
  - **Region**: Bosnia and Herzegovina

[View the site here](https://j4v1ng.github.io/jmbg)
