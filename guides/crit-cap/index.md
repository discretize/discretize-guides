---
title: Crit Cap
date: 2022-08-02T23:55:00.885Z
image: ./images/crit.png
description: Learn how to achieve crit cap on various Guild Wars 2 professions.
---

## Reasoning

Achieving <Attribute name="Critical Chance" text="100% Critical Chance"/> is desirable for most **power-based** Guild Wars 2 builds. As your Critical Damage will be much higher due to large amounts of <Attribute name="Ferocity"/>, the value of <Attribute name="Critical Chance"/> (and therefore <Attribute name="Precision"/>) exceeds other attributes like Power.

At level 80, the conversion formula to calculate <Attribute name="Critical Chance"/> from <Attribute name="Precision"/> is:

> `Critical Chance = (Precision - 895) / 21`

From the above equation, it follows that **<Attribute name="Precision" text="2995 Precision"/>** is enough to reach <Attribute name="Critical Chance" text="100% Critical Chance"/>.

You can subtract the following values in general:

- **<Attribute name="Precision" text="1000 base Precision"/>** at level 80
- <Attribute name="Critical Chance" text="25% Critical Chance"/> from **<Boon name="Fury"/>** ( **<Attribute name="Precision" text="525 Precision"/>**)

Which brings it down to **<Attribute name="Precision" text="1470 Precision"/>**, without any traits, gear, upgrades or consumables.

---

### Gear

Runes and Sigils are our next step to consider increasing <Attribute name="Precision"/> The most obvious choice would be <Item name="Accuracy" type="Sigil"/>, but in Fractals we want to take <Item name="Impact" type="Sigil"/> (and <Item name="Force" type="Sigil"/>) to benefit from frequently broken defiance bars. Which leaves us with item affixes and runes as other sources of <Attribute name="Precision"/>.

A full ascended set of **Berserker** items is equal to **<Attribute name="Precision" text="961 Precision"/>** (dual wield) or **<Attribute name="Precision" text="960 Precision"/>** (two-handed).  
So you'll <Attribute name="Precision" text="509 Precision"/> (dual wield) or <Attribute name="Precision" text="510 Precision"/> (two-handed) to reach <Attribute name="Critical Chance" text="100% Critical Chance"/>. The next source of <Attribute name="Precision"/> we should consider our our runes:

| Common Power Rune Choices | <Attribute name="Precision" text="Precision Required Dual Wield"/>  | <Attribute name="Precision" text="Precision Required Two-Handed"/> |
| ----------------- | ---- | ----|
| <Item id="24836"/> | 509 | 510 |
| <Item id="24818"/> | 209 | 210 |
| <Item id="24723"/> | 334 | 335 |                        

If your chosen Rune doesn't have you reaching <Attribute name="Critical Chance" text="100% Critical Chance"/>, thye next step is to swap Berserker's items (Major: <Attribute name="Power"/>; Minor: <Attribute name="Precision"/>, <Attribute name="Ferocity"/>) for Assassin's (Major: <Attribute name="Precision"/>; Minor: <Attribute name="Power"/>, <Attribute name="Ferocity"/>) to gain more Precision. Additionally some condition builds such as <BuildLink build="Condi Virtuoso" specialization="Virtuoso"/> benefit from incresed <Attribute name="Precision"/>. In this case Viper's items (Major: <Attribute name="Condition Damage"/>, <Attribute name="Power"/>; Minor: <Attribute name="Expertise"/>, <Attribute name="Precision"/>) are swapped for Sinister (Major: <Attribute name="Condition Damage"/>; Minor: <Attribute name="Power"/>, <Attribute name="Precision"/>) and Rampager;s (Major: <Attribute name="Precision"/>; Minor: <Attribute name="Power"/>, <Attribute name="Condition Damage"/>) items. 

Our final gear choice we can make to increase <Attribute name="Precision"/> is to use Consumables and Infusions. Most pwer builds use <Item id="91805"/> for food. However <Item id="91709"/> can be a good choice if you miss a small amount of <Attribute name="Precision"/> to crit cap. Also availible to use is <Item id="12486"/> can be used but we would recmomend taking an extra Assassin's items if possible to be able to benefit from Acsended Feasts. 

Keep in mind that you can also take <Item id="39621"/> (Or its +7 and +9 counterparts), but normally it is easier to calculate with a full set of Power infusions.

Use our [Gear Optimizer](https://optimizer.discretize.eu/) to calculate the optimal setup of Runes, Sigils, Stats and Consumables.

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
| <Specialization name="Mesmer"/>     | Virtuoso         | <Trait name="Quiet Intensity"/>     | Player must have <Boon name="Fury"/>                               | 10%             | 210        |
| <Specialization name="Warrior"/>     | Strength         | <Trait name="Pinnacle of Strength"/>     | -                               | 5%             | 105        |
| <Specialization name="Warrior"/>     | Arms         | <Trait name="Furious Burst"/>     | Player must have <Boon name="Fury"/>                               | 5%             | 105        |

---

#### Traits increasing Precision

| Profession                            | Specialization | Trait                                 | Note                                                                  | Precision |
| ------------------------------------- | -------------- | ------------------------------------- | --------------------------------------------------------------------- | --------- |
| <Specialization name="Soulbeast"/>      | Beastmastery     | <Trait name="Pack Alpha"/>     | This will only apply to yourself if you are in <Skill name="Beastmode"/> | 150        |
| <Specialization name="Thief"/>        | Deadeye        | <Trait name="Be Quick or Be Killed"/> | Target must be marked                                                 | 200       |
| <Specialization name="Elementalist"/> | Weaver         | <Trait name="Elements of Rage"/>      | Converts 13% of your Vitality to Precision                            |           |

_Note: Conversion traits only take flat modifiers from items, runes, food and infusions into consideration. Things like boons (e.g. <Boon name="Might"/>), traits (e.g. other conversions), skills (e.g. <Skill name="Signet of Fury"/>) or the <Item id="79722"/> are not included._
