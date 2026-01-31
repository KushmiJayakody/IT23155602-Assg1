# IT23155602-Assg1
# Singlish to Sinhala Transliteration Testing

## Student Details
- **Name:** Jayakody J.A.K.K.
- **Registration Number:** IT23155602
- **Batch:** BSc (Hons) in Information Technology - Year 3 WE 1.1

## Project Overview
This project focuses on automated functional and UI testing for a Singlish-to-Sinhala transliteration system (https://www.swifttranslator.com/). The testing is performed using **Playwright** to ensure accuracy, robustness, and usability of the application.

## Prerequisites
Before running the tests, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (Latest LTS version recommended)
- [Visual Studio Code](https://code.visualstudio.com/)

## Installation Guide
1. **Clone the repository:**
   ```bash
   git clone https://github.com/KushmiJayakody/IT23155602-Assg1.git

2 Navigate to the project directory:cd IT23155602

3 Install necessary dependencies:npm install

4 Install Playwright Browsers:npx playwright install

5 Running the Tests
  Run all tests (Chromium, Firefox, Webkit):npx playwright test
  Run tests in headed mode (to see the browser):npx playwright test --headed

6 Run a specific test file:npx playwright test tests/positivetest.spec.js
                           npx playwright test tests/negativetest.spec.js
                           npx playwright test tests/uitestspec.js

7 After running the tests, a detailed HTML report is generated:npx playwright show-report