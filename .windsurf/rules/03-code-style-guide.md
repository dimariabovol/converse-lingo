---
trigger: always_on
---

# Code Style Guide

## General Principles

- **Simplicity**: Prioritize readable, maintainable code over clever solutions
- **Consistency**: Follow established patterns in the codebase
- **Documentation**: Document complex logic, architectural decisions, and public APIs
- **File Size**: Keep files under 200 lines; refactor when approaching this limit
- **DRY (Don't Repeat Yourself)**: Avoid code duplication by creating reusable components

## Python Code Style

- Follow [PEP 8](https://pep8.org/) conventions
- Use 4 spaces for indentation (no tabs)
- Maximum line length of 88 characters (compatible with Black formatter)
- Use docstrings for functions, classes, and modules
- Use type hints where appropriate
- Name variables and functions in snake_case
- Name classes in PascalCase
- Constants should be UPPER_SNAKE_CASE

## Django-Specific Guidelines

- Follow the [Django coding style](https://docs.djangoproject.com/en/stable/internals/contributing/writing-code/coding-style/)
- Organize models.py, views.py, etc. into packages when they grow too large
- Use class-based views where appropriate
- Always include verbose_name in model fields for translation
- Write granular, focused tests

## JavaScript Code Style

- Use ES6+ features where possible
- Use camelCase for variables and functions
- Use PascalCase for classes
- Use 2 spaces for indentation (no tabs)
- Maximum line length of 80 characters

## HTML/CSS Style

- Use 2 spaces for indentation in HTML and CSS
- Use kebab-case for CSS class names
- Follow BEM (Block, Element, Modifier) naming convention for CSS classes
- Organize CSS properties alphabetically
- Use semantic HTML elements

## Commit Style

- Use clear, descriptive commit messages
- Start with a verb in the imperative mood (e.g., "Add", "Fix", "Update")
- Keep the first line under 50 characters
- For complex changes, add a detailed description after the first line
