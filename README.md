# Redirect: wisdomsurgery.dental → wisdomsurgery.clinic

This repo exists only to hold the custom domain `wisdomsurgery.dental` and bounce every visitor to
the real site at <https://wisdomsurgery.clinic>.

GitHub Pages allows one custom domain per repository, which is why each secondary domain
needs its own repo. There is nothing to maintain here.

- `index.html` / `404.html` — identical redirect page (meta refresh + JS + canonical link)
- `CNAME` — the custom domain. **Do not edit**, GitHub Pages reads it.

DNS for this domain lives in **Squarespace Domains**:

```
A     @    185.199.108.153
A     @    185.199.109.153
A     @    185.199.110.153
A     @    185.199.111.153
CNAME www  wisdom-surgery.github.io.
```

See `docs/DNS-CUTOVER.md` in `Wisdom-Surgery/wisdomsurgery` for the full picture.
