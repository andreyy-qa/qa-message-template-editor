# QA Testing – Message Template Editor

## Project Overview
Manual QA testing of a SPA application built with React and TypeScript.
Testing was performed after local environment setup using Node.js.

## Environment
- Node.js (local setup)
- npm install / npm run start
- Chrome DevTools
- VS Code

## Scope of Testing
- Template editing functionality
- Variable insertion and processing
- IF-THEN-ELSE conditional logic
- Nested condition validation
- Message generator logic
- Serialization and deserialization
- localStorage integration

## Testing Techniques Used
- Equivalence Partitioning
- Boundary Value Analysis
- Positive and Negative Testing
- Exploratory Testing
- Decision Logic Testing

## Key Testing Focus
- Business logic validation
- Detection of side effects
- Validation of nested conditional execution
- Handling of invalid or unknown variables
- Data persistence and state management

## Result
Testing revealed logical defects in conditional execution and variable handling that affected message generation consistency.

## Test
- [Test Strategy](./Test_Documentation/TestStrategy.md)
- [Test Cases](./Test_Documentation/TestCases.md)
- [Bug Reports](./Test_Documentation/BugReports.md)
- [Assignment Description](./Requirements/Assignment_Description.md)
- [Technical Specification](./Requirements/Technical_Specification.md)
  
## Documentation
- [Original Technical Specification](./Documentation/Original_Technical_Specification.docx)
- [Message template editor](./Documentation/message-template-editor.pdf)
