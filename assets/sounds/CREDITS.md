# Key sounds: credits

Every clip in `keys.js` was cut from three recordings by **Sadiquecat** on Freesound. They were recorded on 2025-02-22 on a Keychron K10 with linear switches, using a Zoom H2n in XY mode, and uploaded on 22 Feb 2025.

**Licence: Creative Commons 0 (CC0 1.0 Universal, public domain dedication), https://creativecommons.org/publicdomain/zero/1.0/.** I checked the licence on each sound's own page on 2026-10-11. No credit is required. The author's note says "Attribution is greatly appreciated but not required", so this file gives the credit anyway.

| Recording | URL | What was cut (start time in the source, in seconds) |
|---|---|---|
| "Keychron k10 A to + individual keys" | https://freesound.org/people/Sadiquecat/sounds/789628/ | `key.down` ×6: 1.175, 2.064, 4.951, 5.971, 6.856, 7.727 (70–85 ms each). `key.up` ×4: 0.328, 4.073, 10.705, 12.015 (85–106 ms each) |
| "Keychron k10 Enter" | https://freesound.org/people/Sadiquecat/sounds/789629/ | `wide.down[0]`: 0.014 (98 ms). `wide.up[0]`: 0.114 (149 ms) |
| "Keychron k10 space_bar" | https://freesound.org/people/Sadiquecat/sounds/789630/ | `wide.down[1]`: 0.015 (120 ms). `wide.up[1]`: 0.138 (118 ms) |

Processing, applied to every clip:
1. Source: the Freesound HQ preview, converted to mono at 44.1 kHz.
2. EQ to take out the desk boom: high-pass at 105 Hz, +4 dB at 170 Hz, +6 dB at 480 Hz, −3 dB at 1.3 kHz, and a −6 dB shelf above 7 kHz.
3. Noise gate.
4. Press clips start 4 ms before the bottom-out and release clips start 2 ms before the release click. Every clip ends with a 12–25 ms cosine fade-out.
5. Loudness matched by A-weighting: the loudest key-down peaks at −3 dBFS, and releases sit 5 dB below the presses.
6. Saved as 16-bit PCM WAV. `wide.up` is at 22.05 kHz and everything else at 44.1 kHz.
