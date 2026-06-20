# Privacy Policies

Public privacy policy pages for apps published by Indra Settyo (isettyo),
hosted via GitHub Pages until a dedicated server is set up.

## Structure

```
index.html              Landing page listing all apps
{app-slug}/privacy-policy.html   Per-app privacy policy
```

## Hosting

Enable GitHub Pages on this repo (Settings → Pages → Deploy from branch
`main`, root `/`). Pages URL pattern:

```
https://idstto.github.io/privacy-policies/{app-slug}/privacy-policy.html
```

## Adding a new app

1. Create a new folder named after the app slug.
2. Add `privacy-policy.html` inside it.
3. Add a link to it from the root `index.html`.
