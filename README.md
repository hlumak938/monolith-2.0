# Monolith 2.0

A modern monolithic application architecture built with Fastify, Next.js, Redis, and RabbitMQ.

## Features

- **Fastify Backend**: High-performance API server
- **Next.js Frontend**: React-based UI with server-side rendering
- **Redis**: Session management and caching
- **RabbitMQ**: Message queue for background processing
- **Docker Support**: Easy local development

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/yourusername/monolith-2.0.git
cd monolith-2.0
```

2. Install dependencies
```bash
npm run setup
```

3. Set up environment variables
```bash
cp .env.example .env
# Edit the .env file with your configuration
```

4. Start the Docker services
```bash
docker-compose up -d
```
