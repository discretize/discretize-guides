---
title: 'Heal Firebrand'
date: '2021-02-24'
rating: 'Offmeta'
role: 'Support'
profession: 'Guardian'
specialization: 'Firebrand'
skills: [9093, 9153, 9251]
boons: ['Quickness', 'Fury', 'Might', 'Stability', 'Retaliation', 'Aegis']
conditions: ['Vulnerability', 'Blinded', 'Crippled']
code: '[&DQEQLjElPjZLF0sXehZ6FksBNgH+AP4AiRKJEgAAAAAAAAAAAAAAAAAAAAA=]'
cmguides: '/cm-guides/guardian/heal-firebrand'
classification: [4, 1, 3, 1, 2]
---

<Message>
This build is very common in PuGs. It is part of a composition called PuG meta, you can read more about it [here](/guides/meta-explained). We **recommend** to play [Heal Renegade](/builds/revenant/heal-renegade) for statics who are starting out and know the mechanics (after around 9000-15000+ <Item id="94020"/>). This recommendation is because  <Specialization name="Firebrand"/> can deal way more damage than <Specialization name="Renegade"/> (Leading to higher group DPS). However if you fail mechanics <Specialization name="Firebrand" text="Heal Firebrand"/> is a way to success.
</Message>

It provides permanent <Boon name="Quickness"/>, <Boon name="Regeneration"/>, <Boon name="Fury"/> and a decent amount of might. Exactly like the meta-counterpart it provides good offensive support via <Skill name="Bane Signet"/>, it is important to understand that the signet share is essential to faster runs and sharing extra power during <Effect name="Exposed"/> (broken Defiance bar). The main source of <Boon name="Quickness"/> is <Skill name="Restoring Reprieve"/> and <Skill name="Potent Haste"/>; <Skill name="Feel My Wrath"/> is optional.

The <Specialization name="Firebrand" text="Heal Firebrand"/> heals with any symbols, dodges, <Boon name="Regeneration"/>, <Skill name="Restoring Reprieve"/>, and if necessary <Skill name="Bow of Truth"/>. If your group is unable to stay alive, you can swap out your offensive support (<Skill name="Bane Signet"/> and radiance) to virtues for more heals, *but* it should not be needed.

When <Instability name="Afflicted"/> is present or enemies are applying conditions, you can use <Skill name="Symbol of Swiftness"/> (Staff3) and blast it with <Skill name="Holy Strike"/> (Staff2) for area condition cleanse.


If you play this build we highly recommend learning the <Skill name="Bane Signet"/> share variant. If you want a good and smooth run, take a look at the [Fractal Pages](/fractals). This class will not be doing much damage but understanding how the class works best and when to do <Skill name="Bane Signet"/> sharing is important! 

<Divider text="Equipment"/>

Note that this build variant is optimized for 150 agony resistance.  
If you have more AR, feel free to swap out harrier pieces for cleric, as long as you are maintaining 100% boon duration. Please take in mind, that this is not _THE_ gear setup you have to play, many variants work. It is all about maximizing boon duration and healing power.  
Yes, you can play full harrier - however, you will lose some healing power.

Check the [gear optimizer](http://old.discretize.eu) for more gear variants!

<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Harrier" helmRune="Monk" shouldersAffix="Harrier" shouldersRune="Monk" coatAffix="Harrier" coatRune="Monk" glovesAffix="Harrier" glovesRune="Monk" leggingsAffix="Harrier" leggingsRune="Monk" bootsAffix="Harrier" bootsRune="Monk" helmInfusionId="49432" shouldersInfusionId="49432" coatInfusionId="49432" glovesInfusionId="49432" leggingsInfusionId="49432" bootsInfusionId="49432" />
</GridItem>
 
<GridItem sm="4">
<Weapons weapon1MainType="Staff" weapon1MainAffix="Harrier" weapon1MainSigil1="Transference" weapon1MainSigil2="Concentration" weapon2MainType="Axe" weapon2MainAffix="Harrier" weapon2MainSigil1="Transference" weapon2OffType="Shield" weapon2OffAffix="Harrier" weapon2OffSigil="Concentration" weapon1MainInfusion1Id="49432" weapon2MainInfusion1Id="49432" weapon1MainInfusion2Id="49432" weapon2OffInfusionId="49432"/>
<Card title="Swap Weapons">
* Greatsword for pulling adds in Nightmare CM after MAMA.
* A hammer for <Boon name="Might"/> pre-stacking
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Cleric" accessory1Affix="Cleric" accessory2Affix="Cleric" amuletAffix="Harrier" ring1Affix="Cleric" ring2Affix="Harrier" backItemInfusion1Id="49432" backItemInfusion2Id="49432" accessory1InfusionId="49432" accessory2InfusionId="49432" ring1Infusion1Id="49432" ring1Infusion2Id="49432" ring1Infusion3Id="49432" ring2Infusion1Id="49432" ring2Infusion2Id="49432" ring2Infusion3Id="49432"/>
<Consumables food="Delicious Rice Ball" utilityId="67528" infusion="Healing +9 Agony Infusion"/>
</GridItem>

</Grid>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Radiance" traits1Selected="Right Hand Strength, Wrath of justice, Perfect Inscriptions" traits2="Honor" traits2Selected="Invigorated Bulwark, Honorable Staff, Writ of Persistence" traits3="Firebrand" traits3Selected="Liberators Vow, Weighty Terms, Loremaster"/>
 
<Card title="Situational Traits">
| | |
| -- | -- |
| <Trait name="Pure of heart" size="big" disableText/> | In some T4s with a lot of attacking enemies it can be beneficial to bring this trait. This trait trades <Boon name="Might"/> for more heals. |
## Wheelchair
In case your team downs frequently and is unable to handle mechanics correctly, you can swap radiance for virtues. This however is **not** the default build and should only be played under extreme circumstances, like very bad instability combos or beginner groups.
<Traits unembossed traits1Id="46" traits1="Virtues"  traits1SelectedIds="625, 610, 554"/>

</Card>
</GridItem>

<GridItem sm="5">
<Skills heal="Mantra of Solace" utility1="Mantra of Potence" utility3="Bane Signet" elite="Feel my Wrath"/>

<Card title="Situational Skills">
| | |
| -- | -- |
| <Skill id="45460" size="big" disableText/> | A strong condition cleanse to counterplay <Instability name="Afflicted"/>. |
| <Skill name="Mantra of Liberation" size="big" disableText/> | For extra <Boon name="Stability"/> for skips. Only use in combat if <Boon name="Fury"/> and <Boon name="Quickness"/> are covered. |
| <Skill id="9246" size="big" disableText/> | A 1,200 range teleport to an ally. Can be used to blink to a <Skill id="9168"/>.|
| <Skill id="9247" size="big" disableText/> | A 1,200 range teleport to an enemy. Very handy for some skips. |
| <Skill name="Hallowed Ground" size="big" disableText/> | Can be used where <Boon name="Stability"/> or stun break is needed. Preferred over <Skill id="9153"/>. |
| <Skill id="9153" size="big" disableText/> | Can be used where <Boon name="Stability"/> or stun break is needed. |
| <Skill id="9175" size="big" disableText/> | A strong AOE heal and condi cleanse on blast combo. |
| <Skill id="9125" size="big" disableText/> | Deals an additional 200 defiance bar damage. |
| <Skill id="9251" size="big" disableText/> | A stationary reflect lasting for 10 seconds. Can be used to counterplay <Instability name="We Bleed Fire"/>.|
| <Skill name="Sanctuary" size="big" disableText/> | A slow but strong CC skill. Also destroys projectiles inside. |
</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="12">
<Card title="Skill Usage">
Prestacking:
- Drop a _Fire Field_ with <Skill name="44364"/> - Skill 4
- Press <Skill name="Empower"/>
- Press <Skill name="Restoring Reprieve"/> and <Skill name="Potent Haste"/> each twice; press <Skill name="Feel My Wrath"/>
- Take mistlock 
- Press <Skill name="Empower"/> again

To keep up <Boon name="Quickness"/>:
- Use <Skill name="Restoring Reprieve"/> and <Skill name="Potent Haste"/> but leave one charge left (unless the fight is close to being over)
- Only use these skills close to your allies - try to "puke" on them with the mantras

To keep up <Boon name="Might"/> and <Boon name="Fury"/>:

- Always prestack <Boon name="Might"/> on the mistlock!
- You can press <Skill name="Symbol of Vengeance"/> (Axe2) two times before your <Skill name="Empower"/> (Staff 4) if off cooldown again.
- You wanna maximize the uptime of <Skill name="Symbol of Vengeance"/> while pressing <Skill name="Empower"/> off cooldown.

CCing:

- Always use <Skill name="Bane Signet"/>! This is one of the most important things you have to do!
- Use <Skill name="Blazing Edge"/> (Axe3)
- Use <Skill name="Shield of Absorption"/> (Shield5)
- On demand: <Skill name="Sanctuary"/>

Tomes are very useful when no other skills are ready. <Skill name="Tome of Justice"/> also gets refreshed every time an enemy dies (works with anomalies at Artsariiv/Arkk, knights at MAMA and hallucinations at Siax).

<Skill name="Tome of Courage"/> and <Skill name="Tome of Resolve"/> are great for high incoming damage scenarios.

- <Skill name="Tome of Justice"/> (F1):
  - Skill 4 is a ticking AoE, good for single target and great for AoE DPS, five stacks of <Condition name="Burning"/>
  - Skill 5 makes your surrounding allies inflict <Condition name="Burning"/> - your main source of damage
  - Skill 3 is an AoE pull (150 defiance bar damage)
- <Skill name="Tome of Resolve"/> (F2):
  - Skill 2 is a party condition cleanse
  - Skill 3 grants <Boon name="Vigor"/>, <Boon name="Regeneration"/> and <Boon name="Swiftness"/>
  - Skill 4 is a good party heal
  - Skill 5 increases healing on allies for 8s by 33% and converts up to 5 conditions to boons
- <Skill name="Tome of Courage"/> (F3):
  - Skill 1 grants <Boon name="Stability"/> and <Boon name="Swiftness"/>
  - Skill 3 is a 5s reflect
  - Skill 4 grants <Boon name="Resistance"/> and breaks stun
  - Skill 5 grants <Boon name="Aegis"/>, <Boon name="Protection"/>, <Boon name="Stability"/> and 300 toughness for 5 seconds

</Card>

</GridItem>

<GridItem>
<Card title="CC skills">
| | |
| -- | -- |
| <Skill name="Blazing Edge"/> | 150 damage |
| <Skill name="Shield of Absorption"/> | 150 damage |
| <Skill name="Bane Signet"/> | 300 damage |
</Card>
</GridItem>
<GridItem>
<Message>
This guide is good for people who want to start fractals with heal firebrand. We still highly recommend running the Radiance/Honor build variant from our Build section so you start playing with the proper build!
</Message>
<Video youtube="oigZbGyQvbQ" title="In-depth build guide by Rheyo"/>
</GridItem>
</Grid>
