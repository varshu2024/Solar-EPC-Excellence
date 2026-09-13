# N Solutions - Solar EPC Excellence Platform

Comprehensive Solar EPC management platform featuring client-facing web application and backend API services.

## Repository Architecture

```
├── backend/                  # Express.js & MongoDB REST API
│   ├── src/                  # Controllers, Models, Routes, Services, Config
│   ├── package.json
│   ├── test.http
│   └── README.md
│
└── frontend/                 # Helios Solar OS & Client Portal
    ├── index.html            # Main SPA entrypoint
    ├── css/                  # Styling & themes
    ├── js/                   # 3D visualization, calculators, telemetry
    └── package.json
```

## Getting Started

### Backend Setup
```bash
cd backend
npm install
npm run dev
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```
