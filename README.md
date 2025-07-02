# A-La-Daggercarte
A single-page website that has a character sheet for Daggerheart and has a search tab for filtering the various cards and tables in the game.

## Character Sheet
An interactive Character Sheet based on the look of the Open Beta v1.5 Character Sheets.

The sheet includes various interactive sections, which automatically update other parts of the sheet for ease of use. For example, the info section at the top has editable boxes like name and pronouns, and dropdowns for ancestry, community, class, and subclass. Changing these options updates the "Features" section, showing the actions that are available for your character to take. Other editable sections include but are not limited to: ability scores, hit points and stress, gold, weapons and armor, and domain cards. The site uses your browser's localstorage to save changes, so you can safely close and reopen the site without having to worry about losing your information, or you can save the sheet to a text file or print it so you can be sure you won't lose it (unfortunately uploading files doesn't work yet, so you'll have to manually change values for now.

Also included is a 'locked' character sheet mode. Clicking the lock icon in the upper right toggles between modes. In 'locked' mode, the only parts of the character sheet that can be changed are the checkboxes for armor, hp, stress, hope, and gold. This ensures that during play, you don't accidentally change things that shouldn't normally be updated outside of leveling up.

Finally, the sheet has a couple sections which can autofill suggestions. When typing the name of weapons or armor, or domain cards, the sheet pulls information from the cards and tables in the game to automatically fill the other sections. Weapons will autofill their damage, ability, features, etc. while domain cards will autofill the card description, cost, and domain. Alternatively, you can (at least for weapons and armor) fill out your own values instead of using pre-selected items. When starting a new character sheet, you can also use the "Autofill Sheet" option in the meatball menu once you have chosen a class, and the site will pull information from the class card to autofill values like evasion, ability scores, and starting weapons and armor (optionally overriding entered values if desired). This allows new players to easily fill out most of their sheet without having to go through the whole character creation process.

## Searching
The first tab is dedicated to searching materials in the game. There are filters for card types, weapons and armor, level and tier, adversaries and environments, and so on.

The cards and tables are lovingly recreated to look like the source materials, while adding searchability and moddability. The cards use inline svgs to display flags in the upper left, domain symbols, and decorative backgrounds for easy visual differentiation. Inline svgs ensure quick loading and 100% offline functionality.

The tables also have the ability to be sorted by clicking on the column headers.

The search input can be used to type keywords and phrases to further filter the cards and tables. For example, try searching "token". This will display all cards that mention the word "token", which inspired me to create a character which maximizes the number of tokens on the table at any given time (my max is 52 - in the 1.5 Open Beta materials - using a Seaborne Druid multiclassed into Grace). The search function takes the card's or table entry's name, domain, type, and description into consideration, and highlights the matched phrases in the results.

## Notes, Encounters, and Options
The remaining tabs are under development.

The Notes tab can be used for keeping notes during a game. It spans the whole page, which is far more space than the inventory section on the character sheet allows for. Currently the notes do not get saved to localstorage and will be erased if you refresh the page.

The Encounter Builder tab will be used for tracking enemy health, stress, and GM Fear. This feature is upcoming and not yet implemented.

The Options tab will have options for changing dark/light mode, changing font size (and even font family!), saving and loading multiple character sheets, clearing localstorage, adding homebrew cards and tables, and more! This feature is upcoming and not yet implemented.

## Screenshots
**Note: This section is not yet updated for the full release update**<br/>
_Top Section of the Character Sheet_<br/>
![Top of the Character Sheet](https://github.com/user-attachments/assets/047b7ec7-4988-427d-ae03-24809011d7d0)<br/><br/>
_The Features Section, Which Updates Automatically_<br/>
![Features Section](https://github.com/user-attachments/assets/90d64c7f-be0c-4273-b7dc-84aa2f44ac94)<br/><br/>
_Domain Card Section. Updates automatically and lets you move cards between your loadout and your vault._<br/>
![Domain Cards Section](https://github.com/user-attachments/assets/06132dc3-b500-4caf-bd29-177bcca0b6aa)<br/><br/>
_Leveling Section. Lets you keep track of choices made when leveling up._<br/>
![Leveling Section](https://github.com/user-attachments/assets/f9d446a6-f118-44b1-b565-cd2e14513c63)<br/><br/>
_Examples of card designs._<br/>
![Card Examples](https://github.com/user-attachments/assets/938e97e4-655b-4f69-b349-f04eebfdc554)<br/><br/>

