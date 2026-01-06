<p align="center">
  <img src="https://github.com/user-attachments/assets/42eb93fd-8082-4080-97ec-71f413da9847" height="200" />
  <img src="https://github.com/user-attachments/assets/de07cf42-f6e3-4830-940c-f554a8eecbe3" height="200" />
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

👉 **GitHub Release (v0.4)**  
[Download](https://github.com/Abubakar-doc/steer_beamng_guide/releases/tag/android-v0.4)

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

### 📱 Mobile App (v0.3)
* Accelerometer (tilt) steering support
* Static gear shifter option
* Faster button hold response
* Layout creation, editing & backup
* Support to add/spawn custom control buttons
* Multiple pages support

### 🖥️ Windows App (v2.0)
* Support for more custom buttons
* Increased custom button limit (up to 98)
* Improved compatibility with mobile layouts

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
<summary><strong>🖥️ Windows Helper App</strong></summary>

### Features

* Runs on **Windows**
* Built using **vJoy public library**
* Creates a **virtual steering wheel device**
* BeamNG detects it as real hardware

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
* **450° (default)**
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

**Manual**

* 5-speed
* 6-speed
* 7-speed
* 8-speed

**Interaction**

* Grab knob anywhere inside bounds
* Drag like a real shifter
* Snaps to nearest gear on release
* No need to look at the screen

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
