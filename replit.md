# EduXplore project notes

## Run the app

- Install dependencies: `npm install`
- Start the Express server and website: `npm start`
- Open the app at `http://localhost:5000`

The server hosts the existing HTML pages and provides the quiz-results API. It saves the latest score, pass status, and attempt count for each topic to `.data/quiz-results.json`. That file is created when a quiz is completed and is not committed to the repository.

This is a simple class-project backend: it does not use user accounts or a database, so results are shared by visitors using the same running app.
