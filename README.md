# CISP1010 — Lab 3: Roman Numerals Converter

## Overview

In this lab, you will write a C++ program that converts numbers between the Arabic numeral system (decimal numbers) and Roman numerals.

Roman numerals originated over 2,000 years ago and use letters to represent values. This program will let the user enter either a Roman numeral or an Arabic number and will output the equivalent value in the other system.

---

## Lab Requirements

### Program Behavior

- Your program must prompt the user to enter **either**:  
  - A valid Roman numeral (using only these characters: `I`, `V`, `X`, `L`, `C`, `D`, `M`)  
  - Or a positive Arabic number between **1 and 3999** inclusive.

- If the input is a Roman numeral, the program converts it to the Arabic number and displays the result.  
- If the input is an Arabic number, the program converts it to a Roman numeral and displays the result.

- If the input is invalid (contains invalid characters, or number out of range), the program prints an appropriate error message.

---

### Roman Numeral Rules

- Valid symbols: `I`, `V`, `X`, `L`, `C`, `D`, `M`  
- Use subtractive notation for 4 (`IV`), 9 (`IX`), 40 (`XL`), 90 (`XC`), 400 (`CD`), and 900 (`CM`)  
- The largest number that can be represented is 3999 (`MMMCMXCIX`)  
- Your program must reject invalid Roman numerals (e.g., invalid order or invalid characters)

---

### User-Defined Methods

Your program **must include at least two user-defined functions** besides `main()`:

- One function to convert Roman numerals to Arabic numbers  
- One function to convert Arabic numbers to Roman numerals  

You can add helper functions as needed.

---

## Sample Program Output

```bash
Enter a Roman numeral or positive Arabic number: XXVII
The decimal value of XXVII is 27.
```
```bash
Enter a Roman numeral or positive Arabic number: MCMXCIV
The decimal value of MCMXCIV is 1994.
```
```bash
Enter a Roman numeral or positive Arabic number: 42
The Roman numeral of 42 is XLII.
```
```bash
Enter a Roman numeral or positive Arabic number: ABC
Invalid Roman numeral.
```
```bash
Enter a Roman numeral or positive Arabic number: -1
Invalid Arabic number.
```
---

## Submission Instructions

-  Push your finished program and ensure your code passes all tests.
-  Click the green checkmark and copy and paste the URL of the resulting page into Brightspace.
- Your code must **compile and run** without errors.

---

## Grading Rubric (100 points total)

| Category                 | Description                                                          | Points |
|--------------------------|----------------------------------------------------------------------|--------|
| **Correctness**          | Program compiles, runs, and passes all functional tests              | 85     |
| • Roman Numeral to Arabic| Produces correct conversion                                          | 30     |
| • Arabic to Roman Numeral| Produces correct conversion                                          | 30     |
| • Output Formatting      | Matches sample output exactly (format, punctuation, spacing)         | 10     |
| • Edge Cases             | Handles values unexpected/invalid numeric values                     | 15     |
| **Code Style & Comments**| Proper indentation, naming, organization, and inline comments        | 15     |
