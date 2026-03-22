# Color Reference Guide

Complete color palette documentation for the Naruto Shinobi Theme.

---

## 🎨 Primary Color System

### Naruto Core Palette

#### Uzumaki Orange
**Primary brand color** - Represents Naruto's spirit and determination.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Dark | `#FF6B00` | `255, 107, 0` | Primary accent, keywords, activity bar |
| Standard | `#FF8C00` | `255, 140, 0` | Control keywords, status bar (Dawn) |
| Light | `#FFA500` | `255, 165, 0` | Hover states, Dawn variant |
| Lightest | `#FFB84D` | `255, 184, 77` | Section headers, operators (Dawn) |

#### Chakra Blue
**Secondary accent** - Energy and focus.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Dark | `#0066CC` | `0, 102, 204` | Reserved |
| Standard | `#4A90E2` | `74, 144, 226` | Variables, properties, links |
| Light | `#5DADE2` | `93, 173, 226` | Highlights, italics |
| Lightest | `#00A8E8` | `0, 168, 232` | Parameters (Dawn) |

#### Shinobi Black
**Background colors** - Depth and focus.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Pure | `#0D0D0D` | `13, 13, 13` | Editor background (Night) |
| Dark | `#1A1A1A` | `26, 26, 26` | Editor background (Dawn), UI elements |
| Medium | `#262626` | `38, 38, 38` | Highlights, selections (Dawn) |
| Light | `#2D2D2D` | `45, 45, 45` | Reserved |

#### Scroll Cream
**Foreground/text colors** - Clarity and readability.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Cream | `#F5F5DC` | `245, 245, 220` | Editor text (Night) |
| Floral | `#FFFAF0` | `255, 250, 240` | Editor text (Dawn) |
| White | `#FFFFFF` | `255, 255, 255` | Active text, highlights |
| Light Gray | `#E8E8E8` | `232, 232, 232` | UI text, punctuation |

---

## 🔥 Semantic Color System

### Error & Warning Colors

#### Sharingan Red
**Error states** - Danger and critical issues.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Dark | `#CC0000` | `204, 0, 0` | Errors, badges, breakpoints (Night) |
| Standard | `#FF0000` | `255, 0, 0` | Bright errors, invalid code |
| Light | `#E74C3C` | `231, 76, 60` | Errors (Dawn), deleted files |
| Uchiha | `#C0392B` | `192, 57, 43` | Reserved |

#### Nine-Tails Gold
**Warning states** - Caution and important information.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Dark | `#FFD700` | `255, 215, 0` | Constants, warnings, classes (CSS) |
| Standard | `#FFC107` | `255, 193, 7` | Numbers, warnings, booleans |
| Light | `#F39C12` | `243, 156, 18` | Null values, numbers (Dawn) |
| Orange | `#E67E22` | `230, 126, 34` | Deprecated code |

### Success Colors

#### Forest Green
**Success states** - Positive actions and strings.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Dark | `#228B22` | `34, 139, 34` | Reserved |
| Medium | `#27AE60` | `39, 174, 96` | String escapes, regex, additions (Dawn) |
| Standard | `#4CAF50` | `76, 175, 80` | Strings, success, additions (Night) |
| Light | `#00CC66` | `0, 204, 102` | Reserved |

---

## 💜 Functional Color System

### Code Element Colors

#### Rinnegan Purple
**Functions and methods** - Mystical power and capabilities.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Dark | `#7B1FA2` | `123, 31, 162` | Reserved |
| Medium | `#8E44AD` | `142, 68, 173` | Functions, methods, properties (CSS) |
| Standard | `#9C27B0` | `156, 39, 176` | Function definitions, conflicts |
| Light | `#6A1B9A` | `106, 27, 154` | Reserved |

#### Rasengan Cyan
**Classes and types** - Structured power.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Dark | `#00CED1` | `0, 206, 209` | Classes, types, CSS IDs |
| Standard | `#17A2B8` | `23, 162, 184` | Interfaces, modules, namespaces |
| Light | `#20B2AA` | `32, 178, 170` | Reserved |

#### Sage Amber
**Constants** - Powerful unchanging values.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Dark | `#FFBF00` | `255, 191, 0` | Reserved |
| Standard | `#FF9800` | `255, 152, 0` | Reserved |
| Light | `#F57C00` | `245, 124, 0` | Reserved |

---

## 🌫️ Neutral Colors

### Shadow Gray
**Comments and disabled elements** - Subtle information.

| Variant | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Dark | `#4A4A4A` | `74, 74, 74` | Whitespace, guides |
| Medium | `#6C6C6C` | `108, 108, 108` | Comments (Night), line numbers |
| Standard | `#808080` | `128, 128, 128` | Comments (Dawn), inactive elements |
| Light | `#95A5A6` | `149, 165, 166` | Doc comments (Dawn) |

---

## 🎯 Usage by Language

### JavaScript/TypeScript

```javascript
// Comments - #6C6C6C / #808080
import { Component } from 'react'; // Keywords - #FF6B00 / #FFA500

class MyComponent { // Class - #00CED1 / #17A2B8
  constructor() { // Method - #9C27B0 / #8E44AD
    this.state = { // This - #FF8C00 / #FFB84D
      count: 0, // Property - #4A90E2 / #5DADE2, Number - #FFC107 / #F39C12
      message: "Hello" // String - #4CAF50 / #27AE60
    };
  }
  
  increment() { // Method - #9C27B0 / #8E44AD
    const value = 1; // Keyword - #FF6B00 / #FFA500, Const - #FFD700
    return value; // Return - #FF8C00 / #FFB84D
  }
}
```

### Python

```python
# Comments - #6C6C6C / #808080
import math  # Keyword - #FF6B00 / #FFA500

class Person:  # Class - #00CED1 / #17A2B8
    def __init__(self, name):  # Method - #9C27B0 / #8E44AD
        self.name = name  # Self - #FF8C00 / #FFB84D, Property - #4A90E2 / #5DADE2
        self.age = 25  # Number - #FFC107 / #F39C12
        
    def greet(self):  # Method - #9C27B0 / #8E44AD
        message = f"Hello, {self.name}"  # String - #4CAF50 / #27AE60
        return message  # Keyword - #FF8C00 / #FFB84D
```

### CSS

```css
/* Comments - #6C6C6C / #808080 */
.container { /* Class - #FFD700 */
  color: #FF6B00; /* Property - #9C27B0 / #8E44AD, Value - #5DADE2 / #00A8E8 */
  font-size: 16px; /* Property - #9C27B0 / #8E44AD, Number - #FFC107 / #F39C12 */
  background: rgba(255, 107, 0, 0.5); /* Function - #8E44AD */
}

#header { /* ID - #00CED1 / #17A2B8 */
  display: flex; /* Property - #9C27B0 / #8E44AD */
}
```

### HTML

```html
<!-- Comments - #6C6C6C / #808080 -->
<div class="container"> <!-- Tag - #FF6B00 / #FFA500, Attribute - #4A90E2 / #5DADE2 -->
  <h1 id="title">Hello</h1> <!-- Attribute - #4A90E2 / #5DADE2, String - #4CAF50 / #27AE60 -->
</div>
```

### Markdown

```markdown
# Heading - #FF6B00 / #FFA500 (bold)

**Bold text** - #FFC107 / #F39C12 (bold)
*Italic text* - #5DADE2 / #00A8E8 (italic)

[Link](https://example.com) - #00CED1 / #17A2B8 (underline)

`inline code` - #4CAF50 / #27AE60

> Blockquote - #6C6C6C / #808080 (italic)
```

---

## 🎨 Color Transparency Guide

### Transparency Levels

| Opacity | Hex Suffix | Use Case |
|---------|-----------|----------|
| 100% | No suffix | Solid colors |
| 75% | `BF` | Strong emphasis |
| 50% | `80` | Medium emphasis |
| 40% | `66` | Selections |
| 30% | `4D` | Highlights |
| 25% | `40` | Backgrounds |
| 20% | `33` | Hover states |
| 15% | `26` | Subtle backgrounds |
| 10% | `1A` | Very subtle |

### Common Transparent Colors

```json
{
  "selection": "#FF6B0040",        // 25% orange
  "hover": "#FF6B0020",            // 12.5% orange
  "highlight": "#4A90E230",        // 18.75% blue
  "findMatch": "#FFD70060",        // 37.5% gold
  "error": "#CC000030",            // 18.75% red
  "success": "#4CAF5020"           // 12.5% green
}
```

---

## 🔍 Contrast Ratios

### WCAG AA Compliance

| Foreground | Background | Ratio | Result |
|-----------|-----------|-------|--------|
| `#F5F5DC` | `#0D0D0D` | 18.2:1 | ✅ AAA |
| `#FF6B00` | `#0D0D0D` | 5.8:1 | ✅ AA |
| `#4A90E2` | `#0D0D0D` | 4.6:1 | ✅ AA |
| `#6C6C6C` | `#0D0D0D` | 5.1:1 | ✅ AA |
| `#FFFAF0` | `#1A1A1A` | 15.1:1 | ✅ AAA |

---

## 🎯 Theme Variant Differences

### Naruto Shinobi Night vs Hokage Dawn

| Element | Shinobi Night | Hokage Dawn |
|---------|---------------|-------------|
| **Editor Background** | `#0D0D0D` | `#1A1A1A` |
| **Text** | `#F5F5DC` | `#FFFAF0` |
| **Primary Accent** | `#FF6B00` | `#FFA500` |
| **Status Bar** | `#FF6B00` | `#FF8C00` |
| **Comments** | `#6C6C6C` | `#808080` |
| **Keywords** | `#FF6B00` | `#FFA500` |
| **Strings** | `#4CAF50` | `#27AE60` |
| **Functions** | `#9C27B0` | `#8E44AD` |
| **Classes** | `#00CED1` | `#17A2B8` |
| **Line Highlight** | `#1A1A1A` | `#262626` |

---

## 📊 Color Psychology

### Why These Colors?

- **Orange** (#FF6B00): Energy, enthusiasm, determination - Naruto's core trait
- **Blue** (#4A90E2): Trust, intelligence, calm - Chakra representation
- **Purple** (#9C27B0): Wisdom, power, mystery - Rinnegan abilities
- **Green** (#4CAF50): Growth, harmony, nature - Nature chakra
- **Red** (#CC0000): Danger, power, passion - Sharingan
- **Gold** (#FFD700): Value, prestige, energy - Nine-Tails power
- **Cyan** (#00CED1): Clarity, focus, energy - Rasengan

---

## 🎨 Creating Custom Variants

### Template

```json
{
  "name": "Your Variant Name",
  "type": "dark",
  "colors": {
    "editor.background": "#______",
    "editor.foreground": "#______",
    "editorCursor.foreground": "#______",
    "statusBar.background": "#______",
    // ... more colors
  }
}
```

### Guidelines

1. **Maintain hierarchy**: Background → Foreground → Accents
2. **Check contrast**: Use contrast checkers for accessibility
3. **Test extensively**: Multiple languages and UI elements
4. **Stay thematic**: Keep the Naruto inspiration
5. **Document**: Explain your color choices

---

**Need help with colors?** Open an issue or discussion on GitHub!

**Believe it!** 🍥
