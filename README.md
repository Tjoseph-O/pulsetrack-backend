# PulseTrack Backend API

Backend API for PulseTrack health monitoring application. Built using Test-Driven Development (TDD) with Node.js, Express, and MongoDB.

## 🚀 Features

- User management
- Activity tracking
- Appointment scheduling
- Built with TDD approach
- Comprehensive test coverage
- RESTful API design

## 📋 Prerequisites

- Node.js (v18 or higher)
- MongoDB (v6 or higher)
- npm or yarn

## 🛠️ Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd pulsetrack-backend
```

2. Install dependencies:
```bash
npm install
```

3. Create environment file:
```bash
cp .env.example .env
```

4. Update `.env` with your configuration

## 🧪 Running Tests
```bash
# Run all tests
npm test

# Run tests in watch mode
npm run test:watch

# Run only unit tests
npm run test:unit

# Run only integration tests
npm run test:integration
```

## 🏃 Running the Application
```bash
# Development mode with auto-reload
npm run dev

# Production mode
npm start
```

## 📁 Project Structure
```
pulsetrack-backend/
├── src/
│   ├── config/         # Configuration files
│   ├── models/         # Mongoose models
│   ├── controllers/    # Route controllers
│   ├── routes/         # API routes
│   ├── middleware/     # Custom middleware
│   └── server.js       # App entry point
├── tests/
│   ├── unit/          # Unit tests
│   ├── integration/   # Integration tests
│   └── setup/         # Test configuration
├── .env.example
├── .gitignore
└── package.json
```

## 🔗 API Endpoints

Documentation coming soon...

## 🧑‍💻 Development Approach

This project follows Test-Driven Development (TDD):

1. Write failing tests (RED)
2. Write minimal code to pass tests (GREEN)
3. Refactor code (REFACTOR)
4. Repeat

## 📝 License

MIT# pulsetrack-backend
