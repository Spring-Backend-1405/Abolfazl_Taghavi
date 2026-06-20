# Course Selling Platform

Backend for an online programming course selling platform, built with Express.js and Prisma.

## Tech Stack

- **Node.js** + **Express.js** — backend framework
- **Prisma** — ORM
- **PostgreSQL** — database

## Prerequisites

- Node.js (v18 or higher)
- PostgreSQL

## Getting Started

1. Clone the repository:

```bash
git clone <repository-url>
cd <project-folder>
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file and set the environment variables:

```env
PORT=3000
DATABASE_URL="postgresql://USER:PASSWORD@localhost:5432/DBNAME?schema=public"
```

4. Run database migrations:

```bash
npx prisma migrate dev
```

5. Start the project:

```bash
npm run dev
```

## Project Structure

```
src/
  ├── app.js          # Express app configuration
  ├── server.js        # Server entry point
  ├── routes/           # Route definitions
  ├── controllers/      # Route controllers
  └── middlewares/      # Middlewares
prisma/
  └── schema.prisma     # Database models
```

## Features (in progress)

- [ ] User registration & authentication
- [ ] Course management
- [ ] Course purchase & payment

## License

ISC
