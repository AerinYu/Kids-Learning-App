Kids Quiz App

Creators:
Coleman Wimpy 
Davis Weaver
Raquel Yupanqui

Purpose: The purpose of this app is to teach kids some basic concepts through quizes.

This app only displays in portrait mode.

Main Layout:
- main layout of the app starts by showing a menu of 4 buttons
- Each button has a label for the subject that the quiz is about.
- Each button has an onClick method that will start the Activity/Class that corresponds to the quiz.

The math quiz has its own layout with the following elements
- TextView that will display the current math equation
- EditTextView that will allow the user to submit an answer, the editTextView only allows the user to enter signed numbers
- TextView showing the user how many questions they have answered correctly compared to the total number of questions they have answered.

The Science Quiz has the following layout elements
- TextView that displays the current questions
- 4 Buttons that each display a different answer choice
each button has an onClick listener that will determine wether or not that button was the right answer
- TextView showing how many questions the user has answered correctly compared to the total number of questions.

The Reading Quiz layout has the following elements
- TextView showing the current sight-word
- Button for going to the next sight-word

The History Quiz has the same layout as the Science Quiz but with questions about history.

The MathQuiz Class generates two random numbers between -10 and 10, then randomly decides if the equation will be addition, subtraction, or multiplication.
It then has a method that is called by the submit button that determines if the answer submitted matches the actual answer

The Science and History class both have an array of Questions with and Array of corresponding answer options, there is also an array with the correct answer for each question.
Each button has an onClick listener that if clicked will determine if that button had the correct answer.

The Reading Quiz will display a sight-word and when the next Button is clicked it will grab the next word out of an array of words.

Each Quiz is an Activity which will allow you to return to the Main menu by pressing the back button.

Also at the end of each quiz it takes you to a new page that says end of quiz with a button to take you back to the main menu.

Thank you for trying our app. Any FeedBack would be appreciated.
Contact us @ cwimpy55@gmail.com