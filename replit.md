# NextGen AI Skills - DevOps Training Platform

## Overview

NextGen AI Skills is a comprehensive DevOps and cloud training platform that provides professional courses in Azure DevOps, AWS DevOps, and AI-powered infrastructure automation. The platform features a modern web application with contact management, course enrollment, and community engagement functionality.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript and Vite for fast development and building
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: TanStack React Query for server state management and caching
- **UI Framework**: Radix UI components with shadcn/ui design system
- **Styling**: Tailwind CSS with custom design tokens and CSS variables for theming
- **Forms**: React Hook Form with Zod validation for type-safe form handling

### Backend Architecture
- **Runtime**: Node.js with TypeScript and ES modules
- **Framework**: Express.js for REST API endpoints
- **Development**: TSX for TypeScript execution in development
- **Build System**: ESBuild for production bundling with external package handling
- **API Structure**: RESTful endpoints for contacts and enrollments with proper error handling

### Database & ORM
- **Database**: PostgreSQL with Neon serverless driver for cloud deployment
- **ORM**: Drizzle ORM for type-safe database operations and migrations
- **Schema**: Strongly typed schema definitions shared between client and server
- **Validation**: Drizzle-Zod integration for runtime validation of database operations

### Authentication & Session Management
- **Session Storage**: PostgreSQL-based session storage using connect-pg-simple
- **User Management**: Built-in user schema with username/password authentication
- **Security**: Prepared for secure session handling and user authentication flows

### Development & Deployment
- **Development Server**: Vite middleware integration for hot module replacement
- **Static Assets**: Vite handles client-side bundling and static file serving
- **Environment**: Separate development and production configurations
- **Error Handling**: Runtime error overlay for development debugging

### Data Models
- **Users**: Authentication and user management
- **Contacts**: Lead capture with personal information and interests
- **Enrollments**: Course enrollment with experience level and goals tracking
- **Schema Sharing**: Common TypeScript types between frontend and backend

## External Dependencies

### Database Services
- **Neon Database**: Serverless PostgreSQL hosting with connection pooling
- **Environment Variables**: DATABASE_URL configuration for database connectivity

### UI Component Libraries
- **Radix UI**: Accessible component primitives for complex UI interactions
- **Lucide React**: Icon library for consistent iconography
- **Embla Carousel**: Carousel component for course showcases

### Development Tools
- **Replit Integration**: Vite plugin for Replit-specific development features
- **PostCSS**: CSS processing with Tailwind CSS and Autoprefixer
- **TypeScript**: Full type safety across the entire application stack

### Utility Libraries
- **Class Variance Authority**: Type-safe CSS class composition
- **clsx & twMerge**: Conditional CSS class handling
- **date-fns**: Date manipulation and formatting
- **Zod**: Runtime type validation and schema validation

### Form & Validation
- **Hookform Resolvers**: Integration between React Hook Form and validation libraries
- **React Hook Form**: Performant form handling with minimal re-renders
- **Zod Validation**: Type-safe form validation with error handling