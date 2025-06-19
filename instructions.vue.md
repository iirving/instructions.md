# GitHub Copilot Guidelines for Vue

## Code Style

- Use meaningful variable and function names

- Follow camelCase naming convention for variables and functions

- Add JSDoc comments for functions and classes

- Keep functions small and focused on a single responsibility

- Avoid using lodash package utils, make sure new code is generated using native JS

## Testing

- Write unit tests

- Use Vitest for testing

- Include test cases for edge cases and error conditions

- Make sure to always use Package.json scripts when running test

- Check test coverage, write test cases to get atleast 90% of coverage

## Best Practices

- Use ES6+ features when appropriate

- Prefer const over let, avoid var

- Use early returns to reduce nesting

- Add error handling where appropriate

- Use pure functions when possible

- Avoid side effects in functions

## Documentation

- Add meaningful comments for complex logic

- Include examples in JSDoc comments

- Document parameters and return types

- Explain any non-obvious implementations

## Performance

- Avoid nested loops when possible

- Be mindful of memory usage

- Consider time complexity of operations

- Cache repeated calculations

## Error Handling

- Use specific error types

- Provide meaningful error messages

- Handle edge cases explicitly

- Validate function inputs

## Version Control

- Write clear commit messages

- Follow semantic versioning

- Keep commits focused and atomic

- Add proper changelog entries

## Dependencies

- Never install or uninstall packages - this must be done by the user themselves

- Never modify package.json dependencies or devDependencies directly

- Never suggest adding new packages. Ask user to consult architects team first

- All package additions/updates must be approved by the architects team before suggesting them
