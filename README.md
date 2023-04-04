# Workflow Course Assignment - Noroff

## Setup local development
1. Clone the repository
1. Run `npm install` to install all dependencies
1. Run `npm start` to start the development server 

## Configuration and Workflow

This project is configured to run several quality assurance and deployment tasks on each commit and merge. The following workflows and hooks are currently in place:

- Prettier: This tool automatically formats and lints code to ensure a consistent style throughout the project. It runs on each commit to ensure that all code is clean and easy to read.
- ESLint: This tool checks for syntax errors and other issues in JavaScript code. It runs on each commit to catch any issues before they make it into the codebase.
- Jest: This tool is used for testing. It runs on each commit to ensure that all code is functioning as expected.
- Deployment to pages: This hook is triggered on each merge to the default branch. It automatically deploys the latest version of the code to the project pages website.

## Status Badges

To help keep track of the status of these workflows and hooks, we have included the following badges in this README file:

- Prettier: [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
- ESLint: [![ESLint: Enabled](https://img.shields.io/badge/ESLint-Enabled-blue.svg)](https://eslint.org/)
- Jest: [![Jest: Tested](https://img.shields.io/badge/Jest-Tested-green.svg)](https://jestjs.io/)
- Deployment to pages: [![Deployment: Pages](https://img.shields.io/badge/Deployment-Pages-orange.svg)](https://pages.github.com/)
