# Contributing to Naruto Shinobi Theme

First off, thank you for considering contributing to the Naruto Shinobi Theme! It's people like you that make this theme better for everyone. 🍥

## 🎯 Ways to Contribute

### 1. Reporting Bugs
If you find a color inconsistency, rendering issue, or any other problem:

- **Check existing issues** first to avoid duplicates
- **Use the issue template** if available
- **Include details**:
  - VS Code version
  - Operating System
  - Theme variant (Shinobi Night or Hokage Dawn)
  - Language/file type where the issue occurs
  - Screenshots showing the problem
  - Steps to reproduce

### 2. Suggesting Enhancements
Have ideas for new features or improvements?

- **Check existing issues** for similar suggestions
- **Be specific** about what you want and why
- **Provide examples** or mockups if possible
- **Consider the theme's philosophy** (Naruto-inspired colors and aesthetics)

### 3. Adding Language Support
Help improve syntax highlighting for specific languages:

- Test the theme with your favorite language
- Identify color tokens that could be better
- Suggest improvements with specific scope names
- Provide code samples for testing

### 4. Creating New Variants
Want to create a new theme variant?

- Follow the existing color palette system
- Maintain consistency with the Naruto theme
- Ensure good contrast and accessibility
- Test across multiple languages

---

## 🚀 Development Setup

### Prerequisites
- Visual Studio Code
- Git
- Node.js (optional, for testing)

### Getting Started

1. **Fork the repository**
   ```bash
   # Click the "Fork" button on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/naruto-shinobi-theme.git
   cd naruto-shinobi-theme
   ```

3. **Open in VS Code**
   ```bash
   code .
   ```

4. **Make your changes**
   - Edit theme files in `themes/` directory
   - Follow the existing structure and naming conventions

5. **Test your changes**
   - Press `F5` to open a new VS Code window with your theme
   - Test with multiple file types and languages
   - Check both light and dark environments

6. **Commit your changes**
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

7. **Push to your fork**
   ```bash
   git push origin your-branch-name
   ```

8. **Create a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your fork and branch
   - Describe your changes

---

## 📁 Project Structure

```
naruto-shinobi-theme/
├── themes/
│   ├── naruto-shinobi-night-color-theme.json    # Main dark theme
│   └── naruto-hokage-dawn-color-theme.json      # Softer variant
├── images/                                       # Theme assets
├── docs/                                         # Documentation
├── package.json                                  # Extension manifest
├── README.md                                     # Main documentation
├── CHANGELOG.md                                  # Version history
└── LICENSE                                       # MIT License
```

---

## 🎨 Theme File Structure

Each theme JSON file contains:

```json
{
  "name": "Theme Name",
  "type": "dark",
  "semanticHighlighting": true,
  "colors": {
    // UI colors (editor, sidebar, status bar, etc.)
  },
  "semanticTokenColors": {
    // Semantic token colors for modern languages
  },
  "tokenColors": [
    // TextMate grammar scopes for syntax highlighting
  ]
}
```

---

## 🎯 Color Guidelines

### Philosophy
- **Stay true to Naruto**: Colors should relate to the Naruto universe
- **Maintain contrast**: Ensure readability and accessibility
- **Be consistent**: Use the established color palette
- **Test thoroughly**: Check across multiple languages and contexts

### Color Palette Reference

#### Primary Colors
- **Uzumaki Orange**: `#FF6B00` - Keywords, primary accents
- **Chakra Blue**: `#4A90E2` - Variables, secondary accents
- **Shinobi Black**: `#0D0D0D` - Backgrounds

#### Semantic Colors
- **Sharingan Red**: `#CC0000` - Errors, danger
- **Forest Green**: `#4CAF50` - Strings, success
- **Nine-Tails Gold**: `#FFD700` - Constants, warnings
- **Rinnegan Purple**: `#9C27B0` - Functions, methods
- **Rasengan Cyan**: `#00CED1` - Classes, types

#### Neutral Colors
- **Shadow Gray**: `#6C6C6C` - Comments, disabled
- **Scroll Cream**: `#F5F5DC` - Text, foreground

### Accessibility
- Ensure WCAG AA contrast ratios (4.5:1 for normal text)
- Test with color blindness simulators
- Avoid relying solely on color to convey information

---

## ✅ Testing Checklist

Before submitting a pull request:

- [ ] Tested with JavaScript/TypeScript
- [ ] Tested with React/JSX
- [ ] Tested with Python
- [ ] Tested with HTML/CSS
- [ ] Tested with JSON/YAML
- [ ] Tested with Markdown
- [ ] Checked UI elements (sidebar, status bar, terminal)
- [ ] Verified Git decorations
- [ ] Tested error/warning highlighting
- [ ] Checked bracket pair colorization
- [ ] Tested peek view and hover widgets
- [ ] No console errors in Extension Host
- [ ] Follows existing code style
- [ ] Updated documentation if needed

---

## 📝 Coding Standards

### JSON Formatting
- Use 2 spaces for indentation
- Keep properties alphabetically sorted within sections
- Add comments where helpful (though JSON doesn't support them, describe in PR)

### Color Values
- Use uppercase hex codes: `#FF6B00` not `#ff6b00`
- Use 6-digit hex for colors: `#FF6B00` not `#F60`
- Use 8-digit hex for transparency: `#FF6B0040`

### Scope Naming
- Follow TextMate scope conventions
- Use specific scopes when possible
- Group related scopes together
- Comment sections for clarity

---

## 🔍 Finding Scope Names

To find the scope name for a specific syntax element:

1. **Open Command Palette** (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Type **"Developer: Inspect Editor Tokens and Scopes"**
3. Click on the text you want to style
4. Look at the **textmate scopes** section
5. Use these scope names in the theme file

---

## 🐛 Bug Report Template

```markdown
## Bug Description
A clear description of the issue.

## Steps to Reproduce
1. Open file type...
2. Look at syntax element...
3. Notice incorrect color...

## Expected Behavior
What should happen.

## Actual Behavior
What actually happens.

## Screenshots
Add screenshots if applicable.

## Environment
- VS Code Version: 
- OS: 
- Theme Variant: 
```

---

## 💡 Feature Request Template

```markdown
## Feature Description
A clear description of the feature.

## Use Case
Why this feature would be useful.

## Proposed Solution
How you think it should work.

## Alternatives Considered
Other approaches you've thought about.

## Additional Context
Any other information or screenshots.
```

---

## 📜 Commit Message Guidelines

Use clear, descriptive commit messages:

### Format
```
<type>: <subject>

<body (optional)>

<footer (optional)>
```

### Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Formatting changes
- `refactor`: Code restructuring
- `test`: Adding tests
- `chore`: Maintenance tasks

### Examples
```bash
feat: add support for Rust language
fix: correct Python string escape color
docs: update installation instructions
style: improve JSON property colors
```

---

## 🎖️ Recognition

Contributors will be:
- Listed in the README
- Mentioned in release notes
- Given credit in the CHANGELOG
- Appreciated forever! 🙏

---

## 📞 Questions?

- Open an issue with the `question` label
- Start a discussion on GitHub Discussions
- Reach out to maintainers

---

## 🌟 Code of Conduct

### Our Pledge
Be respectful, inclusive, and constructive.

### Our Standards
- Use welcoming and inclusive language
- Respect differing viewpoints
- Accept constructive criticism gracefully
- Focus on what's best for the community
- Show empathy towards others

### Unacceptable Behavior
- Harassment or discrimination
- Trolling or insulting comments
- Personal or political attacks
- Publishing others' private information

---

**Thank you for contributing to the Naruto Shinobi Theme!** 

*"The true measure of a shinobi is not how he lives but how he dies."*  
Let's make this theme legendary! 🍥

---

**Believe it!** 🔥
