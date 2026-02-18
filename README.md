# quiz-cli

A small interactive command-line quiz game for learning JavaScript concepts.

## Features
- Terminal-based quiz with multiple categories
- Choose number of questions per run
- Keeps score and shows results

## Prerequisites
- Node.js >= 18

## Installation
1. git clone https://github.com/michalkuta1/elitea-test-app.git
2. cd elitea-test-app
3. npm install

## Usage
Run the app with:

npm start

or

node index.js

The CLI will prompt you to select a category and number of questions, then present questions one by one. Answer by typing the option letter and pressing Enter.

## Example flow
1. Select category (e.g., "JavaScript Basics")
2. Choose number of questions
3. Answer each question (e.g., 'a', 'b', 'c')
4. View final score and summary

## Project structure
- index.js — application entry point / CLI orchestration
- src/ — core modules (quiz logic, input helpers, color helpers)
- data/questions.json — question bank to edit or extend
- package.json — project metadata and scripts

## Extending questions
Add or edit entries in data/questions.json to change or add new questions and categories.

## Development
No tests are included. Run `npm start` to launch the app locally.

## License
MIT

## Notes
This README was added to address Issue #1 (Create README.md).
