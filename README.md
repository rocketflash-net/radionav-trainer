# RadioNav Trainer

A simple web simulator for practicing radio navigation: intercepting courses and flying approaches.

**Try it online:** https://rocketflash-net.github.io/radionav-trainer/

## Training modes

- **VOR Radial**: Intercept a radial, inbound or outbound, using the HSI. You set the course (OBS) yourself and read the CDI and TO/FROM flag.
- **NDB / ADF**: Intercept a QDM or QDR using only the RMI needle. There is no CDI in this mode.
- **ILS Approach**: Follow ATC vectors, capture the localizer and glideslope, and control your own vertical speed. You pass if both needles are within 1 dot at the 200 ft decision altitude.

Each scenario is random. Use the **Hint** button if you get stuck, turn on **random wind** for a harder challenge, or hide the map to fly by instruments only.

## Controls

| Key | Action |
|---|---|
| ← / → | Heading bug ±5° (hold Shift for ±1°) |
| Q / E | Course (OBS) ±5° (hold Shift for ±1°) |
| ↑ / ↓ | Vertical speed ±100 fpm (ILS mode) |
| Space | Pause / resume |
| N | New scenario |
| H | Show hint |

All controls also have on-screen buttons, so it works on phones and tablets.

## Running locally

No installation or build step needed. Download `index.html` and open it in any modern browser.

## Note

This app keeps things simple (no magnetic variation, no DME slant range, fixed turn rate of 3° per second). It is meant to help you understand the concepts. It does not replace training with a flight instructor or a certified simulator.

The in-app text is in Indonesian.
