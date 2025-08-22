# SvelteKit + TypeScript Development Guide

## Overview
Modern full-stack web development using SvelteKit's universal app framework with TypeScript for type safety, Supabase for backend services, and optimized performance patterns.

## Development Principles
- Embrace SvelteKit's file-based routing and universal rendering
- Use TypeScript for comprehensive type safety
- Implement functional and declarative programming patterns
- Optimize for performance with minimal JavaScript
- Prioritize accessibility and SEO best practices

## Technical Stack
- **Framework**: SvelteKit with Svelte 5
- **Language**: TypeScript for type safety
- **Backend**: Supabase for authentication, database, and real-time features
- **Styling**: Tailwind CSS with Shadcn/UI components
- **State Management**: Svelte stores and Drizzle ORM
- **Internationalization**: Paraglide.js for multi-language support

## Coding Standards
### File Organization
- Use SvelteKit's file-based routing conventions
- Organize components in `src/lib/components/`
- Place utilities in `src/lib/utils/`
- Store types in `src/lib/types/`
- Keep server-only code in `+page.server.ts` files

### TypeScript Guidelines
- Use strict TypeScript configuration
- Define interfaces for all data structures
- Implement proper type guards for runtime validation
- Use generic types for reusable components
- Prefer type-only imports when possible

### Component Architecture
- Use single-file components (.svelte)
- Implement proper prop validation with TypeScript
- Use Svelte 5's new reactivity model ($state, $derived, $effect)
- Separate business logic into composable functions
- Follow consistent naming conventions

## Performance Optimization
### Server-Side Rendering (SSR)
- Use SSR by default for better SEO and initial load times
- Implement proper data loading with load functions
- Cache expensive operations appropriately
- Use streaming for large data sets

### Static Site Generation (SSG)
- Pre-render static pages with `adapter-static`
- Use `prerender = true` for content pages
- Implement proper build-time data fetching
- Optimize for CDN distribution

### Client-Side Optimization
- Minimize JavaScript bundle size
- Use code splitting and lazy loading
- Implement proper image optimization
- Use Svelte's built-in optimization features

## Supabase Integration
### Database Operations
- Use Drizzle ORM for type-safe database queries
- Implement proper error handling for database operations
- Use Supabase's real-time subscriptions judiciously
- Follow Row Level Security (RLS) best practices

### Authentication
- Implement secure authentication flows
- Use PKCE for OAuth implementations
- Handle authentication state properly
- Implement proper session management

### Security Best Practices
- Validate all user inputs server-side
- Use environment variables for sensitive data
- Implement proper CORS policies
- Follow OWASP security guidelines

## UI/UX Guidelines
### Styling with Tailwind CSS
- Use utility-first CSS approach
- Implement consistent design system
- Follow responsive design principles
- Use CSS custom properties for theming

### Component Design
- Build reusable Shadcn/UI components
- Ensure accessibility compliance (WCAG)
- Implement proper focus management
- Use semantic HTML elements

### State Management
- Use Svelte stores for global state
- Implement reactive patterns with $derived
- Handle loading and error states consistently
- Use optimistic updates for better UX

## SEO and Meta Management
- Use `svelte:head` for dynamic meta tags
- Implement proper structured data
- Generate sitemaps automatically
- Optimize for Core Web Vitals

## Form Handling
- Use SvelteKit's form actions
- Implement proper client and server validation
- Handle form submissions progressively
- Provide clear error and success feedback

## Internationalization
- Use Paraglide.js for multi-language support
- Implement proper locale routing
- Handle RTL languages appropriately
- Optimize translation loading

## Quality Assurance
### Testing Strategy
- Unit tests for utility functions
- Component testing with Testing Library
- Integration tests for critical user flows
- E2E tests with Playwright

### Development Workflow
- Use TypeScript strict mode
- Implement pre-commit hooks
- Use ESLint and Prettier for code consistency
- Regular dependency updates

## Resources
- [SvelteKit Documentation](https://kit.svelte.dev/docs)
- [Svelte 5 Guide](https://svelte-5-preview.vercel.app/)
- [Supabase Documentation](https://supabase.com/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Drizzle ORM Documentation](https://orm.drizzle.team/)

