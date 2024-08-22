# React Quiz App

Welcome to the React Quiz App, a simple yet powerful quiz application designed to test your knowledge of React concepts. This app leverages the useReducer hook to manage state efficiently, making it a great example of how to build scalable React applications with complex state management.

This project was completed by me as part of the course "The Ultimate React Course 2024: React, Redux & More" created by [Jonas Schmedtmann](https://twitter.com/jonasschmedtman) on the Udemy educational platform.

## Features

- **Dynamic Quiz Loading**: The app starts by loading a set of questions from a mock API, offering you a fresh and engaging quiz experience every time.
- **Multiple Choice Questions**: Each question comes with four options, where you can select your answer. The correct answer is highlighted immediately after your selection.
- **Real-time Progress Tracking**: Keep track of your quiz progress and score as you move through the questions. The progress bar updates in real-time, showing your current score and progress.
- **Immediate Feedback**: After selecting an option, the app provides immediate feedback by marking the selected option as correct or incorrect.
- **Next Question Navigation**: Once an answer is selected, a "Next" button appears, allowing you to move to the next question seamlessly.
- **Timer Functionality**: A built-in timer challenges you to answer all the questions within a set time limit. If the timer runs out, the quiz ends, and your final score is calculated based on the questions answered.
- **State Management with useReducer**: All the app's state, such as the current question, selected answers, score, and timer, is managed using a single useReducer hook, demonstrating a clean and efficient approach to handling complex state in React.

### Deployment

Click this badge to visit the deployed React Quiz on Netlify:
**[![Netlify Status](https://api.netlify.com/api/v1/badges/14635502-241e-4778-ac3a-0e8664b73e60/deploy-status)](https://travel-list-app-kartim.netlify.app)**

## System Requirements:

To run this application locally, ensure you have the following software installed on your system:

- Node.js(version 20.3.0 LTS or higher) **(https://nodejs.org/)**
- Node Package Manager(npm) **(https://www.npmjs.com/)**

### Quality Assurance

Linter Status: The project follows best practices and is linted using ESLint. Ensure your code adheres to the project's linting rules before pushing any changes.

### Linter status:

[![ESLint Status](https://img.shields.io/badge/ESLint-Passing-brightgreen.svg)](https://github.com/karinatimm/Travel-list-react-app.git)
