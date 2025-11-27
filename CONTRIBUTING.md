# Contributing to Interview Persona Engine

Thank you for your interest in contributing to Interview Persona Engine! This document provides guidelines and instructions for contributing to the project.

## Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- Help each other learn and grow
- Report any inappropriate behavior

## How to Contribute

### Reporting Bugs

Before creating bug reports, please check if the issue already exists. When you create a bug report, include as much detail as possible:

- **Describe the bug**: What happened and what did you expect to happen?
- **Steps to reproduce**: Clear steps to reproduce the issue
- **Environment**: OS, Python version, Node version, browser
- **Screenshots**: If applicable
- **Error messages**: Full error stack trace

### Suggesting Enhancements

Enhancement suggestions are always welcome! When suggesting an enhancement:

- Use a clear and descriptive title
- Describe the current behavior and expected behavior
- Explain why this enhancement would be useful
- List other projects that have similar features (if applicable)

### Pull Requests

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Interview-Persona-Engine.git
   cd Interview-Persona-Engine
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. **Make your changes**
   - Keep commits atomic and logical
   - Write clear commit messages
   - Follow the existing code style

4. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```

5. **Push to your branch**
   ```bash
   git push origin feature/AmazingFeature
   ```

6. **Open a Pull Request**
   - Provide a clear description of the changes
   - Reference any related issues
   - Ensure all tests pass

## Development Setup

### Prerequisites
- Python 3.8+
- Node.js 14+
- Git

### Setup Instructions

1. **Clone and navigate**
   ```bash
   git clone https://github.com/PrashantPKP/Interview-Persona-Engine.git
   cd Interview-Persona-Engine
   ```

2. **Backend setup**
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   cp .env.example .env
   # Add your Groq API key to .env
   ```

3. **Frontend setup**
   ```bash
   cd ..
   npm install
   ```

4. **Start development servers**
   - Terminal 1: `cd backend && python app.py`
   - Terminal 2: `npm start`

## Coding Standards

### Python
- Follow PEP 8 style guide
- Use meaningful variable names
- Add docstrings to functions and classes
- Use type hints where applicable
- Keep functions focused and small

### JavaScript/React
- Use meaningful component and variable names
- Follow ES6+ standards
- Add comments for complex logic
- Keep components modular and reusable
- Use functional components with hooks

### General
- Write clean, readable code
- Add comments for non-obvious logic
- Avoid code duplication
- Keep functions/components focused

## Git Commit Messages

Use clear and descriptive commit messages:

```
feat: Add user authentication feature
fix: Resolve bug in API response parsing
docs: Update README with new setup instructions
style: Format code according to PEP 8
refactor: Simplify interview history component
test: Add unit tests for evaluateAnswer function
```

## Testing

Before submitting a pull request:

1. Test your changes locally
2. Verify both frontend and backend work correctly
3. Test with different job roles and experience levels
4. Check for console errors and warnings

## Documentation

When adding new features:

1. Update README.md if needed
2. Add code comments for complex logic
3. Update API documentation in README
4. Add example usage if applicable

## Project Structure Guidelines

When adding new files:

- **Backend routes**: Add to `backend/app.py`
- **Frontend components**: Add to `src/` directory
- **Styles**: Create corresponding `.css` files
- **Configuration**: Use environment variables via `.env`

## Areas for Contribution

We'd love help with:

- [ ] Bug fixes and error handling improvements
- [ ] Performance optimizations
- [ ] UI/UX improvements
- [ ] Additional job roles and interview questions
- [ ] Documentation improvements
- [ ] Mobile responsiveness enhancements
- [ ] Tests and test coverage
- [ ] Accessibility improvements

## Questions?

Feel free to:
- Open an issue for questions
- Check existing issues and discussions
- Reach out via LinkedIn: https://www.linkedin.com/in/prashantpkp/
- Check the portfolio: https://prashantparshuramkar.host20.uk/

## License

By contributing to this project, you agree that your contributions will be licensed under its MIT License.

---

Thank you for contributing! 🎉
