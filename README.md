# Ura Click - Offbeat Metronome

This repository contains the Expo / React Native app and a simple static
GitHub Pages site for App Store review support URLs.

## GitHub Pages Site

The static site is located in `docs/` and is intended to be published with
GitHub Pages.

Pages:

- Home: `docs/index.html`
- Ura Click Support: `docs/ura-click/support/index.html`
- Ura Click Privacy Policy: `docs/ura-click/privacy/index.html`

The placeholder contact email is:

```text
your-email@example.com
```

Replace this value across the repository before release.

## GitHub Pages Setup

1. Open the GitHub repository.
2. Go to **Settings**.
3. Open **Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Set **Branch** to `main`.
6. Set **Folder** to `/docs`.
7. Click **Save**.
8. Wait for GitHub Pages to publish the site.
9. Confirm the public URL shown in the Pages settings.
10. Enter the Support URL and Privacy Policy URL in App Store Connect.

## App Store Connect URL Examples

Replace `<github-username>` and `<repository-name>` with the actual GitHub Pages
URL values.

```text
Support URL:
https://<github-username>.github.io/<repository-name>/ura-click/support/

Privacy Policy URL:
https://<github-username>.github.io/<repository-name>/ura-click/privacy/
```

If you use a custom domain, use the matching custom-domain URLs instead.

## Japanese Page Structure

The current pages are written in English for App Store review. Japanese pages
can be added later by mirroring the same structure, for example:

```text
docs/ja/
docs/ja/ura-click/support/
docs/ja/ura-click/privacy/
```
