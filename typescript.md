# TypeScript Code Conventions

## Core Principles

1.  **Asynchronous Operations:**

- Avoid blocking synchronous operations when possible.
- Handle asynchronous operations with proper error handling.

2.  **Error Handling:**

- Define specific error types using classes or interfaces.
- Use try/catch blocks or `Promise.catch` for error handling.
- Provide meaningful error messages and context.

3.  **Resource Management:**

- Use try/finally blocks or asynchronous resource management techniques to ensure resources are released.
- Avoid resource leaks.

## Code Organization

1. **Code Colocation:**

- Keep related code close together in the same file or directory.
- Place types, interfaces, and their implementations in proximity.
- Group functionality by feature rather than by type.
- Maintain a balance between file size and logical grouping.

## TypeScript Usage

1.  **Types:**

- Define explicit types for data structures and function parameters.
- Use interfaces and type aliases to define complex types.
- Use generics to create reusable types and functions.
- Leverage TypeScript's type system for better type inference.

## File Structure

1.  **Module Organization:**

- Group related modules together.
- Separate interface definitions from implementations.
- Colocate related types and errors.
- Use a clear directory structure to organize code.

## Testing

1.  **Unit Testing:**

- Use Vitest for unit tests.
- Test both success and failure paths.
- Write clear and concise test cases.

## General Guidelines

1.  **Functional Approach:**

- Prefer immutable data structures.
- Use pure functions where possible.
- Avoid side effects.
- Favor composition over inheritance.

2.  **Documentation:**

- Document public APIs with JSDoc.
- Explain the purpose of complex code.
- Document error handling and expected behavior.

## Naming Conventions

1.  **Files:**

- Use kebab-case for file names (e.g., `user-service.ts`).

2.  **Types and Interfaces:**

- Use PascalCase for type names (e.g., `UserService`).

3.  **Functions and Variables:**

- Use camelCase for function and variable names (e.g., `getUser`, `deleteNote`).
- Use descriptive names.
- Use verbs for function names.

## Dependencies

1.  **Library Selection:**

- Choose well-maintained and widely used libraries.
