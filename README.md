# Business Logic

### 1. List of products

- Get list of products from go-store-service
  
### 2. Make an order

- Select product from list of products
- Create order from go-store-order
  - Implement gRPC service to create an order
  - Gen grpc-gateway code for HTTP POST request

### 3. Update a order request

- Only current customers could update their order
- Actions:
  - Cancel order
  - Feedback order

### 4. Get an order by id

- Implement gRPC service to get an order
- Gen grpc-gateway code for HTTP GET request

### 5. Get list of orders

- Implement gPRC service to get list of orders
- Gen grpc-gateway code for HTTP GET request

### 6. Filter order by [id | status]

- Implement gRPC service to search or filter orders
- Gen grpc-gateway code for HTTP GET request
