# Bstk_wako_URL2PP
Basically a clipboard monitor for video links to be used with wako/Helios on Windows x64, through 64-bit Android BlueStacks and PotPlayer.

Once a video URL is copied to the clipboard the video player will launch on Windows and playback your content,
which will perform significantly better than any video player inside the android emulator.

What you need:

0. 64-bit Windows.
1. BlueStacks_bgp64 (64-bit Android version): [Official Link](https://cdn3.bluestacks.com/downloads/windows/bgp64/4.230.10.4001/096e978c8429333d618528e5c71af873/x64/BlueStacks-Installer_4.230.10.4001_amd64_native.exe) (Link found on bstweaker.tk, if this gets outdated Google it or look there). Make sure the source is from bluestacks.com though, NEVER download Android emulators from anywhere else than the official site.
2. PotPlayer 64-bit on Windows: [Official Link](https://potplayer.daum.net/)
3. wako installed in BlueStacks either through Google Play or other means (such as Aurora Store)
4. Obviously Real-Debrid/Premiumize etc. subscription. If you don't have one, I wonder why you are here reading this.

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
The app will automatically quit if BlueStacks is not running or when it's closed.

Feel free to report issues. Sources and binaries are inside the Bstk64_wako_URL2PP.zip in the Releases section.
