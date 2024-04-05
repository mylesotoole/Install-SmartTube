### Running on macOS

1. Make the script executable `chmod +x SmartTubeInstaller`.
2. Run it with `./SmartTubeInstaller`.

<hr>

### How it works:

- Connects to your Android TV via the ADB feature in Android Platform Tools.
- Downloads latest SmartTube release from GitHub and pushes it to your Android TV..

<hr>

### What it uses:

- This script utilizes Homebrew and Android Platform Tools for macOS.
  - These dependencies will automatically be checked. If they are not present, this script will
    install them with your permission.
- ADB debugging is a developer setting on your Android TV and needs to be enabled.
