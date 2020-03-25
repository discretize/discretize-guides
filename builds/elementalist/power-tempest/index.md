﻿---
title: 'Power Tempest'
date: '2019-10-10'
rating: 'T4'
role: 'Damage'
profession: 'Elementalist'
specialization: 'Tempest'
benchmark: { large: { dps: 36152, by: 'Roul [SC]', youtube: '8LnAONl_a5w' } }
skills: [5536, 29719, 30432, 5734, 5624, 5516]
traits: [1502, 1839, 1503]
boons: ['Might', 'Fury', 'Swiftness', 'Protection', 'Vigor', 'Stability']
conditions: ['Weakness', 'Vulnerability', 'Blind', 'Burning', 'Bleeding']
code: '[&DQYRPikvMBsXARcBQgHLAL4BTgFQAVABlwCZEgAAAAAAAAAAAAAAAAAAAAA=]'
---

The <Specialization name="Tempest" text="Power Tempest"/> is a strong DPS variant for fractals with various utilities the <Specialization name="weaver"/> counterpart doesn't offer.

It has very high burst damage in fast-paced fights and its overall DPS is only contested by the [Sword Weaver](/builds/elementalist/power-sword-weaver) and [Staff Weaver](/builds/elementalist/power-staff-weaver) on huge hitboxes.  
Thanks to <Skill name="Overload Air"/> the group's damage is buffed by around 1k DPS, so at least one <Specialization name="Tempest"/> is never a bad idea when thinking about group composition.

Apart from great DPS, the build afflicts tons of <Condition name="vulnerability"/> and helps keeping up <Boon name="might"/> with <Skill name="Heat Sync"/>.

For projectile-heavy scenarios <Skill name="Aftershock"/> and <Skill name="Sand Squall"/> can be used, <Skill name="Shocking Aura"/> and <Skill name="Cyclone"/> help against trash mobs and defiance bars.

Contrary to the [Sword Weaver](/builds/elementalist/power-sword-weaver), melee hate like <Instability name="Social Awkwardness"/> or disruptions like <Instability name="Last Laugh"/> don't matter that much since you can stand on range and have access to a multitude of defensive mechanics like <Boon name="stability"/>, <Trait name="Gale Song"/>.

The degree of difficulty is a little bit higher than the other <Specialization name="Elementalist"/> builds as you need to adhere many small things to achieve top numbers.  
The positiong and timing of skills matter a lot, a single mistake can make your DPS end up several thousands below other damage dealers.

The build benefits heavily from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>

<Tabs outlined>
<Tab title="150 Agony Resistance"aaaaaaaaaaaaaaaaaaaaa>
Check the [gear optimizer](http://old.discretize.eu) for more gear variants!
<Grid>
<GridItem sm="4">
<Armor weight="Light" helmAffix="Assassin" helmRune="Scholar" shouldersAffix="Berserker" shouldersRune="Scholar" coatAffix="Assassin" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Assassin" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Scepter" weapon1MainAffix="Berserker" weapon1MainSigil1="Impact" weapon1OffType="Warhorn" weapon1OffAffix="Berserker" weapon1OffSigil="Force"/>

<Card title="Swap Weapons">
* Scepter with <Item name="Night" type="Sigil"/>
* Warhorn with <Item name="Serpent Slaying" type="Sigil"/>
* Scepters with slaying sigils (see [Consumables Guide](/guides/consumables))
* A dagger for <Skill name="Ring of Fire"/> (fire field for <Boon name="might"/>-stacking) and <Skill name="Ride the Lightning"/> (skipping)
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Assassin" accessory2Affix="Assassin" amuletAffix="Assassin" ring1Affix="Assassin" ring2Affix="Assassin"/>

<Consumables food="Bowl of Sweet and Spicy Butternut Squash Soup" utility="Tin of Fruitcake" infusion="Mighty +9 Agony Infusion"/>
</GridItem>
</Grid>
</Tab>

<Tab title="207 Agony Resistance">
<Grid>
<GridItem sm="4">
<Armor weight="Light" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Berserker" shouldersRune="Scholar" coatAffix="Berserker" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Scepter" weapon1MainAffix="Berserker" weapon1MainSigil1="Impact" weapon1OffType="Warhorn" weapon1OffAffix="Berserker" weapon1OffSigil="Force"/>

<Card title="Swap Weapons">
* Scepter with <Item name="Night" type="Sigil"/>
* Warhorn with <Item name="Serpent Slaying" type="Sigil"/>
* Scepters with slaying sigils (see [Consumables Guide](/guides/consumables))
* A dagger for <Skill name="Ring of Fire"/> (fire field for <Boon name="might"/>-stacking) and <Skill name="Ride the Lightning"/> (skipping)
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Assassin" accessory2Affix="Assassin" amuletAffix="Assassin" ring1Affix="Assassin" ring2Affix="Assassin"/>

<Card title="Extra note">
You need Fractal God, <Item id="86175"/> and 18  Mighty +9 Agony Infusion !
</Card>

<Consumables food="Bowl of Sweet and Spicy Butternut Squash Soup" utility="Tin of Fruitcake" infusion="Mighty +9 Agony Infusion"/>
</GridItem>
</Grid>
</Tab>
</Tabs>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Water" traits1SelectedIds="363,349,2028" traits2="Air" traits2Selected="Ferocious Winds, Stormsoul, Fresh Air" traits3="Tempest" traits3SelectedIds="1886,1902,1839"/>

<Card title="Situational Skills">
| | |
| -- | -- |
|Heal|
| <Skill name="Glyph of Elemental Harmony" size="big" disableText/> | A **stronger** healing alternative if <Boon name="might"/> uptime is good. |
| <Skill name="Wash the pain away" size="big" disableText/> | An alternative heal skill affecting allies close-by. |
|Offensive|
| <Skill name="Arcane Wave" size="big" disableText/> | Use this skill instead of <Skill name="Arcane Blast"/> if you need extra cleave damage at the cost of some target dps. Also useful to generate <Boon name="might"/> with a fire field. |
| <Skill name="Conjure Frostbow" size="big" disableText/> | Faster burst than <Skill name="Conjure Lightning Hammer"/> on large hitboxes with the bonus of being semi-ranged. |
|Defensive|
| <Skill name="Arcane Shield" size="big" disableText/> | Provides three blocks for things like the console in [Underground Facility Fractal](/fractals/underground-facility). |
| <Skill name="Armor of Earth" size="big" disableText/> | Another defensive utility skill granting <Boon name="protection"/> and <Boon name="stability"/>. |
| <Skill name="Aftershock" size="big" disableText/> | A group-wide reflect aura lasting for 4 seconds. |
| Utility |
| <Skill name="Lightning Flash" size="big" disableText/> | A teleport with a range of 900 units. Very important skill for certain skips, especially in combination with <Item name="White Mantle Portal Device"/>, useful in fractals like Cliffside, Aetherblade and Underground Facility. |
| <Skill name="Eye of the Storm" size="big" disableText/> | Grants <Effect name="superspeed"/>, useful for skips especially in combination with <Item name="Executioner Axe Toy"/> or <Item name="Endless Choya Pinata Tonic"/>. |
| <Skill name="Signet of Fire" size="big" disableText/> | If you don't reach 100% critical chance and are too lazy to get Assassin's pieces, take this instead of <Skill name="Arcane Blast"/>. |
</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="Glyph of Elemental Harmony" utility1="Conjure Lightning Hammer" utility2="Glyph of Storms" utility3="Arcane Blast" elite="Conjure Fiery Greatsword"/>
<Card title="Note about Druid">
The builds are without <Specialization name="Druid"/> since the Glyph of Empowerment skill got removed from the game. <Specialization name="Druid"/> no longer grants damage boost aside from <Skill name="Frost Spirit"/> (<Specialization name="Soulbeast"/> can take that), thus making the Renegade/Firebrand comp even more dominant.

You can still use the [Gear Optimizer](http://old.discretize.eu) if you still play with druid.
</Card>
<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait name="Gale Song" size="big" disableText/> | Useful automatic group stunbreak for things like <Instability name="Last Laugh"/> or bosses like MAMA. |
| <Trait name="Aeromancers Training" size="big" disableText/> | If you can't profit from <Trait name="Stormsoul"/> (e.g. Artsariiv). |
| <Trait name="One with Air" size="big" disableText/> | Useful for skipping with <Effect name="superspeed"/>, especially in combination with <Item name="Executioner Axe Toy"/> or <Item name="Endless Choya Pinata Tonic"/>. |
</Card>
<Card title="Defiance Bar Damage">
| | |
| -- | -- |
| <Skill name="Shocking Aura" size="big" disableText/> | 100 with <Control name="stun"/> |
| <Skill name="Cyclone" size="big" disableText/> | 150 with <Control name="pull"/> |
| <Skill name="Blinding Flash" size="big" disableText/> | 20 / s with <Condition name="blind"/> |
| <Skill name="Wind Blast" size="big" disableText/> | 232 with <Control name="launch"/> |
| <Skill name="Dust Storm" size="big" disableText/> | 20 / s with <Condition name="blind"/> |
| <Skill name="Tidal Surge" size="big" disableText/> | 150 with <Control name="knockback"/> |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="6">
<Card title="Skill Priority">
Your entire rotation revolves around using <Skill name="Overload Air"/> as often as possible.

Apart from that, you have the following modifiers:

- <Trait id="1839"/>: 7% damage and condi damage for 7 seconds after <Skill name="Overload Air"/>
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
   2. <Skill name="Lightning Swing"/> => <Skill name="Static Swing"/> => <Skill name="Thunderclap" profession="bundle"/>
2. <Skill name="Conjure Fiery Greatsword"/>
   1. <Skill name="Fiery Rush"/>
   2. <Skill name="Firestorm" profession="bundle"/>
   3. <Skill name="Fiery Whirl"/> (if you can whirl against a wall or have to switch targets)

And lastly, you should use <Skill name="Lightning Strike"/> (instant cast) off recharge and <Skill name="Heat Sync"/> whenever <Boon name="might"/> is low on the group.
</Card>
</GridItem>

<GridItem sm="6">
<Card title="Opener">
1. If a Mistlock Singularity is present
   1. <Skill name="Conjure Fiery Greatsword"/> and reset its cooldown with it
2. <Skill name="Air Attunement"/>
   1. Precast <Skill name="Overload Air"/> so it finishes when the fight starts
   2. <Skill name="Firestorm" profession="bundle"/> (if you have a <Skill name="Conjure Fiery Greatsword" disableText/>)
   3. <Skill name="Lightning Orb"/> (from range, ideally it should pass through the mob when the defiance bar is broken)
   4. <Skill name="Lightning Storm"/>
3. <Skill name="Fire Attunement"/>
   1. <Skill name="Wildfire"/>
   2. <Skill name="Phoenix"/>
   3. <Skill name="Dragons Tooth"/>
4. <Skill name="Earth Attunement"/> (only on huge hitboxes)
   1. <Skill name="Dust Storm"/>
5. <Skill name="Air Attunement"/>
   1. <Skill name="Conjure Lightning Hammer"/>
   2. <Skill name="Invoke Lightning"/> (inside the target's hitbox)
   3. <Skill name="Lightning Swing"/> => <Skill name="Static Swing"/> => <Skill name="Thunderclap" profession="bundle"/> and 3x <Skill name="Arcane Blast">
   4. <Skill name="Overload Air"/>
6. <Skill name="Fire Attunement"/>
   1. <Skill name="Dragons Tooth"/>
7. <Skill name="Air Attunement"/>
   1. <Skill name="Conjure Fiery Greatsword">
   2. <Skill name="Fiery Rush"/>
   3. <Skill name="Firestorm" profession="bundle"/>
   4. <Skill name="Lightning Orb"/>
   5. <Skill name="Overload Air"/>

</Card>

<Card title="Advanced Notes">
* Always cast <Skill name="Lightning Orb"/> from as far as possible
* Try to place the outer ring of <Skill name="Overload Air"/> directly on the target and make sure the cast actually finishes
* Cast <Skill name="Invoke Lightning"/> while standing inside the target's hitbox to make sure all strikes hit
* Remember to already switch to the next attunement *while* casting skills
* <Skill name="Arc Lightning"/> (your <Skill name="Air Attunement"/> auto-attack) deals more damage the longer you channel it, but every other skill has a higher priority
</Card>
</GridItem>
</Grid>
