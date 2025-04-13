# Devarena

Devarena is a decentralized event and booking platform that integrates both Web2 and Web3 technologies. The platform allows users to list, book, and manage events or properties with blockchain-backed transparency and security. It features a seamless combination of traditional web technologies and smart contract-powered functionality.

## Features

- **Event/Property Listings**: Display and search available events or properties.
- **On-Chain Booking**: Decentralized booking system using blockchain for secure and transparent transactions.
- **Integrated Calendar**: View availability and manage bookings with an on-chain calendar.
- **User Authentication**: Integrated with Clerk for a smooth authentication process.
- **Web2 and Web3 Integration**: Combines traditional web practices with decentralized solutions.

## Tech Stack

- **Frontend**: React.js, Next.js
- **Backend**: Convex (Backend as a Service)
- **Blockchain**: Smart contracts for decentralized booking and transactions
- **Authentication**: Clerk for user authentication
- **Deployment**: Vercel (Frontend), Convex (Backend)

## Setup and Installation

### Prerequisites

- Node.js (>= 14.x)
- npm or yarn
- Git
- Clerk account for authentication
- Convex account for backend services

### Clone the Repository

```bash
git clone https://github.com/Bhumika-00/devarena.git
cd devarena
```

### Install Dependencies

Install dependencies for both frontend and backend:

#### Frontend

```bash
cd frontend
npm install
```

#### Backend (Convex)

```bash
cd convex
npm install
```

### Configure Clerk and Convex

1. **Clerk**: Sign up for a Clerk account and configure the authentication in the frontend. Add necessary environment variables (API keys) for Clerk.
2. **Convex**: Set up your Convex project for handling the backend logic and smart contracts. Make sure to configure your Convex instance with the correct API keys and project settings.

### Running Locally

To run the application locally, follow these steps:

#### Start the Frontend

```bash
cd frontend
npm run dev
```

The frontend will be available at `http://localhost:3000`.

#### Start the Backend (Convex)

```bash
cd convex
npx convex dev
```

### Deployment

- **Frontend**: Deploy the frontend to Vercel by linking your GitHub repository to your Vercel project.
- **Backend**: Deploy the backend to Convex, ensuring that the required environment variables and configuration are set up.

Vercel will automatically trigger deployments when you push changes to the main branch.

## Contributing

We welcome contributions to Devarena! Here's how you can help:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push your changes (`git push origin feature/YourFeature`).
5. Create a pull request for review.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Clerk** for seamless user authentication.
- **Convex** for simplifying the backend and smart contract integration.
- The open-source community for providing valuable tools and resources.
