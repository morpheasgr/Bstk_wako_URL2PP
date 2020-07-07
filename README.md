# Bstk_wako_URL2PP
Basically a clipboard monitor to be used with wako/Helios on Windows x64, through 64-bit Android BlueStacks and PotPlayer 64-bit.

Once a video URL is copied to the clipboard the video player will launch on Windows and playback your content,
which will perform significantly better than any video player inside the android emulator.

What you need:

1. BlueStacks_bgp64 (64-bit Android version)
2. PotPlayer 64-bit on Windows
3. wako installed in BlueStaks

BlueStacks and PotPlayer need to be installed in the default installation directories.

Usage:

0. Install prerequisites.
1. Extract to any folder.
2. Run create_shortcut.bat
3. Right-click the generated "wako (BlueStacks)" shortcut, pin to taskbar.
4. In wako/Helios settings, change default play action to "Let me choose".
5. Select what to watch and hit "Copy URL".
6. That is all. PotPlayer will automatically start and play back your cloud file.

Info:
This is written in Batch and AutoHotKey.

Feel free to report issues. Sources and binaries are inside the Bstk64_wako_URL2PP.zip in the Releases section.
