# Controllers And MIDI Messages

MIDI Command Studio is designed for Windows users who want to use MIDI hardware for desktop control, shortcuts, macros, and app-specific workflows.

## Quick Links

- [README](../README.md)
- [Getting Started](getting-started.md)
- [Features And Examples](features-and-examples.md)
- [Troubleshooting](troubleshooting.md)

## Controller Types

Typical controller categories include:

- MIDI keyboards
- Pad controllers
- Fader banks
- Knob controllers
- Endless encoders
- Hybrid controllers with mixed buttons, pads, knobs, and sliders
- Control surfaces with MIDI feedback support where supported by the app and device

## Common MIDI Messages

Support details should be documented against verified releases, but the common message types for MIDI controller macros and Windows shortcuts include:

- Note On / Note Off
- Control Change (CC)
- Encoder-generated CC data
- Velocity-sensitive pad input where applicable
- Feedback messages for supported devices and workflows
- MIDI Thru routing where configured; this requires a virtual MIDI port

MIDI Command Studio works with controllers that send standard MIDI note and CC data. Some devices also support Mackie / MCU-style feedback for LCD screens or motorized faders.

HUI is not currently supported. MMC transport data is only minimally supported; simple commands such as play/stop, and sometimes record, may be usable depending on how the device is configured.

## Mapping Examples

- A pad sends a note message that triggers a Windows shortcut
- A knob sends CC data that controls volume or an adjustment workflow
- A fader is assigned to system volume, app-targeted volume, or Windows input volume control
- Buttons are mapped to macros, preset switching, or application-specific commands
- Supported feedback-capable devices receive visual, LCD, or fader feedback where configured

## X-Touch Notes

MIDI Command Studio includes X-Touch integration, including LCD and fader feedback where supported. Document exact model behavior only after testing a specific device and app version.

For Behringer X-Touch One workflows, Native mode expects the hardware to be in MIDI mode. MCU mode expects an MCU-compatible hardware mode.

## When Adding Device Notes

If this page is expanded with compatibility notes, document:

- Controller make and model
- Connection type
- MIDI input and output ports used
- Which controls were tested
- The MIDI message type sent by each tested control
- Feedback behavior, if tested
- Any setup quirks required for consistent use

## Scope Notes

- Do not claim universal controller compatibility unless it has been tested
- Do not assume all control surfaces behave the same way
- Do not document encoder, fader, LCD, or feedback behavior without verification

## Tested Controller Notes

No model-specific controller notes are published yet. Add entries only after testing a specific controller model with a specific MIDI Command Studio version and Windows version.
