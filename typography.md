# Typography

Typography plays a crucial role in communicating the Vermont Data Science Group brand. Our type system balances professionalism with readability.

## Primary Typefaces

### Headings: Montserrat
**Montserrat** is used for all headings and display text.

- **Font Family**: Montserrat
- **Weights**: 
  - Semi-Bold (600) for H1 and H2
  - Medium (500) for H3 and H4
- **Source**: Google Fonts
- **Usage**: Headlines, section headers, callouts

**Example Sizes:**
- H1: 36px / 2.25rem
- H2: 30px / 1.875rem
- H3: 24px / 1.5rem
- H4: 20px / 1.25rem

### Body Text: Open Sans
**Open Sans** is used for all body text and smaller elements.

- **Font Family**: Open Sans
- **Weights**: 
  - Regular (400) for body text
  - Semi-Bold (600) for emphasis
- **Source**: Google Fonts
- **Usage**: Paragraphs, captions, lists, general text

**Standard Sizes:**
- Body: 16px / 1rem
- Small: 14px / 0.875rem
- Caption: 12px / 0.75rem

## Monospace Font

### Code: Source Code Pro
**Source Code Pro** is used for code snippets and technical content.

- **Font Family**: Source Code Pro
- **Weight**: Regular (400)
- **Source**: Google Fonts
- **Usage**: Code blocks, technical specifications, data tables

## Typography Guidelines

### Hierarchy
Establish clear visual hierarchy through consistent use of font sizes and weights:
1. Most important: Larger sizes, bolder weights
2. Secondary: Medium sizes and weights
3. Supporting: Smaller sizes, regular weights

### Line Height
- **Headings**: 1.2 - 1.3 (tighter for impact)
- **Body Text**: 1.5 - 1.6 (more space for readability)
- **Code**: 1.4 - 1.5

### Line Length
- Optimal line length: 50-75 characters
- Maximum line length: 90 characters
- Use appropriate column widths for readability

### Spacing
- **Paragraph Spacing**: 1em between paragraphs
- **Section Spacing**: 2-3em between major sections
- **Letter Spacing**: Normal for body text, slight increase (0.05em) for headings

## Accessibility

- Minimum font size: 14px for body text
- Maintain proper contrast ratios (see Color Palette)
- Never use all caps for long text passages
- Ensure text remains readable when zoomed to 200%

## Web Implementation

```css
/* Headings */
h1, h2, h3, h4 {
  font-family: 'Montserrat', sans-serif;
}

/* Body */
body, p, li {
  font-family: 'Open Sans', sans-serif;
  font-size: 16px;
  line-height: 1.5;
}

/* Code */
code, pre {
  font-family: 'Source Code Pro', monospace;
}
```

---

Consistent typography helps create a cohesive brand experience across all touchpoints.
