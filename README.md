# MIDI Command Studio

**Control Windows with MIDI hardware: shortcuts, macros, volume, soundboard actions, and app-focused presets.**

[Official Website](https://midicommandstudio.com)  
[Download](https://midicommandstudio.com/download.html)  
[Documentation Home](docs/README.md)  
[Getting Started](docs/getting-started.md)  
[Release Notes](CHANGELOG.md)

MIDI Command Studio is a **Windows-only** desktop application for turning MIDI controllers, MIDI keyboards, pads, knobs, faders, and encoders into practical controls for Windows and creative software.

This repository is for **documentation, release notes, screenshots, download links, and issue tracking**. The application is **closed-source / not open source**, and the source code is not published here.

## At A Glance

| Area | Details |
| --- | --- |
| Platform | Windows only |
| Product type | Standalone desktop application |
| Typical hardware | MIDI keyboards, pad controllers, faders, knobs, encoders, control surfaces |
| Common workflows | Windows shortcuts, macros, app volume control, Windows input volume control, system volume, soundboard actions, and app-focused presets |
| Repository scope | Documentation, releases, screenshots, external links, and issue tracking |
| Source code | Closed-source application; no app source code in this repository |
| Download | [Official download page](https://midicommandstudio.com/download.html) |

## What It Does

MIDI Command Studio receives MIDI input and maps it to desktop actions. It is intended for people who want to control Windows with a MIDI controller instead of relying only on a keyboard, mouse, or dedicated macro pad.

Typical uses include:

- Triggering Windows shortcuts from MIDI pads, keys, buttons, or encoders
- Running macros from MIDI controls
- Typing text, sending mouse actions, running programs, or opening files from macro steps
- Controlling Windows volume for individual apps or the main system output
- Controlling Windows input levels for microphones, aux inputs, and other recording devices
- Building app-focused MIDI controller workflows for creative, streaming, editing, and utility software
- Triggering repeated shortcuts in media players, video editors, photo editors, browsers, chat apps, audio tools, and other shortcut-driven software
- Using MIDI device pads or buttons as a simple soundboard or sample player

## Who This Is For

- Streamers and creators who want physical controls for audio, scenes, playback, and repeatable actions
- Video editors who want MIDI controller shortcuts for editing tools
- Musicians who want to reuse MIDI hardware outside a DAW
- Power users building MIDI controller macros for Windows workflows
- Users looking for a Stream Deck alternative using MIDI hardware they already own
- Anyone who wants to get more practical use from a MIDI controller, keyboard, or control surface

## Core Capabilities

- Dedicated learn buttons for buttons, faders, knobs, and encoders
- Device-specific presets with autosave
- Preset switching to change configured layouts instantly from the controller itself
- Windows shortcut triggering
- Macro execution
- Text input, mouse action, run program, and open file macro steps
- Global or app-focused mappings
- Assignment Check Mode for checking mapped controls without triggering actions
- System volume control
- App-targeted volume control
- Windows input volume control for microphones and other recording devices
- Soundboard support
- MIDI feedback for supported devices
- X-Touch integration, including LCD and fader feedback where supported
- Encoder modifiers
- MIDI Thru for unmapped MIDI messages, requiring a virtual MIDI port
- Multiple device support

## Not A DAW Plugin

MIDI Command Studio is a standalone Windows utility. It is not a VST, instrument, DAW plugin, or MIDI effect. Its purpose is to map MIDI hardware to Windows shortcuts, macros, volume controls, soundboard actions, and app-focused workflows outside a DAW.

## Quick Start

1. Download the current Windows build from the [official download page](https://midicommandstudio.com/download.html).
2. Install and launch MIDI Command Studio.
3. Add or select your MIDI device in the `Devices` panel.
4. Click the learn button that matches the control type, such as button, fader/knob, or encoder/jogwheel.
5. Assign the MIDI message to a shortcut, macro, volume action, soundboard action, or preset workflow.
6. Test the mapping in the target application.

See [Getting Started](docs/getting-started.md) for setup details and first-test recommendations.

## Documentation

- [Documentation Home](docs/README.md)
- [Getting Started](docs/getting-started.md)
- [Controller Compatibility](docs/controller-compatibility.md)
- [Free vs Full](docs/free-vs-full.md)
- [External Resources](docs/external-resources.md)
- [Data And Privacy](docs/data-and-privacy.md)
- [Release Notes](CHANGELOG.md)
- [Support](SUPPORT.md)
- [Security Policy](SECURITY.md)

## Screenshots And Demos

Product screenshots and GIFs are tracked in the repository so the README and docs can reference stable assets over time.

- [`assets/screenshots/`](assets/screenshots/)
- [`assets/gifs/`](assets/gifs/)

No screenshots or demo videos are linked in this repository yet. Add only current visuals that match the public release.

## Downloads And Releases

- Official website: [midicommandstudio.com](https://midicommandstudio.com)
- Download: [midicommandstudio.com/download.html](https://midicommandstudio.com/download.html)
- Current public version: `1.2.0`
- Version history: [CHANGELOG.md](CHANGELOG.md)
- GitHub Releases: use this repository's Releases page for public version notes if release entries are enabled

Suggested release structure:

- Use GitHub Releases for public version notes and known issues
- Keep downloads linked through the official website unless distribution policy changes
- Mirror user-facing release notes in [CHANGELOG.md](CHANGELOG.md)
- Include exact version numbers, dates, and Windows compatibility notes when verified

## External Mentions And Reviews

Verified external resources are listed for reference, including Softpedia, KVR Audio, SaaSHub, and Rekkerd.

See [External Resources](docs/external-resources.md) for the full reference list.

## Support And Feedback

- Product support: [Contact page](https://midicommandstudio.com/contact.html)
- Website: [midicommandstudio.com](https://midicommandstudio.com)
- Download / purchase page: [Download page](https://midicommandstudio.com/download.html)
- Documentation issues: use this repository's issue tracker if enabled
- Application bugs: use the [contact page](https://midicommandstudio.com/contact.html) or the app bug report template if issue tracking is enabled

See [SUPPORT.md](SUPPORT.md) for reporting guidance.
