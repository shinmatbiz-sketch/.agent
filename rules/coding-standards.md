# Coding Standards

This file defines the coding standards and best practices for the AG1 workspace.

## Security
- **NEVER commit .env files or API keys.**
- Use environment variables for all sensitive information.

## Language & Documentation
- **Japanese Preference:** Use Japanese for documentation, comments, and commit messages unless otherwise specified.
- **English Code:** Use English for variable names, function names, and other code identifiers.

## Technology Stack
- **Frontend:** Next.js (App Router), TypeScript, Tailwind CSS.
- **Backend:** Python, Supabase, Prisma.

## Quality Assurance
- **Type Safety:** Ensure TypeScript strict mode is enabled.
- **Error Handling:** Implement robust error handling, especially for external API calls and file operations.
- **Testing:** Verify changes with browser tests where applicable.
