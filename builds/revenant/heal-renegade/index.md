---
title: 'Heal Renegade'
date: '2020-03-28'
rating: 'Offmeta'
role: 'Support'
profession: 'Revenant'
specialization: 'Renegade'
skills: [45773, 44076, 27025, 45686, 27505]
traits: [1786, 1814]
boons: ['Alacrity', 'Might', 'Stability', 'Regeneration', 'Resistance', 'Protection']
conditions: ['Vulnerability']
code: '[&DQkPJgw/Pz/cEdwRBhLUESsSBhLUESsSyhHKERIRDw4GEtQRKxIAAAAAAAA=]'
author: 'Janitsu.6284'
---
<Tabs>
<Tab title="Build">
The **<Specialization text="Heal Renegade" name="Renegade"/>** plays with a mix of harrier's and cleric's gear for maximum power and healing power while still hitting 100% boon duration.
 
Since the damage and life steals of <Skill name="Soulcleaves Summit" /> are based on the **<Specialization text="Heal Renegade" name="Renegade"/>**'s own power and healing power, the <Specialization text="Heal Renegade" name="Renegade"/> aims to maximize those stats.

Feel free to run full Harrier if you are confident that you don't need the extra healing power or toughness from cleric. The more agony resistance you have, the more cleric you can afford to run and still hit 100% boon duration.

<Divider text="Equipment"/>

<Tabs outlined>

<Tab title="150 Agony Resistance">
Check the [gear optimizer](https://old.discretize.eu) for more gear variants!
<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Harrier" helmRune="Monk" shouldersAffix="Harrier" shouldersRune="Monk" coatAffix="Harrier" coatRune="Monk" glovesAffix="Harrier" glovesRune="Monk" leggingsAffix="Harrier" leggingsRune="Monk" bootsAffix="Harrier" bootsRune="Monk"/>
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Harrier" weapon1MainSigil1="Transference" weapon1OffType="Sword" weapon1OffAffix="Harrier" weapon1OffSigil="Concentration" weapon2MainType="Staff" weapon2MainAffix="Harrier" weapon2MainSigil1="Transference" weapon2MainSigil2="Concentration"/>
<Consumables foodId="68634" utilityId="67528" infusionId="37125"/>

</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Harrier" accessory1Affix="Cleric" accessory2Affix="Cleric" amuletAffix="Harrier" ring1Affix="Harrier" ring2Affix="Harrier"/>
<Card title="Swap Weapons">
* Hammer for some skips (most of them require <Item name="whitemantleportaldevice"/>)
* Hammer and main-hand mace can be used for might blasting in groups that do not prestack might properly.
</Card>

</GridItem>
</Grid>
</Tab>
</Tabs>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Salvation" traits1Selected="Tranquil Balance,Invoking Harmony,Selfless Amplification" traits2="Devastation" traits2Selected="Unsuspecting Strikes,Assassins Presence,Swift Termination" traits3="Renegade" traits3Selected="Wrought-Iron Will,All for One,Righteous Rebel"/>
<Card title="Second trait variant">
If you run out of energy too quickly, we recommend the Salvation/Invocation variant. This variant is also better for fractals where <Trait name="Assassins Presence"/> doesn't help your party. This would include fractals where damage is time-gated and where you can't critically hit the enemies that matter.

You should consider running this trait variant in fractals like Molten Furnace and Captain Mai Trin.

Swap Devastation with this line:
<UnembossedTraits traits1Id="3" traits1="Invocation" traits1SelectedIds="1761,1774,1791"/>

Template code:

`[&DQkDJgw/Pz/cEdwRBhLUESsSBhLUESsSyhHKERIRDw4GEtQRKxIAAAAAAAA=]`
</Card>
</GridItem>

<GridItem sm="4">
<Card title="Legends">
<Skill name="Legendary Renegade Stance" size="big"/>
<Skill name="Legendary Centaur Stance" size="big"/>
<Skill name="Legendary Dwarf Stance" size="big"/>
<Skill name="Legendary Demon Stance" size="big"/>
</Card>
</GridItem>
</Grid>
</Tab>

<Tab title="Guide">
<Divider text="Guide"/>

<Grid>
<GridItem sm="12">
<Card title="Abilities">
**Citadel Order Skills**

- <Skill name="Heroic Command"/> -  Share two stacks of <Boon name="Might"/> for each <Effect name="Kallas Fervor"/> stack.
- <Skill name="Citadel Bombardment"/> - Fire ten missiles that inflict high damage, and <Condition name="Burning"/>.
- <Skill name="Orders from Above"/> - Share four pulses of <Boon name="Alacrity"/>.

---

**Sword Skills**

- <Skill name="Preparation Thrust"/> - The autoattack chain cleaves and provides <Condition name="Vulnerability"/> on the two first attacks. The third attack creates an exploding rift on upto three targets, with each explosion hitting three targets. Potentially hitting nine times.
- <Skill name="Chilling Isolation"/> - High damage skill with low cooldown and energy cost, also provides <Condition name="Chilled"/>. The second attack deals increased damage to isolated enemies.
- <Skill name="Unrelenting Assault"/> - A two second evade that also provides <Boon name="Might"/> to oneself.
- <Skill name="Shackling Wave"/> - High damage skill, however should be used in key moments due to the energy cost, cooldown, and application of <Condition name="Vulnerability"/>.
- <Skill name="Death strike"/> - Shadowsteps to target, grants two hits with decent damage. Should be used in key moments, unless energy and timing allows it to be used for damage.

**Staff Skills**

- <Skill name="Rapid Swipe"/> - The autoattack chain cleaves and the last hit provides a decent amount of healing to allies.
- <Skill name="Menders Rebuke"/> - Provides <Condition name="Vulnerability"/> and a small amount of healing to allies.
- <Skill name="Warding Rift"/> - A two second block that <Condition name="Blind"/> foes.
- <Skill name="Renewing Wave"/> - Provides a blast for a combo field, cleanses two conditions and heals allies for a fairly large amount.
- <Skill name="Surge of the Mists"/> - The strongest Crowd Control skill in your arsenal, which grants between three and nine hits of <Effect name="Knockback"/>.

---

**Notable Traits**

- <Trait name="Charged Mists"/> - Grant 25 more energy when you swap Legends below 10 energy.
- <Trait name="Tranquil Balance"/> - When you are above the health threshold your healing to allies is increased.
- <Trait name="Invoking Harmony"/> - When you invoke another legend, your healing is increased for 10 seconds.
- <Trait name="Serene Rejuvenation"/> - When you heal with <Skill name="Natural Harmony"/> you also apply <Boon name="Alacrity"/> to allies near the tablet.
- <Trait name="Lasting Legacy"/> - <Skill name="Heroic Command"/> shares more stacks of <Boon name="Might"/> and the duration is increased with 50%.
- <Trait name="Righteous Rebel"/> - The duration of <Boon name="Alacrity"/> shared from <Skill name="Orders from Above"/> is increased with 50%.

</Card>
</GridItem>
</Grid>

<Grid>
<GridItem sm="12">
<Card title="Legends">

<Message>
You will need to reconsider the legends you are running in almost every fractal and therefore it is a nice habit to develop to check them after each fractal you have done. Some fractals demand three to four different legends in only one fractal. Below you will find the three most common setups that will serve you fine as well as description of the skills in each legend.
</Message>

## Legends Setups:

1. **<Skill name="Legendary Renegade Stance"/>** and **<Skill name="Legendary Centaur Stance"/>**
   - This is you most used setup that has the most healing output as well as a projectile block and extra condition cleanse.
2. **<Skill name="Legendary Renegade Stance"/>** and **<Skill name="Legendary Demon Stance"/>**
   - This is a specific setup for the instability <Effect name="No Pain, No Gain"/> and for when you want to increase your damage output on bosses that generate <Boon name="Protection"/> on themselves or when you need to pull adds using <Skill name="Call to Anguish"/>.
3. **<Skill name="Legendary Renegade Stance"/>** and **<Skill name="Legendary Dwarf Stance"/>**
   - This is the setup you want to use on a few CM bosses (Skorvald and Artsariiv) as well as some fractals (Chaos last boss, possibly in Siren's Reef).

---

**<Skill name="Legendary Renegade Stance"/>**

- <Skill name="Breakrazors Bastion"/> - Summons a spirit that heals you on cast and pulses heal to allies in an area around it. Reduces damages from conditions by 50%.
- <Skill name="Razorclaws Rage"/> - Summons a spirit that causes your party to inflict <Condition name="Bleeding"/> on attack.
- <Skill name="Darkrazors Daring"/> - Summons a spirit that <Control name="Daze"/>s enemies in an area around it for ¼ seconds once per second for six seconds.
- <Skill name="Icerazors Ire"/> -  Summons a spirit that deals high damage to enemies around it and inflicts <Condition name="Vulnerability"> on the targets.
- <Skill name="Soulcleaves Summit"/> - Summons a spirit that enchants your party's attacks with life steal. Increases damage dealth by your party while healing them for each attack.

---

**<Skill name="Legendary Centaur Stance"/>**

- <Skill name="Project Tranquility"/> - Summon Ventari's Tablet which heals nearby allies every few seconds.
- <Skill name="Ventaris Will"/> - Move Ventari's Tablet to the target location.
- <Skill name="Protective Solace"/> - **Toggle:** Summons a protective barrier that **absorbs** (not reflect) projectiles around the tablet.
- <Skill name="Natural Harmony"/> - Heals the party for a decent amount around the tablet.
- <Skill name="Purifying Essence"/> - Cleanses three conditions from allies near the tablet and heals per condition cleansed.
- <Skill name="Energy Expulsion"/> - Drains your remaining energy to explode Ventari's Tablet. Cleanses one condition per 10 energy drained. Ventari's Tablet shatters into smaller fragments that can be picked up by allies for a small heal.

---

**<Skill name="Legendary Demon Stance"/>**

- <Skill name="Empowering Misery"/> - A decent self-heal that heals more for each unique condition on you.
- <Skill name="Pain Absorption"/> - Draw one condition from nearby allies and provide <Boon name="Resistance"/> to your party. Also works as a stunbreak.
- <Skill name="Banish Enchantment"/> - Removes three boons from enemies in a line up to five unique enemies and causes <Condition name="Chilled"/> on enemies hit.
- <Skill name="Call to Anguish"/> - Jump to a location and pull five nearby enemies to your location inflicting <Condition name="Chilled"/> on them.
- <Skill name="Embrace the Darkness"/> - **Toggle:** Deal damage to nearby enemies and pulse <Condition name="Torment"/> to them. Drains energy when toggled on.

---

**<Skill name="Legendary Dwarf Stance"/>**

- <Skill name="Soothing Stone"/> - Powerful self heal and condition removal.
- <Skill name="Inspiring Reinforcement"/> - Grant <Boon name="Stability"/> to your party and inflict <Condition name="Weakness"/> and damage to enemies standing in the field.
- <Skill name="Forced Engagement"/> - Shoot out a chain to your target that applies <Condition name="Taunt"/> and <Condition name="Slow"/> to your target and four nearby enemies.
- <Skill name="Vengeful Hammers"/> - **Toggle:** Summon hammers to spin around you dealing damage to nearby enemies while draining your energy.
- <Skill name="Rite of the Great Dwarf"/> - Stunbreak, which reduces incoming damage by 50% for your party.

</Card>
</GridItem>
</Grid>

<Grid>
<GridItem sm="12">
<Card title="Defiance Bar">

**Hard Crowd Control**

- <Skill name="Surge of the Mists"/> - Up to nine hits of 150 <Control name="Knockback"/>.
- <Skill name="Darkrazors Daring"/> - Up to six hits of 100 <Control name="Daze"/>.
- <Skill name="Jade Winds"/> - 300 <Control name="Stun"/>.
- <Skill name="Call to Anguish"/> - 150 <Control name="Pull"/>.


**Soft Crowd Control**

- <Skill name="Chilling Isolation"/> - <Condition name="Chilled"/> for 33 per second.
- <Skill name="Shackling Wave"/> - <Condition name="Immobile"/> for 50 per second.
- <Skill name="Forced Engagement"/> - <Condition name="Taunt"/> and <Condition name="Slow"/> for 75 and 50 per second.

</Card>
</GridItem>
</Grid>
</Tab>

<Tab title="99CM">
<Divider text="Nightmare"/>
- Please check the [CC distribution](/guides/cc-distribution) to contribute your share of the necessary CC!
- Please also read through the [Nightmare fractal page](/fractals/nightmare) for general encounter information!

<Message>
These rotations are **not** set in stone and therefore you should adjust your gameplay with how your party plays. Pay attention to the length of the phases, any upcoming CC that might be needed and also pay attention to your energy and the management thereof.
</Message>

<Tabs outlined>
<Tab title="MAMA">

<GridItem sm="12">

**Legends**  

<Skill name="Legendary Renegade stance"/> and <Skill name="Legendary Centaur Stance"/>.

---

**Precast**
* Wait for your teammates to drop a fire field and in case you have a <Specialization name="Soulbeast"/>, wait until they use <Skill name="Moa Stance"/> which increases your boon duration by 20 %.
* Your prestacking is relatively simple and follows the same pattern on every boss. Cast <Skill name="Orders from Above"/> and <Skill name="Renewing Wave"/> and take the mistlock and cast them again.

**100 - 75%**  

* Cast <Skill name="DarkrazorsDaring"/> on MAMA as soon as the red circle appear.
* Cast <Skill name="IcerazorsIre"/> right before MAMA becomes vulnerable.
* Use <Skill name="Surgeofthemists"/> to break the defiance bar. Be aware of your positioning to gain an additional hit.
* Swap your weapons as soon as you are no longer in MAMA's hitbox where your <Skill name="Surge of the mists"/> could hit so you stop casting that skill to save some time.
* Swap your legend to <Skill name="Legendary Centaur Stance"/> and cast <Skill name="Citadel Bombardment"/> on MAMA and use <Skill name="Chilling Isolation"/>.

**1st Knight**   
* Use <Skill name="Shackling Wave"/> to deal damage and to apply a soft CC to the knight.
* Change to <Skill name="Legendary Renegade stance"/> to use <Skill name="Heroic Command"/> to share <Boon name="might"/>.

**75-50%**
* Cast <Skill name="SoulcleavesSummit"/> under MAMA so your teammates get some extra damage and get some healing. If they are already at max health, you can save <Skill name="SoulcleavesSummit"/> for a bit later, since there will be a dome attack from MAMA after the first knight. Be sure to have around 25-35 energy at the end of the phase to be able to cast <Skill name="DarkrazorsDaring"/>.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/> when off cooldown.
* Weapon swap to staff near the end of the phase.

**2nd Add**  
* Precast <Skill name="Darkrazors Daring"/> at the location where the add will spawn.
* Change to <Skill name="Legendary Centaur Stance"/>.
* Share <Boon name="might"/> with <Skill name="Heroic Command"/>.


**50-25%**  
* Use <Skill name="Surge of the Mists"/> through MAMA, and weapon swap to swords.
* When MAMA is CC'd you should use your <Skill name="Citadel Bombardment"/> and <Skill name="Chilling Isolation"/> as they deal the largest amount of damage in your kit and there shouldn't be a need for heals. If your allies need heals, remember to use <Skill name="Natural Harmony"/>
* Change to <Skill name="Legendary Renegade stance"/> for the upcoming add.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/> when off cooldown.

**3rd Add**  
* Precast <Skill name="Darkrazors Daring"/> and <Skill name="icerazors ire"/> where the add will spawn.
* Share <Boon name="might"/> with <Skill name="Heroic Command"/>.
* Weapon swap to staff when possible.

**25-0%**  
* Use <Skill name="Warding Rift"/> for MAMAs shockwaves.
* Using <Skill name="Surge of the Mists"/> through MAMA to break the defiance bar.
* Weapon swap and change to <Skill name="Legendary Centaur Stance"/>.
* Cast your <Skill name="Citadel Bombardment"/> and <Skill name="Chilling Isolation"/> on MAMA once again when it's CC'd.

</GridItem>
</Tab>







<Tab title="Siax">

<GridItem sm="12">
**Legends**  

<Skill name="LegendaryRenegadestance"/> and <Skill name="Legendary Centaur Stance"/>.

---


**Precast**  
* Wait for your teammates to drop a fire field and in case you have a <Specialization name="Soulbeast"/>, wait until they use <Skill name="Moa Stance"/> which increases your boon duration by 20 %.
* Your prestacking is relatively simple and follows the same pattern on every boss. Cast <Skill name="Orders from Above"/> and <Skill name="Renewing Wave"/> and take the mistlock and cast them again.
* Ask your <Specialization name="Weaver"/> to precast <Skill name="Conjure Frost Bow"/> for your opening rotation. It is not needed, but it doesn't take anything away from the weaver and is a group DPS increase as well as 300 CC.

**100 - 66%**   
* Have your staff equipped and pick up the <Skill name="Conjure Frost Bow"/>.
* Precast <Skill name="Darkrazors Daring"/> and <Skill name="icerazors ire"/> and change to <Skill name="Legendary Centaur Stance"/> manually using the UI.
* Once the encounter begins cast <Skill name="Frost Storm"/>, <Skill name="Citadel Bombardment"/>, and <Skill name="Frost Fan"/>.
* Change to <Skill name="Legendary Renegade Stance"/>.
* Use <Skill name="Deep Freeze"/> and drop the <Skill name="Conjure Frost Bow"/>.
* Immediately use <Skill name="Surgeofthemists"/> to finish of the defiance bar.
* When you are through the hitbox weapon swap and use <Skill name="Chilling Isolation"/>.
* Share <Boon name="might"/> at the end of the phase with <Skill name="Heroic Command"/>.

**1st Add**  
* Cast <Skill name="icerazors ire"/> on your designated echo.
* Use <Skill name="Shackling Wave"/> and <Skill name="Chilling Isolation"/> to finish off the echo.
* Cast <Skill name="Soulcleaves Summit"/> on Siax.
* Use <Skill name="Deathstrike"/> to shadow step to Siax immediately.

**66-33%**  
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Let <Skill name="Soulcleaves summit"/> and <Skill name="Shackling wave"/> deplete your energy.
* Change to <Skill name="Legendary Centaur Stance"/> and be ready to start kiting the corrosive bubbles Siax casts. This is done by standing further away from the group (almost where the echoes spawn) and waiting for three green bubbles to be cast on you. Once Siax has cast this skill, you can return to your group and share <Boon name="Might"/> and <Boon name="Alacrity"/>.
* Swap back to <Skill name="LegendaryRenegadestance"/> and be ready to cast <Skill name="IcerazorsIre"/> where your designated echo will spawn.

**2nd Add**  
* Use <Skill name="IcerazorsIre"/> where the echo spawns and deal damage by using <Skill name="Chilling isolation"/> and your basic attacks.
* You want to have enough energy for the following phase to cast <Skill name="Ordersfromabove"/>, <Skill name="Heroic Command"/> and <Skill name="SoulcleavesSummit"/>!

**33-0%**  
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Share <Boon name="Might"/> with <Skill name="Heroic Command"/>
* Cast <Skill name="SoulcleavesSummit"/> for the group and try to keep it up as much as possible. If you CC Siax again at the end of this phase, swap to <Skill name="Legendary Centaur Stance"/> and use <Skill name="Chilling isolation"/>, <Skill name="Shackling wave"/> and <Skill name="Citadel Bombardment"/> to deal damage when Siax is <Effect name="Exposed"/>.
---

</GridItem>
</Tab>










<Tab title="Ensolyss">

<GridItem sm="12">

**Legends**  

<Skill name="LegendaryRenegadestance"/> and <Skill name="LegendaryCentaurStance"/> **or** <Skill name="LegendaryRenegadestance"/> and <Skill name="LegendaryDwarfStance"/> if you don't think extra healing is needed and your group lacks a <Specialization name="Firebrand"/> who could give <Boon name="Stability"/> to the group in the last phase.

---

**Precast**  
* Wait for your teammates to drop a fire field and in case you have a <Specialization name="Soulbeast"/>, wait until they use <Skill name="Moa Stance"/> which increases your boon duration by 20 %.
* Your prestacking is relatively simple and follows the same pattern on every boss. Cast <Skill name="Orders from Above"/> and <Skill name="Renewing Wave"/> and take the mistlock and cast them again.

**100-66%**
* Cast <Skill name="IcerazorsIre"/> and <Skill name="DarkrazorsDaring"/> on the red circle that appears where Ensolyss will spawn just as he starts appearing. Be sure to be on time because if you cast them too early, they will get knocked back and if you are too late you will not have time to cast <Skill name="Surgeofthemists"/> to break the defiance bar.
* Use <Skill name="Surgeofthemists"/> to break the defiance bar. Swap to your swords and swap to <Skill name="LegendaryCentaurStance"/> and use your high damage skills (<Skill name="Chilling isolation"/> and <Skill name="Shackling wave"/>) when Ensolyss is <Effect name="Exposed"/>.
* Share <Boon name="Might"/> and <Boon name="Alacrity"/> with <Skill name="Ordersfromabove"/> and <Skill name="Heroic Command"/>.
* When Ensolyss is no longer <Effect name="Stun"/>ned you will need to make sure to cleanse <Condition name="Bleeding"/> from your allies and keep them relatively healthy for the upcoming **orb phase**.

**Orb Phase**
* Weapon swap to staff and change to <Skill name="Legendary Renegade Stance"/>.
* You should use <Skill name="Breakrazors Bastion"/> to keep your <Specialization name="Soulbeast"/>'s <Skill name="Frost spirit"/> alive. If you don't have a <Specialization name="Soulbeast"/>, you can use <Skill name="Breakrazors Bastion"/> to heal your allies that seem to be struggling during the orb phase.

**66-33%**
* Precast <Skill name="Darkrazors Daring"/> right before Ensolyss appear.
* Cast <Skill name="Icerazors Ire"/>, <Skill name="Orders from Above"/> for <Boon name="Alacrity"/>, <Skill name="Heroic Command"/> for <Boon name="Might"/>, and <Skill name="Soulcleaves Summit"/>.
* Use <Skill name="Surge of the mists"/> to break the defiance bar immediately. Be aware of energy management.
* Weapon swap and change to <Skill name="Legendary Assassin Stance"/>.
* Use <Skill name="Chilling isolation"/>, <Skill name="Citadel Bombardment"/> and <Skill name="Shackling Wave"/> on Ensolyss. You should be able to cast <Skill name="Chilling isolation"/> twice when Ensolyss is <Effect name="Exposed"/>.
* Share <Boon name="Alacrity"/> and <Boon name="Might"/> off cooldown.

**Orb Phase**
* Weapon swap to staff and change to <Skill name="Legendary Renegade Stance"/>.
* Cast <Skill name="Breakrazors Bastion"/> on the <Skill name="Frost Spirit"/> to keep it alive for the last phase or if you don't have a <Specialization name="Soulbeast"/>, use it to keep your teammates alive during the orb phase.

**33-0%**
* Precast <Skill name="Darkrazors Daring"/> right before Ensolyss appear.
* Cast <Skill name="Icerazors Ire"/>, <Skill name="Orders from Above"/> for <Boon name="Alacrity"/>, <Skill name="Heroic Command"/> for <Boon name="Might"/>, and <Skill name="Soulcleaves Summit"/>.
* Use <Skill name="Surge of the mists"/> to break the defiance bar immediately. Be aware of energy management.
* Weapon swap and change to <Skill name="Legendary Assassin Stance"/>.
* Use <Skill name="Chilling isolation"/>, <Skill name="Citadel Bombardment"/> and <Skill name="Shackling Wave"/> on Ensolyss. You should be able to cast <Skill name="Chilling isolation"/> twice when Ensolyss is <Effect name="Exposed"/>.
* Share <Boon name="Alacrity"/> and <Boon name="Might"/> off cooldown.

*In the case of teleporting to the edge of the platform.*
* Change to <Skill name="Legendary Renegade Stance"/> and share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>
* Cast <Skill name="Soulcleaves Summit"/> and <Skill name="Icerazors Ire"/>.

---

**Annotation**
* In the case you are using <Skill name="LegendaryDwarfStance"/>, rotation is relatively same. You will want to use <Skill name="Inspiring Reinforcement"/> in the last phase if Ensolyss teleports to the corner to give stability. For damage you can use <Skill name="Vengeful hammers"/> to increase your DPS if you do not need to conserve energy.

</GridItem>
</Tab>
</Tabs>
</Tab>

<Tab title="100CM">
<Divider text="Shattered Observatory"/>
- Please check the [CC distribution](/guides/cc-distribution) to contribute your share of the necessary CC!
- Please also read through the [Shattered Observatory fractal page](/fractals/shattered-observatory) for general encounter information!

<Message>
These rotations are **not** set in stone and therefore you should adjust your gameplay with how your party plays. Pay attention to the length of the phases, any upcoming CC that might be needed and also pay attention to your energy and the management thereof.
</Message>

<Tabs outlined>
<Tab title="Skorvald">

<GridItem sm="12">

**Legends**  

<Skill name="Legendary Renegade Stance"/> and <Skill name="Legendary Dwarf Stance"/>.

---

**Precast**  
* Wait for your teammates to drop a fire field and in case you have a <Specialization name="Soulbeast"/>, wait until they use <Skill name="Moa Stance"/> which increases your boon duration by 20 %.
* Your prestacking is relatively simple and follows the same pattern on every boss. Cast <Skill name="Orders from Above"/> and <Skill name="Renewing Wave"/> and take the mistlock and cast them again.

**100-66%**  
* Precast <Skill name="Darkrazors Daring"/> when the <Specialization name="Weaver"/> is casting <Skill name="Meteorshower"/>.
* Cast <Skill name="Icerazors Ire"/> right before triggering the instance.
* Use <Skill name="Surge of the Mists"/> through Skorvald to break the defiance bar. Be aware of positioning to gain an extra hit.
* Weapon swap and change to <Skill name="Legendary Dwarf Stance"/>.
* Use your low energy skill <Skill name="Chilling Isolation"/> but save your energy for anomalies since you will provide stability for your whole team using <Skill name="Inspiring Reinforcement"/>.
* Use <Skill name="Orders from Above"/> to share <Boon name="Alacrity"/> – if the phase is longer than 10 seconds you can use <Skill name="Heroic Command"/> to share might on the main platform as well, it should be off cooldown at the first or the second add.

**1st Add**
* As soon as you get to the island you want to use <Skill name="Inspiring Reinforcement"/> and <Skill name="Vengeful Hammers"/>.
* Use <Skill name="Heroic Command"/> to share <Boon name="Might"/>.
* Swap to <Skill name="Legendary Renegade Stance"/> before you get into the updraft. You can change legends if you enter the updraft by running into it and not by jumping into it. Also swap to Staff weapon set to be able to use <Skill name="Renewing Wave"/>.

**2nd Add**  
* Use <Skill name="SoulcleavesSummit"/> on the island as soon as you land on it. Blast the fire field with <Skill name="Renewing Wave"/>
* When the add is about to finish the channeled jump, use <Skill name="Citadel Bombardment"/> to deal as much damage as possible.
* Try to swap into <Skill name="Legendary Dwarf Stance"/> before taking the updraft.

**3rd Add**
* Use <Skill name="Inspiring Reinforcement"/> to share <Boon name="Stability"/> as soon as you land on the island.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.

**4th Add**
* Use <Skill name="Inspiring Reinforcement"/> to share <Boon name="Stability"/> as soon as you land on the island.
* Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.
* When the add is about to finish the channeled jump, use <Skill name="Citadel Bombardment"/> to deal as much damage as possible.
* Swap to <Skill name="Legendary Renegade Stance"/> before the anomaly is dead.


**66-33%**
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Cast <Skill name="Soulcleaves Summit"/> and <Skill name="Icerazors Ire"/> immediately.
* Keep <Skill name="SoulcleavesSummit"/> up as long as possible. In shorter phases you can consider using <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/>.
* Share <Boon name="alacrity"/> with <Skill name="Orders from Above"/> when the phase ends.

**Adds**
* Replicate the skill order mentioned above in the earlier add phase.

**33-0%**
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Cast <Skill name="Soulcleaves Summit"/> and <Skill name="Icerazors Ire"/> immediately.
* Keep <Skill name="SoulcleavesSummit"/> up as long as possible. In shorter phases you can consider using <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/>.
* Share <Boon name="alacrity"/> with <Skill name="Orders from Above"/> when the phase ends.
* If Skorvald is not dead before he starts using Solar Cyclone (the attack where he spins around and knocks you back) switch to <Skill name="Legendary Dwarf Stance"/> and use <Skill name="Inspiring Reinforcement"/> before he starts using afromentioned attack.

---

**Annotation**
* Cast <Skill name="Citadel Bombardment"/> right as you jump the shockwave of the 2nd and 4th add. This can save you some time with a good party.
* Be aware of positioning when sharing <Boon name="Alacrity"/> and <Boon name="Might"/> on the islands. Make sure everyone has landed before sharing.
* Cancel <Skill name="Surge of the Mists"/> once you are through the hitbox to gain time to do more damage in the first phase.

</GridItem>
</Tab>




















<Tab title="Artsariiv">

<GridItem sm="12">


**Legends**  

<Skill name="Legendary Renegade Stance"/> and <Skill name="Legendary Dwarf Stance"/>.

---

**Traits**

For this encounter it is recommended to run the following traits in Devastation trait line.

<UnembossedTraits traits1Id="15" traits1="Devastation" traits1SelectedIds="1767,1786,1754"/>

**Precast**  
* Wait for your teammates to drop a fire field and in case you have a <Specialization name="Soulbeast"/>, wait until they use <Skill name="Moa Stance"/> which increases your boon duration by 20 %.
* Your prestacking is relatively simple and follows the same pattern on every boss. Cast <Skill name="Orders from Above"/> and <Skill name="Renewing Wave"/> and take the mistlock and cast them again.

**100-66%**
* Precast <Skill name="Soulcleaves Summit"/> and <Skill name="Icerazors Ire"/> at Artsariiv's location after triggering the encounter.
* Manually change to <Skill name="Legendary Dwarf Stance"/> before Artsariiv becomes vulnerable.
* Use <Skill name="Shackling Wave"/>, and share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Share <Boon name="Might"/> with <Skill name="Heroic Command"/> before using the <Effect name="hypernovalaunch"/> to the corner.
* Weapon swap and use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> for the party.
* Change to <Skill name="Legendary Renegade Stance"/>, and precast <Skill name="Darkrazors Daring"/>, <Skill name="Icerazors Ire"/>, and <Skill name="Soulcleaves Summit"/> at the location where Artsarriv will appear.
* Use <Skill name="Surge of the Mists"/> to break the defiance bar. Use it with the <Effect name="hypernovalaunch"/> to gain additional hits.
* Weapon swap and change to <Skill name="Legendary Dwarf Stance"/>

**Add**
* Use <Skill name="Forced Engagement"/> and <Skill name="Shackling Wave"/> to break the adds defiance bar.


**66-33%**
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/> when everyone is in the middle.
* Use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> for the large AoE attack.
* Change to <Skill name="Legendary Renegade Stance"/>, and use <Skill name="Soulcleaves Summit"/> and <Skill name="Citadel Bombardment"/>.
* Share <Boon name="might"/> with <Skill name="Heroic Command"/>.
* Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> to deplete your energy.
* Change to <Skill name="Legendary Dwarf Stance"/>, and use your <Effect name="hypernovalaunch"/> to the corner.
* Use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> at the corner.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Share <Boon name="might"/> with <Skill name="Heroic Command"/>.
* Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> for additional damage.
* Weapon swap to staff when phase ends.

**Add**
* Use <Skill name="Forced Engagement"/> on the first add.
* Use <Skill name="Surge of the Mists"/> on the second add.

**33-0%**
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/> when everyone is in the middle.
* Use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> for the large AoE attack.
* Change to <Skill name="Legendary Renegade Stance"/>, and use <Skill name="Soulcleaves Summit"/> and <Skill name="Citadel Bombardment"/>.
* Share <Boon name="might"/> with <Skill name="Heroic Command"/>.
* Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> to deplete your energy.
* Change to <Skill name="Legendary Dwarf Stance"/>, and use your <Effect name="hypernovalaunch"/> to the corner.
* Use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> at the corner.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Share <Boon name="might"/> with <Skill name="Heroic Command"/>.
* Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> for additional damage.

---

**Annotation**
* Time <Skill name="Inspiring Reinforcement"/> so that <Boon name="Stability"/> last long enough for the AoE attack in the middle.
* Use <Effect name="hypernovalaunch"/> while using <Skill name="Surge of the Mists"/> to break the defiance bar as quickly as possible.

This part of the guide was taken from [Casual Sophie](https://www.youtube.com/channel/UCh3JEHa_zLroJYrtaftdQzw)'s Renegade guide that you can find [here](/builds/revenant/hybrid-renegade)

</GridItem>
</Tab>























<Tab title="Arkk">

<GridItem sm="12">

**Legends**  


<Skill name="Legendary Renegade Stance"/> and <Skill name="Legendary Centaur Stance"/>.

---

**Traits**

For this encounter it is recommended to run the following traits in Devastation trait line.

<UnembossedTraits traits1Id="15" traits1="Devastation" traits1SelectedIds="1767,1786,1754"/>

---

**Precast**  
* Wait for your teammates to drop a fire field and in case you have a <Specialization name="Soulbeast"/>, wait until they use <Skill name="Moa Stance"/> which increases your boon duration by 20 %.
* Your prestacking is relatively simple and follows the same pattern on every boss. Cast <Skill name="Orders from Above"/> and <Skill name="Renewing Wave"/> and take the mistlock and cast them again.

**100-80%**
* Use <Skill name="Citadel Bombardment"/>, <Skill name="Shackling Wave"/> and <Skill name="Chilling isolation"/> and swap to <Skill name="Legendary Centaur Stance"/>.
* Use <Skill name="Natural Harmony"/> to give <Boon name="Alacrity"/> to your allies and to keep them topped up for the orb phase.
* If this phase is a bit long, you can share <Boon name="Alacrity"/> and <Boon name="Might"/> with <Skill name="Ordersfromabove"/> and <Skill name="Heroic command"/>.
* Once Arkk turns invulnerable, swap to staff weapon set and swap to <Skill name="Legendary Renegade Stance"/>.

**80-70%**
* Cast <Skill name="SoulcleavesSummit"/> on Arkk to create a fire field.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Use <Skill name="Surge of the Mists"/> with the <Effect name="hypernovalaunch"/> to break the defiance bar.
* Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.
* Weapon swap and change to <Skill name="Legendary Centaur Stance"/>.

**Archdiviner**
* Activate <Skill name="Protective Solace"/> on top of the group to prevent the Archdiviner's minions from dealing damage to your group.
* If Archdiviner gets a defiance bar, use your <Effect name="hypernovalaunch"/> to do 232 defiance bar damage to it and blast a fire field if there is one under him.
* Change to <Skill name="Legendary Renegade Stance"/> when the phase is finished.

**70-50%**
* Cast <Skill name="Soulcleaves Summit"/>.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.
* Change to <Skill name="Legendary Centaur Stance"/>.
* Use <Skill name="Citadel Bombardment"/>, <Skill name="Chilling Isolation"/>, and <Skill name="Shackling Wave"/>. If there are still any minions from Archdiviner left, you can use <Skill name="Protective Solace"/> to prevent them from applying conditions on you and from dealing any damage to you.
* Weapon swap and change to <Skill name="Legendary Renegade Stance"/> when the phase is finished.

**50-40%**
* Precast <Skill name="Soulcleaves Summit"/> at Arkk's location.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Use <Skill name="Surge of the Mists"/> with the <Effect name="hypernovalaunch"/> to break the defiance bar.
* Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.
* Weapon swap and change to <Skill name="Legendary Centaur Stance"/>.

**Gladiator**
* Activate <Skill name="Protective Solace"/> on top of the group to prevent the robots from dealing damage to your group. There is also one robot that applies conditions, especially detrimental to your group's damage is <Condition name="Weakness"/>.
* If Gladiator gets a defiance bar, use your <Effect name="hypernovalaunch"/> to do 232 defiance bar damage to it and blast a fire field if there is one under him.
* Change to <Skill name="Legendary Renegade Stance"/> when the phase is finished.

**40-30%**
* Use <Skill name="SoulcleavesSummit"/> to get your teammates healed.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/> in the middle.
* Weapon swap at the end of the phase.

**30-0%**
* Precast <Skill name="Darkrazors Daring"/>, <Skill name="Icerazors Ire"/>, and <Skill name="Soulcleaves Summit"/> at Arkk's location.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Use <Skill name="Surge of the Mists"/> with the <Effect name="hypernovalaunch"/> to break the defiance bar.
* Weapon swap and change to <Skill name="Legendary Centaur Stance"/>.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Use <Skill name="Citadel Bombardment"/>, <Skill name="Chilling Isolation"/>, and <Skill name="Shackling Wave"/> until the encounter is finished.

---
</GridItem>
</Tab>
</Tabs>
</Tab>


</Tabs>
