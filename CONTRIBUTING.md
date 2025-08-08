# Contributing to ProteGear CLI

We love contributions from everyone! By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## Getting Started

### Prerequisites

- Go 1.19 or later
- Git

### Setting up your development environment

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR-USERNAME/protegear-cli.git`
3. Navigate to the project directory: `cd protegear-cli`
4. Create a new branch for your feature: `git checkout -b feature-name`

## How to Contribute

### Reporting Bugs

Before creating bug reports, please check the existing issues to see if the problem has already been reported. When you are creating a bug report, please include as many details as possible:

- Use a clear and descriptive title
- Describe the exact steps to reproduce the problem
- Provide specific examples to demonstrate the steps
- Describe the behavior you observed and what behavior you expected
- Include details about your configuration and environment

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- Use a clear and descriptive title
- Provide a step-by-step description of the suggested enhancement
- Provide specific examples to demonstrate the steps
- Describe the current behavior and explain which behavior you expected to see
- Explain why this enhancement would be useful

### Pull Requests

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build
2. Update the [README.md](./README.md) with details of changes to the interface, including new environment variables, exposed ports, useful file locations, and container parameters
3. Increase the version numbers in any examples files and the [README.md](./README.md) to the new version that this Pull Request would represent
4. Follow the Go coding conventions and style guide

#### Code Style

- Follow the standard Go formatting guidelines (`gofmt`)
- Use meaningful variable and function names
- Add comments for exported functions and types
- Write unit tests for new functionality
- Ensure all tests pass before submitting

#### Commit Messages

Follow [conventional commits](https://www.conventionalcommits.org) conventions for commit messages:

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

#### Testing

- Write tests for new code
- Ensure all tests pass: `go test ./...`
- Run linting: `golangci-lint run` (if available)
- Test your changes thoroughly before submitting

#### Documentation

- Update documentation for any new features
- Ensure code comments are clear and helpful
- Update [README.md](./README.md) if necessary

## Development Workflow

1. Fork and clone the repository
2. Create a new branch from `main`
3. Make your changes
4. Write or update tests
5. Run tests and ensure they pass
6. Run `go fmt` to format your code
7. Commit your changes following [conventional commits](https://www.conventionalcommits.org/) with a clear commit message
8. Push to your fork
9. Submit a pull request

## Getting Help

If you need help with contributing, please:

- Check the documentation
- Search existing issues
- Create a new issue with the "question" label

## Recognition

Contributors will be recognized in the project documentation and releases.

Thank you for contributing to ProteGear CLI!