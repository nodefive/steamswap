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

## License

MIT License — Copyright (c) 2025 nodefive

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
