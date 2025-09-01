# Simple Node.js/Express Service

This is a simple Node.js/Express service with two endpoints:

- **GET /products**: Returns a hardcoded list of products (id, name, price).
- **POST /cart**: Accepts a productId and quantity, and returns the total price.

## Setup

1. Install dependencies:
   ```sh
   npm install
   ```
2. Start the server:
   ```sh
   npm start
   ```
3. The server runs at http://localhost:3000

## API Endpoints

### GET /products
- **Response:**
  ```json
  [
    { "id": 1, "name": "Eco Toothbrush", "price": 99 },
    { "id": 2, "name": "Reusable Bottle", "price": 299 },
    { "id": 3, "name": "Bamboo Straw", "price": 49 }
  ]
  ```

### POST /cart
- **Request Body:**
  ```json
  { "productId": 1, "quantity": 2 }
  ```
- **Response:**
  ```json
  { "total": 198 }
  ```

## Push to GitHub
1. Initialize git:
   ```sh
   git init
   ```
2. Add files:
   ```sh
   git add .
   ```
3. Commit:
   ```sh
   git commit -m "Initial commit"
   ```
4. Create a new repository on GitHub and follow their instructions to push your code.
