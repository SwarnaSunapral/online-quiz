# online-quiz

This is an interactive quiz application built using HTML, CSS, and JavaScript. The app allows users to test their knowledge through a series of multiple-choice questions. It features a timer, dynamic scoring, and an easy-to-use interface.

## Features  

- **Start Quiz Button**: Launch the quiz easily with a single click.  
- **Information Box**: Displays the rules before the quiz begins.  
- **Dynamic Questions**: Questions and options are dynamically loaded from a JavaScript array.  
- **Timer**: Each question is timed to keep the game challenging.  
- **Result Calculation**: Shows the user's score at the end of the quiz.  
- **Restart and Quit Options**: Allows users to replay the quiz or exit.  

## How to Use  

1. Clone the repository or download the source code.  
   ```bash
   git clone https://github.com/Swarna-Sunapral/online-quiz
   ```
2. Open the `index.html` file in a web browser to start the quiz.  

## Technologies Used  

- **HTML**: Structure of the app.  
- **CSS**: Styling and layout.  
- **JavaScript**: Dynamic behavior, including question logic, timers, and scoring.  

## How It Works  

1. **Starting the Quiz**: Clicking the **Start Quiz** button displays the rules.  
2. **Playing the Quiz**: Users select answers within the time limit for each question.  
3. **Scoring**: Correct answers are highlighted, and the score is calculated at the end.  
4. **Replay or Quit**: Users can choose to replay or quit after viewing their score.  

## Customization  

### Adding Questions  
1. Open the `js/questions.js` file.  
2. Add your questions in the following format:  
   ```javascript
   let questions = [
       {
           numb: 6,
           question: "Your Question Here",
           answer: "Correct Answer Here",
           options: [
               "Option 1",
               "Option 2",
               "Option 3",
               "Option 4"
           ]
       },
   ];
   ```

### Styling  
Modify `style.css` to change the look and feel of the app.  

## Screenshots  

1. **Start Screen**  
   ![Start Screen](screenshot1.png)  

2. **Quiz Screen**  
   ![Quiz Screen](screenshot2.png)  

3. **Result Screen**  
   ![Result Screen](screenshot3.png)  



