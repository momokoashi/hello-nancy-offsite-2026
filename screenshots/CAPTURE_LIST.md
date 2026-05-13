# Screenshots to Capture

Each setup slide has 2 screenshot slots waiting for real images. Capture from your actual flow (login state varies, so generic public screenshots aren't useful here) and drop them into this folder.

## File naming

Save with these exact names — the deck looks for them:

| Slot in deck | File path |
|---|---|
| Meta · Invitation Email | `screenshots/meta-invite.png` |
| Meta · Business Manager Dashboard | `screenshots/meta-bm.png` |
| Claude · Plans & Billing | `screenshots/claude-plans.png` |
| Claude · Code Logged In | `screenshots/claude-code.png` |
| Gemini · AI Studio API Key Page | `screenshots/gemini-key.png` |
| Gemini · Claude Connected | `screenshots/gemini-claude.png` |
| VPN · 1Password Credential Share | `screenshots/vpn-share.png` |
| VPN · Client Connected | `screenshots/vpn-on.png` |
| GitHub · Signup Form | `screenshots/github-signup.png` |
| GitHub · Org Invitation Accepted | `screenshots/github-org.png` |

## To swap a placeholder for the real image

In `index.html`, find the `<div class="shot-slot">` block matching the screenshot. Replace it with:

```html
<div class="shot-slot has-img"><img src="screenshots/meta-invite.png" alt="Meta invitation email"></div>
```

The `.has-img` class strips the dashed border and padding so the image sits clean.

## Capture tips

- **Mask anything sensitive** — credit card last-4, real email addresses except work ones, account balances.
- **1280×800 or 1440×900** is ideal — fits the slot without resizing artifacts.
- **PNG** for sharp UI, **JPG** if file size matters.
- **Crop tight** — chrome (the browser kind), bookmarks bar, etc. don't add anything.

## Capture order suggestion

Easiest path through:
1. GitHub signup → org acceptance (do this first, fast)
2. Claude plans page → Claude Code logged in
3. Gemini AI Studio → first image gen test
4. Meta invitation email → Business Manager
5. VPN share → VPN connected (do last, after Momo sends creds)
