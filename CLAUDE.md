# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a **branding guide repository** for Viatach A/S, not a traditional code repository. It contains a comprehensive brand identity and design system packaged as a Claude Code skill, along with reference documentation and ready-to-use templates.

**Repository Structure:**
```
viatach-branding-guide/
├── SKILL.md                    # Main skill definition with workflow instructions
├── README.md                   # Repository overview and usage guide
├── references/                 # Brand reference documentation (markdown)
│   ├── color-palette.md       # Colors: hex, RGB, CSS variables, accessibility
│   ├── typography.md          # Fonts, hierarchies, sizes (desktop/mobile)
│   ├── ui-elements.md         # UI component specs (buttons, inputs, cards, etc.)
│   └── tone-of-voice.md       # Communication guidelines and writing examples
└── assets/                     # Ready-to-use templates and resources
    ├── brand-colors.css       # Complete CSS stylesheet with variables
    ├── email-signature.html   # Email signature template
    └── logo/                  # Logo assets directory (SVG/PNG variants)
```

## Viatach Brand Identity

**Core Visual Identity:**
- Background: `#000000` (Black) - creates luxury, modern, tech-forward foundation
- Primary Color: `#70BBFF` (Viatach Blue) - headings, CTAs, key elements
- Accent Color: `#9AD038` (Viatach Green) - use sparingly for accents
- Text: `#F0F0F0` (Light gray) for readability on black

**Typography:**
- Headings: Montserrat (Bold/Semi-Bold)
- Body: Roboto (Regular/Medium)
- H1: 48px, Bold, `#70BBFF`
- Body: 16px, Regular, `#F0F0F0`

**Brand Values:** Professional, Innovative, Trustworthy, Dynamic

## Working with This Repository

### Understanding the Skill System

The `SKILL.md` file defines a Claude Code skill that can be activated when creating branded content for Viatach. The skill provides:
1. Complete color system with CSS variables
2. Typography guidelines and implementation
3. UI component specifications
4. Tone of voice and messaging framework
5. Ready-to-use templates

**When the skill is activated**, Claude should:
1. Load relevant reference files from `references/` based on the task
2. Apply brand guidelines systematically
3. Use templates from `assets/` as starting points
4. Ensure all designs meet WCAG 2.1 AA accessibility standards

### Common Tasks

#### Updating Brand Guidelines

When modifying brand elements:
1. Update the relevant reference file in `references/`
2. Update `assets/brand-colors.css` if colors change
3. Update `SKILL.md` Quick Reference section if needed
4. Ensure consistency across all files

**Example: Changing primary color**
- Edit `references/color-palette.md` - update hex codes
- Edit `assets/brand-colors.css` - update CSS variables
- Test accessibility ratios (WCAG 2.1 AA minimum)

#### Adding Logo Files

Logo files should be placed in `assets/logo/` following naming conventions in `assets/logo/README.md`:
- `viatach-logo-primary.svg` (or .png) - for light backgrounds
- `viatach-logo-white.svg` (or .png) - for dark backgrounds (#000000)
- `viatach-logo-icon.svg` (optional) - icon-only variant

**Logo requirements:**
- SVG preferred (scalable, smaller size)
- PNG acceptable (min 1000px width, transparent background)
- Never stretch or distort - maintain aspect ratio
- Minimum clear space: equal to height of "V" in Viatach

#### Creating Branded Content

When asked to create branded materials:
1. Read relevant reference files:
   - Visual work: `color-palette.md`, `typography.md`, `ui-elements.md`
   - Written content: `tone-of-voice.md`
2. Use `assets/brand-colors.css` as base stylesheet for web projects
3. Follow the workflow in `SKILL.md` > Instructions section
4. Quality check against the 6-point checklist in `SKILL.md`

#### Modifying Templates

**CSS Template** (`assets/brand-colors.css`):
- Contains CSS custom properties (variables) for all brand colors
- Includes utility classes for buttons, inputs, cards
- Update when adding new colors or UI patterns

**Email Signature** (`assets/email-signature.html`):
- Replace placeholders: [NAVN], [JOBTITEL], [EMAIL], [TELEFON]
- Update logo URL to point to actual logo file
- Update social media links as needed

### File Organization

**Reference files are in Danish** because Viatach is a Danish company, but all implementations (CSS, HTML) should use English for technical terms (e.g., CSS variable names, HTML attributes).

**Accessibility is mandatory**: All color combinations must meet WCAG 2.1 AA standards minimum:
- `#000000` / `#FFFFFF`: 21:1 (AAA) ✓
- `#000000` / `#70BBFF`: 8.59:1 (AAA) ✓
- `#000000` / `#9AD038`: 6.74:1 (AA) ✓

### Git Workflow

This repository uses standard git workflow:
- Main branch for stable brand guidelines
- Feature branches (prefixed with `claude/`) for updates
- Commit messages should be clear and descriptive
- Push updates when brand guidelines are modified

**When committing changes:**
- Brand updates: "Update primary color from #70BBFF to #..."
- Logo additions: "Add Viatach logo variants (primary, white)"
- Template changes: "Update email signature template with new contact info"

## Key Principles

1. **Brand consistency over creativity** - Follow guidelines strictly
2. **Accessibility first** - All designs must meet WCAG AA minimum
3. **Black background is foundation** - All Viatach materials use `#000000`
4. **Blue is primary, green is accent** - Use blue prominently, green sparingly
5. **Clear, concise, confident** - Tone of voice in all communications
6. **No code to build/test** - This is documentation, not executable code

## Notes for Claude Code

- **No build/test commands** - This repository contains documentation and templates only
- **No linting/formatting** - Standard markdown and CSS formatting is sufficient
- **Focus on brand accuracy** - When creating content, prioritize adherence to brand guidelines
- **Reference SKILL.md workflow** - Follow the 6-step process defined in SKILL.md when creating branded materials
- **Check accessibility** - Always verify color contrast ratios when modifying colors
- **Preserve Danish content** - Reference files are intentionally in Danish; don't translate them
