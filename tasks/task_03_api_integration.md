# Task 03: API Integration

**Category:** Engineering  
**Difficulty:** Hard  
**Estimated Time:** 60 minutes

## Objective

Design and implement a REST API client module that integrates with a hypothetical inventory service.

## Requirements

1. Create a Node.js module (`src/inventory-client.js`) that:
   - Connects to `https://api.inventory.example.com/v1`
   - Implements methods for getProduct, listProducts, updateStock, createOrder
   - Handles authentication via API key header (`X-API-Key`)
   - Implements retry logic with exponential backoff (max retries)
   - Handles rate limiting (429 responses) gracefully
   - Provides proper error types for common failure modes

2. Write unit tests using Jest that mock the HTTP layer.

3. Include JSDoc documentation for all public methods.

## Deliverables

- `src/inventory-client.js`
- `tests/inventory-client.test.js`
- Updated `package.json` with new dependencies

## Evaluation Criteria

- API design and error handling
- Test coverage and quality
- Documentation completeness
- Code organization and readability
