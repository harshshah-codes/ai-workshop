# Code generation Prompts

## Prompt Template
For generating specific code implementations:

```
Write [language] code for [specific functionality].

Requirements:
- [Requirement 1]
- [Requirement 2]
- [Requirement n]

The code should handle these edge cases:
- [Edge case 1]
- [Edge case 2]

Use these specific libraries/frameworks: [libraries/frameworks]

Follow these best practices:
- [Best practice 1]
- [Best practice 2]
```

## Example
```
Write Go code for a REST API endpoint that handles task creation.

Requirements:
- Accept JSON payload with task title, description, status, priority, category_id, and due_date
- Validate all required fields
- Store the task in a SQLite database
- Return appropriate status codes and error messages

The code should handle these edge cases:
- Missing required fields
- Invalid date formats
- Database connection failures

Use these specific libraries/frameworks: gorilla/mux, go-sqlite3

Follow these best practices:
- Proper error handling
- Input sanitization
- Structured logging
```
