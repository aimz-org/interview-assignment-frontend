# Interview Assignment: Python API Service

## Overview
Your task is to build a Python API service that provides search, mutation, and subscription capabilities for a dataset of user information. The service should be built with scalability, maintainability, and performance in mind.

## Dataset
The dataset (`data/mock_data.csv`) contains user information with the following fields:
- id
- first_name
- last_name
- email
- gender
- ip_address

## Requirements

### 1. API Endpoints

#### Search Endpoint
- Implement a search endpoint that allows querying the dataset
- Support filtering by any field or combination of fields
- Implement pagination for large result sets
- Return results in JSON format

#### Change Endpoint
- Implement endpoints to:
  - Add new records
  - Update existing records
  - Delete records
- Validate input data
- Handle errors appropriately

#### Subscribe Endpoint
- Implement a subscription system that allows clients to:
  - Subscribe to changes in specific records
  - Subscribe to search results (when new records matching a search query are added)
- Notify subscribers in real-time when relevant changes occur
- Support one or multiple subscription types (WebSocket, SSE, or similar)

### 2. Technical Requirements
- Use Python 3.x
- Consider scalability and performance

### 3. Bonus Points
- Implement authentication and authorization
- Add rate limiting
- Implement caching
- Add monitoring and logging
- Containerize the application

## Evaluation Criteria
Your solution will be evaluated based on:
1. Code quality and organization
2. Implementation of requirements
3. Error handling and edge cases
4. Performance considerations
5. Documentation
7. Bonus features implementation

## Submission
Please provide:
1. Link to repository with source code
2. README with setup and running instructions
3. API documentation
4. Any additional notes or considerations
