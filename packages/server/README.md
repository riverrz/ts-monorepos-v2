# @seeds/server

This package provides the backend server for the Seeds application, built with Express.js and TypeScript.

## Overview

The server package implements:
- RESTful API endpoints for seed and plant data
- Data loading and parsing from YAML files
- Request logging and error handling
- CORS configuration
- Environment-based configuration

## Key Features

- Express.js server with TypeScript
- Winston logging integration
- YAML data parsing
- CORS support
- Environment variable configuration
- Comprehensive test suite

## API Endpoints

- `GET /api/seeds` - Returns the complete seed packet collection

## Development

This package is part of the Seeds monorepo. See the root README.md for development setup instructions.

### Running the Server

```bash
# Development mode with hot reload
pnpm dev

# Build the server
pnpm build

# Run tests
pnpm test
``` 