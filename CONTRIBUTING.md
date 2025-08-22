# Contributing to Awesome Copilot Instructions

Thank you for your interest in contributing to this project! This guide will help you create high-quality copilot instructions that benefit the entire development community.

## 📋 Before You Contribute

- Check if instructions for your technology stack already exist
- Review existing instruction files to understand our standards
- Ensure your contribution follows our naming conventions
- Test your instructions with real projects before submitting

## 🏗️ Creating New Instructions

### Directory Structure
Create a new directory under `rules-copilot-instructions/` following this naming pattern:
- `language-framework-purpose` (e.g., `python-django-web`)
- `framework-version-focus` (e.g., `react-18-hooks`)
- Keep names concise and descriptive
- Use lowercase with hyphens as separators

### File Structure
Each instruction set should contain:
```
your-technology-stack/
└── copilot-instructions.md
```

### Instruction Template
Use this template for consistency:

```markdown
# [Technology/Framework] Copilot Instructions

## Overview
Brief description of the technology stack and its primary use cases.

## Development Principles
- Core principles and best practices for this technology
- Focus on maintainability, performance, and security
- Emphasize clean code and proper architecture

## Technical Stack
- Primary language/framework versions
- Key dependencies and libraries
- Development tools and environment setup

## Coding Standards
### Naming Conventions
- Variable naming patterns
- Function and class naming
- File and directory structure

### Code Organization
- Project structure guidelines
- Module organization
- Separation of concerns

### Best Practices
- Performance considerations
- Security guidelines
- Error handling patterns
- Testing strategies

## Common Patterns
- Frequently used design patterns
- Architecture guidelines
- Code reuse strategies

## Quality Assurance
- Testing approaches
- Code review guidelines
- Documentation requirements
- Deployment considerations

## Resources
- Official documentation links
- Community resources
- Additional learning materials
```

## ✅ Quality Standards

### Content Requirements
- **Comprehensive**: Cover all major aspects of development with the technology
- **Practical**: Include actionable guidelines, not just theory
- **Current**: Use up-to-date versions and best practices
- **Tested**: Verify guidelines work in real projects

### Writing Style
- Use clear, concise language
- Write in active voice
- Include specific examples where helpful
- Use bullet points for better readability
- Maintain consistent formatting

### Technical Accuracy
- Reference official documentation
- Include version numbers for dependencies
- Verify all code examples work
- Update deprecated practices

## 🚀 Submission Process

1. **Fork** the repository and create your branch from `main`
2. **Create** a new directory following naming conventions
3. **Add** your instruction file using the standard template
4. **Test** your instructions with a real project
5. **Submit** a pull request with:
   - Clear description of the technology stack
   - Brief explanation of what makes your instructions unique
   - Evidence of testing (screenshots, project examples)

## 🔧 Improving Existing Instructions

### Types of Improvements
- **Updates**: New versions, deprecated practices, emerging patterns
- **Enhancements**: Additional sections, better examples, clearer explanations
- **Fixes**: Corrections, typos, broken links
- **Optimization**: Better organization, more concise language

## 📝 Style Guidelines

### Markdown Formatting
- Use `#` for main title
- Use `##` for major sections  
- Use `###` for subsections
- Use `-` for bullet points
- Use `**bold**` for emphasis
- Use `code` for inline code

### Language and Tone
- Professional but approachable
- Focus on practical guidance
- Avoid jargon without explanation
- Use inclusive language
- Be specific and actionable

## 🏷️ Naming Conventions

### Good Examples
- `python-fastapi-rest-api`
- `react-typescript-hooks`
- `java-spring-boot-microservices`
- `go-gin-web-development`

### Avoid
- Names with `copilot`, `rules`, or `prompt` (already implied)
- Overly long names (keep to 3-4 segments)
- Generic terms like `awesome` or `ultimate`

## Code of Conduct

Be respectful and constructive in all interactions. See the [Contributor Covenant](https://www.contributor-covenant.org/) for guidance.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

**Thank you for contributing to better development practices!** 🙏
