# Soft Kaizo IronMON

This ruleset's goal is to:
- Make the early game much more tolerable
- Make the endgame more interesting
- Increase the amount and quality of pivot options and the spots in the run that have viable pivots
- Introduce a Perish Song counterplay possibility
- Eliminate the need to juggle HM Friends to and from the PC
- Other minor improvements and Quality of Life changes

Base for the rules is [Kaizo IronMON](http://ironmon.gg)

The settings for this run require using a fork of the randomizer - [Something-Smart's Randomizer](https://github.com/something-smart/ironmon-randomizer)

Also, to be able to increase wild/trainer Pokemon levels beyond the 1.5x limit, you can prep a ROM that only has these values modified, then use it as a base for the usual randomization.

## Rule Changes
### Your Pokemon
| Rule                           | Details                                                                                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Non-Random Starter             | You can pick the Pokemon after looking at all the options                                                                               |
| Limited Lab Legendaries        | You can pick legendaries under 600 BST in the lab                                                                                       |
| Limited Pseudos                | You can pick pseudo-legendaries that have a 4x weakness in the lab and catch them in the wild. If they have an ability that helps with that 4x weakness (Color Change excluded), then you can only use them in the lab fight(s) and afterwards you have to pivot to another Pokemon |
| No Favourites Clause           | Since you can pick the above in the lab, the favourite clause is no longer in effect                                                    |
| HM Friends Limits              | You can have up to a maximum of 2 HM friends with you in the party for the whole run and you can catch them as soon as you get out of the Lab. If they die in double/triple/rotation battles, due to Perish Song counterplays (see Perish Song Counterplay Rule) or other situations, you cannot revive them with items. Keep that in mind if you're in a dungeon with a double battle for example |
| No Boxing of HM Friends        | You are not allowed to box your current HM Friends. If you wish to replace one, you can box it after catching a new one                 |
| Speed Up Friendship            | Setting that increases base friendship to 215. You might also use in-game NPCs that increase friendship instead if you like             |
### Trainer Pokemon
| Rule                           | Details                                                                                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Additional Trainer Pokemon     | Boss Trainers now have 4 additonal Pokemon and Important Trainers - 1 extra mon                                                         |
| Ensure Champion 100s           | Trainer Pokemon level increase might be higher than 50% to ensure the final boss of the challenge has all level 100s if he/she doesn't yet. It needs to be the minimal amount needed to reach that. Please refer to Game Specific Information section below to learn the exact values |
| Delay Fully-evolved            | Level for guaranteed fully-evolved Pokemon appearance on trainers might be delayed so that the 2nd Gym leader has a chance to have not fully-evolved Pokemon. Please refer to Game Specific Information section below to learn the exact level |
### Catching / Pivoting
| Rule                           | Details                                                                                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Catch Rates                    | Minimum Catch Rate is set to level 5, which means the catches are guaranteed                                                            |
| Maximum Total Level Upgrade    | You can now pivot up a total of 4 levels but only cumulatively across the entire run. Pivoting down levels doesn't affect the total     |
| Rebalance Encounters (optional)| You can use a rando fork's setting to 'Rebalance Encounters'. This is optional, but recommended                                         |
| Match Coverage Guy             | (TO BE TESTED) Wild Pokemon levels are further increased to match "after Lab" pivots with the first mandatory trainer you fight after that. Please refer to Game Specific Information section below to confirm the exact values |
| More Pivots                    | You can re-enter or enter prematurely any dungeon if it's ONLY for pivoting purposes. You can't fight any trainers or pick up any items there if you do that |
### Moves
| Rule                           | Details                                                                                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| All TMs learnable              | All TMs are learnable 100%, but some rules still apply as to which ones you can use                                                     |
| Gym Leader TMs                 | Gym Leader TMs are now 100% learnable and those are the only ones you can teach unless your Pokemon falls under the Stoners+ rule       |
| Stoners+                       | Any Pokemon that is normally evolved from using an evolution stone (like Arcanine, Nidoking, etc.) can now learn 1 non gym leader TM OR a move tutor move of your choice. After learning the move you cannot use any non gym leader TMs or move tutors on that Pokemon |
| HM Moves in Battle             | You may now use HM moves in battle but only if they are in your Pokemon's learnset. This is possible thanks to rando fork's setting. If you choose to delete that HM move you cannot relearn it |
| HM Moves Outside of Battle     | Considering you can now have an HM move in your learnset, you are not allowed to use it outside of battle until you acquire a corresponding HM item |
| Legal Drain Moves              | Drain moves - meaning attacking moves that deal damage and heal the user based on damage done - are now legal to use everywhere. These are for example Drain Punch, Giga Drain, Leech Life. So not Leech Seed, Pain Split, Endeavor, etc. |
| Banned Moves in Dungeons       | You can now use a banned move that your Pokemon learned by level-up or from a legal TM, but only once per dungeon (exactly one use of a move). You cannot use it in the overworld. This limit resets if you get a forced heal inside a dungeon. Healing with pp restoring items or other means doesn't reset the limit |
| Sketch Scouting                | You are allowed to learn any TM move that would make Sketch scouting safe if you have Sketch in your moveset, but you are not allowed to use that move in trainer battles  |
| Beat Up Shedinja               | You may use Beat Up but only as a Shedinja coverage move                                                                                |
### Abilities
| Rule                           | Details                                                                                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Pure/Huge Power Usage          | You might use the benefits of Pure Power or Huge Power if your Pokemon is 425 BST or lower. You may still run a Pokemon with Pure Power or Huge Power with higher BST, but then you are not allowed to use moves that benefit from the ability excluding Struggle |
| Extra Banned Abilities         | Parental Bond is banned                                                                                                                 |
### Items
| Rule                           | Details                                                                                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Additional Held Items          | These held items become legal: Smoke Ball, Cleanse Tag, Pure Incense                                                                    |
### Combat
| Rule                           | Details                                                                                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Free Lab                       | You are allowed to lose the Lab fight(s) and then continue the run                                                                      |
| Perish Song Counterplay        | You are allowed to hard switch out to your HM friend if you're affected by Perish Song, but then you have to immediately switch back    |
| Switch-out Moves Sanity        | Attacking moves that switch the user out like U-turn or Volt Switch (so not Baton Pass) can now be used when you have your HM friends with you, but only if no volatile negative effects and no negative stat changes are on your main Pokemon. This includes confusion, infatuation, leech seed, perish song and all similar negative effects that go away when you switch out. After you use such a move, you have to immediately switch back |

## Optional Settings
| Setting                        | Details                                                                                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Other Misc. Tweaks (optional)  | These are optional, but recommended: 'Revert Bad Berries', 'Fix Mythical Pokemon Experience', 'Lock Imposter to Ditto', 'Balance Static Pokemon Levels', 'Ban Unown From Wild'. Might be more worth considering that are game-specific. Some of these might not be available in certain games |

## Game Specific Information
Extra Information about the general rules above, but game-specific. The rule names below match the rule names that are present above.

### Pokemon Platinum
| Rule                           | Details                                                                                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Ensure Champion 100s           | Cynthia's lowest level is 58 in the original. That means the base ROM used for randomization needs an initial increase of Trainer Pokemon Levels of 15%. This ensures that after applying the usual 50% on top of that, it will be just enough to elevate all her Pokemon to lvl 100 |
| Match Coverage Guy             | Highest level wild that could be acquired before the first mandatory trainer on Route 202 (Ace level 9) has level 4 in the original and 6 in standard IronMON. Due to extra trainer level increase we need to match the level 9. That requires the base ROM used for randomization to have an initial increase of Wild Pokemon Levels of 38%. This ensures that after applying the usual 50% on top of that, it will be just enough to elevate the early pivot options to level 9 |
| Delay Fully-evolved            | Due to the further trainer Pokemon level increase, lowest level of Gardenia's Pokemon will be 35. That means guaranteed fully-evolved Pokemon appearance level setting should be set to 36 |
