# Common Workflows

This page describes practical workflows for using MIDI Command Studio as MIDI macro software for Windows, a volume control surface, or an app-focused shortcut tool.

## Quick Links

- [README](../README.md)
- [Getting Started](getting-started.md)
- [Supported Use Cases](use-cases.md)
- [Troubleshooting](troubleshooting.md)

## Windows Shortcuts From MIDI Controls

Use the matching learn button to assign a pad, key, button, knob, fader, encoder, or jogwheel to a Windows shortcut or shortcut sequence.

Common examples:

- Media controls
- Window management shortcuts
- Application commands
- Repeated editing shortcuts
- Utility macros

Add a screenshot or GIF here once a current public build is available for capture.

## App-Focused MIDI Controller Workflows

MIDI Command Studio can be used to build mappings for a specific target application.

Common examples:

- Trigger application shortcuts
- Toggle mute or playback actions
- Trigger recording, streaming, editing, or utility commands
- Run soundboard actions
- Use separate presets for different applications or work modes

Example target applications can include OBS, DaVinci Resolve, browsers, chat tools, editors, media players, and audio utilities.

## Editing And Production Shortcuts

For editing and production workflows, MIDI controls can be mapped to repeated application shortcuts or macros.

Common examples:

- Timeline navigation shortcuts
- Cut, trim, marker, and playback commands
- Presets for edit, color, audio, or review tasks

Example target applications can include shortcut-driven editing, review, playback, and production tools.

## MIDI Volume Control

Faders and knobs can be used for volume workflows, including system output volume, app-targeted volume control, and Windows input volume control for microphones or other recording devices where supported by the current release.

Common examples:

- Browser volume
- Music app volume
- Voice chat volume
- Streaming or recording software volume
- System output volume
- Microphone or recording-device input volume

Add a volume-control GIF here once a current public build is available for capture.

## Macros

Macros let a single MIDI control run more than one action. They are useful when a shortcut alone is not enough.

Common macro step types include:

- Keyboard shortcuts
- Run program or open file
- Mouse click, move, or scroll
- Text input
- Wait or delay between actions

Macro steps run in order when the mapped control is triggered.

## Soundboard And Audio Sample Playback

The full version supports simple audio sample playback. Audio mappings can trigger samples, stop playback quickly, and control the overall sample playback level from a MIDI control.

## Preset Switching

Preset switching lets one MIDI controller serve different roles depending on the current task or application.

Common examples:

- Streaming preset
- Editing preset
- Audio control preset
- General Windows shortcuts preset

Add a preset-switching GIF here once a current public build is available for capture.

Presets are device-specific and autosaved as you edit mappings and macros. Switching presets changes which controls are active, which apps shortcuts target, which macros run, and how faders or encoders behave.

## Assignment Check Mode

Assignment Check Mode lets you press controls on the selected device and see what they are assigned to without sending the mapped shortcuts, macros, or volume actions.

Use it when you have already built a preset and want to confirm which pads, buttons, knobs, faders, or encoders are mapped.

## MIDI Feedback And X-Touch Workflows

For supported devices, MIDI feedback can keep hardware state aligned with the active preset or action state. X-Touch integration can include LCD and fader feedback where supported.

Document exact device behavior only after testing a specific model and version.

Add an X-Touch feedback demo here once model-specific behavior has been verified.

## MIDI Thru

MIDI Thru can route MIDI onward to another MIDI destination. This requires a virtual MIDI port.

When MIDI Thru is enabled, mapped controls still trigger their assigned actions. Unmapped MIDI messages are sent to the virtual MIDI Thru port, which is useful when part of a keyboard or controller should still feed another MIDI application.
