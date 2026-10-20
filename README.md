# ULTRA REMOTE PC [TURBO LINK]
High-Performance Wi-Fi & Hotspot Phone-to-PC Controller & Bidirectional Batch File Transfer Engine

======================================================================================
FILES IN THIS PACKAGE (READY TO USE):
======================================================================================
1. bin\RemotePC_Installer.exe  -> Windows Native Setup Installer (Installs Server + Shortcuts + Startup)
2. bin\RemoteController.apk   -> Android Mobile Application (Signed Universal APK for ALL Android versions)
======================================================================================
NEW FEATURES IMPLEMENTED (PER USER REQUEST):
======================================================================================

1. NATIVE WINDOWS SETUP INSTALLER (NO PORTABLE):
   - `bin\RemotePC_Installer.exe`: A native Windows setup installer.
   - Installs server files cleanly to `%LOCALAPPDATA%\Programs\UltraRemotePC`.
   - Automatically creates Desktop and Start Menu shortcuts with high-res icon.
   - Registers Windows Add/Remove Programs (Control Panel) uninstaller (`uninstall.exe`).
   - Automatically configures Windows Boot Auto-Start.

2. RUNS IN BACKGROUND ON CLOSE:
   - When you click the `[X]` (Close) button or Alt+F4 on the PC server window, it does NOT quit!
   - It automatically minimizes to the Windows System Tray (Taskbar notification area) with tooltip.
   - Keeps listening and streaming files even with the window closed!
   - Double-click the tray icon to restore the dashboard at any time.
   - Right-click tray menu provides: Open Dashboard, Start with Windows Boot toggle, Reset Pairing, Exit Server.

3. AUTO-START WITH WINDOWS BOOT:
   - Registers `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run`.
   - On PC startup, launches silently in background (`--minimized`) directly to tray without intrusive popups.
   - Can be toggled ON/OFF directly from the PC dashboard or tray menu anytime.

4. UNIVERSAL ANDROID COMPATIBILITY (ANDROID 5 TO 16/18+):
   - Includes native C libraries compiled for ALL 4 Android ABIs:
     * `arm64-v8a` (Modern Android Phones & Tablets)
     * `armeabi-v7a` (Older 32-bit Android Phones)
     * `x86_64` (64-bit Android Emulators / Intel PCs / Chromebooks)
     * `x86` (32-bit Android Emulators)
   - Resilient Scoped Storage & Downloads directory resolution: works seamlessly on Android 11, 12, 13, 14, 15, and future versions without permission crashes.

5. GORGEOUS HIGH-TECH NEON APP ICON:
   - Custom-crafted glowing cyber controller and PC link emblem.
   - Packaged across all Android mipmap densities (mdpi, hdpi, xhdpi, xxhdpi, xxxhdpi) + Windows `.ico`.

======================================================================================
CORE REMOTE FEATURES:
======================================================================================
1. DRAG & DROP FILE STREAMING:
   - Drag files onto PC window to send to phone instantly at full Wi-Fi/Hotspot wire-speed.
   - Batch sending supported (1 to 50+ files).
   - Zero internet data consumption (pure local TCP/UDP socket).
2. ONE-TIME PAIRING WHITELIST:
   - 1st connection asks PC permission; once approved, permanently whitelisted.
3. 5 RICH PHONE CONTROLLER TABS:
   - Touchpad: 1-finger move, 1-finger tap (left click), 2-finger tap (right click), 2-finger scroll, sensitivity slider.
   - Keyboard: Function keys (F1-F12, Esc), Modifiers (Ctrl, Shift, Alt, Win), Navigation (Enter, Backspace, Tab, Space, Del, Arrows), Direct Text Input.
   - Media: Glowing Play/Pause, Next, Prev, 5s Seek Back/Fwd, Timeline Seekbar (0-100%), Volume Slider & Mute.
   - Shortcut Commands: Lock PC, Sleep, Shutdown, Restart, Show Desktop, Close Window, Task Manager.
   - Files: Select & send multiple files with real-time speedometer (MB/s) and progress monitor.
