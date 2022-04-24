[![Build FG-Usable File](https://github.com/FG-Unofficial-Developers-Guild/FG-PFRPG-Advanced-Item-Actions/actions/workflows/create-ext.yml/badge.svg)](https://github.com/FG-Unofficial-Developers-Guild/FG-PFRPG-Advanced-Item-Actions/actions/workflows/create-ext.yml) [![Luacheck](https://github.com/FG-Unofficial-Developers-Guild/FG-PFRPG-Advanced-Item-Actions/actions/workflows/luacheck.yml/badge.svg)](https://github.com/FG-Unofficial-Developers-Guild/FG-PFRPG-Advanced-Item-Actions/actions/workflows/luacheck.yml)

# PFRPG Advanced Item Actions
This extension changes the way items are added to a characters inventory. In particular what happens when you do.
If the item added is a wand, potion or scroll and is equipped it will generate an action item for it in the action tab. It will look up the spell from the item name that is within ()
So a Wand (Cure Light Wounds) will create a spell class caster level 1 and have 50 uses of level spells.
You can also now use Wand of Cure Light Wounds or Potion or Scroll.
This also works with the Enhanced Items v4 extension to keep track of charges.
For potions, wands and scrolls to work you need to have a module loaded that has the spell in it.

Shields also have the ability to do damage as well as have ac associated with them. With this they now get an action item generated for them for shield bash. This means you no longer need to have 2 items for a shield if your character does shield bash.
If the item is a weapon and and has flaming, flaming burst, igniting, frost, icy burst, corrosive, corrosive burst, shock and shocking burst in the properties it will generate the 1d6 damage as part of the weapon.

To override the caster level of an item, change the item name before equipping it.
For example: Scroll of Cure Light Wounds (CL 5)

To override the remaining charges of a wand, change the item name before equipping it.
For example: Wand of Cure Light Wounds [13 charges]

Originally created by [rmilmine](https://www.fantasygrounds.com/forums/member.php?215591-rmilmine).

# Compatibility
This extension has been tested with [FantasyGrounds Unity](https://www.fantasygrounds.com/home/FantasyGroundsUnity.php) 4.1.13 (2022-01-05).
