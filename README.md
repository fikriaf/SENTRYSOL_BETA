# SENTRYSOL_BETA

[![Netlify Status](https://img.shields.io/netlify/12345678-1234-1234-1234-123456789abc)](https://app.netlify.com/sites/your-site-name)
[![Vercel](https://img.shields.io/badge/deployed%20on-vercel-black?logo=vercel)](https://vercel.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/node-%3E=18.0.0-green)](https://nodejs.org/)
[![React](https://img.shields.io/badge/react-18+-blue)](https://react.dev/)

## Overview

**SENTRYSOL_BETA** is a modern web application for blockchain analytics and wallet management, built with React, Vite, TypeScript, and a Python backend. It features real-time data visualization, wallet connection, and advanced analytics for blockchain transactions.

## Features

- Blockchain wallet connection and management
- Real-time transaction flow and fund flow visualization (D3.js)
- Dashboard with analytics and pricing
- Modular frontend (React + Vite + Tailwind CSS)
- Python backend for data processing and API
- Supabase integration
- Netlify/Vercel deployment ready

## Tech Stack

- **Frontend:** React, TypeScript, Vite, Tailwind CSS
- **Backend:** Python (Flask/FastAPI), custom modules
- **Data:** Supabase, custom APIs
- **Deployment:** Netlify, Vercel

## Getting Started

### Prerequisites

- Node.js >= 18.x
- Python >= 3.9
- pnpm (recommended) or npm/yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/fikriaf/SENTRYSOL_BETA.git
cd SENTRYSOL_BETA

# Install frontend dependencies
pnpm install

# (Optional) Set up Python backend
your-python-env\Scripts\activate
pip install -r requirements.txt
```

### Running the App

#### Frontend

```bash
cd client
pnpm dev
```

#### Backend

```bash
python server.py
```

### Build for Production

```bash
pnpm build
```

## Folder Structure

- `client/` — React frontend
- `modules/` — Python backend modules
- `server.py` — Python backend entry point
- `public/` — Static assets
- `scripts/` — Build scripts

## Contributing

Contributions are welcome! Please open issues or pull requests for suggestions and improvements.

## License

This project is licensed under the MIT License.
