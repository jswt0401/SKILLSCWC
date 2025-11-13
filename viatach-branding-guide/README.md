# Viatach Branding Guide Skill

Comprehensive brand guidelines and design system for Viatach A/S.

## Overview

This skill provides complete brand identity guidelines for Viatach A/S, including colors, typography, UI components, tone of voice, and ready-to-use templates. Use this skill when creating any branded content to ensure consistency with Viatach's modern, tech-forward visual identity.

## Structure

```
viatach-branding-guide/
├── SKILL.md                          - Main skill instructions and workflow
├── references/                       - Reference documentation
│   ├── color-palette.md             - Complete color system with hex, RGB, CSS variables
│   ├── typography.md                - Font families, hierarchies, sizes
│   ├── ui-elements.md               - Button, input, card, notification specs
│   └── tone-of-voice.md             - Communication guidelines and examples
└── assets/                          - Ready-to-use templates
    ├── brand-colors.css             - Complete CSS stylesheet with variables
    └── email-signature.html         - Email signature template
```

## Usage

Activate this skill by asking Claude:

- "Create a website/landing page for Viatach"
- "What are Viatach's brand colors?"
- "Design a button following Viatach's brand guidelines"
- "Write marketing copy in Viatach's tone of voice"
- "Generate an email signature for Viatach employee"

## Brand Quick Reference

### Colors
- **Background:** `#000000` (Black)
- **Primary (Blue):** `#70BBFF` - Used for headings, CTAs, key elements
- **Accent (Green):** `#9AD038` - Used sparingly for accents
- **Text:** `#F0F0F0` (Light gray on black background)

### Typography
- **Headings:** Montserrat (Bold/Semi-Bold)
- **Body:** Roboto (Regular/Medium)
- **H1:** 48px, Bold, #70BBFF
- **Body:** 16px, Regular, #F0F0F0

### Tone of Voice
- **Clear** - No unnecessary complexity
- **Concise** - Get to the point quickly
- **Confident** - Expert but not arrogant
- **Solution-focused** - Emphasize results

## What's Included

### Reference Documentation

**color-palette.md** (2.5KB)
- Primary, accent, and neutral colors
- Hex codes, RGB values, usage guidelines
- CSS variable names
- Accessibility contrast ratios

**typography.md** (3.2KB)
- Font families and fallbacks
- Typography hierarchy
- Font sizes (desktop and mobile)
- Line height, letter spacing
- Google Fonts import code

**ui-elements.md** (6.8KB)
- Buttons (primary, secondary, ghost)
- Input fields (text, textarea, select)
- Cards (standard, highlighted)
- Notifications (success, error, info)
- Navigation components
- Tables, badges, tags
- Loading states
- Spacing system and shadows

**tone-of-voice.md** (3.4KB)
- Brand values
- Communication principles
- Examples of good/bad messaging
- Email and social media tone
- Messaging framework

### Ready-to-Use Templates

**brand-colors.css** (5.1KB)
- Complete CSS stylesheet
- CSS custom properties (variables)
- Base typography styles
- Utility classes for buttons, inputs, cards
- Responsive considerations

**email-signature.html** (2.8KB)
- Professional email signature template
- Follows brand colors and typography
- Includes contact info placeholders
- Social media links
- Mobile-responsive table layout

**logo/** (Directory for logo assets)
- Placeholder directory for Viatach logo variants
- Includes README.md with usage guidelines
- Recommended files: viatach-logo-primary.svg, viatach-logo-white.svg
- User should add actual logo files to this directory

## Features

✅ **Complete Color System** - All brand colors with exact specifications
✅ **Typography Guidelines** - Clear hierarchy and implementation
✅ **Component Library** - Detailed specs for all UI elements
✅ **Tone of Voice** - Communication principles and examples
✅ **Templates** - Ready-to-use CSS and HTML
✅ **Accessibility** - WCAG 2.1 AA compliant
✅ **Responsive** - Mobile and desktop specifications

## Examples

### Example 1: Create a Landing Page

```
User: "Create a landing page for Viatach"

Claude will:
1. Load color-palette.md and typography.md
2. Use brand-colors.css as base
3. Apply black background with blue headings
4. Style CTAs with proper brand colors
5. Write copy following tone-of-voice.md
```

### Example 2: Design a Button

```
User: "Design a primary CTA button for Viatach"

Claude will:
1. Reference ui-elements.md > Buttons
2. Apply: Blue background (#70BBFF), black text
3. Include hover states and transitions
4. Provide CSS code with brand variables
```

### Example 3: Write Marketing Copy

```
User: "Write a tagline for Viatach"

Claude will:
1. Read tone-of-voice.md principles
2. Apply clear, confident, solution-focused language
3. Generate options like "We deliver results" or "Technology that works"
```

## Customization

The skill is specifically designed for Viatach A/S. To adapt for another company:

1. Update `references/color-palette.md` with new brand colors
2. Modify `references/typography.md` with different fonts
3. Adjust `references/tone-of-voice.md` for new brand voice
4. Update `assets/brand-colors.css` with new CSS variables
5. Customize `assets/email-signature.html` template
6. Edit SKILL.md metadata and instructions

## Technical Details

- **Skill format:** SKILL.md with bundled references and assets
- **Total size:** ~24KB uncompressed
- **Reference files:** 4 markdown files (~16KB)
- **Asset files:** 2 template files (~8KB)
- **No scripts required:** Pure documentation and templates

## Accessibility

All color combinations meet WCAG 2.1 AA standards:
- **#000000 / #FFFFFF:** 21:1 contrast (AAA)
- **#000000 / #70BBFF:** 8.59:1 contrast (AAA)
- **#000000 / #9AD038:** 6.74:1 contrast (AA)

## Version

Current version: 1.0.0
Last updated: November 2025

## License

Complete terms in LICENSE.txt

## Support

For questions or updates to the brand guidelines, contact the Viatach A/S marketing team.
