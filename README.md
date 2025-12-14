# Prodigy_CS_passwordcomplexitychecker
*Password Complexity Checker*

This Python program evaluates the strength of a user-entered password based on commonly accepted security standards. It checks whether the password meets essential complexity requirements and provides clear feedback on its strength.

*Features*

Verifies minimum password length (at least 8 characters)

Checks for the presence of:

Uppercase letters (A–Z)

Lowercase letters (a–z)

Numbers (0–9)

Special characters (e.g., !@#$%^&*)

Classifies passwords as Weak, Good, or Strong

*How It Works*

The program uses Python’s built-in re (regular expressions) module to analyze the password. Each satisfied condition contributes to a score, which determines the final strength classification.

*Strength Criteria*

Strong Password: Meets all complexity requirements

Good Password: Meets at least three requirements

Weak Password: Meets fewer than three requirements

*Use Case*

This script can be used in beginner cybersecurity projects, authentication systems, or as a learning example for regular expressions and input validation in Python.
