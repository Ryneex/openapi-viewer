# OpenAPI Viewer

A simple web-based OpenAPI specification viewer that uses the Scalar API Reference component to display OpenAPI specifications.

## Features

- Display OpenAPI specifications in a clean, purple-themed interface
- Supports both direct URL input and URL parameter passing
- Uses the official Scalar API Reference component
- Responsive design that works on all devices

## Usage

### Option 1: URL Parameter

You can directly pass the OpenAPI specification URL as a query parameter:

```
https://ryneex.github.io/openapi-viewer/?url=https://example.com/api-docs
```

### Option 2: Manual Input

If no URL parameter is provided, the viewer will prompt you to enter the OpenAPI specification URL.

## Requirements

- Modern web browser with JavaScript enabled
- Internet connection (required for loading the Scalar API Reference component)
