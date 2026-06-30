# Contributing to Amine's Hardware Projects 🛠️

First off, thanks for taking the time to contribute! 🎉 It's people like you that make our hardware security community amazing.

---

## 📋 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

---

## 🚀 How Can I Contribute?

### 🐛 Reporting Bugs

Before creating bug reports, please check the [issue list](../../issues) as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps which reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed after following the steps**
- **Explain which behavior you expected to see instead and why**
- **Include screenshots and animated GIFs if possible**
- **Include your environment** (OS, hardware, software versions)

### 💡 Suggesting Enhancements

Enhancement suggestions are tracked as [GitHub issues](../../issues). When creating an enhancement suggestion, please include:

- **A clear and descriptive title**
- **A step-by-step description of the suggested enhancement**
- **Specific examples to demonstrate the steps**
- **A description of the current behavior and expected behavior**
- **Explain why this enhancement would be useful**

### 🔧 Pull Requests

- Fill in the required template
- Follow the [coding standards](#coding-standards)
- Include appropriate test cases
- End all files with a newline
- Avoid platform-dependent code

---

## 📝 Coding Standards

### Hardware Design
- **PCB Files**: Use KiCAD format (.kicad_sch, .kicad_pcb)
- **Schematics**: Clear, well-organized, properly labeled
- **Comments**: Document complex circuits and design decisions
- **Naming**: Use meaningful component designators (R1, C1, U1, etc.)

### Firmware
- **Language**: C/C++ for embedded systems
- **Style**: Follow Linux kernel coding style
- **Comments**: Document all functions and complex logic
- **Testing**: Test on actual hardware before submitting

### Python Scripts
- **PEP 8**: Follow Python Enhancement Proposal 8
- **Docstrings**: Document all modules, functions, and classes
- **Type Hints**: Use type hints for better code clarity
- **Testing**: Include unit tests where applicable

---

## 🔐 Security Guidelines

When contributing code with security implications:

1. **Never commit secrets** - API keys, passwords, tokens
2. **Sanitize user input** - Prevent injection attacks
3. **Use secure defaults** - Encryption enabled by default
4. **Test thoroughly** - Security issues are critical
5. **Document security** - Explain security mechanisms
6. **Report responsibly** - Use [SECURITY.md](SECURITY.md) for vulnerabilities

---

## 📚 Documentation

Good documentation is just as important as code. When contributing:

- Update README.md with new features
- Add docstrings to all functions
- Include usage examples
- Add comments for non-obvious logic
- Update CHANGELOG.md

---

## 🧪 Testing

Before submitting a pull request:

```bash
# Test your code
python -m pytest tests/

# Check code style
pylint *.py

# Run on actual hardware (if applicable)
# Verify all features work as expected
```

---

## 📦 Commit Messages

Write clear and meaningful commit messages:

```
[TYPE] Brief description (50 chars max)

More detailed explanation if needed (72 chars max per line).
Explain WHAT and WHY, not HOW.

References: #issue_number
```

**Types:**
- `[FEAT]` - New feature
- `[FIX]` - Bug fix
- `[DOCS]` - Documentation
- `[STYLE]` - Code style changes
- `[REFACTOR]` - Code refactoring
- `[TEST]` - Adding tests
- `[CHORE]` - Build, dependencies, etc

---

## 🎯 Development Workflow

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/project.git
   cd project
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Write clean, readable code
   - Add comments where needed
   - Update documentation

4. **Test everything**
   - Run unit tests
   - Test on hardware if applicable
   - Check for regressions

5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Submit a Pull Request**
   - Fill in the PR template completely
   - Link related issues
   - Request review from maintainers

---

## 🎓 Getting Help

- 📖 **Documentation**: Check [our wiki](../../wiki)
- 💬 **Discussions**: Use [GitHub Discussions](../../discussions)
- 📧 **Email**: amine.tech.div@gmail.com
- 🐛 **Issues**: Search existing [issues](../../issues)

---

## 📊 Recognition

All contributors will be recognized in:
- README.md contributors section
- Release notes
- Special mentions in documentation

---

## 🙏 Thank You!

Your contributions make this project better for everyone. We appreciate:
- Bug reports
- Feature suggestions
- Code improvements
- Documentation updates
- Community support

---

**Happy Contributing!** 🚀

---

<div align="center">
  <p><b>🛡️ Building Secure Hardware Together 🔐</b></p>
</div>