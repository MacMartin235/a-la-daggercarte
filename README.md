# A-La-Daggercarte
A single-page website that has a character sheet for Daggerheart Open Beta v1.5 and has a search function for filtering the various cards and tables in the game.

## Character Sheet
An interactive Character Sheet based on the look of the Open Beta v1.5 Character Sheets.

The sheet includes various interactive sections, which automatically update other parts of the sheet for ease of use. For example, the info section at the top has editable boxes like name and pronouns, and dropdowns for ancestry, community, class, and subclass. Changing these options updates the "Features" section, showing the actions that are available for your character to take. Other editable sections include but are not limited to: ability scores, hit points and stress, gold, weapons and armor, and domain cards. The site uses your browser's localstorage to save changes, so you can safely close and reopen the site without having to worry about losing your information, or you can save the sheet to a text file or print it so you can be sure you won't lose it (unfortunately uploading files doesn't work yet, so you'll have to manually change values for now.

Also included is a 'locked' character sheet mode. Clicking the lock icon in the upper right toggles between modes. In 'locked' mode, the only parts of the character sheet that can be changed are the checkboxes for armor, hp, stress, hope, and gold. This ensures that during play, you don't accidentally change things that shouldn't normally be updated outside of leveling up.

Finally, the sheet has a couple sections which can autofill suggestions. When typing the name of weapons or armor, or domain cards, the sheet pulls information from the cards and tables in the game to automatically fill the other sections. Weapons will autofill their damage, ability, features, etc. while domain cards will autofill the card description, cost, and domain. Alternatively, you can (at least for weapons and armor) fill out your own values instead of using pre-selected items. When starting a new character sheet, you can also use the "Autofill Sheet" option in the meatball menu once you have chosen a class, and the site will pull information from the class card to autofill values like evasion, ability scores, and starting weapons and armor (optionally overriding entered values if desired). This allows new players to easily fill out most of their sheet without having to go through the whole character creation process.

## Cards and Tables
All the cards and tables included in the Open Beta v1.5 materials, with a search bar that allows you to easily find things.

The cards and tables are lovingly recreated to look like the beta materials, while adding searchability and moddability. The cards use inline svgs to display flags in the upper left, domain symbols, and decorative backgrounds for easy visual differentiation. Inline svgs ensure quick loading and 100% offline functionality.

The tables have the ability to be sorted by clicking on the column headers, and the cards can be filtered with the dropdown on the top left.

The search bar can be used to type keywords and phrases to further filter the cards and tables. For example, try searching "token". This will display all cards that mention the word "token", which inspired me to create a character which maximizes the number of tokens on the table at any given time (my max is 52 using a Seaborne Druid multiclassed into Grace). The search function is a 'fuzzy' search, and takes the card's or table entry's name, domain, type, and description into consideration.

## Screenshots
