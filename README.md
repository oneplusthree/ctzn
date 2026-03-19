# Canadian Citizenship Practice Test

A Progressive Web App (PWA) for practicing the Canadian citizenship exam, based on the official "Discover Canada: The Rights and Responsibilities of Citizenship" study guide.

## Disclaimer

**This is a personal hobby project for educational purposes only.**

- This app is **NOT** affiliated with, endorsed by, or connected to Immigration, Refugees and Citizenship Canada (IRCC) or the Government of Canada.
- Use at your own discretion. No warranty is provided.
- Questions are based on the publicly available official study guide.

See [DISCLAIMER.md](DISCLAIMER.md) for full legal notice.

## Features

- 100 practice questions covering all topics from Discover Canada
- 45-minute timed tests (matching real exam format)
- Progress auto-saved - resume tests anytime
- Track scores and history with full question details
- Detailed answer review - incorrect answers shown first
- Spaced repetition - frequently missed questions appear more often
- All data stored locally on your device

## Test Format

- 20 random questions per test
- 4 multiple choice options per question
- 75% passing score (15/20 correct)
- 45-minute time limit
- Auto-advances to next question on selection

## Quick Start

### Live Demo

Visit: https://YOUR_USERNAME.github.io/REPO_NAME/

### Local Development

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/citizenship-test.git
cd citizenship-test

# Serve locally
python -m http.server 8000
# or
npx serve

# Open http://localhost:8000
```

### Install as PWA

1. Open the app in Chrome, Edge, or Safari
2. Click "Add to Home Screen" or use browser menu

## Project Structure

```
/
├── index.html           # Main app (all-in-one HTML)
├── manifest.json        # PWA manifest
├── sw.js               # Service worker
├── js/
│   ├── anime.min.js    # Animation library (local)
│   └── questions.js    # Question bank (100 questions)
├── assets/icons/       # PWA icons
├── .github/workflows/  # GitHub Actions
├── DISCLAIMER.md
├── LICENSE
├── PRIVACY.md
├── CONTRIBUTING.md
├── SECURITY.md
└── README.md
```

## Security

- No external API calls
- No analytics or tracking
- All data stored in browser localStorage
- No server-side code
- HTTPS enforced on GitHub Pages

See [SECURITY.md](SECURITY.md) for details.

## Privacy

- All data stays on your device
- No personal information collected
- No cookies used
- Works completely offline

See [PRIVACY.md](PRIVACY.md) for details.

## Contributing

This project is not accepting contributions. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT License - see [LICENSE](LICENSE)
