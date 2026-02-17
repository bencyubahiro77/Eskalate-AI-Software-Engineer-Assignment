# AI Experts Assignment (JS/TS)

This assignment evaluates your ability to:

- set up a small JavaScript/TypeScript project to run reliably (locally + in Docker),
- pin dependencies for reproducible installs,
- write focused tests to reproduce a bug,
- implement a minimal, reviewable fix.

## Setup and Running Tests

### Locally

To run the tests locally, follow these steps:

1.  **Install dependencies**:
    ```bash
    npm install
    ```
2.  **Run tests**:
    ```bash
    npm test
    ```

### Docker

To build and run the tests using Docker:

1.  **Build the image**:
    ```bash
    docker build -t ai-assignment-test .
    ```
2.  **Run the container**:
    ```bash
    docker run --rm ai-assignment-test
    ```

## Bug Explanation
(See [EXPLANATION.md](file:///d:/eskalate/ai-software-engineer-assignment-ts/EXPLANATION.md) for details)

