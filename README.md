<p align="center">
  <img src="https://github.com/user-attachments/assets/42eb93fd-8082-4080-97ec-71f413da9847" height="200" />
  <img src="https://github.com/Abubakar-doc/steer_beamng_guide/blob/main/assets/console_manual_gearbox.png" height="200" />
</p>

**Steer BeamNG** is an **hobby project** that gives you an **enhanced driving experience** in any game that supports **steering hardware**, using an **Android phone as a controller**.

Built purely for **fun, learning, and experimentation**, this project explores how far a mobile device can replicate real steering hardware.

---

## 💬 Community

Join the discussion on Discord:  
👉 [https://discord.gg/ubXXndzd](https://discord.gg/6xbQEECnma)

---

## 📥 Analytics

[![Total Downloads](https://img.shields.io/github/downloads/Abubakar-doc/steer_beamng_guide/total.svg)]()
[![Latest Release Downloads](https://img.shields.io/github/downloads/Abubakar-doc/steer_beamng_guide/latest/total.svg)]()

---

## ⬇️ Downloads

### 📱 Android Controller App

👉 **GitHub Release (v0.5)**  
[Download](https://github.com/Abubakar-doc/steer_beamng_guide/releases/tag/android-v0.5)

👉 **Google Drive (backup)**  
[Download](https://drive.google.com/drive/folders/1v5a4XZ01TdK4u7N93i6R76977p9U6g6d?usp=drive_link)

---

### 🖥️ Windows Helper App

👉 **GitHub Release (v2.0)**  
[Download](https://github.com/Abubakar-doc/steer_beamng_guide/releases/tag/v2.0)

👉 **Google Drive (backup)**  
[Download](https://drive.google.com/drive/folders/1TUNcVbo4Q0VQBiAy46MAfK1aTaKlzSSX)

---

## 🆕 What’s New (Latest Updates)

### 📱 Mobile App (v0.6) - Major Update
-   **Sequential Gearbox Mode**: New high-performance +/- shifting logic for racing and GT3 simulations.
-   **Enhanced Haptic Feedback**: Advanced motor mapping that translates real-time FFB data into 4 tunable intensity bands (Low, Med, High, Max).
-   **Universal Help System**: Premium interactive guide system with high-res screenshots and loading shimmer animations.
-   **Interactive Image Viewer**: Swipeable gallery with pinch-to-zoom and animated double-tap-to-zoom support.
-   **Context-Aware Help**: Dedicated help buttons in every configuration screen (Connection, Controls, Layout, Haptics).

### 🖥️ Windows App (v3.0) - Major Update
*   **Force Feedback (FFB) Listening**: New capability to receive real-time physics and torque data from the game and sync it to your phone.
*   **Sequential Gearbox Support**: Native support for the Android app's new +/- shifting logic.
*   **Expanded Button Mapping**: Support for up to 128 custom vJoy buttons.
*   **Improved Compatibility**: Refined for complex multi-page mobile layouts.

---

<details>
<summary><strong>🚀 Project Overview</strong></summary>

Steer BeamNG works as a **two-part system**:

* **Windows Helper App**

  * Creates a virtual steering wheel using **vJoy**
* **Android Controller App**

  * Sends real-time control input over network

BeamNG detects the setup as a **real steering wheel**.

</details>

---

<details>
<summary><strong>🖥️ Windows Helper App (v3.0)</strong></summary>

### Features

* Runs on **Windows**
* Built using **vJoy public library**
* Creates a **virtual steering wheel device** (up to 128 buttons)
* BeamNG detects it as real hardware
* **Force Feedback (FFB)**: Listens to the game's Torque and physics data and sends it to the phone.
* **Sequential Gearbox Mapping**: Ready to work with the Android +/- shifter logic.

### Installer

The installer automatically:

* Installs the Helper App
* Installs **vJoy**
* Configures **Windows Firewall**

  * Allows UDP send/receive

### Networking

* **Protocol:** UDP
* **Port:** 5000
* Supports:

  * Single Android user
  * Multiple Android users simultaneously

</details>

---

<details>
<summary><strong>📱 Android Controller App (Detailed)</strong></summary>

### Real-Time Network Status

* Live **ping indicator (ms)**
* Shows connection health instantly

---

### 🎛️ Vehicle Action Buttons

* Fix vehicle
* Flip vehicle
* Gearbox mode change
* Ignition
* Fog light
* Headlight
* Flash
* Left / Right indicator
* Hazard light
* Diff lock
* ESC
* 4WD
* Camera zoom in / out
* Camera change
* Camera behind
* Horn

**Hold supported**

* Fix
* Ignition
* Zoom in / out
* Camera behind

---

### 🛞 Steering Wheel

* Real steering-wheel behavior
* Thumb-rotation based
* Smooth & sensitive input
* Springs back to center

**Supported angles**

* 270°
* 360°
* **450° (default)** = 900° total lock for realistic physics
* 540°
* 720°
* 900°

**Special**

* Horn in wheel center
* Hold center → speedy flashes

---

### ⚙️ Gearbox System

**Automatic**

* P / R / N / D / S

**Sequential**

* High-performance +/- shifting logic.
* Ideal for racing and GT3 cars.

**Manual**

* 5-speed
* 6-speed
* 7-speed
* 8-speed

**Interaction**

* **Blind Shifting**: Grab anywhere in the gearbox area to register the shifter knob for eyes-free driving.
* Drag like a real shifter
* Snaps to nearest gear on release

---

### 🦶 Pedal System (3-in-1)

Single pedal supports:

* Accelerator
* Brake / Reverse
* Handbrake

**Usage**

* Drag up → accelerate
* Drag down → brake
* Left side → handbrake

**Advanced**

* Accelerator + handbrake
* Brake + handbrake
* Neutral + handbrake

All with **one thumb**.

---

### 🎥 Camera Controls

* Camera buttons
* Free camera joystick
* Double-tap joystick → camera reset

---

### ⚙️ Advanced Features

-   **Context-Aware Help**: Dedicated help buttons in every configuration screen (Connection, Controls, Layout, Haptics).
-   **Universal Help System**: Premium interactive guide system with high-res screenshots and loading shimmer animations.
-   **Interactive Image Viewer**: Swipeable gallery with pinch-to-zoom and animated double-tap-to-zoom support.
-   **Sequential Gearbox Mode**: New high-performance +/- shifting logic for racing and GT3 simulations.
-   **Enhanced Haptic Feedback**: Advanced motor mapping that translates real-time FFB data into 4 tunable intensity bands (Low, Med, High, Max).
-   **Advanced Layout Manager**: Support for multiple pages per layout, spawning any control type, and custom vJoy button mapping (slots 34+).

---

### ⭐ Favorites & Auto Connect

* Favorite a Windows device
* Auto-discover & auto-connect on app restart

---

### 🔄 Connectivity Handling

* Automatic reconnect
* Manual connect / disconnect from settings
* Restart app if required

</details>

---

<details>
<summary><strong>🔧 Input & Game Binding</strong></summary>

* All inputs map to **vJoy axes & buttons**
* Users must bind controls inside **BeamNG**
* Works like any real steering wheel
* **vJoy Monitor** can be used to verify inputs

</details>

---

<details>
<summary><strong>📐 Layout Customization</strong></summary>

### Custom UI Layouts
*   Create and manage **unlimited custom layouts** for different car types (drift, truck, F1).
*   **Multi-Page Layouts**: Separate your main driving controls from secondary switches (lights, ignition) using multiple pages.
*   **Dynamic Spawning**: Enter **Edit Mode** to live-spawn steering wheels, pedals, and shifters.
*   **Custom vJoy Buttons**: Create unique buttons mapped to vJoy slots (up to 128) and place them anywhere.
*   **Import/Export**: Share your `.layout.json` files with other players or back them up to your device.

</details>

---

<details>
<summary><strong>📳 Haptic (Force) Feedback</strong></summary>

### Real-Time Torque Simulation
*   **Force Feedback Mapping**: Translates raw Torque data from Windows v3.0 helper into phone vibrations.
*   **4 Intensity Bands**: Categorizes feedback into **Low, Medium, High, and Max** effects (like road texture vs. curb strikes).
*   **Range Editor**: Visually set the thresholds for when each vibration effect should kick in.
*   **Vibration Calibration**: Set the motor intensity (1–100%) for each category to match your specific phone hardware.
*   **Game Setup**: Requires enabling **Force Feedback** in game settings (e.g., BeamNG) and selecting the **Gamepad** feedback type.

</details>

---

<details>
<summary><strong>📟 Motion (Accelerometer) Steering</strong></summary>

### Tilt-to-Steer
*   **Realistic Rotation**: Control your car by tilting your phone like a physical steering wheel (up to 1080°).
*   **Smoothing Factor**: Tune the input smoothing to eliminate jitters while maintaining responsiveness.
*   **Calibration**: Zero-out your phone's tilt to match your natural resting position.
*   **Mode Swapping**: Easily toggle between Motion and Thumb-Drag steering modes in the settings.

</details>

---

<details>
<summary><strong>📖 Universal Help & UI</strong></summary>

### Context-Aware Guidance
*   **Multi-Screen Help**: Dedicated help buttons in Connections, Controls, Layouts, and Haptics.
*   **Premium Viewers**: Interactive, high-resolution image galleries with **Pinch-to-Zoom** and **Double-tap zoom**.
*   **In-Game Binding**: Built-in screenshot guides showing exactly how to map vJoy inputs in simulation games.
*   **Invert Display**: Support for flipping the entire UI for left-handed play or unique cockpit mounting positions.

</details>

---

<details>
<summary><strong>🎯 Purpose of This Project</strong></summary>


* Learn **Flutter & real-time networking**
* Explore **virtual input devices**
* Experiment with **vJoy**
* Enjoy BeamNG without physical hardware

</details>

---

<details>
<summary><strong>⚠️ Disclaimer</strong></summary>

* Personal hobby project
* Experimental & unstable by nature
* Not affiliated with BeamNG or vJoy
* Use at your own risk

</details>

---

<details>
<summary><strong>🤝 Contributions</strong></summary>

Open for:

* Learning
* Experimentation
* Improvements

Feel free to fork or suggest ideas.

</details>
