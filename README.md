# Gifton Shibu | Data Analyst Portfolio

Modern, dark-themed personal portfolio built with plain HTML/CSS/vanilla JavaScript (no frameworks).

## Live Preview

If you host it somewhere (GitHub Pages, Netlify, etc.), link it here.

## Features

- Dark design system with CSS variables
- Loading screen overlay with fade-out sequence
- Hero section animations:
  - Animated gradient name
  - Typing effect (pure JS)
  - Word-by-word tagline reveal
- Scroll reveal animations using `IntersectionObserver`
- Animated counters when the About stats enter the viewport
- Parallax motion for hero background blobs/photo (using `requestAnimationFrame`)
- Project cards with hover glow/lift effects
- Responsive layout for tablet/mobile/short screens
- Custom cursor for pointer devices (disabled on touch)

## Project Structure

- `index.html` - Page markup + all JavaScript (at the bottom of the file)
- `style.css` - All CSS styling
- `profile photo` - `gifton.jpeg` (place in the same folder)
- `resume` - `resume.pdf` (optional, place in the same folder if you want the resume download links to work)

## Assets You Should Add

- `gifton.jpeg` (required for the hero photo)
- `resume.pdf` (recommended)

If you don't have a resume PDF yet, you can remove/disable the resume links in `index.html` so there are no broken URLs.

## Run Locally

From this folder:

```powershell
cd "C:\Users\DELL\OneDrive\Desktop\Gifton Portfolio"
python -m http.server 5500
```

Open:

- `http://localhost:5500`

## Links

- LinkedIn: https://www.linkedin.com/in/gifton07
- GitHub: https://github.com/Gifton07

## Notes

This project intentionally uses no external UI libraries. Google Fonts are loaded from the stylesheet in `index.html`.

