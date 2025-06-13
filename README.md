# Playwright Automation Framework

## Setup Instructions

1. Install Node.js (v18 or higher)
2. Clone the repository
3. Install dependencies:
   \`\`\`
   npm ci
   \`\`\`
4. Install Playwright browsers:
   \`\`\`
   npx playwright install --with-deps
   \`\`\`

## Running Tests

To run the tests:
\`\`\`
npx playwright test
\`\`\`

## Generating Allure Reports

To generate Allure reports:
\`\`\`
npx playwright show-report
\`\`\`

## Project Structure

- \`/tests\`: Test cases
- \`/pages\`: Page Objects
- \`/fixtures\`: Custom test fixtures
- \`/utils\`: API clients, helpers, types

## Environment Variables

Create a \`.env\` file based on \`.env.example\` if any environment variables are required.
