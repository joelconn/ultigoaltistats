---
title: Support
---

# Support & Contact

Need help with UltiGoaltiStats? Start with the guides built into the app, or email me at **[ultigoaltistats@gmail.com](mailto:ultigoaltistats@gmail.com)**.

## Built-in help

1. Open the app.
2. Tap the **Help (?)** button in the toolbar on the Teams screen.
3. Pick a guide:
   - **Getting Started**: quick start and feature overview
   - **Google Sheets Setup**: connecting your Google account for spreadsheet export
   - **GitHub Pages Setup**: publishing your stats as a website
   - **Troubleshooting**: fixes for common problems
   - **What's New**: recent changes
   - **Contact & Support**: send a bug report, feature idea or question

Tap the **(i)** button on any stats screen to see what each stat abbreviation means.

## Common issues

### Google Sheets export doesn't work

- **"No Google Client ID configured"**: Google export needs a one-time setup. Follow **Help → Google Sheets Setup** in the app, then tap **⚙ Setup** on the export screen and add your Client ID.
- **Signed in to the wrong account**: sign out of Google in the app and sign in again with the right account.
- **Can't find the spreadsheet**: each export creates a **new** spreadsheet in your Google account, named like *Team vs Opponent – Sep 27, 2026* (or *Team – Lifetime Stats*). Look for it in Google Sheets or Google Drive under that name. After exporting, the app shows a link that opens it directly.
- **Sign-in expired or access was revoked**: sign out and sign in again.

### GitHub Pages site isn't updating

1. Check that your GitHub settings in the app are filled in: repository owner, repository name, branch and a personal access token.
2. Make sure the token hasn't expired and can write to that repository (for a fine-grained token, **Contents: Read and write**).
3. Make sure GitHub Pages is turned on for the repository and is set to deploy from the same branch.
4. GitHub can take a minute or two to rebuild the site. Then hard-refresh your browser (**Cmd+Shift+R** on Mac, **Ctrl+Shift+R** on Windows).

To set up publishing on another device that isn't signed in to the same iCloud account, use the export/import settings option in the app's GitHub settings. The copied settings string includes your token, so treat it like a password.

### Player names or stats are missing

1. Make sure the players are on the team roster and marked **Active**.
2. Make sure a game has been started and a lineup selected for the point.
3. If something still looks wrong, close and reopen the app.

## Bug reports & feature requests

I'd love to hear from you. Email **[ultigoaltistats@gmail.com](mailto:ultigoaltistats@gmail.com)** with a subject like:

- "Bug: [short description]". Include your app version, your device, and the steps that cause the problem. A screenshot helps a lot.
- "Feature request: [your idea]"
- "Question: [your question]"

I usually reply within a few days.

## Privacy

UltiGoaltiStats doesn't collect your data. Everything stays on your device unless you choose to export it to your own Google or GitHub account. Read the full [Privacy Policy](privacy-policy.html).
