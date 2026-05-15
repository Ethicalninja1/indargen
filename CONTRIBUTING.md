# Contributing to IndarGen

## How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Code Standards

- Follow PEP 8 guidelines
- Keep it pure Python3 — no external dependencies
- Add color support for new features
- Include comments for complex logic
- Test on both Linux and Windows (WSL)

## Adding New Mutation Patterns

If you want to add new password mutation logic:

1. Add the function in the designated section
2. Integrate it into `run_password_generation()` pipeline
3. Ensure it returns a `set()` for easy deduplication
4. Add progress print statement with color codes
5. Update README with new feature documentation

## Pull Request Process

1. Update README.md with details of changes if needed
2. Update any relevant documentation
3. The PR will be reviewed within 48 hours
4. Merge requires at least one maintainer approval
