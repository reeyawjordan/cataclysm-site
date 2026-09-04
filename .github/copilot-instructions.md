# CATACLYSM PROJECT RULES

These instructions apply to every new Cataclysm episode.

## Hero Slide Template

Every episode must reuse the existing hero slide architecture.

Each episode includes:

* Episode label.
* Hero title.
* Description.
* Poster image in `assets/images/`.
* Background video in `assets/videos/`.

Never redesign the slideshow structure.

## Video Rules

Every hero background video must:

* HTML5 `<video>`
* autoplay
* muted
* loop
* playsinline
* preload="metadata"
* object-fit: cover
* object-position: center center

Videos restart from the beginning whenever their slide becomes active.

Inactive videos pause and reset.

Never animate the video itself.

Never apply transforms, shaking, jitter, blur, pulse, scale, rotation, or filters to the video element.

## Overlay Rules

Effects always live ABOVE the video and BELOW the text.

Each episode gets one unique environmental effect.

### Episode Effects

* Extinction → Embers and ash.
* Arrival → Cosmic particles and energy.
* Deluge → Rain, droplets, mist.
* Rupture → Dust, debris, seismic effects.
* Contagion → Toxic spores and smoke.
* Permafrost → Blizzard, frost edges, ice cracks.
* Fallout → Radioactive ash, smoke, heat haze, burnt vignette.

Future episodes follow this same system.

## Performance Rules

Optimize for GitHub Pages.

* Only preload the active and next hero videos.
* Pause inactive videos.
* Preserve poster images.
* Keep slideshow timing at 8 seconds.
* Preserve fade transitions.
* Never preload all videos eagerly.

## Design Style

Premium Apple / HBO / Netflix cinematic aesthetic.

Readable typography.

Do not add HUDs or metadata bars unless explicitly requested.

Preserve navigation dots, progress bar, overlays, and cinematic transitions.

New episodes should integrate into the existing architecture without modifying previous episodes.
