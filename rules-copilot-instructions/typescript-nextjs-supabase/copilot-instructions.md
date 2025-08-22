# TypeScript + Next.js + Supabase Copilot Instructions

## Overview
Modern full-stack development combining TypeScript's type safety, Next.js's full-stack capabilities, and Supabase's backend-as-a-service for rapid application development.

## Development Principles
- Embrace functional and declarative programming patterns
- Use TypeScript for comprehensive type safety
- Implement server-first architecture with Next.js App Router
- Prioritize performance optimization and SEO
- Follow responsive, mobile-first design principles

## Technical Stack
- TypeScript for type safety
- Next.js 14+ with App Router
- Supabase for backend services (database, auth, storage)
- Tailwind CSS with Shadcn UI components
- Radix UI for accessible component primitives
- Vercel AI SDK for AI-powered features

## Coding Standards
### TypeScript Best Practices
- Use strict TypeScript configuration
- Prefer interfaces over types for object shapes
- Implement proper error handling with Result types
- Use type guards for runtime validation

### Next.js Architecture
- Leverage Server Components by default
- Use Client Components only when necessary
- Implement proper data fetching with async/await
- Follow App Router conventions for file organization

### Component Design
- Create modular, reusable components
- Implement proper prop validation with TypeScript
- Use Radix UI primitives for accessibility
- Follow Shadcn UI patterns for consistent styling

## Performance Optimization
### Rendering Strategy
- Use Server Components for static content
- Implement streaming for better user experience
- Cache data with proper revalidation strategies
- Optimize images with Next.js Image component

### Bundle Optimization
- Implement dynamic imports for code splitting
- Use next/bundle-analyzer to monitor bundle size
- Optimize third-party scripts loading
- Implement proper tree-shaking

## Database Integration
### Supabase Best Practices
- Use TypeScript types generated from Supabase schema
- Implement Row Level Security (RLS) policies
- Use Supabase client with proper error handling
- Implement real-time subscriptions where appropriate

### Data Fetching
- Use Server Actions for mutations
- Implement proper caching with Next.js cache API
- Handle loading and error states consistently
- Use optimistic updates for better UX

## AI Integration
### Vercel AI SDK
- Implement streaming responses for chat interfaces
- Use proper token management for AI calls
- Handle rate limiting and errors gracefully
- Implement user feedback mechanisms

## Quality Assurance
- Unit testing with Jest and Testing Library
- E2E testing with Playwright
- Type checking in development and CI
- Performance monitoring with Web Vitals
- SEO optimization with Next.js metadata API

## Security Considerations
- Implement proper authentication flows
- Validate all user inputs server-side
- Use environment variables for sensitive data
- Follow OWASP security guidelines

