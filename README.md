# CopifyX ✋

**CopifyX** is a powerful, privacy-first Android utility that allows you to select and copy text from almost any application—even those that normally restrict text selection (like Instagram, YouTube, or system menus).

## ✨ Features

- **Universal Grab**: Extract text from any screen using Android's Accessibility Services.
- **Floating Bubble**: A draggable, non-intrusive floating button for quick access.
- **Quick Settings Tile**: Trigger a text grab or toggle the floating button directly from your notification shade.
- **Privacy First**: No **INTERNET** permission. Your data never leaves your device.
- **Modern UI**: Built with Jetpack Compose and Material 3, featuring a sleek "Deep Space" theme.

## 🚀 How to Use

1. **Enable Accessibility Service**: After installing, open the app and follow the prompt to enable CopifyX in your device's Accessibility settings.
2. **Trigger Grab**:
   - Tap the **Floating ✋ Button** on your screen.
   - Or, use the **CopifyX Tile** in your Quick Settings.
3. **Select & Copy**: A text selection overlay will appear with all the readable text on your screen. Select the portion you need and hit **COPY TEXT**.
4. **Dismissing**: Drag the floating button to the bottom "✕" to hide it, or toggle it back on via the app/tile.

## 🛡️ Privacy & Security

CopifyX is designed to be completely offline:
- **Zero Data Collection**: No analytics, no tracking.
- **No Internet Access**: The app does not request the `INTERNET` permission, ensuring total data isolation.
- **Local Processing**: Text extraction happens entirely on-device via the Accessibility API.

## 🛠️ Technical Details

- **Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Service**: `AccessibilityService` (for screen content analysis)
- **Minimum SDK**: API 26 (Android 8.0)
- **Target SDK**: API 36

---
*Created by [Bapi Karmakar/[GitHub](https://github.com/Bapi-Karmakar-Lab)]*
