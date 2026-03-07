# Steam Account Swapper

A quick Bash utility to instantly swap Steam profiles and configurations between two local users without needing to re-enter credentials or restart the Steam client manually every time.

## Features
- Reads `registry.vdf` to detect the currently active Steam user.
- Quickly symlinks `~/.steam` and `~/.local/share/Steam/config` to the target user's backup directories.
- Simplifies local couch-coop or shared PC setups.

## Usage
Make the script executable and run it:
```bash
chmod +x steamswap
steamswap
```
Follow the interactive prompt to switch accounts.
