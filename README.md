# BUD launcher

This repository contains the public, stateless iPhone Home Screen launcher for BUD.

- Launcher: https://kanokpongth.github.io/bud-launcher/
- Production app: the existing Google Apps Script deployment linked from index.html
- Icon: https://raw.githubusercontent.com/kanokpongTH/bud-ios-icon/main/apple-touch-icon-180.png

The launcher contains only branding, iOS metadata, and a navigation target. It does not contain financial data, application source, credentials, spreadsheet IDs, or proxy logic.

## Physical iPhone test

1. Open the launcher URL in Safari on the iPhone.
2. Tap Share, then Add to Home Screen.
3. Confirm the name is BUD and inspect the gold background with black BUD icon.
4. Add it, then open the Home Screen icon and confirm it reaches the production BUD app.

## Rollback/removal

To disable the launcher, turn off GitHub Pages in repository Settings > Pages, or delete this repository. The production Apps Script app is independent and remains unchanged.
