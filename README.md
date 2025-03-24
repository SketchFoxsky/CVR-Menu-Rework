# CVR Menu Rework

This project uplifts the menu to better match the theming of the game. Some settings may be moved and new functionality may be introduced in the future.

## Example Image
 ![image](https://github.com/user-attachments/assets/9d920da6-c7bf-45ee-a077-bf52ce074666)

## Current Changes

- Toggles, Dropdowns, and Sliders are now consistent and are themed after the game aesthetics.
- Dropdown entries were made more narrow and were given clear borders, entries overlapping other settings shouldnt blend into the settings button.
- Some elements were using the wrong CSS class, this has been fixed!
- Button classes had thin borders that broke when playing without Anti Aliasing.

## Planned Changes

- Support NotoSans for non latin characters. Primarily for Japanese, Chinese, and Korean characters.
- Combine Prop and Avatar filter pages to a consolidated Content Filter page.
- Make Large list of settings Collapsable based on its subcategory, IE Post Processing, Avatar Removables, VR and Gampead controls etc.
- Remove redundant filters that are handled by removeable filters.
- Depending on how the Excessively Huge/Small tags are handled in the future, those filters will possibly be removed as well as they are largely ignored or unused.

## Far Out plans
These plans are more optimistic in the project and are not guaranteed!

- Advance Safety to have Text input fields for precise number input!
- Mods Toolbar button to replace where CursorLock used to be!
  - This is to bring modding aspect of the game forward to innexperienced modders
  - Simillar to browsing Avis, Props or Worlds. Find and select mods for install, a prompt to restart will appear and then ML and the selected mods will be installed.
  - This is where you will find Mod Configs as well!
- Player Notes on a user profile, a TXT file will be made in the UserData folder under Notes. Names of the TXT files will correspond to the UUID of a user.
  - This can be used to keep track of old names of a player or other important information you would like to keep!
- Introduce Tab functionality to the menu as shown in the UI 2.0 preview!
