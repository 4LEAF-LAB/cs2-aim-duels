# Changelog
[РУССКАЯ ВЕРСИЯ](https://github.com/4LEAF-LAB/cs2-aim-duels/blob/main/CHANGELOG-RU.md)

## What's Changed in 16.14-9-26

* Added new Duel mini-modes:

  * **Standard** - 13 rounds, AK + Deagle. Both players receive the selected weapon regardless of the weapon configured for them.
  * **Standard - Headshots Only** - body damage is disabled.
  * **King of the Hill** - duration can be selected by the player: 1, 2, or 3 minutes. Added a HUD timer. The duel ends when the time runs out, and the player with more frags wins.
  * **Race for Glory** - duration can be selected by the player: 1, 2, or 3 minutes. Points are awarded only for headshot kills.
  * **Knife** - round count can be selected by the player: 3, 6, or 12. Players receive only a knife, and all weapon selection is blocked.

* Improved the arena development mode:

  * Reworked menu sorting and structure.
  * Arena management now uses a complete **Arena -> Group -> Side** binding.
  * Added the ability to configure points separately for CT and T, allowing more logical and convenient training positions.
  * Spawns can now be placed with the specific side in mind.

* Added and updated spawn points for the following maps:

  * **aim_redline**
  * **duels_mirage_1x1**
  * **duels_aim_map**

* Added the ability to select weapons using chat commands, such as `!ak47`, `!awp`, and others.

* Added weapon selection through the menu.

* All three weapon selection methods are now supported:

  * through the buy menu;
  * through chat commands;
  * through the Duel menu `!duel` / `!d`.

* The Duel menu can now be opened using either `!duel` or the shortened `!d` command.

* Added the ability to disable and configure the cooldown interval between private Duels.

* Added the ability to disable and configure the weapon change cooldown interval.

* Added protection against accidental arena deletion - deleting an arena now requires additional confirmation.

* Added protection against accidental deaths caused by the game world. Previously, such deaths could teleport players to the zero arena. Access to it is now correctly restricted regardless of the cause of death.

* Added localization support:
  * **RU**
  * **EN**
  * Added support for custom translations.

## What's Changed in 15.10-9-26

- Added support for Metamod 2.0 / Plugin API 18.
- Migrated hooks from SourceHook to KHook.
- Updated compatibility with the latest hl2sdk-cs2.
- Fixed plugin loading and compatibility issues.
- Fixed various minor bugs and issues.

## What's Changed in 14.04-8-26

- Initial public release of AIM DUELS.
