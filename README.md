# The Gauntlet

A twenty-rung encounter ladder for Pathfinder Second Edition Remastered, for Foundry VTT.

Your party fights a level-1 encounter. Clear it, level to 2, and face the level-2 encounter. Keep
climbing until rung 20 goes down or the party does. Clear rung 20 and the next run opens at a higher
ascension tier, so the ladder still has somewhere to go.

The module handles the table work: it builds the arena scene, assembles each rung against PF2e's own
encounter budget, spawns the enemies as real `pf2e` sheets carrying their gear and their spells,
dresses the board with a background plate, props, weather and terrain, watches the rounds so hazards
keep moving, reads the win or the wipe off Hit Points, and pays out the treasure and the level.

It ships 41 warbands of five archetypes each, 205 hand-built creatures in all, and 93 environmental
effects with on-grid footprints.

## Requirements

|             |                                                    |
| ----------- | -------------------------------------------------- |
| Foundry VTT | v13.348 or later. Verified against v13.351         |
| Game system | Pathfinder Second Edition (`pf2e`), any version    |
| Players     | 1 to 8 characters, and the budget scales with them |

Load the module in a world running another system and it posts an error, then stands down.

## Install

In Foundry, open **Add-on Modules**, press **Install Module**, and paste this into the Manifest URL
field:

```
https://github.com/ernieayala/the-gauntlet/releases/latest/download/module.json
```

## Animations

Foundry offers three modules alongside this one. Every one of them is optional.

| Module                                                            | What it adds                                                                                                       |
| ----------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| [Sequencer](https://github.com/fantasycalendar/FoundryVTT-Sequencer) | Plays the effects. Nothing animates without it                                                                     |
| [JB2A free](https://github.com/Jules-Bens-Aa/JB2A_DnD5e)          | The free animation library. Every cue this module names lives in it, so a free table sees strikes, auras and hazards animate |
| JB2A Patreon                                                      | Several times the assets under the same namespace. Where you have it, a fire strike burns and a cold one rimes      |

Install none of them and the board still draws each hazard, aura and patch of terrain as a coloured
shape. The ladder runs the same either way.

## Play

1. Enable the module in a `pf2e` world and log in as the GM.
2. Open the **Token** scene controls and press the dungeon button.
3. Drag each player's character from the Actors sidebar onto the party drop zone. The gauntlet
   touches whoever you enrol there and nobody else in the world.
4. Pick a warband, a starting difficulty and a seed. The same seed against the same party builds the
   same ladder every time, so a table can replay a run it lost.
5. Press **Start Run**, then **Spawn to scene**.
6. Fight it out. Once every enemy is down the run window says so, and **Win** pays the party, levels
   them, and sets up the next rung.

The party panel sits beside the dungeon button and opens for players too. Their copy is read-only,
and it shows the rung, the warband and everyone's Hit Points as the fight moves.

Your table can vote on the next rung's difficulty. The GM calls the vote from the run window, each
player casts one ballot from their own client, and the count lands back on the GM's screen.

## What it puts in your world

|                    |                                                                                    |
| ------------------ | ---------------------------------------------------------------------------------- |
| One scene          | `Gauntlet Arena`, 20 squares square, redressed for each rung                       |
| One actors folder  | `The Gauntlet / Rung NN / <warband>`, holding the sheets it spawned                |
| One journal        | `The Gauntlet`, stating the house rules the ladder runs on                          |
| Six world settings | the run, its spawned tokens, the party, the payout ledger, the record and the vote  |

Everything it spawns is unlinked and filed under that one folder, so clearing a rung leaves your own
actors alone.

## Rules content

The Gauntlet's maths comes from Pathfinder Second Edition Remastered: the encounter budget, creature
XP by level difference, the treasure table, and the conditions each effect applies. Every creature
and every hazard it ships is written for this module and stamped as its own publication.

This module uses trademarks and copyrights owned by Paizo Inc., used under Paizo's Community Use
Policy (paizo.com/communityuse). Paizo has not published, endorsed or approved it. For more about
Paizo Inc. and Paizo products, visit paizo.com. Rules text transcribed from Remastered material is
Licensed Material under the ORC License, and this module carries that licence on the sheets it
builds.

## Licence

See [LICENSE](LICENSE). You may run this at your table, including a game you stream or record. You
may not redistribute it or publish a modified copy.

Development happens in a separate repository. This one carries the built module and its artwork.
