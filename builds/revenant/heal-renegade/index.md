---
title: 'Heal Renegade'
date: '2019-09-04'
rating: 'Great'
role: 'Support'
profession: 'Revenant'
specialization: 'Renegade'
skills: [45773, 44076, 27025, 45686, 27505]
traits: [1802, 1814]
boons: ['Alacrity', 'Might', 'Stability','Regeneration']
conditions: ['Vulnerability']
code: '[&DQkMPw8ePz/cEdwRBhIGEisS1BHUESsSyhHKERESDwAAAAAAAAAAAAAAAAA=]'
---

For **<Specialization text="Heal Renegade" name="Renegade"/>** we have chosen Harrier and Cleric for maximum power and healing power while while still hitting 100% boon duration because <Skill name="Soulcleaves Summit" /> deals damage and lifesteals based on the **<Specialization text="Heal Renegade" name="Renegade"/>**'s own power and healing power.
Feel free to run full Harrier if you are confident that you don't need the extra healing power or toughness from Cleric. the more agony resistance you have, the more Cleric you can afford to run and still  hit 100% boon duration.


<Divider text="Equipment"/>
<Tabs outlined>
<Tab title="150 Agony Resistance">
<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Harrier" helmRune="Monk" shouldersAffix="Harrier" shouldersRune="Monk" coatAffix="Harrier" coatRune="Monk" glovesAffix="Harrier" glovesRune="Monk" leggingsAffix="Harrier" leggingsRune="Monk" bootsAffix="Harrier" bootsRune="Monk"/>
</GridItem>
 
<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Harrier" weapon1MainSigil1="Transference" weapon1OffType="Sword" weapon1OffAffix="Harrier" weapon1OffSigil="Concentration" weapon2MainType="Staff" weapon2MainAffix="Harrier" weapon2MainSigil1="Transference" weapon2MainSigil2="Concentration"/>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Harrier" accessory1Affix="Cleric" accessory2Affix="Cleric" amuletAffix="Harrier" ring1Affix="Harrier" ring2Affix="Harrier"/>

<Consumables food="Delicious Rice Ball" utilityId="67528" infusion="Healing +9 Agony Infusion"/>
</GridItem>
</Grid>


<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Salvation" traits1Selected="Tranquil Balance,Invoking Harmony,Selfless Amplification" traits2="Devastation" traits2Selected="Unsuspecting Strikes,Assassins Presence,Swift Termination" traits3="Renegade" traits3Selected="Wrought-Iron Will,All for One,Righteous Rebel"/>

<Card title="Second trait variant">
**If you feel your energy runs out too quick, we recommend the Salvation/Incovation variant.**
</Card>

<Traits traits1="Salvation" traits1Selected="Tranquil Balance,Invoking Harmony,Selfless Amplification" traits2="Invocation" traits2Selected="Rising Tide,Spirit Boon,Charged Mists" traits3="Renegade" traits3Selected="Wrought-Iron Will,All for One,Righteous Rebel"/>
 
</GridItem>

<GridItem sm="5">

**Your two base legends are <Skill id="41858"/> and <Skill name="Legendary Centaur Stance"/>**

With <Skill id="41858"/>:

<Skills heal="Breakrazors Bastion" utility1="Razorclaws Rage" utility2="Darkrazors Daring" utility3="Icerazors Ire" elite="Soulcleaves Summit"/>

---

With <Skill name="Legendary Centaur Stance"/>:

<Skills heal="Project Tranquility" utility1=" Protective Solace" utility2=" Natural Harmony" utility3="Purifying Essence" elite="Energy Expulsion"/>

---



If <Instability name="No Pain, No Gain"/> is present, swap <Skill name="Legendary Centaur Stance"/> to <Skill id="28494"/>:

<Skills heal="Empowering Misery" utility1="Pain Absorption" utility2="Banish Enchantment" utility3="Call to anguish" elite="Embrace the Darkness"/>
</GridItem>
</Grid>

<Divider text="Details"/>

<Grid>
<GridItem sm="8">
<Card title="Skill Usage">
The general list of priorities looks like this:

- Grant <Boon name="Alacrity"/> to your allies by using <Skill name="Orders from Above"/> near them whenever it's ready
- Provide group <Boon name="Might"/> with <Skill name="Heroic Command"/> when it's below 25 stacks
- Break defiance bars with <Skill name="Surge of the Mists"/> (Staff 5)
- Maximize <Skill name="Soulcleaves Summit"/> uptime on the group
- Spam 111 on Sword (using anything else is usually a party DPS loss)
- Spam 111 on Staff if you need extra heal.
- Use <Skill name="Renewing Wave"/> (Staff 4) if you are in need of condition cleanse.

You'll always want to use <Skill id="41858"/> as your first legend:

- <Skill name="Breakrazors Bastion"/> is a strong group heal
- <Skill name="Darkrazors Daring"/> is a slow but strong CC
- <Skill name="Soulcleaves Summit"/> is a really strong group DPS buff, use it shortly before defiance bars break

Use <Skill name="Legendary Centaur Stance"/>: as your second legend:

- <Skill name="Protective Solace"/> is a barrier, good for absorbing projectiles
- <Skill name="Purifying Essence"/> is a condition cleanse and heal
- <Skill name="Natural Harmony"/> is a strong heal and grants <Boon name="Alacrity"/> if traited with <Trait name="Serene Rejuvenation"/>
- <Skill name="Energy Expulsion"/> is a small CC, creates heal orbs and a fast energy burst if you need to swap back to other legend for 75 energy if traited with <Trait name="Charged Mists"/>)


If <Instability name="No Pain, No Gain"/>, <Instability name="Vengeance"/> or other sources of boons on enemies are present you will swap <Skill name="Legendary Centaur Stance"/> to <Skill id="28494"/> as your second legend:

- <Skill name="Pain Absorption"/> applies <Boon name="resistance"/> and acts as a stunbreak
- <Skill name="Banish Enchantment"/> strips three boons on up to five targets
</Card>
</GridItem>

<GridItem sm="4">
<Card title="Defiance Bar Damage">
| | |
| -- | -- |
| <Skill name="Surge of the Mists" size="big" disableText/> | 3-6x150 with <Control name="knockback"/> |
| <Skill name="Darkrazors Daring" size="big" disableText/> | 6x100 with <Control name="daze"/> |
</Card>
</GridItem>
</Grid>
