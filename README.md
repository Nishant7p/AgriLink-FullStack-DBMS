# AgriLink Harvest Hub

AgriLink Harvest Hub is a full-stack web application designed to connect farmers and buyers directly, eliminating middlemen and streamlining the agricultural supply chain. The platform enables farmers to list products, manage inventory, and analyze sales, while buyers can browse, order, and track agricultural products in real time.

## Project Description

This project was built as a demonstration of a modern, scalable, and user-friendly agricultural marketplace. It features:
- Direct farmer-to-buyer connections
- Product listing and browsing
- Order placement and management
- Inventory tracking for farmers
- Analytics dashboard for insights
- Responsive design for desktop and mobile

## Technologies & Tools Used

### Frontend
- **React**: Component-based UI library for building interactive interfaces
- **Vite**: Fast build tool and development server
- **TypeScript**: Type-safe JavaScript for scalable code
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **React Router**: Client-side routing
- **@tanstack/react-query**: Data fetching and caching
- **Shadcn/UI**: Modern UI components

### Backend (for demo/integration)
- **Node.js & Express**: REST API server (if using custom backend)
- **Supabase**: (For some versions) Backend-as-a-Service for authentication, database, and real-time APIs
- **Sequelize & MySQL**: (For some versions) ORM and relational database
- **JWT**: Authentication tokens
- **CORS, dotenv**: Security and environment management

### Other Tools
- **ESLint & Prettier**: Code linting and formatting
- **Postman**: API testing
- **Git**: Version control

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- (Optional) MySQL or Supabase account for backend

### Installation
1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd agrilink-harvest-hub-18-main/agrilink-harvest-hub-18-main
   ```
2. **Install frontend dependencies:**
   ```bash
   npm install
   ```
3. **Start the frontend:**
   ```bash
   npm run dev
   ```
   The app will be available at [http://localhost:5173](http://localhost:5173) or the port shown in your terminal.

## Features
- **Farmer Dashboard:** Manage products, inventory, and view analytics
- **Buyer Dashboard:** Browse products, place orders, and track purchases
- **Authentication:** Secure login and registration
- **Responsive UI:** Works on all devices
- **Real-time Data:** Instant updates with Supabase or REST API
