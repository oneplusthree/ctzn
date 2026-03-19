# Canadian Citizenship Practice Test

A Progressive Web App (PWA) for practicing the Canadian citizenship exam, based on the official "Discover Canada: The Rights and Responsibilities of Citizenship" study guide.

## ⚠️ Disclaimer

**This is a personal hobby project for educational purposes only.**

- This app is **NOT** affiliated with, endorsed by, or connected to Immigration, Refugees and Citizenship Canada (IRCC) or the Government of Canada.
- Use at your own discretion. No warranty is provided.
- Questions are based on the publicly available official study guide.

See [DISCLAIMER.md](DISCLAIMER.md) for full legal notice.

## Features

- 📝 100 practice questions covering all topics from Discover Canada
- ⏱️ 45-minute timed tests (matching real exam format)
- 💾 Progress auto-saved - resume tests anytime
- 📊 Track your scores and history
- 📖 Detailed answer review with explanations
- 📱 Installable as PWA (works offline)
- 🔒 All data stored locally on your device

## Test Format

- 20 random questions per test
- 4 multiple choice options per question
- 75% passing score (15/20 correct)
- 45-minute time limit

## Tech Stack

- Vanilla JavaScript (no framework)
- IndexedDB for data persistence
- Service Worker for offline support
- CSS3 for styling

## Installation

### Option 1: GitHub Pages (Recommended)

This app is designed to work directly from GitHub Pages. Simply host this repository on GitHub Pages.

### Option 2: Local Development

1. Clone the repository
2. Serve with any local server:
   ```bash
   python -m http.server 8000
   # or
   npx serve
   ```
3. Open http://localhost:8000

### Option 3: Install as PWA

1. Open the app in a modern browser (Chrome, Edge, Safari, Firefox)
2. Click "Add to Home Screen" when prompted or use browser menu

## Project Structure

```
/
├── index.html           # Main HTML entry point
├── manifest.json        # PWA manifest
├── sw.js               # Service worker
├── css/
│   └── styles.css      # Styles
├── js/
│   ├── app.js          # Main application logic
│   ├── questions.js    # Question bank (100 questions)
│   ├── router.js       # Simple SPA router
│   └── storage.js      # IndexedDB wrapper
├── assets/
│   └── icons/          # PWA icons
├── DISCLAIMER.md       # Legal disclaimer
├── LICENSE             # MIT License
├── PRIVACY.md          # Privacy policy
├── CONTRIBUTING.md     # Contribution guidelines
├── SECURITY.md         # Security policy
└── README.md           # This file
```

## Data Storage

All data is stored locally in your browser using IndexedDB:
- Test progress and answers
- Completed test results
- Personal stats

**No data is sent to any server.**

## Contributing

This project is not accepting contributions. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Security

This is a static client-side app with no server or database. See [SECURITY.md](SECURITY.md) for details.

## License

MIT License - see [LICENSE](LICENSE)

---

*Good luck with your citizenship test preparation! 🍁*
