# Advanced Dialog and Menu vB User Manual (version 1.0)

https://github.com/dochardware/Advanced-Dialog-and-Menu/assets/1316677/08bb50b8-64b4-4c7f-a5a7-516da3b803a9

Advanced Menu and Advanced Dialog are designed to add more flexibility with drawing text and text boxes to the overlay/window layer but maintaining the ease of use. The plugin utilizes the ability to copy background tiles to the window layer to create the *illusion* of placing dialog and text boxes anywhere on screen. 

These are based on [Pautomas' Plugin Pack](https://github.com/pau-tomas/gb-studio-plugins/tree/get_tile_id)
<br>
<br>
## How It Works

<img width=70% height=70% src="https://github.com/dochardware/Advanced-Dialog-and-Menu/assets/1316677/611b816a-6b26-4d8a-ad41-a954c2a1bd11">
<img width=70% height=70% src="https://github.com/dochardware/Advanced-Dialog-and-Menu/assets/1316677/66c1f342-c303-48f0-a6c9-4211d87881a1">
<img width=70% height=70% src="https://github.com/dochardware/Advanced-Dialog-and-Menu/assets/1316677/5d012898-8bfd-4fef-a337-97b04c60b920">
<br>
<br>

## Advanced Menu 2.0
*Layout Tab* - UI design and positioning

<img width="382" alt="Screenshot 2023-10-28 at 8 06 14 PM" src="https://github.com/dochardware/Advanced-Dialog-and-Menu/assets/1316677/32ca842d-5ac0-4f54-81ea-4d2d27e303ce">

- **Box Width** - Width of textbox

- **Box Height** - Height of textbox

- **Box Position X** - X position of box on screen

- **Box Position Y** - Y position of box on screen

- **Show Border** - Toggle to display ui frame border around textbox. GB Studio will still render a box behind your menu.

- **Clear Previous Content** - Overwrites overlay tiles with background tiles from current camera view.

- **Show Actors** - Toggle allow actors to appear above the overlay
<br>


*Options Tab* - Menu items

<img width="382" alt="Screenshot 2023-10-28 at 8 05 59 PM" src="https://github.com/dochardware/Advanced-Dialog-and-Menu/assets/1316677/1be47e72-04f0-4be4-af6c-2ff0093405b0">

- **Select a Variable** - Variable the game will store the player's selection to

- **Number of Options** - Number of menu items

- **Set variable to '*n*' if** - Menu item name. This field accepts [GBVM control codes](https://gbstudiolab.neocities.org/guides/gbvm-overlay-hud-2) and variables (syntax: `$001$`, `$L01$`, `#001#`)

- **Text Position X/Y** - Sets the position of menu option on screen

- **Select Option** - Sets which option the cursor moves to next when the corresponding button is pressed
<br>
<br>

## Advanced Dialog Version B
*Layout Tab* - UI design and positioning

<img width="382" alt="Screenshot 2023-10-28 at 8 05 39 PM" src="https://github.com/dochardware/Advanced-Dialog-and-Menu/assets/1316677/416952eb-76d4-41f8-b0b5-840026046faf">

- **Box Height/Width** - Size of textbox in tiles
- **Box Position X/Y** - Position of textbox on screen in tiles
- **Show Border** - Toggle UI frame
- **Show Actors** - Toggle whether actors appear on the overlay
- **Clear Previous Content** - Replace the current overlay tiles with background tiles from the current camera view
- **Invert Font** - toggle black text on white and vice versa
- **Text Position X/Y** - Text position on overlay
- **Close When** - toggle when to close dialog/remove overlay
<br>

*Text Tab* - Text entry

<img width="384" alt="Screenshot 2023-10-28 at 8 05 26 PM" src="https://github.com/dochardware/Advanced-Dialog-and-Menu/assets/1316677/0a3546e5-53bc-4d47-ad49-0f12ed388cf7">

- Dialog features such as loading fonts (`!f`), speed options (`!s`), displaying variables, and using control codes work as they would with default dialog or advanced dialog events.

## Best Usage
- Pause Screens
- Status Menus
- RPG Battle screens
- Single-screen level ui
- Single-screen level backgrounds
- and anything where the camera/background isn't moving. 

**Bugs/Issues**
Unfortunately the way avatars are hardcoded, they are not compatible. Using actors is recommended instead.

**Future Updates**
- The ability to use variables in all parameters
- Pixel units for size and position
