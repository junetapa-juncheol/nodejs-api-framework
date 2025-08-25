# Node.js API Framework

A lightweight, production-ready API framework built with Node.js and Express.

## Features

- User authentication with JWT
- MongoDB database integration
- Security middleware
- Error handling
- Input validation
- Environment configuration

## Quick Start

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables
4. Run development server: `npm run dev`

## API Endpoints

### Authentication
- POST `/api/auth/register` - User registration
- POST `/api/auth/login` - User login
- GET `/api/auth/profile` - Get user profile

### Health Check
- GET `/health` - API health status

## Environment Variables

Create a `.env` file with:

```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/api-framework
JWT_SECRET=your-secret-key
```

## License

MIT License - Created by Jun Park (jun22sky@nate.com)