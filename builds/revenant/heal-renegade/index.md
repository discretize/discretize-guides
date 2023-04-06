---
title: Heal Renegade
hidden: false
archive: true
rating: Offmeta
role: Support
profession: Revenant
specialization: Renegade
skills:
  - 45773
  - 44076
  - 27025
  - 45686
  - 27505
traits:
  - 1786
  - 1814
conditions:
  - name: Vulnerability
boons:
  - name: Alacrity
    variant: Party
    uptime: 100%
  - name: Might
    uptime: 10 Stacks
    variant: Party
  - name: Fury
    uptime: 90%
    variant: Party
  - name: Stability
    uptime: On Demand
    variant: Party
  - name: Regeneration
    variant: Party
    uptime: 100%
  - name: Protection
    uptime: 100%
    variant: party
  - name: Resistance
    uptime: On Demand
    variant: Party
code: '[&DQkPJgw/Pz/cEdwRBhLUESsSBhLUESsSyhHKERIRDw4GEtQRKxIAAAAAAAA=]'
cmGuide: ''
classification:
  - 4
  - 1
  - 3
  - 2
  - 2
date: '2022-08-05T22:39:42.575Z'
---

The **<Specialization text="Heal Renegade" name="Renegade"/>** plays with a mix of harrier's and cleric's gear for maximum power and healing power while still hitting 100% boon duration.

Since the damage and life steals of <Skill name="Soulcleaves Summit" /> are based on the **<Specialization text="Heal Renegade" name="Renegade"/>**'s own power and healing power, the <Specialization text="Heal Renegade" name="Renegade"/> aims to maximize those stats.

Feel free to run full Harrier if you are confident that you don't need the extra healing power or toughness from cleric. The more agony resistance you have, the more cleric you can afford to run and still hit 100% boon duration.

<Divider text="Equipment"/>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Salvation" traits1Selected="Tranquil Balance,Invoking Harmony,Generous Abundance" traits2="Devastation" traits2Selected="Unsuspecting Strikes,Assassins Presence,Swift Termination" traits3="Renegade" traits3Selected="Wrought-Iron Will,All for One,Righteous Rebel"/>
<Card title="Second trait variant">
If you run out of energy too quickly, we recommend the Salvation/Invocation variant. This variant is also better for fractals where <Trait name="Assassins Presence"/> doesn't help your party. This would include fractals where damage is time-gated and where you can't critically hit the enemies that matter.

You should consider running this trait variant in fractals like Molten Furnace and Captain Mai Trin.

Swap Devastation with this line:
<Traits unembossed traits1Id="3" traits1="Invocation" traits1SelectedIds="1761,1774,1791"/>

Template code:

`[&DQkDJgw/Pz/cEdwRBhLUESsSBhLUESsSyhHKERIRDw4GEtQRKxIAAAAAAAA=]`

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Legend Combos">

## Normal

<Skill name="Legendary Renegade Stance" disableText size="big"/> <Skill name="Legendary Centaur Stance" disableText size="big"/>

## When <Boon name="Stability"/> is needed

<Skill name="Legendary Renegade Stance" disableText size="big"/> <Skill name="Legendary Dwarf Stance" disableText size="big"/>

## No Pain No Gain <Label>Use the Salvation / Invocation / Renegade variant for more energy!</Label>

<Skill name="Legendary Renegade Stance" disableText size="big"/> <Skill name="Legendary Demon Stance" disableText size="big"/>

## For more explanation go to the Guides tab above.

</Card>
<Card title="Healing Basics">
Your healing skills in order of effectiveness are:

1. <Skill id="45773"/>
2. <Skill id="45686"/>
3. <Skill id="27025"/>
4. <Trait id="1815"/>
5. <Skill id="27356"/>
6. <Skill id="29002"/>
7. <Skill id="28427"/>

With <Skill id="45773"/> you can sustain your group for the whole time you have energy on <Skill id="41858"/>. When you are about to swap off, you should use your <Skill id="45686"/> on the group as it lingers even when you swap to a different legend and will maintain the heals. <Skill id="28195"/> has a good proactive way to lessen the incoming damage by proper usage of <Skill id="26821"/>. You also have heals when you use your basic staff auto attack <Skill id="29002"/> (note that this is the last part of the auto attack sequence).

</Card>
</GridItem>
</Grid>

<Divider text="Guide"/>

<Grid>
<GridItem sm="12">
<Card title="Abilities">

**Citadel Order Skills**

- <Skill name="Heroic Command"/> - Share two stacks of <Boon name="Might"/> for each <SpecialActionKey name="kallas fervor"/> stack.
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

<Information>

You will need to reconsider the legends you are running in almost every fractal and therefore it is a nice habit to develop to check them after each fractal you have done. Some fractals demand three to four different legends in only one fractal. Below you will find the three most common setups that will serve you fine as well as a description of the skills in each legend.

</Information>

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
- <Skill name="Icerazors Ire"/> - Summons a spirit that deals high damage to enemies around it and inflicts <Condition name="Vulnerability"/> on the targets.
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
