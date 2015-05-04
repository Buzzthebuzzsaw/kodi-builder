# kodi-builder
The purpose of this script is to build various versions of Kodi/Xbmc from a particular version used inside Openelec.
Kodi-builder will build the latest version of Openelec by default, extract the version of Kodi/Xbmc used and then proceed to build for various other systems.
The script so far builds Openelec(Raspberry Pi 2), and then builds a complementary version for Linux(x86), Linux Headless(server) and finally Android.

This means that if a centeral database for media is being used all systems on a network can be kept at the same version of Kodi/Xbmc and they are all in sync.
