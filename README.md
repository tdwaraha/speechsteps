# Speech Steps website (GitHub Pages)

Plain HTML and CSS, no build step. All links are relative, so it works at `https://USERNAME.github.io/REPO/` or on a custom domain.

| Page | File | Use in App Store Connect |
|---|---|---|
| Home | `index.html` | Marketing URL (optional) |
| Support | `support.html` | **Support URL** (required) |
| Privacy policy | `privacy.html` | **Privacy Policy URL** (required) |
| Terms of use | `terms.html` | Optional |

## 1. Fill in three things

Search all files and replace:
- `{{DEVELOPER_NAME}}`: your name or business name, as shown as the seller on the App Store.
- `{{APP_STORE_URL}}`: your app's App Store link (use `support.html` until the app is live).
- `YOUR_EMAIL@example.com`: your support email (appears in `support.html`, `privacy.html`, `terms.html`).

Also check "Province of Ontario" in `terms.html`.

## 2. Publish on GitHub Pages

1. Create a public repository (e.g. `speechsteps`) and upload everything in this folder to the root of `main` (including `.nojekyll`).
2. Settings → Pages → Source: "Deploy from a branch", Branch `main`, folder `/ (root)` → Save.
3. After about a minute: `https://USERNAME.github.io/speechsteps/`.

## 3. App Store Connect

- Privacy Policy URL: `https://USERNAME.github.io/speechsteps/privacy.html`
- Support URL: `https://USERNAME.github.io/speechsteps/support.html`
- App Privacy: "Data Not Collected".

The policy matches the app as built (no networking, accounts, ads or analytics). If you add any of those, update the policy first.
