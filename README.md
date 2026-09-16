# TestMine 🧪

**Turn code into tests** — Generate unit tests from your code with AI.

## What it does

Paste your code and pick a framework — TestMine writes unit tests covering the happy path and edge cases. Powered by Pollinations.

- **Connect Pollen** → approve the consent screen → every request is paid from **your own** Pollen balance (default budget 5, valid 7 days, revocable anytime from https://enter.pollinations.ai/keys).
- Free tier: `openai/gpt-5.4-nano` · Premium toggle: `openai/gpt-5.5`.

## Options

- **Framework:** `Jest (JavaScript)/Pytest (Python)/JUnit (Java)/Go test/Mocha (JS)/Vitest (JS/TS)`
## Stack

- Static single-file frontend (no build step), deployed on GitHub Pages.
- Pollinations [Connect User Wallets / BYOP](https://github.com/pollinations/pollinations/blob/main/BRING_YOUR_OWN_POLLEN.md) OAuth PKCE flow — the app never touches your secret key.
- Scoped keys live in `sessionStorage` only, never localStorage/logs/URLs.

## Links

- **Live app:** https://fadyabohamza-netizen.github.io/testmine/
- Source: https://github.com/fadyabohamza-netizen/testmine
- App key (publishable, earnings enabled): `pk_eBVurnM8LCAUB32i`
- Powered by [Pollinations](https://gen.pollinations.ai) · Author: [fadyabohamza-netizen](https://github.com/fadyabohamza-netizen)
