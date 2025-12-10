# PhaseZero Catalog Service

A Spring Boot REST API for managing product catalog data.

## Tech Stack
- Java 17+
- Spring Boot
- Spring Data JPA
- H2 In-Memory Database
- Maven

## Features
- Add new products
- Fetch all products
- Input validation
- Global exception handling

## API Endpoints

### Add Product
POST /products

Request Body:
```json
{
  "partNumber": "P001",
  "partName": "walker",
  "category": "instrument",
  "price": 1500,
  "stock": 5
}
