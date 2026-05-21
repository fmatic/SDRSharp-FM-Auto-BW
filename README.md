SDRSharp FM Auto BW

TEF6686-inspired adaptive FM bandwidth plugin for SDR#.

Designed especially for FM-DXing with Airspy HF+ receivers and other SDR# compatible radios.

⸻

Features

* Adaptive WFM bandwidth control
* SNR-based automatic bandwidth adjustment
* Stereo pilot aware bandwidth expansion
* Adjustable Attack / Release behavior
* Min / Max bandwidth limits
* FM-DX focused profiles:
    * Es DX
    * Tropo
    * RDS Logging
    * Hi-Fi
* WFM-only safe mode
* Manual bandwidth override
* Lightweight SDR# native UI

⸻

Why?

Many FM DXers using TEF6686-based tuners discovered how effective adaptive bandwidth can be during:

* Sporadic-E openings
* Meteor scatter
* Tropo
* Weak adjacent-channel situations
* Unattended RDS logging

This plugin brings similar adaptive behavior into SDR#.

Instead of using a fixed FM filter width, the plugin dynamically adjusts WFM bandwidth based on real-time signal conditions.

⸻

Current Adaptive Logic

The current alpha version uses:

* Visual SNR
* Stereo pilot detection
* Attack / Release smoothing
* User-defined bandwidth limits

Stereo signals may automatically allow slightly wider bandwidth, while weaker mono signals can force narrower filtering for improved DX performance.

⸻

Profiles

Es DX

Aggressive adaptive behavior for fast-changing Sporadic-E conditions.

Tropo

More stable behavior optimized for long-duration enhancement conditions.

RDS Logging

Optimized for weak-signal unattended monitoring and PI/RDS decoding.

Hi-Fi

Prefers wider bandwidth and smoother transitions for listening quality.

⸻

Requirements

* SDR# Studio
* Windows
* SDR# Plugin API support
* Recommended:
    * Airspy HF+
    * Airspy HF+ Discovery
    * Airspy Mini

⸻

Status

Early Alpha Release

Algorithms and behavior will continue evolving through real-world FM-DX testing.

⸻

Planned Features

* Adjacent channel intelligence
* Spectrum-aware adaptive filtering
* Advanced damping logic
* Preset saving
* Per-profile custom settings
* Smarter stereo behavior
* Optional logging/debug mode

⸻

Screenshot

(Add screenshot here)

⸻

Credits / Inspiration

Inspired by:

* TEF6686 adaptive bandwidth behavior
* FM-DX community experimentation
* Sjef Verhoeven (PE5PVB) and TEF6686 firmware work
* Airspy SDR ecosystem

⸻

Disclaimer

This project is experimental and intended primarily for FM-DX hobby use.
