# Dream Mouse for Windows/Android
<p align="center"><img width="150" height="150" alt="icon" src="https://github.com/user-attachments/assets/0203090e-a42c-4221-a4bc-7946ad192229" /><br>This app turns your Google Daydream or Samsung Gear VR controller into a wireless mouse on Windows and Android devices</p>

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
- Windows PC with Bluetooth (macOS and Linux support coming soon) or an Android 8.0+ phone/tablet

### Installation on Windows

1. Download the [zip file](https://github.com/kaminoer/Dream-Mouse/releases/download/v2.0/Dream.Mouse-v2.0-Windows.zip).
2. Unzip the archive.
3. Pair your controller in Windows via Bluetooth.
   - *Daydream*: Hold the Home (circle) button.
   - *Gear VR*: Hold Home (house) until the light flashes.
4. Open Dream Mouse.exe.

### Installation on Android

1. Download the [apk file](https://github.com/kaminoer/Dream-Mouse/releases/download/v2.0/Dream.Mouse-v2.0-Android.apk).
2. Use a file browser to open the apk on your Android device.
3. Install the app. You may have to allow installation from unknown sources.
4. If you are on Android 13 or later, [allow restricted settings](https://support.google.com/android/answer/12623953?hl=en) for Dream Mouse. This is required to give the app permissions to Android Accessibility.
5. Pair your controller using Android's Bluetooth settings.
   - *Daydream*: Hold the Home (circle) button.
   - *Gear VR*: Hold Home (house) until the light flashes.
6. Find and open the Dream Mouse app. When asked, give the app permission to search for nearby devices and show notifications.
7. Tap **Enable Accessibility** -> **OPEN SETTINGS**.
8. Find Dream Mouse in Downloaded Apps and enable it to give permission to control the mouse.

---

## How to use

### Connecting

1. Turn on the controller and make sure it's paired.
2. Ensure the controller is lying flat on a stable surface for calibration.
3. The app will auto-detect whether you are using a Daydream or Gear VR controller. Alternatively, if you own both and want to specify the one you'd like to connect to, select your controller manually in Controller Type.
4. Click or tap **Connect** in Dream Mouse.
5. If it's your first time running the app, the controller connects with Test Mode enabled (on Android, you may have to scroll down to see it). Once you've tested your controller, disable Test Mode to control the mouse.

### Default Controls

Controls are fully customizable in the **Button Bindings** tab (Windows only). Here are the defaults:

| Daydream | Gear VR | Default Action |
|----------|---------|----------------|
| **Touchpad** | **Touchpad** | Move cursor (Swipe) |
| **Click Touchpad** | **Trigger** / **Click Touchpad** | Left Click |
| **Home Button (○)** | **Home Button (🏠)** | Right Click |
| **App Button** (—) | **Back Button** (↩) | Gyro Mouse - Hold (Windows) / Toggle (Android) and wave |
| **Vol Up** | **Vol Up** | Scroll Up |
| **Vol Down** | **Vol Down** | Scroll Down |

---

## Windows exclusive features

### Custom Button Bindings
Go to the **Button Bindings** tab to remap any button on the controller to:
- **Mouse Buttons**: Left/Right/Middle click, scroll.
- **Keyboard Keys**: Enter, Space, Esc, Arrows, etc.
- **System Actions**: Copy, Paste, Alt-Tab, Media Play/Pause, Volume Mute, etc.
- **Trigger Modes**: Set actions to trigger once, hold (while pressed), or toggle (on/off).
<img width="689" height="315" alt="bind_win" src="https://github.com/user-attachments/assets/71980cab-b064-4e8d-aeae-e71a3bd999cb" />

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

### Controller options
- **Controller Type**: Defaults to **Auto-detect**, but you can force Daydream or Gear VR mode if needed.
- **Mouse API (Windows)**: Choose between `SendInput` (Recommended, works in games and fullscreen apps) or `Pynput` (Desktop/windowed apps only).

### Sensitivity
- **Touch Sensitivity**: Speed of the touchpad cursor.
- **Gyro X/Y Speed**: Sensitivity of the motion controls.
- **Deadzone**: Helps prevent drift by ignoring tiny unintentional movements.

### Test Mode
When enabled, mouse control is disabled. Instead, you can see a live 2D visualizer of your controller inputs. Use this to test buttons and calibration without your mouse flying around the screen. Note that it shows the Daydream controller even if Gear VR is connected. I may update this at some point.

### Android Specific Settings
- **Enable Cursor**: Shows or hides the mouse cursor overlay.
- **Cursor Size**: Adjusts how big the pointer looks.
- **Scroll Strength**: How far page scrolls per click.
- **Keep Screen On**: Prevents device from sleeping while using the controller.

### Windows Specific Settings
- **Minimize to System Tray**: Sends the app to system tray instead of the taskbar when minimized. Useful if you want to hide it running in the background.

---

## Tips

- **Calibration matters**: Keep the controller still and flat when connecting.
- **Drifting?** If the cursor starts drifting in gyro mode, try increasing the **Gyro Deadzone** or disconnecting and reconnecting while keeping the controller flat.
- **Radial Menu**: Try binding the Radial Menu to the "Home" or "App" button for quick access to media controls or copy/paste while browsing.
- **Battery**: If things get wonky, your controller might just need a charge or a new battery.

---

## Troubleshooting

**Can't find the controller?**
- Ensure Bluetooth is on and the controller is paired in system settings.
- Waking the controller (press Home) *before* clicking **Connect** often helps.

**Controller connects but disconnects immediately?**
- Battery might be low.
- Try unpairing and repairing in Windows/Android Bluetooth settings.

---

## Acknowledgments

- [Daydream2HID](https://hardfault.life/p/daydream-controller) for Daydream reverse engineering info.

---

*Found a bug? Got a feature idea? Open an issue or PR!*
