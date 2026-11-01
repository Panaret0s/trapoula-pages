# Public pages

Static pages Google Play and the App Store need at public addresses:

- `privacy.html`: the Privacy Policy
- `delete-account.html`: how to delete an account without the app

**Before publishing:** replace `[TRADER NAME]`, `[ADDRESS]`, `[SUPPORT EMAIL]` and `[DATE]`. These are drafts: a Cyprus lawyer must review them before public launch (COMPLIANCE.md).

**Hosting:** any static host works. Upload this folder to Netlify Drop, Cloudflare Pages or GitHub Pages. Supabase Edge Functions can't serve these, because they don't send HTML as web pages.

Keep `privacy.html` in step with the app's data use whenever a new service or data type is added..
