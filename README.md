# NoCapsOnThisCut

Downloads for the NoCapsOnThisCut video editor. This repository holds the
installers and nothing else; the source is private.

**[Latest release](https://github.com/yurusux/NoCapsOnThisCut-releases/releases/latest)**

## Windows (10 or 11, x64)

1. Download `NoCapsOnThisCut_<version>_x64-setup.exe`.
2. Run it. It installs for your user only, so no administrator prompt.

## macOS (Apple Silicon, 13.3 or newer)

1. Download `NoCapsOnThisCut_<version>_aarch64.dmg`, open it, and drag the app
   into Applications.
2. Open the app. The first time, macOS says it cannot check it for malicious
   software, because this preview is not yet signed with an Apple Developer ID.
3. Open **System Settings → Privacy & Security**, scroll to the message about
   NoCapsOnThisCut, press **Open Anyway**, then open the app again. You only
   do this once.

Dubbing is Windows-only for now. Captions on a Mac need Python with
`faster-whisper`; the captions panel tells you the commands if it is missing.

## Updates

Both versions check for a new release each time they start, and install it
themselves.
