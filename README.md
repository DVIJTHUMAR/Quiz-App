# Quiz Application Frontend

This is a React-based frontend for a Quiz Application where users can select a quiz, answer questions, and view their scores at the end.

## **Features**

- **Quiz List Page**: Displays a list of available quizzes with basic information (title, description).
- **Quiz Page**: Shows questions with multiple-choice answers. Users can select an answer and move to the next question.
- **Score Summary Page**: Displays the user's score and correct answers after completing the quiz.
- **State Management**: Uses React hooks (`useState`, `useEffect`) to manage quiz state (questions, answers, scores).
- **Styling**: Uses Bootstrap (or Tailwind CSS) for a clean, responsive design.

## **Tech Stack**

- **React**: Frontend library for building the user interface.
- **React Router DOM**: For navigation between different pages of the application.
- **Bootstrap / Tailwind CSS**: For styling the application.

## **Project Structure**

# Quiz Application Backend

This is the backend server for the Quiz Application. It handles quiz data, manages user responses, calculates scores, and provides API endpoints for the frontend.

## **Features**

- **Quiz Management**: Create, read, update, and delete quizzes.
- **Question Management**: Manage questions and multiple-choice answers for each quiz.
- **User Response Handling**: Collect user answers and calculate scores.
- **API Integration**: RESTful API endpoints for communication with the frontend.

## **Tech Stack**

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for building RESTful APIs.
- **MongoDB**: NoSQL database for storing quizzes and user data (can be replaced with other databases if needed).
- **Mongoose**: ODM library for MongoDB to simplify database interactions.
- **Cors**: Middleware to enable cross-origin requests from the frontend.

## **Project Structure**

