# Zafehouse Access: Getting Started Guide
## About the Game
from the [Steam page for Zafehouse: Diaries](https://store.steampowered.com/app/249360/Zafehouse_Diaries/)

"Stuck in a remote, abandoned town, you must lead five survivors with conflicting motivations, fragile relationships, and fiery prejudices to safety from the roving undead. A sophisticated engine produces new survivors, towns, and content so every adventure is a different experience, and you can use built-in editors to add yourself and others to the game."

Zafehouse: Diaries is a turn-based strategy role-playing game set during the zombie apocalypse. The game takes place in a simulated pen and paper journal, complete with a diary, hand-drawn map, and clipboard for managing orders and supplies. You will need to manage their delicate relationships by strategically assigning them to tasks, siding with them on difficult decisions, and sewing rumors about their past because their disposition towards one another has a huge impact on their success. Choose your moves carefully and be cautious, because combat in this game is brutal, especially in the early-game.

## About the Mod
Zafehouse Access adds full screen-reader support and keyboard navigation to Zafehouse Diaries, making it 100% playable without sight. All screens and gameplay mechanics are supported including menus, diary entries, survivor dossiers, the town map, dilemmas, the custom content editor, and everything in between. See full details on the game interface and mod features below. The only requirements are a copy of Zafehouse Diaries, a screen-reader, and this mod.

## Installation
### Automatic Installer (Recommended)
Download the game and run it to complete the initialization process, then follow these steps.
1. Download the mod archive.
2. Run the Zafehouse Installer.exe, packaged with the mod. You will need to authorize the app to make changes. It should check the file path for your game automatically.
3. Double check the file path displayed in the installer is correct, and press install. You should hear a spoken confirmation that was successful.
4. Launch Zafehouse Diaries normally. You should hear "Zafehouse Access Loaded" and be able to navigate the main menu with arrow keys after it loads.
## Manual Installation
1. Copy the DLL's for harmony, tolk, NVDA controller, and Zafehouse Access into the main game directory.
2. Run the entry point patcher.exe
3. Launch the game
### Uninstalling
You can uninstall the game using the installer. Alternatively, delete the mod files from your game directory and verify files in steam.

## Getting Help
* See the [Zafehouse: Diaries Manual](https://www.zafehouse.com/manual/) for more information about game mechanics and strategy.
* Press F1 in-game to activate the help overlay, which explains mechanics and controls for the screen you're currently viewing. Press CTRL+O on the help overlay to open the entire help system as an HTML document in your web browser.
* Press F2 to toggle input help, which will speak available key commands on the various screens when the view changes.

You can also join the Axdelve Games Discord Server](https://discord.gg/sKCCx9NFd) to ask questions, receive support, and chat with others about the game.
# Interface and Controls
## menus
Includes main menu, pause menu, game mode select, and options
* UP/DOWN - move through Items
* Enter - activate
* Tab - switch tabs (if present)
* Escape - close
## General In-Game Layout
The play environment is divided into a few main areas
* Diary - an open book, displaying a two-page spread, with a stopwatch in the bottom corner. This is where all game events will be written and where you will start.
* Clues - a corkboard displaying notes and photographs of the clues/rescue items you've discovered for the current game mode. Not available in No Survivors.
* Town map - A hand-drawn map of the town, with survivor tokens represented by everyday objects, like a penny, a pebble, etc. portrait Photographs of each survivor run along the bottom of the screen, showing essential information about each character.
* Clipboard - Shown as a sidebar to the right of the map, contains information, orders, and supplies for the currently-selected location. The map, clipboard, and survivor portraits are collectively refered to as "planning view"
* Survivor Dossiers - shows information about the selected survivor on the right, with a relationship summary displayed on the left-hand side.
* Move planner - shows a list of items available at the current location on the left, and a list of items packed on the right, with the ability to choose a move strategy (investigate, assault, breach)
## General Navigation
* A/D move left/right through the following views in order: Clues, Diary, map, clipboard
S opens survivor view
* T - Announce time/day
* SPACE - Advance time 1 hour.
* CTRL+SPACE - Advance time until something is written to the diary.
## Diary
* UP/DOWN - read diary entries
* left/right or z/x - turn pages
* Home/End - jump to top or bottom of open pages
* page up/down - jump to the diary entries for the previous/next hour.
* \ (backslash) - open bookmarks menu
* left/right brackets - jump to previous/next bookmark without opening menu.
## Clues
* ARROWS - Navigate the table
* ENTER - pick up/drop item for rearranging.
## Planning View
### Map Grid
* Arrows - navigate map grid
* shift+arrows - skip empty lots to reach the next location in that direction.
* W - View security report for selected location
* Q - toggle on/off survivor tokens (purely visual)
### Moving Survivors
* Enter picks up a survivor token at the selected location. If more than one survivor exists there, it opens a menu where you can select who you want to move.
* To select multiple survivors for a move, hold shift and use the arrow keys to select/deselect them in the menu. You can also add them to an existing order from the clipboard.
* Once you are dragging a survivor token, move to the destination and press enter. By default, this sends someone to investigate with no equipment. Hold Shift and press enter to issue the move order and also open the movement strategy/equipment screen, where you can change their intent and customize their loadout. You can also reach this screen by interacting with the move order assignment in the clipboard.
### Map Scanner
* Page up/down - browse scanner items
* shift+page up/down - switch categories
* End - cycle subcategories
* home - announce distance from current location
* Shift+home - jump to location on map.

All locations are sorted by distance from your current location.
### Clipboard
The clipboard shows information about the location currently selected on the map in a vertical list. It has three collapsible sections: info, orders, and supplies. Note that all orders and supplies are based on the current location on the map grid. You do not equip survivors, except when you pack items for a move order. They will automatically select and use items available at their current location.
* up/down - navigate the listright arrow - expand a collapsed section.
* left/right - collapse/expand sections. left arrow will jump back to parent section header first if inside that section.
* i - view item  information

You can also safely use the map scanner and check information from survivor portraits on this screen.
### Survivor Portraits
The portraits along the bottom of the planning view provide essential information about each survivor at a glance. For sighted players, different effects are applied to indicate their state (sepia for resting, blood splatter for injuries, etc.). Sighted players can also click on these portraits to open the survivors view directly to that character, and they can right click to flip the portrait over, revealing a slightly longer summary about the character on the back. All of these features are supported with the following commands, available at all times in the planning view:
* numbers 1-5 - announce status for each portrait slot.
* Shift+1-5 - view back-of-photo summary
* ctrl+1-5 - open that survivor's dossier.
* Alt+1-5 - jump to survivor's location on map.
## Movement Strategy and Equipment View
Reachable either by holding shift when you press enter to execute a move on the map or by interacting with an existing move order in the clipboard. It consists of two side-by-side lists of supplies (those available at the location and those in your loadout), with a picker for the raid intent at the top.
* Aa/d - change intent (investigate > breach > assault)
* up/down - Browse supply lists
* tab - switch between available and packed items
* i - read item details
* C - announce carry weight
* CTRL+S - save current loadout for future use.
* CTRL+L - Load saved loadout.
* Escape - save and close
## Survivors View
The survivors view is split into two panes: a relationship map on the left and an informational dossier on the right for the chosen survivor.
* z/x or 1-5 - change active survivor
* up/down - read information.
* Tab - switch panes
* Escape or S - Close
## Custom Content Editor
The content editor allows you to create your own survivors, location photos, occupations, and items. It opens on a grid-based file browser, with a toolbar for creating new content, saving, or exiting; a content filter, and a grid containing all of your custom content. All screens in the content editor use the same general control scheme:
* Tab - move to different components (e.g. toolbar, file list, etc.)
* arrow keys - navigate items/controls in the component that has focus
* Enter - Activate

## AI Disclosure & Credits
AI was used in the creation of this mod.Huge thanks to Happy Starfish for their [Accessibility Modding Template](https://github.com/HappyStarfish/Accessibility-mod-template), which was instrumental to the success of this project and my own learning journey.

## Support my Work
I do this because I like to play games, not for money. If you do want to support my work and buy more cookies for Claude (who is always hungry) then feel free to donate using the following link:

[Send me money on Ko-Fi]()https://ko-fi.com/axdelvegames)