# Classic Ryde Driver Newsletter

Landing page for the monthly Classic Ryde driver newsletter, in 11 languages.

**Live page:** https://mclassicryde.github.io/Newsletter/
**Hosting:** GitHub Pages, branch `main`, root folder.

## What is in this repo

| File | Purpose |
|---|---|
| `index.html` | The newsletter landing page. One `<section id="xx">` per language. |
| `logo.png` | Classic Ryde logo. Used by the page and the email. |
| `ctg-logo.png` | CTG logo (CTG feature box). |
| `sentry-logo.png` | Sentry logo (Sentry feature box). |
| `README.md` | This file. |

The email sent through MailerLite loads these images by URL, so **do not rename or delete them** while a campaign that uses them is live.

## Languages

English (en, default), Spanish (es), Chinese (zh), Russian (ru), Bengali (bn), Haitian Creole (ht), Korean (ko), Arabic (ar, RTL), Urdu (ur, RTL), French (fr), Punjabi (pa).

The email's language buttons link to `https://mclassicryde.github.io/Newsletter/#xx`, for example `#es`.

## Monthly update

1. Build the new `index.html` and email (the content is prepared outside this repo).
2. On GitHub: **Add file → Upload files**, drag in `index.html` and any new images, then **Commit changes** to `main`. Files with the same name are replaced.
3. Wait about 1 minute for GitHub Pages to redeploy.
4. Open the live page and check: the month is correct, every language button works, and Arabic and Urdu read right to left.
5. Only then send the MailerLite campaign (after approval in Slack #newsletter-inputs).

## Rules

- Do not change the page URL, the 11 languages, or the language bar and its JavaScript.
- Keep Arabic and Urdu sections as `dir="rtl"`.
- Keep numbers, phone numbers, addresses, URLs, and driver names and numbers exactly the same in every language.
- No long dashes in the text.
- Never send the newsletter to drivers without approval.

## Contact

Classic Ryde · media@classicryde.com · 718-777-7800
276 Greenpoint Ave, Suite 251, Brooklyn, NY 11222
