# Privacy Policies & Terms of Service

Hosted Privacy Policy and Terms of Service pages for all apps/products, published via GitHub
Pages so each app can point its Play Store / App Store listing at a stable public URL.

## Convention for adding a new app

1. Create a new folder at the repo root, named with the app's slug (lowercase, hyphenated —
   e.g. `gratuity-eosb-calculator`).
2. Inside it, add `privacy-policy.html` and `terms-of-service.html`, copying the structure of an
   existing app's pages (same `<head>`, same `assets/style.css` reference one level up, same
   `doc-nav` block linking the two pages to each other).
3. Add an entry to `index.html` at the repo root linking to the new pages.
4. Keep `assets/style.css` app-agnostic — no per-app branding there. Each page's `<h1>` and emoji
   in `app-header` is where the app's identity goes.
5. Before an app is actually published, replace that app's `support@example.com` placeholder with
   a real support email, and double check every factual claim (what data is collected, which ad
   network is used, etc.) actually matches what that app's current build does — these pages are
   legal documents, not boilerplate.

## URLs

Once GitHub Pages is enabled (Settings → Pages → Deploy from branch `main`, root), pages are
served at:

```
https://tousif72.github.io/privacy_policies_and_term_conditions_pages/
https://tousif72.github.io/privacy_policies_and_term_conditions_pages/<app-slug>/privacy-policy.html
https://tousif72.github.io/privacy_policies_and_term_conditions_pages/<app-slug>/terms-of-service.html
```

Use the `privacy-policy.html` URL for the Play Console "Privacy Policy" field (App content →
Privacy policy) and the Data Safety form.
