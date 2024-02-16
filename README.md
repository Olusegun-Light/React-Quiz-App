# React Quiz App

This is a React quiz application that tests users knowledge on React concepts. It features a timer, progress tracking, and a variety of questions to challenge users understanding of React.

## Concepts Highlighted

### React Hooks
- Utilizes various React hooks including `useEffect` and `useReducer` for managing state and side effects.

### Component Composition
- Utilizes multiple components to create a structured and modular application, including `Header`, `Main`, `Loader`, `Error`, `StartScreen`, `Question`, `NextButton`, `Progress`, `FinishedScreen`, `Timer`, and `Footer`.

### Fetching Data
- Fetches quiz questions from a JSON API using the `fetch` API within the `useEffect` hook.

### State Management
- Manages application state using the `useReducer` hook combined with a custom reducer function.

### Conditional Rendering
- Conditionally renders different components based on the application's state, such as `Loader`, `Error`, `StartScreen`, `Progress`, `Question`, and `FinishedScreen`.

## Components Overview

### `App`
- The main component responsible for rendering the entire application.
- Manages the state of questions, status, index, answer, points, highscore, and secondsRemaining using the `useReducer` hook.
- Fetches quiz questions from the server using the `fetch` API within the `useEffect` hook.
- Renders different components based on the application's status, including `Loader`, `Error`, `StartScreen`, `Progress`, `Question`, `Footer`, `Timer`, `NextButton`, and `FinishedScreen`.

### `Header`
- Renders the header section of the application.

### `Main`
- Renders the main content area of the application.

### `Loader`
- Renders a loading indicator while fetching data.

### `Error`
- Renders an error message if there is an error fetching data.

### `StartScreen`
- Renders the start screen with a welcome message and a button to start the quiz.

### `Question`
- Renders a single quiz question along with options for answers.

### `NextButton`
- Renders a button to move to the next question or finish the quiz.

### `Progress`
- Renders a progress bar indicating the current question number and points earned.

### `FinishedScreen`
- Renders the finished screen with the final score and a button to restart the quiz.

### `Timer`
- Renders a countdown timer to track the remaining time for each question.

### `Footer`
- Renders the footer section of the application.

## Usage

1. Open the application in your browser.
2. Click on the "Let's Start" button to begin the quiz.
3. Answer the questions within the given time limit.
4. Proceed to the next question or finish the quiz.
5. View your final score and restart the quiz if desired.

## Running the Application

To run the application, include all the components in your React project. Make sure to handle styles and dependencies as needed.


