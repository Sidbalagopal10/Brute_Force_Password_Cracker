# Brute_Force_Password_Cracker

This script is a Python-based password-cracking simulation using a brute-force method. It attempts to guess a user-provided password by randomly generating character combinations until it matches the input password.

Key Features:
Character Set: Includes a mix of numbers, lowercase and uppercase letters, and special characters (@, !, $, #, %, _) to increase password complexity.
Guessing Mechanism: Utilizes Python's random.choices() function to randomly select characters from the character list, forming guesses of the same length as the input password.
Loop Until Match: The loop continues until the randomly generated guess matches the input password.
How it Works:
The script prompts the user to enter a password.
It then enters a loop where it generates random guesses by selecting characters from a defined character set.
Each guess is printed to the console, showing the progression of guesses until a match is found.
Once the correct password is guessed, it prints "Your password is [password]."
⚠️ Disclaimer: This script is for educational purposes only. It demonstrates how brute-force attacks work in a controlled environment. Always follow ethical practices and only test with permissions.
