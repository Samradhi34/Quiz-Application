# Quiz-Application

# Overview
This is a simple, interactive Quiz Application built using Java Swing and AWT. It features a user-friendly interface with multiple-choice questions, dynamic timers, lifelines, and score tracking. The application has separate screens for Login, Rules, Quiz, and Score. It offers an engaging and smooth user experience by utilizing Java's event handling and graphics capabilities.

# Features
1. Login Screen: Users enter their name to start the quiz.
2. Rules Screen: Displays quiz instructions and how to play.
3. Quiz Screen:
 - 10 multiple-choice questions.
 - A 15-second timer for each question.
 - Lifeline to eliminate two incorrect options.
 - Navigation through questions with Next and Submit buttons.
4. Score Screen: Displays the final score and provides an option to exit or restart.

# Technologies Used
Java Swing: Used for building the GUI, including buttons, labels, and radio buttons.
AWT: Utilized for handling custom graphics (e.g., timer countdown).
Git: Version control for code management.

# Folder Structure
QuizApp
│
├── .idea               # IntelliJ IDEA project files (configuration, metadata)
├── out                 # Compiled .class files (output directory)
├── src                 # Source directory for Java files and assets
│   ├── icons           # Folder containing image assets for UI
│   ├── quiz\app        # Main package containing Java files
│   │   ├── Login.java  # Handles user login and name input
│   │   ├── Quiz.java   # Core quiz functionality: questions, timers, navigation
│   │   ├── Score.java  # Displays final score and restart options
│   │   ├── Rules.java  # Displays quiz rules and starts the quiz
│   ├── .gitignore      # Specifies files to exclude from version control
│   └── QuizApp.iml     # IntelliJ IDEA module file

# Setup Instructions
Clone the repository to your local machine:
git clone https://github.com/yourusername/QuizApp.git
Open the project in IntelliJ IDEA or any preferred Java IDE.

Run the Login.java file to start the quiz application.

# How to Play
1. On the Login Screen, enter your name and click "Next" to proceed.
2. Review the Rules Screen and click "Start" to begin the quiz.
3. Answer each question by selecting one of the four options. You have 15 seconds per question.
4. If needed, use the Lifeline button to remove two incorrect options.
5. After completing the quiz, the Score Screen will display your total score.
6. You can either Exit the app or go back to the Login Screen.
Contributing
