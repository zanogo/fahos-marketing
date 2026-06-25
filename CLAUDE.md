# CLAUDE.md

## What this is

A static marketing site deployed to **Firebase Hosting** (free **Spark** tier).

## Source of truth

`public/index.html` is the source of truth for the site. Everything served lives under `public/`.

## Deploy

```bash
firebase deploy --only hosting
```

The default Firebase project (`fahos-marketing`) is set in `.firebaserc`.

## Notes

- Spark (free) tier — keep usage within Hosting's free limits; no Cloud Functions or other paid services.
- No build step: edit files in `public/` directly.
