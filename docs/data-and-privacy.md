# Data And Privacy

This page summarizes what MIDI Command Studio and the official website send, and what they do not send.

Full privacy page: [https://midicommandstudio.com/privacy.html](https://midicommandstudio.com/privacy.html)

## Quick Links

- [README](../README.md)
- [Support](../SUPPORT.md)
- [Security Policy](../SECURITY.md)

## App Analytics And Telemetry

MIDI Command Studio sends data only for licensing and when you choose to send feedback or crash reports.

The app itself does not include usage analytics or background telemetry.

## Licensing And Activation

The app makes network requests for license actions, including activate, status, and deactivate.

These requests include:

- License key
- Non-identifying device or install identifiers
- A non-reversible machine hash
- Install ID

These identifiers are used to manage activations. In full-license mode, a status check may run on startup.

No usage tracking or MIDI input data is transmitted during licensing checks. If a licensing response includes an email address, it is displayed locally only.

## Feedback And Crash Reports

Feedback and crash reports are optional. If you choose to send one, the app sends the report content to help diagnose issues.

Reports can include:

- App version
- Device or preset labels
- Stack traces
- A log tail from `error_log.txt`, up to 200 KB
- A non-reversible machine hash
- Optional log text prefilled in the feedback form

The log redacts the Windows user path, for example:

```text
C:\Users\<redacted>\...
```

No license keys are included unless you manually add them.

## Local Presets

Presets are saved locally as JSON files under the user's Windows profile:

```text
%LOCALAPPDATA%\MIDI Command Studio\presets
```

Each device has its own folder inside the presets directory. These folders can be backed up or copied if you want to preserve or move presets.

## MIDI Data

MIDI input data is used locally for mappings and control detection.

MIDI input data is not transmitted as part of licensing checks or background telemetry.

## Website Analytics

The official website uses Cloudflare Web Analytics to understand page views, referrers, approximate visitor location, device/browser information, and page performance.

Cloudflare Web Analytics does not use cookies or local storage for analytics, and Cloudflare states that it does not collect or use visitors' personal data for Web Analytics.

Analytics data is used only to improve the website and understand which pages are useful.
