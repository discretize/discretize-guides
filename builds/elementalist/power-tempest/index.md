---
title: 'Power Tempest'
date: '2018-12-11'
rating: 'Meta'
role: 'Damage'
profession: 'Elementalist'
specialization: 'Tempest'
benchmark: { huge: { dps: 36439, by: 'Roul [SC]', youtube: '7iChM4gEXqE' } }
skills: [5536, 29719, 30432]
traits: [264, 1502, 1952, 1839, 1986, 2033]
boons: ['Might', 'Fury', 'Swiftness', 'Protection', 'Vigor']
conditions: ['Weakness', 'Vulnerability', 'Blind']
---

The <Specialization name="Tempest" text="Power Tempest"/> is a strong DPS variant for fractals with various utilities the <Specialization name="weaver"/> counterpart doesn't offer.

It has very high burst damage in fast-paced fights and its overall DPS is only contested by the [Sword Weaver](/builds/elementalist/power-sword-weaver) and [Staff Weaver](/builds/elementalist/power-staff-weaver) on huge hitboxes.  
Thanks to <Skill name="Overload Air"/> the group's damage is buffed by around 1k DPS, so at least one <Specialization name="Tempest"/> is never a bad idea when thinking about group composition.

Apart from great DPS, the build afflicts tons of <Condition name="vulnerability"/> and helps keeping up <Boon name="might"/> with <Trait name="Elemental Attunement"/> and <Skill name="Heat Sync"/>. Another bonus is the extended boon duration from <Trait name="Imbued Melodies"/> on the entire party making the life of your <Specialization name="Chronomancer"/> a little bit easier.

For projectile-heavy scenarios <Skill name="Aftershock"/> and <Skill name="Sand Squall"/> can be used, <Skill name="Shocking Aura"/> and <Skill name="Cyclone"/> help against trash mobs and defiance bars.

Contrary to the [Sword Weaver](/builds/elementalist/power-sword-weaver), melee hate like <Instability name="Social Awkwardness"/> or disruptions like <Instability name="Last Laugh"/> don't matter that much since you can stand on range and have access to a multitude of defensive mechanics like <Boon name="stability"/>, <Trait name="Gale Song"/> and <Trait name="Final Shielding"/>.

The degree of difficulty is a little bit higher than the other <Specialization name="Elementalist"/> builds as you need to adhere many small things to achieve top numbers.  
The positiong and timing of skills matter a lot, a single mistake can make your DPS end up several thousands below other damage dealers.

The build benefits heavily from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>

<Tabs outlined>
<Tab title="150 Agony Resistance (No Spotter)">
<Grid>
<GridItem sm="4">
<Armor weight="Light" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Assassin" shouldersRune="Scholar" coatAffix="Assassin" coatRune="Scholar" glovesAffix="Assassin" glovesRune="Scholar" leggingsAffix="Assassin" leggingsRune="Scholar" bootsAffix="Assassin" bootsRune="Scholar"/>
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
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Assassin" accessory2Affix="Assassin" amuletAffix="Berserker" ring1Affix="Assassin" ring2Affix="Berserker"/>

<Consumables food="Bowl of Sweet and Spicy Butternut Squash Soup" utility="Tin of Fruitcake" infusion="Mighty +9 Agony Infusion"/>
</GridItem>
</Grid>
</Tab>

<Tab title="207 Agony Resistance (No Spotter)">
<Grid>
<GridItem sm="4">
<Armor weight="Light" helmAffix="Assassin" helmRune="Scholar" shouldersAffix="Assassin" shouldersRune="Scholar" coatAffix="Assassin" coatRune="Scholar" glovesAffix="Assassin" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Assassin" bootsRune="Scholar"/>
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
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Assassin" accessory2Affix="Berserker" amuletAffix="Berserker" ring1Affix="Berserker" ring2Affix="Berserker"/>

<Consumables food="Bowl of Sweet and Spicy Butternut Squash Soup" utility="Tin of Fruitcake" infusion="Mighty +9 Agony Infusion"/>
</GridItem>
</Grid>
</Tab>
</Tabs>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Arcane" traits1Selected="Arcane Precision, Final Shielding, Bountiful Power" traits2="Air" traits2Selected="Ferocious Winds, Tempest Defense, Fresh Air" traits3="Tempest" traits3Selected="Unstable Conduit, Harmonious Conduit, Imbued Melodies"/>

<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait name="Gale Song" size="big" disableText/> | Useful automatic group stunbreak for things like <Instability name="Last Laugh"/> or bosses like MAMA. |
| <Trait name="Elemental Bastion" size="big" disableText/> | Another defensive option instead of <Trait name="Imbued Melodies"/> when heals and damage reduction are more valuable than reflects and longer boons. Combine it with <Trait name="Unstable Conduit"/> if possible. |
| <Trait name="Aeromancers Training" size="big" disableText/> | If you can't profit from <Trait name="Tempest Defense"/> (e.g. Artsariiv). |
| <Trait name="Renewing Stamina" size="big" disableText/> | If you don't get enough <Boon name="vigor"/> from your <Specialization name="chronomancer"/>. |
| <Trait name="Elemental Contingency" size="big" disableText/> | If you don't get enough <Boon name="retaliation"/> from your <Specialization name="chronomancer"/>. |
| <Trait name="Lucid Singularity" size="big" disableText/> | Counters movement-impairing conditions while overloading, useful in scenarios like the <Condition name="Immobile"/> on interact with the consoles in [Aetherblade Fractal](/fractals/aetherblade). |
| <Trait name="One with Air" size="big" disableText/> | Useful for skipping with <Effect name="superspeed"/>, especially in combination with <Item name="Executioner Axe Toy"/>. |
</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="Glyph of Elemental Harmony" utility1="Conjure Lightning Hammer" utility2="Glyph of Storms" utility3="Arcane Blast" elite="Conjure Fiery Greatsword"/>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill name="Signet of Fire" size="big" disableText/> | If you don't reach 100% critical chance and are too lazy to get Assassin's pieces, take this instead of <Skill name="Arcane Blast"/>. |
| <Skill name="Aftershock" size="big" disableText/> | A group-wide reflect aura lasting for 4 seconds. |
| <Skill name="Arcane Wave" size="big" disableText/> | Deals the same damage as <Skill name="Arcane Blast"/> but on multiple foes. Also useful to generate <Boon name="might"/> with a fire field. |
| <Skill name="Conjure Frostbow" size="big" disableText/> | Faster burst than <Skill name="Conjure Lightning Hammer"/> on large hitboxes with the bonus of being semi-ranged. |
| <Skill name="Lightning Flash" size="big" disableText/> | A teleport with a range of 900 units. Sufficient for most blink spots. |
| <Skill name="Arcane Brilliance" size="big" disableText/> | Sometimes used to blast <Boon name="might"/> in fights like Skorvald. |
| <Skill name="Glyph of Elementals" size="big" disableText/> | If you can't benefit from <Skill name="Conjure Fiery Greatsword"/>. |
| <Skill name="Rebound" size="big" disableText/> | Prevents otherwise deathly mechanics for the entire group, like Corporal Reassignment (Doomed) at Artsariiv or Arkk. |
| <Skill name="Wash the pain away" size="big" disableText/> | An alternative heal skill affecting allies close-by. |
| <Skill name="Arcane Shield" size="big" disableText/> | Provides three blocks for things like the console in [Underground Facility Fractal](/fractals/underground-facility). |
| <Skill name="Armor of Earth" size="big" disableText/> | Another defensive utility skill granting <Boon name="protection"/> and <Boon name="stability"/>. |
| <Skill name="Eye of the Storm" size="big" disableText/> | Grants <Effect name="superspeed"/>, useful for skips especially in combination with <Item name="Executioner Axe Toy"/> or <Item name="Endless Choya Pinata Tonic"/>. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="6">
<Card title="Skill Priority">
Your entire rotation revolves around using <Skill name="Overload Air"/> as often as possible.

Apart from that, you have the following modifiers:

- <Trait name="Harmonious Conduit"/>: 10% damage increase for 4 seconds after <Skill name="Overload Air"/> finishes
- <Trait name="Fresh Air"/>: 250 ferocity for 5 seconds after attuning to air
- <Trait name="Tempest Defense"/> and <Item name="Impact" type="Sigil"/> when the target's defiance bar is broken
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

<Video youtube="7iChM4gEXqE" title="Huge Hitbox: 36.4k DPS by Roul [SC]"/>
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
* Always cast <Skill name="Lightning Orb"/> from as far as possible but don't miss group buffs like <Skill name="Well of Action"/>
* Try to place the outer ring of <Skill name="Overload Air"/> directly on the target and make sure the cast actually finishes
* Cast <Skill name="Invoke Lightning"/> while standing inside the target's hitbox to make sure all strikes hit
* Remember to already switch to the next attunement *while* casting skills
* <Skill name="Arc Lightning"/> (your <Skill name="Air Attunement"/> auto-attack) deals more damage the longer you channel it, but every other skill has a higher priority
</Card>

<Card title="Defiance Bar Damage">
| | |
| -- | -- |
| <Skill name="Shocking Aura" size="big" disableText/> | 100 per hit with <Control name="stun"/> |
| <Skill name="Cyclone" size="big" disableText/> | 150 with <Control name="pull"/> |
| <Skill name="Blinding Flash" size="big" disableText/> | 20 per second with <Condition name="blind"/> |
| <Skill name="Wind Blast" size="big" disableText/> | 232 with <Control name="launch"/> |
| <Skill name="Dust Storm" size="big" disableText/> | 20 per second with <Condition name="blind"/> |
| <Skill name="Tidal Surge" size="big" disableText/> | 150 with <Control name="knockback"/> |
</Card>
</GridItem>
</Grid>
