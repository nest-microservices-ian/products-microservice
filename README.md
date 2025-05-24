# Products Microservice

This microservice is part of the e-commerce platform and is responsible for managing products. It provides APIs to create, read, update, and delete products.

## Development Setup

1. Clone the repository:
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` based on `.env.example`:
   ```bash
   cp .env.example .env
   ```
4. Execute prisma migrations:
   ```bash
   npx prisma migrate dev
   ```
5. Start the development server:
   ```bash
   npm run start:dev
   ```
