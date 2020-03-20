---
title: 'Power Dragonhunter'
date: '2020-03-20'
rating: 'Offmeta'
role: 'Damage'
profession: 'Guardian'
specialization: 'Dragonhunter'
benchmark:
  { large: { dps: 35340, by: 'Shetsa [SC]', youtube: 'ioA6ux3AC3Q' } }
skills: [30783, 30039, 9153, 9251]
boons: ['Retaliation', 'Aegis']
conditions: ['Vulnerability', 'Blind', 'Crippled']
code: '[&DQEQLyo6GzkmDyYPihItAUgBSAH+AP4AtRJxEgAAAAAAAAAAAAAAAAAAAAA=]'
---
<Tabs>

<Tab title="Build">

The <Specialization name="dragonhunter" text="Power Dragonhunter"/> is currently a good and easy to play build for fractals. It has great burst options and deals high consistent damage while providing good defiance bar damage and <Condition name="vulnerability"/>.

The build also offers strong on-demand party support with <Skill id="30039"/> and reflects like <Skill id="9251"/>.

It benefits from slaying potions such as <Item id="50082"/> and <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>
<Tabs>
<Tab title="150 AR">
Check the [gear optimizer](http://old.discretize.eu) for more gear variants!
<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Assassin" shouldersRune="Scholar" coatAffix="Assassin" coatRune="Scholar" glovesAffix="Assassin" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Assassin" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainId="46762" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24868" weapon1MainType="Greatsword" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact" weapon2MainId="46769" weapon2MainSigil1Id="24615" weapon2MainType="Scepter" weapon2MainAffix="Berserker" weapon2MainSigil1="Force" weapon2OffId="46761" weapon2OffSigilId="24868" weapon2OffType="Focus" weapon2OffAffix="Berserker" weapon2OffSigil="Impact"/>

<Card title="Alternative weapons">
- Greatswords and Scepters/Swords with <Item name="Night" type="Sigil" disableText/>/<Item name="impact" type="Sigil" disableText/> and <Item name="Serpent Slaying" type="Sigil" disableText/>/<Item name="Impact" type="Sigil" disableText/>
- Greatswords and foci with (see [Consumables Guide](/guides/consumables))
- Hammer for <Boon name="might"/> stacking
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemId="49390" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="77569" infusionId="37131"/>

<Card title="Notes">
If you use <Trait name="Perfectinscriptions"/> you are lacking crit chance, therefore the assassins pieces. You can of course mitigate this by increasing your agony resistance. 

It is not recommended to run <Trait name="Righthandstrength"/> unless you have multiple <Specialization name="guardian"/> or another source of <Boon name="Retaliation"/>.
</Card>
</GridItem>
</Grid>
</Tab>

<Tab title="203 AR">
Check the [gear optimizer](http://old.discretize.eu) for more gear variants!
<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Berserker" helmRune="Scholar" shouldersAffix="Berserker" shouldersRune="Scholar" coatAffix="Berserker" coatRune="Scholar" glovesAffix="Berserker" glovesRune="Scholar" leggingsAffix="Berserker" leggingsRune="Scholar" bootsAffix="Berserker" bootsRune="Scholar"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainId="46762" weapon1MainSigil1Id="24615" weapon1MainSigil2Id="24868" weapon1MainType="Greatsword" weapon1MainAffix="Berserker" weapon1MainSigil1="Force" weapon1MainSigil2="Impact" weapon2MainId="46769" weapon2MainSigil1Id="24615" weapon2MainType="Scepter" weapon2MainAffix="Berserker" weapon2MainSigil1="Force" weapon2OffId="46761" weapon2OffSigilId="24868" weapon2OffType="Focus" weapon2OffAffix="Berserker" weapon2OffSigil="Impact"/>

<Card title="Alternative weapons">
- Greatswords and Scepters/Swords with <Item name="Night" type="Sigil" disableText/>/<Item name="impact" type="Sigil" disableText/> and <Item name="Serpent Slaying" type="Sigil" disableText/>/<Item name="Impact" type="Sigil" disableText/>
- Greatswords and foci with (see [Consumables Guide](/guides/consumables))
- Hammer for <Boon name="might"/> stacking
</Card>
</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemId="49390" backItemAffix="Berserker" accessory1Id="39233" accessory1Affix="Berserker" accessory2Id="39232" accessory2Affix="Berserker" amuletId="39273" amuletAffix="Berserker" ring1Id="75669" ring1Affix="Berserker" ring2Id="76024" ring2Affix="Berserker"/>

<Consumables foodId="41569" utilityId="77569" infusionId="37131"/>
</GridItem>
</Grid>
</Tab>
</Tabs>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="16" traits1="Radiance" traits1SelectedIds="574,565,579" traits2Id="42" traits2="Zeal" traits2SelectedIds="634,653,2017" traits3Id="27" traits3="Dragonhunter" traits3SelectedIds="1898,1835,1955"/>
</GridItem>

<GridItem sm="5">
<Skills healId="21664" utility1Id="30364" utility2Id="9168" utility3Id="9093" eliteId="30273"/>

<Card title="Situational">
| | |
| -- | -- |
| <Skill id="9102" size="big" disableText/> | A two seconds block. Can be stowed, but only blocks without heal then.
| <Skill id="29965" size="big" disableText/> | When your team lacks <Boon name="quickness"/>.|
| <Skill id="9246" size="big" disableText/> | A 1,200 range teleport to an ally. Can be used to blink to a <Skill id="9168"/>.|
| <Skill id="9247" size="big" disableText/> | A 1,200 range teleport to an enemy. Very handy for some skips. |
| <Skill name="Hallowed Ground" size="big" disableText/> | Can be used where <Boon name="stability"/> or stunbreak is needed. Preferred over <Skill id="9153"/>. |
| <Skill id="9153" size="big" disableText/> | Can be used where <Boon name="stability"/> or stunbreak is needed. |
| <Skill id="9125" size="big" disableText/> | Deals additional 200 defiance bar damage. |
| <Skill id="41571" size="big" disableText/> | A 5 seconds projectile absorb. Good to counterplay  <Instability name="We bleed fire"/> in case your team sucks.
| <Skill id="9251" size="big" disableText/> | A stationary reflect lasting 10 seconds. Can be used to counterplay <Instability name="We bleed fire"/>.|
| <Skill name="Sanctuary" size="big" disableText/> | A slow but strong CC skill. Also destroys projectiles inside <Instability name="We bleed fire"/>. |
</Card>
</GridItem>
</Grid>
</Tab>

<Tab title="Guide">
<Divider text="Details"/>

<Grid>
<GridItem sm="7">
<Card title="Rotation">
**Scepter Rotation:**
1. <Skill name="banesignet" profession="guardian"/>
1. <Skill name="Symbol of Punishment" profession="guardian"/> (Scepter 2)
1. <Skill name="Ray of Judgment" profession="guardian"/> (Focus 4)
1. <Skill name="Shield of Wrath" profession="guardian"/> (Focus 5)
1. **Weapon Swap**
1. <Skill name="Sword of Justice" profession="guardian"/>
1. <Skill name="Procession of Blades " profession="guardian"/> 
1. <Skill name="Spear of Justice" profession="guardian"/> (F1)
1. <Skill name="Symbol of Wrath " profession="guardian"/> (GS 4)
1. <Skill name="Whirling Wrath" profession="guardian"/> (GS 2)
1.  <Skill name="Sword of Justice" profession="guardian"/> 
1. <Skill name="Dragons Maw" profession="guardian"/>
1.  <Skill name="Sword of Justice" profession="guardian"/>
1.  <Skill name="Leap of Faith" profession="guardian"/> (GS 3)
1.  <Skill name="Binding Blade" profession="guardian"/> (GS 5)
1. If the phase lasts longer than this, continue with the SC rotation. 
</Card>
</GridItem>

<GridItem sm="5">
<Card title="CC skills">
| | |
| -- | -- |
| <Skill id="9093"/> | 300 damage |
| <Skill id="9226"/> (after <Skill id="9147"/>) | 150 damage |
| <Skill id="33134"/> (after <Skill id="29887"/>) | 150 damage |
| <Skill id="30273"/> | 150 damage |
</Card>
</GridItem>

<GridItem sm="7">
<Card title="Notes">
* Always start on scepter/sword
* Delay swapping to GS until the CC-bar is about to be broken. This is especially important at ensolyss without insta CC. 
* Always cast your <Skill name="whirlingwrath"/> inside the hitbox to get the additional hits. 
* Always cast your <Skill name="bindingblade"/> inside the hitbox to get the additional hits.
* Dont interrupt your GS auto-attack chain
* In certain scenarios (precasting traps, starting with <Skill name="onewolfpack"/>) it can be benifical to get your <Skill name="spearofjustice"/> out first.)
* Use <Skill id="9098"/> after <Skill id="9090"/> to cancel the aftercast
* Dont waste your key skills on meaningless adds
* Scepter is stronger than sword when you use just the symbol

</Card>
</GridItem>

</Grid>
</Tab>

<Tab title="99CM">
<Divider text="Nightmare"/>
- Please check the [CC distribution](/guides/cc-distribution) to contribute your share of the necessary CC!
- Please also read through the [nightmare fractal page](/fractals/nightmare) for general encounter information!
<Tabs>
<Tab title="Mama">
### **General**
- Do not use traps on the adds
- Strategically cast your <Skill name="banesignet"/> 
- Start on Scepter/Sword
- Use <Skill name="binding blade"/> inside MAMAs hitbox, when the small adds are coming close
- Check with your team if you are using <Skill name="Feelmywrath"/>

### **Precast**
- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the first add and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- (Use <Skill name="Feelmywrath"/> - depends on your precast)
- Take the mistlock.

### **1st Phase**
- Drop a <Skill name="symbolofpunishment"/>
- Swap
- <Skill name="processionofblades"/>, <Skill name="spearofjustice"/>
- <Skill name="Symbolofwrath"/>, <Skill name="Whirlingwrath"/>
</Tab>

<Tab title="Siax">
**tl;dr**
- Use your <Skill name="Binding Blade"/> inside Siax' hitbox to get 5 additional hits. This is the reason why <Specialization name="guardian"/> is very strong at this boss. Do not miss this.
- Save some <Skill id="9168"/> for a quicker add kill. 
- It is beneficial to take a sword here to quickly blink to the add.
- Use <Skill name="Wings of resolve"/> to navigate around and keep your HP up.
- Use <Skill name="Bane Signet"/> to help with CC and buff your party.
- Use <Skill name="shieldofwrath"/> and <Skill name="Shieldofcourage"/> to block the expanding AoEs.
- Check with your team if you take <Skill name="Feelmywrath"/>

---

### **Precast**
- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the boss and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- Take the mistlock.
- You can precast <Skill id="29789"/> (LB4), <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss if you are using a portal.

### **100%-66%**
Your gameplay is heavily influenced by the dps your team can pull. If your team has very high dps (phases Siax in >5s) you wanna precast <Skill name="Bane Signet"/> and fire everything you have as soon as you are getting in combat.   
No matter what group you are running with, start on scepter/sword! If you are running in a PuG or just clear it daily, it is beneficial to delay your traps slightly, to fit more of the hits into the cc bar. In a fast team save <Skill name="bindingblade"/> for the 2nd phase when the adds spawn, if not use it. Just make sure to press it when the adds are in range for big dps.

### *1st Add*
- Use <Skill name="spearofjustice"/> on your add for the modifier from <Trait name="biggamehunter"/>. 
- <Skill name="Whirling wrath"/> and a couple AA to kill it.
- Use <Skill name="wingsofresolve"/>, <Skill name="Symbol of blades"/> and <Skill name="Leapoffaith"/> for movement.

### **66%-33%**
Nothing extraordinary, all information from 100-66 and tl;dr are still valid. Try to end on scepter/sword.

### *2nd Add*
- Use <Skill name="spearofjustice"/> on your add for the modifier from <Trait name="biggamehunter"/>. 
- Kill it with a symbol and AAs.
- In fast runs you might wanna save a <Skill name="Swordofjustice"/>.

### **33%-0%**
Nothing extraordinary, all information from 100-66 and tl;dr are still valid. Try to end on scepter/sword.
</Tab>

<Tab title="Ensolyss">
WIP
</Tab>

</Tabs>
</Tab>
<Tab title="100CM">
<Divider text="Shattered Observatory"/>
- Please check the [CC distribution](/guides/cc-distribution) to contribute your share of the necessary CC!
- Please also read through the [shattered observatory fractal page](/fractals/shattered-observatory) for general encounter information!
<Tabs>
<Tab title="Skorvald">
### **Precast**
- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the boss and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- Use <Skill name="Feelmywrath"/>.
- Take the mistlock.
- You can precast <Skill id="29789"/> (LB4), <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss.

### **Burn phases**
Your gameplay is heavily influenced by the dps your team can pull. If your team has very high dps (phases Skorvald >5s) you wanna precast <Skill name="Bane Signet"/> and fire everything you have as soon as you are getting in combat.

### **Adds**
You can kill the first two adds with greatsword. You can use traps on the 2nd add, without having them on cooldown when you are back at Skorvald. Make sure, that you are on scepter/sword at the last add and you are not having cooldown on the weapon swap, or you DPS will suffer a lot. You can freely use Traps and GS on the first two adds. Swap to scepter/sword after that.

</Tab>
<Tab title="Artsariiv">
### **General**
- If your team does not have a <Specialization name="soulbeast"/>, you can take <Skill name="Wall of reflection"/> for omega reflects. 
- Use <Skill name="shieldofcourage"/> and <Skill name="shieldofwrath"/> strategically to block the knockbacking attacks.
- Save a Skill name="shieldofcourage"/> or <Skill name="shieldofwrath"/> for the expanding AoE so you can deal continues DPS during the mid burn.

### **Precast**
- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the boss and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- Use <Skill name="Feelmywrath"/>.
- Take the mistlock.
- You can precast <Skill id="29789"/> (LB4), <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss in a coordinated team.

### **100%**
- If you are not skipping the first Anomaly, you should place the <Skill name="wallofreflection"/> in the middle.  
- Again it is recommended to start on scepter or sword. 
- Use your <Skill name="Bane Signet"/> to help with CC and boost the party dps as soon as Artsariiv arrives at the corners. 
- Always use <Skill name="Bindingblade"/> and <Skill name="Whirlingwrath"/> inside Artsariivs hitbox for big damage.

### *Adds*
- Help your team CCing with [consumables](/guides/consumables). 
- Swap to scepter and camp it to be ready for the mid burst.
- Do not waste your bane signet or <Skill name="Binding Blade"/> (GS5) for this. 
- Use your special action key to quickly navigate to adds. 

### **66% and 33%**
- When all adds are broken, your traps will be off cooldown again. 
- Start on scepter again, use <Skill name="Shield of Wrath"/> to block the expanding AoE and fire everything you have.  
- When Artsariiv arrives at the corners again immediately place your <Skill name="Wall of reflection"/>.
</Tab>

<Tab title="Arkk">
### **General**  
- Play scepter here!
- Good teams: start on scepter/sword, so that you are on scepter during the bloom phase.
- Bad teams: start on greatsword and do SC rotation
- Your goal is to start on scepter/sword at every 10% burn phase, that is why you need to consider weapon swaps carefully. 
- Pull adds in with GS5. 
- Cast <Skill name="Bane Signet"/> early, so you get more DPS time. 
- The fastest way to do the blooms is to walk into the lightning and auto attack with scepter. Use <Skill name="Wings of Resolve"/> to regain health. 
- Use <Skill name="binding blade"/> inside Arkks hitbox when adds are present.

### **Precast**
- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the boss and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- Use <Skill name="Feelmywrath"/>.
- Take the mistlock.
- You can precast <Skill id="29789"/> (LB4), <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss if you are using a portal.
</Tab>
</Tabs>
</Tab>

</Tabs>
