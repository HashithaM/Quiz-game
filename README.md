# Quiz-game
This is a simple quiz game with api question data and GUI interface
This Python script is a part of a quiz application. Let me explain the different components and what they do:

Imports:

from question_model import Question: Imports the Question class from the question_model module. This class likely represents a single question in the quiz.
from data import question_data: Imports question_data, which presumably contains a list of dictionaries, each representing a question along with its correct answer.
from quiz_brain import QuizBrain: Imports the QuizBrain class, which seems to handle the logic of the quiz, such as keeping track of the questions, user answers, and scores.
from ui import QuizInterface: Imports the QuizInterface class, which is probably responsible for the user interface of the quiz.
Building Question Bank:

A question_bank list is initialized to store instances of the Question class. It iterates through the question_data list, extracts the question text and correct answer for each question, creates a new Question object, and appends it to the question_bank.
Creating QuizBrain Object:

A QuizBrain object named quiz is created with the question_bank as its parameter. This initializes the quiz with the questions from the question_bank.
Creating QuizInterface Object:

A QuizInterface object named quiz_ui is created with the quiz object as its parameter. This likely starts the user interface for the quiz.
Quiz Execution (commented out):

There is a commented-out while loop that appears to be the main execution loop of the quiz. It's likely been commented out for testing purposes.
Inside the loop, quiz.next_question() is called repeatedly until there are no more questions left in the quiz.
Print Final Score:

After the loop (or commented out loop), a message is printed indicating that the quiz has been completed, along with the final score.
Overall, this script sets up a quiz application, initializes the quiz with questions, creates the user interface, and then prints out the final score once the quiz is completed. The main execution loop has been commented out, likely for testing purposes.






