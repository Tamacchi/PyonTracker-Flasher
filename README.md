# PyonTracker Firmware Flasher

The Windows app for updating PyonTracker firmware.

## Download

**[Download the latest Windows app](https://github.com/Tamacchi/PyonTracker-Flasher/releases/latest/download/PyonTrackerFlasher.exe)**

[Release notes and ZIP downloads](https://github.com/Tamacchi/PyonTracker-Flasher/releases/latest)

Windows 10/11, 64-bit. Run the EXE; no Python installation is needed. Firmware is included, and flashing works offline.

## Flash your trackers

1. Close SlimeVR Server and other serial-monitor apps.
2. Connect the main tracker USB-C port with a USB data cable and turn the tracker on.
3. Wait for identification. If asked, choose the IMU model printed on the tracker lid.
4. The latest bundled firmware is marked Recommended. Review the selected trackers, then click **Flash**.
5. Keep trackers powered on and connected until flashing and verification finish. They restart automatically.

Use **Help** in the app for cable, power and CH340 driver guidance.

## App updates

Starting with app 0.1.18, the app checks for newer releases when opened. You can also click **Check for updates**. **Download update** opens the official release page. Close the old app before running the new EXE.

App 0.1.17 and earlier need this download once to gain update checking. Internet is needed for the update check, not for flashing the bundled firmware.

## Need help?

Click **Copy support details** in the app, then paste the report into your message to PyonTracker support. This reboots the tracker, captures startup and requests device/build information. Common Wi-Fi credential fields are redacted; review logs from custom firmware before sharing. Nothing is uploaded automatically.

The executable is currently unsigned. Download it from this repository or the resource link provided by PyonTracker.
