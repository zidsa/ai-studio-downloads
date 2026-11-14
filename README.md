# Zid AI Studio Downloads

Use this page to find the installer for your device.

| Device | Download |
| --- | --- |
| Mac with Apple Silicon (Apple M-series) | [Download Zid AI Studio 0.1.9 for Apple Silicon](https://github.com/zidsa/ai-studio-downloads/releases/download/v0.1.9/Zid-AI-Studio_0.1.9_macOS-arm64-199a0e35.dmg) |
| Intel Mac | [Download Zid AI Studio 0.1.9 for Intel Mac](https://github.com/zidsa/ai-studio-downloads/releases/download/v0.1.9/Zid-AI-Studio_0.1.9_macOS-x64-199a0e35.dmg) |
| Windows x64 (test build, not yet Authenticode-signed) | [Download Zid AI Studio 0.1.9 for Windows](https://github.com/zidsa/ai-studio-downloads/releases/download/v0.1.9/Zid-AI-Studio_0.1.9_Windows-x64-199a0e35-UNSIGNED.exe) |

**Mac:** to install or update, quit any running copy of the app. Open the DMG, drag **Zid AI Studio** into **Applications**, and choose **Replace** if Finder asks. Then open it from **Applications**, not from the disk image. To check your Mac type, open **Apple menu → About This Mac** and look for **Chip** or **Processor**.

The 0.1.9 Mac installers are not notarized yet. If macOS says **“Zid AI Studio” is damaged and can’t be opened**, eject the disk image, make sure the app is in **Applications**, then open **Terminal** and run:

```
xattr -dr com.apple.quarantine "/Applications/Zid AI Studio.app"
```

Then open the app from **Applications** again. A notarized build will replace these files.

**Windows:** run the installer. This test build is not yet Authenticode-signed, so Windows may show **Windows protected your PC**. Choose **More info**, then **Run anyway**.

You need a Zid store account and a signed-in Claude Code or Codex account to use the assistant.

[0.1.9 release notes and checksums](https://github.com/zidsa/ai-studio-downloads/releases/tag/v0.1.9) · [All releases](https://github.com/zidsa/ai-studio-downloads/releases) · [Previous version (0.1.8)](https://github.com/zidsa/ai-studio-downloads/releases/tag/v0.1.8)
