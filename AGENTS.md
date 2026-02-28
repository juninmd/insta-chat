```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the consistent, maintainable, and robust development of the AGENTS repository. Adherence to these principles is critical for long-term success.

## 1. DRY (Don't Repeat Yourself)

*   All code, including functions, classes, and modules, should have a single, clear purpose.
*   Avoid duplication of logic. When a feature needs to be reused, create a reusable component.
*   Refactor existing code to eliminate redundancy.

## 2. KISS (Keep It Simple, Stupid)

*   Strive for simplicity in design and implementation.
*   Prioritize readability and understandability.
*   Avoid overly complex solutions that sacrifice clarity.
*   Keep functions and classes short and focused.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class should have one, and only one, reason to change.
*   **Open/Closed Principle:** Systems should be extensible without modifying their existing code.
*   **Liskov Substitution Principle:** Subtypes must be substitutable for their base types without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients shouldn't be forced to satisfy contracts they don't need.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Implement only the functionality required for the current task.
*   Avoid adding features or code that isn’t currently needed.
*   Defer future requirements until they are explicitly requested.

## 5. Testing & Mocking

*   **All development must be productive.** Do not use mocks or fake implementations.
*   **Mocks ONLY for testing.** Mocking should be used to verify expected behavior and boundary conditions during testing.
*   Implement unit tests for every function and class.
*   Test coverage should be at least 80%.

## 6. File Length Constraint

*   Each file should be no more than 180 lines of code.

## 7. Code Style & Conventions

*   Follow a consistent code style (e.g., using a linter and formatter).
*   Use meaningful variable and function names.
*   Document code with clear and concise comments where necessary.
*   Adhere to established naming conventions.
*   Use whitespace appropriately for readability.

## 8. Data Structures & Algorithms

*   Select appropriate data structures for efficient operations.
*   Employ efficient algorithms for common tasks.
*   Consider performance implications when designing data structures.

## 9. API Design

*   Define clear and consistent API endpoints.
*   Provide appropriate error handling.
*   Document API usage.

## 10. Configuration & Dependencies

*   Use a modular configuration approach.
*   Clearly define dependencies.
*   Avoid globally declared variables.

## 11.  Specific Considerations (Agents.py)

*   The `Agents.py` file will contain logic for agent communication, data processing, and event handling.
*   Ensure all agent-related code is organized and follows best practices for modularity.
*   Prioritize clear, concise, and well-documented code.

## 12.  Maintainability Checklist

*   Easy to understand and maintain.
*   Easy to modify and extend.
*   Well-tested.

## 13.  Code Review Process

*   Mandatory code reviews for all changes.
*   Review should focus on code quality, adherence to principles, and potential issues.

## 14.  Version Control

*   Use a version control system (e.g., Git) for all code.
*   Follow established branching and merging practices.
```