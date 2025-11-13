# Viatach A/S - UI Elements

Specifikationer for brugergrænseflade elementer der følger Viatach brand guidelines.

## Knapper (Buttons)

### Primær Knap (Primary CTA)

**Visual:**
- **Baggrund:** `#70BBFF` (Viatach Blue)
- **Tekst:** `#000000` (Sort)
- **Font:** Roboto Bold (700)
- **Font Size:** 16px
- **Border:** Ingen
- **Border Radius:** 4px
- **Padding:** 12px 24px
- **Letter Spacing:** 0.05em

**Hover State:**
- **Baggrund:** `#5AA8E6` (Darkened blue)
- **Transform:** `scale(1.02)`
- **Transition:** `all 0.2s ease`

**Active/Pressed:**
- **Baggrund:** `#4A98D6`
- **Transform:** `scale(0.98)`

**Disabled:**
- **Baggrund:** `#555555`
- **Tekst:** `#999999`
- **Cursor:** `not-allowed`

### Sekundær Knap (Secondary CTA)

**Visual:**
- **Baggrund:** `#000000` (Transparent eller sort)
- **Tekst:** `#9AD038` (Viatach Green)
- **Font:** Roboto Bold (700)
- **Border:** `1px solid #9AD038`
- **Border Radius:** 4px
- **Padding:** 12px 24px

**Hover State:**
- **Baggrund:** `#9AD038`
- **Tekst:** `#000000`
- **Border:** `1px solid #9AD038`

### Ghost/Text Knap

**Visual:**
- **Baggrund:** Transparent
- **Tekst:** `#70BBFF`
- **Font:** Roboto Medium (500)
- **Border:** Ingen
- **Underline on hover**

## Input Felter

### Text Input

**Visual:**
- **Baggrund:** `#000000`
- **Tekst:** `#FFFFFF`
- **Font:** Roboto Regular (400)
- **Font Size:** 16px
- **Border:** `1px solid #555555`
- **Border Radius:** 4px
- **Padding:** 10px 12px

**Focus State:**
- **Border:** `2px solid #70BBFF`
- **Outline:** Ingen (fjern default browser outline)
- **Box Shadow:** `0 0 0 3px rgba(112, 187, 255, 0.1)`

**Error State:**
- **Border:** `2px solid #FF4444`
- **Helper text color:** `#FF4444`

**Placeholder:**
- **Color:** `#555555`
- **Font Style:** italic (optional)

### Textarea

Samme som Text Input, men:
- **Min Height:** 100px
- **Resize:** vertical

### Select Dropdown

**Visual:**
- Samme som Text Input
- **Arrow icon:** Custom SVG i `#70BBFF`
- **Dropdown menu baggrund:** `#1A1A1A` (lidt lysere end sort)
- **Dropdown option hover:** `#2A2A2A` med `#70BBFF` tekst

## Kort (Cards)

### Standard Card

**Visual:**
- **Baggrund:** `#0A0A0A` (Very dark gray, ikke helt sort)
- **Border:** `1px solid #1A1A1A`
- **Border Radius:** 8px
- **Padding:** 24px
- **Box Shadow:** `0 4px 6px rgba(0, 0, 0, 0.3)`

**Hover State:**
- **Border:** `1px solid #70BBFF`
- **Box Shadow:** `0 8px 12px rgba(112, 187, 255, 0.2)`
- **Transform:** `translateY(-2px)`
- **Transition:** `all 0.3s ease`

### Highlighted Card (Featured)

**Visual:**
- Samme som Standard Card
- **Border:** `2px solid #70BBFF`
- **Background:** Linear gradient overlay: `linear-gradient(135deg, rgba(112, 187, 255, 0.05) 0%, transparent 100%)`

## Notifikationer

### Success Notification

**Visual:**
- **Baggrund:** `rgba(154, 208, 56, 0.1)` (Green med transparens)
- **Border Left:** `4px solid #9AD038`
- **Tekst:** `#FFFFFF`
- **Icon:** Checkmark i `#9AD038`

### Error Notification

**Visual:**
- **Baggrund:** `rgba(255, 68, 68, 0.1)`
- **Border Left:** `4px solid #FF4444`
- **Tekst:** `#FFFFFF`
- **Icon:** X eller warning i `#FF4444`

### Info Notification

**Visual:**
- **Baggrund:** `rgba(112, 187, 255, 0.1)` (Blue med transparens)
- **Border Left:** `4px solid #70BBFF`
- **Tekst:** `#FFFFFF`
- **Icon:** Info "i" i `#70BBFF`

## Navigation

### Top Navigation Bar

**Visual:**
- **Baggrund:** `#000000` eller `rgba(0, 0, 0, 0.95)` (med backdrop blur)
- **Height:** 64px
- **Border Bottom:** `1px solid #1A1A1A`
- **Logo:** Viatach logo (hvid variant)
- **Links:** `#F0F0F0`, hover til `#70BBFF`

### Sidebar Navigation

**Visual:**
- **Baggrund:** `#0A0A0A`
- **Width:** 240px
- **Border Right:** `1px solid #1A1A1A`
- **Active link:** `#70BBFF` med left border `3px solid #70BBFF`
- **Hover:** Baggrund `#1A1A1A`

## Tabeller

### Data Table

**Visual:**
- **Header baggrund:** `#0A0A0A`
- **Header tekst:** `#FFFFFF`, Roboto Medium
- **Border:** `1px solid #1A1A1A`
- **Row hover:** Baggrund `#0A0A0A`
- **Alternating rows:** Optional, `#050505` for even rows
- **Cell padding:** 12px 16px

## Badges & Tags

### Badge

**Visual:**
- **Baggrund:** `#70BBFF`
- **Tekst:** `#000000`
- **Font Size:** 12px
- **Font:** Roboto Bold
- **Border Radius:** 12px (pill shape)
- **Padding:** 4px 10px

### Tag (Outline)

**Visual:**
- **Baggrund:** Transparent
- **Tekst:** `#70BBFF`
- **Border:** `1px solid #70BBFF`
- **Font Size:** 12px
- **Border Radius:** 4px
- **Padding:** 4px 8px

## Loading States

### Spinner

**Visual:**
- **Color:** `#70BBFF`
- **Size:** 32px (default)
- **Border width:** 3px
- **Animation:** Smooth rotation

### Skeleton Loader

**Visual:**
- **Baggrund:** `#0A0A0A`
- **Shimmer:** Linear gradient animation med `#1A1A1A`
- **Border Radius:** Match element being loaded

## Spacing System

```css
--spacing-xs: 4px;
--spacing-sm: 8px;
--spacing-md: 16px;
--spacing-lg: 24px;
--spacing-xl: 32px;
--spacing-2xl: 48px;
--spacing-3xl: 64px;
```

## Elevation (Box Shadows)

```css
--shadow-sm: 0 1px 3px rgba(0, 0, 0, 0.5);
--shadow-md: 0 4px 6px rgba(0, 0, 0, 0.4);
--shadow-lg: 0 8px 12px rgba(0, 0, 0, 0.3);
--shadow-xl: 0 16px 24px rgba(0, 0, 0, 0.2);

/* Colored shadows for emphasis */
--shadow-blue: 0 8px 16px rgba(112, 187, 255, 0.3);
--shadow-green: 0 8px 16px rgba(154, 208, 56, 0.3);
```

## Transitions

```css
--transition-fast: 0.15s ease;
--transition-normal: 0.3s ease;
--transition-slow: 0.5s ease;
```
