# TEST.md

This document outlines the testing strategy for the nOS web-based operating system.

## Unit Tests (Node.js Service)

* Framework: Jest (recommended)
* Location: `src/__tests__`
* Focus: Testing individual modules and functions of the Node.js service.
* Execution: `npm test`

## Integration Tests (Node.js Service and WebSockets)

* Framework: ws, supertest.
* Purpose: Testing communication between the Node.js service and the browser UI via WebSockets.
* Execution: `npm run test:integration`

## End-to-End (E2E) Tests (Browser UI)

* Framework: Cypress or Playwright.
* Purpose: Simulating user interactions with the browser UI and testing end-to-end functionality.
* Execution: `npm run test:e2e`

## Manual Testing

* Purpose: Exploratory testing and usability testing.
* Focus: Testing in different browser environments, performance, and edge cases.
