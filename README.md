# Property Matching System

A sophisticated real estate property matching system that connects customers with suitable properties based on their preferences. The system uses intelligent matching algorithms to provide personalized property recommendations.

## Features

- Property listing management for different regions of Riyadh
- Customer preference tracking and management
- Intelligent property matching based on:
  - Location preferences
  - Price range
  - Property type
  - Number of bedrooms
  - Area requirements
- Caching system for improved performance
- Multilingual support (Arabic-English) for district names

## Project Structure

```
├── data/                  # Data storage directory
│   └── Customers.csv     # Customer information and preferences
├── public/               # Static files for frontend
├── utils/               # Utility functions
├── districts.js         # District mapping and translations
├── server.js           # Main application server
├── package.json        # Project dependencies
└── README.md          # Project documentation
```

## Prerequisites

- Node.js >= 14.0.0
- npm or yarn package manager

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Install dependencies:
```bash
npm install
```

3. Start the server:
```bash
npm start
```

For development with auto-reload:
```bash
npm run dev
```

## API Endpoints

The server runs on port 3000 by default and provides various endpoints for property matching and customer management.

## Data Structure

### Property Listings
Properties are stored in JSON format for different regions:
- East of Riyadh
- West of Riyadh
- North of Riyadh
- South of Riyadh

### Customer Data
Customer information and preferences are stored in CSV format with fields for:
- Phone Number
- Interest

## Caching

The system implements a caching mechanism with a 5-minute duration to optimize performance and reduce database load.

## License

MIT 
