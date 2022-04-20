---
title: 'Power Tempest'
date: '2021-02-24'
rating: 'Other'
role: 'Power Damage'
archive: true
hidden: false
profession: 'Elementalist'
specialization: 'Tempest'
benchmark: { large: { dps: 38069, by: 'Roul [SC]', youtube: '7tF8y7bUoQU' } }
skills: [29719, 5734, 5624, 5516]
traits: [1502, 1503, 1839]
boons:
  - name: Might
  - name: Fury
  - name: Swiftness
  - name: Protection
  - name: Vigor
  - name: Stability
conditions: ['Weakness', 'Vulnerability', 'Blinded', 'Burning', 'Bleeding']
code: '[&DQYRPikvMBsXARcBQgHLAL4BTgFQAVABlwCZEgAAAAAAAAAAAAAAAAAAAAA=]'
---

The <Specialization name="Tempest" text="Power Tempest"/> is a strong DPS variant for fractals with various utilities the <Specialization name="Weaver"/> counterpart doesn't offer.

It has very high burst damage in fast-paced fights and its overall DPS is only contested by the [Sword Weaver](/builds/elementalist/power-weaver) on huge hitboxes.  
Thanks to <Skill name="Overload Air"/>, the group's damage is buffed by around 1k DPS, so at least one <Specialization name="Tempest"/> is never a bad idea when thinking about group composition.

Apart from great DPS, the build afflicts tons of <Condition name="Vulnerability"/> and helps keeping up <Boon name="Might"/> with <Skill name="Heat Sync"/>.

For projectile-heavy scenarios, <Skill name="Aftershock"/> and <Skill name="Sand Squall"/> can be used, <Skill name="Shocking Aura"/> and <Skill name="Cyclone"/> help against trash mobs and defiance bars.

Contrary to the [Sword Weaver](/builds/elementalist/power-weaver), melee hate like <Instability name="Social Awkwardness"/> or disruptions like <Instability name="Last Laugh"/> don't matter that much since you can stand on range and have access to a multitude of defensive mechanics like <Boon name="Stability"/> and <Trait name="Gale Song"/>.

The degree of difficulty is a little bit higher than the other <Specialization name="Elementalist"/> builds, as you need to adhere to many small things to achieve top numbers.  
The positioning and timing of skills matter a lot, a single mistake can make your DPS end up several thousand below other damage dealers.

The build benefits heavily from slaying potions and sigils such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>

<CharacterWithAr>

<Character gear={{
  "profession": "Elementalist",
  "weight": "Light",
  "gear": [
    "Berserker",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Assassin",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 13995,
    "Armor": 2210,
    "Power": 3425,
    "Precision": 2574,
    "Toughness": 1243,
    "Vitality": 1235,
    "Ferocity": 2082,
    "Condition Damage": 850,
    "Expertise": 0,
    "Concentration": 483,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.322,
    "Critical Chance": 0.9995238095238095,
    "Critical Damage": 2.888,
    "Power Coefficient": 4408,
    "Burning Coefficient": 4.4,
    "Bleeding Coefficient": 4.4,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Burning Duration": 0.2,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 26669.902586333137,
    "Power DPS": 45267.974817310926,
    "Siphon DPS": 45267.974817310926,
    "Bleeding Damage": 109.472625,
    "Bleeding Stacks": 4.4,
    "Bleeding DPS": 481.67955,
    "Burning Damage": 394.02646875,
    "Burning Stacks": 5.28,
    "Burning DPS": 2080.459755,
    "Confusion Damage": 134.14145625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 126.7183125,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 162.4093875,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 47969.86412231092,
    "Effective Health": 73221686.00253552,
    "Survivability": 37225.0564324024,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24723,
  "runeName": "Eagle",
  "infusions": [
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432
  ],
  "weapons": {
    "weapon1MainType": "Scepter",
    "weapon1MainSigil1Id": 24615,
    "weapon1OffType": "Warhorn",
    "weapon1OffSigilId": 24868,
    "weapon2MainSigil2Id": 24868
  },
  "consumables": {
    "foodId": 91805,
    "utilityId": 50082
  },
  "skills": {
    "healId": 21656,
    "utility1Id": 5624,
    "utility2Id": 5734,
    "utility3Id": 5539,
    "eliteId": 5516
  },
  "assumedBuffs": [
    {
      "id": "might",
      "type": "Boon"
    },
    {
      "id": "fury",
      "type": "Boon"
    },
    {
      "id": "protection",
      "type": "Boon"
    },
    {
      "id": "vulnerability",
      "type": "Condition"
    },
    {
      "id": "bannerOfStrength",
      "gw2id": 14405,
      "type": "Skill"
    },
    {
      "id": "bannerOfDiscipline",
      "gw2id": 14407,
      "type": "Skill"
    },
    {
      "id": "frostSpirit",
      "gw2id": 12497,
      "type": "Skill"
    },
    {
      "id": "jade-bot-base",
      "type": "Text"
    },
    {
      "id": "jade-bot-per-tier",
      "type": "Text"
    },
    {
      "id": "assassinsPresence",
      "gw2id": 1786,
      "type": "Trait"
    }
  ]
}} >

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>

<Character gear={{
  "profession": "Elementalist",
  "weight": "Light",
  "gear": [
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 13995,
    "Armor": 2300,
    "Power": 3610,
    "Precision": 2569,
    "Toughness": 1333,
    "Vitality": 1235,
    "Ferocity": 2076,
    "Condition Damage": 850,
    "Expertise": 0,
    "Concentration": 573,
    "Healing Power": 0,
    "Agony Resistance": 222,
    "Condition Duration": 0,
    "Boon Duration": 0.382,
    "Critical Chance": 0.9971428571428571,
    "Critical Damage": 2.8840000000000003,
    "Power Coefficient": 4408,
    "Burning Coefficient": 4.4,
    "Bleeding Coefficient": 4.4,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Burning Duration": 0.2,
    "Siphon Base Coefficient": 139.75,
    "Effective Power": 28027.863444278297,
    "Power DPS": 47572.90029356132,
    "Siphon DPS": 47572.90029356132,
    "Bleeding Damage": 109.472625,
    "Bleeding Stacks": 4.4,
    "Bleeding DPS": 481.67955,
    "Burning Damage": 394.02646875,
    "Burning Stacks": 5.28,
    "Burning DPS": 2080.459755,
    "Confusion Damage": 134.14145625,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 126.7183125,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 162.4093875,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 50274.789598561314,
    "Effective Health": 76203564.6180234,
    "Survivability": 38741.008956798876,
    "Effective Healing": 390,
    "Healing": 390
  },
  "runeId": 24723,
  "runeName": "Eagle",
  "infusions": [
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432
  ],
  "weapons": {
    "weapon1MainType": "Scepter",
    "weapon1MainSigil1Id": 24615,
    "weapon1OffType": "Warhorn",
    "weapon1OffSigilId": 24868,
    "weapon2MainSigil2Id": 24868
  },
  "consumables": {
    "foodId": 91805,
    "utilityId": 50082
  },
  "skills": {
    "healId": 21656,
    "utility1Id": 5624,
    "utility2Id": 5734,
    "utility3Id": 5539,
    "eliteId": 5516
  },
  "assumedBuffs": [
    {
      "id": "might",
      "type": "Boon"
    },
    {
      "id": "fury",
      "type": "Boon"
    },
    {
      "id": "protection",
      "type": "Boon"
    },
    {
      "id": "vulnerability",
      "type": "Condition"
    },
    {
      "id": "bannerOfStrength",
      "gw2id": 14405,
      "type": "Skill"
    },
    {
      "id": "bannerOfDiscipline",
      "gw2id": 14407,
      "type": "Skill"
    },
    {
      "id": "frostSpirit",
      "gw2id": 12497,
      "type": "Skill"
    },
    {
      "id": "jade-bot-base",
      "type": "Text"
    },
    {
      "id": "jade-bot-per-tier",
      "type": "Text"
    },
    {
      "id": "assassinsPresence",
      "gw2id": 1786,
      "type": "Trait"
    }
  ]
}} >

You need Fractal God, <Item id="86175"/> and 18 Mighty +9 Agony Infusion !

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!

</Character>

</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Water" traits1SelectedIds="363,349,361" traits2="Air" traits2Selected="Ferocious Winds, Stormsoul, Fresh Air" traits3="Tempest" traits3SelectedIds="1886,1902,1839"/>

<Card title="Situational Skills">

|                                                                   |                                                                                                                                                                                                                                                                                                                                                     |
| ----------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Heal                                                              |
| <Skill name="Glyph of Elemental Harmony" size="big" disableText/> | A stronger healing alternative if <Boon name="Might"/> uptime is good.                                                                                                                                                                                                                                                                              |
| <Skill name="Wash the pain away" size="big" disableText/>         | Another healing alternative affecting allies close-by.                                                                                                                                                                                                                                                                                              |
| Offensive                                                         |
| <Skill name="Arcane Wave" size="big" disableText/>                | Use this skill instead of <Skill name="Arcane Blast"/> if you need extra cleave damage at the cost of some target dps. Also useful to generate <Boon name="Might"/> with a fire field.                                                                                                                                                              |
| <Skill name="Conjure Frostbow" size="big" disableText/>           | Faster burst than <Skill name="Conjure Lightning Hammer"/> on large hitboxes with the bonus of being semi-ranged.                                                                                                                                                                                                                                   |
| Defensive                                                         |
| <Skill name="Arcane Shield" size="big" disableText/>              | Provides three blocks for things like the console in [Underground Facility Fractal](/fractals/underground-facility).                                                                                                                                                                                                                                |
| <Skill name="Armor of Earth" size="big" disableText/>             | Another defensive utility skill granting <Boon name="Protection"/> and <Boon name="Stability"/>.                                                                                                                                                                                                                                                    |
| <Skill name="Aftershock" size="big" disableText/>                 | A group-wide reflect aura lasting for 4 seconds.                                                                                                                                                                                                                                                                                                    |
| Utility                                                           |
| <Skill name="Lightning Flash" size="big" disableText/>            | A teleport with a range of 900 units. Very important skill for certain skips, especially in combination with <Item name="White Mantle Portal Device"/>, useful in fractals like [Cliffside Facility Fractal](/fractals/cliffside), [Aetherblade Fractal](/fractals/aetherblade) and [Underground Facility Fractal](/fractals/underground-facility). |
| <Skill name="Eye of the Storm" size="big" disableText/>           | Grants <Effect name="Superspeed"/>, useful for skips, especially in combination with <Item name="Executioner Axe Toy"/> or <Item name="endlesschoyapiatatonic"/>.                                                                                                                                                                                   |
| <Skill name="Signet of Fire" size="big" disableText/>             | If you don't reach 100% critical chance and are too lazy to get Assassin's pieces, take this instead of <Skill name="Arcane Blast"/>.                                                                                                                                                                                                               |

</Card>
</GridItem>

<GridItem sm="5">

<Card title="Swap Weapons">

- Scepter with <Item name="Night" type="Sigil"/>
- Warhorn with <Item name="Serpent Slaying" type="Sigil"/>
- Scepters with slaying sigils (see [Consumables Guide](/guides/consumables))
- A dagger for <Skill name="Ring of Fire"/> (fire field for <Boon name="Might"/>-stacking) and <Skill name="Ride the Lightning"/> (skipping)

</Card>

<Card title="Situational Traits">

|                                                       |                                                                                                                                                                   |
| ----------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Trait name="Gale Song" size="big" disableText/>      | Useful automatic group stunbreak for things like <Instability name="Last Laugh"/>.                                                                                |
| <Trait name="Soothing Power" size="big" disableText/> | Use this instead of <Trait name="Powerful Aura"/> when you are not using <Trait name="Unstable Conduit"/>.                                                        |
| <Trait name="Raging Storm" size="big" disableText/>   | If you can't profit from <Trait name="Stormsoul"/> (e.g. Warden Amala in [Twilight Oasis](/fractals/twilight-oasis).                                              |
| <Trait name="One with Air" size="big" disableText/>   | Useful for skipping with <Effect name="Superspeed"/>, especially in combination with <Item name="Executioner Axe Toy"/> or <Item name="endlesschoyapiatatonic"/>. |

</Card>
<Card title="Defiance Bar Damage">

|                                                       |                                         |
| ----------------------------------------------------- | --------------------------------------- |
| <Skill name="Shocking Aura" size="big" disableText/>  | 100 with <Control name="Stun"/>         |
| <Skill name="Cyclone" size="big" disableText/>        | 150 with <Control name="Pull"/>         |
| <Skill name="Blinding Flash" size="big" disableText/> | 20 / s with <Condition name="Blinded"/> |
| <Skill name="Wind Blast" size="big" disableText/>     | 232 with <Control name="Launch"/>       |
| <Skill name="Dust Storm" size="big" disableText/>     | 20 / s with <Condition name="Blinded"/> |
| <Skill name="Tidal Surge" size="big" disableText/>    | 150 with <Control name="Knockback"/>    |

</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="6">
<Card title="Skill Priority">

Your entire rotation revolves around using <Skill name="Overload Air"/> as often as possible.

Apart from that, you have the following modifiers:

- <Trait id="1839"/>: 7% damage and condition damage for 7 seconds after <Skill name="Overload Air"/>
- <Trait name="Fresh Air"/>: 250 ferocity for 5 seconds after attuning to air
- <Trait name="Stormsoul"/> and <Item name="Impact" type="Sigil"/> when the target's defiance bar is broken
- <Skill name="Conjure Lightning Hammer"/>: 75 ferocity while wielding it
- <Skill name="Conjure Fiery Greatsword"/>: 260 power while wielding it

You want to use your most damaging skills while these modifiers are active.  
Therefore your basic rotation optimally is:

1. <Skill name="Overload Air"/>
2. Attune to _something_ else
3. Critically hit with _something_ fast to trigger <Trait name="Fresh Air"/>
4. <Skill name="Air Attunement"/>
5. High damage skills like <Skill name="Lightning Storm"/>, <Skill name="Lightning Orb"/> and <Skill name="Arcane Blast"/>
6. Repeat

In reality, the _something_ looks like the following:

- In <Skill name="Fire Attunement"/>:
  - <Skill name="Wildfire"/>
  - <Skill name="Phoenix"/>
  - <Skill name="Dragons Tooth"/>
- In <Skill name="Earth Attunement"/>:
  - <Skill name="Dust Storm"/> (only on large hitboxes)
- In <Skill name="Water Attunement"/>:
  - <Skill name="Shatterstone"/> (useful for <Condition name="Vulnerability"/>)

When attuning back to <Skill name="Air Attunement"/>, you will have 5 seconds cooldown before you can use <Skill name="Overload Air"/> again.  
During this window you want to use your conjured weapons:

1. <Skill name="Conjure Lightning Hammer"/>
   1. <Skill name="Invoke Lightning"/>
   2. <Skill name="Lightning Swing"/> => <Skill name="Static Swing"/> => <Skill name="Thunderclap" profession="bundle" />
2. <Skill name="Conjure Fiery Greatsword"/>
   1. <Skill name="Fiery Rush"/>
   2. <Skill name="Firestorm" profession="bundle"/>
   3. <Skill name="Fiery Whirl"/> (if you can whirl against a wall or have to switch targets)

And lastly, you should use <Skill name="Lightning Strike"/> (instant cast) off recharge and <Skill name="Heat Sync"/> whenever <Boon name="Might"/> is low on the group.

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Opener">

1. If a Mistlock Singularity is present
   1. <Skill name="Conjure Fiery Greatsword"/> and reset its cooldown with it
2. <Skill name="Air Attunement"/>
   1. Precast <Skill name="Overload Air"/> so it finishes when the fight starts
   2. <Skill name="Firestorm" profession="bundle"/> (if you are wielding a <Skill name="Conjure Fiery Greatsword" disableText/>)
   3. <Skill name="Lightning Orb"/> (from range, ideally it should pass through the mob/boss when its defiance bar is broken)
   4. <Skill name="Lightning Storm"/>
3. <Skill name="Fire Attunement"/>
   1. <Skill name="Wildfire"/>
   2. <Skill name="Dragons Tooth"/>
   3. <Skill name="Phoenix"/>
4. <Skill name="Earth Attunement"/> (only on huge hitboxes)
   1. <Skill name="Dust Storm"/>
5. <Skill name="Air Attunement"/>
   1. <Skill name="Conjure Lightning Hammer"/>
   2. <Skill name="Invoke Lightning"/> (inside the target's hitbox)
   3. <Skill name="Lightning Swing"/> => <Skill name="Static Swing"/> => <Skill name="Thunderclap" profession="bundle" /> and 3x <Skill name="Arcane Blast" />
   4. <Skill name="Overload Air"/>
6. <Skill name="Fire Attunement"/>
   1. <Skill name="Dragons Tooth"/>
7. <Skill name="Air Attunement"/>
   1. <Skill name="Conjure Fiery Greatsword"/>
   2. <Skill name="Fiery Rush"/>
   3. <Skill name="Firestorm" profession="bundle"/>
   4. <Skill name="Lightning Orb"/>
   5. <Skill name="Overload Air"/>

</Card>

<Card title="Advanced Notes">

- Always cast <Skill name="Lightning Orb"/> from as far as possible.
- Try to place the outer ring of <Skill name="Overload Air"/> directly on the target and make sure the cast finishes.
- Cast <Skill name="Invoke Lightning"/> while standing inside the target's hitbox to make sure all strikes hit.
- Remember to already switch to the next attunement _while_ casting skills.
- <Skill name="Arc Lightning"/> (your <Skill name="Air Attunement"/> auto-attack) deals more damage the longer you channel it, but every other skill has a higher priority.

</Card>
</GridItem>
</Grid>
