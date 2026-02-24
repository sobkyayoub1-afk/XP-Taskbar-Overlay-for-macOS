Bring the nostalgic Windows XP taskbar to macOS! This Python-powered overlay adds a Start menu, running app indicators, a clock, and optional pinned apps — all without replacing your Dock.

Features

Start Menu: Lists all apps in /Applications and ~/Applications. Click to launch apps quickly.

Running Apps: Shows currently open apps with buttons to bring them to the front.

Pinned Apps (Experimental): Pin your favorite apps for one-click access.

Clock: Always visible on the taskbar.

Overlay: Does not replace or hide the macOS Dock. Always stays on top.

Theme: Windows XP-style gradient with familiar dark blue look.

Installation

Make sure you have Python 3 installed via Homebrew.

Install dependencies:

pip3 install pyqt5

Download the .app bundle or clone the repository and run:

python3 themes.py
Usage

Launch the taskbar via the .app bundle for a standalone experience.

Open apps via the Start menu or pinned apps.

Pinned apps will retain preferences in the configuration file.

Notes

Pinned Apps: Currently experimental; app icons may not always display correctly.

Always on Top: Taskbar remains on top of all other windows, but may occasionally need to be restarted.

Works on macOS without interfering with the Dock.

Contributing

Contributions are welcome! Feel free to submit pull requests for new features, bug fixes, or UI improvements.

License

MIT License 
