# OSFR Launcher
A launcher for the Open-Source FreeRealms Project:

https://github.com/Open-Source-Free-Realms/OpenSourceFreeRealms
![Alt text](https://github.com/Lillious/OSFR-Launcher/blob/main/teaser.png?raw=true)

# Install Instructions

- Download **launcher-win32-x64.zip** from the latest release located at: https://github.com/Lillious/OSFR-Launcher/releases/

- Extract **launcher-win32-x64.zip**

- Open the extracted **launcher-win32-x64** folder and run **launcher.exe**

# Usage Instructions

- Once **launcher.exe** is opened (see "Install Instructions"), Click **Install** - *This step can take a while depending on your setup*
- Click **Start Server** to start a local server - *This is also required to play locally*
- Enter your **nickname** in the **Username** input field
- Enter the **server ip** or **domain** in the **Server** input field - *This is only required if connecting externally and is not required for playing locally*
- Click **Play** to jump into Free Realms!
- Select the **Cog Wheel** at the bottom left to change your character's customization options.

# Compiling Instructions

- Download the latest version of NodeJS: https://nodejs.org/en/download/current
- Open Command Promt and navigate to project folder
- type **npm i electron** and hit enter
- then type **npx electron-packager . OSFRLauncher --overwrite --icon=src\www\img\icon.ico**
