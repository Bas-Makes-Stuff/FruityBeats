# FruityBeats

Independent music workstation development builds for Windows and Apple Silicon macOS.

## Downloads

Open [Releases](https://github.com/Bas-Makes-Stuff/FruityBeats/releases) and download the named asset for your system:

- **FruityBeats-Windows.zip** — `FruityBeats.exe` and a categorized `Sounds` folder. Windows 10/11 with .NET Framework 4.8.
- **FruityBeats-macOS.app.zip** — standalone Apple Silicon `FruityBeats.app` and the same `Sounds` folder. macOS 15 or newer; its runtime is bundled.

Both include 347 original WAV samples in Drums, Bass, Keys, Leads, Pads and FX. Download the named release assets rather than GitHub's automatically generated source-code archives.

## Current status

Windows 1.5 passes 82 acceptance checks. Mac preview 3 corrects bundle layout and ad-hoc signing. A native arm64/macOS 15.8.2 job verifies signatures before and after ZIP extraction, passes all 63 packaged engine checks with the bundled runtime, and checks that the GUI process remains running for 10 seconds. See the release's MAC-VERIFICATION.txt and [verification run](https://github.com/Bas-Makes-Stuff/FruityBeats/actions/runs/41212149070).

**Gatekeeper still rejects the ad-hoc development identity. Developer ID signing and notarization are unavailable; security blocking may remain. This is not a trusted production Mac release.** Physical audio/MIDI, interactive workflow acceptance and full Windows/Mac feature parity remain incomplete. No system security settings were changed. The Windows executable remains unsigned.

The full DAW feature set remains in development. FruityBeats is independent software and is not affiliated with Image-Line. Its synthesis and sound library contain no third-party recordings.
