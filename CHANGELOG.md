# Changelog

This changelog tracks public MIDI Command Studio release notes.

The application is closed-source. This repository contains documentation, release notes, screenshots, download links, and issue-tracking guidance.

## 1.2.3

- Current public version.
- Release date: 23 July 2026
- Installer: `MidiCommandStudio_Setup_1.2.3.exe`
- Publisher: Meltopia
- Platform: Windows 10/11
- Download installer: [MidiCommandStudio_Setup_1.2.3.exe](https://github.com/jpcrowther-cloud/midi-command-studio/releases/download/v1.2.3/MidiCommandStudio_Setup_1.2.3.exe)

### Highlights

- Fixed a potential application crash when a connected MIDI device was physically unplugged.
- Fixed manually entered shortcuts incorrectly filling or replacing mapping descriptions.

## 1.2.2

- Previous public version.
- Release date: 19 June 2026
- Installer: `MidiCommandStudio_Setup_1.2.2.exe`
- Publisher: Meltopia
- Platform: Windows 10/11
- Download installer: [MidiCommandStudio_Setup_1.2.2.exe](https://github.com/jpcrowther-cloud/midi-command-studio/releases/download/v1.2.2/MidiCommandStudio_Setup_1.2.2.exe)

### Highlights

- Added an `Open Windows shortcut (.lnk)` macro step.
- Improved mouse-position capture with immediate keyboard capture and no countdown.
- Improved installer handling when MIDI Command Studio is still running in the system tray.
- Improved uninstall options for retaining presets, settings, shortcut lists, and licence data.
- Simplified diagnostics, log, and licence controls in Settings.
- Reduced false diagnostic reports during application startup.
- General stability and usability improvements.

## 1.2.1

- Previous public version.
- Installer: `MidiCommandStudio_Setup_1.2.1.exe`
- Publisher: Meltopia
- Platform: Windows 10/11
- Download installer: [MidiCommandStudio_Setup_1.2.1.exe](https://github.com/jpcrowther-cloud/midi-command-studio/releases/download/v1.2.1/MidiCommandStudio_Setup_1.2.1.exe)

### Highlights

- Improved app shutdown stability, including close, quit, and tray-exit cleanup behavior.
- Simplified the update flow so the app opens a dedicated website update page for direct downloads.

## 1.2.0

- Previous public version.
- Installer: `MidiCommandStudio_Setup_1.2.0.exe`
- Publisher: Meltopia
- Platform: Windows 10/11
- Download installer: [MidiCommandStudio_Setup_1.2.0.exe](https://github.com/jpcrowther-cloud/midi-command-studio/releases/download/v1.2.0/MidiCommandStudio_Setup_1.2.0.exe)

### Highlights

- Added encoder-based volume control for system, app, and input volume.
- Added adjustable encoder volume step size.
- Improved encoder learning for speed-sensitive hardware.
- Improved app-volume mapping workflow by focusing the app selector automatically when app volume is chosen.
- Added tooltip help for `On` and `Off` actions in the Note and CC Button editors.
- Added preset cycling so one controller button can step through a chosen list of presets for a device.
- Added in-app update checking with installer download flow and download-page fallback.
- Improved preset-switch conflict handling across saved presets for the same device.
- Improved Mackie / MCU support, including feedback behavior and setup flow for compatible devices.
- Added overlay display for triggered mappings/actions with a settings toggle.

## Edition Notes

Free and full version differences are documented in [Free vs Full](docs/free-vs-full.md).
