--------Practice Question Generator--------
--------
Overview
--------
Practice Question Generator is a Python-based tool that helps students revise quickly by generating random questions from different subjects. It supports MCQs, fill-in-the-blanks, short answers, and long answers.
Each subject has its own custom module, making the project clean, organized, and easy to expand.

Features
--------
1. Random question selection
2. Supports:
   - MCQ
   - Fill in the blanks
   - Short answer
   - Long answer
3. Four custom user-made modules for questions
4. CLI interface is beginner friendly
5. Good to look at as it does not use many external liberaries keeping the code clean
6. Includes a simple automated test script

Technologies Used
--------
Python 3.13.0
1. Built-in Modules used
 - random — used to randomly select questions
2. Custom User-Made Modules used (Subject Question Files) - These Custom modules help to reduce code length , edit easily to add more questions and make user experience better :
 - EnglishQuestions.py
 - ChemistryQuestions.py
 - PhysicsQuestions.py
 - MathsQuestions.py (and TestMathsModule.py for testing)

3)Development Tools used
 - Git & GitHub for version control
 - Visual Studio Code for coding & debugging

Simple Installation Guide (Windows PC)
--------
1. Install Python
 - Download Python 3.x:
 - https://www.python.org/downloads/
 - Make sure to check Add Python to PATH during installation.

2. Download the Project
 - Download ZIP
 - Go to the repo page
 - Click Code → Download ZIP
 - Extract the ZIP
 - Open the extracted folder

3. Run the Program
 - Install VS Code
 - https://code.visualstudio.com/
 - Enable:
     - Add “Open with Code” to context menu
 - Open the Project
 - VS Code → File → Open Folder → select VITyarthi-Project
3. Select Python Interpreter
 - Ctrl + Shift + P → Python: Select Interpreter → choose Python 3.13
4. Run the Program
 - Open PracticeQuestionGenerator.py → click Run ▶
 - Or run in the terminal:
     - PracticeQuestionGenerator.py

Testing Instructions
-
- Automated Test Script
  - Go to test folder
  - Access the test.py
  - Run the test script
  - Expected example output :
     - Q: Derivative of x² is:
     - Options: ['x', '2x', 'x²']
     - Correct option number: 2
     - -----Here you go! ^-^-----

Future Improvements
-
 - GUI version
 - Score system
 - Difficulty levels
 - Import questions from JSON / CSV
 - More subjects
 - Access for Teachers to upload questions directly
 - Custom Question ability
 - Keep log of incorrect questions for later practice
 - Timer based system

  



