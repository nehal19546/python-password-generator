Password Generator

A simple and user-friendly Password Generator developed using Python. The project allows users to generate random and customizable passwords based on their preferred length and character requirements.

📌 Project Description

The Password Generator is a Python-based command-line application designed to generate random passwords according to the user's selected requirements. The program allows the user to specify the desired password length and choose whether the password should contain uppercase letters, numbers, and special characters.

The application uses Python's built-in string and random modules to generate passwords. Based on the options selected by the user, the program creates a character set and randomly selects characters to construct the password.

The program also ensures that the generated password satisfies the selected requirements by including at least one uppercase letter, number, or special character when those options are enabled. The generated characters are then shuffled to make the final password more randomized.

This project is suitable for beginners and demonstrates important Python programming concepts such as functions, variables, conditional statements, loops, strings, lists, modules, user input, exception handling, randomization, and string manipulation.

✨ Features

🔐 Generate random passwords
📏 Choose the required password length
🔠 Option to include uppercase letters
🔢 Option to include numbers
🔣 Option to include special characters
🎲 Randomly generates password characters
🔀 Shuffles the generated password
⚠️ Validates password length
💻 Simple command-line interface
🚀 Easy to run and use

🛠️ Technologies Used

-Python 3
-random module
-string module
-🐍 Python Concepts Used
-Variables
-Data types
-Functions
-Function arguments
-Conditional statements
-if statements
-for loops
-Strings
-Lists
-User input
-Exception handling
-Modules
-Random character selection
-String manipulation

📁 Project Structure

Password-Generator/
│
├── password_generator.py
└── README.md
password_generator.py

Contains the complete Python program used to generate customizable random passwords.

README.md

Contains information about the project, its features, setup instructions, usage, and implementation.

▶️ How to Run

1. Install Python

Make sure Python 3 is installed on your computer.

Check the installed Python version using:

python --version

or:

python3 --version

2. Clone the Repository

Clone your GitHub repository using:

git clone https://github.com/your-username/password-generator.git
3. Open the Project Folder
cd password-generator
4. Run the Program

Run the Python program using:

python password_generator.py

If your system uses python3:

python3 password_generator.py

🔐 How It Works

-The program starts by asking the user to enter the desired password length.
-The user is asked whether uppercase letters should be included.
-The user is asked whether numbers should be included.
-The user is asked whether special characters should be included.
-The program checks whether the requested password length is sufficient for the selected requirements.
-If uppercase letters are selected, at least one uppercase letter is added.
-If numbers are selected, at least one number is added.
-If special characters are selected, at least one special character is added.
-The remaining characters are randomly selected from the allowed character set.
-The generated password characters are shuffled and displayed to the user.

🎯 Objective

The main objective of this project is to develop a simple password generation tool using Python while gaining practical experience with randomization, strings, functions, conditional statements, loops, lists, modules, and exception handling.

The project also demonstrates how user-defined requirements can be used to generate customized output.

⚙️ Password Generation

The program uses the Python string module to obtain different types of characters.

Lowercase Letters

The program uses:

string.ascii_lowercase

to include lowercase English letters.

Uppercase Letters

When the user selects the uppercase option, the program uses:

string.ascii_uppercase

to add uppercase letters.

Numbers

When numbers are selected, the program uses:

string.digits

to include numerical characters.

Special Characters

When special characters are selected, the program uses:

string.punctuation

to include symbols such as !, @, #, $, %, and other punctuation characters.

🔀 Randomization

The project uses Python's random module to select characters randomly.

The function:

random.choice()

is used to select random characters from the available character set.

After generating the password, the characters are converted into a list and shuffled using:

random.shuffle()

This helps randomize the order of the required characters.

⚠️ Error Handling

The program includes error handling for password length requirements.

If the selected password length is too short to satisfy the required character categories, the program raises a ValueError.

The message displayed is:

Password length is too short for the specified criteria.

For example, if the user requests a password length of 2 while selecting uppercase letters, numbers, and special characters, the program rejects the request because at least three required characters need to be included.

💻 Sample Execution

Example:

Enter password length: 12
Include uppercase letters? (y/n): y
Include numbers? (y/n): y
Include special characters? (y/n): y

A7#mqp2!Kx9@

The exact password will be different each time because the program generates characters randomly.

📋 Input Options

-Input	Purpose
-Password length	Specifies the number of characters
-y	Enables the selected character category
-n	Disables the selected character category
-Uppercase	Adds uppercase letters
-Numbers	Adds numerical characters
-Special characters	Adds punctuation/symbols

🌟 Advantages

-Simple and easy to use.
-Generates passwords quickly.
-Allows customization based on user requirements.
-Uses random character selection.
-Supports uppercase letters, numbers, and special characters.
-Prevents passwords from being shorter than the selected mandatory criteria.
-Requires no external Python libraries.
-Can be executed directly from the command line.

⚠️ Limitations

The current version has some limitations:

-It generates only one password per execution.
-It does not provide a graphical user interface.
-It does not save generated passwords.
-It does not calculate password strength.
-It does not allow the user to specify the exact number of each character type.
-The program does not provide advanced password-management features.

🔮 Future Improvements

The project can be enhanced in the future by adding:
🔄 Generate multiple passwords at once.
📊 Password strength checking.
🎨 Graphical User Interface (GUI).
📋 Copy generated password to clipboard.
💾 Save passwords securely.
🔢 Allow users to specify the exact number of uppercase letters, numbers, and special characters.
🔐 Add stronger cryptographic password generation.
📁 Export generated passwords to a file.
⚙️ Add customizable password generation presets.
🎓 Learning Outcomes

Through this project, the following Python concepts are practiced:

-Python functions
-Variables and data types
-Conditional statements
-Loops
-Strings
-Lists
-Modules
-User input
-Exception handling
-Randomization
-String manipulation
-Basic command-line application development

👨‍💻 Author

NEHAL JANGID
Integrated M.Tech Computational and Data Science
VIT Bhopal University

📜 License
This project is created for educational and learning purposes.
