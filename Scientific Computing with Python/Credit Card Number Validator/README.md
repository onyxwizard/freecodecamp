# 🔢 Credit Card Number Validator 🛡️

This Python script implements a **Luhn Algorithm** to validate credit card numbers. It ensures that a given card number adheres to the checksum rules defined by the Luhn Algorithm, which is widely used for verifying the validity of identification numbers like credit cards.


## 📋 How It Works

1. **Input Card Number** : Provide a credit card number as a string (e.g., `'4111-1111-4555-1142'`).
2. **Preprocessing** : Remove any hyphens (`-`) or spaces () from the input.
3. **Validation** :
    - Reverse the card number.
    - Apply the Luhn Algorithm to calculate the checksum.
    - Determine if the total sum modulo 10 equals zero (`total % 10 == 0`).
4. **Output** : Print whether the card number is `VALID!` or `INVALID!`.


## 🌟 Key Features

- 🔢 **Luhn Algorithm** : Implements the industry-standard checksum algorithm for validating card numbers.
- 🔄 **Handles Formatting** : Automatically removes hyphens (`-`) and spaces () from the input.
- ✅ **Simple Validation** : Outputs `VALID!` if the card number passes the checksum test, otherwise `INVALID!`.
- 📚 **Modular Code** : Separates validation logic into reusable functions for clarity and scalability.

## 🚀 Example Output

```plaintext
Input Card Number: 4111-1111-4555-1142

Output: VALID!
```

## 🛠️ Code Breakdown

1. **`verify_card_number` Function** :
    
    - Reverses the card number and processes odd and even digits separately.
    - Doubles every second digit (even-indexed in reversed order) and adjusts values greater than or equal to 10.
    - Sums all digits and checks if the total is divisible by 10.
2. **`main` Function** :
    
    - Defines a sample card number and preprocesses it using `str.translate` to remove formatting characters.
    - Calls the `verify_card_number` function and prints the result.



## 🌍 Try It Yourself!

1. Clone this repository.
2. Run the script in your Python environment.
3. Replace the `card_number` variable in the `main` function with your own test card numbers (e.g., `'5555-5555-5555-4444'`).
4. Experiment with valid and invalid card numbers to see the validation in action! 🧪


Happy Coding! ✨💻  Validate credit card numbers effortlessly with this implementation of the Luhn Algorithm! 🔢🛡️