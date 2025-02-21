# Mangement_App 

## Overview

This project consists of a **backend** built with Node.js, Express, and Prisma, and a **frontend** using Next.js with Redux and AWS Amplify. The application provides a scalable architecture for full-stack development.

## Technologies Used

### Backend:

- **Node.js** - JavaScript runtime
- **Express** - Web framework
- **Prisma** - ORM for database interactions
- **TypeScript** - Strongly typed JavaScript
- **Dotenv** - Environment variable management
- **Morgan & Helmet** - Logging and security enhancements

### Frontend:

- **Next.js** - React framework for SSR and static site generation
- **Redux Toolkit** - State management
- **AWS Amplify** - Authentication and backend services
- **Material UI** - UI components
- **Tailwind CSS** - Utility-first styling

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (Latest LTS version recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [PostgreSQL](https://www.postgresql.org/) (or your preferred database)

### Installation

#### Clone the Repository

```sh
git clone <repository-url>
cd <project-folder>
```

#### Backend Setup

1. Navigate to the backend folder:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root of the backend folder.
   - Add the required variables (e.g., `DATABASE_URL` for Prisma, `PORT` for the server).
4. Run database migrations:
   ```sh
   npx prisma migrate dev
   ```
5. Start the backend server:
   ```sh
   npm run dev
   ```

#### Frontend Setup

1. Navigate to the frontend folder:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables:
   - Create a `.env.local` file in the root of the frontend folder.
   - Add necessary API URLs and authentication keys.
4. Start the development server:
   ```sh
   npm run dev
   ```

---

## Scripts

### Backend Scripts

| Command         | Description                                 |
| --------------- | ------------------------------------------- |
| `npm run dev`   | Runs the backend server in development mode |
| `npm run build` | Builds the project for production           |
| `npm run start` | Starts the backend in production mode       |
| `npm run seed`  | Runs the Prisma seeding script              |

### Frontend Scripts

| Command         | Description                           |
| --------------- | ------------------------------------- |
| `npm run dev`   | Starts the Next.js development server |
| `npm run build` | Builds the project for production     |
| `npm run start` | Starts the Next.js server             |
| `npm run lint`  | Runs ESLint to check for code issues  |

---

## Deployment

### Backend Deployment

1. Build the backend project:
   ```sh
   npm run build
   ```
2. Deploy to your cloud provider (e.g., AWS, Vercel, or DigitalOcean).

### Frontend Deployment

1. Build the frontend project:
   ```sh
   npm run build
   ```
2. Deploy to a hosting service like Vercel, Netlify, or AWS Amplify.

---

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Follow the conventional commit message style.

---



