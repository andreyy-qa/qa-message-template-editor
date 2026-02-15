# Technical Specification – Message Template Editor

## Objective
Develop a message template editor with preview functionality.

## Functional Requirements

### 1. Variable Handling
- The editor must receive an array of variable names.
- Variables must be inserted in the format {variable}.
- Unknown variables must be treated as plain text.

### 2. IF-THEN-ELSE Logic
- The editor must support conditional blocks.
- Nested IF-THEN-ELSE structures must be supported.
- Only one branch (THEN or ELSE) should execute.

### 3. Preview Widget
- Generated message must update dynamically.
- All variables must be visible and editable.
- Missing values must be treated as empty strings.

### 4. Data Persistence
- Template must be serialized to string.
- Template must be saved in localStorage.
- No side effects are allowed during message generation.
