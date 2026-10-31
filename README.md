# EPAM IT Marathon 2026 - Homework #6

## Group Pre-Order - Owner View

Implementation of group pre-order management for the reservation owner in Green & Tasty.

## Features

- View all participants and their pre-orders
- Display individual dishes and subtotals
- Calculate the consolidated order total
- Track submission statuses and refresh data
- Confirm and submit the consolidated pre-order
- Exclude unsubmitted selections
- View submitted orders after page reload
- Prevent duplicate submissions

## Technologies

- Frontend: Angular, TypeScript, SCSS
- Backend: C#, .NET 10
- AWS Lambda, API Gateway, DynamoDB, Cognito

## Run Frontend

cd frontend/restaurant-frontend-app
npm install
npm start

Local address: http://localhost:4200
Requires a configured backend API and authentication.

## Testing

Frontend: npm run test:hw
Backend: dotnet test

- Frontend: 61/61 tests passed
- Backend: 158/158 tests passed
- AWS submission and page reload verified

## Project Structure

- frontend/restaurant-frontend-app
- backend/restaurant-backend-app

AWS credentials and deployment artifacts are excluded.
