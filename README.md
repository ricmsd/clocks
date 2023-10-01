# Clocks
Lots of clocks (planned).

## How to build
### Requirements
- Node.js (Tested on v18.17.1)
- Windows OS (Tested on Windows 11, not sure if it works as expected on MacOS or Linux)

### Build
    git clone https://github.com/ricmsd/clocks.git
    cd clocks
    npm install
    npm run make

If the above is successful, the installer will output `clocks-X.X.X Setup.exe` (where `X.X.X` is the version number) under `clocks/out`. Run this to install.

If you want to try it out without installing it, run `npm run start` instead of `npm run make`.
