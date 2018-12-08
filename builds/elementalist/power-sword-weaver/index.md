---
title: 'Power Sword Weaver'
date: '2018-11-18'
rating: 'Meta'
role: 'Damage'
profession: 'Elementalist'
specialization: 'Weaver'
benchmark:
  {
    large: { dps: 38120, by: 'Fallen [SC]', youtube: '6oRoJ72CNqI' },
    small: { dps: 36644, by: 'Derpy Moa [SC]', youtube: 'yxeQA63tUtw' },
  }
skills: [5536]
traits: [1502]
conditions: ['Weakness', 'Vulnerability']
---

The <Specialization name="Weaver" text="Power Sword Weaver"/> is currently one of the strongest DPS builds for fractals.

It has quick burst damage and doesn't rely as much on pre-casting as [Power Staff Weaver](/builds/elementalist/power-staff-weaver) or [Power Tempest](/builds/elementalist/power-tempest). Since you don't have long casting times and the rotation loops fluently, it is fun to play as long as there are no Instabilities that discourage melee interactions.

Aside from <Condition name="vulnerability"/>, an additional crowd control skill with <Skill name="Updraft"/> and high DPS the Power Sword Weaver build unfortunately doesn't provide much utilities. Additionally, the missing Arcane traits such as <Trait name="Final Shielding"/> make you inherently squishy.

The build benefits heavily from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>

<Grid>
<GridItem sm="4">
<Armor weight="Light" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Berserker" shouldersRune="Scholar" coatAffix="Berserker" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Berserker" weapon1MainSigil1="Impact" weapon1OffType="Dagger" weapon1OffAffix="Berserker" weapon1OffSigil="Force"/>

<Card title="Swap Weapons">
* Sword with <Item name="Night" type="Sigil"/>
* Dagger with <Item name="Serpent Slaying" type="Sigil"/>
* Swords with slaying sigils (see [Consumables Guide](/guides/consumables))
* A scepter for <Skill name="Dragons Tooth"/> and <Skill name="Phoenix"/> to stack <Boon name="might"/>
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Berserker" accessory2Affix="Berserker" amuletAffix="Berserker" ring1Affix="Berserker" ring2Affix="Berserker"/>

<Consumables food="Bowl of Sweet and Spicy Butternut Squash Soup" utility="Tin of Fruitcake" infusion="Mighty +9 Agony Infusion"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Fire" traits1Selected="Burning Precision, Pyromancers Training, Persisting Flames" traits2="Air" traits2Selected="Ferocious Winds, Tempest Defense, Bolt to the Heart" traits3="Weaver" traits3Selected="Superior Elements, Swift Revenge, Elements of Rage"/>

<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait name="Masters Fortitude" size="big" disableText/> | With <Trait name="Spotter"/> or more than 200 agony resistance you are crit capped without <Trait name="Superior Elements"/>, then you can take this trait for extra survivability. |
| <Trait name="Fresh Air" size="big" disableText/> | With low group DPS and long phases this might pull ahead of <Trait name="Bolt to the Heart"/>. |
| <Trait name="Aeromancers Training" size="big" disableText/> | If you can't profit from <Trait name="Tempest Defense"/> (e.g. Artsariiv). |
| <Trait name="One with Air" size="big" disableText/> | Useful for skipping with <Effect name="superspeed"/>, especially in combination with <Item name="Executioner Axe Toy"/>. |
| <Trait name="Inscription" size="big" disableText/> | Niche trait to reduce the cooldown of <Skill name="Glyph of Storms"/>. |
</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="Glyph of Elemental Harmony" utility1="Conjure Lightning Hammer" utility2="Glyph of Storms" utility3="Arcane Blast" elite="Conjure Fiery Greatsword"/>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill name="Arcane Wave" size="big" disableText/> | Deals the same damage as <Skill name="Arcane Blast"/> but on multiple foes. Also useful to generate <Boon name="might"/> with a fire field. |
| <Skill name="Primordial Stance" size="big" disableText/> | On small hitboxes and fights with a lot of phasing (e.g. Arkk) <Skill name="Conjure Lightning Hammer"/> isn't that valuable so you can use this instead. |
| <Skill name="Unravel" size="big" disableText/> | Can be used to get quicker into <Skill name="Fire Attunement" disableText/>/<Skill name="Fire Attunement" disableText/> for very short-phased fights. |
| <Skill name="Conjure Frostbow" size="big" disableText/> | Faster burst than <Skill name="Conjure Lightning Hammer"/> on large hitboxes with the bonus of being semi-ranged. |
| <Skill name="Lightning Flash" size="big" disableText/> | A teleport with a range of 900 units. Sufficient for most blink spots. |
| <Skill name="Arcane Brilliance" size="big" disableText/> | Sometimes used to blast <Boon name="might"/> in fights like Skorvald. |
| <Skill name="Glyph of Elementals" size="big" disableText/> | If you can't benefit from <Skill name="Conjure Fiery Greatsword"/>. |
| <Skill name="Aquatic Stance" size="big" disableText/> | An alternative heal skill providing additional group heal. |
| <Skill name="Arcane Shield" size="big" disableText/> | Provides three blocks for things like the console in [Underground Facility Fractal](/fractals/underground-facility). |
| <Skill name="Armor of Earth" size="big" disableText/> | Another defensive utility skill granting <Boon name="protection"/> and <Boon name="stability"/>. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation (Bolt to the Heart)">
The general idea is to loop between <Skill name="Air Attunement" disableText/>/<Skill name="Air Attunement" disableText/> and <Skill name="Fire Attunement" disableText/>/<Skill name="Fire Attunement" disableText/> using your strongest skills like <Skill name="Invoke Lightning"/> in Fire with <Trait name="Elements of Rage"/> up.

<Grid>
<GridItem sm="2">
<Skill name="Air Attunement" size="large" disableText/> <Skill name="Air Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="10">
1. <Skill name="Lightning Storm"/>
2. <Skill name="Quantum Strike"/>
</GridItem>

<GridItem sm="2">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Air Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="10">
1. <Skill name="Pyro Vortex"/>
2. <Skill name="Ride the Lightning"/>
3. <Skill name="Flame Uprising"/>
4. <Skill name="Conjure Lightning Hammer"/>
</GridItem>

<GridItem sm="2">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="10">
1. <Skill name="Invoke Lightning"/>
2. <Skill name="Cauterizing Strike"/>
3. <Skill name="Fire Grab"/>
4. <Skill name="Flame Uprising"/>
</GridItem>

<GridItem sm="2">
<Skill name="Air Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="10">
1. <Skill name="Ring of Fire"/>
2. <Skill name="Charged Strike"/> => <Skill name="Polaric Slash"/> => <Skill name="Call Lightning" profession="elementalist"/>
3. <Skill name="Charged Strike"/> => <Skill name="Polaric Slash"/> => <Skill name="Call Lightning" profession="elementalist"/>
</GridItem>

<GridItem sm="2">
<Skill name="Air Attunement" size="large" disableText/> <Skill name="Air Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="10">
1. <Skill name="Charged Strike"/> => <Skill name="Polaric Slash"/> => <Skill name="Call Lightning" profession="elementalist"/>
3. <Skill name="Quantum Strike"/>
</GridItem>

<GridItem sm="2">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Air Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="10">
1. <Skill name="Pyro Vortex"/>
2. <Skill name="Ride the Lightning"/>
3. <Skill name="Flame Uprising"/>
4. <Skill name="Conjure Fiery Greatsword"/>
</GridItem>

<GridItem sm="2">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="10">
1. <Skill name="Fiery Rush"/>
2. <Skill name="Firestorm" profession="bundle"/>
3. <Skill name="Cauterizing Strike"/>
4. <Skill name="Ring of Fire"/>
5. <Skill name="Fire Strike"/> => <Skill name="Fire Swipe"/> => <Skill name="Searing Slash"/>
6. <Skill name="Flame Uprising"/>
</GridItem>

<GridItem sm="2">
<Skill name="Air Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="10">
1. <Skill name="Charged Strike"/> => <Skill name="Polaric Slash"/> => <Skill name="Call Lightning" profession="elementalist"/>
2. <Skill name="Fire Grab"/>
3. <Skill name="Charged Strike"/> => <Skill name="Polaric Slash"/> => <Skill name="Call Lightning" profession="elementalist"/>
</GridItem>
</Grid>

With <Trait name="Fresh Air"/>, you do one <Skill name="Twin Strike"/> in <Skill name="Water Attunement" disableText/> before going directly into <Skill name="Air Attunement" disableText/>/<Skill name="Air Attunement" disableText/> after using your Fire skills.
</Card>
</GridItem>

<GridItem sm="5">
<Card title="Opener">
- If a Mistlock Singularity is present
   - <Skill name="Conjure Fiery Greatsword"/> and reset its cooldown with it
   - Precast <Skill name="Firestorm" profession="bundle"/>
- If the defiance bar won't be broken immediately (e.g. Ensolyss)
   - Start in <Skill name="Fire Attunement" disableText/> <Skill name="Earth Attunement" disableText/>
   - <Skill name="Flame Uprising"/> and <Skill name="Lava Skin"/>
   - Attune to <Skill name="Air Attunement" disableText/> <Skill name="Air Attunement" disableText/> and delay until the bar is about to be broken
   - Continue with the usual rotation

</Card>

<Card title="Advanced Notes">
- Try to finish your auto-attack chains (<Skill name="Fire Attunement" disableText/>/<Skill name="Searing Slash" disableText/> and <Skill name="Air Attunement" disableText/>/<Skill name="Call Lightning" profession="elementalist" disableText/>)
- Use <Skill name="Arcane Blast"/> when the target's defiance bar is broken and you have <Trait name="Elements of Rage"/> and <Skill name="Conjure Lightning Hammer"/> up
- On small hitboxes <Skill name="Firestorm"/> is better than <Skill name="Lightning Storm"/>, use it while attuning to <Skill name="Fire Attunement" disableText/> <Skill name="Fire Attunement" disableText/>

</Card>

<Card title="Defiance Bar Damage">
| | |
| -- | -- |
| <Skill name="Updraft" size="big" disableText/> | 332 with <Control name="launch"/> |
| <Skill name="Wind Blast" size="big" disableText/> | 232 with <Control name="launch"/> |
| <Skill name="Polaric Leap" size="big" disableText/> | 100 with <Control name="daze"/> |
</Card>

<Video youtube="6oRoJ72CNqI" title="Huge Hitbox: 38.1k DPS by Fallen [SC]"/>
</GridItem>
</Grid>
