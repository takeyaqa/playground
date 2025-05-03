# Playground

A simple static HTML playground for testing web features and interactions.

## Overview

This repository serves as a testing ground for various HTML, CSS, and JavaScript features. Each HTML file is designed to test specific web functionality in isolation, making it easier to understand and debug web behaviors.

## Usage

To use this playground:

1. Clone the repository
2. You can either:
   - Open any HTML file directly in your browser, or
   - Launch a local server to serve the files (recommended for testing certain features)

### Launching a Local Server

You can use Python's built-in HTTP server to serve these static files:

```bash
# Default port 8000
python -m http.server

# Custom port (example: 8080)
python -m http.server 8080
```

After starting the server, open your browser and navigate to `http://localhost:8000` (or the custom port you specified, e.g., `http://localhost:8080`).

## Purpose

This playground is useful for:

- Testing specific HTML/CSS/JavaScript features in isolation
- Debugging web interactions
- Creating minimal test cases for web behavior
- Learning web development concepts with simple examples
