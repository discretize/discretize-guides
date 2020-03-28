---
title: 'Power Holosmith'
date: '2020-03-28'
rating: 'Offmeta'
role: 'Damage'
profession: 'Engineer'
specialization: 'Holosmith'
benchmark: { small: { dps: 38143, by: 'TJ [SC]', youtube: 'p6mZtHhu7GM' } }
skills: [30815, 43739]
conditions: ['Vulnerability', 'Blind', 'Crippled', 'Immobile']
effects: ['Stealth']
code: '[&DQMGOyYfOSsqDyoPowCGAIYAowBXFlcW8BWJAQAAAAAAAAAAAAAAAAAAAAA=]'
---

The engineer build that currently fares best in fractals is the <Specialization text="Power Holosmith" name="holosmith"/>, offering a mix of high damage and a relatively good amount of crowd control and utility in form of <Condition name="vulnerability"/> and some <Condition name="Blind"/>, <Condition name="Crippled"/> and <Condition name="Immobile"/>.

The build benefits from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.


<Tabs>
<Tab title="Build">
<Divider text="Equipment"/>
Check the [gear optimizer](http://old.discretize.eu) for more gear variants!
<Grid>
<GridItem sm="4">
<Armor weight="Medium" helmId="48087" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48089" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48085" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48086" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48088" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48084" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Berserker"  weapon1MainSigil1="Force" weapon1OffSigil="Impact" weapon1OffType="Pistol" weapon1OffAffix="Berserker"/>

<Card title="Alternative weapons">
* Rifle with <Item id="36053" disableText/> / <Item id="24615" disableText/> and slaying sigils  
* Swords with slaying sigils.
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemId="49390" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="67530" infusionId="37131"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="38" traits1="Firearms" traits1SelectedIds="1914,1923,526" traits2Id="6" traits2="Explosives" traits2SelectedIds="1882,1892,1947" traits3Id="57" traits3="Holosmith" traits3SelectedIds="2106,2152,2137"/>

<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait name="Sanguine Array" size="big" disableText/> | If you are already crit capped without <Trait name="High Caliber"/> and struggle with <Boon name="Might"/> uptime. |
You can swap Firearms traitline with Tools and replace <Skill id="5805"/> on <Skill id="43739"/>. This will help you to maintain your <Boon name="Quickness"/> better. Especially in weaker groups this build shines. It is pretty friendly for new players. 
</Card>
<Traits traits1Id="21" traits1="Tools" traits1SelectedIds="532,517,1856"/>
</GridItem>

<GridItem sm="5">
<Skills healId="21659" utility1Id="5818" utility2Id="6020" utility3Id="42842" eliteId="42009"/>

<Card title="Additional Skills">
| | |
| -- | -- |
| Toolbelt | <Skill id="21661" size="big" disableText/><Skill id="6178" size="big" disableText/><Skill id="6172" size="big" disableText/><Skill id="42163" size="big" disableText/> |
| <Skill id="6020" size="big" disableText/> |<Skill id="5806" size="big" disableText/><Skill id="5807" size="big" disableText/><Skill id="5808" size="big" disableText/><Skill id="5809" size="big" disableText/><Skill id="5810" size="big" disableText/> |
</Card>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill id="5977" size="big" disableText/> | You can equip <Skill id="5927"/> shortly before the fight and precast its toolbelt skill if you want to go the extra mile. |
| <Skill id="5857" size="big" disableText/> | An alternative heal skill if condition cleanse is needed, you can cast it AFTER (cause of water field) firefield to blast might. |
| <Skill id="43739" size="big" disableText/> | Another (group) block that even reflects projectiles if heat is above 50. (replace it with <Skill id="6020"/>)  |
| <Skill id="30337" size="big" disableText/> | Good alternative for burst, replace it with <Skill id="5818"/>, you can stack multiple times <Skill id="6164"/> before the start. |
</Card>
</GridItem>
</Grid>
</Tab>

<Tab title="Guide">

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation">
1. **Preheat to 90%**
2. <Skill name="Laser Disk" profession="Engineer"/>
3. <Skill name="engage Photon Forge" profession="Engineer"/>
4. <Skill name="Prime light beam" profession="Engineer"/> (To help with CCing)
5. <Skill name="Grenade Barrage" profession="Engineer"/>
6. <Skill name="Corona Burst" profession="Engineer"/>
7. <Skill name="Photon Blitz" profession="Engineer"/>
8. <Skill name="Light Strike" profession="Engineer"/>
    9. <Skill name="Bright Slash" profession="Engineer"/>
    10. <Skill name="Flash Cutter" profession="Engineer"/>
    11. x2
12. <Skill name="Corona Burst" profession="Engineer"/>
11. <Skill name="Deactivate Photon Forge" profession="Engineer"/>
12. <Skill name="Refraction Cutter" profession="Engineer"/>
13. <Skill name="Shrapnel Grenade" profession="Engineer"/>
    14. <Skill name="Poison Grenade" profession="Engineer"/>
15. <Skill name="Sun Edge" profession="Engineer"/>
    16. <Skill name="Sun Ripper" profession="Engineer"/>
    17. <Skill name="Gleam Saber" profession="Engineer"/>
    18. x2
19. <Skill name="Refraction Cutter" profession="Engineer"/>
20. <Skill name="Shrapnel Grenade" profession="Engineer"/>
21. <Skill name="Sun Edge" profession="Engineer"/>
    22. <Skill name="Sun Ripper" profession="Engineer"/>
    23. <Skill name="Gleam Saber" profession="Engineer"/>
    24. x2
25. <Skill name="Refraction Cutter" profession="Engineer"/>
    26. <Skill name="Blowtorch" profession="Engineer"/>
27. <Skill name="Shrapnel Grenade" profession="Engineer"/>
28. <Skill name="engage Photon Forge" profession="Engineer"/> (your heat should be around 90%)
29. Repeat from step 4 
</Card>
</GridItem>

<GridItem sm="5">
<Card title="Notes and Tips">
* Don't interrupt your auto attack chain in Photon Forge
* Keep in mind that <Trait id="2106"/> consumes its charges while <Trait id="2122"/> is a duration buff.
* Use <Skill id="42842"/> and <Skill id="42009"/> off cooldown.
* Use <Skill id="6178"/> and <Skill id="42163"/> off cooldown.
* Make use of <Skill id="5808"/> to mitigate damage in add heavy fights.
* <Skill id="5830"/> can help in controlling movement of enemies without breakbar. 
* Never <Skill id="44386"/>, always try to <Skill id="41123"/> at 149 heat.

You can switch to <Specialization name="scrapper"/> and equip <Skill id="30815"/> if you need <Effect name="stealth"/> for longer passages (e.g. [Twilight Oasis Fractal](https://discretize.eu/fractals/twilight-oasis)). It provides >40 seconds for the whole group. A smoke field can also be provided by <Skill id="5824"/> to blast <Effect name="stealth"/>.
</Card>

<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="42009"/> | 232 damage |
| <Skill id="42521"/> | 232 damage |
| <Skill id="21661"/> | 100 damage |
</Card>

</GridItem>

</Grid>
</Tab>
</Tabs>
