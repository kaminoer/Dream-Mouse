# Dream Mouse for Windows/Android
<p align="center"><img width="150" height="150" alt="icon" src="https://github.com/user-attachments/assets/0203090e-a42c-4221-a4bc-7946ad192229" /><br>This app turns your Google Daydream VR controller into a wireless mouse on Windows and Android devices</p>

<p align="center"><img width="745" height="720" alt="app" src="https://github.com/user-attachments/assets/b67ce969-6475-4f30-b0d3-18f2f808ded0" /><br><i>Dream Mouse on Windows</i></p>

<p align="center"><img width="745" height="800" alt="app" src="https://github.com/user-attachments/assets/97841889-acf3-4e29-954d-431a5c76aded" /><br><i>Dream Mouse on Android</i></p>

---



## What does it do?

This app connects to your Daydream controller via Bluetooth and lets you use it as a mouse. You can move the cursor by swiping on the touchpad or by waving the controller around (gyro mode). It's pretty neat for presentations or couch browsing.

---

## Getting started

### What you need

- A Google Daydream controller
- Windows PC with Bluetooth (macOS and Linux support coming soon) or an Android 8.0+ phone/tablet

### Installation on Windows

1. Download the [zip file](https://github.com/kaminoer/Dream-Mouse/releases/download/v1.0.1/Dream.Mouse-v1.0.1-Windows.zip).
2. Unzip the archive.
3. Pair your Daydream controller. If you've already paired the controller earlier and it's off/not connected, press the home (circle) button to connect.
4. Open Dream Mouse.exe

### Installation on Android

1. Download the [apk file](https://github.com/kaminoer/Dream-Mouse/releases/download/v1.0/Dream.Mouse-v1.0-Android.apk).
2. Use a file browser to open the apk on your Android device.
3. Install the app. You may have to allow installation from unknown sources.
4. If you are on Android 13 or later, [allow restricted settings](https://support.google.com/android/answer/12623953?hl=en) for Dream Mouse. This is required to give the app permissions to Android Accessibility, and allow it to show a cursor and control the mouse.
5. Pair your Daydream controller using Android's Bluetooth settings. If you've already paired the controller earlier and it's off/not connected, press the home (circle) button to connect.
6. Find the Dream Mouse app in your app drawer or home screen.
7. Open Dream Mouse. Allow it to find nearby devices and show notifications when asked.
8. Tap **Enable Accessibility**.
9. Tap **OPEN SETTINGS**.
10. Look for Downloaded apps and Dream Mouse. Depending on your Android version and phone, this may look different.
11. Enable Dream Mouse in your Accessibility settings to give it permission to control the mouse.

## How to use

### Connecting

1. Connect the controller to your device in Bluetooth settings. If it's paired, it should auto connect when you press the home (circle) button.
2. Make sure the controller is lying flat on a stable surface. This is required for calibration. Don't touch the controller.
3. Click or tap **Connect** in Dream Mouse.
4. Wait for it to find your controller (takes a few seconds), calibrate, and connect.

Once connected, you're good to go! You can now dial in your settings if required.

### Controls

| Controller | Action |
|------------|--------|
| **Touchpad swipe** | Move cursor |
| **Touchpad click** | Left click |
| **Home button** (circle) | Right click on Windows / Long press on Android |
| **App button** (line) + **wave controller** | Gyro mouse mode |
| **Volume Up** | Scroll up |
| **Volume Down** | Scroll down |

To use the gyro mode, hold the app button and physically move the controller to move your cursor. Great for when you want to feel like a wizard.

---

## Settings

### Touch Sensitivity
How fast the cursor moves when you swipe on the touchpad. Crank it up if you want to zoom across the screen, lower it for precision work.

### Gyro X Speed / Gyro Y Speed
Controls how sensitive the gyro mouse is when you're waving the controller around. If the cursor is flying off the screen, turn these down. If it feels sluggish, bump them up.

### Gyro Deadzone
Ignores tiny movements when using gyro mode. Helps prevent cursor drift when you're trying to hold the controller still. Higher = more stable but less responsive.

### Touch Deadzone
Same idea but for the touchpad. If the cursor moves when you're just resting your finger, increase this a bit.

### Test Mode
When enabled:
- Shows a visual representation of your controller
- You can see all button presses and touch position in real-time
- **Mouse control is disabled** so you can mess around without your cursor going crazy

Use it to get your settings dialed in or just to see if everything is working. Turn it off when you actually want to use it as a mouse.

### Minimize to System Tray (Windows only)
When enabled, minimizing the app sends it to your system tray instead of the taskbar. Nice if you want it running in the background without cluttering things up. Double-click the tray icon to bring it back.

### Enable Cursor (Android only)
Shows or hides the cursor.

### Cursor Size (Android only)
Controls the size of the cursor. Useful if you want to sit back and control your Android device from a distance.

### Scroll Strength (Android only)
Controls how far the page scrolls with volume buttons.

### Keep Screen On (Android only)
Prevents the screen from sleeping.

---

## Tips

- **Calibration matters** - Keep the controller still and flat when it's calibrating. If the gyro feels off, disconnect and reconnect.

- **Start with TEST MODE on** - Get familiar with how the touchpad maps to movement before going live.

- **Gyro is for fun, touchpad is for precision** - The gyro mode is cool but the touchpad gives you more control.

- **Battery** - The Daydream controller uses a rechargeable battery. If things get wonky, it might just need a charge.

---

## Troubleshooting

**Can't find the controller?**
- Make sure Bluetooth is on
- Press the home button on the controller to wake it up
- Try bringing it closer to your PC / Android device
- Make sure it's not connected to something else

**Cursor drifting in gyro mode?**
- Increase the gyro deadzone
- Try recalibrating by reconnecting

---

## Known issues
The cursor may appear dark on some older Android devices with dark mode enabled (observed on an older Xiaomi device running Android 10). The workaround is to disable dark mode, either system wide or just for the Dream Mouse app. 

---

## Acknowledgments

- [Daydream2HID](https://hardfault.life/p/daydream-controller). Super helpful if you want to learn how the controller works.

---

*Found a bug? Got a feature idea? Open an issue or PR!*
