# RandomPasswordGenerator.github.io
This Python script generates a **strong, random password** based on user input. The password ensures security by incorporating a mix of lowercase letters, uppercase letters, numbers, and special characters.

---

## Features
- Generates a strong password with a customizable length.
- Ensures at least **60% letters** and **40% digits and punctuation marks** in the password.
- Validates user input for numeric and length requirements.
- Uses Python's built-in `random` module for secure randomization.

---

## Requirements
- Python 3.6+

---

## Usage
1. Clone this repository or download the script.
2. Run the script in your terminal:
   ```bash
   python password_generator.py
   ```
3. Follow the prompts to enter the desired password length (minimum 8 characters).

---

## Example
### Input
```plaintext
How many characters do you want in your password? 12
```

### Output
```plaintext
Strong Password: Gq1m@2R+o!8T
```

---

## Code Explanation

### Step 1: Import Required Modules
- The script uses the `string` module for predefined character sets and the `random` module for randomization.

### Step 2: Character Groups
The following groups are stored in separate lists:
- Lowercase letters (`a-z`)
- Uppercase letters (`A-Z`)
- Digits (`0-9`)
- Punctuation (special characters like `@, #, !`, etc.)

### Step 3: User Input Validation
- The user is prompted for the password length.
- Ensures the input is:
  - A valid number.
  - At least 8 characters long.

### Step 4: Password Composition
- 60% of the password is composed of letters (30% lowercase, 30% uppercase).
- 40% is composed of digits and punctuation.
- The script uses `random.shuffle()` to ensure randomness.

### Step 5: Password Generation
- The characters are joined into a single string to produce the password.

---

## Screenshot
Here’s a mock terminal screenshot showing the program in action:
![image](https://github.com/user-attachments/assets/0f36ddf0-b1a4-426b-b587-39bb87121725)
