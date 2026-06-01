# Architecture

## Request Flow

User
  ↓
HTTP API
  ↓
Sandbox Manager
  ↓
Language Runtime
  ↓
Execution Result

## Components

### HTTP API
Receives execution requests.

### Sandbox Manager
Creates isolated execution environments.

### Language Runtime
Compiles and executes code.

### Result Handler
Returns output and errors.
