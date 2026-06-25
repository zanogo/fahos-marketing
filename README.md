# Archive Marketing

Static marketing site hosted on Firebase Hosting.

## Structure

- `public/` — site files served by Firebase Hosting (`public/index.html` is the entry point).

## Deploy

```bash
firebase deploy --only hosting
```

Requires the [Firebase CLI](https://firebase.google.com/docs/cli) and authentication (`firebase login`). The target project is configured in `.firebaserc`.
