# EduXplore

**An Interactive Web-Based Computer Hardware Learning Guide**

EduXplore is a web application created by Group 28 for MO-IT161 Web Systems and Technology. It is designed to help junior and senior high school students, especially ICT students and beginners, identify and understand basic computer hardware.

The application provides categorized lessons, computer-part references, lesson videos, and short topic quizzes. Students receive immediate feedback and can review their latest quiz scores, status, and attempt count.

## Current Status

The project keeps its original HTML, CSS, and browser JavaScript pages. A small Express.js server now saves the latest score, pass status, and attempt count for each topic quiz in a JSON file on the server.

There are no user accounts or database. Quiz progress is shared by visitors using the same running app, which keeps this backend feature small and suitable for a class project.

## Main Features

- Categorized lessons for internal components, input devices, output devices, and storage devices
- Computer-part pictures, descriptions, functions, and basic specifications
- Live Computer Parts search with a Clear button and result counter
- Lesson videos displayed through a popup window
- Short quizzes for individual hardware topics
- Immediate answer feedback and quiz results
- Quiz status, scores, and attempt tracking saved by the Express server
- Responsive layout for desktop and smaller screens

## Application Pages

| Page | Purpose |
| --- | --- |
| `index.html` | Introduces EduXplore and provides access to its learning features. |
| `lessons.html` | Displays categorized hardware lessons, videos, and topic quizzes. |
| `components.html` | Provides detailed hardware references and the Computer Parts search. |
| `quiz.html` | Displays quiz history, scores, status, and retake counts. |
| `about.html` | Explains the project purpose, target users, features, and group information. |

## Technologies Used

- HTML5 for webpage structure and learning content
- CSS3 for shared styling and responsive layouts
- Browser JavaScript for videos, quizzes, search, and frontend interactions
- Node.js and Express.js for the quiz-results API and website server
- A server-side JSON file for saving quiz progress between browser sessions

## How to Use the Application

1. Download or clone the repository.
2. Install the project packages with `npm install`.
3. Start the website and backend with `npm start`.
4. Open the app at `http://localhost:5000`.
5. Use the navigation menu to open the Lessons, Computer Parts, Quiz, or About page.
6. Take a topic quiz, then open the Quiz page to see the server-saved result.

Quiz results are stored in `.data/quiz-results.json`, which is created after the first quiz is completed and is excluded from Git.

## Project Structure

```text
Web_System_Group-28/
├── server.js
├── package.json
├── package-lock.json
├── index.html
├── lessons.html
├── components.html
├── quiz.html
├── about.html
├── styles.css
├── script.js
├── README.md
└── replit.md
```

## Milestone 1 Documentation

- [Browser-Based Application Development Workflow Worksheet](https://docs.google.com/spreadsheets/d/10Rh_oHCJGaDs-8cfMLEl7meDu0ndk5jpZmbqjAfwmuU/edit?usp=sharing)
- [AI Use Statement](https://docs.google.com/document/d/1rvmMHryl3yYhevG8d83DOrMTR-XaBjohv9LhZdnnBlY/edit?usp=sharing))


## Repository

[GitHub Repository – Web System Group 28](https://github.com/Kenzojae/Web_System_Group-28)

## Group Members

| Member | Main Contribution |
| --- | --- |
| Lawrence Malasa | Home page, shared styling, Computer Parts search, review, and workflow documentation |
| John Carlo Rendon | Quiz and About pages, quiz interactions, and progress tracking |
| Eric Paolo Mempin | Lessons and Computer Parts content and page structure |

Additional work was completed collaboratively through testing, review, scope discussions, documentation, and GitHub updates.

## Current Scope and Future Improvements

Milestone 1 focuses on manageable frontend features that directly support learning. The group removed the proposed 3D models and other advanced features to keep the project realistic for the course timeline.

Possible improvements for later milestones include:

- Reviewing and replacing lesson videos with more reliable educational sources
- Adding more hardware topics and quiz questions
- Adding quiz difficulty levels and lesson completion indicators
- Separating progress by student with accounts if the project needs personalized tracking
- Creating teacher-managed lesson content or a progress dashboard

## AI Use Disclosure

The group used AI tools to support selected development, review, testing, explanation, and documentation tasks. AI-assisted suggestions were reviewed by the members before they were incorporated into the project. The complete description of the group's AI use is provided in the linked AI Use Statement.

## Educational Use

EduXplore was developed for educational purposes as part of MO-IT161 Web Systems and Technology.
