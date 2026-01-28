# CI/CD Tools and Practices Final Project Template

**Project name:** ci-cd-final-project

## CI/CD Tools and Practices Final Project - JavaScript/Node.js Version

This repository contains a Node.js/Express.js version of the counter service for the Final Project of the Coursera course **CI/CD Tools and Practices**.

## Features

- RESTful API for managing counters
- In-memory storage
- Comprehensive error handling
- Security middleware (Helmet, CORS)
- Logging middleware
- Full test coverage with Jest
- Docker support
- Health check endpoint

## API Endpoints

- `GET /` - Service information
- `GET /health` - Health check
- `GET /counters` - List all counters
- `POST /counters/:name` - Create a new counter
- `GET /counters/:name` - Read a specific counter
- `PUT /counters/:name` - Increment a counter
- `DELETE /counters/:name` - Delete a counter

## Setup

1. **Install dependencies:**
```bash
   npm install
```

**Then commit and push:**
```bash
git add -A
git commit -m "Added project name to README"
git push
```

That's it! The instructions just want you to add those two lines at the top showing it's the CI/CD final project template with the project name clearly stated.

Ready to update it?