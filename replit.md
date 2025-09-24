# Overview

Pump.fun Alert is a meme coin price monitoring application built for Solana ecosystem traders. The app allows users to set custom price alerts for meme coins with audio notifications and real-time monitoring. It features a modern React frontend with a Node.js/Express backend, designed specifically for cryptocurrency traders who need to monitor volatile meme coin markets on the pump.fun platform.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React 18 with TypeScript using Vite as the build tool
- **UI Library**: Shadcn/ui components with Radix UI primitives for accessibility
- **Styling**: Tailwind CSS with custom design system optimized for crypto trading interfaces
- **State Management**: TanStack Query for server state management and caching
- **Routing**: Wouter for lightweight client-side routing
- **Form Handling**: React Hook Form with Zod validation for type-safe form schemas

## Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules
- **API Design**: RESTful endpoints for token information retrieval
- **Data Fetching**: Integration with Solana blockchain APIs (Solana Tracker API)
- **Error Handling**: Centralized error middleware with structured error responses

## Database Layer
- **ORM**: Drizzle ORM with PostgreSQL dialect
- **Database**: Configured for Neon Database (PostgreSQL-compatible)
- **Schema Management**: Type-safe database schemas with Zod integration
- **Storage Abstraction**: Interface-based storage layer supporting both memory and database implementations

## Design System
- **Theme**: Dark mode optimized for crypto trading with light mode support
- **Typography**: Inter for UI text, JetBrains Mono for addresses and numerical data
- **Color Palette**: Golden yellow for alerts/notifications, green/red for price changes
- **Component Library**: Comprehensive UI components following Fluent Design principles

## Audio System
- **Notification Sounds**: Featured alert presets with customizable volume controls
- **Playback Options**: Support for different repeat modes (once, five-times, repeat-until-cancelled)
- **Sound Management**: Audio player components with play/stop controls and volume adjustment

## Data Models
- **Token Information**: Contract address, metadata, market cap, price tracking, and age calculation
- **Price Alerts**: User-defined alerts with target prices, sound preferences, and repeat configurations
- **Settings**: Extensible app configuration for future customization features

## Build and Development
- **Development**: Hot module replacement with Vite dev server
- **Production**: Optimized builds with code splitting and asset optimization
- **Type Safety**: Comprehensive TypeScript coverage across frontend, backend, and shared schemas
- **Path Mapping**: Absolute imports with @ aliases for clean code organization

# External Dependencies

## Blockchain APIs
- **Solana Tracker API**: Primary data source for token information and price data
- **Fallback APIs**: Architecture supports multiple API providers for reliability

## Database Services
- **Neon Database**: PostgreSQL-compatible serverless database for production
- **Connection Pooling**: Configured through connection strings with SSL support

## UI and Styling
- **Google Fonts**: Inter and JetBrains Mono for typography
- **Radix UI**: Comprehensive primitive components for accessibility
- **Tailwind CSS**: Utility-first styling with custom design tokens

## Development Tools
- **Vite**: Build tool with React plugin and runtime error overlay
- **Replit Integration**: Cartographer plugin for development environment
- **ESBuild**: Fast bundling for production builds

## Audio Resources
- **Web Audio API**: Browser-native audio playback capabilities
- **Base64 Audio**: Embedded sound files for notification alerts