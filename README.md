<p align="center">
  <a href="https://limbvol.de">
    <img src="assets/limbvol-logo.svg" alt="LimbVolScanner" width="420">
  </a>
</p>

<h3 align="center">Measure limb volume in 3D.</h3>

<p align="center">
  Capture a limb's shape with an iPhone and calculate its volume from a 3D model.
</p>

<p align="center">
  <a href="https://limbvol.de"><img alt="Website" src="https://img.shields.io/badge/website-limbvol.de-006DFF?style=flat-square"></a>
  <img alt="Platform" src="https://img.shields.io/badge/platform-iPhone-1d1d1f?style=flat-square&logo=apple">
  <img alt="Status" src="https://img.shields.io/badge/status-development%20prototype-52617b?style=flat-square">
</p>

> [!IMPORTANT]
> **Development prototype.** LimbVolScanner is not CE-marked and is not available for clinical use.
> It is not a tool for diagnosis or treatment decisions. Accuracy and repeatability have not yet been validated.

---

## Why 3D measurement?

**Measure the shape itself.**

| | Current method | With LimbVolScanner |
|---|---|---|
| **Approach** | Tape measurements at a few selected points | Scan the whole leg from thigh to ankle |
| **Volume from** | A simplified geometric approximation | The captured 3D surface |

Capturing the full surface does not by itself prove greater accuracy or clinical usefulness. That has to be shown through validation (see [Validation](#validation)).

## How it works

**Scan. Review. Track.**

1. **Scan the leg.** Move the iPhone around the leg, from thigh to ankle, following the on-screen guidance.
2. **Review the volume.** Check the 3D model and the calculated volume, then save the measurement.
3. **Track changes.** Compare with earlier scans to follow volume changes between visits.

The scanned segment runs from the upper thigh to the ankle. The foot is excluded.

## Features

- 📱 **Runs on iPhone**: no extra hardware needed
- 🧊 **3D limb capture**: the whole surface instead of a handful of circumferences
- 🧭 **Guided workflow**: on-screen guidance during the scan
- 📈 **Digital volume tracking**: saved measurements you can compare over time

## Areas for evaluation

We want to find out how 3D measurements could help track limb-volume changes in:

- Lymphedema
- Lipedema
- Pre- and post-treatment measurements
- Long-term volume monitoring

## Validation

**Performance validation is pending.**

| Metric | Status |
|---|---|
| Volume error | Not yet published |
| Repeatability | Not yet published |
| Scan time | < 1 min (development target) |

Open validation questions:

- Volume error against an appropriate reference method
- Repeatability across repeated scans
- Effects of different operators and capture conditions
- A consistent definition of the measured leg segment

Supported iPhone models and a validated capture protocol have not been specified yet.

More detail: [Measurement approach](https://limbvol.de/measurement.html)

## Pilot program

Clinics and researchers can get in touch to discuss a structured evaluation, either through
[limbvol.de](https://limbvol.de/#pilot-form) or by email at **[kontakt@limbvol.de](mailto:kontakt@limbvol.de)**.

Sending an inquiry does not enroll anyone in a study or authorize patient use. Any evaluation needs a separate
agreement and the applicable regulatory and data-protection arrangements.

> [!CAUTION]
> Please do **not** send patient information or health data, by email or in GitHub issues.

## Links

- 🌐 Website: [limbvol.de](https://limbvol.de)
- 📐 Measurement approach: [limbvol.de/measurement](https://limbvol.de/measurement.html)
- ✉️ Contact: [limbvol.de/contact](https://limbvol.de/contact.html)
- 🔒 Privacy: [limbvol.de/privacy](https://limbvol.de/privacy.html)
- Impressum: [limbvol.de/impressum](https://limbvol.de/impressum.html)

## License

© 2026 LimbVolScanner. All rights reserved.
This repository does not grant any license to use, copy, modify, or distribute its contents unless explicitly stated otherwise.

<p align="center"><sub><b>3D measurement. Real impact.</b></sub></p>
