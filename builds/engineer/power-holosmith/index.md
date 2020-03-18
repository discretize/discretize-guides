---
title: 'Power Holosmith'
date: '2019-09-04'
rating: 'Offmeta'
role: 'Damage'
profession: 'Engineer'
specialization: 'Holosmith'
benchmark: { small: { dps: 34170, by: 'Sony [SC]', youtube: 'jDnK-Im9Hg8' } }
skills: [30815, 43739]
traits: [517]
conditions: ['Vulnerability', 'Blind', 'Crippled', 'Immobile']
effects: ['Stealth']
code: '[&DQMmLwYbOTtVFhQBhgCjAAcBLxZXFuUW8BUSAQAAAAAAAAAAAAAAAAAAAAA=]'
---

The engineer build that currently fares best in fractals is the <Specialization text="Power Holosmith" name="holosmith"/>, offering a mix of high damage and a relatively good amount of crowd control and utility in form of <Condition name="vulnerability"/> and some <Condition name="Blind"/>, <Condition name="Crippled"/> and <Condition name="Immobile"/>.

The build benefits from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>
Check the [gear optimizer](http://old.discretize.eu) for more gear variants!e
<Grid>
<GridItem sm="4">
<Armor weight="Medium" helmId="48087" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48089" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48085" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48086" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48088" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48084" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainId="46768" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24868" weapon1MainType="Rifle" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact"/>

<Card title="Alternative weapons">
* Rifle with <Item id="36053" disableText/> / <Item id="24615" disableText/> and slaying sigils  
  (<Item id="36054"/> doesn't stack anymore)
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
<Traits traits1Id="38" traits1="Firearms" traits1SelectedIds="1914,1923,526" traits2Id="6" traits2="Explosives" traits2SelectedIds="1882,1892,1541" traits3Id="57" traits3="Holosmith" traits3SelectedIds="2106,2152,2064"/>

<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait id="1923" size="big" disableText/> | If you are lacking fury, consider using it instead of <Trait id="2006"/>. |
| <Trait id="505" size="big" disableText/> | On longer fights without adds, this may pull slightly ahead of <Trait id="1541"/>. |
| <Trait name="Sanguine Array" size="big" disableText/> | If you are already at crit cap without <Trait name="High Caliber"/> and struggle with <Boon name="Might"/> uptime. |
</Card>
</GridItem>

<GridItem sm="5">
<Skills healId="40507" utility1Id="5812" utility2Id="6020" utility3Id="42842" eliteId="42009"/>

<Card title="Additional Skills">
| | |
| -- | -- |
| Toolbelt | <Skill id="43845" size="big" disableText/><Skill id="5813" size="big" disableText/><Skill id="6172" size="big" disableText/><Skill id="42163" size="big" disableText/> |
| <Skill id="5812" size="big" disableText/> |<Skill id="5842" size="big" disableText/><Skill id="5823" size="big" disableText/><Skill id="5822" size="big" disableText/><Skill id="5824" size="big" disableText/><Skill id="5939" size="big" disableText/> |
| <Skill id="6020" size="big" disableText/> |<Skill id="5806" size="big" disableText/><Skill id="5807" size="big" disableText/><Skill id="5808" size="big" disableText/><Skill id="5809" size="big" disableText/><Skill id="5810" size="big" disableText/> |
</Card>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill id="5977" size="big" disableText/> | You can equip <Skill id="5927"/> shortly before the fight and precast its toolbelt skill if you want to go the extra mile. |
| <Skill id="5857" size="big" disableText/> | An alternative heal skill if condition cleanse is needed. |
| <Skill id="21659" size="big" disableText/> | Provides additional CC with the toolbelt skill <Skill id="21661"/>. |
| <Skill id="43739" size="big" disableText/> | Another (group) block that even reflects projectiles if heat is above 50. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation">
1. **Preheat to 75**
2. <Skill name="Big Ol Bomb" profession="Engineer"/> (Tool belt)
3. <Skill id="5823" profession="Engineer"/> (Bomb kit 2)
4. <Skill name="Shrapnel Grenade" profession="Engineer"/> (Grenade kit 2)
5. <Skill name="Grenade Barrage" profession="Engineer"/> (Tool belt)
6. <Skill name="Engage Photon Forge" profession="Engineer"/> (F5)
    7. <Skill name="Corona Burst" profession="Engineer"/> (Skill 1)
    8. <Skill name="Photon Blitz" profession="Engineer"/> (Skill 4)
    9. <Skill id="43937" profession="Engineer"/>
10. <Skill name="Laser Disk" profession="Engineer"/> (Utility)
11. <Skill name="Prime Light Beam" profession="Engineer"/> (Elite)
12. <Skill name="Overcharged Shot" profession="Engineer"/> (Rifle 4, **Repeat from here**)
13. <Skill name="Jump Shot" profession="Engineer"/>(Rifle 5)
14. <Skill name="Blunderbuss" profession="Engineer"/> (Rifle 3)
15. <Skill name="Shrapnel Grenade" profession="Engineer"/> (Grenade kit 2)
16. <Skill id="5823" profession="Engineer"/> (Bomb kit 2)
    17. <Skill id="5842" profession="Engineer"/> until <Skill id="5823" profession="Engineer"/> is on 5s (Bomb kit 1)
18. <Skill name="Shrapnel Grenade" profession="Engineer"/> (Grenade kit 2)
19. <Skill name="Poison Grenade" profession="Engineer"/> (Grenade kit 5)
20. <Skill name="Freeze Grenade" profession="Engineer"/> (Grenade kit 4)
21. <Skill id="5842" profession="Engineer"/> until <Skill id="5823" profession="Engineer"/> is ready (Bomb kit 1)
22. <Skill name="Blunderbuss" profession="Engineer"/> (Rifle 3)
23. <Skill name="Shrapnel Grenade" profession="Engineer"/> (Grenade kit 2)
24. <Skill id="5823" profession="Engineer"/> (Bomb kit 2)
    25. <Skill id="5842" profession="Engineer"/> until <Skill name="Engage Photon Forge" profession="Engineer"/> is ready (Bomb kit 1)
26. <Skill name="Engage Photon Forge" profession="Engineer"/> (F5)
    27. <Skill name="Corona Burst" profession="Engineer"/> (Skill 3)
    28. <Skill name="Photon Blitz" profession="Engineer"/> (Skill 4)
    29. **Autoattack chain** until <Skill name="Corona Burst" profession="Engineer"/> is ready
    30. <Skill name="Corona Burst" profession="Engineer"/> (Skill 3)
    31. <Skill name="Deactivate Photon Forge" profession="Engineer"/> (F5)
32. <Skill name="Shrapnel Grenade" profession="Engineer"/>(Grenade kit 2)
33. <Skill name="Blunderbuss" profession="Engineer"/> (Rifle 3)
34. <Skill id="5823" profession="Engineer"/> (Bomb kit 2)
35. <Skill name="Engage Photon Forge" profession="Engineer"/> (F5)
    37. **Autoattack chain** until <Skill name="Corona Burst" profession="Engineer" disableText/> and <Skill name="Photon Blitz" profession="Engineer" disableText/> are ready
    38. <Skill name="Corona Burst " profession="Engineer"/>(Skill 3)
    39. <Skill name="Photon Blitz" profession="Engineer"/> (Skill 4)
    40. <Skill id="43937" profession="Engineer"/>
41. <Skill name="Laser Disk " profession="Engineer"/> (Utility)
42. <Skill name="Prime Light Beam" profession="Engineer"/> (Elite)
43. **Repeat from** `Step 9`
</Card>
</GridItem>

<GridItem sm="5">
<Card title="Notes and tips">
* Don't interrupt your auto attack chain in Photon Forge
* Use your hardest hitting skills under the effect of the <Trait id="2106"/> (and possibly <Trait id="2122"/>) buff. These include the landing damage from <Skill id="6005"/>, <Skill id="6153"/> and <Skill id="42009"/>. Keep in mind that <Trait id="2106"/> consumes its charges while <Trait id="2122"/> is a duration buff.
* Try to utilize your toolbelt skills off cooldown with <Skill id="42163"/> only being used above 50 heat.
* Make sure to use Corona Burst towards the end of your <Skill id ="42938"/> in order to have the <Boon name ="stability"/> from <Trait id="2152"/> preventing knockback from <Skill id="6154"/>.
* Make use of <Skill id="5808"/> and <Skill id="5824"/> to mitigate damage in add heavy fights.
* <Skill id="5939"/> can help in controlling movement of enemies without breakbar. 
* Even though <Trait id="2064"/> counters the initial damage of overheating, it still does almost 4k damage over time so consider leaving Photon Forge early if you are at low health even at the cost of some DPS.

You can switch to <Specialization name="scrapper"/> and equip <Skill id="30815"/> if you need <Effect name="stealth"/> for longer passages (e.g. [Twilight Oasis Fractal](https://discretize.eu/fractals/twilight-oasis)). It provides >40 seconds for the whole group. A smoke field can also be provided by <Skill id="5824"/> to blast <Effect name="stealth"/>.
</Card>

<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="5813"/> | 332 damage |
| <Skill id="6154"/> | 232 damage |
| <Skill id="42009"/> | 232 damage |
| Holographic Shockwave | 232 damage |
| <Skill id="21661"/> | 100 damage |
</Card>

</GridItem>

</Grid>
