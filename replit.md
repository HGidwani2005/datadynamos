# Overview

This is an AI-powered internship recommendation system designed to help students in India find perfect internship matches. The application combines user profiling with intelligent matching to connect students with relevant opportunities across various companies and locations. It features a clean, accessible design with multilingual support and follows government portal-inspired UI patterns for broad usability.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React with TypeScript using Vite as the build tool
- **Routing**: Wouter for client-side routing with a simple Switch/Route pattern
- **State Management**: TanStack Query for server state management and caching
- **UI Library**: Shadcn/ui components built on Radix UI primitives
- **Styling**: Tailwind CSS with custom design system based on Indian tricolor theme
- **Form Handling**: React Hook Form with Zod validation for type-safe form management

## Backend Architecture
- **Server**: Express.js with TypeScript
- **API Design**: RESTful API with routes for user profiles and internships
- **Data Layer**: In-memory storage with interface-based design for future database integration
- **Validation**: Zod schemas shared between client and server for consistent validation
- **Error Handling**: Centralized error handling with proper HTTP status codes

## Design System
- **Theme**: Indian tricolor-inspired color palette (saffron, white, green) with dark mode support
- **Typography**: Inter font with accessibility-focused sizing (18px+ body text)
- **Layout**: Card-based design with generous spacing using Tailwind's spacing scale
- **Accessibility**: High contrast ratios (4.5:1 minimum), large touch targets (44px+), clear focus states
- **Responsive**: Mobile-first approach with breakpoint-based responsive design

## Data Architecture
- **Database Schema**: PostgreSQL schema defined with Drizzle ORM
- **Tables**: User profiles and internships with array fields for skills and interests
- **Type Safety**: Full type safety from database to frontend using Drizzle's type inference
- **Validation**: Zod schemas derived from database schema for consistent validation

## Authentication & Authorization
- Currently implements basic session handling setup with connect-pg-simple for future session management
- No authentication implemented yet but infrastructure prepared for user sessions

# External Dependencies

## Database
- **Neon Database**: Serverless PostgreSQL database (@neondatabase/serverless)
- **Drizzle ORM**: Type-safe database toolkit with PostgreSQL dialect
- **Migration System**: Drizzle Kit for database schema migrations

## UI Libraries
- **Radix UI**: Comprehensive set of accessible React components for dropdowns, dialogs, forms, etc.
- **Lucide React**: Icon library for consistent iconography
- **Tailwind CSS**: Utility-first CSS framework with custom configuration

## Development Tools
- **Vite**: Fast build tool with React plugin and development server
- **TypeScript**: Full TypeScript support across client, server, and shared code
- **ESBuild**: Fast bundler for production builds
- **PostCSS**: CSS processing with Tailwind and Autoprefixer

## Form & Validation
- **React Hook Form**: Performant forms with validation
- **Zod**: TypeScript-first schema validation
- **@hookform/resolvers**: Zod resolver for React Hook Form integration

## Additional Libraries
- **date-fns**: Date manipulation library
- **clsx & class-variance-authority**: Utility for conditional CSS classes
- **cmdk**: Command palette component
- **embla-carousel-react**: Carousel component for UI interactions