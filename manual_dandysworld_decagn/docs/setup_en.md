# Manual Randomizer Setup Guide

## Required Software

- None

## Installation Procedures

Needs content.

## Dandy's World Options

The world options can be set in the player's Archipelago YAML. Toon and trinket selections use YAML lists:

```yaml
Final_Floor_Num: 20
Goal_Toon_Mode: Random
Number_Of_Toons_To_Reach_Goal: 3
Starting_Toons: [Boxten, Poppy]
Include_Toons: []
Exclude_Toons: [Rudie]
Include_Trinkets: []
Exclude_Trinkets: [Egg_Radar]
Event_Twisteds: true
```

- `Final_Floor_Num` selects the goal check name (for example, `Beat Final Floor 20`) and is saved in slot data. Floor progression itself is not yet balanced against this value.
- `Goal_Toon_Mode` can be `Any`, `Random`, or `Specific`. `Any` requires the configured number of collected toons; `Random` assigns that many toons for the goal; `Specific` requires every name in `Toons_To_Win_With`, such as `[Astro, Pebble]`.
- `Starting_Toons` defaults to `[Boxten, Poppy]`. Use `[Random]` to start with one randomly selected toon. At least one starting toon is required.
- Leave an `Include_*` list empty to allow all items of that type. `Exclude_*` removes listed items; exclusions take precedence if a name is in both lists. Related toon-shop, toon-goal, and trinket-goal checks are removed with their items.
- Set `Event_Twisteds` to `false` to remove seasonal event Twisted checks. Other event content is unaffected.

## Joining a MultiWorld Game

Needs content.

## Multiplayer Manual

Needs content.

## Game Troubleshooting

Needs content.