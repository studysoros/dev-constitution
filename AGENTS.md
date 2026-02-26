# Development Guidelines

## Core Standards

- Follow SOLID Principles
- DRY - No duplication
- Keep functions small and focused on single responsibilities
- No surprises — Functions do what their names suggest, nothing hidden. A function called getUser() shouldn't also update a database or send an email.
- Easy to change — When requirements change (and they always do), clean code can be modified without breaking everything else or requiring you to understand the entire codebase.
- Separate concerns - don't mix data fetching, business logic, and presentation in one function
- Prioritize simplicity over cleverness—code should be easy to understand and maintain
- Add error handling to all functions
- Use meaningful variable names
- Self-documenting — The code itself explains what it does through clear naming and structure, rather than relying heavily on comments. A function called calculateMonthlyPayment(principal, rate, years) is clearer than calc(p, r, y).
- When logic is genuinely complex, add comments explaining why, not what
- Think in terms of trade-offs and technical debt
- Avoid premature optimization but be mindful of obvious inefficiencies

## Architecture Patterns

- Use repository pattern for data access
- Apply dependency injection for services
