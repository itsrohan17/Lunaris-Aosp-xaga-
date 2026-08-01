<div align="center">

# 🚀 Lunaris AOSP Changelog

### Redmi K50i / POCO X4 GT (xaga)

![Android](https://img.shields.io/badge/Android-16-3DDC84?style=for-the-badge&logo=android)
![Latest](https://img.shields.io/badge/Latest-v3.12-blue?style=for-the-badge)
![Maintainer](https://img.shields.io/badge/Maintainer-Rohan-red?style=for-the-badge)

</div>

| Version | Date |
|---------|------|
| v3.12 | July 2026 |
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

📅 **July 2026**

> This release is the final major Android 16 update and includes all daily updates from June 9 through July 31, 2026.

### 📝 Complete Daily Changelog

```text
[09/06/26 8:55 pm] Daily Update: -  Fix clock color not resetting when media playback stops
[09/06/26 8:55 pm] Daily Update: - Add clock style wobble charging animation
[09/06/26 8:58 pm] Daily Update: - Re-add notification and call event in dynamic bar
[09/06/26 8:58 pm] Daily Update: - Fix sporadic jumps in statusbar brightness control
[09/06/26 8:58 pm] Daily Update: - Boost clock style album art color saturation
[09/06/26 11:24 pm] Daily Update: - Fix notification click for center-aligned mode
[09/06/26 11:27 pm] Daily Update: - Fix percentage not showing properly for call/voice stream in redesigned mode
[10/06/26 11:41 am] Daily Update: - Fix nowplaying visibility flicker and show logic
[10/06/26 11:42 am] Daily Update: - Fix nowplaying seek bar position desync on overlay open
[10/06/26 5:07 pm] Daily Update: - Ensure locked app stay locked even after swipe manually
[10/06/26 5:29 pm] Daily Update: - Launcher hotseat compact searchbar style
[13/06/26 10:06 am] Daily Update: - Add haptic feedback in Power menu
[13/06/26 10:07 am] Daily Update: - Add album art color mode in nowplaying
[13/06/26 10:07 am] Daily Update: - Exempt QS expansion from keyguard behind scrim visibility
[13/06/26 11:04 am] Daily Update: - Add hold option to open apps in bubble from sidebar
[13/06/26 11:06 am] Daily Update: - Nuke backup pref from settings homepage
[13/06/26 11:19 am] Daily Update: - Redesign app drawer searchbar design like pixel launcher
[13/06/26 11:48 am] Daily Update: - Make launcher navbar burn-in toggleable
[13/06/26 11:48 am] Daily Update: - Make lock gesture toggleable
[13/06/26 11:49 am] Daily Update: - Add toggle to disable recent scroll vibration
[13/06/26 11:57 am] Daily Update: - Add fullscreen mode in sidebar launch-mode popup
[14/06/26 11:25 pm] Daily Update: - Add Bottom Fade options for depth wallpaper subject Layer
[14/06/26 11:26 pm] Daily Update: - Fix Pixel Launcher unlock animation
[14/06/26 11:28 pm] Daily Update: - Remove broken Launcher3 unlock animation
[14/06/26 11:28 pm] Daily Update: - Increase launcher3 hotseat qsb space
[15/06/26 12:56 am] Daily Update: - Add kill-app action in dynamic bar recents chip
[15/06/26 12:58 am] Daily Update: - Fix activity transition hang issue in some devices
[15/06/26 5:28 pm] Daily Update: - Update gms package
[15/06/26 5:29 pm] Daily Update: - Fix live captions download
[15/06/26 5:30 pm] Daily Update: - Fix Cinematic motion photo package download
[16/06/26 5:54 pm] Daily Update: - Replace MSDL haptics with native haptic feedback on brightness slider
[16/06/26 6:15 pm] Daily Update: - Added Backup & Restore functionality in idlemanager
[16/06/26 6:15 pm] Daily Update: - Fix essential notification and appspoof settings scroll issue
[16/06/26 6:23 pm] Daily Update: - Add vanilla new prebuilts
[16/06/26 6:38 pm] Daily Update: PUSHED ✅✅
[18/06/26 11:57 am] Daily Update: - Backport launcher blur app launch animation from a17
[18/06/26 11:58 am] Daily Update: - BP improved tile bounce animation
[18/06/26 11:58 am] Daily Update: - BP small tile detailed footer view
[18/06/26 11:59 am] Daily Update: - BP art and boot optimization
[18/06/26 11:59 am] Daily Update: - BP media qs fixes
[19/06/26 11:09 am] Daily Update: - Improve tile click animation by leveraging the existing tile spring animation
[19/06/26 11:09 am] Daily Update: - Improve brightness slider animation and haptic
[19/06/26 12:34 pm] Daily Update: - Allow changes custom clock horizontal position
[20/06/26 11:57 pm] Daily Update: - Add model based auto depth wallpaper extractor
[20/06/26 11:58 pm] Daily Update: - Fix text clipping and close icon in dynamic bar recents card
[20/06/26 11:59 pm] Daily Update: - Switch to a17 style flash light tile
[20/06/26 11:59 pm] Daily Update: - Fix dynamic bar torch strength missing
[20/06/26 11:59 pm] Daily Update: - Add Autobrightness tile
[20/06/26 11:59 pm] Daily Update: - Add tile animation on ringer tile mode switch
[20/06/26 11:59 pm] Daily Update: - Add haptic feedback on ringer tile mode change
[21/06/26 12:00 am] Daily Update: - Improve few more custom clock layouts
[21/06/26 12:00 am] Daily Update: - Fix tag corruption in clock color apply
[22/06/26 1:32 am] Daily Update: - Reduce extra space when wifi standard icon on
[24/06/26 10:08 pm] Daily Update: - Qs volume panel (1:1 with brightness slider customisation)
[24/06/26 10:09 pm] Daily Update: - Relax default 5G NR SA SS-RSRP signal strength thresholds
[24/06/26 10:09 pm] Daily Update: - Fix sleepmode handler usages
[25/06/26 6:19 pm] Daily Update: - 4 new clocks
[26/06/26 2:56 pm] Daily Update: - Improve shade expansion transitioning between QQS and QS
[26/06/26 2:57 pm] Daily Update: - Enable early expansion when touching the shade form a17 (test)
[26/06/26 2:57 pm] Daily Update: - Remove extra shade expansion trace markers and debugs
[26/06/26 2:58 pm] Daily Update: - Update pixel fingerprints to June 2026 release
[26/06/26 2:59 pm] Daily Update: - Update default wallpaper (by Alister Grey)
[26/06/26 3:00 pm] Daily Update: - Add hex input field to clock color custom tab
[26/06/26 7:22 pm] Daily Update: - Allow edit app name in launcher3
[27/06/26 10:46 pm] Daily Update: - Add sidebar slider auto hide option
[27/06/26 10:47 pm] Daily Update: - hide home screen in fullscreen appdrawer styles
[27/06/26 10:47 pm] Daily Update: - Cancel ongoing animations before entering allapps
[29/06/26 9:25 pm] Daily Update: - Redesign dynamic bar lockscreen music chip ui
[29/06/26 9:26 pm] Daily Update: - New click animation in dynamic bar chip
[29/06/26 9:26 pm] Daily Update: - Dynamic bar extend media bottom click animation
[29/06/26 9:27 pm] Daily Update: - Use different dimens for overkay to change ls dynamic bar position
[30/06/26 7:18 pm] Daily Update: - Allow control qs shade and notification scrim alpha
[30/06/26 7:18 pm] Daily Update: - Show albumart in music expand dialog bg
[30/06/26 7:19 pm] Daily Update: - Fix default lockscreen view shown when custom weather enable
[30/06/26 7:20 pm] Daily Update: - Allow disable extra bottom space when qsb disable
[02/07/26 8:16 am] Daily Update: - Per-app icon customisation
[02/07/26 8:17 am] Daily Update: - Hide dynamicbar event count badge for media chip only
[02/07/26 8:17 am] Daily Update: - Introduce APIs for advanced picture color adjustments
[02/07/26 8:17 am] Daily Update: - Add simple RGB color balance transform
[02/07/26 8:55 pm] Daily Update: - Fix bottom searchbar not moving when keyboard is open
[03/07/26 1:48 pm] Daily Update: - Disable split shade for landscape and restore split notification
[03/07/26 5:57 pm] Daily Update: - Set launcher3 as default launcher
[03/07/26 6:20 pm] Daily Update: PUSHED ✅✅
[05/07/26 11:44 am] Daily Update: v3.12 – Last major update for Android 16.

All changes from this update onward will be pushed to the main branch as soon as they are listed here, instead of first being pushed to the test/private branches.
[05/07/26 3:06 pm] Daily Update: - Add support for third-party search widgets in dock (https://t.me/lunaris_hub/109229?single)
[05/07/26 3:06 pm] Daily Update: - Blur homescreen menu, folder and popup menu
[05/07/26 3:06 pm] Daily Update: - Fix redesign overview collapsing when all its buttons are hidden
[05/07/26 3:07 pm] Daily Update: - Update Updater app design
[05/07/26 9:28 pm] Daily Update: - Add ambient action (for shake gesture)
[05/07/26 9:28 pm] Daily Update: - Add themed icon customisation
[05/07/26 9:30 pm] Daily Update: - Preserve per-view clock alpha through wobble animation
[08/07/26 12:57 am] Daily Update: - Inbuilt AtmosphereEffect
[08/07/26 12:58 am] Daily Update: - silence some logs and debugs
[08/07/26 12:59 am] Daily Update: - Switch to usb prompt bottomsheet
[08/07/26 12:59 am] Daily Update: - Fix OOS icon crash
[09/07/26 12:41 pm] Daily Update: - Add auto-subject extraction on wallpaper change
[09/07/26 12:41 pm] Daily Update: - Set icon scale default size 100
[09/07/26 4:20 pm] Daily Update: - Replace incall haptic with legacy vibration
[14/07/26 12:32 pm] Daily Update: - Add 2 nos4 clock style
[14/07/26 12:32 pm] Daily Update: - Add bold clock and period separator for statusbar clock
[14/07/26 12:33 pm] Daily Update: - Allow disable screen-on memory reclaim
[16/07/26 12:14 am] Daily Update: - Add system popup bar
[16/07/26 12:15 am] Daily Update: - Fix translucent notification switch not working after adding blur
[16/07/26 12:15 am] Daily Update: - Add blur in headsup notification
[16/07/26 2:04 pm] Daily Update: - Add gradient color customization for clock style
[17/07/26 8:56 am] Daily Update: - Allow to copy screenshots to clipboard instead of saving in storage
[17/07/26 8:56 am] Daily Update: - Allow disable split landscape notification
[18/07/26 1:27 am] Daily Update: - Add round compact mode for dynamic bar chip
[18/07/26 1:27 am] Daily Update: - Optimizing shade blur
[18/07/26 1:28 am] Daily Update: - Replace location with torch tile in system popup
[18/07/26 1:28 am] Daily Update: - Enlarge folders and Folder customisations
[18/07/26 1:32 am] Daily Update: - Sandbox and app hide changes
[18/07/26 1:33 am] Daily Update: - Fix keyguard music chip action button bg
[20/07/26 12:53 pm] Daily Update: - Add status bar lyric
[20/07/26 12:53 pm] Daily Update: - add Lyrics fetcher using LRCLIB for spotify and other
[20/07/26 12:54 pm] Daily Update: - Add music lyrics mode on now playing
[20/07/26 12:54 pm] Daily Update: - Fix tap-to-expand now playing overlay not disabling
[20/07/26 12:54 pm] Daily Update: - Hide nowplaying when keyguard dynamic bar panel visible
[21/07/26 2:53 pm] Daily Update: - Improve lyrics sync timing
[21/07/26 2:54 pm] Daily Update: - Improve keyguard music pill layout a bit
[24/07/26 12:46 am] Daily Update: - Fix call and other events chip position when using circle style
[24/07/26 1:43 pm] Daily Update: https://t.me/LunarisOS/355
[31/07/26 10:45 pm] Daily Update: - Add storage save in screenshot ui for clipboard only screenshot
[31/07/26 10:45 pm] Daily Update: - Expose supported blur algorithms to choose
[31/07/26 10:46 pm] Daily Update: - Add back system animation styles
[31/07/26 10:46 pm] Daily Update: - Some base cleanup
[31/07/26 10:46 pm] Daily Update: - Update optimized-routines v26.07 release
[31/07/26 10:59 pm] Daily Update: - Fixup Smart 5G service
```

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
