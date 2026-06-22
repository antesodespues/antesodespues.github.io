# Antes o Después

**Educational timeline game about the history of women's rights and gender equality.**

🌐 [antesodespues.app](https://antesodespues.app)

---

## What is it?

Antes o Después is a free, browser-based timeline game inspired by Asmodee's *Timeline*. Players place cards in chronological order on a growing timeline. Each card represents a real milestone — a law, a movement, a pioneering figure, or a cultural moment — related to the conquest of gender equality.

The game has two modes:
- **Explore** — browse all 79 cards by category, flip them to reveal dates and descriptions
- **Play** — build a growing timeline by placing cards in the right chronological position

### Game features
- 79 cards across 8 thematic categories
- 3 game lengths: Exprés (16 cards), Media (40 cards), Extendida (up to 80 cards) — desktop only; mobile is Exprés only
- Category selection for each game
- Optional countdown timer (10 seconds per card) — desktop only
- Session statistics: streak, accuracy, breakdown by category and decade
- Light/dark mode
- Fully playable on mobile (portrait mode)

### Categories
1. Mujeres pioneras (Pioneering women)
2. Avances legislativos (Legislative advances)
3. Movimientos sociales (Social movements)
4. Cuerpos y salud (Bodies and health)
5. Violencia machista y resistencias (Gender-based violence and resistance)
6. Cultura y representación (Culture and representation)
7. Deporte e igualdad (Sport and equality)
8. Ciencia y tecnología con enfoque de género (Science and technology with a gender lens)

---

## Built with

- Pure HTML, CSS and JavaScript — no frameworks, no dependencies
- [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (Google Fonts)
- [EmailJS](https://www.emailjs.com/) for the contact form
- [Google Analytics 4](https://analytics.google.com/) for usage tracking

---

## Project structure

```
antesodespues.github.io/
├── index.html        # Main game
├── faq.html          # Frequently asked questions
├── contacto.html     # Contact page
├── guia.html         # Educator's guide
├── proyecto.html     # About the project (coming soon)
├── bibliografia.html # Bibliography (coming soon)
└── README.md
```

---

## Run locally

No setup needed. Just open `index.html` in any modern browser.

```bash
git clone https://github.com/antesodespues/antesodespues.github.io.git
cd antesodespues.github.io
open index.html
```

---

## Why does this exist?

This project was born as a university assignment and grew into something bigger. The goal is simple: make the history of gender equality more accessible, memorable and fun — especially for educational settings.

It's a non-profit, ad-free project made with care. If you use it in your classroom or workshop, I'd love to hear about it.

---

## Mobile experience

The game is fully playable on mobile (portrait mode). The mobile version has been specifically optimized and differs from desktop in several ways:

**Header**
- Both subtitles hidden to reduce visual noise
- "Beta" badge hidden
- More compact padding
- Hamburger menu fixed to top-right corner (doesn't overlap the title)

**Filters**
- Collapsed behind a "Filter by category" toggle button (desktop: always visible)

**Explore mode**
- 3-column card grid (desktop: flexible wrap)
- Card front shows title only — badge, category label and hint hidden
- Card back shows description only — no repeated title or hint
- Tapping a card opens a full detail modal (title, description, year, category) instead of flipping — flip animation is not used on mobile

**Play mode**
- Card placement uses a **tap-to-place** mechanic: tap the golden card to select it, then tap the gap where you want to place it on the timeline (desktop uses drag & drop)
- Only Exprés mode available (16 cards) — duration selector skipped
- Countdown timer disabled
- "Timeline" and "Card to place" labels hidden to save space
- Reduced spacing throughout
- Scorebar shows only 2 metrics: Aciertos (correct) and Racha (streak) — desktop shows 6
- Instructions text adapted to describe the tap-to-place mechanic

The full statistics panel remains available in both versions.

---

## Contributing

Found an error in a date or description? Have a suggestion for a new card? Open an issue or write to [paula@antesodespues.app](mailto:paula@antesodespues.app).

---

## License

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) — © 2026 Antes o Después

Inspired by *Timeline* by [Asmodee](https://www.asmodee.es/).
