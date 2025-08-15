# This project was made by students of the University of Colorado Boulder - Ann and H.J. Smead Aerospace Engineering Sciences.
ASTRA (Astronaut Stability Training Response Apparatus) was a 2024-2025 [Senior Design Project](https://www.colorado.edu/aerospace/academics/undergraduates/senior-design-projects). This repository is a host for the deployed [HTML5 game executable](https://github.com/auma4987/ASTRA/blob/main/ASTRA%20Game%20-%20Published%20Versions/astra_game-html5.zip), developed for the currently complete ASTRA project. It was designed to be used in conjunction with the software from [auma4987/ASTRA](https://github.com/auma4987/ASTRA) but can also be played just with keyboard or a Wii Balance Board.

## Controls
Movement:    
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/a-feltesdeyapp/ASTRA-Game/blob/main/readme-assets/WASD-Arrows_w.png" width=152>
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/a-feltesdeyapp/ASTRA-Game/blob/main/readme-assets/WASD-Arrows_k.png" width=152>
    <img alt="W A S D keys and arrow keys" src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  </picture>

Pause:    
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/a-feltesdeyapp/ASTRA-Game/blob/main/readme-assets/P_w.png" width=25>
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/a-feltesdeyapp/ASTRA-Game/blob/main/readme-assets/P_k.png" width=25>
    <img alt="P key" src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  </picture>

Reset:    
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/a-feltesdeyapp/ASTRA-Game/blob/main/readme-assets/R_w.png" width=27>
      <source media="(prefers-color-scheme: light)" srcset="https://github.com/a-feltesdeyapp/ASTRA-Game/blob/main/readme-assets/R_k.png" width=27>
      <img alt="R key" src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
    </picture>

## Playing with a Wii Balance Board 
*Note: Windows Only due to firmware limitations*
1. Install [Wii Balance Walker](https://github.com/lshachar/WiiBalanceWalker) onto your PC
2. Turn on Wii Balance Board. Open the battery cover
3. Open Wii Balance Walker. Press <kbd>Add/Remove bluetooth Wii device</kbd>. Copy device pin and close the window
4. Open Settings/Bluetooth. Press <kbd>Add Bluetooth or Other Device</kbd>
5. Look for Nintendo brand device in bluetooth devices. Paste device pin to finish connecting as needed
6. On the Wii Balance Board, press and hold the small reset button directly above the batteries. Do not let go of reset button until board is connecting
7. In Wii Balance Walker, press <kbd>Connect to Wii Balance Board</kbd>. When connected, numbers will replace the letters in the boxes along the top of the window.
8. Unselect "Disable All Actions" on lower right-hand side of window.


### Common Errors
- Wii Balance Walker isn't connecting to the Wii Balance Board
  - Disconnect and reconnect existing Wii Balance Board from bluetooth
  - Connect board to PC using DevicePairingWizard.exe <kbd>Windows</kbd> + <kbd>R</kbd> before connecting to Wii Balance Walker
  - Change batteries in Wii Balance Board
- Game is not reacting to motion on Wii Balance Board 
  - Check that “Disable All Actions” option in wii_balance_walker is toggled off.
  - Check that "Enable vJoy Output" is toggled off.

ASTRA Game executable was developed using the [DragonRuby Game Toolkit](https://dragonruby.org/).
