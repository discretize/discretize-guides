---
title: 'Power Soulbeast'
date: '2019-03-29'
rating: 'Meta'
role: 'Damage'
profession: 'Ranger'
specialization: 'Soulbeast'
benchmark: { small: { dps: 31612, by: 'Casual [SC]', youtube: 'BupIpBs-eOQ' } }
skills: [12497, 12638]
conditions: ['Vulnerability']
effects: ['Stealth']
---

<Specialization name="Soulbeast" text="Power Soulbeast"/> is a DPS build with very high burst damage that in addition provides a strong party buff with <Skill name="Frost Spirit"/> (in groups without a Druid), some <Condition name="Vulnerability"/> and crowd control skills.

Furthermore, <Skill name="Whirling Defense"/> is an exceedingly strong reflect skill that comes in handy on several encounters (e.g. Artsariiv).

The build benefits from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>

<Tabs outlined>
<Tab title="150 Agony Resistance (No Spotter)">
<Grid>
<GridItem sm="4">
<Armor weight="Medium" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Berserker" shouldersRune="Scholar" coatAffix="Assassin" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Assassin" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Berserker" weapon1MainId="46774" weapon1MainSigil1="Force" weapon1MainSigil1Id="24615" weapon1OffType="Axe" weapon1OffAffix="Berserker" weapon1OffId="46759" weapon1OffSigil="Impact" weapon1OffSigilId="24868" weapon2MainId="46762" weapon2MainSigil1Id="24615" weapon2MainSigil2Id="24868" weapon2MainType="Greatsword" weapon2MainAffix="Berserker" weapon2MainSigil1="Force" weapon2MainSigil2="Impact"/>

<Card title="Swap Weapons">
* Warhorn for <Boon name="might"/> pre-stacking. Also useful as a replacement for Greatsword one some bosses (e.g. Skorvald).
* Sword with <Item name="Night" type="Sigil"/> and other with <Item name="Serpent Slaying" type="Sigil"/>
* Axes and Greatswords with slaying sigils (see [Consumables Guide](/guides/consumables))
* Longbow to precast <Skill name="Barrage"/>
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Assassin" accessory2Affix="Assassin" amuletAffix="Berserker" ring1Affix="Berserker" ring2Affix="Berserker"/>

<Consumables food="Bowl of Sweet and Spicy Butternut Squash Soup" utility="Tin of Fruitcake" infusion="Mighty +9 Agony Infusion"/>
</GridItem>
</Grid>
</Tab>

<Tab title="207 Agony Resistance (No Spotter)">
<Grid>
<GridItem sm="4">
<Armor weight="Medium" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Assassin" shouldersRune="Scholar" coatAffix="Berserker" coatRune="Scholar" glovesAffix="Assassin" glovesRune="Scholar" leggingsAffix="Assassin" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Berserker" weapon1MainId="46774" weapon1MainSigil1="Force" weapon1MainSigil1Id="24615" weapon1OffType="Axe" weapon1OffAffix="Berserker" weapon1OffId="46759" weapon1OffSigil="Impact" weapon1OffSigilId="24868" weapon2MainId="46762" weapon2MainSigil1Id="24615" weapon2MainSigil2Id="24868" weapon2MainType="Greatsword" weapon2MainAffix="Berserker" weapon2MainSigil1="Force" weapon2MainSigil2="Impact"/>

<Card title="Swap Weapons">
* Warhorn when <Boon name="might"/> is blasted.
* Sword with <Item name="Night" type="Sigil"/> and other with <Item name="Serpent Slaying" type="Sigil"/>
* Axes and Greatswords with slaying sigils (see [Consumables Guide](/guides/consumables))
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Berserker" accessory1Affix="Berserker" accessory2Affix="Berserker" amuletAffix="Berserker" ring1Affix="Berserker" ring2Affix="Berserker"/>

<Consumables food="Bowl of Sweet and Spicy Butternut Squash Soup" utility="Tin of Fruitcake" infusion="Mighty +9 Agony Infusion"/>
</GridItem>
</Grid>
</Tab>
</Tabs>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="8" traits1="Marksmanship" traits1SelectedIds="1014,1000,996" traits2Id="32" traits2="Beastmastery" traits2SelectedIds="1606,1047,1066" traits3Id="55" traits3="Soulbeast" traits3SelectedIds="2071,2085,2143"/>
  
<Card title="Pets">
| | | |
| -- | -- | -- |
| <Skill id="43636" size="big" disableText/> | [Rock Gazelle](https://wiki.guildwars2.com/wiki/Juvenile_Rock_Gazelle) | Best CC pet for small hitboxes, also this is the pet you use in <Skill id="42944"/>. |
| <Skill id="31568" size="big" disableText/> | [Smokescale](https://wiki.guildwars2.com/wiki/Juvenile_Smokescale) | Provides a 5 second smoke combo field to stack <Effect name="stealth"/>. |
| <Skill id="12658" size="big" disableText/> | [Jungle Stalker](https://wiki.guildwars2.com/wiki/Juvenile_Jungle_Stalker) | Provides 5 stacks of <Boon name="might"/>, useful after long intermediate phases (e.g. orbs at Ensolyss). |
</Card>  
</GridItem>

<GridItem sm="5">
<Skills healId="31914" utility1Id="12633" utility2Id="12497" utility3Id="12491" eliteId="45717"/>

<Card title="Situational">
| | |
| -- | -- |
| <Trait name="Leader of the Pack" size="big" disableText/> | Very strong alternative to <Trait name="Oppressive Superiority"/> for fights where your party can profit from the shared <Skill name="One Wolf Pack"/>. Currently meta with Firebrand/Renegade on Skorvald, Arkk and Ensolyss. You should also activate it when precasting <Skill name="One Wolf Pack"/> and retrait before getting into combat. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation">
* Enter <Skill id="42944"/> with Gazelle
* Cast <Skill id="12497"/>
1. <Skill id="45717"/> (Elite) 
2. <Skill id="12633"/> (Utility)
3. <Skill id="12525"/> (Greatsword 2)
4. <Skill id="12475"/> (Greatsword 5)
5. <Skill id="12525"/> (Greatsword 2)
6. <Skill id="40729"/> (F3)  
7. **Swap to sword**
8. <Skill id="12638"/> (Axe 4)
9. <Skill id="12639"/> (Axe 5)
10. <Skill id="41524"/> (F1)
11. <Skill id="45743"/> (F2)
12. Autoattack chain 4x
13. <Skill id="12638"/> (Axe 4)
14. **Swap to greatsword**
15. <Skill id="12525"/> (Greatsword 2)
16. <Skill id="12522"/> -> <Skill id="12624"/> (Greatsword 4 2x)  
17. Autoattack chain 1x
18. <Skill id="12525"/> (Greatsword 2)
19. <Skill id="41524"/> (F1)
20. <Skill id="45743"/> (F2)
21. Autoattack chain 2x  
22. **Repeat from** `Step 1`

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Notes">
- Warhorn is currently only used with very fast groups on Skorvald, simply use <Skill name="Hunters Call"/> before swapping to axe
- Precast <Skill name="Firestorm" profession="bundle"/> from <Skill name="Conjure Fiery Greatsword"/> if you have one, otherwise <Skill name="Barrage"/> from longbow
- For short-phased fights with greatsword you can skip steps 4 and 5 to cast <Skill id="12639"/> earlier
- <Skill id="12639"/> reflects projectiles - this is very strong on Artsariiv (learn the animation of her throwing the orbs) and some other encounters (with <Boon name="Stability"/> and <Boon name="Aegis"/> you can even reflect the orbs on Arkk)
</Card>

<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="45743"/> | 200 damage (F2 in <Skill id="42944"/>) |
| <Skill id="12638"/> | 150 damage (Axe 4) |
| <Skill id="12475"/> | 150 damage (Greatsword 5) from behind |
</Card>

<Video youtube="BupIpBs-eOQ" title="Power Soulbeast by Casual [SC]"/>
</GridItem>
</Grid>
