# Contributing to step-criterion

We welcome contributions to step-criterion! This document provides guidelines for contributing to the project.

## Development Setup

1. Fork the repository on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/yourusername/step-criterion.git
   cd step-criterion
   ```

3. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. Install the package in development mode:
   ```bash
   pip install -e .
   pip install pytest jupyter  # For testing and examples
   ```

## Code Style

- Follow PEP 8 style guidelines
- Use meaningful variable and function names
- Add docstrings for all public functions
- Keep lines under 88 characters when possible

## Testing

- Add tests for new functionality
- Ensure all existing tests pass
- Test with both OLS and GLM models
- Include edge cases in tests

Run tests with:
```bash
pytest
```

## Documentation

- Update the README.md for significant changes
- Update docstrings for API changes
- Add examples to `examples_usage.ipynb` for new features

## Submitting Changes

1. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```

2. Make your changes and commit:
   ```bash
   git add .
   git commit -m "Add feature description"
   ```

3. Push to your fork:
   ```bash
   git push origin feature-name
   ```

4. Create a Pull Request on GitHub

## Issue Guidelines

When reporting issues:

- Use a clear, descriptive title
- Provide a minimal reproducible example
- Include your Python and package versions
- Describe expected vs actual behavior

## Questions?

Feel free to open an issue for questions about contributing!
