# Dominatus Codex

A companion web app for the Warhammer 40,000 (11th edition) **Dominatus** narrative campaign: card browser, campaign tracker, upgrade collection and rules guide.

The app is access-code protected: `index.html` contains only an encrypted copy of the app (AES-256-GCM, key derived from the code with PBKDF2), which the browser decrypts after the code is entered.

Unofficial fan tool; not affiliated with Games Workshop.

A shareable demo with placeholder content (no access code) lives in `demo/`.
