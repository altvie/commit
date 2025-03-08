# Commit Message Format

A well-structured commit message format helps maintain a clear and organized Git history. Below is a standardized format to follow:

## Format
```
[type]: [short description]

[optional longer description]

[optional references to issues or PRs]
```

## Types
Use one of the following types to categorize your commit:

- **feat**: A new feature
- **fix**: A bug fix
- **refactor**: Code changes that neither fix a bug nor add a feature
- **docs**: Documentation updates
- **style**: Code style changes (e.g., formatting, missing semicolons)
- **test**: Adding or updating tests
- **chore**: Maintenance or non-production changes
- **perf**: Performance improvements
- **ci**: Changes to CI/CD configuration
- **build**: Changes to build system or dependencies
- **revert**: Revert a previous commit

## Examples
### Feature Addition
```
feat: add user authentication

Implemented JWT-based authentication with login and registration endpoints.
```

### Bug Fix
```
fix: resolve issue with incorrect user roles

Fixed a bug where new users were assigned incorrect roles upon registration.
Fixes #23.
```

### Documentation Update
```
docs: update README with installation steps

Added detailed installation steps to help new contributors set up the project.
```

### Code Refactoring
```
refactor: optimize database query in user service

Improved the efficiency of the user data retrieval query to enhance performance.
```

## Best Practices
- Use the imperative mood (e.g., "Add feature" instead of "Added feature").
- Keep the summary under 50 characters if possible.
- Provide additional details in the body if necessary.
- Reference related issues or pull requests.

Following this format ensures a clear and structured Git commit history, making collaboration easier for all contributors.

