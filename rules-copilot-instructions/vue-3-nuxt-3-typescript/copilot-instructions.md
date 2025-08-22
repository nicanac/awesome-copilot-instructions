# Vue 3 + Nuxt 3 + TypeScript Copilot Instructions

## Overview
Modern full-stack web development with Vue 3's Composition API, Nuxt 3's universal rendering, and TypeScript for enhanced development experience.

## Development Principles
- Embrace Vue 3's Composition API and script setup syntax
- Use TypeScript for type safety and better development experience
- Follow functional programming patterns where applicable
- Implement responsive-first design with Tailwind CSS
- Optimize for performance and SEO

## Technical Stack
- Vue 3 with Composition API
- Nuxt 3 with Universal Rendering
- TypeScript for type safety
- Vite for fast development and building
- Tailwind CSS for styling
- VueUse for utility functions

## Coding Standards
### TypeScript Guidelines
- Prefer interfaces over types for object shapes
- Avoid enums; use union types or const assertions
- Use strict TypeScript configuration
- Implement proper type guards for runtime type checking

### Vue 3 Best Practices
- Use script setup for single-file components
- Prefer reactive() and ref() over Vue 2 style data
- Implement composables for reusable logic
- Use defineProps and defineEmits with TypeScript

### Component Organization
- Follow functional component patterns
- Separate business logic into composables
- Use provide/inject for deep component communication
- Implement proper component lifecycle management

## Performance Optimization
### Code Splitting
- Use dynamic imports for non-critical components
- Implement lazy loading for routes and components
- Optimize bundle size with proper tree-shaking

### Rendering Optimization
- Use server-side rendering where appropriate
- Implement proper caching strategies
- Optimize images with Nuxt Image module
- Use WebP format for better compression

### Reactive Performance
- Use shallowRef and shallowReactive for large objects
- Implement proper watchers with flush timing
- Avoid unnecessary reactivity for static data

## UI/UX Guidelines
### Responsive Design
- Mobile-first approach with Tailwind CSS
- Use Nuxt UI components for consistency
- Implement proper focus management for accessibility
- Ensure proper color contrast and semantic HTML

### State Management
- Use Pinia for complex state management
- Implement composables for local state
- Handle loading and error states consistently
- Use optimistic updates for better UX

## Quality Assurance
- Unit testing with Vitest
- E2E testing with Playwright
- Type checking in CI/CD pipeline
- Performance monitoring with Nuxt DevTools

