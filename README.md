# Gas Tracker Dashboard 🔥 A real-time gas tracker dashboard for monitoring Ethereum and other blockchain networks' gas prices, with built-in transaction simulation capabilities.

## Features ✨ - 
**Real-time Gas Price Monitoring**: Live updates of gas prices across different networks - 
**Multi-Chain Support**: Track gas prices across multiple blockchain networks - 
**Interactive Charts**: Visual representation of gas price trends - 
**Transaction Simulation**: Simulate transactions to estimate gas costs - 
**Wallet Integration**: Connect your wallet to get personalized insights - 
**Status Indicators**: Clear visual indicators for network status - 
**Alert System**: Customizable alerts for gas price thresholds

## Technologies Used ⚡ - 
**Frontend Framework**: React 18 with TypeScript - 
**Build Tool**: Vite - 
**State Management**: Zustand - 
**Real-time Updates**: WebSocket - 
**Blockchain Integration**: 
- Ethereum providers 
- Uniswap SDK - 
**Styling**: CSS Modules - 
**Charts**: Interactive data visualization - 
**Development Tools**: 
- ESLint for code quality 
- TypeScript for type safety 
- Multiple tsconfig setups for different build targets

## Prerequisites 📋 Before you begin, ensure you have the following installed: - 
Node.js (v18 or higher) - 
npm (v9 or higher) - 
A modern web browser - 
(Optional) MetaMask or another Web3 wallet

## Installation 🚀 
1. Clone the repository: ```bash git clone [your-repo-url] cd gas-tracker-dashboard``` 
2. Install dependencies: ```bash npm install``` 
3. Create a `.env` file in the root directory with your configuration: ```env VITE_WS_URL=your_websocket_url VITE_API_KEY=your_api_key``` 
4. Start the development server: ```bash npm run dev``` 
The application will be available at `http://localhost:5173`

## Project Structure 📁 
```
gas-tracker-dashboard/
├── src/
│   ├── components/ # Reusable UI components
│   ├── hooks/ # Custom React hooks
│   ├── lib/ # Utility functions and constants
│   ├── pages/ # Page components and API routes
│   ├── stores/ # Zustand state management
│   └── assets/ # Static assets
```

## Available Scripts 📜 
- `npm run dev` - Start development server 
- `npm run build` - Build for production 
- `npm run preview` - Preview production build 
- `npm run lint` - Run ESLint 
- `npm run type-check` - Run TypeScript type checking

## Components 🎯 
### Core Components 
1. **ChainSelector** - 
   Select different blockchain networks - 
   Displays network-specific information 
2. **GasPriceChart** - 
   Interactive chart showing gas price trends - 
   Customizable time ranges 
3. **WalletSimulator** - 
   Simulate transaction costs - 
   Calculate estimated fees 
4. **ChainStatusCards** - 
   Display network status - 
   Show current gas prices 
5. **Alert** - 
   Customizable price alerts - 
   Notification system

## Configuration ⚙️ 
### ESLint Setup 
The project uses a comprehensive ESLint configuration with: 
- TypeScript-aware lint rules 
- React-specific linting 
- Strict type checking 

### TypeScript Configuration 
Multiple TypeScript configurations are used: 
- `tsconfig.json` - Base configuration 
- `tsconfig.app.json` - Application-specific settings 
- `tsconfig.node.json` - Node.js environment settings