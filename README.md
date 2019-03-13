# RPG
A WPF/XAML game, based on Scotlilly.com Tutorials

Features of the game


First Sprint

User can create a player
Different classes (different bonuses for each class)
Player can move to locations
The location might have a monster to fight
If the player defeats the monster, they receive:
Experience points, gold, random loot
If the player loses to the monster, they:
Return home
Are completely healed
The location might have a quest
Completing the quest requires turning in an item
Item is from monster loot
When the player has the quest completion item, and returns to the location where they received the quest, they receive:
Experience points, gold, a reward item
The location might have a trader
Player can buy/sell items
Player can save/load game
 

Backlog

Add automated tests of the code
Support multiple languages
Improved graphics (J-RPG style?)
Player can learn crafting skills, to create items
Crafting requires recipes? Levels of crafting skill?
Player can learn, and use, spells
Scrolls? More potions?
Add armor
Add magic jewelry
Ability to enchant items
Add pets
Helps in combat? Heals? Attacks?
More complex combat (apply armor/weapon/jewelry/potion/spell bonuses)
Populate world (locations/monsters/items/quests/etc.) from disk (files or database)
Game Creator app, to let people create their own locations/monsters/items/quests/etc. without writing any code (the app creates the files or adds to the database)
 

User interface of the game

The player’s information is in the upper-left. The lower-left will show their inventory and quests. The lower-right will have the movement and combat controls. And, the large upper-right section will show the player’s current location, current enemy (if they are fighting a monster), and the game messages.


The game world

For the first version of the game, we’ll create a small world. This is a map of the locations in the world.

There are only nine locations in this map. But, he player can encounter monsters in three of them, get quests at two of them, and trade at one location. 
