# Quiz App

A dynamic quiz application built with React that tests users' knowledge of defined topic via questions.js file. This interactive quiz features a timer, immediate feedback, and a comprehensive summary of results.

## Features

- Interactive quiz interface
- Timer for each question
- Progress tracking
- Answer validation with visual feedback
- Final score summary with statistics
- Responsive design
- Animated transitions

## Technology Stack

- React
- Vite
- CSS3

## Project Structure

```
Quiz-App/
├── public/
│   └── quiz-logo.png
├── src/
│   ├── assets/
│   │   ├── quiz-complete.png
│   │   └── quiz-logo.png
│   ├── components/
│   │   ├── Answers.jsx
│   │   ├── Header.jsx
│   │   ├── Question.jsx
│   │   ├── QuestionTimer.jsx
│   │   ├── Quiz.jsx
│   │   └── Summary.jsx
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   └── questions.js
└── package.json
```

## Features in Detail

- **Timer**: Each question has a configurable countdown timer that adds excitement and challenge to the quiz experience
- **Answer Validation**: Provides immediate visual feedback when an answer is selected, showing correct/incorrect status
- **Progress Tracking**: Clear visual indication of current question number and overall progress through the quiz
- **Score Summary**: Comprehensive end-of-quiz summary showing:
  - Total correct answers
  - Time taken
  - Performance statistics
- **Responsive Design**: Fully responsive interface that works seamlessly across desktop, tablet, and mobile devices
- **Animations**: Smooth transitions and animations enhance the user experience

## Customization

The quiz questions can be easily customized by modifying the `questions.js` file in the `src` directory. Each question should follow this format:

```javascript
{
  text: "Your question text",
  answers: [
    "Answer option 1",
    "Answer option 2",
    "Answer option 3",
    "Answer option 4"
  ],
  correctAnswer: 0  // Index of the correct answer
}
```
