# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |

## Reporting a Vulnerability

This is a static client-side application with:
- No server-side code
- No database
- No authentication system
- No user accounts
- No sensitive data collection

As such, there are few traditional security concerns. However, if you discover a genuine security issue, please report it by opening an issue on GitHub with:
- Description of the issue
- Steps to reproduce
- Potential impact

**Please do not disclose security issues publicly before they are addressed.**

## General Security Practices

- All data is stored locally in the user's browser (localStorage/IndexedDB)
- No third-party scripts are loaded except optional privacy-friendly analytics
- The service worker only caches the app's own static assets
- No external API calls are made

---

*Last updated: March 2026*
