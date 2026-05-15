# Common Workflows

This page summarizes common ways to use MIDI Command Studio.

For setup instructions, see [Getting Started](getting-started.md).

## Quick Links

- [README](../README.md)
- [Getting Started](getting-started.md)
- [Supported Use Cases](use-cases.md)
- [Troubleshooting](troubleshooting.md)

## Shortcut Control

Use MIDI pads, keys, buttons, encoders, jogwheels, faders, or knobs to trigger Windows shortcuts and app shortcuts.

Common examples:

- Media controls
- Window management shortcuts
- App commands
- Editing shortcuts
- Browser, chat, playback, or utility shortcuts

Useful features:

- Dedicated learn buttons for different control types
- Shortcut Palette
- Keyboard shortcut capture
- Global or app-focused targeting

## App-Focused Control

Use mappings that target a specific application instead of always sending commands globally.

Common examples:

- Controls that only work when a selected app is in the foreground
- Controls that bring a selected app forward before sending a shortcut
- Separate mappings for media players, editors, browsers, chat apps, audio tools, or other shortcut-driven software

Useful features:

- `Global`
- `Only when app has focus`
- `Force focus`
- Per-app icons in the mappings list

## Volume Control

Use MIDI faders, knobs, encoders, or jogwheels to control Windows audio levels.

Common examples:

- Main system output volume
- Individual app volume
- Browser or media player volume
- Voice chat volume
- Microphone or recording-device input volume

Useful features:

- `System` volume mappings
- `App Target` volume mappings
- Windows input volume mappings
- Optional mute controls where supported

## Multi-Step Macros

Use a single MIDI control to run a sequence of actions when a shortcut alone is not enough.

Common examples:

- Send several shortcuts in order
- Launch a program or open a file
- Type text
- Click, move, or scroll the mouse
- Add waits or delays between steps

Useful features:

- Macro editor
- Shortcut steps
- Mouse and text steps
- Run program / open file steps

## Soundboard And Sample Playback

Use MIDI pads or buttons as a simple soundboard or sample player.

Common examples:

- Trigger a short audio sample
- Stop playback quickly
- Control sample playback level from a fader, knob, or encoder

Note: simple audio sample playback is a full-version feature.

## Preset-Based Layouts

Use presets when one MIDI device needs different layouts for different work modes.

Common examples:

- General Windows shortcuts
- Editing controls
- Audio controls
- Streaming or recording controls
- App-specific shortcut layouts

Useful features:

- Device-specific presets
- Autosave
- Preset switching from the controller
- Preset cycling

## Mapping Review

Use Assignment Check Mode when you want to inspect a preset without triggering actions.

Common examples:

- Check what a pad or button is assigned to
- Review a controller layout before using it live
- Confirm mappings after editing a preset

Useful features:

- Assignment Check Mode
- Temporary pause of normal mapped actions while checking assignments

## MIDI Thru

Use MIDI Thru when unmapped MIDI messages should continue to another MIDI destination.

Common examples:

- Use part of a MIDI keyboard for shortcuts while the rest still plays a virtual instrument
- Keep unmapped controls available to another MIDI application
- Route unmapped MIDI through a virtual MIDI port

Requirement:

- MIDI Thru requires a virtual MIDI port.

## Hardware Feedback

Use hardware feedback when supported devices should show mapping, preset, or control state on the controller itself.

Common examples:

- LED feedback for mapped buttons
- LCD feedback on supported devices
- Motorized fader feedback on supported Mackie / MCU or native-device workflows

Useful features:

- LED modes
- Device feedback settings
- Native or MCU protocol modes where supported
