# angler-media

Public asset host for [Angler](https://getanglerapp.com) — served via GitHub Pages.
Kept **separate and public** so the main app repo (`angler`) can stay private while
the website still loads these files.

```
demo.mp4        the marketing demo video (site hero)
downloads/      notarized DMGs, e.g. downloads/Angler-1.0.0.dmg
index.html      placeholder root (noindex)
.nojekyll       serve files as-is, no Jekyll processing
```

Public URLs once Pages is enabled (Settings → Pages → Deploy from `main` / root):

```
https://octagon-simon.github.io/angler-media/demo.mp4
https://octagon-simon.github.io/angler-media/downloads/Angler-1.0.0.dmg
```

To add a release: drop the DMG in `downloads/`, commit, push. That's the URL the
site's download button and `appcast.xml` point at.
