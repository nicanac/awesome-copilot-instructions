# SvelteKit TypeScript Guide Copilot Instructions

## Key Principles
- Use SvelteKit for modern full-stack Svelte applications
- Implement TypeScript for type safety and better developer experience
- Leverage Supabase for authentication and real-time database features
- Use Drizzle ORM for type-safe database operations
- Apply Tailwind CSS and Shadcn components for consistent styling

## SvelteKit Best Practices
- Use server-side rendering (SSR) by default
- Implement static site generation (SSG) for performance where appropriate
- Use SvelteKit's load functions for efficient data fetching
- Leverage SvelteKit's form actions for server-side form handling
- Follow SvelteKit's file-based routing conventions

## TypeScript Guidelines
- Use strict TypeScript configuration
- Define types for all props, stores, and API responses
- Leverage TypeScript utility types for better type inference
- Use proper type annotations for Svelte components
- Implement type-safe database schemas with Drizzle

## Project Structure
- Organize routes in `src/routes/` following SvelteKit conventions
- Place reusable components in `src/lib/components/`
- Store database schemas in `src/lib/schema/`
- Keep utilities and helpers in `src/lib/utils/`
- Use proper TypeScript path mapping in `tsconfig.json`

## Supabase Integration
- Use Supabase client with proper TypeScript types
- Implement authentication with Supabase Auth
- Use real-time subscriptions for live data
- Follow Supabase security best practices (RLS policies)
- Handle errors gracefully in database operations

## Performance Optimization
- Use SvelteKit's prerendering for static content
- Implement proper caching strategies
- Optimize images and assets
- Use code splitting with dynamic imports
- Minimize client-side JavaScript

## UI and Styling
- Use Tailwind CSS for utility-first styling
- Implement Shadcn components for consistent UI
- Follow responsive design principles
- Support dark/light theme switching
- Ensure accessibility compliance (WCAG guidelines)

## Development Guidelines
- Write concise, functional code with minimal side effects
- Use Svelte stores for global state management
- Implement proper error handling and validation
- Follow naming conventions (camelCase for variables, PascalCase for components)
- Use meaningful component and function names

## SEO and Internationalization
- Use SvelteKit's `<svelte:head>` for meta tags
- Implement Paraglide.js for internationalization
- Ensure proper URL structure and routing
- Use structured data for better SEO
- Optimize Core Web Vitals

