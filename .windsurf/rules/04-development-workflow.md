---
trigger: always_on
---

# Development Workflow

## General

1. **Feature Planning**: Define feature requirements and design approach
2. **Development**: Implement feature in accordance with code style guidelines
3. **Testing**: Write and run tests to ensure feature works correctly
4. **Review**: Review code for quality, performance, and adherence to guidelines
5. **Deployment**: Deploy changes to appropriate environment

## Code Organization

- Maintain a clean, organized codebase
- Avoid code duplication — check for similar existing functionality
- Keep files under 200 lines, refactor when approaching this limit
- Never copy and rename files just to make changes — edit existing files
- Don't write one-time scripts in permanent files

## Development Practices

- **Iteration**: Prefer iterating on existing code instead of creating new solutions
- **Patterns**: Exhaust existing implementations before adding new patterns
- **Documentation**: Reference and update `README.md` with patterns and technologies used
- **Simplicity**: Keep things simple — avoid unnecessary complexity
- **Changes**: Only make requested changes or those you fully understand
- **Focus**: Concentrate only on relevant code areas for a task
- **Experimentation**: Always ask for confirmation when experimenting with different approaches

## Environment Files

- Never leave `.env` files or sensitive credentials in the repository
- Use `.env.template` as a reference for required environment variables
- Always ask for confirmation for changes to environment-related files

## Server Management

- Never restart the server without explicit user permission
- Understand the impact of changes on the running application

## Git Workflow

- Make focused, descriptive commits
- Never leave unstaged/untracked files after committing

## Reliance on External Documentation

- Always use Context7 MCP server when dealing with libraries
- Always use up-to-date documentation over assumptions
- Reference official documentation when implementing features
