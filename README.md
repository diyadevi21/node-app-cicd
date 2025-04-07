# Node.js App with CI/CD

This is a simple Node.js application that demonstrates CI/CD using GitHub Actions.

## Features

- Node.js app with basic structure
- Dockerfile for containerization
- GitHub Actions workflow for CI/CD
- Automatically installs dependencies and runs on push/pull request to main

## How to Use

1. Clone the repo
2. Run npm install
3. Start the app with node index.js

## CI/CD

The GitHub Actions workflow is located at .github/workflows/ci-cd.yml and is triggered on:

- Push to main
- Pull request to main

It runs:
- npm install
- (You can add test and deploy steps next)
