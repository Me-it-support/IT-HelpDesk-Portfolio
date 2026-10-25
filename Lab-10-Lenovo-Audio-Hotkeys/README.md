# Lab 10 - Lenovo ThinkPad Audio Hotkeys Troubleshooting

## 📌 Overview

This lab documents a real-world IT support case involving malfunctioning audio function keys on a Lenovo ThinkPad 11e running Windows 10. The troubleshooting process focused on identifying the issue, restoring the correct audio key functions, and verifying the successful resolution.

## 🖥️ Device Information

- Device: Lenovo ThinkPad 11e
- Machine Type: 20DA
- Operating System: Windows 10
- Audio Controls: F1 (Mute), F2 (Volume Down), F3 (Volume Up)

## ⚠️ Problem Description

The audio function keys were not performing their intended functions. Pressing F1, F2, or F3 caused the audio to toggle between muted and unmuted states instead of providing the expected mute, volume down, and volume up controls.

The red mute indicator light also remained illuminated even when the audio was unmuted through Windows.

## 🔍 Troubleshooting

- Checked the audio controls and confirmed that volume adjustment through Windows worked.
- Reviewed the BIOS keyboard function settings.
- Checked Device Manager for keyboard and audio-related devices.
- Investigated the Lenovo Hotkey Client Loader service.
- Identified that the `IBMPMSVC` service was initially missing.
- Ran Windows system file checks and repaired corrupted system files.
- Installed the Lenovo Power Management Driver compatible with the device.

## 🛠️ Solution

Installed the Lenovo Power Management Driver and restarted the laptop.

After restarting, the audio function keys returned to their expected behavior.

## 🧪 Verification

- F1 correctly muted and unmuted the audio.
- F2 correctly decreased the volume.
- F3 correctly increased the volume.
- The red mute indicator light turned off when the audio was unmuted.
- The `IBMPMSVC` service was confirmed to be running.

## 📸 Screenshots

Screenshots to be added:

- Audio keys before and after troubleshooting
- Lenovo Power Management Driver installation
- Successful audio key functionality
- `IBMPMSVC` service status showing RUNNING

## 🎯 Outcome

The audio hotkey issue was successfully resolved by installing the appropriate Lenovo Power Management Driver and restarting the device. This case demonstrates the importance of driver compatibility, systematic troubleshooting, service dependency investigation, and post-repair verification.
