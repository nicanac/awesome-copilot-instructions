# TypeScript Next.js Copilot Instructions

## Key Principles
- Use TypeScript for strict type safety and enhanced developer experience
- Follow Next.js App Router patterns for modern React applications
- Implement server and client components appropriately
- Use Drizzle ORM with TypeScript for type-safe database operations
- Style with Daisy UI and Tailwind CSS for responsive design

## Project Structure
- Use Next.js 14+ App Router directory structure
- Organize components in `app/components/`
- Place database schemas in `lib/schema.ts`
- Store utilities in `lib/utils.ts`
- Use `bun` as the package manager for improved performance

## Development Guidelines
- Plan step-by-step with detailed pseudocode before coding
- Write secure, functional, and efficient TypeScript code
- Use functional and declarative programming patterns
- Follow descriptive variable naming conventions
- Implement modular code structure for maintainability

## TypeScript Best Practices
- Enable strict mode in `tsconfig.json`
- Use proper type definitions for all functions and variables
- Leverage TypeScript's utility types (`Pick`, `Omit`, `Partial`, etc.)
- Create custom types for API responses and data structures

## Next.js App Router Guidelines
- Use server components by default; mark client components explicitly
- Implement proper data fetching with `fetch` and caching
- Optimize images with Next.js `Image` component
- Follow Next.js documentation for routing and rendering patterns

## Styling and UI
- Use Daisy UI components for consistent design system
- Apply Tailwind CSS utilities for custom styling
- Ensure responsive design across all screen sizes
- Implement dark/light theme support when applicable

## Database and ORM
- Define schemas with Drizzle ORM for type safety
- Use migrations for database structure changes
- Implement proper error handling for database operations
- Follow database normalization best practices

## Performance Optimization
- Implement server-side rendering where appropriate
- Use dynamic imports for code splitting
- Optimize bundle size with tree shaking
- Implement proper caching strategies

