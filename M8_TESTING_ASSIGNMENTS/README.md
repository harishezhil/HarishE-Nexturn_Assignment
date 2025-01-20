
# Testing Exercises

This project contains unit tests for various JavaScript functions. It covers string utilities, error handling, async functions, mocking, DOM manipulation, and more.

## 1. Fundamentals: String Utilities

**Functions:**
- `capitalize(word)`
- `reverseString(str)`

**Tests:**
- Validate `capitalize` for empty strings and single-character words.
- Test `reverseString` for palindromes and empty strings.

## 2. Error Handling: Array Index

**Function:**
- `getElement(arr, index)`

**Tests:**
- Validate valid indices.
- Throw error for negative or out-of-range indices.

## 3. Async Functions: Delayed Greeting

**Function:**
- `delayedGreeting(name, delay)`

**Tests:**
- Validate resolved message.
- Use mock timers to test delay.

## 4. Mocking: Notification Service

**Function:**
- `sendNotification(notificationService, message)`

**Tests:**
- Mock `send` method to test success and failure cases.

## 5. Spying: DOM Manipulation

**Function:**
- `toggleVisibility(element)`

**Tests:**
- Spy on style changes and test visibility toggling.

## 6. Bonus Challenge: Integrate All Concepts

**Function:**
- `fetchAndDisplayUser(apiService, userId, element)`

**Tests:**
- Mock API service for success and failure scenarios.
- Spy on DOM element updates.
