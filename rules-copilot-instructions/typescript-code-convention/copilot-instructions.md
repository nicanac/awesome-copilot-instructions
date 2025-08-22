# TypeScript Code Convention Copilot Instructions

## Key Principles
- Write concise, modular TypeScript code with functional programming patterns
- Avoid classes; prefer functions and composition
- Use consistent naming conventions and code formatting
- Implement proper error handling and validation
- Follow mobile-first responsive design approach

## TypeScript Guidelines
- Use strict TypeScript configuration
- Define explicit types for all function parameters and return values
- Leverage TypeScript utility types for better type safety
- Use `const` assertions and `as const` for immutable data
- Avoid `any` type; use proper type definitions

## Naming Conventions
- Use camelCase for variables and functions
- Use PascalCase for components and types
- Use UPPER_SNAKE_CASE for constants
- Use kebab-case for file names
- Use descriptive, meaningful names

## Error Handling and Validation
- Use structured error handling with try-catch blocks
- Implement input validation at API boundaries
- Use Zod or similar libraries for runtime type checking
- Log errors appropriately with contextual information
- Provide user-friendly error messages

## UI and Styling Guidelines
- Use Shadcn UI and Radix UI for consistent components
- Apply Tailwind CSS for utility-first styling
- Use NativeWind for React Native projects
- Follow mobile-first responsive design principles
- Ensure accessibility compliance (WCAG guidelines)

## API and Authentication
- Use tRPC for type-safe API calls
- Implement authentication with Clerk or similar services
- Secure API endpoints with proper validation
- Use proper HTTP status codes and response formats

## Performance Optimization
- Implement dynamic loading for code splitting
- Optimize images with Next.js Image component
- Use proper caching strategies
- Minimize bundle size through tree shaking
- Implement lazy loading for large datasets

## Next.js Specific Guidelines
- Use App Router for modern Next.js applications
- Implement server-side rendering appropriately
- Follow Next.js data fetching best practices
- Use server components by default, client components when necessary

## Expo Specific Guidelines
- Utilize Expo SDK features for native functionality
- Follow Expo best practices for app configuration
- Implement proper navigation with Expo Router
- Optimize for both iOS and Android platforms

