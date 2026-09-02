# GymPass-style API

A study API for gym discovery and check-ins, built to apply SOLID principles in a realistic backend domain.

## Project goal

Implement authentication, nearby gym search and check-in rules while keeping use cases testable and persistence replaceable.

## Features

- User registration and JWT authentication
- Nearby and name-based gym search
- Distance- and time-based check-in rules
- Role-based gym registration and check-in validation
- Unit and end-to-end tests

## Technologies

- **TypeScript**
- **Node.js**
- **Fastify**
- **Prisma**
- **PostgreSQL**
- **Vitest**
- **JWT**
- **Zod**

## What I learned

- Expressing business rules as isolated use cases
- Applying repository abstractions and dependency inversion
- Testing domain behavior with in-memory repositories
- Testing HTTP behavior against a real database environment

## Running locally

```bash
npm install
docker compose up -d
npx prisma migrate dev
npm run start:dev
```

## About this repository

This repository documents a learning project and the technical decisions explored while building it. It is not presented as a production-ready system.
