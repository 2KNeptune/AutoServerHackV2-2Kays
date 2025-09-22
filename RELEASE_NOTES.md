# Release v2.0.0 — Final Steam release (port)

**Release date:** 2023-04-28

**Summary**
This release is a direct, unmodified port of the final Bitburner script originally published on Steam Workshop by **2Kays**. The repository contains the exact script file included in the Steam upload: `AutoServerHackV2-2Kays.js`. 

**Files included**
- `AutoServerHackV2-2Kays.js` — Final release script (no changes)

**Notable details**
- This script is single-target and single-threaded. It runs an infinite loop and will alternate between `weaken`, `grow`, and `hack` according to the in-script settings.
- The script contains `SETTING` placeholders (see the file comments). Before running in Bitburner, edit these placeholders to set:
  - The target server hostname (`s = "SETTING"`),
  - The ideal balance fraction (`ib = mb * SETTING`),
  - The ideal security offset (`is = ms + SETTING`).

**Credits & references**
- Original Steam Workshop page: https://steamcommunity.com/sharedfiles/filedetails/?id=2968252827
- This is my original creation before changing my online name from 2Kays to Neptune2K
