The Password Complexity Checker is an application that evaluates a password's security level based on its length, and use of uppercase/lowercase letters, numbers, and special characters. It categorizes password strength into Very Weak, Weak, Good, or Strong and provides suggestions for improvement.
It is built using Python and Tkinter, making it a simple yet effective tool for personal and professional use.

🛠 Technologies Used
1️⃣ Python
• The core programming language is used to develop the logic behind password assessment.
• Uses Regular Expressions (re module) to check for different character types in the password.
2️⃣ Tkinter (Python's GUI Library)
• Used for creating a user-friendly graphical interface.
• Provides labels, buttons, and entry fields to interact with the user.
3️⃣ Regular Expressions (Regex)
• Helps validate passwords by checking the presence of lowercase letters, uppercase letters, numbers, and special characters.

🚀 Features of the Password Complexity Checker
1️⃣ Graphical User Interface (GUI)
• The tool has a simple and intuitive interface using Tkinter.
• Users can enter a password, click a button, and instantly get feedback.
2️⃣ Password Strength Evaluation
Evaluate passwords based on:
✅ Length
✅ Uppercase letters
✅ Lowercase letters
✅ Numbers
✅ Special characters
3️⃣ Strength Categorization
The tool assigns a strength level:
• Very Weak (score < 40)
• Weak (score between 40-59)
• Good (score between 60-79)
• Strong (score ≥ 80)
4️⃣ Detailed Feedback for Improvement
If a password is weak, the tool provides suggestions such as:
"Include uppercase letters."
"Add special characters like @, #, !, $."
"Increase password length to at least 8 characters."
5️⃣ Hidden Password Input
• The password entry field hides characters using show="*" to protect user input.
6️⃣ Responsive Design
• The GUI automatically adjusts to window resizing, making it user-friendly.
