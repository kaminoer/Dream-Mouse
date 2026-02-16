# Dream Mouse for Windows/Android/Android TVs/Linux
<p align="center"><img width="150" height="150" alt="icon" src="https://github.com/user-attachments/assets/0203090e-a42c-4221-a4bc-7946ad192229" /><br>This app turns your Google Daydream or Samsung Gear VR controller into a wireless mouse on Windows, Linux, and Android devices</p>

---

## What does it do?

Dream Mouse connects to your Daydream or Gear VR controller via Bluetooth and lets you use it as a wireless mouse. You can move the cursor by swiping on the touchpad or by waving the controller around (gyro mode). It features a fully customizable input system, letting you bind buttons to keyboard keys, media controls, and a radial menu for quick actions.

---
  
https://github.com/user-attachments/assets/fd794340-fdf4-462a-b036-5d934026028d 

<p align="center"><i>GearVR on Android</i></p>

https://github.com/user-attachments/assets/4a714923-f988-408c-a8d3-2752c76ea7af

<p align="center"><i>Daydream on Windows</i></p>

## Getting started

### What you need

- **Google Daydream controller** OR **Samsung Gear VR Controller**
- Windows or Linux PC with Bluetooth (macOS support coming soon) or an Android 8.0+ phone/tablet/TV

### Installation on Windows

1. Download the [zip file](https://github.com/kaminoer/Dream-Mouse/releases/download/v2.2/Dream.Mouse-v2.2-Windows.zip).
2. Unzip the archive.
3. Pair your controller in Windows via Bluetooth.
   - *Daydream*: Hold the Home (circle) button.
   - *Gear VR*: Hold Home (house) until the light flashes.
4. Open Dream Mouse.exe.

### Installation on Android (Phones & Tablets)

1. Download the [apk file](https://github.com/kaminoer/Dream-Mouse/releases/download/v2.2/Dream.Mouse-v2.2-Android.apk).
2. Use a file browser to open the apk on your Android device.
3. Install the app. You may have to allow installation from unknown sources.
4. If you are on Android 13 or later, [allow restricted settings](https://support.google.com/android/answer/12623953?hl=en) for Dream Mouse. This is required to give the app permissions to Android Accessibility.
5. Pair your controller using Android's Bluetooth settings.
   - *Daydream*: Hold the Home (circle) button.
   - *Gear VR*: Hold Home (house) until the light flashes.
6. Find and open the Dream Mouse app. When asked, give the app permission to search for nearby devices and show notifications.
7. Tap **Enable Accessibility** -> **OPEN SETTINGS**.
8. Find Dream Mouse in Downloaded Apps and enable it to give permission to control the mouse.

### Installation on Android TV / FireOS

There is a separate build optimized for Android TVs. This version handles pairing within the app to bypass limitations on some TV operating systems.

1. [Download the Android TV APK](https://github.com/kaminoer/Dream-Mouse/releases/download/v2.2/Dream.Mouse-v2.2-Android-TVs.apk).
2. Install the APK on your TV.
3. Open Dream Mouse. When asked, give the app permission to search for nearby devices (on older Android versions this is often simply called Bluetooth and/or Location) and show notifications.
5. Click **Enable Accessibility**.
6. If your Android TV exposes Accessibility settings for apps in the OS Settings, click **OPEN SETTINGS**, find Dream Mouse in Downloaded Apps and enable it to give permission to control the mouse. If your TV OS hides Accessibility settings (common on most Android/Fire TV builds), you may need to grant permission via ADB:
   `adb shell pm grant com.dreammouse android.permission.WRITE_SECURE_SETTINGS`
   
   Run this command from a computer or another device connected to your TV via ADB over WiFi and click **TRY ENABLE** in Dream Mouse.

### Installation on Linux

This is still a work in progress. See [here](https://github.com/kaminoer/Dream-Mouse/releases/tag/v2.1-Linux) for an experimental version.

---

## How to use

### Connecting

1. Turn on the controller and make sure it's paired (If your TV OS BT scan doesn't detect the controller, click **Scan & Pair** available in the Android TV Dream Mouse to pair the controller).
2. Ensure the controller is lying flat on a stable surface for calibration.
3. The app will auto-detect whether you are using a Daydream or Gear VR controller. Alternatively, if you own both and want to specify the one you'd like to connect to, select your controller manually in Controller Type.
4. Click or tap **Connect** in Dream Mouse.
5. If you need to recalibrate later, you can use the **Recalibrate** button.

### Default Controls

Controls are fully customizable in the **Button Bindings** tab (Windows and Linux only). Here are the defaults:

| Daydream | Gear VR | Default Action |
|----------|---------|----------------|
| **Touchpad** | **Touchpad** | Move cursor (Swipe) |
| **Press Touchpad** | **Trigger** / **Press Touchpad** | Left Click/Tap, hold the button on Android for long press |
| **Tap Touchpad** | **Tap Touchpad** | Left Click/Tap |
| **Home Button (○)** | **Home Button (🏠)** | - Windows, Linux: Right Click <br> - Android/Android TV: Press once to go back, hold to go home |
| **App Button** (—) | **Back Button** (↩) | Toggle Gyro Mouse Mode. Wave the controller to move the cursor |
| **Vol Up** | **Vol Up** | Scroll Up |
| **Vol Down** | **Vol Down** | Scroll Down |

- You can perform gestures on Android (for example, drag and drop) by holding the trigger/touchpad click and moving the cursor.
- On Android and Windows, you can enable Touchpad scrolling in gyro mouse mode and swipe up or down on the touchpad to scroll.
- On Android TV, you can enable Touchpad scrolling in gyro mouse mode and swipe up, down, left, or right on the touchpad to move focus to the next available tile or card in that direction.

---

## Windows and Linux exclusive features

### Custom Button Bindings
Go to the **Button Bindings** tab to remap any button on the controller to:
- **Mouse Buttons**: Left/Right/Middle click, scroll.
- **Keyboard Keys**: Enter, Space, Esc, Arrows, etc.
- **System Actions**: Copy, Paste, Alt-Tab, Media Play/Pause, Volume Mute, etc.
- **Trigger Modes**: Set actions to trigger once, hold (while pressed), or toggle (on/off).
<img width="695" height="355" alt="obraz" src="https://github.com/user-attachments/assets/bbd5efce-3517-433a-9651-6f9ed61b8c39" />


### Radial Menu
Bind any button to the **Radial Menu** action to unlock 8 extra virtual buttons.
1. Hold the bound button to make the menu appear at your cursor.
2. Move your mouse towards a slice (Play, Copy, Paste, etc.).
3. Release the button to execute the action.
You can customize the labels, colors, and actions for each slot in the **Radial Menu** tab.
<img width="695" height="393" alt="radial_win" src="https://github.com/user-attachments/assets/607cf5f2-c095-4cfa-9ca3-6d6a0316ff1b" />
<img width="365" height="361" alt="radial2_win" src="https://github.com/user-attachments/assets/07b235bc-1889-4f18-bb73-bda21aa73597" />

---

## Settings

### Controller Connection
- **Controller Type**: Defaults to **Auto-detect**, but you can force Daydream or Gear VR mode if needed.
- **Recalibrate**: Recalibrate on demand if drift occurs. Remember to put the controller on a flat surface before you click it.
- **Battery Status**: View current controller battery level.

### Controller Options
- **Touch Sensitivity**: Speed of the touchpad cursor.
- **Gyro X/Y Speed**: Sensitivity of the motion controls.
- **Deadzone**: Helps prevent drift by ignoring tiny unintentional movements.
- **Touchpad scrolling**: Lets you use the touchpad to scroll when gyro mouse mode is enabled.
- **Touchpad tap**: Controls whether tapping the touchpad to perform an action is enabled in touchpad mouse mode and gyro mouse mode.

### Android Specific Settings
- **Continuous Scroll**: Lets you hold the volume button to keep scrolling.
- **Auto Reconnect**: Automatically reconnect if connection is lost.
- **Quick Actions**: Disconnect or recalibrate directly from the notification.
- **Enable Cursor**: Shows or hides the mouse cursor overlay. The cursor auto-hides when no device is connected.
- **Cursor Size**: Adjusts how big the pointer looks.
- **Scroll Strength**: How far page scrolls per click.
- **Reset to Defaults**: Quickly reset all sliders and toggles.
- **GearVR Gyro Scale (Gear VR only)**: Adjust raw gyro scale before deadzone offsets.
- **Acceleration Curve (Experimental)**: Set acceleration from linear (1.0) to faster speeds.
- **Cursor Smoothing (Experimental)**: Applies an EMA filter to reduce jitter.

### Windows Specific Settings
- **Minimize to System Tray**: Sends the app to system tray instead of the taskbar when minimized. Useful if you want to hide it and keep it running in the background.

---

## Tips

- **Calibration matters**: Keep the controller still and flat when connecting and calibrating.
- **Drifting?** If the cursor starts drifting in gyro mode, try increasing the **Gyro Deadzone** or recalibrating.
- **Radial Menu** (Windows and Linux only): Try binding the Radial Menu to the "Home" or "App" button for quick access to media controls or copy/paste while browsing.
- **Battery**: Percentage status is displayed in the app. If things get wonky, check if you need a charge or a new battery.

---

## Troubleshooting

**Can't find the controller?**
- Ensure Bluetooth is on and the controller is paired in system settings.
- Waking the controller (press Home) *before* clicking **Connect** often helps.
- On Android TV: Use the app's internal pairing if the OS BT scan doesn't find the controller.

**Controller connects but disconnects immediately?**
- Battery might be low. Check the status indicator.
- Try unpairing and repairing in Windows/Android Bluetooth settings.
- Enable **Auto Reconnect** in settings.

**Mouse pointer is laggy, buttons lag or are often unresponsive?**
- This usually means that your device is not powerful enough to process the input commands from Dream Mouse in real time. Older generation Android TV systems often exhibit this behavior. Another reason could be the quality of the Bluetooth connection.

---

## Acknowledgments

- [Daydream2HID](https://hardfault.life/p/daydream-controller) for Daydream reverse engineering info.

---

*Found a bug? Got a feature idea? Open an issue or PR!*
