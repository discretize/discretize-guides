---
title: 'Soulbeast'
date: '2019-11-18'
rating: 'Meta'
role: 'Damage'
profession: 'Ranger'
specialization: 'Soulbeast'
benchmark:
  { small: { dps: 33162, by: 'Obvious Trash [SC]', youtube: 'E8ky10gAxB4' } }
skills: [12497, 12638]
conditions: ['Vulnerability']
effects: ['Stealth']
code: '[&DQQIGiA7Nzp5AC4XrAGsAbwAtQClAaUBLhYuFjsuLxUAAAAAAAAAAAAAAAA=]'
---

<Tabs>
<Tab title="Build">

<Specialization name="Soulbeast" text="Power Soulbeast"/> is a DPS build with very high burst damage that in addition provides a strong party buff with <Skill name="Frost Spirit"/> (in groups without a Druid), some <Condition name="Vulnerability"/> and crowd control skills.

Furthermore, <Skill name="Whirling Defense"/> is an exceedingly strong reflect skill that comes in handy on several encounters (e.g. Artsariiv).

The build benefits from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment without Spotter"/>

<Tabs outlined>
<Tab title="150 Agony Resistance">
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

<Tab title="222 Agony Resistance">
<Grid>
<GridItem sm="4">
<Armor weight="Medium" helmAffix="Assassin" helmRune="Scholar" shouldersAffix="Assassin" shouldersRune="Scholar" coatAffix="Berserker" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
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

<Card title="Extra note">
You need Fractal God, <Item id="86175"/> and <Item id="70596"/> !
</Card>

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
| <Trait name="Leader of the Pack" size="big" disableText/> | Very strong alternative to <Trait name="Oppressive Superiority"/> for fights where your party can profit from the shared <Skill name="One Wolf Pack"/>. Currently meta on Skorvald, Arkk, Siax and Ensolyss. You should also activate it when precasting <Skill name="One Wolf Pack"/> and retrait before getting into combat. |
</Card>
</GridItem>
</Grid>
</Tab>

<Tab title="Guide">
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
16. <Skill id="12522"/> -> <Skill id="12523"/> (Greatsword 4 2x)  
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
</GridItem>
</Grid>
</Tab>

<Tab title="99CM">
<Divider text="Nightmare"/>
<Tabs>
<Tab title="Mama">
<Specialization name="Soulbeast"/> is not a great pick at this boss. However, in daily clears you have to find a way to make it work.

---

**Precast**  
- Remember to share <Skill name="Moastance"/> and blast with <Skill name="Callofthewild"/>.
- Before you cast <Skill id="5531"/> and <Skill name="Barrage"/> on MAMA: share <Skill name="One wolf pack"/> with <Trait name="leaderofthepack"/> and then swap back to <Trait name="oppressivesuperiority"/>. 

**Opening**

You wanna do a modified Greatsword rotation: 
- <Skill name="Maul"/> and <Skill name="Sicem"/> during the cast
- <Skill name="Worldly impact"/>
- <Skill name="Path of scars"/>
- <Skill name="Whirling defense"/>
- it should be phased now.

**1st Add**
- Help CCing with <Skill id="45743"/> 
- autoattack the add to death with your sword.

**2nd phase**

When you go back back to MAMA swap to GS and use:
- <Skill name="Maul"/>
- <Skill name="hiltbash"/>
- <Skill name="Maul"/>
- <Skill id="41524"/> (dont use <Skill name="Sicem"/> here)

**2nd Add**
- Help CCing with <Skill id="45743"/> 
- Use a mix of <Skill name="Maul" profession="ranger"/> and autoattacks to kill it.

**3rd phase**

In phase 3 you do same rotation as in p1 (although you can do the full gs rotation if you have hilt bash off cd).  
MAMA should phase while you're casting your <Skill name="Whirling defense"/>, then do <Skill name="Monarchs Leap"/> for free evade away from the poison field and to get to the add faster.

**3rd Add**  
- Swap to GS as soon as possible.
- Do the same thing as before. Save your <Skill id="45743"/>.

**4th phase**
- Help with cc by doing <Skill name="Hilt bash"/> and <Skill id="45743"/> 
- Normal GS rotation.

</Tab>
<Tab title="Siax">
### **General**
- You can take <Skill name="Bearstance"/> for condi cleanse instead of <Skill name="Wehealasone"/>.
- In organized groups its worth it to take <Skill name="Frosttrap"/> over <Skill name="Signetofthewild"/>.
- In organized groups you can take longbow and use <Trait name="Leaderofthepack"/>

---

**Precast**

Precast <Skill name="Frosttrap"/> on the boss like a <Specialization name="Dragonhunter"/> in disguise. Remember to share <Skill name="Moastance"/> and blast with <Skill name="Callofthewild"/>. Share <Skill name="One wolf pack"/> and take the mistlock.

**Opening**

You wanna do following opening: 
- Summon <Skill name="Frostspirit"/> as he triggers
- <Skill name="Frosttrap"/> so you have two of those ticking at the same time.
- <Skill name="Sicem"/> 
- <Skill name="Barrage"/>
- CC: <Skill id="45743"/> and <Skill name="Pointblankshot"/>
- <Skill name="Rapidfire"/>
- You shouldnt use <Skill name="Whirling defense"/> in phase 1.
 
**1st Add**  
- Use <Skill id="12622"/> to get to the add quickly. 
- Kill it with  <Skill name="Path of scars"/> and <Skill name="Whirling defense"/>. If your group sucks, you can save your important dps skills and kill the mob with a mix of AA and F1/F2s. The weaver should help you anyway.

**Phase 2**  
- Use <Skill name="onewolfpack"/> in the middle. 
- AA as as all your skills are on CD.

**2nd Add**  
- Use longbow here. <Skill name="pointblankshot"/> and <Skill name="rapidfire"/> 
- The remaining damage should be dealt by the <Specialization name="Dragonhunter"/> with a <Skill name="Swordofjustice"/>.
- If you are using GS do GS2, 5, 2, F1, F2 to kill the add.

**Phase 3**

Longbow:
- <Skill name="Barrage"/> on Siax
- <Skill name="Frost trap"/>
- <Skill name="Path of scars"/> and <Skill name="Whirling defense"/>

Greatsword:
- <Skill name="Worldlyimpact"/> 
- <Skill name="Path of scars"/> and <Skill name="Whirling defense"/>
</Tab>
<Tab title="Ensolyss">
In no <Specialization name="Firebrand"/> comp you wanna play <Skill name="Moastance"/> over <Skill name="Signet of the wild"/>. Use <Skill name="Moastance"/> at the beginning of each phase. Regardless what group you are playing with, you should be playing <Trait name="Leaderofthepack"/>. Longbow is superior to greatsword.

**Opening**  
- Right after Ensolyss spawns: <Skill id="5531"/> and <Skill name="Barrage"/>
- <Skill id="45743"/>, <Skill name="Pointblankshot"/> for insta CC
- <Skill name="onewolfpack"/>, <Skill name="sicem"/>
- <Skill name="rapidfire"/>
- <Skill name="worldlyimpact"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/>
- Pick up <Skill name="conjurelightninghammer"/> and use <Skill id="5725"/>
- AA with <Skill name="conjurelightninghammer"/> until its phased or your <Skill name="pathofscars"/> is back up

**Orb phases**

Use <Skill name="We heal as one"/> to keep up <Boon name="alacrity"/>. 

**66% and 33%**  
- <Skill name="onewolfpack"/>
- <Skill id="5531"/> if available and <Skill name="Barrage"/>
- <Skill name="sicem"/>
- <Skill id="45743"/> and <Skill name="pointblankshot"/>
- <Skill name="Rapidfire"/>
- <Skill name="worldlyimpact"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/>
- Pick up <Skill name="conjurelightninghammer"/> and use <Skill id="5725"/>
- AA with <Skill name="conjurelightninghammer"/> until its phased or your <Skill name="pathofscars"/> is back up

</Tab>
</Tabs>
</Tab>
<Tab title="100CM">
<Divider text="Shattered Observatory"/>
<Tabs>
<Tab title="Skorvald">
**General**  
- In organized groups its worth it to take <Skill name="Frosttrap"/> over <Skill name="Signetofthewild"/>.
- In organized groups you can take warhorn and use <Trait name="Leaderofthepack"/>

**Precast**

Precast <Skill name="Frosttrap"/> on the boss like a <Specialization name="Dragonhunter"/> in disguise. Before blasting <Boon name="Might"/> cast your <Skill name="Frostspirit"/> and wait for it to loose some hp. Remember to share <Skill name="Moastance"/> and blast with <Skill name="Callofthewild"/>. Share <Skill name="One wolf pack"/> and take the mistlock.

Teleport your <Skill name="Frostspirit"/> down to the platform.

**Opening**

- <Skill id="5531"/> and <Skill name="Barrage"/>
- Swap to warhorn
- <Skill name="Onewolfpack"/>
- <Skill name="Frosttrap"/>, <Skill name="Sicem"/>
- <Skill name="hunterscall"/>
- <Skill name="Worldlyimpact"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/>

**Adds**  
Can use <Skill name="whirlingdefense"/> on the 2nd one. Swap to sword/warhorn and kill the adds with a mix of F1, F2 and AAs. Blast <Boon name="might"/> on the 3rd or 4th island.
Resummon <Skill name="Frostspirit"/> on the last island. Take FGS if available. Take the portal early to teleport <Skill name="Frostspirit"/> to you.

**66% and 33%**  
In these phases you wanna make sure all ticks of <Skill name="Whirlingdefense"/> hit while he's CCed: 
- <Skill id="5531"/>
- <Skill name="Onewolfpack"/>
- <Skill name="Frosttrap"/>, <Skill name="Sicem"/>
- <Skill name="hunterscall"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/>

Skip F3 in fast parties, because it has kind of a long cast time.

<Message>
<Skill name="Hunterscall"/> has a bit of an aftercast and you can cancel it earlier
</Message>

</Tab>
<Tab title="Artsariiv">
Summon <Skill name="Frost Spirit"/> in middle before someone triggers her. While she is talking start your precast <Skill id="5531"/> and <Skill name="Barrage"/>. Use <Skill name="Maul"/> <Skill name="Hiltbash"/> and <Skill name="Maul"/> while she is still in the middle. Teleport to the corner and teleport <Skill name="Frost Spirit"/> to you.

Now go through this rotation:
- <Skill name="onewolfpack"/>, <Skill name="sicem"/>
- <Skill id="45743"/>, <Skill name="pathofscars"/> for insta CC
- <Skill name="Whirlingdefense"/> to reflect for omegadps

Use Consumables to CC the adds.

**66% and 33%**

- <Skill name="Maul"/> <Skill name="Hiltbash"/> <Skill name="Maul"/>
- <Skill id="41524"/> <Skill id="45743"/>
- Dodge (do not use sic em here)
- Special action key into the corner
- <Skill name="Maul"/> and <Skill name="sicem"/> into the cast
- <Skill name="Worldlyimpact"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/> to reflect again

If you dont skip anomalies you can just try to reflect and hope she targets someone close
or you could go for reflecting her spin attack.
</Tab>
<Tab title="Arkk">
**General**
- You can take <Skill name="trollunguent"/> for pushing the orbs inside the lightning
- In organized groups its worth it to take <Skill name="Frosttrap"/> over <Skill name="Signetofthewild"/>.
- In organized groups you can take longbow and use <Trait name="Leaderofthepack"/>
- Do not use <Skill name="Sicem"/> on 10% burns. 
- Push orbs with longbow inside the lightning. Use <Skill name="trollunguent"/> to stay alive.

**Precast**

Precast <Skill name="Frosttrap"/> on the boss like a <Specialization name="Dragonhunter"/> in disguise. Remember to share <Skill name="Moastance"/> and blast with <Skill name="Callofthewild"/>. Share <Skill name="One wolf pack"/> and take the mistlock.

If you have a portal to get there early, summon your <Skill name="Frost spirit"/>.

**Opening**

- <Skill id="5531"/>
- <Skill name="Frosttrap"/> so you have two of those ticking at the same time.
- <Skill name="Sicem"/>
- <Skill name="Barrage"/> <Skill name="Pointblankshot"/> <Skill name="Rapidfire"/>
- <Skill name="Worldlyimpact"/>
- <Skill name="Pathofscars"/> <Skill name="Whirling defense"/>
- <Skill id="45743"/> <Skill id="41524"/>

**10% burn phases**

Your dps will be low, because you do not want to use <Skill name="Sicem"/> there. You can either do <Skill name="Whirling defense"/> or <Skill name="Barrage"/> <Skill name="Pointblankshot"/> <Skill name="Rapidfire"/>.

**Archdiviner phase**

Pull one add with <Skill name="Path of scars"/>. This does not work reliable.  
The weaver should give you a <Skill name="conjurefierygreatsword"/> in the archdiviner phase. Take it and use <Skill name="Fierywhirl"/> in combination with the special action key to get all hits on the archdiviner.

Precast <Skill id="5531"/> when archdiviner is dead.

**Big burn phase**

- <Skill name="Barrage"/>
- <Skill name="onewolfpack"/> <Skill name="Sicem"/>
- <Skill name="Frosttrap"/>
- <Skill name="Pointblankshot"/> <Skill name="Rapidfire"/>
- <Skill name="Worldlyimpact"/>
- <Skill name="Pathofscars"/> <Skill name="Whirling defense"/>

**Gladiator phase**

You can use <Skill name="Sicem"/> and <Skill name="whirlingdefense"/> to kill him fast.

**10% burn phase**

Press random buttons, but no buttons with cooldowns.

**Last big burn phase**

Full rotation with everything off cooldown.
</Tab>
</Tabs>
</Tab>

</Tabs>
