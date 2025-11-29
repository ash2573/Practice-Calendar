# Mini Calendar

This small front-end project (Practice-Calendar) is a simple mini calendar built to learn and explore practical implications of web development concepts such as DOM manipulation, the JavaScript `Date` API, and responsive styling with CSS.

## Purpose

- **Learning goal:** I built this project to practice real-world skills: reading and formatting dates in JavaScript, updating the DOM, and designing a compact UI with HTML/CSS.
- **Practical implications:** The project demonstrates how to retrieve the current date and present it in a visually appealing, accessible component that can be integrated into larger apps (dashboards, task managers, scheduling UIs).

## Files

- `index.html`: Minimal HTML structure and the calendar container.
- `style.css`: Styles for layout, colors, and typography.
- `app.js`: JavaScript that reads the current date and updates the DOM elements (`date`, `day`, `month`, `year`).

## Features

- Shows current day of the week.
- Shows current date with leading zero when needed (e.g., `01`).
- Shows month abbreviation and full year.
- Clean, compact card-style UI that can be reused.

## How to run

1. Open `index.html` directly in your browser by double-clicking the file, or serve the folder with a simple HTTP server (recommended for development).

PowerShell (from the project folder):

```powershell
python -m http.server 8000
# or, if using Python 2
# python -m SimpleHTTPServer 8000
```

Then open `http://localhost:8000` in your browser.

## How it works (brief)

- `app.js` uses `new Date()` to get the current date and time.
- It maps the numeric weekday and month values to readable strings and writes them into the DOM using `element.innerHTML`.
- `style.css` positions the calendar as a centered card and styles the left/right halves for contrast.

## Customization ideas / Next steps

- Add clickable controls to navigate days or months.
- Replace month abbreviations with localized names (i18n support).
- Add events/notes per date and persist them (localStorage or backend).
- Add animations (fade/slide) when the date updates.
- Make it responsive to smaller screens and accessible (ARIA labels, keyboard support).

## License

This project is for learning and personal use. Feel free to reuse or adapt the code.

---

If you want, I can extend this README with screenshots, contribution notes, or a short demo GIF. Want me to add any of those?
