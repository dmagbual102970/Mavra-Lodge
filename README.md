# Mavra Lodge — demo website

**Demo only. Sample content. No backend.**

- **Live:** https://dmagbual102970.github.io/Mavra-Lodge/
- **Theme:** terracotta · M monogram emblem · matching favicon
- **Hero:** photograph supplied by the client (low-resolution source — replace with a higher-res photo)
- **Contact:** +675 472 5912 · WhatsApp · Lae, Morobe Province
- **Demo content:** sample rooms (Standard K450, Garden K550, Family K650), services with photos,
  "why book direct", sample policies, guest stories.
- **Demo booking:** booking wizard, availability and "find my booking" work locally (no Firebase).

## Rebuilding

```bash
cd "Edgewood Hotel & Apartment/website"
VITE_DEMO_CONTENT=true node ./node_modules/vite/bin/vite.js build --base=/Mavra-Lodge/
```

Copy `dist/` here, copy `index.html` to `404.html`, keep `.nojekyll`.
