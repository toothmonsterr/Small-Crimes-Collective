---
tags:
  - system
  - player
---
Downtime actions are based off of real world time and are associated with two categories: **regular** and **progress**.
## Regular Actions
**Regular** actions are able to be done **once a day**, with a reset of your daily allowance at **midnight EST**, meaning you do not need to wait a full 24 hours to do your daily downtime. These actions are free and do not cost resources unless specified.

The regular actions available are as follows:
* Forming Bonds with Players or NPCs
* Resting
* Working for zenit
* [[Crafting#Transmutation|Transmuting]] materials
### Bonds
Bonds can be formed with any player character or NPC you have interacted with. You must have an established relationship with the PC to form a bond with them. Every bond starts with a strength of 1 and a single emotion unless otherwise stated by a feature or quirk, ex. the Fettered Heart quirk.

Bonds formed must be logged in downtime-log using the following format:
```
Character: [Character Name]
Action: Bonds with [Character Name]
Bond Level:
Emotion(s):
```

It is also recommended you log it in your character's profile thread.
### Relaxing
Relaxing can be done once a day, and will have the benefit of charging your HP and MP up to full. You still have to [[Marketplace#Replenishing|replenish your IP]] through spending zenit, which you can mark in the market-log channel.

You gain **+1 Fabula Point** every time you relax provided you have **less than 4 Fabula Points**. You cannot gain more than 4 Fabula Points by relaxing.

Resting also triggers Skills from classes that provide resources each time you **Rest**. Otherwise, those effects only happen during Games. This includes but is not limited to gaining money from **Winds of Trade** as a Merchant and gaining ingredients from **Cooking** as a Gourmet. Though, you can only benefit from each of these features once per week.

Relaxing must be logged in downtime-log using the following format:
```
Character: [Character Name]
Action: Relaxes
Gains: [+1 Fabula Point|Cooking|Etc]
```
### Earning Zenit
Zenit can be earned in downtime once a day. There are two options for making zenit through downtime:
* **Working a job** -- An average day at work. Make an 【INS + WLP】 check and multiply your result by ([[Player Progression#Player Tiers|character tier]] * 2). That result is the zenit you earn.
* **Doing dangers** -- Expeditions, pit fighting, and other physical labors. Make a 【DEX + MIG】 check and multiply your result by (character tier * 2). That result is the zenit you earn.

Earning zenit must be logged after the rolls described above using this format:
```
Character: [Character Name]
Action: Earns zenit through [working a job|doing dangers]
Gains: [Zenit earned]
```
### Transmutation
TBD.
## Progress Actions
**Progress** actions require the use of a currency known as **Echo Points** (EP). All characters start with **4** EP, and more are gained on a weekly basis. Characters gain **2** EP at the start of every Saturday (midnight EST), and can have a **maximum** of **8** EP.

Progress actions currently available are as follows:
* [[Crafting#Creating Equipment|Creating Equipment]] through crafting
* Projects
* Rituals
* Retraining
* Research

To start a Progress action, you **must** have the available zenit, XP, and/or materials to spend upfront. The exception to this is EP-- you do not need the total to be available immediately, and you are free to progress clocks as you gain EP week-over-week.
### Progressing the Clock
Progress actions are almost always associated with a Clock. Progressing the clock **requires** spending EP to progress it. The exchange rate is generally 1 EP per tick on the clock.

Other players, as long as they share a [[Crafting#Crafting Classes Table|prerequisite class]] for the task at hand (ex. a Weaponmaster assisting a Commander to craft a martial melee weapon), can help progress preexisting clocks provided they have discussed it with the clock's owner. The exchange rate remains 1 EP per tick, but from the other player's EP pool.

In some certain circumstances, such as exceptionally powerful projects or crafting world-changing artifacts, progressing the clock may also require a successful check. When present, failing this check can cause complications to the action or even reverse the clock. 
### Equipment Crafting
Creating equipment with EP is generally based on the rarity of the [[Materials]] required. For example, a [[Crafting#Custom Weapons|Custom Weapon]] at is base level only requires **common** materials, so it would only cost 1 EP to craft. In this case, a clock is not required, however a **🌠mythic** material would have a clock with 8 ticks.

Crafting generally does not require checks to progress clocks.

| Rarity     | Total EP Cost | Clock Segments |
| ---------- | ------------- | -------------- |
| common     | 1             | N/A            |
| ❇️crafted  | 2             | 2              |
| 🌀strange  | 4             | 4              |
| ✨enigmatic | 6             | 6              |
| 🌠mythic   | 8             | 8              |
You'll use the following template to start the progress action in downtime-log:
```
Character [Character Name]
Action: Crafting [Equipment Category]
Customizations: [If using a Custom Weapon]
Quality: [If equipment has a Quality]
Materials: [List of Materials used]
Clock: 0/[EP Cost]
```

You can create your clock within a thread branching off of the post you create. After making your thread (you need the channel to exist first), simply type /clock and create a clock with your needed segments using the provided Discord command. Track the EP you spend in this thread as well.
### Projects
Projects are custom inventions, consumables, or other enhancements that fall outside the realm of equipment and standard crafting. The primary purpose of projects are to provide interactions with the world in new ways without interfering with established mechanics. 

Projects **must** be started and progressed via downtime, meaning they cannot be started nor progressed during sessions in any way that influences the ongoing session.

Some examples of Projects include:
* Non-Combat Vehicles
* Exploration & Research Tools
* Environmental Changes
* Tactical devices (ex. spy equipment)
* Lore-based creations (ex. a project established to reverse a villain's clock)

You **cannot** create projects that do the following:
* Anything that alters combat mechanics -- Crafting and the use of [[Qualities]] are the system to use for this.
* Anything that intentionally ignores or subverts the spirit of the game. Improvise the parts of the game that expect you to improvise-- keep your projects restricted to the cool, interesting idea you had versus countless objects to subvert game mechanics.
* Items that nullify conflict -- No anti-magic fields, no mind control devices, no [[Threats|threat]] neutralizers.

Projects can be **vetoed.** If you want to craft a project that doesn't align with the above rules or is generally ill-suited for the server (ex. a spaceship), you may be told to halt your project and reconsider it.
#### Project Costs
Projects have elements to them that establish their potency, area of effect, and number of uses. Materials and zenit must be available up-front to start a project.

| Potency | Base Zenit | Base EP | The invention can...                                                                                                                                                                                    |
| ------- | ---------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Minor   | 100z       | 1       | Provide light, transport people or cargo on land or water, obtain some limited form of protection.                                                                                                      |
| Medium  | 200z       | 2       | Travel underwater, contain a spell, relay sound or speech, perform a specific operation in place of the inventor, provide short-term energy.                                                            |
| Major   | 400z       | 4       | Fly, alter the nature of an area for a short time, cancel the effects of a spell, possess minor intelligence, fight alongside the inventor, provide long-term energy, capture or immobilize the target. |
| Extreme | 800z       | 8       | Alter the nature of an area for a long time, contain the power of a demon, prevent a catastrophe, possess a full intelligence and personality                                                           |

| Area       | Zenit Multiplier | Additional EP cost | The effects of the invention may effect...                                                             |
| ---------- | ---------------- | ------------------ | ------------------------------------------------------------------------------------------------------ |
| Individual | x1               | 0                  | A human-sized creature, a door, a tree, or a weapon.                                                   |
| Small      | x2               | +2                 | A group of human-sized creatures, a large creature, a small clearing, a room, a railway car, or a hut. |
| Large      | x3               | +4                 | A crowd, a small forest, an airship or galleon, a castle hall, a house, or a giant creature.           |
| Huge       | x4               | +6                 | A fortress, a lake, the top of a mountain, a village, or a city block.                                 |

| Uses       | Zenit Multiplier | EP multiplier | Once activated, the invention can...                                        |
| ---------- | ---------------- | ------------- | --------------------------------------------------------------------------- |
| Consumable | x1               | x1            | Can never be used again unless the inventor creates a different copy of it. |
| Permanent  | x5               | x2            | Remains available for multiple uses in different situations.                |

Material can be used to lessen zenit costs. The reduction of zenit is based on the material's rarity tag. The conversions are as follows:

| Rarity     | Zenit Cost Reduction     |
| ---------- | ------------------------ |
| common     | -250z                    |
| ❇️crafted  | -500z                    |
| 🌀strange  | -1250z                   |
| ✨enigmatic | -1750z                   |
| 🌠mythic   | -2000z                   |
| 📕artifact | Replaces full zenit cost |

> [!info] Example
> A project with **Major** potency, **Small** effect, and a **single** use would cost 800 zenit and a 5 EP with a 5-section clock.

You will log your project with the following template:
```
Character [Character Name]
Action: Starting a Project
Description: [Short description of the project]
Cost: [Zenit]
Clock: 0/[EP Cost]
```

Similarly to crafting, create your clock within a thread branching off of the above post. Track the EP you spend here.
#### Tinkerer Projects
If you have the Visionary skill, your zenit costs are 【SL × 100】 cheaper. You get 【SL】 progress on the clock at the start of the project without the need to spend EP.
#### Gourmet Projects
The Gourmet class also allows for the completion of projects, with the caveat they are always **consumable**, meaning they are one-time use. Their area of effect is based on the number and type of creatures you need to nourish.
### Rituals
Similar to Projects, Rituals are custom magical effects, world-changing spells, or other magic-induced narrative change to the environment. Similarly, the primary purpose of rituals are to provide interactions with the world in new ways without interfering with established mechanics.

However, unlike projects, rituals can and often do occur during sessions, used as a tool to resolve circumstances with magical means. Rituals only become project actions when their scope falls outside the scope of the average or ongoing session.

Some examples of downtime rituals include:
* Rituals with an **Extreme** potency (ex. weaken a divine entity, prevent a catastrophe, cause a week-long change in a creature or location).
* Rituals with an area of **Huge** (ex. a fortress, a lake, a mountaintop, a village, a city block).
* Rituals that change any ongoing world-clocks, forward or backward.
* Rituals related to longer term plot threads.

Rituals should never:
* Cause direct damage to a group of enemies. Collateral damage **is** allowed, however-- for example, a chasm opening up beneath a group of enemies and causing them damage from a fall.
* Inflict or remove status effects on characters or enemies.
* Cause characters to lose, gain, or otherwise influence any currency (i.e. zenit, MP, HP, Fabula Points, etc).
* Replicate mechanical effects already existing via skills or spells.
* Generate equipment, creatures, or permanent abilities.

Downtime rituals **require** the use of materials to replace the upfront MP cost. This is **instead** of MP. As well, progressing Ritual Clocks with a potency of Medium or higher requires a successful Magic Check every tick of the progress clock.

The EP costs, material costs, and effectiveness of a given Ritual is as follows:

| Potency | Base EP | Material Cost                   | Magic Check DL |
| ------- | ------- | ------------------------------- | -------------- |
| Minor   | 1       | 1 x ❇️crafted or 2 x common     | 7              |
| Medium  | 2       | 1 x 🌀strange or 2 x ❇️crafted  | 10             |
| Major   | 4       | 1 x ✨enigmatic or 2 x 🌀strange | 13             |
| Extreme | 8       | 1 x 🌠mythic or 2 x ✨enigmatic  | 16             |

| Area       | Additional EP Cost | Material Mutliplier |
| ---------- | ------------------ | ------------------- |
| Individual | +0                 | x 1                 |
| Small      | +2                 | x 2                 |
| Large      | +4                 | x 3                 |
| Huge       | +6                 | x 4                 |

Failing the Magic Check has the result of either undoing a tick on the progress clock, *or* the effects of the ritual are changed or twisted in some unexpected way. If choosing the second option, ping a GM to propose or receive a twist to the ritual.

You will log your ritual with the following template:
```
Character [Character Name]
Action: Starting a Ritual
Description: [Short description of the ritual]
Cost: [Materials used]
Clock: 0/[EP Cost]
```
### Retraining
TBD.
### Research
TBD.