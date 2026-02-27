\# 🔊 Audio Switcher



A lightweight Windows 11 system tray app that lets you instantly toggle your default audio output between two devices with a global hotkey.



!\[Windows](https://img.shields.io/badge/Windows%2010%2F11-0078D6?style=flat\&logo=windows\&logoColor=white)

!\[.NET 8](https://img.shields.io/badge/.NET%208-512BD4?style=flat\&logo=dotnet\&logoColor=white)

!\[License](https://img.shields.io/badge/license-MIT-green)



\## ✨ Features



\- \*\*Global hotkey toggle\*\* — press Ctrl+Alt+S (or any custom combo) to switch audio output instantly, even while another app is focused

\- \*\*System tray icon\*\* — lives quietly in your taskbar with a custom speaker icon; right-click for all options

\- \*\*Device picker\*\* — choose which two playback devices to toggle between

\- \*\*Customizable hotkey\*\* — change the key combination anytime through the tray menu

\- \*\*Settings persistence\*\* — your choices are saved to a JSON config file and survive restarts

\- \*\*Start with Windows\*\* — optional toggle to launch the app automatically on login

\- \*\*Toast notifications\*\* — a clean dark popup briefly shows which device is now active

\- \*\*About dialog\*\* — version info, credits, and live config status

\- \*\*Zero dependencies\*\* — no NuGet packages; everything uses built-in Windows APIs via COM interop



\## 📥 Download



Grab the latest release from the \[Releases](https://github.com/junderw52/AudioSwitcher/releases) page.



Just download `AudioSwitcher.exe`, run it, and you're good to go — no installation or .NET runtime required.



\## 🚀 Quick Start



1\. Run `AudioSwitcher.exe`

2\. A speaker icon appears in your system tray

3\. Right-click → \*\*Select Devices\*\* to pick your two audio outputs

4\. Press \*\*Ctrl + Alt + S\*\* to toggle between them

5\. That's it!



\## ⚙️ Configuration



| Setting | How to change |

|---|---|

| Audio devices | Right-click tray → \*\*Select Devices\*\* |

| Hotkey | Right-click tray → \*\*Change Hotkey\*\* |

| Start with Windows | Right-click tray → check \*\*Start with Windows\*\* |



Settings are saved to `%LOCALAPPDATA%\\AudioSwitcher\\settings.json`.



\## 🛠️ Build from Source



Requires \[.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0).



