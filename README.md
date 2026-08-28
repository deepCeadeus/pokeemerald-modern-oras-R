# Pokémon Modern Emerald ORAS 3.4R
Modern Emerald Documents
You can get more information about Modern Emerald at [Pokecommunity](https://www.pokecommunity.com/showthread.php?t=494005)
You can get the hackrom documentation following [this link](https://docs.google.com/spreadsheets/d/1QEFJmFhfaZqgxSUnM7MFpufrnrRk_NMzNoNWl2m3y_0/edit#gid=414283818)

# ✨CHANGES FROM BASE MODERN EMERALD 

**TL;DR:** Use Heart Scales (Fallarbor) and go to the Ability Trainer (Lilycove). Weather is back on the menu (including hail + Ice Body). Weather Buffs for Hail and Sandstorm. Some abilities were added or tuned. Several moves were reworked/added. Elemental Fangs were added back, including **Night Slash**, **U-Turn/Volt Switch**, and **Roost**. **Sucker Punch** was added. **Prankster-style moves** now exist as move effects (granting +1 priority) instead of adding the Prankster ability. Signature moves were restored for **Wyrdeer, Farigiraf, Dundunsparce, Kleavor,** and **Annihilape**. There is a table for Judgment/Hidden Power IV's towards bottom of this README.

### Project Goals
My goal is make Modern Emerald feel more like a “Generation 3.5” experience while preserving the spirit of Pokémon Emerald.

Key goals include:
- Strengthening underperforming types, especially Bug and Steel.
- Giving Pokémon clearer identities through ability and movepool changes.
- Preserving compatibility with the original games whenever practical.
- Adding selected Generation IV mechanics and Pokémon while maintaining a cohesive Gen III feel.
- Keeping changes organized and easy to port to other Modern Emerald–based projects. (HOPEFULLY)

---

## Quality of Life & Compatibility

### Selectable Shiny Rates (LESS GRIND)
Players can choose one of the following shiny odds:
- 1/16
- 1/32
- 1/64
- 1/128
- 1/256

Additional features:
- The **1/16** setting guarantees a shiny starter.
- Compatible with **Random Starter** mode.
- Debug-generated shinies continue to use the original **1/8192** legality check (to my knowledge).

**Compatibility Note:** Pokémon obtained using increased shiny rates may not remain shiny when transferred to an unmodified game.

---

## ORAS Tileset Update
Updated to **ORAS Tileset Fork v3.4**.

---

## Event & Map Fixes

### Deoxys Meteor Fix
- Missing meteor metatile data prevented proper Deoxys form interactions.
- Reworked into scripted **Rock Smash** interactions.

### Celebi Event Fix
- Fixed an incorrectly placed interaction tile that prevented the Celebi encounter from triggering.

---

## Compatibility Philosophy

### Transfer Compatibility
Pokémon using original moves and original abilities should generally transfer and function as expected. (TESTING)

### Record Mixing
Mixing records with original games remains largely compatible.

### Abilities
Many Pokémon received new secondary abilities. Most if not all retain at least **1** original ability. Most abilities recieved a buff. 

---

## Encounter Changes

### Daytime Encounters
- slight changes from Modern Emerald

### Safari Zone
**Scyther**
- Encounter rate increased to roughly match Pinsir and Heracross (about 4–5%).

**Rare Johto Starter Evolutions**
Added rare Safari Zone encounters:
- Bayleef
- Quilava
- Croconaw

These appear alongside the existing Kanto starter evolutions at about 1% encounter rates.
Several existing encounters were reduced from 5% to 4% to make room.

### Route 101
**Eevee**
- 1% encounter rate (existing Modern Emerald encounter)

**Pikachu**
- Added at 1% encounter rate

### Route 119

- Added some new encounters (less oddish) 

### Ocean Routes 

- Slight changes to make Surf encounters more interesting. 

### Meteor Falls

- Surf and Fishing encounters updated

### Mt Pyre 

Slight changes to top floor and outside peak encounters.

### Night Encounters 

- All major land routes have updated night encounters fishing, rocksmash, and surf included. 
- Night time should feel different than day.
- Treeko, Torchic, Mudkip and evolutions can be found in night encounters 
- Check out the **Desert** 
- Rare 1-2% encounters 
- **Safari Zone**: Wild, fishing, surf, and rocksmash updated.
- **Safari Zone**: Starters and evos are more present
- **Jagged Pass** and **Fiery Path** have night encounters 
 
---

## Move Changes

### Reworked Moves

#### Beat Up
- Now functions similarly to Rock Blast.
- Hits **2–5 times**.

#### ViceGrip
- Now a **Bug-type** move.
- **75 BP**.
- **50%** chance to lower **Defense**.
- Distributed primarily to Pokémon with crab-like appendages.

#### Night Shade
- Now a **40 BP Special** priority move.

#### Water Gun
- **55 BP**.
- Increased critical-hit chance.

---

### Buffed Moves
- **Air Cutter:** 70 BP Special Atk
- **Steel Wing:** 70 BP, 20% chance to raise def up from 10%
- **Rapid Spin:** 50 BP, Raises SPEED +1 stage (Modernized) 
- **Binding Moves:** Moves like bind, clamp, whirlpool remove 1/8 hp per turn for 2-5 turns
- **Camouflage:** Raises Evasion +2 stages 
- **Stockpile:** Raises SpDef +1 Stage each use and not reduced by Spit Up or Swallow
- **Spit up:** 30% chance to reduce Accuracy
- **Swallow:** In addition to healing it now cures status problems
- **False Swipe:** 70 BP
- **Metal Claw:** 65 BP, **20%** chance to flinch
- **Poison Tail:** 55 BP, high crit ratio, **20%** poison chance
- **Poison Sting:** 25 BP, high crit ratio, **30%** poison chance
- **Bubble:** 30 BP, **20%** chance to lower Speed
- **ThunderShock:** 45 BP, **10%** paralysis chance
- **Ember:** 45 BP, **20%** burn chance
- **Powder Snow:** 45 BP, **10%** freeze chance
- **Vine Whip:** 45 BP, **10%** chance to flinch
- **Fury Cutter:** 30 BP; doubles each turn, capped after 3 turns
- **Leech Life:** 65 BP
- **Absorb:** 25 BP
- **Mega Drain:** 50 BP
- **Razor Wind:** restored increased critical-hit ratio
- **Needle Arm:** 70 BP
- **Bullet Seed:** 25 BP (Modernized)

---

## Physical Coverage Additions

Added:
- **Fire Fang**
- **Thunder Fang**
- **Ice Fang**
- **Night Slash**

### Fang Adjustments
Because Gen IV flinch mechanics aren’t present:
- Fire Fang: **20%** burn
- Thunder Fang: **20%** paralysis
- Ice Fang: **20%** freeze
- They use the regular in game battle effects for status
---

## Generation IV Move Additions

### U-Turn
- 70 BP
- 100 accuracy

### Volt Switch
- 70 BP
- 100 accuracy

### Custom Switch Logic
U-Turn and Volt Switch use custom battlescripts and animations.

The battle effect is labeled HitEscape like it is in other forks but this was built from the ground up using existing Baton pass battlescripts and Spikes battlescripts.

Behavior:
- No switch occurs after defeating a wild Pokémon.
- No switch occurs after defeating a trainer’s final Pokémon.
- If a switch is impossible, the user is visually sent back out from Poké Ball to the field after experience is resolved.

This prevents cases where a Pokémon vanishes and later reappears without explanation.

**Wild-battle note (animation detail):**
If a wild Pokémon uses U-Turn, it animates as if it leapt/flew away. You will see the wild pokemon return out of a thrown pokeball. This is intended.

**Encounter table note:**
You technically should not run into this scenario during normal encounters. If you use a randomizer and a wild Pokémon uses U Turn, you may see this behavior.

If you want to remove it for alternate animations, you can remove:
- `switchinanim BS_ATTACKER, TRUE` (this is the pokeball throw)
- This is found where the script follows the end path for example: `BattleScript_HitEscapeEnd:` , `BattleScript_HitEscapeEnd2` , and  `BattleScript_HitEscapeArenaFaintedMon` path where EXP is resolved and fainted pokemon are handled.
- How the move **works** is in battle_scripts.s 
- How the move is **animated** is in battle_anim_scripts.s 

I used the switchin animation in the battlescript(battle_scripts.s) because it looks clean and worked well with the move animation script (battle_anim_scripts.s).
- Might migrate things to TM's instead at a later time. Avoids the the wild pokemon flying out of a ball thing completely. 

Tested in:
- Single Battles
- Double Battles
- Battle Frontier formats
- Battle Arena
- Battle Tents

### Sucker Punch
- 70 BP
- 100 accuracy
Partially adapted from Exalted Emerald. Used a SpecialVar like they did. Mostly looked at the frame work to adapt it here.
Includes a custom animation compatible with Modern Emerald assets.

### Roost
- Added.
- Works like Recover.
- Does not remove the Flying type.

### Judgment
- 100 BP
- Uses the hidden power effect when not using the Multitype Ability. Works like normal gen iv Judgment while ability is Multitype. 
- Refer to Hidden Power table at bottom


---

## Other Move Additions 

### Barrier Rush (Psyshield Bash – name too long)
- 70 BP Physical move
- 50% chance to raise Defense

### Twin Beam
- 50 BP
- Hits twice

### Hyper Drill
- 70 BP
- New functionality: works like Smelling Salts.
- Doubles damage against PAR targets and removes paralysis.
- (Especially useful with Serene Grace Body Slam.)

### Rage Fist
- 60 BP (Ghost)
- Functions like normal Rage in Gen 3.
- Stacks with Defiant until stat stages cap.

### Stone Axe
- Added as a **Rock-type** move.
- **50 BP**, **90 accuracy**, hits twice.
- Available on:
  - **Kleavor**
  - **Kabutops**

### Head Smash
- Added as a **110 BP recoil** move.
- **85 accuracy**.
- Recoil behaves like Double-Edge (style-wise).
- Replaces Stone Edge on many Pokémon.

---

## Hidden Priority Moves (Prankster-Style)
Several Pokémon gain hidden “Prankster-style” priority moves.

These moves:
- Have increased priority.
- Must be relearned using a Heart Scale at MOVE RELEARNER in Fallarbor.
- The moves are recover, will o wisp, taunt, and torment with +1 priority
- 
Available on:
- Murkrow / Honchkrow
  -Taunt/Torment 
- Shuppet / Banette
  -Taunt/Torment/Will O Wisp 
- Sableye
  - Taunt/Torment/Will O Wisp/Recover

---

## Ability Changes

Most Pokémon now have access to a secondary ability. Many received alternatives based on Gen 4–5 results or similar themes (e.g., Blastoise → Rain Dish, Venusaur → Chlorophyll, Charizard → Drought).

Abilities can be changed using the **Ability Changer in Lilycove City**.

### Ability Reworks

**LightningRod**
- Works like Speed Boost for Sp. Atk. 
- Conditional to require Rain for boosts to trigger.
- Sceptile and Manectric benefit on rain teams.
- Retains Electric Redirection in doubles.
- No Electric Immunity added (Standard gen 3 mechanics here).

**Forecast**
- Recovers 1/8 HP in Weather each turn (sandstorm is not considered weather).

**Ice Body and Rain Dish**
- Boosted to recover 1/12 HP per turn in Weather vs 1/16

**Water Veil**
- Added a 1/16 HP recovery unconditional. (think aqua ring)

**Early Bird**
- Recovers 1/8 HP while sleeping each turn.
- Balanced by the reduced sleep counter (Original ability effect unchanged).

**Truant**
- Recovers 1/8 HP while sleeping each turn.
- Still skips every other turn while awake. 

**Oblivious**
- Intimidate prevented
- Taunt immunity

**Own Tempo**
- Intimidate prevented

**Color Change**
- Still changes on hit
- New effect: Kecleon's normal moves change with the type change
- Move type change also works with reworked camouflage
- Kecleon can now build evasion stages using camouflage after color change type change 

**Pickup**
- Retains original function outside of battle.
- New in battle function.
- Every move used against a pokemon with pickup gives it a 20% chance to find a berry that gives a random +2 stat stage.
- Status down moves and attack moves work.
- I set it up so multi-hit moves get a roll each hit.

**Keen Eye**
- Modernized to ignore evasion stages.

**Damp**
- Added a 50% reduction to fire damage like thick fat
  
**Stench**
- Added a 10% accuracy penalty to opponents targeting defender with stench ability
- Slightly different flavor than flinch chance in modern games.
- Should stack with bright powder.

**Hyper Cutter**
- Same as before.
- Also buffs **ViceGrip** (now 75 BP bug-type) “like Crush Claw.”
- This is a **1.2×** buff (90 BP).
- Distributed to: Pokémon with pincers and Trapinch.

**Rough Skin**
- Buffed to take **1/8** damage on contact.
- Distributed to: Gyarados (No moxie for you!), still has Intimidate.
  -Gyarados already has a strong moveset Dragon Dance, Ice Fang, Waterfall, Headsmash, Earthquake, Crunch 
- Sharpedo still has Rough Skin but has Speed Boost for second ability.

**Plus & Minus**
- 1.1× damage boost outside Double Battles.
- Given to:
  - Pikachu
  - Mareep line

**Illuminate**
- 1.1× boost to Electric-type attacks. (Standard in base Modern Emerald)
- 10% accuracy loss on opponents targeting pokemon with illuminate

**Run Away**
- 1.2× Defense and Special Defense below 50% HP.
- Ability adds +1 Speed Stage below 50% HP.
- Max +1 Stage above Default gained from Run Away.
	- Works like Speed boost 
	- Only triggers if speed is less than or equal to default stage	
	- Only triggers on end turn
	- Because it is a stat stage -> Agility and X Speed work with it
		- +1 stage is a 1.5x speed boost.
		- Abillity will add +1 every turn until the net result is +1 stage over default.
		- For refrence Speed Boost will go until it hits the cap +6 stages over default.
		- For reference Swift Swim and Chlorophyll are a 2x buff on entry with weather.
		- Example: A +2 Speed Stage from agility will cause this ability not to trigger the speed change.
		- Example: A +1 from Run Away and +2 from agility means +3 total.
		- Example A -2 speed stage will go up +1 every turn if run away is triggered -> -2,-1,0,+1, Ability stops.
		- the 1.2x defenses boost is mainly for triggering the ability consistantly it allows for the rare cases where you have a sliver of HP and can counter. 

**Guts**
- Added a Guts Failsafe to activate at low HP
- This exists as an alternative to Flame Orb
- Works Like Run Away
- +1 ATK at 30% HP if <=DEFAULT ATK STAGE
- Will only trigger if not under a status (STATUS1)
- Will not go over +1 ATK
- Ramps up each turn to hit net +1 stage over default
- If at +2 and above from sword dance, ETC it will not activate
- Rare case exists where you get status after this activates and get boost from both failsafe and normal guts attack buff.
	- If you last long enough for that its fair game the way I see it.

**Multitype**
- REMOVED: damage boost from matching correct hold items to attack types. Arceus retained Normal type.
- NEW: Type changes based on hold item effect.
    - Works on switch in and displays message of type change.     
    - Applies correct type STAB.
    - Added capacity for ability to change type on hit if hold effect changed
        - Allows for more gen 3 friendly behavior.
        - Trace can change type on hit with correct hold effects.
        - Knock off can remove type by removing item (reverts to normal)
        - Trick can switch items and change type on hit
- Judgment now changes with type!

**Legend Plate** 
- Arceus gains second new ability
- Retains Normal Type but judgment takes new form-> Works like Hidden power use the table at the bottom to pick your type or let RNG pick.
- Static 2x boost to judgment (2.4x with correct hold item) TESTED
- Compared to Multitype Judgment (STAB (1.5)x 1.2 Hold Effect = 1.8x) TESTED
- 

---

## New Ability Distributions

**Adaptability**
- STAB increased to 2×.
- Given to:
  - Delcatty
  - Eevee
  - Corphish
  - Crawdaunt
  - Porygon-Z
  - Hitmontop
  - Deoxys-A

**Iron Fist**
- 1.2× boost to punching moves.
- Given to:
  - Hitmonchan
  - Breloom

**Reckless**
- 1.2× boost to recoil moves.
- Given to:
  - Hitmonlee
  - Rhyperior
  - Tauros
  - Bagon
  - Machamp
  - Machoke
  - Machop

**Berserk**
- 1.5× Special Attack below 50% HP.
- Given to:
  - Omastar (**LORD HELIX**)
  - Farigiraf
  - Deoxys-D
  - Houndoom

**Sharpness**
- 1.2× boost to slicing moves.
- Given to:
  - Gallade
  - Kleavor
  - Scyther

**Tough Claws**
- 1.2× boost to contact (PHYSICAL) moves.
- Given to:
  - Persian
  - Meowth 
  - Swellow
  - Tailow
  - Metagross
  - Metang
  - Beldum
  - Aerodactyl 

**Skill Link**
- Given to:
  - Ambipom (Check Egg Moves)
  - Cloyster
  - Heracross (lost Swarm)

**Strong Jaw**
- Granbull (Got lots of biting moves)
- Retains 1.5x boost because on granbull none of the moves get STAB

**Super Luck**
- Replaces Sniper on most affected Pokémon.
- Given to:
  - Fearow
  - Spearow
  - Honchkrow
  - Murkrow
  - Beedrill
  - Kingdra
  - Seadra
  - Horsea
  - Octillery
  - Remoraid

**Defiant**
- Gives 1 Attack stat stage instead of 2 (made it immune to intimidate for this reason)
- Given to:
  - Mankey
  - Primeape
  - Annihilape
  - Farfetch'd
  - Mightyena
  - Poochyena
  - Vigoroth
  - Regigigas (also got Guts)

**Rivalry**
- 1.25× damage vs same-gender opponents.
- 0.9× damage vs opposite-gender opponents.
- Given to:
  - Nidoking Evo. line
  - Nidoqueen Evo. line
  - Goldeen + Seaking (Territorial goldfish/betta)
  - Barboach + Whiscash (Territorial catfish)

**Run Away** 
- Electivire gets reworked Run Away as it is closer to Motor Drive/Rattled. 
- Clamperl (also got reworked modern rapid spin as egg move -> +1 speed )

**Legend Plate**
- Arceus gets second ability
- Retains Normal Type
- Judgment gets 2x multiplier.

**Multitype**
- Arceus
- Unown (also has levitate)
  - Unown has new movepool  
 

---

## Type-Changing Abilities
These abilities change move typing only and do not add extra damage boosts.

**Dragonize**
- Feraligatr

**Aerilize**
- Salamence
- Pinsir
- Pidgeot (Movepool leans towards special attacker)
- Pidgeotto
- Pidgy

**Pixilate**
- Sylveon


**Metal Coat** (new)
- Makes Normal-type moves Steel.
- Scizor
- Registeel

I wanted a simple way to modernize Scizor in a Gen 3 ecosystem. Example moveset options: (STEEL) Quick Attack, U-Turn, Swords Dance, (STEEL) Body Slam (para chance), and (BUG) ViceGrip (50% def down chance).

Additional Scizor changes:
- Lost Double-Edge via tutor 
- Gained Body Slam via tutor
- Gained Mega Kick via tutor

**Mind’s Eye** (Reworked to be similar to Dragonize)
- Normal-type moves become Ghost-type
- Bloodmoon Ursaluna
- Typhlosion

NOTE: Silk Scarf still gives a 1.2× hold boost to type changed moves.
A workaround was applied so correct hold items give the 1.2× boost to type changed normal moves.

---

## Weather Abilities
NOTE: **Hail update** -> Blizzard is accurate in Hail (Gen IV), Ice types get 1.5x Defense boost in Hail (Gen IX snowscape)
- NEW: ICE types get boost 1.3x to ICE MOVES 
**Restricted to type unlike sun/rain fire/water boosts. Have to be adapted to damaging weather.**
NOTE: **Sandstorm update** -> Rock-type Pokemon get 1.5x Special Defense boost in sandstorm like gen iv.
- NEW: STEEl types get boost 1.3x to STEEL MOVES
- NEW: GROUND types get boost 1.3x to GROUND MOVES
**Restricted to type unlike sun/rain fire/water boosts. Have to be adapted to damaging weather.**

**Drizzle**
- Wingull
- Pelipper
- Politoed
- Luvdisc
- Zapdos
- Kyogre

**Drought**
- Charmander line
- Vulpix
- Ninetales
- Moltres
- Chikorita line
- Sunflora
- Torkoal
- Groudon

**Sand Stream**
- Sandshrew Evo. line
- Shuckle
- Phanpy Evo. line
- Tyranitar

**Snow Warning**
- Smoochum
- Jynx
- Articuno
- Froslass
- Glaceon

**Ice Body**
- Seel
- Dewgong
- Articuno
- Spheal Evo. line
- Snoorunt Evo. line
- Regice
- Glaceon

**Air Lock**
- Zubat Evo. line
- Lugia
- Rayquaza

**Cloud Nine**
- Psyduck Evo. line
- Dragonite
- Stantler
- Wyrdeer
- Swablu
- Altaria

---

## Pokémon Changes

**some pokemon have changed stats**
- Pidgeot lost some attack(-10) and def(-5) to gain +20 SpAtk
- Fearow gained +10 HP
- Swellow gained +5 Atk and +10 SpDef
- Honchkrow remains high attack/sp atk and high hp with low defenses

**Wailmer + Wailord**
- Significant changes to base stats. 
- Retains HP
- Stats moved around and new ability:
        [SPECIES_WAILORD] =
        .baseHP        = 170,
        .baseAttack    = 50, // -40
        .baseAttack_old    = 90,
        .baseDefense   = 75, // +30
        .baseDefense_old   = 45,
        .baseSpeed     = 20, // -40
        .baseSpeed_old     = 60,
        .baseSpAttack  = 110, // +20
        .baseSpAttack_old  = 90,
        .baseSpDefense = 75, // +30
        .baseSpDefense_old = 45,
        .abilities = {ABILITY_HUGE_POWER, ABILITY_OBLIVIOUS},
**Swellow**
- Now Fighting/Flying
- slightly buffed stats and new movepool

**Typhlosion**
- Now Fire/Ghost (Hisuian-themed).

**Feraligatr**
- Now Water/Dragon.

**Blastoise**
- Now Water/Steel.

**Bloodmoon Ursaluna**
- Added as Ground/Ghost.

**Pinsir**
- Now Bug/Flying (Mega themed) 

**Scyther and Kabutops**
- Both get 1.5x damage bonus (STAB) to Normal Type Slash 70bp 

---

## Item Changes

### Hold Items
- All type-boosting hold items increased to 1.2× power.
- (Maybe you won’t use Leftovers now?!)

**NEW:** Everstone now also works as Eviolite!
- 1.5× Defense / Special Defense boost.
- Rare drop/catch from:
  - Geodude
  - Graveler
  - Golem
  - Eevee
  - Scyther (Safari Zone)

## Modified Shiny Chain System from Base Modern Emerald

## Sweet Scent Chaining and Chain Fishing

The shiny chain system adds additional shiny rolls as the chain increases. The selected shiny rate remains the base chance, while maintaining a longer chain increases the number of independent shiny checks per encounter.

Current formula:

```c
shinyRolls = 1 + chain / 3;
```

A longer chain gradually increases shiny encounter frequency without replacing the selected shiny rate.

### Shiny Rolls by Chain Length

| Chain | Shiny Rolls |  1/16 |  1/32 |  1/64 | 1/128 | 1/256 |
| ----: | ----------: | ----: | ----: | ----: | ----: | ----: |
|     0 |           1 |  6.2% |  3.1% |  1.6% |  0.8% |  0.4% |
|    20 |           7 | 36.3% | 19.9% | 10.4% |  5.3% |  2.7% |
|    50 |          17 | 66.6% | 41.7% | 23.5% | 12.5% |  6.4% |
|    80 |          27 | 82.5% | 57.6% | 34.6% | 19.1% | 10.0% |
|   100 |          34 | 88.9% | 66.0% | 41.5% | 23.4% | 12.5% |

### Design Intent

* **1/16 and 1/32:** Designed for players who want to actively target hunt specific Pokémon. The chain helps reduce the frustration of finding rare encounters.
* **1/64:** A middle-ground shiny experience that rewards hunting while keeping shinies special.
* **1/128 and 1/256:** Intended as more relaxed, lower-grind alternatives to traditional shiny rates.
* The chain system rewards dedication by increasing shiny opportunities over time rather than directly changing the base shiny odds.

The goal is for longer chains to feel increasingly rewarding while keeping the selected shiny rate meaningful.


## HIDDEN POWER/JUDGMENT TABLE

| Stat            | Fighting |  Flying |  Poison |  Ground |   Rock  |   Bug   |  Ghost  |  Steel  |  Fairy  |
| --------------- | :------: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| **HP**          |    30    |    30   |    30   |    30   |    30   |    30   |    30   |    30   |    30   |
| **Attack**      |    30    |    30   |    30   |    30   |    30   |    30   |    30   |    30   |    30   |
| **Defense**     |    30    |    31   |    30   |    31   |    30   |    31   |    30   |    31   |    30   |
| **Sp. Attack**  |    30    |    30   |    30   |    30   |    31   |    31   |    31   |    31   |    30   |
| **Sp. Defense** |    30    |    30   |    30   |    30   |    30   |    30   |    30   |    30   |    31   |
| **Speed**       |    30    |    30   |    31   |    31   |    30   |    30   |    31   |    31   |    30   |
| **Total IVs**   |  **180** | **182** | **182** | **184** | **182** | **184** | **184** | **186** | **182** |

| Stat            |   Fire  |  Water  |  Grass  | Electric | Psychic |   Ice   |  Dragon |   Dark  |
| --------------- | :-----: | :-----: | :-----: | :------: | :-----: | :-----: | :-----: | :-----: |
| **HP**          |    30   |    30   |    30   |    30    |    30   |    30   |    30   |    31   |
| **Attack**      |    30   |    30   |    30   |    30    |    30   |    30   |    30   |    31   |
| **Defense**     |    31   |    30   |    31   |    30    |    31   |    30   |    31   |    31   |
| **Sp. Attack**  |    30   |    30   |    30   |    31    |    31   |    31   |    31   |    31   |
| **Sp. Defense** |    31   |    31   |    31   |    31    |    31   |    31   |    31   |    31   |
| **Speed**       |    30   |    31   |    31   |    30    |    30   |    31   |    31   |    31   |
| **Total IVs**   | **184** | **184** | **186** |  **184** | **186** | **186** | **188** | **186** |

# BASE MODERN EMERALD DOCUMENTS AND INFO
This is a decompilation of Pokémon Emerald, edited to be "Pokémon Modern Emerald".
You can get more information about Modern Emerald at [Pokecommunity](https://www.pokecommunity.com/showthread.php?t=494005)
You can get the hackrom documentation following [this link](https://docs.google.com/spreadsheets/d/1QEFJmFhfaZqgxSUnM7MFpufrnrRk_NMzNoNWl2m3y_0/edit#gid=414283818)

# If you want to compile:

Please follow [Pret's guide on how to build the rom](https://github.com/pret/pokeemerald/blob/master/INSTALL.md) but using this branch instead of theirs. 
When compiling, **use the modern compiler** with the "make modern" command. 
_Compiling using the old compiler won't work._
The game was compiled using `(devkitARM release 62) 13.2.0`, but it _should_ work up to `release 65` without any issues. Higher versions may not work, so manual fixes might be required.

# 🦀MODERN EMERALD EXPANDS!

Official releases:
* [Pokémon Modern Heart and Soul](https://github.com/resetes12/HNS_modern) by myself
    * Experience Johto and Kanto, but now with enhancements, bug fixes, and other stuff.
* Pokémon Modern FireRed & LeafGreen by myself
    * _Soon_ ™️. Experience FRLG, but Modernized.

Modern Emerald has been used as a base to create other hacks:
* [Pokémon Heart and Soul](https://github.com/PokemonHnS-Development/pokemonHnS) by @lildill31
    * Experience Johto and Kanto, but for the GBA!
* [Pokémon Emerald Worped](https://github.com/worpbane/pokeemerald-worped/) by @worpbane

Modern Emerald also has some small mods:
* [Modern Emerald with ORAS Tilset](https://github.com/lbsbezerra/pokeemerald-modern-oras) by @lbsbezerra

# 📃 DOCUMENTATION:

[Documentation can be found online](https://docs.google.com/spreadsheets/d/1QEFJmFhfaZqgxSUnM7MFpufrnrRk_NMzNoNWl2m3y_0/edit?gid=1310408794#gid=1310408794)
Includes:
- Pokémon location and changes (plus an extra, more specific Pokémon location).
- Static and special encounters.
- New item locations (only includes new locations, old locations still work unless told otherwise).
- Other information that could be relevant.

# ✨FEATURES

**Selectable options (at the start of the game):**
Check which options are enabled or disabled by going to any Pokécenter PC and opening the "CHALLENGES" option.

Gamemode page:

* Choose between a "Classic" or "Modern" preset, or customize it to your liking. **WARNING! All selected options are permanent until starting a new game.**
* Encounter modes: Original, New (aka Modern), and Post-game.
    - "Original encounters" are vanilla Emerald encounters with zero changes. R/S exclusives are NOT included.
    - "New (modern) encounters" include all 423 Pokémon between the game and the post-game.
    - "Post-game encounters" are vanilla Emerald encounters UNTIL beating the game. Afterwards, it uses the "New encounters" tables.
* Modern Typings: Some Pokémon have their types changed to buff them (Check docs).
* Add Fairy Type: Adds Fairy Type to Pokémon that had it added in Generation 6. Note: Only affects Pokémon typing. Moves are controlled by "Pokémon Movepool" option.
* Better Stats: Some Pokémon have their stats changed to buff them (Check docs).
* Extra Legendaries: Adds new legendaries that weren't available in vanilla Emerald. Check docs for the location, or explore by yourself!
* Legendary abilities: Buffs some legendaries giving them a better ability than "Pressure".
* Pokémon Movepool: Adds 14 new moves, and modifies all Pokémon movepool to add them. TM/HMs and egg moves are also modified.
* Type chart: The type effectiveness has been slightly balanced to slightly power up less useful types. 
    - Dark and Ghost do 1x to Steel
    - Water does 0.5x damage to Ice
    - Ice does 1x to Water
    - Bug does 1x to Ghost and Fairy
    - Steel does 1x to Ice
    - Rock does 0,5x to Rock
    - Rock does 1x to Ground
    - Ground does 1x to Rock
      Choosing the "GenVI+" type chart only adds Steel not resisting Ghost and Dark.
* Nature mints: Adds nature mints to the game, available after the 4th gym, or after becoming champion (if disabled from the start).
* Synchronize: Choose if this ability works like in modern games or like in Gen 3.
* Sturdy: Choose if this ability works like in modern games or like in Gen 3.
* Reusable TMs: Choose between a faithful usage of TMs or a simplistic option that makes TMs infinite. All TMs can be bought in the Battlefrontier PokéMart only if you have Reusable TMs off, and makes Move Tutors one time only just like in the original (Move tutors are infinite if you enable Reusable TMs).
* Sitrus berry: Choose if it works like Gen 3 or like Gen 4+.
* Survive Poison: If enabled, your Pokémon will survive poison damage with 1hp when outside of battle.

Features page:
* RTC Type: Choose between using a real clock, or using a fake clock. Fake clock rate is 1h irl, 1 day ingame.
* Shiny Chance: 8192 (Emerald default) - 4096 (Gen VI+) - 2048 - 1024 - 512.
* Shiny Colors: Enables or disables new shiny colored forms for 24 Pokémon.
* Item Drops: Items held by wild Pokémon, when defeated, will be dropped and obtained by the player. Forget about catching it or using Thief!
* Wondertrade: Wondertrade stations are available in the 1BF of every Pokécenter. If disabled, they will be available after beating the game.
* Uncapped wondertrade: No 3-daily limit.
* Easier Feebas: If enabled, Feebas have a 5% chance to appear around the whole Route 119.
* Frontier bans: Decide if you want legendaries banned or not in Battle Frontier. If enabled, remember that the bans depend on your chosen difficulty!

Randomizer page:
* Includes every option that any randomizer has, and it's completely modular.
  For technical reasons, some special or particular Pokémon might not be randomized. 

Nuzlocke page:
* Any option that any Nuzlocker would want to use. Includes EASY, NORMAL, and a HARDCORE mode, plus many options.

Difficulty page:
* Lock difficulty: locks the current select option that was selected during Birch's Speech and can't be changed in-game. Hard sets "Battle Style" to "Set" always. Beating the game disables the lock.
* Number of Party Members limit: From 1 to 5
* Level caps: Includes two difficulties, Normal caps and Hard caps.
* Exp. Multipliers: Choose between x1, x1.5, x2 or x0.
* Hard mode Experience: Reverts the exp. nerf that Hard Mode does (Not recommended, Hard Mode exp. gain has been manually tested)
* Less chance of running away: Enabling this feature will be like in SMT games; running away from battles isn't as easy!
* Player items: Control whether you can use items in battles, or not.
* Trainer items: Control whether enemy trainers can use items in battles, or not.
* Player IVs: Sets all IVs from wild Pokémon to 31 if "No" is chosen. If you choose "No (HP)", it uses between 30 and 31 to allow for different Hidden Powers.
* Trainer IVs: Control whether enemy trainers have 31 IVs in every stat, or if they should have the default IV value set by the game. "Scale" uses gym badges to slowly add IVs. If enabled together with "Player IVs", you'll completely remove IVs from the game (everyone will have 31 IVs)!
* Player EVs: Control whether your Pokémon can get EVs, or not. "Off" is Emerald default, "Scale" offers a good challenge, and "Hard" and "Extreme" are what they say they are.
* Trainer EVs: Control whether enemy Pokémon can get EVs, or not. Doesn't affect the Battle Frontier, they still have EVs!
* Escape Rope / Dig: Prevent the usage of Escape Rope and prevent using Dig while in dungeons.

Challenges page:
* Pokécenter challenge: Play without Pokémon Centres.
* PC doesn't heal: Enabled by default in the Pokécenter Challenge.
* Ultra expensive challenge: Don't you always have spare money? Maybe not anymore. Offers x5, x10, and x50.
* Evolution limits.
* One type only challenges: You can catch only one type of Pokémon.
* BST equalizers.
* Mirror Mode.
* Mirror Mode Thief.

**Story related:**
* You can now name your rival!
* Mom gives you a new "Outfit box" so you can switch between the Emerald outfit and the Ruby and Sapphire outfits.
* Gym rematches are easier to trigger. After 10 wild battles or 5 trainer battles won, there is a 50% chance of getting a rematch.
* The Elite Four can be rematched after battling with Steven, and they can be single or double battles (you choose!)
* After completing the Elite Four Rematch, a rematch with Steven will be available. You will get a unique, special prize.
* The Sealed Chambers puzzles have changed slightly. Learn Braille and find out what changed!
* Also, there are 6 Regis. Try to discover where the new 3!
* All the trainer rematches scale up a lot more than in the original game, and their parties have been changed.
* All the trainers in the Battle Frontier have new Pokémon in their teams and have been buffed or modified. Includes all the new Post-Gen 3 Pokémon.
* All the gym leaders, Elite Four, the 2 champions, Wally, Magma / Aqua leaders, and Red and Leaf will appear during the Battle Frontier challenges.


**Pokémon related:**
* Following Pokémon _(Optional, with a second option to enable or not Big Followers like Rayquaza)_.
* Unique surfing animations _(Optional)_.
* 44 new Pokémon species, mostly from Generation 4, and a few Gen 9 (Annihilape, Dudunsparce, Farigiraf).
* 1 new box space, for a total of 450 Pokémon box space.
* Birch's bag can show shiny starters!
* New shiny star (like FRLG) in the summary page. Also shows up in eggs that have shiny species inside!
* All the buffs from later generations are in _(Optional)_.
* Extra buffs for other Pokémon are in. Includes stats, abilities and/or typings. (Ex. Arbok is now POISON / DARK and Meganium is now GRASS / FAIRY) _(Optional)_.
* Pokémon have new learnsets, which are a mix from Gen 3 and newer generations _(Optional)_.
* All Egg moves and tutor moves have been improved with data from later generations, plus some extra ones.
* New evolution methods.
* Pokémon inherit 5 IV's from their parents, no item is needed.
* The number of steps needed for leveling up Pokémon in the daycare has been decreased.
* Everstone works on male or female Pokémon and guarantees nature.
* Gen. VIII Synchronize _(Optional)_.
* Shuckle can make berry juice just like in Gen. II!! Yay?
* Groudon has STAB with Fire moves, but retains its Ground-only typing _(Optional, "Pokémon stats" needs to be set to Modern)_.
* Spinda has a 2% chance of multiplying by two the damage of moves _(Optional, "Pokémon stats" needs to be set to Modern)_.
* Nature Mints are available to buy in the Flower Shop after the 4th Gym _(Optional)_, or after becoming champion if not enabled from the start.
* Deoxys forms can be changed at Birth Island, using the meteorites.
* All Hoenn and National Dex Pokémon need to be obtained to obtain the Completion Diploma, or it won't count as completed.


**Battle related:**
* Modern Battle Frontier, Battle Tents and Trainer Hill. Your Pokémon will be limited to level 50 when playing in those battle facilities, even if your level is 1 or 100.
* Some of the Move buffs AND nerfs from later generations are in, with small changes to make them work in a 3rd gen game _(Optional)_.
* HM01 Cut is now Grass type, Night Shade does 50 static damage, Hidden Power is now 60 static damage and shows the type in the summary screen and in battle, and more move buffs and changes.
* 15 new Moves from Gen IV to buff typings that didn't have a certain Physical / Special move. (Ex. Dark Pulse, as Dark type didn't have a Special Dark type move). _(Optional)_.
* Fairy type introduced _(Optional)_.
* 4 New abilities for Sylveon, Regidrago, Regieleki and Arceus.
* Gen. VI EXP. SHARE and Gen III EXP. SHARE in the same game. "EXP. SHARE S" can be obtained at the Slateport Mart after obtaining the "EXP. SHARE" at Devon Corp.
* A new ability tutor, after becoming champion, is available in Lilycove.
* EV Training is available in Lilycove.
* IV Maximizer is available in Lylicove, after beating the game, with the option to set IVs to 30 or 31 to allow different Hidden Potentials. Needs a level 100 Pokémon.
* A nurse NPC is available after beating the game to farm EXP. in Lilycove.
* New battle backgrounds, completely optional, in the options menu.
* x2 battles! Enable "Anim Speed" option in the options menu.
* Faster battle intros. Enable "Fast Intros" option in the options menu.
* Faster-paced battles. Enable "Fast Battles" option in the options menu.
* Win streaks in the Battle Frontier multiply the amount of Battle Points obtained even more.
* 3 beeps when low-health, then it stops.
* Press START while selecting a move to open a new Submenu with information about the selected move.
* Trainer class-based Pokéballs.
* Catching EXP.
* Macho Brace multiplies EV gain * 5.
* Gen. IV Sitrus Berry _(Optional)_.


**UI related:**
* The game has been fully decapped! Hard work made by @fanyx
* New Pokédex! You can now see important information on the new "Stats" page. It's very, VERY useful, and it's like having the game documentation in-game.
* The Pokédex can now be scrolled faster: if you hold left or right, it will advance like before, but without the need to keep pressing left and right.
* The Pokédex can now be scrolled faster than faster! If you hold left or right AND you hold the R button, it will scroll even faster than explained above!
* Faster trainer transitions ported from Fire Red.
* Choose between holding L+R+A or holding B when entering a wild battle to instantly run, or pressing B when the battle has started to run away faster. _(Optional)_.
* You can now register 2 key items: Pressing (as usual) and holding SELECT!
* Swap Pokémon in the Party Menu by pressing SELECT.
* Colored Stats (red = good, blue = bad).
* Pressing L in the stats section of a Pokémon will bring the EVs, pressing R will bring the IVs, and pressing START will bring the default stats.
* HM moves don't need to be taught anymore. If you have a Pokémon that can use a certain HM, if you have the correct HM in the bag, and if you have the required badge, you will be able to perform an HM move.
* (Nuzlocke only) HMs do not impede advancing in the game. Pokémon that usually don't learn certain HMs will now learn them in order not to halt your progress.
* HM moves can be deleted since they are not that important anymore.
* Some TMs had their price changed, especially if you are not using Infinite TMs.
* The bag now holds up to 90 items, and item capacity has been upgraded to x999.
* When the bag is full, items go to the PC.
* You can change the ball your Pokémon is in using a different ball from the bag.
* "Move" can be used from "Item" submenu in the Summary screen
* Reusable repel prompt.
* The time on the clock can be changed by pressing R, and time events should work. Can be also changed the official way by pressing R+B+LEFT on the main menu.
* Three pages with additional options in the options menu.
* New friendship and shiny indicator in the Summary Page of every Pokémon (ported from Heart and Soul)
* The Pokédex now registers Shiny Pokémon, which can be seen pressing the A button.
* Debug menu can be enabled by everybody, so you can cheat or modify whatever you want. **BE MINDFUL THAT IT CAN BREAK YOUR SAVE IF USED INCORRECTLY!** Refer to the Faq to learn how.


**Gameplay related:**
* RNG is fixed and properly works.
* _(Optional, but gets enabled for every save after beating the game)_ Wonder Trade is available on the basement floor of every Pokémon Center, available after the 5th badge unless you are doing a randomizer, which makes it available from the start, or a challenge, which enables WT after beating the game. The number of Wonder-trades is 3 per day, unless using the "Unlimited Wondertrades" option.
* Wonder Trade uses a tier system, so rare Pokémon are rare to obtain as well. 
* 3 difficulty modes (EASY, NORMAL and HARD). Selected at the start of the game, can be changed anytime from the options menu (unless using the "Limit difficulty" option).

    EASY mode: Makes the game quite a lot easier by scaling levels down, and obtaining more EXP. (+20%).
    - Trainer Pokémon and Wild Pokémon scale down to 10 levels compared to the original game. More badges, lower levels.
    - There are no restrictions on the Battle Frontier.

    NORMAL mode: Vanilla.
    - No changes, except rematches and small things (also on EASY mode).

    HARD mode: Makes the game a bit more difficult. This mode does not intend to offer a "difficulty" hack-rom, it only tries to be a bit more difficult than vanilla, especially mixed with other options like EV/IV scaling, for example.
    - Experience gain has been lowered by 40% to make up for the level scaling, plus some more. There's an option to remove this slower Exp. gain, although it is not recommended, as it has been hand-crafted and tested.
    - Trainer Pokémon and Wild Pokémon scale up to 10 levels compared to the original game. More badges, more levels.
    - Certain ace Pokémon have had their abilities or items changed to make everything a bit more difficult. This mode does not change anything else in most trainer parties or their strategies.
    - "SET MODE" is automatically selected and can't be disabled if you lock the difficulty.
    - Only four items can be used in battle.
    - There are more restrictions on the Battle Frontier _(Optional)_.
    - The GEN VI Exp. Share will give less Exp. to the battling Pokémon.
    - Legendaries will have higher stats WHILE battling, to make it more challenging, and some will have their catch rate reduced. They are now true Boss Battles! Good luck!

* Optional PHYSICAL / SPECIAL MOVE split from Gen. IV+. Selected in the options menu, second page.
* Day / Night System. Now, Daytime is from 6AM to 20PM. Night-time is from 20PM to 6AM. For the 2 new evolutions, Morning is from 6AM to 9AM. Also includes cool lighting at night!
* Run everywhere.
* Autorun (in the options menu).
* HM moves text and interaction is way faster.
* Rock smash provides Shards and Heart Scales.
* Link with Fire Red / Leaf Green available from the start.
* One-time tutors are infinite, but you have to pay now (only if Infinite TMs is on).
* Trainer Hill rewards have been greatly improved: You'll always get 20BP for each win and, if you finish within 10min or less, you can obtain Gamecube exclusive berries (Ganlon, Petaya, Salac & Apicot Berry) and up to 1.000.000$ (scales with time spent during the Trainer Hill challenge). 
* Match and Acro Bike are now one. Change between them by pressing "R".
* Easier fishing has been added to the options menu (FR/LG fishing).
* Chain fishing AND Sweet Scent chaining!
* All tickets are available to buy in the Battle Frontier.
* Faster nurse Joy healing, and now with an even faster version in the options menu (with a confirmation sound).
* A new item, the Big Nugget! It can be sold for a very high price. Available from Rich trainers (rematch only).
* You can check the Soot Sack to know how much ash you have.
* Interacting with berry trees is faster.
* Berry trees that are in rainy routes don't need to be watered, and berry trees don't decay.
* Higher berry yield (6 max, 4 min).
* A new "Growth Mulch" item, which makes berries instantly grow.
* New Self-trader to force trade evolutions (trading with another game still works).
* PokéMarts' items change with every badge.
* AI improvements, although nothing too drastic.
* Amulet coin works always, doesn't matter who has it.
* New NPC in the Battle Frontier Pokécenter that lets you turn off some enabled challenges from your savegame (EvoLimit, Mirror, Mirror Thief, Limit Difficulty, One Type challenge, Party Limit, PokeCenter Challenge, No Items (Player), No Items (Trainer))

**Map related:**
* Navel Rock is now a proper dungeon.
* Unown Chamber is now part of Navel Rock.
* A few new maps to introduce the new Regis and the legendary events.
* New zone in the Safari zone to capture the Hoenn starters _(not available for "Original Encounters")_
* Mirage Island can be forced with a certain Pokémon in the party, apart from its unusual rate, and works even if they are sitting on the PC.

**Sound related:**
* Added all the music and sound effects from Pokémon Diamond, Pearl, Platinum, HeartGold, and SoulSilver.
* You can listen to all this music using the combo "Right DPAD + Select + B" in the Title Screen.
* All legendaries have their music swapped for something different using all the newly included tracks from the games mentioned above.
* Option to disable or enable music.
* Option to disable or enable Surf and Bike music.
* Option to choose between different tracks for Wild Battles, Trainers and Frontier Trainers ("Hoenn", "Kanto 1", "Sinnoh", "Johto", "Kanto 2", "Random").
* Option to choose between "Gen 3", "DPPl", and "HGSS" sound effects.

# 🔧 FOR DEVELOPERS:

Please follow [Pret's guide on how to build the rom](https://github.com/pret/pokeemerald/blob/master/INSTALL.md) but using this branch instead of theirs. 

When compiling, **use the modern compiler** with the "make modern" command. 
_Compiling using the old compiler won't work._

The game was compiled using `(devkitARM release 62) 13.2.0`, but it _should_ work up to `release 65` without any issues. Higher versions may not work, so manual fixes might be required.

# 🗿 QUICK FAQ:

**Can't open the repo in Porymap!**
* This project is not yet compatible with Porymap 6. Use Porymap 5 instead.

**I can't compile Modern Emerald!!**
* First thing: When compiling, **you have to use the modern compiler** with the "make modern" command. The old compiler will never work.
* Second thing: The game was compiled using `(devkitARM release 62) 13.2.0`, but it should work up to `release 65`. Higher versions WON'T probably work, for many reasons, as of right now.

**My game crashes on an emulator that's not recent / it's not mGBA or real hardware!**
Decompilation hack-roms may crash or have strange bugs if you are using other emulators other than mGBA or a real GBA. This is not something I can fix, as it relies on the base pokeemerald project adding support or fixes to it.

**Help! PkHex / PKSM / Similar tools or apps can't open the savefile!**
These programs rely on knowing where to find the data on the savefile, and Modern Emerald has modified certain parts of the savedata which makes it incompatible with these apps or tools. Use the debug menu to cheat, as it provides the same options, mostly.

# 🤷‍♂️ AI DISCLAIMER

* 99,9% of my code has been made by hand.
    - Currently, only one commit has had some help from an AI.
    - Contributors do not count towards this percetange. I do not control or limit any contributor.
* Some text strings have been corrected or had their wording improved using AI tools.

# 🪪 CREDITS

* [Pret's Pokeemerald](https://github.com/pret/pokeemerald) for its base
* Pret's Wiki Tutorials:
    - TONS of their tutorials were used!
* Repos:
    - HGSS / DPPt / BW music from: 
        - https://github.com/CyanSMP64/pokeemerald/tree/dppt_hgss_music 
        - https://github.com/CyanSMP64/pokeemerald/tree/dppt_hgss_bw_music_old
    -  Day/Night system / Followers:
        - https://github.com/aarant/pokeemerald/tree/followers-expanded-id
    - PHY/SP new icons and Stab indicator:
        - https://github.com/worpbane/pokeemerald-worped/commits/battle-ui-rework/
    - Many stuff was ported from HnS:
        - https://github.com/PokemonHnS-Development/pokemonHnS
* Contributors:
   - Decap by @fanyx
   - Tweaks and commits by [@aloven](https://github.com/aloven), [@pinkshellos](https://github.com/PinkShellos), [@insertCreativeName5](https://github.com/InsertCreativeName5). [@davidgfnet](https://github.com/davidgfnet), [@unique-github-username](https://github.com/unique-github-username), [@TixoRebel](https://github.com/TixoRebel), [@bfedie5](https://github.com/bfedie518) and [@deepCeadeus](https://github.com/deepCeadeus)
