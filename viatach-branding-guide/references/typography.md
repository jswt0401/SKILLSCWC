# Viatach A/S - Typografi

Vi vælger en sans-serif skrifttype, der er klar, moderne og læsbar på sort baggrund.

## Primære Skrifttyper

### Hovedskrifttype: Montserrat
- **Anvendelse:** Overskrifter (Bold/Extra Bold) og vigtige tal
- **Karakteristika:** Giver et solidt, geometrisk præg
- **Download:** Google Fonts - https://fonts.google.com/specimen/Montserrat
- **Fallback:** 'Poppins', 'Inter', 'Arial Black', sans-serif

### Brødtekst: Roboto
- **Anvendelse:** Brødtekst og UI-elementer
- **Karakteristika:** Kendt for høj læsbarhed
- **Download:** Google Fonts - https://fonts.google.com/specimen/Roboto
- **Fallback:** 'Lato', 'Open Sans', 'Arial', sans-serif

## Typografi Hierarki

| Niveau | Skrifttype | Vægt (Weight) | Farve | Anvendelse |
|--------|-----------|---------------|-------|------------|
| H1 (Overskrift) | Montserrat | Bold (700) | `#70BBFF` | Vigtigste sektionstitler |
| H2 / H3 | Montserrat | Semi-Bold (600) | `#FFFFFF` | Under-sektionstitler |
| H4 / H5 | Montserrat | Medium (500) | `#F0F0F0` | Mindre overskrifter |
| Body (Tekst) | Roboto | Regular (400) | `#F0F0F0` | Brødtekst, paragraffer |
| Body Strong | Roboto | Medium (500) | `#FFFFFF` | Fremhævet tekst |
| CTA (Knap) | Roboto | Bold (700) | `#000000` | Tekst på knapper |
| Small Text | Roboto | Regular (400) | `#555555` | Footer, disclaimers |

## Font Sizes (Desktop)

```css
--font-size-h1: 48px;      /* Hero headlines */
--font-size-h2: 36px;      /* Section titles */
--font-size-h3: 28px;      /* Sub-sections */
--font-size-h4: 22px;      /* Card titles */
--font-size-body: 16px;    /* Body text */
--font-size-small: 14px;   /* Secondary text */
--font-size-tiny: 12px;    /* Footer, captions */
```

## Font Sizes (Mobile)

```css
--font-size-h1-mobile: 32px;
--font-size-h2-mobile: 26px;
--font-size-h3-mobile: 22px;
--font-size-h4-mobile: 18px;
--font-size-body-mobile: 16px;
--font-size-small-mobile: 14px;
```

## Line Height

- **Headings:** 1.2 - 1.3
- **Body text:** 1.6 - 1.8
- **Small text:** 1.4 - 1.5

## Letter Spacing

- **H1:** -0.02em (tighter for large text)
- **H2-H4:** 0em (normal)
- **Body:** 0.01em (slight spacing for readability)
- **Buttons:** 0.05em (increased for emphasis)

## Google Fonts Import

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500;600;700;800&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
```

## CSS Font Stack

```css
font-family: 'Montserrat', 'Poppins', 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
font-family: 'Roboto', 'Lato', 'Open Sans', -apple-system, BlinkMacSystemFont, sans-serif;
```
