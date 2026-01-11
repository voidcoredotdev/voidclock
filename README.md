# VoidClock

A local, offline-first clock and time context display.

VoidClock started as a very simple idea:

> **A shower clock that doesn’t turn the screen off.**

Over time, it evolved into something more intentional — a set of small,
self-contained clock variants that run entirely in the browser and rely only on
the system clock.

No backend.  
No accounts.  
No tracking.  
No updates required.

---

## Design philosophy

VoidClock is built around a few strict principles:

- No servers
- No network dependency
- No data collection
- No external services

Everything runs locally using **HTML, CSS, JavaScript, and the system clock**.

The goal is to provide useful time context at a glance without noise, friction,
or unnecessary features.

If something stops being useful, it can be removed just as easily as it was added.

---

## Variants

Different contexts need different amounts of information.  
That’s why VoidClock exists in multiple variants:

- **Classic**  
  A simple clock with timezone selection, 12/24-hour mode, and light/dark theme.

- **Pro**  
  Everything in Classic, plus a keep-awake function for tablets and kiosks.

- **Ultimate**  
  An early experimental version with year progress and city display.

- **UltimateProPlus**  
  A weekday-based layout with day and year progress bars.

- **Year**  
  A focused countdown to the next year (days, hours, minutes, seconds).

Each variant is intentionally narrow in scope.

---

## Why progress bars?

The day and year progress indicators are not deadlines.

They exist purely as **context** — a quiet sense of where you are in time.

If they ever stop being useful, they don’t belong there.

---

## Where this runs

VoidClock can be opened directly from the local file system and works fully
offline.

It is suitable for:

- desktops
- tablets
- wall displays
- kiosk setups
- Raspberry Pi devices in kiosk mode

---

## Download

All clock variants can be downloaded as a static offline bundle:

👉 **https://cdn.voidcore.dev/voidclock.zip**

Unzip it and open the files directly — no build step required.

---

## Source & transparency

VoidClock runs entirely client-side.

The core clock logic is open-source.  
The surrounding UI and presentation are intentionally lightweight.

You can inspect everything directly via your browser (or this repo).

---

## Final note

VoidClock is built to be:

> **simple, durable, and boring — in the best possible way.**
