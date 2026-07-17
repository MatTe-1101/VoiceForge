
# 🎤 VoiceForge

<p align="center">
  <img src="docs/images/banner.png" alt="VoiceForge Banner" width="100%">
</p>

<p align="center">
  <strong>Turn your Android device into a powerful real-time wireless microphone.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/language-Kotlin-7F52FF?logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4" alt="Compose">
  <img src="https://img.shields.io/badge/Material-Material%203-1976D2" alt="Material 3">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT">
  <img src="https://img.shields.io/badge/status-In%20Development-orange" alt="Development">
</p>

---

## 🚀 About

**VoiceForge** is an open-source Android application designed to transform your smartphone into a professional live microphone and voice processing studio.

Unlike traditional microphone apps, VoiceForge aims to provide a modular real-time audio engine capable of:

* 🎤 Low-latency live microphone monitoring
* 🔊 Real-time audio amplification
* 🎛 Professional audio processing
* 🎵 Voice effects
* 🎼 AutoTune (planned)
* 📡 Wireless audio streaming
* 🎧 Bluetooth audio support
* 🎚 Advanced mixer
* 💾 Presets & profiles
* 🎨 Beautiful Material You interface

The long-term goal is to become one of the most advanced open-source audio applications available for Android.

---

# ✨ Planned Features

## 🎤 Live Microphone

* Real-time microphone monitoring
* Ultra-low latency
* Gain control
* Mute
* Output routing
* Volume boost

## 🎚 Audio Processing

* Noise Gate
* Compressor
* Limiter
* Equalizer
* Noise Reduction
* Echo Cancellation
* Feedback Reduction

## 🎵 Voice Effects

* Reverb
* Delay
* Chorus
* Flanger
* Phaser
* Robot Voice
* Megaphone
* Radio
* Alien
* Demon
* Helium
* Deep Voice

## 🎼 AutoTune (Roadmap)

* Real-time pitch correction
* Major/Minor scales
* Key selection
* Humanize
* Vibrato
* Formant correction
* Adjustable correction speed

## 📡 Connectivity

* Phone speaker
* Wired headphones
* Bluetooth audio
* USB audio devices
* Wi-Fi audio streaming *(planned)*

---

# 🏗 Architecture

VoiceForge follows a modern Android architecture.

* Kotlin
* Jetpack Compose
* Material 3
* MVVM
* Clean Architecture
* Dependency Injection (Hilt)
* Navigation Compose
* DataStore
* Room
* Coroutines
* Flow

Future versions will integrate a native DSP engine using **C++** and **Oboe** for professional-grade real-time audio performance.

---

# 📂 Project Structure

```text
VoiceForge
│
├── app/
├── core/
│   ├── audio/
│   ├── dsp/
│   ├── autotune/
│   ├── bluetooth/
│   ├── network/
│   └── common/
│
├── feature/
│   ├── home/
│   ├── live/
│   ├── mixer/
│   ├── effects/
│   └── settings/
│
├── designsystem/
├── docs/
└── .github/
```

---

# 🎨 Design

VoiceForge is built entirely with **Material You (Material 3)**.

Design goals:

* Clean
* Fast
* Accessible
* Animated
* Beginner friendly
* Professional

---

# 📈 Roadmap

## Version 0.1

* Project setup
* Material You UI
* Navigation
* Home screen
* Audio engine foundation

## Version 0.2

* Live microphone
* Audio routing
* Volume controls

## Version 0.3

* Equalizer
* Compressor
* Noise Gate

## Version 0.4

* Voice Effects

## Version 0.5

* AutoTune Engine

## Version 1.0

* Stable release
* Wireless streaming
* Plugin system
* Complete documentation

---

# 🤝 Contributing

Contributions are welcome.

Ideas, bug reports, pull requests and feature suggestions are encouraged.

If you'd like to help improve VoiceForge, feel free to open an Issue or submit a Pull Request.

---

# 📜 License

This project will be released under the **MIT License**.

---

# ⭐ Support the Project

If you enjoy VoiceForge, consider giving the repository a ⭐.

It helps the project grow and reach more developers.

---

<p align="center">
Made with ❤️ using Kotlin, Jetpack Compose and open-source technologies.
</p>
