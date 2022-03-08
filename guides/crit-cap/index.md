---
title: Crit Cap
date: 2022-03-08T23:53:27.789Z
image: ./images/crit.png
description: Learn how to achieve crit cap on various Guild Wars 2 professions.
---

## Reasoning

Achieving 100% Critical Chance is desirable for most power-based Guild Wars 2 builds. As your Critical Damage will be much higher due to large amounts of Ferocity, the value of Critical Chance (and therefore Precision) exceeds other attributes like Power.

At level 80, the conversion formula to calculate Critical Chance from Precision is:

> `Critical Chance = (Precision - 895) / 21`

From the above equation, it follows that **2995 Precision** is enough to reach 100% Critical Chance.

You can subtract the following values in general:

- **1000 base Precision** at level 80

- 20% Critical Chance from **<Boon name="Fury"/>** (= **420 Precision**)

- In groups with a <Specialization name="Berserker"/>: **100 Precision** from **<Skill name="Banner of Discipline"/>**

- In groups with a <Specialization name="Druid"/> or <Specialization name="Soulbeast"/>: **100 Precision** from **<Trait name="Spotter"/>**

Which brings it down to **1475 Precision** or **1375 Precision** required (with <Trait name="Spotter"/>).

Apart from that, the <Item id="79722"/> grants Precision, Concentration and Toughness as high as `1.5 * Agony Resistance`.  
So **with 150 Agony Resistance you'd receive 225 additional Precision**.

Now we only need **1250 Precision** (without <Trait name="Spotter"/>) or **1150 Precision** (with <Trait name="Spotter"/>) to achieve 100% Critical Chance (`2995 - 1000 - 420 - 100 - 225` and `-100`)!  
We have two options to accomplish that - via items or skills/traits.

---

### Items

The most obvious choice would be <Item name="Accuracy" type="Sigil"/>, but in Fractals we want to take <Item name="Impact" type="Sigil"/> (and <Item name="Force" type="Sigil"/>) to benefit from frequently broken defiance bars.  
Which leaves us with item affixes and runes as other sources of Precision.

A full ascended set of **Berserker** items is equal to **961 Precision** (dual wield) or **960 Precision** (two-handed).  
So you'll only need a few more points of Precision to reach 100% Critical Chance:

| Agony Resistance                                                                                                                         | Without <Trait name="Spotter"/> + Dual Wield | Without <Trait name="Spotter"/> + Two-handed | With <Trait name="Spotter"/> + Dual Wield | With <Trait name="Spotter"/> + Two-handed |
| ---------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- | -------------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| 150 (Standard)                                                                                                                           | 289                                          | 290                                          | 189                                       | 190                                       |
| 162 (18x <Item id="37131" disableText/>, no [Augmentations](https://wiki.guildwars2.com/wiki/Account_Augmentation))                      | 271                                          | 272                                          | 171                                       | 172                                       |
| 207 (18x <Item id="37131" disableText/>, all [Augmentations](https://wiki.guildwars2.com/wiki/Account_Augmentation))                     | 203                                          | 204                                          | 103                                       | 104                                       |
| 222 (18x <Item id="37131" disableText/>, all [Augmentations](https://wiki.guildwars2.com/wiki/Account_Augmentation), <Item id="70596"/>) | 181                                          | 182                                          | 81                                        | 82                                        |

In general, you want to stack as much Agony Resistance as possible to benefit from the Precision conversion if you're not crit capped with profession-specific traits. <Item id="37131"/> is usually the way to go as better regular infusions (e.g. <Item id="49439"/>) are very expensive.  
After that, you need to swap Berserker items (Major: Power; Minor: Precision, Ferocity) for Assassins (Major: Precision; Minor: Power, Ferocity) to gain more Precision.

Keep in mind that you can also take <Item id="37132"/> but normally it is easier to calculate with a full set of Power infusions.

Use our [Gear Optimizer](https://optimizer.discretize.eu/) to calculate the optimal distribution of Assassin's items.

---

### Skills/Traits

While some professions have access to passive signet utility skills increasing Precision by 180 points, there is usually a better DPS skill if you are crit capped already.  
If for some reason your build isn't optimized yet and you are missing at least those 180 points, it is recommended to take the Precision signet instead of the weakest other utility skill.

Apart from that, various traits increase either Precision or Critical Chance directly.  
Some of them will easily put you above 100% Critical Chance so you don't need any Assassin's pieces.

Below are some popular trait choices to push Critical Chance.

---

#### Skills increasing Critical Chance

| Profession                            | Skill                             | Precision |
| ------------------------------------- | --------------------------------- | --------- |
| <Specialization name="Warrior"/>      | <Skill name="Signet of Fury"/>    | 180       |
| <Specialization name="Thief"/>        | <Skill name="Signet of Agility"/> | 180       |
| <Specialization name="Elementalist"/> | <Skill name="Signet of Fire"/>    | 180       |

---

#### Traits increasing Critical Chance

| Profession                            | Trait Line       | Trait                               | Condition                                                   | Critical Chance | Precision  |
| ------------------------------------- | ---------------- | ----------------------------------- | ----------------------------------------------------------- | --------------- | ---------- |
| <Specialization name="Elementalist"/> | Weaver           | <Trait name="Superior Elements"/>   | Target must have <Condition name="Weakness"/>               | 10%             | 210        |
| <Specialization name="Guardian"/>     | Radiance         | <Trait name="Radiant Power"/>       | Target must have <Condition name="Burning"/>                | 10%             | 210        |
| <Specialization name="Guardian"/>     | Radiance         | <Trait name="Righteous Instincts"/> | Player must have <Boon name="Resolution"/>                  | 25%             | 525        |
| <Specialization name="Guardian"/>     | Radiance         | <Trait name="Right-Hand Strength"/> | -                                                           | 3.8%            | 80         |
| <Specialization name="Ranger"/>       | Skirmishing      | <Trait name="Hunters Tactics"/>     | Player must hit from behind or the side                     | 10%             | 210        |
| <Specialization name="Ranger"/>       | Skirmishing      | <Trait name="Vicious Quarry"/>      | Player must have <Boon name="Fury"/>                        | 10%             | 210        |
| <Specialization name="Engineer"/>     | Firearms         | <Trait name="Hematic Focus"/>       | Target must have <Condition name="Bleeding"/>               | 10%             | 210        |
| <Specialization name="Engineer"/>     | Firearms         | <Trait name="High Caliber"/>        | Target must be closer than 300 units                        | 15%             | 315        |
| <Specialization name="Thief"/>        | Critical Strikes | <Trait name="Keen Observer"/>       | Player health must be above 90%                             | 5%              | 105        |
| <Specialization name="Thief"/>        | Critical Strikes | <Trait name="Twin Fangs"/>          | Player must hit from behind or the side                     | 7%              | 147        |
| <Specialization name="Necromancer"/>  | Curses           | <Trait name="Target the Weak"/>     | 2% per unique condition on target                           | up 28%          | up to 588  |
| <Specialization name="Necromancer"/>  | Reaper           | <Trait name="Decimate Defenses"/>   | 2% per stack of <Condition name="Vulnerability"/> on target | up to 50%       | up to 1050 |
| <Specialization name="Revenant"/>     | Invocation       | <Trait name="Roiling Mists"/>       | <Boon name="Fury"/> has increased effectiveness             | 20%             | 420        |
| <Specialization name="Revenant"/>     | Renegade         | <Trait name="Brutal Momentum"/>     | Player must have full endurance                             | 33%             | 693        |
| <Specialization name="Virtuoso"/>     | Virtuoso         | <Trait name="Quiet Intensity"/>     | Player must have <Boon name="Fury"/>                               | 10%             | 210        |

---

#### Traits increasing Precision

| Profession                            | Specialization | Trait                                 | Note                                                                  | Precision |
| ------------------------------------- | -------------- | ------------------------------------- | --------------------------------------------------------------------- | --------- |
| <Specialization name="Warrior"/>      | Discipline     | <Trait name="Doubled Standards"/>     | <Skill name="Banner of Discipline"/> (this only applies to yourself!) | 50        |
| <Specialization name="Thief"/>        | Deadeye        | <Trait name="Be Quick or Be Killed"/> | Target must be marked                                                 | 200       |
| <Specialization name="Elementalist"/> | Weaver         | <Trait name="Elements of Rage"/>      | Converts 13% of your Vitality to Precision                            |           |

_Note: Conversion traits only take flat modifiers from items, runes, food and infusions into consideration. Things like boons (e.g. <Boon name="Might"/>), traits (e.g. other conversions), skills (e.g. <Skill name="Signet of Fury"/>), group buffs (e.g. <Skill name="Banner of Strength"/>) or the <Item id="79722"/> are not included._
