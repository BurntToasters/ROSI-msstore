# ROSI

[<img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200"/>](https://apps.microsoft.com/detail/9p4q134b2jw3?referrer=appbadge&mode=direct)

ROSI is an Electron GUI for yt-dlp

### ⚠️ THIS IS THE MICROSOFT STORE VERSION OF ROSI. Extra tweaks are made to this version only to support ROSI being published to the microsoft store. To download the STANDALONE version binaries, please go to the [main repo](https://github.com/BurntToasters/ROSI).

<img width="700" alt="ROSI" src="https://github.com/user-attachments/assets/52694114-57a3-487e-837b-6bf5d4960ba3" />

___

# LICENSES

Rosi includes the official YT-DLP binary which on its own uses the [unlicense] license, however there are bundled third party packages. Read [THIRD‑PARTY‑NOTICES](THIRD‑PARTY‑NOTICES.md) for more.

___

# Requirements

ROSI requires ffmpeg to be installed in your system and available in its PATH.
Learn how to install ffmpeg: [https://help.rosie.run/installing-ffmpeg](https://help.rosie.run/installing-ffmpeg)
- **Windows:** `winget install ffmpeg`
___

# Build ROSI from source:

### ⚠️ THIS IS THE MICROSOFT STORE VERSION OF ROSI. Building this version is NOT reccomended as it is modified to support the Windows Store. To build the main version, please go to the [main repo](https://github.com/BurntToasters/ROSI).

Download ROSI source code from source (main)
1) Download zip of release source code (non-release source code are not recommended as they may contain issues not yet fixed for a release).
2) Unzip the folder folder, place it in a good location on your computer.
3) Install [NodeJS](https://nodejs.org/en/download) and [NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) *(Required to build ROSI)*.
4) Open a terminal window within the project's folder and type `npm i --save-dev electron` to download the required electron packages. (May also need to run `npm i` on its own if other required packages were not installed).
5) Run `npm run build` or `npm run build -- --[extra args]` to build ROSI for your Host OS.

___

# Need help with something?

If there is an issue with the program, feel free to create a **Github Issue**!  
For other issues/general contact, please go to [https://help.rosie.run/contact](https://help.rosie.run/contact).
