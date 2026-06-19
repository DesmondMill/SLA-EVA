# SLA Pulse - Backend (SLA-EVA)

SLA-EVA is the core backend engine for SLA Pulse, responsible for tracking and enforcing Service Level Agreements (SLAs) across multiple platforms.

## Tech Stack
- **Node.js**
- **TypeScript**
- **Express**
- **TypeORM**
- **PostgreSQL**

## Getting Started

### Prerequisites
- Node.js (v18+)
- npm

### Installation
```bash
npm install
```

### Running the App
```bash
# Development mode
npm run dev

# Build for production
npm run build

# Start production server
npm run start
```

## Project Structure
- `src/config`: Configuration files
- `src/controllers`: Request handlers
- `src/models`: Database entities (TypeORM)
- `src/routes`: API route definitions
- `src/services`: Business logic
- `tests`: Test files
