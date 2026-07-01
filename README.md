Single-file email template with embedded styles and markup for maximum email compatibility.

---

## Core Logic

### Layout System

The template is built entirely with nested HTML tables to ensure consistent rendering across email clients, including legacy Outlook versions.

---

### Responsive Behavior

- Desktop: fixed 600px centered layout
- Mobile: stacked columns, full-width images
- Media queries handle padding and column behavior

---

### Dark Mode Support

Uses `prefers-color-scheme: dark` to adjust:

- Background colors
- Text colors
- Section contrast for readability

---

### Outlook Compatibility

Includes:

- Conditional MSO/IE comments
- Table-based rendering instead of modern layout systems
- Inline styles for guaranteed email support

---

## Email Sections

### 1. Header
- Centered logo
- Divider line

---

### 2. Hero Section
- Intro text
- Main headline
- Featured image
- Description text
- Primary CTA button (“Update Now”)

---

### 3. Product Section
- 2-column product grid
- Product image
- Title and price
- CTA button (“Buy”)

---

### 4. Footer
- Copyright text
- Contact email
- Social media icons row

---

## Performance Notes

- No external dependencies (except fonts)
- Minimal CSS for email safety
- Inline styling for maximum compatibility
- Lightweight single-file structure

---

## Limitations

- No JavaScript support (email restrictions)
- Layout depends on tables (not modern CSS)
- Some styling limited by email clients
- Font rendering depends on client support

---

## Future Improvements

- Convert to MJML for easier maintenance
- Dynamic product injection system
- A/B testing variants
- AMP Email version
- Modular email components

---

---

## Author

Dmytro  
Frontend Developer (React / TypeScript)
