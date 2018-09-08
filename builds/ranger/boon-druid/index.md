---
title: 'Boon Druid'
date: '2018-05-16'
rating: 'Meta'
role: 'Support'
profession: 'Ranger'
specialization: 'Druid'
skills: [31869, 12495, 12493, 12497, 12498, 12569, 31582]
traits: [2057, 1016]
boons:
  [
    'Might',
    'Fury',
    'Regeneration',
    'Swiftness',
    'Protection',
    'Vigor',
    'Stability',
  ]
conditions: ['Weakness', 'Vulnerability', 'Blind']
effects: ['Stealth']
---

At the moment <Specialization name="druid" prefix="boon"/> is a great build for fractals, primarily providing the group with heals. Aside from keeping up the health bars (<Item id="24836"/> uptime), it also facilitates a bunch of utilities and strong offensive party support in form of <Skill id="12497"/>, <Skill id="31582"/>, <Trait id="2057"/>, <Trait id="1016"/> and <Condition name="vulnerability"/>.

The Druid's main source of healing comes from <Skill id="31869"/>, which is replenished by acquiring Astral Force from healing allies and damaging foes (<Trait id="1874"/>). Using CA replaces your weapon skills with strong AoE healing skills.

Besides healing, the <Skill id="31869"/> skills (and any glyph outside of CA like <Skill id="31582"/> due to <Trait id="2001"/>) trigger <Trait id="2057"/> which generates 25x <Boon name="might"/> for up to 10 people with a boon duration setup.

With the help of its pets, the druid also has access to heavy defiance bar damage with <Skill id="31639"/> (_Electric Wyvern_) and <Skill id="43636"/> (_Rock Gazelle_). Moreover, the _Smokescale_ pet can be used to stack party <Effect name="stealth"/> with its <Skill id="31568"/> smoke field.

<Divider text="Equipment (150 AR)"/>

Keep in mind that the setup below is optimized for healing in fractals and is not recommended for raid content due to the high Toughness amount from Minstrel and Cleric items. **If you don't care about optimizing and want to use one set for everything, simply run a full Harrier setup instead.**

<Grid>
<GridItem sm="4">
<Armor helmId="75022" helmRuneId="24842" helmRuneCount="6" helmAffix="Minstrel" helmRune="Monk" shouldersId="48017" shouldersRuneId="24842" shouldersRuneCount="6" shouldersAffix="Cleric" shouldersRune="Monk" coatId="70834" coatRuneId="24842" coatRuneCount="6" coatAffix="Minstrel" coatRune="Monk" glovesId="48014" glovesRuneId="24842" glovesRuneCount="6" glovesAffix="Cleric" glovesRune="Monk" leggingsId="75340" leggingsRuneId="24842" leggingsRuneCount="6" leggingsAffix="Minstrel" leggingsRune="Monk" bootsId="48012" bootsRuneId="24842" bootsRuneCount="6" bootsAffix="Cleric" bootsRune="Monk"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainId="74905" weapon1MainSigil1Id="74326" weapon1MainType="Axe" weapon1MainAffix="Minstrel" weapon1MainSigil1="Transference" weapon1OffId="71116" weapon1OffSigilId="72339" weapon1OffAffix="Minstrel" weapon1OffType="Warhorn" weapon1OffSigil="Concentration" weapon2MainId="75200" weapon2MainSigil1Id="74326" weapon2MainSigil2Id="24551" weapon2MainType="Staff" weapon2MainAffix="Minstrel" weapon2MainSigil1="Transference" weapon2MainSigil2="Water"/>

<Card title="Swap Weapons">
* Offhand axe when <Skill id="12638"/> is needed to <Control name="pull"/>
</Card>
</GridItem>

<GridItem sm="4">
<Trinkets backItemId="79830" backItemStatId="155" backItemAffix="Cleric" accessory1Id="39547" accessory1Affix="Cleric" accessory2Id="39546" accessory2Affix="Cleric" amuletId="39566" amuletAffix="Cleric" ring1Id="39597" ring1Affix="Cleric" ring2Id="79446" ring2StatId="1134" ring2Affix="Minstrel"/>

<Consumables foodId="68634" utilityId="67528" infusionId="37125"/>
</GridItem>
</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="30" traits1="Skirmishing" traits1Selected="1069,1016,1064" traits2Id="25" traits2="Nature Magic" traits2Selected="1060,964,1038" traits3Id="5" traits3="Druid" traits3Selected="2016,2001,2057"/>

<Card title="Pets">
| | | |
| -- | -- | -- |
| <Skill id="43636" size="big" disableText/> | [Rock Gazelle](https://wiki.guildwars2.com/wiki/Juvenile_Rock_Gazelle) | Best CC pet for small hitboxes, also does defiance bar damage with its auto-attack. |
| <Skill id="44980" size="big" disableText/> | [Jacaranda](https://wiki.guildwars2.com/wiki/Juvenile_Jacaranda) | Recommended if you want to replace <Skill id="12493"/> but are missing <Condition name="vulnerability"/> without it. |
| <Skill id="12708" size="big" disableText/> | [Pink Moa](https://wiki.guildwars2.com/wiki/Juvenile_Pink_Moa) | Hits one time for 200 Defiance bar damage. |
| <Skill id="12709" size="big" disableText/> | [Black Moa](https://wiki.guildwars2.com/wiki/Juvenile_Black_Moa) | Hits three times for 100 Defiance bar damage. |
| <Skill id="31568" size="big" disableText/> | [Smokescale](https://wiki.guildwars2.com/wiki/Juvenile_Smokescale) | Provides a 5 second smoke combo field to stack <Effect name="stealth"/>. |
</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="31407" utility1="31582" utility2="12497" utility3="12493" elite="12569"/>

<Card title="Situational">
| | |
| -- | -- |
| <Skill id="12489" size="big" disableText/> | A better condition clear, use it in combination with <Trait id="1075"/>. |
| <Skill id="31746" size="big" disableText/> | Instant 200 defiance bar damage in case you need more CC. |
| <Skill id="12495" size="big" disableText/> | Grants <Boon name="protection"/> to the party. |
| <Skill id="12498" size="big" disableText/> | Adds about 200 DPS per affected target (for non-condition builds). |
| <Skill id="31888" size="big" disableText/> | If you can't profit from <Boon name="stability"/>, this provides more consistent healing and some <Boon name="might"/>. |
| <Trait id="978" size="big" disableText/> | If you don't need improved resurrecting, this adds quite a bit of healing power. |
| <Trait id="1935" size="big" disableText/> | Mainly a matter of taste, useful if you need more frequent projectiles absorption from <Skill id="31496"/> and a little bit more CC (<Skill id="31869"/> counts as Staff weapon swap as well). |

Note that you should replace <Skill id="12493"/> if you have 25x <Condition name="vulnerability"/> without it, otherwise replace <Skill id="12497"/>.
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem>
<Card title="Rotation">
* To keep up your strong <Boon name="regeneration"/>, swap to your Warhorn set and <Trait id="1064"/> <Skill id="12621"/> with <Item id="72339"/>. Go into <Skill id="31869"/> and stay there for 9 seconds, leave it and <Trait id="1064"/> <Skill id="12621"/> again before switching back to Staff.
* Use your glyphs like <Skill id="31582"/> whenever they are off cooldown to proc <Trait id="2057"/> and generate <Boon name="might"/> through <Trait id="2001"/>, but don't overwrite stacks from <Skill id="31869"/>
* Use your spirits whenever they are off cooldown, but don't explode them unless you have permanent <Boon name="alacrity"/> or your team has to leave the combat area
* <Skill id="31496"/> is amazing against (reflectable) projectiles
* You can blast the water field from <Skill id="31496"/> for additional heal and the light field from <Skill id="31406"/> for condition cleanse with <Skill id="31535"/>, <Skill id="12621"/> and <Skill id="31318"/>
</Card>
</GridItem>

<GridItem>
<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="43636"/> | 232 damage (*Rock Gazelle*) |
| <Skill id="12708"/> | 200 damage (*Pink Moa*) |
| <Skill id="12709"/> | 300 damage (*Black Moa*) |
| <Skill id="43636"/> | 232 damage with *Rock Gazelle* |
| <Skill id="31318"/> | 200 damage (in *<Skill id="31869"/>*) |
| <Skill id="12490"/> | 132 damage with <Condition name="chilled"/> |
</Card>
</GridItem>
</Grid>
