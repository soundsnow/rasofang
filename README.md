# rasofang

### Why this exists?
Setting up J2ME / Java ME (Java Micro Edition) emulators is a nightmare. Most emulators require manual input, and the resolution data found on popular download sites is often flat-out wrong. 

I spent **two years** manually testing J2ME apps and games across various platforms. I even purchased several original Java Mobile devices to verify the results. Unlike other databases, I **never** add mismatched resolutions. Every entry here is verified against real hardware. Note: The entries for 320x400 and 640x200 are included only because their calculated results are identical. Please note that no actual testing has been performed specifically for the 320x400 resolution.

**Note:** I originally had a massive database of hardware features, but due to a storage failure, some "Brand" and "Device" metadata was lost. Currently, these fields contain placeholders.

### Sources Verified:
- [GSMArena](https://www.gsmarena.com/) / [DPSoftware](https://www.dpsoftware.org/)
- [Mobiles24](https://www.mobiles24.co/) / [Dedomil](http://dedomil.net/games/) / [Phoneky](https://phoneky.com/)
- [Puyo Pop Fever Re:Chained (Java ME / J2ME)](https://github.com/Realtimeless785/Puyo-Pop-Fever-Re-Chained-J2ME)
- Real-world hardware testing.

### Key Features (UI Demo):
This project is a standalone web-based UI template for J2ME settings:
- **No Install Required:** Runs directly in your browser.
- **Precision Input:** Set Width, Height, and Font Sizes (FS/FM/FL).
- **One-Click Swap:** Quickly toggle between Portrait and Landscape (x/X button).
- **Verified Presets:** Access a list of resolutions that actually match the games.
- **Device Config:** Radio-button selection for different configurations (Keypad/Touch settings currently limited due to data loss).

*Note: This is a UI project only; it does not include a J2ME emulator.*
