# Lab 10 - Lenovo ThinkPad Audio Hotkeys Troubleshooting

## 📌 Overview

This lab documents a real-world IT support case involving malfunctioning audio function keys on a Lenovo ThinkPad 11e running Windows 10.

## 🖥️ Device Information

- Device: Lenovo ThinkPad 11e
- Machine Type: 20DA
- Operating System: Windows 10
- Audio Controls: F1 (Mute), F2 (Volume Down), F3 (Volume Up)

## ⚠️ Problem Description

The audio function keys did not perform their intended functions. Pressing F1, F2, or F3 caused the audio to toggle between muted and unmuted states instead of providing the expected controls.

The red mute indicator light also remained illuminated even when audio was unmuted through Windows.

## 🔍 Troubleshooting

- Confirmed that volume control through Windows worked.
- Reviewed BIOS keyboard function settings.
- Checked keyboard and audio-related devices in Device Manager.
- Investigated the Lenovo Hotkey Client Loader service.
- Found that the `IBMPMSVC` service was initially missing.
- Ran Windows system file checks and repaired corrupted system files.
- Installed the Lenovo Power Management Driver compatible with the device.

## 🛠️ Solution

Installed the Lenovo Power Management Driver and restarted the laptop.

After restarting, the audio function keys returned to their expected behavior.

## 🧪 Verification

- F1 correctly muted and unmuted the audio.
- F2 correctly decreased the volume.
- F3 correctly increased the volume.
- The red mute indicator light turned off when audio was unmuted.
- The `IBMPMSVC` service was confirmed to be running after installation.

## 📸 Screenshots

No screenshots were captured during the original troubleshooting session. The successful resolution was verified through functional testing and checking the service status after installation and restart.

## 🎯 Outcome

The audio hotkey issue was successfully resolved after installing the appropriate Lenovo Power Management Driver and restarting the device.

This case demonstrates the importance of driver compatibility, systematic troubleshooting, service dependency investigation, and post-repair verification.
