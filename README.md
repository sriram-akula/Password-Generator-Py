🔐 Python Password Generator (Tkinter GUI)
📌 Project Overview

This project is a GUI-based Random Password Generator built using Python and Tkinter.

The application allows users to:

Specify password length

Choose whether characters can repeat

Instantly generate a secure random password

It combines Python programming, GUI development, and basic input validation.

🎯 Features

🔢 User-defined password length

🔁 Option to allow or prevent character repetition

🔐 Generates strong passwords using:

Uppercase letters

Lowercase letters

Numbers

Special characters

⚠️ Error handling for invalid inputs

🖥️ Simple and interactive GUI

🛠️ Technologies Used

Python

Tkinter (GUI Development)

Random Module

Exception Handling

⚙️ How It Works

User enters:

Password length

Repetition choice (1 = No repetition, 2 = Allow repetition)

Program:

Uses random.sample() if no repetition

Uses random.choices() if repetition allowed

Displays generated password in a read-only field

🚀 How to Run

Install Python (3.x recommended)

Save the script as password_generator.py

Run:
