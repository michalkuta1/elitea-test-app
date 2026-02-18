# Quiz CLI

An interactive, educational command-line quiz game for learning JavaScript, Node.js, and general programming fundamentals. Built with ES modules and modern Node.js APIs.

## High-Level Description

**Quiz CLI** is a Node.js-powered terminal application that quizzes users on programming knowledge via an interactive command-line interface. Users select a topic, choose how many questions to answer, receive instant feedback, and can review missed questions at the end. This project demonstrates practical use of ES modules, async/await, file I/O, CLI user input, and clean architecture in JavaScript.

## Features

- Multiple quiz categories (JavaScript, Node.js, General programming)
- Randomized question order and user-selected question count
- Instant validation and explanations for each answer
- CLI-based interactive menus and questions
- Color-coded terminal output (success, errors, highlights)
- Results summary and review of incorrectly answered questions
- Replayable for continuous learning

## Project Structure

```
elitea-test-app/
│
├── index.js              # App entry: CLI logic & main app flow
├── package.json          # Project metadata, start/test scripts, engine requirements
│
├── data/
│   └── questions.json    # All quiz questions & explanations (grouped by category)
│
└── src/
    ├── colors.js         # Terminal color utility functions (pure ANSI)
    ├── input.js          # CLI input handling (prompts, selects, confirmation)
    └── quiz.js           # Quiz game logic (Quiz class, scoring, review)
```

## Getting Started

### Requirements

- Node.js 18.0.0 or newer

### Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/michalkuta1/elitea-test-app.git
    cd elitea-test-app
    ```
2. (Optional) Review `package.json` for available scripts and supported engines.

### Running the Quiz

- Start the CLI quiz (from the project root):

    ```sh
    node index.js
    ```

- Or, if you added to `PATH` or set executable:
    ```sh
    ./index.js
    ```

### Usage

- Follow the interactive prompts to:
    - Select a category
    - Choose number of questions
    - Answer each question (type the number of your choice)
    - Review your score and missed questions
    - Play again if desired

### Project Scripts

- Start quiz: `npm start`
- (Optional) Run tests: `npm test` (if implemented)

---

**Happy learning! 🚀**  
*Contributions and suggestions welcome!*
