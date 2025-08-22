# Next.js + Supabase Todo App Copilot Instructions

## Overview
Full-stack todo application built with Next.js and Supabase, emphasizing modern React patterns and real-time data synchronization.

## Development Principles
- Follow React functional patterns with hooks
- Implement real-time updates using Supabase subscriptions  
- Prioritize accessibility and responsive design
- Use TypeScript for type safety
- Maintain clean separation between client and server logic

## Technical Stack
- Next.js 14+ with App Router
- Supabase for backend (database, auth, real-time)
- TypeScript for type safety
- Tailwind CSS for styling
- React Query/SWR for data fetching

## Coding Standards
### Component Structure
- Use functional components with React hooks
- Implement custom hooks for data fetching and state management
- Separate business logic from UI components

### Database Operations
- Use Supabase client for CRUD operations
- Implement proper error handling for database queries
- Use TypeScript types generated from Supabase schema

### State Management
- Use React Context for global app state
- Implement optimistic updates for better UX
- Handle loading and error states consistently

## Best Practices
### Performance
- Implement proper caching strategies
- Use React.memo for expensive components
- Lazy load components when appropriate

### Security
- Validate all user inputs
- Implement proper authentication checks
- Use Row Level Security (RLS) in Supabase

### User Experience
- Provide immediate feedback for user actions
- Implement proper error handling and user notifications
- Ensure responsive design across all devices

## Common Patterns
- Custom hooks for Supabase operations
- Error boundary components for graceful error handling
- Reusable form components with validation
- Modal components for todo creation/editing

## Quality Assurance
- Unit tests for utility functions
- Integration tests for critical user flows
- Accessibility testing with screen readers
- Performance monitoring and optimization
