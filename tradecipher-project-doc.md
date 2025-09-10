# TradeCipher Project Documentation

## Project Overview
**Domain:** tradecipher.in  
**GitHub Repository:** https://github.com/mr5cell/tradecipher  
**Live Site:** https://mr5cell.github.io/tradecipher/  
**Purpose:** Share honest trading insights and market observations with fellow traders  
**Development:** Side project, build slowly  
**Tone:** Personal, minimal, no SEO fluff - trader to trader communication  

## Technical Stack

### Frontend
- HTML5 + CSS3 + Vanilla JavaScript
- No frameworks initially
- Can add complexity later if needed

### Backend (when needed)
- Go (Golang)

### Deployment
- Currently: GitHub Pages (static hosting)
- Future: VPS when backend needed

## Design Direction

### Inspiration: Zerodha Kite
- Clean, minimal interface
- Focus on clarity
- Professional look
- No decorative elements or emojis
- Typography-focused design

### Color Palette (Kite-inspired)
```css
--primary: #387ed1;        /* Blue */
--success: #00d09c;        /* Green */
--danger: #eb5b3c;         /* Red */
--text-primary: #44475b;   /* Dark gray */
--text-secondary: #7c7e8c; /* Light gray */
--bg-primary: #ffffff;     /* White */
--bg-secondary: #fafafa;   /* Light gray */
--border: #e0e0e0;         /* Border gray */
```

## Current Project Structure
```bash
tradecipher/
├── index.html          # Minimal WIP landing page
├── css/
│   └── main.css       # Clean, Kite-inspired styles
├── js/
│   └── main.js        # Placeholder JS file
├── .gitignore         # Git ignore file
└── assets/
    └── images/        # Empty, for future use
```

## Current Implementation

### Landing Page (index.html)
- Simple header with "TradeCipher" branding
- Main content area with:
  - "Work in progress" status text
  - Headline: "Trading insights. No noise."
  - Subtitle about building a space for market observations
- Truly minimal design - no cards, no animations, no emojis
- Clean typography on white background

### Styling (main.css)
- System font stack for clean rendering
- Subtle borders (#e0e0e0)
- Generous whitespace
- Mobile responsive
- No unnecessary animations or effects
- Focus on readability

## Git & Deployment Setup

### Repository
- Initialized with git
- Main branch (not master)
- Connected to GitHub: mr5cell/tradecipher
- Using GitHub CLI (gh) for authentication

### GitHub Pages Configuration
- Deployed from main branch root (/)
- HTTPS enforced
- Live at: https://mr5cell.github.io/tradecipher/
- Will eventually point to custom domain: tradecipher.in

## Future Components to Build

1. **Navigation Bar** - Simple horizontal nav
2. **Strategy Posts** - Individual strategy pages
3. **Trade Journal** - Real trades with entry/exit points
4. **Market Notes** - Daily/weekly observations
5. **Filter/Search** - Simple filtering by strategy type

## Development Philosophy
- Keep it simple and honest
- No marketing speak or SEO optimization
- Focus on actual trading content
- Build trust through transparency (show losses too)
- Gradual improvements based on actual needs

## Next Steps
1. Add actual trading content/strategies
2. Create individual strategy pages
3. Set up custom domain (tradecipher.in)
4. Add basic navigation between pages
5. Consider adding a simple blog/journal section

---

*Last Updated: September 10, 2025*  
*Version: 2.0 - Simplified to true minimal design*