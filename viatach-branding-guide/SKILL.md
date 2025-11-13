---
name: viatach-branding-guide
description: This skill should be used when creating branded content, designs, or materials for Viatach A/S. It provides comprehensive brand guidelines including colors, typography, UI elements, tone of voice, and ready-to-use templates.
license: Complete terms in LICENSE.txt
---

# Viatach Branding Guide

Comprehensive brand guidelines and design system for Viatach A/S, providing everything needed to create consistent, professional branded materials.

## About This Skill

This skill equips Claude with Viatach A/S's complete brand identity and design system. Use this skill when creating any branded content—from websites and presentations to emails and marketing materials—to ensure consistency with Viatach's modern, tech-forward visual identity.

### What This Skill Provides

1. **Complete Color System** - Primary colors, neutrals, semantic colors, and CSS variables
2. **Typography Guidelines** - Font families, hierarchies, sizes, and web font integration
3. **UI Components** - Buttons, inputs, cards, notifications with exact specifications
4. **Tone of Voice** - Communication principles, messaging framework, and writing examples
5. **Ready-to-Use Templates** - CSS stylesheet and email signature template
6. **Logo Assets** - Directory for Viatach logo variants (primary and white versions)
7. **Design Principles** - Spacing, shadows, transitions, and accessibility guidelines

## When to Use This Skill

Activate this skill when the user requests:

- "Create a website/landing page for Viatach"
- "Design branded materials following Viatach guidelines"
- "What are Viatach's brand colors?"
- "Generate a presentation/email template for Viatach"
- "Write marketing copy in Viatach's voice"
- "Style this UI component according to Viatach's design"

## Brand Core Values

Viatach A/S embodies:
- **Professional** - Reliable and expert
- **Innovative** - Forward-thinking and tech-savvy
- **Trustworthy** - Dependable and credible
- **Dynamic** - Agile and adaptable

The visual identity reflects these values through:
- **Black background (#000000)** - Luxury, modernity, technology
- **Cool Blue (#70BBFF)** - Innovation, trust, primary brand color
- **Lime Green (#9AD038)** - Energy, growth, accent color

## Instructions

### Step 1: Understand the Request

Identify what branded content the user needs:
- **Digital content** (websites, emails, presentations)
- **Marketing materials** (brochures, social media, ads)
- **UI/UX design** (applications, dashboards, interfaces)
- **Written content** (copy, messaging, communications)

### Step 2: Load Relevant Reference Materials

Based on the request type, read the appropriate reference files:

**For visual/design work:**
- Read `references/color-palette.md` for exact color specifications
- Read `references/typography.md` for font families and hierarchies
- Read `references/ui-elements.md` for component specifications

**For written content:**
- Read `references/tone-of-voice.md` for messaging guidelines
- Reference brand values and communication principles

**For quick implementation:**
- Use `assets/brand-colors.css` as base stylesheet
- Use `assets/email-signature.html` for email templates

### Step 3: Apply Brand Guidelines

**Visual Design:**
1. Start with black background (#000000)
2. Use Viatach Blue (#70BBFF) for primary elements (headings, CTAs, emphasis)
3. Use Viatach Green (#9AD038) sparingly for accents and secondary actions
4. Ensure white/light gray text (#F0F0F0) for readability
5. Apply Montserrat for headings, Roboto for body text

**Component Design:**
- Follow exact specifications in `references/ui-elements.md`
- Use consistent spacing from the spacing system
- Apply hover states and transitions
- Include proper accessibility (WCAG AA minimum)

**Written Content:**
- Be clear, concise, and confident
- Focus on solutions and results
- Avoid buzzwords and jargon
- Use active voice and direct language
- Reference tone of voice examples in `references/tone-of-voice.md`

### Step 4: Leverage Templates

**For web projects:**
```html
<!-- Import brand CSS -->
<link rel="stylesheet" href="brand-colors.css">

<!-- Or copy CSS variables from assets/brand-colors.css -->
```

**For email signatures:**
- Copy `assets/email-signature.html`
- Replace placeholders: [NAVN], [JOBTITEL], [EMAIL], [TELEFON]
- Update logo URL and social media links

**For presentations:**
- Use black background with Viatach Blue headings
- Apply typography hierarchy (H1: 48px Montserrat Bold in #70BBFF)
- Limit use of Viatach Green to key CTAs or highlights

### Step 5: Quality Check

Before delivering, verify:

✅ **Colors:** Only using approved brand colors
✅ **Typography:** Montserrat for headings, Roboto for body
✅ **Contrast:** Text is readable (WCAG AA minimum)
✅ **Consistency:** All elements follow UI specifications
✅ **Tone:** Writing is clear, confident, and professional
✅ **Branding:** Logo placement and sizing is appropriate

### Step 6: Provide Implementation Notes

When delivering designs or code:
- Include instructions for Google Fonts import (if web-based)
- Note any dependencies or required assets
- Provide fallback fonts for cross-platform compatibility
- Include accessibility considerations
- Document any customization points

## Reference Files Summary

| File | Contains | Use When |
|------|----------|----------|
| `references/color-palette.md` | All brand colors with hex, RGB, and usage | Designing any visual element |
| `references/typography.md` | Fonts, sizes, weights, hierarchies | Setting up text styles |
| `references/ui-elements.md` | Button, input, card, notification specs | Building UI components |
| `references/tone-of-voice.md` | Writing guidelines, examples, messaging | Creating written content |
| `assets/brand-colors.css` | Complete CSS with variables and utilities | Quick web project start |
| `assets/email-signature.html` | Email signature template | Setting up employee emails |
| `assets/logo/` | Viatach logo variants (primary, white) | Any branded material requiring logo |

## Quick Reference

### Primary Colors
- Background: `#000000`
- Primary (Blue): `#70BBFF`
- Accent (Green): `#9AD038`
- Text: `#F0F0F0`

### Typography
- Headings: Montserrat (Bold/Semi-Bold)
- Body: Roboto (Regular/Medium)
- H1: 48px, #70BBFF
- Body: 16px, #F0F0F0

### CTAs
- Primary button: Blue bg (#70BBFF), black text
- Secondary button: Transparent bg, green border and text (#9AD038)

### Spacing
- XS: 4px, SM: 8px, MD: 16px, LG: 24px, XL: 32px

## Examples

### Example 1: Landing Page Request

**User:** "Create a landing page for Viatach"

**Process:**
1. Read `references/color-palette.md` and `references/typography.md`
2. Use `assets/brand-colors.css` as base
3. Apply black background with blue headings
4. Include CTA button with proper styling
5. Write copy using tone from `references/tone-of-voice.md`

### Example 2: Button Design Request

**User:** "Design a primary CTA button for Viatach"

**Process:**
1. Read `references/ui-elements.md` > Buttons section
2. Apply: Background #70BBFF, text #000000, Roboto Bold
3. Include hover state: #5AA8E6 with scale(1.02)
4. Provide CSS code with proper variables

### Example 3: Marketing Copy Request

**User:** "Write a tagline for Viatach"

**Process:**
1. Read `references/tone-of-voice.md`
2. Apply principles: Clear, confident, solution-focused
3. Reference examples: "We deliver results", "Technology that works"
4. Generate options that embody brand values

## Notes

- **Logo:** Logo files are located in `assets/logo/` directory. Use `viatach-logo-white.svg` on dark backgrounds (#000000) and `viatach-logo-primary.svg` on light backgrounds. See `assets/logo/README.md` for detailed usage guidelines and file naming conventions.
- **Accessibility:** All designs must meet WCAG 2.1 AA standards minimum
- **Responsive:** Consider mobile breakpoints when designing for web
- **Consistency:** When in doubt, prioritize brand consistency over creativity
- **Updates:** If user provides updated brand guidelines, note the changes

## Advanced Usage

### Custom Color Variations

If slight variations are needed (e.g., disabled states, overlays):
- Darken blue: Use `#5AA8E6` (hover) or `#4A98D6` (active)
- Lighten backgrounds: Use `#0A0A0A` for cards
- Transparency: Add alpha channel, e.g., `rgba(112, 187, 255, 0.1)`

### Animation Principles

- Fast transitions: 0.15s for micro-interactions
- Normal transitions: 0.3s for most UI changes
- Slow transitions: 0.5s for page-level animations
- Use `ease` timing function for natural feel

### Grid System

While not explicitly defined, use:
- 12-column grid for desktop layouts
- 8px baseline grid for vertical rhythm
- Max content width: 1200px
- Container padding: 24px (mobile), 48px (desktop)
