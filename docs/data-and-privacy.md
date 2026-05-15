# Data And Privacy

MIDI Command Studio is a Windows desktop application. This page summarizes the public data and privacy notes relevant to support, feedback, and licensing.

## Quick Links

- [README](../README.md)
- [Support](../SUPPORT.md)
- [Security Policy](../SECURITY.md)
- [FAQ](faq.md)

## Local Presets And Data

Presets are saved locally as JSON files under the user's Windows profile:

```text
%LOCALAPPDATA%\MIDI Command Studio\presets
```

Each device has its own folder inside the presets directory. These folders can be backed up or copied if you want to preserve or move presets.

## Feedback And Error Logs

MIDI Command Studio does not send feedback or error-log data automatically. Data is sent only when you explicitly submit the feedback form.

If you choose to send an error log, the report is intended to include the local error log contents needed for troubleshooting. Avoid adding license keys, private account details, or personal information to public issues or logs.

## Licensing Requests

Activation and license-status checks require an internet connection. Licensing actions may send the license key and non-identifying device or install identifiers required to manage activations.

## MIDI Data

MIDI input data is used locally for mappings and control detection. Do not include raw logs publicly if they contain private workflow details you do not want to share.
