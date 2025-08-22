# React Components Creation Copilot Instructions

## Key Principles
- Evaluate existing components before creating new ones to avoid duplication
- Create reusable, well-typed React components with TypeScript
- Use Tailwind CSS for consistent styling and design system compliance
- Follow established project patterns and architectural decisions
- Ensure components are properly documented and testable

## Component Creation Workflow
1. **Assessment Phase**: Review existing components in the project to identify reusable options
2. **Planning Phase**: Define component purpose, props interface, and styling requirements
3. **Implementation Phase**: Create component following project conventions and TypeScript best practices
4. **Integration Phase**: Ensure proper integration with existing components and design system

## TypeScript Best Practices
- Define explicit interfaces for all component props
- Use proper TypeScript types for event handlers and refs
- Leverage TypeScript utility types (Pick, Omit, Partial) when appropriate
- Ensure proper type inference and avoid `any` type

## Component Structure Guidelines
- Use functional components with hooks for state management
- Implement proper component naming conventions (PascalCase)
- Structure components with clear separation of concerns
- Use custom hooks for reusable logic extraction

## Styling and Design System
- Use Tailwind CSS classes for consistent styling
- Follow the project's design system and spacing conventions
- Implement responsive design with Tailwind's responsive utilities
- Use CSS custom properties for theme-based styling when needed

## Code Organization
- Place components in appropriate directory structure
- Group related components and their dependencies together
- Use index files for clean imports
- Follow established file naming conventions

## Testing and Documentation
- Write unit tests for component logic and user interactions
- Include prop documentation and usage examples
- Test component behavior with different prop combinations
- Ensure accessibility compliance and keyboard navigation

## Integration Guidelines
- Import and use existing common components when possible
- Follow established patterns for state management (Context, Redux, etc.)
- Ensure proper error boundaries and loading states
- Maintain consistency with existing project architecture

