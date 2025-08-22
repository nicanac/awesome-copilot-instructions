# Astro + TypeScript Copilot Instructions

## Astro Development Guidelines
- Enforce strict TypeScript settings for type safety.
- Use TailwindCSS for all styling (utility-first approach).
- Ensure Astro components are modular, reusable, and maintain separation of concerns.

## TypeScript Guidelines
- Enforce strict TypeScript settings in all .ts files for type safety.

## TailwindCSS Styling
- Use TailwindCSS for all styling in .astro files, following the utility-first approach.

## Coding Style
- Code must start with a path/filename one-line comment.
- Comments should describe purpose, not effect.
- Prioritize modularity, DRY principles, and performance.

## Commit Messages
- Always suggest a conventional commit with type and optional scope in lowercase.
- Format: <type>(<scope>): <description>
- Types: build, chore, ci, docs, feat, fix, perf, refactor, revert, style, test
- Description: imperative mood, lowercase, no period
- Keep commit messages concise (≤60 characters) and ready to paste.
- For breaking changes: Add `!` after type/scope or use `BREAKING CHANGE:` footer
- Provide the full git commit command.
- Enable the /commit command to generate a conventional commit message.
