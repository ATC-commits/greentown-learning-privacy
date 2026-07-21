# Publish the Greentown Learning privacy page with GitHub Pages

This folder is a complete two-page static site. It uses no cookies, scripts, analytics, fonts, or external assets.

## Before publishing

Review these values in `index.html` and `support.html`:

- Operator name: Aaron Cox
- Contact email: aaron.tcox@icloud.com
- Effective date: July 21, 2026

The policy describes the current school beta. It must be updated before individual/family accounts, subscriptions, public self-registration, advertising, analytics, or additional service providers are launched.

## Publish using only the GitHub website

1. Sign in to GitHub.
2. Create a new **public** repository named `greentown-learning-privacy`.
3. Choose **Add file → Upload files**.
4. Upload `index.html` and `support.html` from this folder. Uploading the README and Markdown source is optional.
5. Commit the files to the `main` branch.
6. Open the repository's **Settings**.
7. In the left sidebar, open **Pages**.
8. Under **Build and deployment**, choose **Deploy from a branch**.
9. Select branch `main` and folder `/ (root)`, then save.
10. Wait a few minutes. GitHub will show the published address.

The URL will normally look like:

`https://YOUR-GITHUB-USERNAME.github.io/greentown-learning-privacy/`

Open the URL in a private/incognito browser window. Confirm that it works without signing in and that the English, Chinese, and support links open correctly.

## Enter the URL in App Store Connect

Use the published root URL as the **Privacy Policy URL**.

You may also use:

`https://YOUR-GITHUB-USERNAME.github.io/greentown-learning-privacy/support.html`

as the optional **User Privacy Choices URL** or later as a support URL.

## Important limitations

This is a practical beta policy based on the current app architecture. It is not a substitute for legal advice. A public mainland-China launch needs additional review for guardian consent, cross-border processing, children's privacy rules, filings, and any applicable AI-generated-content labeling duties.
