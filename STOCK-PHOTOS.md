# Alafia Cleaning - Stock Photo Library & Plan

A working reference for every image on the site: what we use now, where it appears, how many we should gather per category, and search keywords to find nicer options in the future.

- **Total image placements on the site:** 32
- **Unique photos in use right now:** 18
- **Recommended future library size:** ~58 photos
- **To gather next:** ~40 photos

The gap is because many slots reuse the same photo (see "Duplicates to replace" below). Building a larger library lets us give every page a distinct, high quality look.

---

## How images are used (technical notes)

All photos are currently hot-linked from Pexels (free to use, no attribution required). URL format:

```
https://images.pexels.com/photos/<ID>/pexels-photo-<ID>.jpeg?auto=compress&cs=tinysrgb&w=<WIDTH>
```

Widths used by slot type:

| Slot type | Width param | Orientation | Notes |
| --- | --- | --- | --- |
| Page hero (full-bleed background) | `w=1600` to `w=1920` | Landscape (wide) | Needs a strong focal point that survives a dark/light overlay |
| Home service cards | `w=800` | Portrait-ish (4:3 crop) | Clear subject, reads well small |
| Service page gallery | `w=600` | Landscape (crops to h-48) | 3 per page, should feel varied |
| Areas / feature image | `w=900` | Landscape | Bright, welcoming interior |

**For a self-hosted future library:** download each photo at 2x the display width (e.g. hero at 2560px, cards at 1600px) so they stay crisp on retina screens. Recommended folder layout if we move off hot-linking:

```
assets/stock/
  hero/
  regular-house-cleaning/
  deep-cleaning/
  office-commercial/
  airbnb-turnover/
  move-in-move-out/
  carpet-cleaning/
  team/
  areas/
  details/
```

---

## Category plan: have vs need

| Category | In use now | Target library | To gather | Where it appears |
| --- | ---: | ---: | ---: | --- |
| Hero / brand lifestyle | 1 | 5 | 4 | Home hero, future rotating banners |
| Regular House Cleaning | 3 | 6 | 3 | Home card + service page hero/gallery |
| Deep Cleaning | 3 | 6 | 3 | Home card + service page hero/gallery |
| Office / Commercial | 2 | 6 | 4 | Home card + service page hero/gallery |
| Airbnb / Rental Turnover | 2 | 6 | 4 | Home card + service page hero/gallery |
| Move In / Move Out | 2 | 6 | 4 | Home card + service page hero/gallery |
| Carpet Cleaning | 3 | 6 | 3 | Home card + service page hero/gallery |
| Team / People (cleaners) | 2 | 6 | 4 | Service galleries, future About/Team |
| Areas / local interiors | 1 | 5 | 4 | Areas section, future location pages |
| Details / supplies / accents | 0 | 6 | 6 | Section accents, backgrounds, future blog |
| **Totals** | **~18** | **~58** | **~40** | |

"In use now" counts distinct photos that fit each category; a few photos serve more than one category.

---

## Full inventory (every slot on the site)

### Home page (`index.html`) - 8 placements

| Slot | Current photo ID | Review link |
| --- | --- | --- |
| Hero background | 37734652 | https://www.pexels.com/photo/37734652/ |
| Card: Regular House Cleaning | 27176673 | https://www.pexels.com/photo/27176673/ |
| Card: Deep Cleaning | 5591852 | https://www.pexels.com/photo/5591852/ |
| Card: Office / Commercial | 34516670 | https://www.pexels.com/photo/34516670/ |
| Card: Move In / Move Out | 18041820 | https://www.pexels.com/photo/18041820/ |
| Card: Airbnb / Rental Turnover | 9462738 | https://www.pexels.com/photo/9462738/ |
| Card: Carpet Cleaning | 9462316 | https://www.pexels.com/photo/9462316/ |
| Areas Served feature image | 36411467 | https://www.pexels.com/photo/36411467/ |

### Regular House Cleaning (`regular-house-cleaning.html`) - 4 placements

| Slot | Current photo ID | Review link |
| --- | --- | --- |
| Hero background | 8055202 | https://www.pexels.com/photo/8055202/ |
| Gallery 1 | 27176673 | https://www.pexels.com/photo/27176673/ |
| Gallery 2 (team) | 6195277 | https://www.pexels.com/photo/6195277/ |
| Gallery 3 | 37734652 | https://www.pexels.com/photo/37734652/ |

### Deep Cleaning (`deep-cleaning.html`) - 4 placements

| Slot | Current photo ID | Review link |
| --- | --- | --- |
| Hero background | 5591852 | https://www.pexels.com/photo/5591852/ |
| Gallery 1 | 5591852 (same as hero) | https://www.pexels.com/photo/5591852/ |
| Gallery 2 | 32908422 | https://www.pexels.com/photo/32908422/ |
| Gallery 3 | 9462644 | https://www.pexels.com/photo/9462644/ |

### Office / Commercial (`office-commercial-cleaning.html`) - 4 placements

| Slot | Current photo ID | Review link |
| --- | --- | --- |
| Hero background | 34516670 | https://www.pexels.com/photo/34516670/ |
| Gallery 1 | 34516670 (same as hero) | https://www.pexels.com/photo/34516670/ |
| Gallery 2 | 10567364 | https://www.pexels.com/photo/10567364/ |
| Gallery 3 (team) | 6195122 | https://www.pexels.com/photo/6195122/ |

### Airbnb / Rental Turnover (`airbnb-rental-turnover.html`) - 4 placements

| Slot | Current photo ID | Review link |
| --- | --- | --- |
| Hero background | 9462738 | https://www.pexels.com/photo/9462738/ |
| Gallery 1 | 9462738 (same as hero) | https://www.pexels.com/photo/9462738/ |
| Gallery 2 | 37734652 | https://www.pexels.com/photo/37734652/ |
| Gallery 3 | 32696578 | https://www.pexels.com/photo/32696578/ |

### Move In / Move Out (`move-in-move-out-cleaning.html`) - 4 placements

| Slot | Current photo ID | Review link |
| --- | --- | --- |
| Hero background | 18041820 | https://www.pexels.com/photo/18041820/ |
| Gallery 1 | 18041820 (same as hero) | https://www.pexels.com/photo/18041820/ |
| Gallery 2 | 4239146 | https://www.pexels.com/photo/4239146/ |
| Gallery 3 | 32696578 | https://www.pexels.com/photo/32696578/ |

### Carpet Cleaning (`carpet-cleaning.html`) - 4 placements

| Slot | Current photo ID | Review link |
| --- | --- | --- |
| Hero background | 9462316 | https://www.pexels.com/photo/9462316/ |
| Gallery 1 | 9462316 (same as hero) | https://www.pexels.com/photo/9462316/ |
| Gallery 2 | 7703301 | https://www.pexels.com/photo/7703301/ |
| Gallery 3 | 36813400 | https://www.pexels.com/photo/36813400/ |

---

## Duplicates to replace first (highest impact)

These reuses are the main reason the site feels repetitive. Replacing them gives the biggest visual upgrade for the least effort.

1. **Every service page hero = its own card image = its first gallery image.** Deep, Office, Airbnb, Move In/Out, and Carpet each show the same photo 3 times. Give each service page a distinct wide hero photo.
2. **37734652** appears 3 times (home hero, Regular gallery 3, Airbnb gallery 2). Keep it on the home hero only.
3. **32696578** appears twice (Airbnb gallery 3, Move In/Out gallery 3). Swap one out.

Target: no photo used more than once, except an intentional brand hero.

---

## Search keywords by category (for Pexels / Unsplash)

Pick bright, natural-light, modern photos. Avoid heavy stock-photo staging and visible logos.

- **Hero / brand lifestyle:** "clean modern living room", "bright tidy home interior", "sunlit apartment", "minimal home"
- **Regular House Cleaning:** "wiping kitchen counter", "dusting shelf", "person cleaning home", "vacuuming living room"
- **Deep Cleaning:** "scrubbing tile", "cleaning oven", "detailed bathroom cleaning", "grout cleaning", "shower deep clean"
- **Office / Commercial:** "clean modern office", "cleaning office desk", "commercial cleaning", "sanitizing workplace"
- **Airbnb / Rental Turnover:** "hotel bed made", "styled guest bedroom", "fresh linens", "clean airbnb interior"
- **Move In / Move Out:** "empty apartment", "moving boxes clean room", "empty room hardwood", "cleaning empty kitchen"
- **Carpet Cleaning:** "carpet cleaning machine", "vacuuming rug", "steam cleaning carpet", "clean fluffy carpet"
- **Team / People:** "professional cleaner smiling", "cleaning crew uniform", "housekeeper portrait", "cleaning team"
- **Areas / local interiors:** "cozy home living room", "suburban home interior", "welcoming home entryway"
- **Details / supplies / accents:** "cleaning supplies flat lay", "spray bottle microfiber", "sparkling clean surface", "fresh towels"

---

## How to swap a photo (quick guide)

1. Find a photo on Pexels and copy its numeric ID from the URL (`pexels.com/photo/<ID>/`).
2. In the relevant HTML file, replace the old ID in the image URL with the new one. Keep the `?auto=compress&cs=tinysrgb&w=...` part so the size stays correct.
3. Update the nearby `alt="..."` text to describe the new photo.
4. If self-hosting instead, download at 2x, drop it in the matching `assets/stock/<category>/` folder, and point the `src` at the local path.

---

## Licensing

- **Pexels** and **Unsplash** photos are free for commercial use with no attribution required.
- Avoid photos with recognizable people if you plan to imply they are Alafia staff or clients; use clearly generic shots or real team photos when available.
- When you have them, real photos of the Alafia team and completed jobs will always outperform stock. This library is the fallback until then.
