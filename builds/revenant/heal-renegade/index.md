---
title: 'Heal Renegade'
date: '2020-07-25'
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
nightmareguide: '/cm-guides/revenant/heal-renegade/nightmare'
shatteredguide: '/cm-guides/revenant/heal-renegade/shatteredobservatory'
---

The **<Specialization text="Heal Renegade" name="Renegade"/>** plays with a mix of harrier's and cleric's gear for maximum power and healing power while still hitting 100% boon duration.
 
Since the damage and life steals of <Skill name="Soulcleaves Summit" /> are based on the **<Specialization text="Heal Renegade" name="Renegade"/>**'s own power and healing power, the <Specialization text="Heal Renegade" name="Renegade"/> aims to maximize those stats.

Feel free to run full Harrier if you are confident that you don't need the extra healing power or toughness from cleric. The more agony resistance you have, the more cleric you can afford to run and still hit 100% boon duration.

<Divider text="Equipment"/>

<Tabs outlined>

<Tab title="162 Agony Resistance">
Check the [gear optimizer](https://old.discretize.eu) for more gear variants!
<Grid>
<GridItem sm="4">
<Armor weight="Heavy" helmAffix="Harrier" helmRune="Monk" shouldersAffix="Harrier" shouldersRune="Monk" coatAffix="Harrier" coatRune="Monk" glovesAffix="Harrier" glovesRune="Monk" leggingsAffix="Harrier" leggingsRune="Monk" bootsAffix="Harrier" bootsRune="Monk" helmInfusionId="49432" shouldersInfusionId="49432" coatInfusionId="49432" glovesInfusionId="49432" leggingsInfusionId="49432" bootsInfusionId="49432" />
</GridItem>

<GridItem sm="4">
<Weapons weapon1MainType="Sword" weapon1MainAffix="Harrier" weapon1MainSigil1="Transference" weapon1OffType="Sword" weapon1OffAffix="Harrier" weapon1OffSigil="Concentration" weapon2MainType="Staff" weapon2MainAffix="Harrier" weapon2MainSigil1="Transference" weapon2MainSigil2="Concentration" weapon1MainInfusion1Id="49432" weapon2MainInfusion1Id="49432" weapon1OffInfusionId="49432" weapon2MainInfusion2Id="49432"/>
<Consumables foodId="68634" utilityId="67528" infusionId="37125"/>

</GridItem>

<GridItem sm="4">
<BackAndTrinkets backItemAffix="Harrier" accessory1Affix="Cleric" accessory2Affix="Cleric" amuletAffix="Harrier" ring1Affix="Harrier" ring2Affix="Harrier" backItemInfusion1Id="49432" backItemInfusion2Id="49432" accessory1InfusionId="49432" accessory2InfusionId="49432" ring1Infusion1Id="49432" ring1Infusion2Id="49432" ring1Infusion3Id="49432" ring2Infusion1Id="49432" ring2Infusion2Id="49432" ring2Infusion3Id="49432"/>
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



<GridItem sm="5">
<Card title="Legend combos">
## Normal
<Skill name="Legendary Renegade Stance" disableText size="big"/> <Skill name="Legendary Centaur Stance" disableText size="big"/> 

## More stability needed
<Skill name="Legendary Renegade Stance" disableText size="big"/> <Skill name="Legendary Dwarf Stance" disableText size="big"/>   

## No Pain No Gain   <Label>Use the Salvation / Invocation / Renegade variant for more energy!</Label>
<Skill name="Legendary Renegade Stance" disableText size="big"/>  <Skill name="Legendary Demon Stance" disableText size="big"/>

## For more explanation go to the Guides tab above.
</Card>
</GridItem>

</Grid>

<Divider text="Guide"/>

<Grid>
<GridItem sm="12">
<Card title="Abilities">
**Citadel Order Skills**

- <Skill name="Heroic Command"/> -  Share two stacks of <Boon name="Might"/> for each <SpecialActionKey name="kallas fervor"/> stack.
- <Skill name="Citadel Bombardment"/> - Fire ten missiles that inflict high damage, and <Condition name="Burning"/>.
- <Skill name="Orders from Above"/> - Share four pulses of <Boon name="Alacrity"/>.

---

**Sword Skills**

- <Skill name="Preparation Thrust"/> - The auto-attack chain cleaves and provides <Condition name="Vulnerability"/> on the two first attacks. The third attack creates an exploding rift on up to three targets, with each explosion hitting three targets. Potentially hitting nine times.
- <Skill name="Chilling Isolation"/> - High damage skill with low cooldown and energy cost, also provides <Condition name="Chilled"/>. The second attack deals increased damage to isolated enemies.
- <Skill name="Unrelenting Assault"/> - A two second evade that also provides <Boon name="Might"/> to oneself.
- <Skill name="Shackling Wave"/> - High damage skill, however should be used in key moments due to the energy cost, cooldown, and application of <Condition name="Vulnerability"/>.
- <Skill name="Death strike"/> - Shadowsteps to target, grants two hits with decent damage. Should be used in key moments, unless energy and timing allow it to be used for damage.

**Staff Skills**

- <Skill name="Rapid Swipe"/> - The autoattack chain cleaves and the last hit provides a decent amount of healing to allies.
- <Skill name="Menders Rebuke"/> - Provides <Condition name="Weakness"/> and a small amount of healing to allies.
- <Skill name="Warding Rift"/> - A two second block that <Condition name="Blinded"/> foes.
- <Skill name="Renewing Wave"/> - Provides a blast for a combo field, cleanses two conditions and heals allies for a fairly large amount.
- <Skill name="Surge of the Mists"/> - The strongest Crowd Control skill in your arsenal, which grants between three and nine hits of <Control name="Knockback"/>.

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
You will need to reconsider the legends you are running in almost every fractal and therefore it is a nice habit to develop to check them after each fractal you have done. Some fractals demand three to four different legends in only one fractal. Below you will find the three most common setups that will serve you fine as well as a description of the skills in each legend.
</Message>

## Legends Setups:

1. **<Skill name="Legendary Renegade Stance"/>** and **<Skill name="Legendary Centaur Stance"/>**
   - This is your most used setup that has the most healing output as well as a projectile block and extra condition cleanse.
2. **<Skill name="Legendary Renegade Stance"/>** and **<Skill name="Legendary Demon Stance"/>**
   - This is a specific setup for the instability <Instability name="No Pain, No Gain"/> and for when you want to increase your damage output on bosses that generate <Boon name="Protection"/> on themselves or when you need to pull adds using <Skill name="Call to Anguish"/>.
3. **<Skill name="Legendary Renegade Stance"/>** and **<Skill name="Legendary Dwarf Stance"/>**
   - This is the setup you want to use on a few CM bosses (Skorvald and Artsariiv) as well as some fractals (Chaos last boss, possibly in Siren's Reef).

---

**<Skill name="Legendary Renegade Stance"/>**

- <Skill name="Breakrazors Bastion"/> - Summons a spirit that heals you on cast and pulses heal to allies in an area around it. Reduces damages from conditions by 50%.
- <Skill name="Razorclaws Rage"/> - Summons a spirit that causes your party to inflict <Condition name="Bleeding"/> on attack.
- <Skill name="Darkrazors Daring"/> - Summons a spirit that <Control name="Daze"/>s enemies in an area around it for ¼ seconds once per second for six seconds.
- <Skill name="Icerazors Ire"/> -  Summons a spirit that deals high damage to enemies around it and inflicts <Condition name="Vulnerability"> on the targets.
- <Skill name="Soulcleaves Summit"/> - Summons a spirit that enchants your party's attacks with life steal. Increases damage dealt by your party while healing them for each attack.

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
