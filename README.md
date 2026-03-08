# Dream Mouse for Windows/Android/Android TVs/Linux
<p align="center"><img width="150" height="150" alt="icon" src="https://github.com/user-attachments/assets/0203090e-a42c-4221-a4bc-7946ad192229" /><br>Dream Mouse turns your Google Daydream or Samsung Gear VR controller into a Bluetooth wireless air mouse on Windows, Linux, and Android devices. You can move the cursor by swiping on the touchpad or by waving the controller around (gyro mode). It features a fully customizable input system, letting you bind buttons to OS actions, keyboard keys, media controls, app launchers, and a radial menu for quick actions (desktop only).
</p>

https://github.com/user-attachments/assets/fd794340-fdf4-462a-b036-5d934026028d

<p align="center"><i>GearVR on Android</i></p>

https://github.com/user-attachments/assets/4a714923-f988-408c-a8d3-2752c76ea7af

<p align="center"><i>Daydream on Windows</i></p>

## Getting started

### What you need

- **Google Daydream controller** or **Samsung Gear VR Controller**
- Windows or Linux PC with Bluetooth (macOS support coming soon) or an Android 8.0+ phone/tablet/TV

### Installation on Windows

1. Download the [zip file](https://github.com/kaminoer/Dream-Mouse/releases/download/v3.0b/Dream.Mouse-v2.3a-Windows.zip).
2. Unzip the archive.
3. Pair your controller in Windows via Bluetooth.
   - *Daydream*: Hold the Home (circle) button.
   - *Gear VR*: Hold Home (house) until the light flashes.
4. Open Dream Mouse.exe.

### Installation on Android (Phones & Tablets)

1. Download the [apk file](https://github.com/kaminoer/Dream-Mouse/releases/download/v3.1-Android/Dream.Mouse-v3.1-Android.apk).
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

1. [Download the Android TV APK](https://github.com/kaminoer/Dream-Mouse/releases/download/v2.3/Dream.Mouse-v2.3-Android-TVs.apk).
2. Install the APK on your TV.
3. Open Dream Mouse. When asked, give the app permission to search for nearby devices (on older Android versions this is often simply called Bluetooth and/or Location) and show notifications.
5. Click **Enable Accessibility**.
6. If your Android TV exposes Accessibility settings for apps in the OS Settings, click **OPEN SETTINGS**, find Dream Mouse in Downloaded Apps and enable it to give permission to control the mouse. If your TV OS hides Accessibility settings (common on most Android/Fire TV builds), you may need to grant permission via ADB:
   `adb shell pm grant com.dreammouse android.permission.WRITE_SECURE_SETTINGS`

   Run this command from a computer or another device connected to your TV via ADB over WiFi and click **TRY ENABLE** in Dream Mouse.

### Installation on Linux

This is still a work in progress. See [here](https://github.com/kaminoer/Dream-Mouse/releases/tag/v2.1-Linux) for an experimental version.

## How to use

### Connecting

1. Turn on the controller and make sure it's paired (If your TV OS BT scan doesn't detect the controller, click **Scan & Pair** available in the Android TV Dream Mouse to pair the controller).
2. Ensure the controller is lying flat on a stable surface for calibration.
3. The app will auto-detect whether you are using a Daydream or Gear VR controller. Alternatively, if you own both and want to specify the one you'd like to connect to, select your controller manually in Controller Type.
4. Click or tap **Connect** in Dream Mouse.
5. If you need to recalibrate later, you can use the **Recalibrate** button.

### Default Controls

Controls are fully customizable in the **Button Bindings** section. On Android, each button supports short press, long press, and double press actions. Here are the defaults:

| Daydream | Gear VR | Default Action |
|----------|---------|----------------|
| **Touchpad** | **Touchpad** | Move cursor (Swipe) |
| **Press Touchpad** | **Trigger** / **Press Touchpad** | Left Click/Tap, hold the button on Android for long press |
| **Tap Touchpad** | **Tap Touchpad** | Left Click/Tap|
| **Home Button (○)** | **Home Button (🏠)** | - Windows, Linux: Right Click <br> - Android/Android TV: Press once to go back, hold to go home |
| **App Button** (—) | **Back Button** (↩) | Toggle Gyro Mouse Mode. Wave the controller to move the cursor |
| **Vol Up** | **Vol Up** | Scroll Up |
| **Vol Down** | **Vol Down** | Scroll Down |

- You can perform gestures on Android (for example, drag and drop) by holding the trigger/touchpad click and moving the cursor.
- On Android and Windows, you can enable Touchpad scrolling in gyro mouse mode and swipe up or down on the touchpad to scroll.
- On Android TV, you can enable Touchpad scrolling in gyro mouse mode and swipe up, down, left, or right on the touchpad to move focus to the next available tile or card in that direction.

## Features

### Custom Button Bindings
Go to the **Button Bindings** section to remap any button on the controller. On Android, each of the 6 physical buttons (Clickpad, App/Back, Home, Volume Up, Volume Down, and Trigger) supports three press types: **short press**, **long press**, and **double press**, giving you up to 18 customizable slots.

Available actions include:
- **Mouse**: Left Click, Right Click
- **Navigation**: Back, Home, App Switcher (Recents), Notification Shade, Quick Settings
- **Scrolling**: Scroll Up/Down/Left/Right
- **Media**: Play/Pause, Next/Previous Track
- **Volume**: Volume Up/Down
- **Display**: Brightness Up/Down, Screen On/Off
- **D-Pad**: DPad Up/Down/Left/Right
- **Input**: Toggle Gyro Mouse, AI Assistant, Voice Typing
- **Apps**: Launch any installed app

On Windows and Linux, you can also bind:
- **Keyboard Keys**: Enter, Space, Esc, Arrows, etc.
- **System Actions**: Copy, Paste, Alt-Tab, etc.
- **Trigger Modes**: Set actions to trigger once, hold (while pressed), or toggle (on/off).
<p align="center"><img width="1149" height="581" alt="bindings_win" src="https://github.com/user-attachments/assets/6e00b991-5029-43df-abe5-e37d2c8d1bdb" /></p>
<p align="center"><i>Button Bindings interface on Windows</i></p>

<p align="center"><img width="250" height="500" alt="bindings_android" src="https://github.com/user-attachments/assets/da83563c-fbfb-48ec-8bde-0eea5ded2e5c" /></p>
<p align="center"><i>Button Bindings interface on Android</i></p>

### Radial Menu (Windows and Linux only)
Bind any button to the **Radial Menu** action to unlock 8 extra virtual buttons.
1. Hold the bound button to make the menu appear at your cursor.
2. Move your mouse towards a slice (Play, Copy, Paste, etc.).
3. Release the button to execute the action.
You can customize the labels, colors, and actions for each slot in the **Radial Menu** tab.

<img width="1154" height="712" alt="obraz" src="https://github.com/user-attachments/assets/0cb93c59-fd95-4346-ab11-2d57a54a893e" />

### Test Mode
Enable **Test Mode** in the Options section to see a real-time controller state visualizer. It displays touch point position, button press states, and movement arrows. Test mode disables pointer control so you can inspect raw input without moving the cursor.

## Settings

### Controller Connection
- **Controller Type**: Defaults to **Auto-detect**, but you can force Daydream or Gear VR mode if needed.
- **Recalibrate**: Recalibrate on demand if drift occurs. Remember to put the controller on a flat surface before you click it.
- **Battery Status**: View current controller battery level with a color-coded indicator. The app alerts you when battery drops below 15%.

### Controller Options
- **Touch Sensitivity**: Speed of the touchpad cursor.
- **Gyro X/Y Speed**: Sensitivity of the motion controls.
- **Gyro Deadzone**: Helps prevent drift by ignoring tiny unintentional gyro movements.
- **Touch Deadzone**: Minimum touchpad movement required before the cursor responds.
- **Touchpad scrolling**: Lets you use the touchpad to scroll when gyro mouse mode is enabled. On Android, horizontal scrolling can be enabled separately.
- **Touchpad tap**: Controls whether tapping the touchpad performs an action. The tap action is configurable (defaults to Left Click). Separate settings are available for touchpad mouse mode and gyro mouse mode.

### Android Specific Settings
- **Reverse Scroll**: Inverts the scroll direction.
- **Auto Reconnect**: Automatically reconnect if connection is lost.
- **Quick Actions**: Disconnect or recalibrate directly from the notification.
- **Enable Cursor**: Shows or hides the mouse cursor overlay. The cursor auto-hides when no device is connected.
- **Cursor Size**: Adjusts how big the pointer looks.
- **Scroll Strength**: How far page scrolls.
- **Reset to Defaults**: Quickly reset all sliders and toggles.
- **GearVR Gyro Scale (Gear VR only)**: Adjust raw gyro scale before deadzone offsets.
- **Acceleration Curve**: Set pointer acceleration from linear (1.0) to faster speeds.
- **Cursor Smoothing**: Applies an EMA filter to reduce jitter.
- **Keep Screen On**: Prevents the screen from turning off while Dream Mouse is running.
- **Stop Service on Exit**: Stops the accessibility service when closing the app. Useful for compatibility with banking and security apps that refuse to work if an accessibility service is running.
- **Gyro Touchpad D-Pad**: In gyro mouse mode, tap on the touchpad edges (top, down, left, right) to send D-Pad directional input.
- **Gyro Touchpad Tap Hold**: In gyro mouse mode, tap and hold on the touchpad to perform continuous actions.
- **Advanced Tuning**: A hidden menu with 16 fine-tunable parameters for gesture detection (tap timing, drag thresholds, fling behavior, scroll sensitivity, etc.). Access it by tapping the version number 5 times.

### Windows Specific Settings
- **Minimize to System Tray**: Sends the app to system tray instead of the taskbar when minimized. Useful if you want to hide it and keep it running in the background.
- **Start minimized**. Lets you force Dream Mouse to start minimized. When combined with Minimize to System Tray, this lets you hide the app on boot, for example on PCs that you want to have Dream Mouse open and connected at all times.
- **Auto-connect on app startup**. With this option enabled, when you open Dream Mouse, it will automatically keep trying to connect to a controller until a successful connection is established. You may find it useful on PCs that don't have any other input devices connected and want to rely on Dream Mouse for controls. You can add Dream Mouse to your autostart applications in Windows settings and enjoy a wireless pointer experience without any setup on boot.
- **Auto-reconnect when controller disconnects**. With this option enabled, Dream Mouse will try to reconnect automatically until a connection with a controller is established. This triggers when connection status changes to disconnected for any reason.


## Tips

- **Calibration matters**: Keep the controller still and flat when connecting and calibrating.
- **Drifting?** If the cursor starts drifting in gyro mode, try increasing the **Gyro Deadzone** or recalibrating.
- **Radial Menu** (Windows and Linux only): Try binding the Radial Menu to the "Home" or "App" button for quick access to media controls or copy/paste while browsing.
- **Battery**: Percentage status is displayed in the app. You'll get a low battery alert at 15% on Android.

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

**Banking or security apps not working?**
- Turn on **Disable Accessibility on Exit** in Options, then close Dream Mouse before opening the banking app.
- Alternatively, disable Dream Mouse's Accessibility Service manually in Android settings.

> [!CAUTION]
> Dream Mouse uses Android's Accessibility Service and draws a system-level overlay to render a mouse cursor and simulate input events.
> Because of this, some banking, financial, and security-sensitive apps may block interaction while this app is running.
>
> Many banking apps implement security protections that:
>
> - Detect active Accessibility Services
> - Detect apps that draw overlays
> - Block input when another app can observe or modify screen interactions
>
> If you open a banking app while this accessibility service is active, you may see a message similar to:
>
> "For security reasons, access is disabled on your device."
>
> In most cases, functionality is restored after:
>
> - Disabling Dream Mouse's Accessibility Service (toggle in Options and close the app), or
> - Force stopping Dream Mouse
>
> This behavior is intentional and controlled by the banking app, not a bug in Dream Mouse.
> Modern financial apps are designed to prevent overlay-based phishing attacks, tapjacking, accessibility-based malware, and automated input injection.
> Since Dream Mouse uses similar system capabilities (for legitimate controller-based pointer control), it may be treated as a potential risk by those apps.
>
> Dream Mouse:
> - Does not collect personal data
> - Does not intercept credentials
> - Does not transmit user input
> - Runs entirely on-device
>
> However, individual apps may still restrict functionality as part of their internal security policies.

## Acknowledgments

- [Daydream2HID](https://hardfault.life/p/daydream-controller) for Daydream reverse engineering info.

*Found a bug? Got a feature idea? Open an issue!*
