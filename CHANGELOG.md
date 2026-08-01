<div align="center">

# 🚀 Lunaris AOSP Changelog

### Redmi K50i / POCO X4 GT (xaga)

![Android](https://img.shields.io/badge/Android-16-3DDC84?style=for-the-badge&logo=android)
![Latest](https://img.shields.io/badge/Latest-v3.12-blue?style=for-the-badge)
![Maintainer](https://img.shields.io/badge/Maintainer-Rohan-red?style=for-the-badge)

</div>

| Version | Date |
|---------|------|
| v3.12 | July 31, 2026 |
| v3.11 | June 7, 2026 |
| v3.10 Hotfix 1.2 | May 20, 2026 |
| v3.10 Hotfix | May 10, 2026 |
| v3.10 | May 6, 2026 |
| v3.9 | April 21, 2026 |
| v3.8 Hotfix | March 23, 2026 |
| v3.8 | March 6, 2026 |
| v3.7 | February 17, 2026 |

> [!NOTE]
> **Latest stable release:** **Lunaris AOSP v3.12**

---

# 🚀 Lunaris AOSP v3.12 - xaga

📅 **July 31, 2026**

---

### ✨ Highlights

- 🎵 System-wide music lyrics with LRCLIB integration.
- 🌙 Added System Popup Bar.
- 🎨 Per-app icon customization.
- 🖼️ Automatic wallpaper subject extraction.
- 🔊 Built-in AtmosphereEffect.
- 📸 Clipboard screenshot workflow.
- 📶 QS Volume Panel.
- 📱 Third-party search widget support in Launcher dock.
- 🎮 Status Bar Lyrics.

---

### ⚡ Improvements

- Improved QS expansion and tile animations.
- Improved brightness slider animation and haptics.
- Improved Dynamic Bar animations.
- Improved launcher blur animations.
- Improved custom clock layouts.
- Improved lyrics sync timing.
- Optimized shade blur.
- Updated Pixel fingerprints, wallpaper, GMS and optimized routines.

---

### ➕ Added & Features

- Backup & Restore in IdleManager.
- Kill App action in Dynamic Bar.
- Auto Brightness tile.
- Sidebar auto-hide & fullscreen mode.
- Ambient Action for Shake Gesture.
- Themed icon customization.
- Gradient clock colors.
- Two new NOS4 clock styles.
- Bold status bar clock.
- Blur for heads-up notifications.
- Launcher folder customization.
- Screenshot copy to clipboard.
- Selectable blur algorithms.

---

### 🎨 Customization

- Bottom Fade for Depth Wallpaper.
- Hex input for clock colors.
- Launcher compact search bar.
- Editable app names.
- Album art color mode.
- Toggle launcher burn-in.
- Toggle lock gesture.
- Toggle recent scroll vibration.
- Notification/QS scrim alpha controls.

---

### 🔄 System Changes

- Launcher3 as default launcher.
- USB prompt bottom sheet.
- Vanilla prebuilts updated.
- Base cleanup.
- Last major Android 16 release.

---

### 🐞 Fixes

- Fixed clock color reset.
- Fixed status bar brightness jumps.
- Fixed Now Playing flicker and seekbar.
- Fixed activity transition hangs.
- Fixed live captions & cinematic photo downloads.
- Fixed launcher unlock animation.
- Fixed Dynamic Bar clipping & torch strength.
- Fixed sleep mode handler.
- Fixed OOS icon crash.
- Fixed translucent notifications.
- Fixed Keyguard music chip.
- Fixed Smart 5G service.

---

## 🚀 Lunaris AOSP v3.11 - xaga

📅 **June 7, 2026**

---

### ✨ Highlights

* 📶 **Split QS:** Improved pulldown animation, added left/right swipe gestures, and introduced directional swipe controls (WIP).
* 🕒 **Clock Engine:** Reworked custom clocks with 15 new styles, weather support, and refined weather/date text alignment and coloring.
* 🎨 **Monet & Customization:** Advanced Monet customisation, LC info widget color/opacity controls, and album art color override for lockscreen clock.
* 🎮 **Recents & Launcher:** Custom recents animations, task corner radius setting, notification badge counts, and adaptive icon pack shape support.
* 🔊 **Audio:** Added Dolby Atmos support.

---

### ⚡ Improvements

* **System:** Merged new Lineage changes.
* **Dynamic Bar:** Updated color tokens, aligned expanded cards to top center, and improved extended media text color in light mode.
* **Quick Settings:** Replaced Quickspace OOS clock color polling with static split color; added haptics to QS widget sliders.
* **Clocks:** Moved weather text next to clock date on most custom clocks; matched weather text styling with clock date.
* **Lockscreen:** Improved bouncer fallback color; replaced white flash on screen wakeup in light mode with proper scrim.
* **Launcher:** Improved app-to-home animation; updated launcher random messages.
* **Recents:** Improved custom recents animations.
* **Notifications:** Improved essential notifications.
* **Status Bar:** Fixed Wi-Fi and signal icon sizing.
* **Haptics:** Replaced MSDL haptics with native haptic feedback on tiles.
* **UI:** Enabled Material 3 for document UI (file manager).

---

### ➕ Added & Features

* 📶 **Quick Settings:** Implemented vertical brightness slider expanding.
* 📶 **Split QS:** Added left/right swipe gestures; directional swipe for split QS (WIP).
* 🕒 **Clocks:** Added 15 new clock styles with weather support; album art color override for lockscreen clock.
* 🎨 **Customization:** Color customisation and opacity control for LC info widget; center alignment option for LC compact notification icons; advanced Monet customisation.
* 📸 **System:** Added partial screenshot action.
* 🌙 **AOD:** Added back peek AOD.
* 📱 **Recents:** Added recents task corner radius setting; notification badge counts; adaptive gesture pill window controls for freeform.
* 🎨 **Icons:** Respect adaptive icon pack shapes.
* 🖼️ **Wallpapers:** Live wallpapers optional with flag (enabled by default).
* 📷 **Apps:** Google Photos optional with flag (enabled by default).
* 🔊 **Audio:** Added Dolby Atmos.

---

### 🔄 System Changes

* Temporarily disabled split notification shade when Split QS is on in landscape.

---

### 🐞 Fixes

* 🐛 **Dynamic Bar:** Fixed collapse event; fixed extended media text color in light mode.
* 🐛 **Quick Settings:** Fixed volume slider fill not hiding at zero volume; fixed slider widget inner corner radius when set rounded; fixed QS media position reset issue in QQS and QS.
* 🐛 **Clocks:** Fixed custom clock weather text not following clock color; fixed clock scale overflowing layout.
* 🐛 **Haptics:** Fixed always-on haptics mode triggering visual pulse.
* 🐛 **Gestures:** Fixed shake gesture ringer mode not working.
* 🐛 **Status Bar:** Fixed battery percentage color when status bar tint is on.
* 🐛 **Media:** Removed progress bar from media chip.
* 🐛 **Security:** App lock and sandbox fixes.

---

## 🚀 Lunaris AOSP v3.10 (Hotfix 1.2) - xaga

📅 **May 20, 2026**

---

### ✨ Highlights

* 🎨 **Clock Engine Upgrades:** Added new clock styles, updated layout sizes, introduced an option to browse all available clocks, and added **Skydrove** color customization.
* ⚙️ **Interface & Controls:** Introduced an initial **Split QS** (Quick Settings) option and a new gesture for status bar brightness control.
* 🛠️ **Performance & Stability:** Resolved performance drops associated with the OneUI app drawer style and fixed a critical app lock notification issue.

---

### ⚡ Improvements

* **Clocks:** Updated and refined specific custom clock sizes for better visual alignment.
* **Launcher3:** Implemented the L3 popup unlock animation for a smoother device wake experience.

---

### ➕ Added & Features

* ⚙️ **Status Bar:** Added status bar brightness control functionality.
* 📶 **Quick Settings:** Introduced an initial **Split QS** option.
* 🧠 **Idle Manager:** Added a new preference to trigger the Idle Manager *only* when Sleep Mode is turned on.
* 🔋 **System Visuals:** Enabled the power button Gemini animation.

#### 🎨 Customization

* **Clocks:** Added an option to browse all available clock styles in the selection menu.
* **Colors:** Implemented **Skydrove** color customization for clock styles.
* **Clocks:** Integrated several new clock faces into the collection.

---

### 🐞 Fixes

* 🐛 **Launcher:** Fixed performance issues and sluggishness when using the OneUI app drawer style.
* 🐛 **System:** Fixed an issue where app lock notifications were not behaving or hiding correctly.

---

## 🚀 Lunaris AOSP v3.10 (Hotfix) - xaga

📅 **May 10, 2026**

---

### ✨ Highlights

* 🛡️ **Security & Integrity:** Switched to the **Tricky Store** implementation for better integrity and app compatibility.
* 🚀 **Boot Performance:** Significantly reduced high CPU usage during the boot process, leading to faster load times and less heat after a reboot.
* 🛠️ **Stability Fixes:** Resolved critical issues with system-wide blur, screen flickering in freeform mode, and AOD fingerprint visibility.

---

### ⚡ Improvements

* **Dynamic Bar:** Further under-the-hood optimizations for better responsiveness.
* **Sandbox:** Performance optimizations for the system sandbox.
* **Charging Info:** Improved keyguard charging info accuracy and layout.
* **Visuals:** Optimized wallpaper zoom transitions for a smoother UI feel.

---

### ➕ Added & Features

* 📱 **Launcher:** Added back the option to **Hide Apps** directly from the launcher.
* 🕒 **Clocks:** Added 2 new clock styles featuring a colon ( : ) separator.

---

### 🔄 System Changes

* Switched to **Tricky Store** implementation.
* Reduced system load immediately following a reboot.

---

### 🗑️ Removed

* ❌ Dropped the broken screen-off AOD animation.

---

### 🐞 Fixes

* 🐛 **Fixed system-wide blur** not working in various UI elements.
* 🐛 Fixed **iOS8 clock size** issues.
* 🐛 Resolved **Depth Clock unlock delay** for a faster wake-up experience.
* 🐛 Fixed screen flicker when exiting **freeform mode**.
* 🐛 Fixed **Fingerprint (FP) icon** not showing up on the Always-On Display (AOD).
* 🐛 Fixed high CPU usage and slow loading during the boot process.

---

## 🚀 Lunaris AOSP v3.10 - xaga

📅 **May 6, 2026**

---

### ✨ Highlights

* 🔄 **Dynamic Bar Refinements:** Redesigned the lockscreen extended media panel, aligned seekbar timestamps inline with the progress bar, and significantly improved the extended media blur visuals.
* 🎮 **Gaming Enhancements:** Switched to the Axion GameSpace UI and introduced a new toggle for auto-detecting apps within GameSpace.
* 🎨 **Clock & Emoji Customizations:** Brought in 14 new clock designs (including the Neumatic clock style) and added Swift and Facebook system emoji styles.

---

### ⚡ Improvements

* Reduced app-to-home animation duration for a snappier launcher experience.
* Reduced redundant `applyBlur` calls, improving rendering efficiency.
* Refined lockscreen charging info logic.
* Tuned various clock layouts for better visual alignment.
* Optimized the resolver lookup tile background custom color scheme.
* Sent load-up hint on finger down for faster and more responsive fingerprint unlock.

---

### ➕ Added & Features

* 🔦 **Added working torch intensity control.**
* Introduced the QS panel media & slider widget.
* Added a launcher swipe-up gesture for freeform mode.
* Added a brief AOD timer.
* Added system sandbox support.

#### 🎨 Customization

* **Clocks:** Added the Neumatic clock style and 13 additional random clock styles.
* **Media & QS:** Allowed changing the QS media player position and added animation styles for QS tile toggles.
* **Lockscreen:** **Added a CPU info overlay for lockscreen widgets**, added an option to toggle lockscreen wallpaper tint visibility, implemented a tap wake/sleep animation, and used accent ripple for lockscreen widget click actions.
* **Visuals:** Added Swift and Facebook emoji styles, increased the max blur limit, and made compose volume follow the volume dialog haptic switch.

---

### 🔄 System Changes

* Switched fully to the Axion GameSpace UI.
* Changed the SmartPixel implementation.
* Gated the display engine category on a persist prop.

---

### 🗑️ Removed

* ❌ Removed certain dynamic bar changes (like notification and cust).
* ❌ Dropped MSDL feedback from fingerprint authentication.

---

### 🐞 Fixes

* 🐛 Fixed the pulse effect showing above the UDFPS icon.
* 🐛 Fixed Depth wallpaper showing above the extended dynamic bar panel.
* 🐛 Fixed the accent transparent status bar chip.
* 🐛 Fixed custom clock scale clipping.

---

# 📜 Previous Releases

## 🚀 Lunaris AOSP v3.9 - xaga

📅 **April 21, 2026**

---

### ✨ Highlights

* 🔄 **Dynamic Bar Overhaul:** Switched to Dynamic Bar (dropping the ongoing chip) with redesigned media pills, improved lockscreen UI, and refined padding/sizing.
* 🎨 **Massive Customization Drop:** Brought back Gradient and Classic A11 QS styles, introduced Depth Wallpapers, Edge Light glow, and 21 new clock styles.
* 🔋 **Performance & Battery:** Crucial fixes for 100% CPU drain bugs (Viper4Android and Audio Service), plus rendering overhead optimizations. 

---

### ⚡ Improvements

* Improved freeform app scrolling and device idle state detection (IdleManager).
* Improved ongoing chip miniplayer popup animation and OmniJaws front end.
* Refined Refresh Rate Controller and CachedAppOptimizer.
* Further optimized rendering for wallpaper effects, reducing QS compose rendering overhead.
* Fixed jank caused by media player layer type and improved screen-on animation in dark mode.
* Improved custom and stock font handling, fixing font weight issues across the system.
* Brought back the scroll optimizer for smoother scrolling.
* Tuned the biometric dialog UI for a better look and feel.

---

### ➕ Added & Features

* 🎵 Lockscreen "Now Playing" popup dialog.
* 🔔 Essential Notifications Lite and allowed bubble notification apps.
* 🧹 "Clear History" option in the IdleManager dashboard.
* 📱 Navbar pill auto-hide (exclusive to Launcher3).
* 🎮 Brightness slider in the Game Space panel and option to disable sidebar when GameSpace is on.
* 📹 Extended screen recorder options and added more sidebar customization.
* 📞 Separated active call card from the dynamic island notification.
* ⚙️ System option to ignore Factory Reset Protection (Disabled FRP).

#### 🎨 Customization

* **Clocks:** 21 new clock styles, custom clock AOD transition animations, new custom clock selection UI, Lockscreen OOS clock style, and OOS-like QuickSpace style.
* **QS & Status Bar:** Brought back Gradient style and classic A11-like QS panel style. Added alternate shade option for notification backgrounds, option to use themed icons in QS, and legacy QS notification icon styles.
* **Icons & Themes:** Added new charging/battery themes, user-selected statusbar icon support, and system emoji styles. Matched circle battery style colors with landscape icons. Allowed users to switch to legacy (filled) status bar icons.
* **Dynamic Bar/Notch:** Added glow effect in notch ring, ongoing chip opacity control, and separated switch for dynamic bar actual charging info on the lock screen. Made the keyguard dynamic bar music pill optional.
* **Visuals:** Introduced Depth Wallpaper feature and Edge Light glow effect.
* **Launcher:** Turned app drawer sort feature into a preference. Dropped animation override flag in favor of a direct override toggle.

---

### 🔄 System Changes

* Switched to Dynamic Bar entirely (dropped ongoing chip) and redesigned the media pill style to look similar to OneUI.
* Dynamic bar extended media player now follows the QS media seekbar style.
* Merged the latest LineageOS changes.
* Switched to the Sun OS RefreshRateManager.
* Disabled Smartspace when using a custom clock to prevent overlapping.
* Updated Flex font and utilized the MD3 variable font family in Launcher3 QuickSpace.
* Matched L3 Pixel searchbar color with stock Pixel and made music chip backgrounds slightly more vibrant.
* Changed light mode notification shade color when blur is turned off.
* Auto-toggle wallpaper overlay on quickswitch.
* Enabled back gesture background by default.
* Use default privacy chip background color for location.

---

### 🗑️ Removed

* ❌ Removed Viper4Android (caused 100% CPU usage).
* ❌ Removed Xiaomi touch commit from duchamp (was added previously but wasn't working).
* ❌ Dropped useless timeout changes from IdleManager.
* ❌ Dropped broken "Nothing" charging animation.
* ❌ Removed compact chip toggle for dynamic bar.

---

### 🐞 Fixes

* 🐛 Fixed `android.hardware.audio.service` using 100% of the prime core (which drained battery and caused heating).
* 🐛 Fixed statsD unnecessary CPU usage.
* 🐛 Fixed ongoing chip media art visibility issues for Spotify.
* 🐛 Fixed the AiMode Button in the Pixel-style searchbar.
* 🐛 Fixed left statusbar logo touching the statusbar clock.
* 🐛 Fixed dynamic bar download/upload progress issues and various other dynamic bar glitches.
* 🐛 Fixed Switch Tensor feature handling.
* 🐛 Fixed rounded corners in the wallpaper picker preview.
* 🐛 Fixed broken mobile network reset button.
* 🐛 Fixed video wallpaper and custom UDFPS icons failing to load after a system restart.
* 🐛 Prevented the custom clock font from resetting after a long idle period.
* 🐛 Cleaned up and fixed potential PixelPropsUtils issues.
* 🐛 Resolved minor color customization and Launcher-related bugs.

---

## 🚀 Lunaris AOSP v3.8 (Hotfix) - xaga
📅 **March 23, 2026**

---

### ✨ Highlights

* ⚡ Improved overall performance & smoothness
* 🔧 Better stability (removed problematic components)
* 🎨 UI polish + new customization options

### ⚡ Improvements

* Improved system performance and responsiveness
* Optimized ongoing chip behavior
* Improved legacy recent action padding
* Minor UI tweaks in media player & popups
* General visual polish across system

### ➕ Added

* 🛌 Basic Sleep Mode
* 🔋 Battery indicator in notch ring
* 🎵 Music progress ring in notch ring
* 🧠 Idle manager (similar to Greenify)
* 🔦 Torch toggle on double-tap power
* 🚫 Option to disable Flash SMS
* 🔄 Switch to legacy status bar icon order
* 🎭 Proper UI for per-app spoofing

#### 🎨 Customization

* 🎵 Music chip background color options
* 📱 App drawer styles + search bar location
* 🎨 Custom app drawer background color
* ⏱️ Adjustable custom clock size
* 🧩 New clock faces (Iconify)
* 📊 Volume panel with percentage
* 🔲 Hotseat QSB style customization
* 📏 Disable extra QSB height in workspace
* 🕒 Mask-style status bar clock

### 🔄 System Changes

* 🔄 Updated Smartspace → **CP1A.260305.018**
* 📶 New dynamic VoLTE / VoWiFi icons
* 📡 New VoNR status bar icons
* 🌫️ Switched back to clamp blur
* 🔐 Fixed TEE check (cert changes)
* 🚫 Block PairIP license check

### 🗑️ Removed

* ❌ Lunaris Dolby (stability issues)
* ❌ Gradient customization (performance heavy)
* ❌ Unnecessary system boost tweaks
* ❌ Recent card scale animation

### 🐞 Fixes

* Fixed recent card fast snap issue
* Fixed volume panel ringer in landscape
* Fixed Launcher3 crash (icon packs)
* Fixed developer mode search crash
* Fixed backup settings crash
* Fixed footer settings long press crash
* 💳 PhonePe working (thanks to @Angxddeep)

---

## 🔹 v3.8 — March 6, 2026

### Added & Improved

* 🎨 Redesigned recent overview with improved L3 animations
* 🔒 Accent color privacy indicators
* 🧩 Clock faces, gradients, and notch progress ring
* 📊 Daily/weekly data usage cycles
* 📶 SSID labels on QS tiles
* 🔐 March Security Patch (r4)
* 🔤 Switched to Gsans Flex font

### Fixed

* Fixed battery widget stuck/loading
* Fixed settings crash after font reset
* Fixed torch & WiFi lockscreen widget issues

---

## 🔹 v3.7 — February 17, 2026

### Added

* 📁 Categorized folders (Lawnchair Caddy)
* 🔊 Volume panel styles
* 🏝️ Island notifications
* 🌙 Ambient display (CPU temp / username)
* 🤳 Shake gestures

### Device (xaga)

* 🎧 Lunaris Dolby
* 🎮 Xiaomi touch for gaming
* 🎵 ViperFX

### Fixed & Optimized

* Fixed PixelProp & integrity issues
* Improved multitasking & ServiceManager priority
