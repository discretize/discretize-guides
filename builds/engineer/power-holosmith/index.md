---
title: 'Power Holosmith'
date: '2018-07-01'
rating: 'Great'
role: 'Damage'
profession: 'Engineer'
specialization: 'Holosmith'
benchmark: { small: { dps: 33097, by: 'hint [SC]', youtube: 'rVVBwpQOXaU' } }
skills: [30815, 43739]
traits: [517]
conditions: ['Vulnerability', 'Blind', 'Crippled', 'Immobile']
effects: ['Stealth']
---

The engineer build that currently fares best in fractals is the <Specialization prefix="power" name="holosmith"/>, offering a mix of high damage and a good amount of CC and utility in form of <Condition name="vulnerability"/> and <Condition name="Blind"/>. It can also provide soft CC in form of <Condition name="crippled"/> and <Condition name="immobile"/>. As a power class it benefits from slaying potions like <Item id="50082"/> and <Item id ="24868"/>.

It has two weapon sets that perform equally well when only looking at raw DPS while the rifle variant usually has a little higher burst and doesn't necessarily has to stay as close as the sword variant.

<Divider text="Equipment"/>

<Grid>
<GridItem>
<Armor helmId="48087" helmRuneId="24836" helmRuneCount="6" helmAffix="Berserker" helmRune="Scholar" shouldersId="48089" shouldersRuneId="24836" shouldersRuneCount="6" shouldersAffix="Berserker" shouldersRune="Scholar" coatId="48085" coatRuneId="24836" coatRuneCount="6" coatAffix="Berserker" coatRune="Scholar" glovesId="48086" glovesRuneId="24836" glovesRuneCount="6" glovesAffix="Berserker" glovesRune="Scholar" leggingsId="48088" leggingsRuneId="24836" leggingsRuneCount="6" leggingsAffix="Berserker" leggingsRune="Scholar" bootsId="48084" bootsRuneId="24836" bootsRuneCount="6" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem>
<Weapons weapon1MainId="46768" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24868" weapon1MainType="Rifle" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact"/>

<Card title="Alternative weapons">
* Rifle with <Item id="36053" disableText/> / <Item id="24615" disableText/> and slaying sigils  
  (<Item id="36054"/> doesn't stack anymore)
</Card>
</GridItem>

<GridItem>
<Trinkets backItemId="49384" backItemStatId="584" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="67530" infusionId="37131"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="38" traits1="Firearms" traits1Selected="1914,2006,526" traits2Id="6" traits2="Explosives" traits2Selected="1882,1892,1541" traits3Id="57" traits3="Holomsith" traits3Selected="2106,2152,2064"/>

<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait id="1923" size="big" disableText/> | If lacking fury, consider swapping out <Trait id="2006"/>. |
| <Trait id="505" size="big" disableText/> | On longer fights without adds, this may pull slightly ahead of <Trait id="1541"/>. |
</Card>
</GridItem>

<GridItem>
<Skills heal="40507" utility1="5812" utility2="6020" utility3="42842" elite="42009"/>

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
| <Skill id="5857" size="big" disableText/> | An alternative healing skill if condition cleanse is needed. |
| <Skill id="21659" size="big" disableText/> | Provides additional CC with the toolbelt skill <Skill id="21661"/>. |
| <Skill id="43739" size="big" disableText/> | Is another (group) block skill which even reflects projectiles above 50 heat. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Skill Usage and Tips">
* Don't interrupt your auto attack chain in Photon Forge
* Use your hardest hitting skills under the effect of the <Trait id="2106"/> (and possibly <Trait id="2122"/>) buff. These include the landing damage from <Skill id="6005"/>, <Skill id="6153"/> and <Skill id="42009"/>. Keep in mind that <Trait id="2106"/> consumes its charges while <Trait id="2122"/> is a duration buff.
* Try to utilize your toolbelt skills off cooldown with <Skill id="42163"/> only being used above 50 heat.
* Make sure to use Corona Burst towards the end of your <Skill id ="42938"/> in order to have the <Boon name ="stability"/> from <Trait id="2152"/> avoiding knockback from <Skill id="6154"/>.
* Make use of <Skill id="5808"/> and <Skill id="5824"/> to mitigate damage in add heavy fights.
* <Skill id="5939"/> can help in controlling movement of enemies without breakbar. 
* Even though <Trait id="2064"/> counters the initial damage of overheating, it still does almost 4k damage over time so consider leaving Photon Forge early if you are at low health even at the cost of some DPS.

You can switch to <Specialization name="scrapper"/> and equip <Skill id="30815"/> if you need <Effect name="stealth"/> for longer passages (e.g. [Twilight Oasis Fractal](https://discretize.eu/fractals/twilight-oasis)). It provides >40 seconds for the whole group. A smoke field can also be provided by <Skill id="5824"/> to blast <Effect name="stealth"/>.
</Card>

</GridItem>

<GridItem>
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
