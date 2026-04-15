# Rabbit Music Player

Rabbit is a modern, high-performance Android music player built with Jetpack Compose and Material 3. It focuses on high-fidelity audio, immersive UI, and a seamless user experience.

## 🌟 Key Features

### 🎧 High-Fidelity Audio
- **Advanced Format Support**: Full support for Hi-Res (24-bit/96kHz+), Lossless (FLAC/ALAC), Dolby Atmos, and DTS:X.
- **Dynamic Quality Badges**: Real-time identification and visual tagging of audio quality and channel configuration (Mono, Stereo, Surround).
- **Audio Engine**: Powered by Android Media3 (ExoPlayer) for low-latency, gapless playback.

### 🎨 Immersive Design (Material 3)
- **Immersive Now Playing**: A full-screen album art experience with dynamic gradient overlays and contrast-optimized typography.
- **Segmented Seekbar**: A unique 35-segment digital seekbar with a minimal dot thumb for precise and stylish control.
- **Red Accent Theme**: A consistent, modern red-accented design language across all UI components (buttons, sliders, indicators).
- **Circular Aesthetics**: Consistent use of `CircleShape` for album art, mini-players, and playback controls.

### 📜 Lyrics & Metadata
- **Embedded Lyrics Support**: Direct rendering of embedded lyrics with a high-contrast overlay.
- **Online Lyrics Search**: Integrated capability to search for missing lyrics online.
- **Technical Info**: Detailed track metadata view including bitrate, sample rate, bit depth, and file paths.

### 📂 Library Management
- **Organized Browsing**: Easy navigation through Songs, Albums, and Artists using a themed `TabRow`.
- **Quick Search**: Real-time filtering of the entire music library.
- **Media Scanner**: Automatic background scanning of local storage to keep the library up to date.

## 🛠️ Tech Stack
- **Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Design System**: Material 3
- **Audio Engine**: Media3 (ExoPlayer & MediaSession)
- **Image Loading**: Coil
- **Architecture**: MVVM (Model-View-ViewModel)
- **Asynchronous**: Kotlin Coroutines & Flow

## 🚀 Getting Started
1. Clone the repository.
2. Open the project in **Android Studio (Ladybug or newer)**.
3. Sync Gradle and run the `:app` module.
4. Grant storage permissions when prompted to allow the app to scan your local music.

## 📸 UI Highlights
- **Library Screen**: Features a red-accented `TabRow` and circular album art list items.
- **Now Playing**: Full-screen artwork with a segmented seekbar and red FAB playback controls.
- **Settings**: Minimalist configuration for technical info display and library management.

---
*Developed by iamyourbrownstar*
