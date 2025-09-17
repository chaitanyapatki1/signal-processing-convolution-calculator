# Contributing to Signal Processing Convolution Calculator

Thank you for your interest in contributing to this project! This document provides guidelines and information for contributors.

## 🚀 Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager
- Git for version control
- Basic knowledge of React, TypeScript, and Tailwind CSS

### Setting Up Development Environment

1. **Fork the repository**
   - Click the "Fork" button on the GitHub repository page
   - Clone your fork locally:
   ```bash
   git clone https://github.com/yourusername/signal-processing-convolution-calculator.git
   cd signal-processing-convolution-calculator
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Create a new branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📋 How to Contribute

### Types of Contributions
- **Bug fixes**: Fix issues or improve existing functionality
- **Feature additions**: Add new signal processing capabilities
- **Documentation**: Improve README, comments, or add tutorials
- **UI/UX improvements**: Enhance the user interface and experience
- **Performance optimizations**: Improve application speed and efficiency
- **Testing**: Add or improve test coverage

### Before You Start
1. Check existing [issues](https://github.com/yourusername/signal-processing-convolution-calculator/issues) to avoid duplicates
2. For major changes, open an issue first to discuss your proposal
3. Make sure your development environment is properly set up

## 🔧 Development Guidelines

### Code Style
- **TypeScript**: Use strict typing and avoid `any` types
- **React**: Use functional components with hooks
- **Naming**: Use descriptive names for variables, functions, and components
- **Comments**: Add comments for complex algorithms and signal processing logic
- **Formatting**: The project uses ESLint for consistent code formatting

### Component Structure
```typescript
// Good component structure
interface ComponentProps {
  // Define clear prop types
}

const Component: React.FC<ComponentProps> = ({ prop1, prop2 }) => {
  // Component logic
  
  return (
    // JSX with proper Tailwind classes
  );
};

export default Component;
```

### Signal Processing Guidelines
- Implement algorithms clearly with step-by-step comments
- Maintain mathematical accuracy in convolution calculations
- Provide educational value through clear trace outputs
- Test with various signal inputs and edge cases

### UI/UX Guidelines
- Follow the existing dark theme with blue accents
- Ensure responsive design works on all screen sizes
- Add smooth transitions and micro-interactions
- Maintain accessibility standards
- Use Lucide React icons consistently

## 🧪 Testing

### Manual Testing
- Test all signal input methods (manual entry, presets)
- Verify convolution calculations with known results
- Check responsive design on different screen sizes
- Test all navigation flows and error states

### Test Cases to Consider
- Empty signals
- Single-element signals
- Large signals (performance testing)
- Negative values
- Zero values
- Edge cases in search functionality

## 📝 Commit Guidelines

### Commit Message Format
```
type(scope): brief description

Detailed explanation if needed

- List any breaking changes
- Reference issues: Fixes #123
```

### Commit Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `perf`: Performance improvements
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

### Examples
```bash
feat(convolution): add support for complex number signals
fix(ui): resolve responsive layout issue on mobile devices
docs(readme): update installation instructions
style(components): improve code formatting and consistency
```

## 🔍 Pull Request Process

### Before Submitting
1. **Test thoroughly**: Ensure your changes work correctly
2. **Update documentation**: Modify README or comments as needed
3. **Check code style**: Run `npm run lint` to verify formatting
4. **Build successfully**: Run `npm run build` to ensure no build errors

### Pull Request Template
When creating a pull request, include:

```markdown
## Description
Brief description of changes made

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement
- [ ] Other (please describe)

## Testing
- [ ] Manual testing completed
- [ ] All existing functionality verified
- [ ] New functionality tested with various inputs

## Screenshots (if applicable)
Include screenshots for UI changes

## Additional Notes
Any additional context or considerations
```

### Review Process
1. Automated checks must pass (linting, building)
2. At least one maintainer review required
3. Address any feedback or requested changes
4. Maintain clean commit history

## 🐛 Reporting Issues

### Bug Reports
Include the following information:
- **Description**: Clear description of the issue
- **Steps to reproduce**: Detailed steps to recreate the bug
- **Expected behavior**: What should happen
- **Actual behavior**: What actually happens
- **Environment**: Browser, OS, screen size
- **Screenshots**: If applicable

### Feature Requests
- **Description**: Clear description of the proposed feature
- **Use case**: Why this feature would be valuable
- **Implementation ideas**: Any thoughts on how to implement
- **Examples**: Similar features in other applications

## 📚 Resources

### Learning Resources
- [React Documentation](https://react.dev/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Digital Signal Processing Fundamentals](https://en.wikipedia.org/wiki/Digital_signal_processing)

### Project-Specific Resources
- [Convolution Algorithm Explanation](https://en.wikipedia.org/wiki/Convolution)
- [Discrete-Time Signal Processing](https://en.wikipedia.org/wiki/Discrete-time_signal)

## 🤝 Community Guidelines

### Code of Conduct
- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow
- Focus on the technical aspects of contributions

### Getting Help
- Check existing documentation first
- Search through existing issues
- Ask questions in issue comments
- Be specific about your problem or question

## 🎯 Priority Areas

Current areas where contributions are especially welcome:
- **Algorithm optimizations**: Improve convolution computation performance
- **Additional signal types**: Support for different signal formats
- **Enhanced visualizations**: More interactive plotting features
- **Educational content**: Tutorials and examples
- **Accessibility improvements**: Better screen reader support
- **Mobile experience**: Enhanced mobile interface

## 📄 License

By contributing to this project, you agree that your contributions will be licensed under the MIT License.

---

Thank you for contributing to the Signal Processing Convolution Calculator! Your efforts help make signal processing education more accessible and engaging for everyone.
