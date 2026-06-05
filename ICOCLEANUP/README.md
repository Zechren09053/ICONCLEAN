# ICOCLEAR — Desktop Icon Manager

A lightweight Windows tray app to show/hide desktop icons and the taskbar with one click.

**By Zechren**

---

## Features
- Show / hide desktop icons instantly
- Hide / restore the Windows taskbar
- Auto-hide mode with configurable inactivity timeout
- DPI-aware, multi-monitor support
- Draggable edge-docked button (left or top)
- Animated splash screen on startup
- Runs silently in the system tray

## Build Requirements
- .NET 9.0 (Windows)
- Visual Studio 2022+

## How to Build
```
cd Projects/DesktopIconToggle
dotnet build -c Release
```

The `.exe` will be in `bin/Release/net9.0-windows/`.

## Project Structure
```
Projects/
  DesktopIconToggle/
    Program.cs          ← Entry point + splash launch
    SplashScreen.cs     ← Animated ICOCLEAR splash screen
    ToggleButton.cs     ← Main tray app logic
```
