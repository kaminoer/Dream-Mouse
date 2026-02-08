# Dream Mouse 🎮🖱️
<p align="center"><img width="397" height="397" alt="icon" src="https://github.com/user-attachments/assets/0203090e-a42c-4221-a4bc-7946ad192229" /></p>

This app turns your Google Daydream VR controller into a wireless mouse. 

I had one of these controllers lying around collecting dust and thought I'd give it a try and see if it's possible to use it as a mouse.

<img width="745" height="626" alt="app" src="https://github.com/user-attachments/assets/8975642e-4359-47f3-b9f3-f1d777213655" />
---

## What Does It Do?

This app connects to your Daydream controller via Bluetooth and lets you use it as a mouse. You can move the cursor by swiping on the touchpad or by waving the controller around (gyro mode). It's pretty neat for presentations or couch browsing.

---

## Getting started

### What you need

- A Google Daydream controller
- Windows PC with Bluetooth (macOS and Linux support coming soon)

### Installation

1. Download the [zip file](https://github.com/kaminoer/Dream-Mouse/releases/download/v1.0/Dream.Mouse-v1.0-Windows.zip).

2. Unzip the file and open Dream Mouse.exe

## How to use

### Connecting

1. Pair your Daydream controller in Windows. If it's already paired, make sure it's connected. If you've already paired the controller earlier and it's off/not connected, press the home (circle) button to connect.
2. Make sure the controller is lying flat on a stable surface. This is required for calibration. Don't touch the controller.
3. Click **Connect** in Dream Mouse.
4. Wait for it to find your controller (takes a few seconds), calibrate, and connect.

Once connected, you're good to go!

### Controls

| Controller | Action |
|------------|--------|
| **Touchpad swipe** | Move cursor |
| **Touchpad click** | Left click |
| **Home button** (circle) | Right click |
| **App button** (line) + **wave controller** | Gyro mouse mode |
| **Volume Up** | Scroll up |
| **Volume Down** | Scroll down |

In the gyro mode, hold the app button and physically move the controller to move your cursor. Great for when you want to feel like a wizard.

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

### TEST MODE
When enabled:
- Shows a visual representation of your controller
- You can see all button presses and touch position in real-time
- **Mouse control is disabled** so you can mess around without your cursor going crazy

Use it to get your settings dialed in or just to see if everything is working. Turn it off when you actually want to use it as a mouse.

### Minimize to System Tray
When enabled, minimizing the app sends it to your system tray instead of the taskbar. Nice if you want it running in the background without cluttering things up. Double-click the tray icon to bring it back.

---

## Tips

- **Calibration matters** - Keep the controller still and flat when it's calibrating. If the gyro feels off, disconnect and reconnect.

- **Start with TEST MODE on** - Get familiar with how the touchpad maps to movement before going live.

- **Gyro is for fun, touchpad is for precision** - The gyro mode is cool but the touchpad gives you more control.

- **Battery** - The Daydream controller uses a regular rechargeable battery. If things get wonky, it might just need a charge.

---

## Troubleshooting

**Can't find the controller?**
- Make sure Bluetooth is on
- Press the home button on the controller to wake it up
- Try bringing it closer to your PC
- Make sure it's not connected to a phone or something else

**Cursor drifting in gyro mode?**
- Increase the gyro deadzone
- Try recalibrating by reconnecting

---

## Acknowledgments

- [Daydream2HID](https://hardfault.life/p/daydream-controller). Super helpful if you want to learn how the controller works.

---

*Found a bug? Got a feature idea? Open an issue or PR!*
