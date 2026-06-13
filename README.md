# Tuki Demo

Download the latest macOS demo app from the release below.

- Download: https://github.com/xxykens/tuki-demo-download/releases/download/tuki-demo-v1.0.0/Tuki-1.0.0-arm64.dmg
- SHA-256: `790166e8bc9ff766e595b2263ad498d6443be01a72394920872e246c60c0ff4d`

This is an unsigned demo build. It can be downloaded and installed, but it is not Apple-notarized, so macOS may show:

> Apple could not verify "Tuki" is free of malware.

To open the demo on macOS:

1. Open the DMG and move `Tuki` to `Applications`.
2. In Finder, Control-click or right-click `Tuki`.
3. Choose `Open`, then choose `Open` again.
4. If macOS shows `"Tuki" Not Opened` with only `Done` and `Move to Trash`, choose `Done`.
5. Go to System Settings > Privacy & Security, then allow `Tuki` in the Security section.

If macOS still blocks the app after that, advanced users can remove the download quarantine flag:

```sh
xattr -dr com.apple.quarantine /Applications/Tuki.app
open /Applications/Tuki.app
```

Only open this demo if you downloaded it from this repository.
