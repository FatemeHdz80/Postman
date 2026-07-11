# GitHub API Testing with Postman & Newman

## Overview

This project is an API testing project for GitHub REST API using Postman and Newman.

The goal of this project is to validate GitHub API endpoints by creating automated API tests, covering positive and negative scenarios.

## Tools

- Postman
- Newman
- GitHub REST API

## Test Scenarios

### Users

- Get User
- Get User Repositories
- Get Non Existing User
- Get Repositories of Invalid User

### Repositories

- Create Repository
- Get Repository
- Update Repository
- Create Duplicate Repository
- Delete Repository

## Test Coverage

The collection includes tests for:

- HTTP status codes
- Response body validation
- Response headers
- Data types validation
- Environment variables
- Positive testing
- Negative testing
- Response time validation

## Environment Variables

The project uses Postman Environment variables:

- mainUrl
- username
- token
- repositoryName

Before running the collection, set your own GitHub token.

## Run with Newman

Install Newman:

```bash
npm install -g newman

Run Collection :
newman run GitHub API Testing.postman_collection.json -e GitHub.postman_environment.json
```
