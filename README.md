The Password Strength Checker is a beginner-friendly cybersecurity project designed to evaluate the robustness of user-provided passwords. Developed using Python, this tool analyzes password composition based on length, character variety (uppercase, lowercase, digits, and special characters), and assigns a strength rating. This project serves as an educational resource for understanding fundamental security principles and regular expression usage in Python.
Features
Length Validation: Ensures the password meets a minimum length requirement (8 characters).
Character Diversity Analysis: Checks for the presence of:
Uppercase letters (A-Z)
Lowercase letters (a-z)
Numerical digits (0-9)
Special characters (non-alphanumeric symbols)
Strength Scoring System: Assigns a score from 0 to 5 based on criteria met.
Clear Output: Provides immediate feedback categorizing the password as Weak, Medium, or Strong.

Project Structure
password_checker/
├── README.md             # Project documentation
├── password_checker.py   # Core Python script for logic execution
└── index.html            # Basic frontend interface (optional)

Prerequisites
Python 3.x installed on your system.
No external libraries are required; the project uses only Python’s built-in re module.

Installation and Usage

1.Clone the Repository:
git clone https://github.com/your-username/password_checker.git
cd password_checker

2.Run the Script:
Execute the Python script in your terminal or command prompt:
python password_checker.py

3. Input Password:
When prompted, enter the password you wish to evaluate:
Enter your password:

4. View Results:
The script will output the strength classification:
Weak: Score ≤ 2
Medium: Score 3–4
Strong: Score 5

How It Works: 
The script evaluates the password against five criteria:
1.Length ≥ 8 characters.
2.Contains at least one uppercase letter.
3.Contains at least one lowercase letter.
4.Contains at least one digit.
5.Contains at least one special character.

Each criterion met adds 1 point to the total score. The final score determines the strength category.
Enter your password:  MyP@ssw0rd!
Password Strength: Strong 
