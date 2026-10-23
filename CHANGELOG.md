# Changelog

## 1.1.1

### Fixes
- With a single camera, the summary reads **Camera disabled** (*Caméra désactivée*) while it is hidden, instead of "All cameras are hidden".

## 1.1.0

### Changes
- With a single camera, its name is the card title (unless `title` is set) and its privacy badge reads **Disable** while it films and **Enable** while it is hidden (*Désactiver* / *Activer* in French).

## 1.0.0

First public release.

### What's new
- Camera card: every home camera in one grid, with the number of cameras live and hidden in the header.
- One privacy badge per camera; tap to toggle its privacy switch or its smart plug. Hidden cameras leave the grid.
- HD / SD switch, from an `input_select` shared by every dashboard or from the card itself.
- Live grid, clips, snapshots, PTZ and fullscreen through Advanced Camera Card, with `camera_card` to set any of its options; Home Assistant's own camera cards when it is not installed.
- Automatic discovery on the camera's device: privacy switch, PTZ buttons and SD stream (Tapo naming).
- Visual editor in the dashboard UI, labels in English and French.
- Light and dark theme compatible, installable via HACS.
