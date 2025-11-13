# Viatach Logo Assets

This directory contains Viatach A/S logo variants for use in branded materials.

## Logo Files

Place your logo files in this directory with the following naming convention:

### Required Logo Variants

1. **viatach-logo-primary.svg** (or .png)
   - Full color logo for use on light/white backgrounds
   - Recommended format: SVG (vector) or PNG (min 500px width)
   - Use cases: White backgrounds, light colored materials

2. **viatach-logo-white.svg** (or .png)
   - White/light version for use on dark/black backgrounds
   - Recommended format: SVG (vector) or PNG with transparency
   - Use cases: Black backgrounds (#000000), dark hero sections, footers

### Optional Logo Variants (if available)

3. **viatach-logo-icon.svg** (or .png)
   - Icon-only version (without text)
   - For use in favicons, social media, small spaces
   - Recommended size: Square aspect ratio, min 512x512px

4. **viatach-logo-horizontal.svg** (or .png)
   - Horizontal lockup version
   - For use in navigation bars, email signatures

## File Format Recommendations

### SVG (Preferred)
- Scalable to any size without quality loss
- Smaller file size
- Best for web and digital use
- Ensure all text is converted to outlines/paths

### PNG (Acceptable)
- High resolution: minimum 1000px width
- Transparent background (for logo-white variant)
- 24-bit PNG with alpha channel
- File size: keep under 200KB if possible

## Usage Guidelines

### Logo Placement
- Minimum clear space: Equal to the height of the "V" in Viatach
- Never stretch or distort the logo
- Maintain aspect ratio at all times

### Logo Colors
When using the primary color logo, ensure:
- Background provides sufficient contrast
- Logo is clearly visible and legible
- Brand colors are accurately reproduced (see color-palette.md)

### Logo on Black Background
- Always use the white/light logo variant (logo-white)
- Ensure sufficient contrast ratio (minimum 4.5:1)
- Consider adding subtle glow or shadow if needed for visibility

## Integration with Skill

Once logos are added, they can be referenced in:

### HTML/Web Projects
```html
<!-- Primary logo (light backgrounds) -->
<img src="assets/logo/viatach-logo-primary.svg" alt="Viatach Logo" height="40">

<!-- White logo (dark backgrounds) -->
<img src="assets/logo/viatach-logo-white.svg" alt="Viatach Logo" height="40">
```

### Email Signatures
Update the email signature template (email-signature.html) to reference the actual logo:
```html
<img src="path/to/viatach-logo-white.svg" alt="Viatach Logo" height="40">
```

### Presentations
- Export logos as PNG (transparent background)
- Use white logo on dark slides
- Use primary logo on light slides

## Current Status

⚠️ **Logos Not Yet Added**

Please add your logo files to this directory following the naming conventions above.

After adding logos:
1. Commit the files to git
2. Push to the remote branch
3. Optionally: Re-package the skill using `scripts/package_skill.py`

## Questions?

If you need help with:
- Logo file formats
- Exporting from design software
- Integration into branded materials

Contact the Viatach marketing team or ask Claude for assistance.
