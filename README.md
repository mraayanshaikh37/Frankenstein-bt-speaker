# Frankenstein BT Speaker 🔊⚡

A childhood dream, still being chased: a working Bluetooth speaker built entirely from salvaged parts. The enclosure is a repurposed cooking oil carton, and every component inside came from old electronics that would've otherwise ended up as scrap.

Currently on v3 — mid-debug.

## Enclosure
Upcycled cotton seed oil carton (1kg).

## Drivers
- 3x oval full-range speakers (from an old TV)
- 1x round subwoofer driver (from an old TV's sub tunnel)

## Version History

| Version | What changed |
|---|---|
| v0.1  | Aux-powered speakers — worked, but with heavy noise |
| v0.5  | Salvaged a BT receiver module from car tape/headphone/boombox chipsets, paired with borrowed speakers and a salvaged IC6283 amp |
| v1    | Used a proper amp IC with a BT module scavenged from headphones |
| v2    | Switched to a premade BT module chip + amp IC |
| v2.5  | Replaced the IC amp with a PAM8403 module |
| v3    | Added a proper regulated 5V supply (7805) — but this shorted out both the PAM and BT module chipsets |

## Current Status (v3, patch in progress)
- BT module removed for testing after the short — checking if it's dead or recoverable
- 12V adapter temporarily repurposed for another project
- A spare IC6283 is on hand, being considered for the next revision

## What's Next
- Confirm whether the BT module survived the short
- Rebuild the power stage more carefully around the 7805 regulator
- Possibly integrate the spare IC6283
- Clean up internal wiring ("jungle mode" — function over form, for now)

## Why
Building a working Bluetooth speaker has been a goal since childhood. Every version here is a step closer — salvaged parts, real failures, real debugging. 
