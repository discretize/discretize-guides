---
title: 'Hybrid Chronomancer'
date: '2018-09-18'
rating: 'Great'
role: 'Support'
profession: 'Mesmer'
specialization: 'Chronomancer'
benchmark:
  { small: { dps: 13383, by: 'Kirasia [SC]', youtube: '9aGQDaCkOGo' } }
skills: [10197, 10200, 29830, 10267, 10186, 10302, 10236, 29519]
traits: [1852]
boons: ['Quickness', 'Alacrity', 'Might', 'Fury', 'Swiftness', 'Vigor', 'Aegis']
conditions: ['Vulnerability']
effects: ['Stealth']
---

The <Specialization text="Hybrid Chronomancer" name="chronomancer"/> is the ideal support variant if you're playing with a <Specialization name="druid"/> and <Specialization name="weaver" text="Air Weaver"/>s. It provides permanent <Boon name="quickness"/>, <Boon name="alacrity"/> and around 10x <Boon name="might"/> while dealing relatively high personal DPS.

With the **Dueling/Illusions** variant you have to run <Skill id="10311"/> to keep up <Boon name="quickness"/> and can't share <Boon name="aegis"/> but gain <Boon name="vigor"/> and deal high DPS; while the **Inspiration/Illusions** variant allows you to run <Skill id="29519"/> and spam group <Boon name="aegis"/> with <Trait id="1852"/>, <Trait id="1980"/>, <Trait id="1890"/>, <Trait id="1869"/>, <Skill id="10236"/> and <Trait id="1866"/>.

The build has access to the usual mesmer utilities such as <Skill id="10197"/> and <Effect name="stealth"/> skips, strong reflects, boon strip and amazing crowd control skills. You can also run a focus for <Skill id="10363"/> <Control name="pull"/>s and reflects with <Trait id="751"/>.

While the sheer amount of possibilities are nice to look at, the Chronomancer is one of the harder builds to play as the skills require timing and good dynamic decision-making.

<Divider text="Equipment (150 AR + Regular Infusions)"/>

As the <Specialization text="Hybrid Chronomancer" name="chronomancer"/> does not use the Chaos specialization with <Trait name="Chaotic Persistence"/>, it can not reach 100% Boon Duration without Harrier items, 161+ AR or Concentration infusions.

Please use our [Gear Optimizer](http://old.discretize.eu) to calculate the optimal gear for your personal Agony Resistance level.

<Grid>
<GridItem sm="4">
<Armor weight="Light" helmAffix="Harrier" helmRune="Leadership" shouldersAffix="Berserker" shouldersRune="Leadership" coatAffix="Commander" coatRune="Leadership" glovesAffix="Harrier" glovesRune="Leadership" leggingsAffix="Commander" leggingsRune="Leadership" bootsAffix="Harrier" bootsRune="Leadership"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Commander" weapon1MainSigil1="Concentration" weapon1OffType="Shield" weapon1OffAffix="Commander" weapon1OffSigil="Force" weapon2OffType="Sword" weapon2OffAffix="Commander" weapon2OffSigil="Force"/>

<Card title="Swap Weapons">
* Focus when reflects or pulls are needed
* Torch for <Boon name="might"/> stacking
* Pistol for extra CC
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Commander" accessory1Affix="Commander" accessory2Affix="Commander" amuletAffix="Commander" ring1Affix="Commander" ring2Affix="Commander"/>

<Consumables foodId="89002" utilityId="67530" infusionId="49432"/>
</GridItem>
</Grid>

<Divider text="Duel/Illu Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="1" traits1="Dueling" traits1SelectedIds="701,708,692" traits2Id="24" traits2="Illusions" traits2SelectedIds="721,729,733" traits3Id="40" traits3="Chronomancer" traits3SelectedIds="1995,1978,1890"/>
</GridItem>

<GridItem sm="5">
<Skills healId="21750" utility1Id="30814" utility2Id="29856" utility3Id="10236" eliteId="10311"/>

<Video youtube="9aGQDaCkOGo" title="Duel/Illu by Kirasia [SC] - 13.4k DPS"/>

This build variant has the highest personal DPS but needs <Skill id="10311"/> to keep up permanent <Boon name="quickness"/> and can't share <Boon name="aegis"/>.
</GridItem>
</Grid>

<Divider text="Situational"/>

<Grid>
<GridItem>
<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait id="1987" size="big" disableText/> | A slight DPS loss but adds some party healing. |
| <Trait id="751" size="big" disableText/> | Use it together with a focus for <Control name="pull"/>s and reflects. Swap out your offhand sword in that case. |
| <Trait id="674" size="big" disableText/> | Increases the duration of all your <Effect name="stealth"/> skills by 50%. |
| <Trait id="740" size="big" disableText/> | Heals and removes conditions on every Shatter skill. |
| <Trait id="744" size="big" disableText/> | A strong personal condition cleanse. |
| <Trait id="721" size="big" disableText/> | A minor DPS increase, if you don't run <Trait id="1980"/> you can trait it anyway. |
| <Trait id="752" size="big" disableText/> | Two seconds longer duration for Glamour skills like <Skill id="10197"/>. |
</Card>
</GridItem>

<GridItem>
<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill id="30305" size="big" disableText/> | A stronger group heal and condition cleanse if your party has problems with incoming damage. |
| <Skill id="34326" size="big" disableText/> | One of the strongest reflect skills, protecting everyone inside from projectiles for 6 seconds. |
| <Skill id="10197" size="big" disableText/> | Party escort service. |
| <Skill id="10200" size="big" disableText/> | A 1200 range teleport. It breaks <Control name="stun"/> on use, which means it gets executed even if there is no valid path to your mouse target - keep this in mind. |
| <Skill id="29578" size="big" disableText/> | Enables you to use key utilities twice. If you use <Skill id="29830"/> at the end of the cast, you get a "free" mimic and can do stuff like triple <Skill id="10200"/> without the need for any illusions. |
| <Skill id="10267" size="big" disableText/> | Necessary if you need to remove boons and have no <Specialization name="spellbreaker"/>. |
| <Skill id="10245" size="big" disableText/> | Useful for party skipping. Provides 15 seconds of <Effect name="stealth"/> with <Trait id="674"/> and <Skill id="29830"/>. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Written Opener">
1. Open on Sword/Sword with <Skill id="10173"/> and <Skill id="10174"/>
2. Cast <Skill id="29830"/> during the aftercast of one of the following skills:
    1. <Skill id="21750"/> for maximum DPS
    2. <Skill id="29519"/> if you need CC and run Insp/Illu
    3. <Skill id="30643"/> if you need CC and run Duel/Illu
3. Cast <Skill id="10311"/> if you run Duel/Illu
4. <Skill id="10236"/> and <Skill id="29856"/>
5. You will have enough time left for <Skill id="30814"/> with Insp/Illu, otherwise <Skill id="30747"/> will end during the cast
6. Cast <Skill id="29856"/> and <Skill id="30814"/> again
7. <Skill id="10174"/> -> <Skill id="21750"/> -> <Skill id="10174"/>
8. Weapon swap
9. <Skill id="10236"/>
</Card>

<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="29519"/> | 1000 damage |
| <Skill id="30643"/> | 200-1200 damage |
| <Skill id="10287"/> | 100-400 damage |
| <Skill id="10363"/> | 150 damage |
| <Skill id="30814"/> | 150 damage with <Condition name="slow"/> |
| <Skill id="10358"/> | 100 damage |
| <Skill id="29856"/> | 99 damage with <Condition name="chilled"/> |
</Card>
</GridItem>

<GridItem sm="5">
<Card title="Skill priority">
As it is almost impossible to follow a fixed rotation in fractals, try to keep to the following list of priorities:

1. Keep up <Boon name="quickness"/> using <Skill id="10311"/>, <Skill id="30814"/>, <Trait id="729"/> and <Skill id="10236"/>
2. Keep up <Boon name="alacrity"/> using <Skill id="30643"/>, <Skill id="29856"/>, <Trait id="1927"/> and <Skill id="10236"/>
3. Break any defiance bar as fast as possible using <Skill id="30643"/>, <Skill id="10287"/> and <Skill id="29519"/>
4. Do as much DPS as possible
   1. Use <Skill id="10174"/> with <Skill id="21750"/> whenever ready
   2. Use <Skill id="10334"/> off recharge, possibly twice with <Skill id="29830"/> (with three illusions)
   3. Don't interrupt your auto-attack chains as the third hit (<Skill id="10172"/>) deals the most damage
   4. Cast <Skill id="49068"/> (twice if traited) followed by <Skill id="10190"/> whenever you have three illusions up and don't plan to use <Skill id="29830"/> in the next 15 seconds
   5. <Skill id="30769"/> is not worth using over auto-attack for DPS but grants <Boon name="protection"/>

</Card>
</GridItem>
</Grid>
