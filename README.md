# Trust, Lemons, Markets — interactive walkthrough

A 20-step click-through that walks through how **information asymmetry** breaks markets — the core argument of George Akerlof's 1970 paper *"The Market for Lemons,"* extended into iPhones, capital markets, and the trust systems we built (auditing, the SEC, GAAP, ACA, building inspectors, professional licensure) to ease the asymmetry.

Built for a Seeds of Fortune talk at Yale, May 4, 2026. Rick Antle, Yale School of Management.

## Run it

Open **`index.html`** in any modern browser. No build step, no install. React + Babel load from CDN.

A live deployed copy is at: `https://<your-username>.github.io/<repo-name>/`

## Files

- **`index.html`** — current canonical version. This is what visitors land on.
- **`akerlof-lemons-v4.html`** — version-named archive (v4.6.0). Identical to `index.html` today; preserved as a permanent snapshot once future versions ship.

## Update flow

When a new version ships:

1. Save it as `akerlof-lemons-v4.x.y.html` in this folder (archive).
2. Copy it over `index.html` (the version visitors see).
3. Commit and push. GitHub Pages redeploys automatically.

Old version-named files stay reachable at their direct URLs (`/<repo>/akerlof-lemons-v4.6.0.html`, etc.) so prior shares don't break.

## Enable GitHub Pages (one-time setup)

In the repo on GitHub:

1. **Settings → Pages**
2. Source: **Deploy from a branch**, branch: **`main`**, folder: **`/ (root)`**
3. Save. Wait ~1 minute. The URL appears at the top of the Pages settings page.

## Hidden dev tools

- **Triple-click the page header** to toggle dev-mode jump buttons (lets you skip to any step). Audience-safe — invisible until clicked.
- **`?notes=1`** in the URL or the 📝 toggle in the header surfaces speaker notes inline.
