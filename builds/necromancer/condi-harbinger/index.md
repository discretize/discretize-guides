---
title: Condi (Quick) Harbinger
hidden: false
archive: false
hasBeginner: false
rating: Good
role: Condi Damage
profession: Necromancer
specialization: Harbinger
traits: []
conditions:
  - name: Vulnerability
    uptime: 20 stacks
  - name: Torment
  - name: Bleeding
  - name: Poisoned
  - name: Burning
boons:
  - name: Quickness
    uptime: 100%
    variant: (using Quickness variant)
  - name: Fury
    uptime: 100%
    variant: (using Quickness variant)
  - name: Might
    uptime: 6 stacks
    variant: (13 stacks on Quickness variant)
  - name: Swiftness
    uptime: 65%
    variant: (using Quickness variant)
  - name: Regeneration
    uptime: 50%
    variant: (using Quickness variant)
code: '[&DQgnNjI1QD/nGhIA1BpvAYAAcAHsGncBkgCVAAAAAAAAAAAAAAAAAAAAAAA=]'
classification:
  - 3
  - 4
  - 4
  - 3
  - 4
date: 2022-07-31T11:55:48.258Z
---

The <Specialization name="Harbinger" text="Condi Harbinger"/> provides high Condition damage while having some self-generated boons due to Elixirs as well as some group <Boon name="Might"/> through <Skill name="Blood is Power"/>. You can also adapt your build to provide <Boon name="Quickness"/> as well as share your Elixir boons with your group. You can also upkeep 25 stacks of <Condition name="Vulnerability"/> on your own after the initial ramp-up.

The <Specialization name="Harbinger" text="Condi Harbinger"/> is more squishy than other <Specialization name="Necromancer"/> builds because it loses maximum health due to the <Effect name="Blight"/> mechanic and <Skill name="Harbinger Shroud"/> does not act as a second health bar. However, even with maximum <Effect name="Blight"/> stacks, you will still be at around 15k health.

Due to being a condition-based build, it will not benefit from slaying potions or <Item name="Impact" type="Sigil"/>.

<Divider text="Equipment"/>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits
traits1="Curses" traits1Selected="Plague Sending, Master of Corruption, Lingering Curse"
traits2="Soul Reaping" traits2Selected="Unyielding Blast, Soul Barbs, Dhuumfire"
traits3="Harbinger" traits3Selected="Septic Corruption , Dark Gunslinger, Doom Approaches"/>
<Card title="Quickness Variant">

Use this setup if you are responsible for providing Quickness to your group.
<Traits traits1="Harbinger" traits1Selected="Septic Corruption , Twisted Medicine, Deathly Haste" unembossed/>

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                               |                                                                                                                                                                                                      |
| ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill name="Summon Flesh Golem" size="big" disableText/>     | Can be taken for additional CC.                                                                                                                                                                      |
| <Skill name="Elixir of Ambition" size="big" disableText/>     | Useful for stacking boons at the singularity. Can be useful in niche situations to increase boon uptime or give yourself <Boon name="Aegis"/>.                                                       |
| <Skill name="Elixir of Bliss" size="big" disableText/>        | Can help cleansing conditions. Keep in mind that delaying your Elixirs also means delaying your <Effect name="Blight"/> application.                                                                 |
| <Skill name="Elixir of Ignorance" size="big" disableText/>    | Acts as a stun-break. Keep in mind that delaying your Elixirs also means delaying your <Effect name="Blight"/> application.                                                                          |
| <Skill name="Epidemic" size="big" disableText/>               | Spreads conditions on your current target to up to 5 enemies in the surrounding area. Can help to kill the anomaly at Arkk.                                                                          |
| <Skill name="Spectral Grasp" size="big" disableText/>         | A useful 1200 range 5 target <Control name="Pull"/>. It provides an extra 150 defiance bar damage and can hit up to five times if you cast it inside the boss while there are other enemies outside. |
| <Skill name="Summon Flesh Wurm" size="big" disableText/>      | A 1200 range teleport skill useful for various skips.                                                                                                                                                |
| <Skill name="Spectral Walk " size="big" disableText/>         | Another teleport skill. Useful for <Boon name="Swiftness"/> or skips such as soloing the turret room in the [Thaumanova](/fractals/thaumanova-reactor) fractal.                                      |
| <Skill name="Corrosive Poison Cloud" size="big" disableText/> | A useful skill for mitigating projectiles.                                                                                                                                                           |

</Card>
</GridItem>
</Grid>

<Divider text="Skills and Basics"/>
<Grid>

<GridItem sm="6">

<Card title="Blight">

- Using Elixir skills and staying in <Skill name="Harbinger Shroud"/> will inflict <Effect name="Blight"/> on you, reducing your maximum health by 1.5% per stack (up to 37.5% at 25 stacks).
- <Trait name="Septic Corruption"/> increases the damage you deal with conditions for each stack of <Effect name="Blight"/>.
- <Trait name="Alchemic Vigor"/> heals you every second for each stack of <Effect name="Blight"/>.
- Certain skills consume some <Effect name="Blight"/> when you are above a treshold to deal more damage, namely <Skill name="Devouring Cut"/> (Shroud 3) and your Elixirs when above 5 stacks of <Effect name="Blight"/> and <Skill name="Voracious Arc"/> (Shroud 4) when above 10 stacks.

</Card>

<Card title="Pistol skills">

- Your auto-attack <Skill name="Vicious Shot"/> deals good damage and will be used to fill any gaps in the rotation.
- <Skill name="Weeping Shots"/> sends out multiple bullets and fills up Life Force for each bullet that hits an enemy. This skill also pierces which can be useful to help with the anomaly at Arkk as an example.
- <Skill name="Vile Blast"/> fires a dart that, on impact, will explode and give you some Life Force per enemy hit and <Control name="Stun"/> as well as inflict <Condition name="Weakness"/> and <Condition name="Poisoned"/>.

</Card>

<Card title="Harbinger Shroud">

- Unlike on core <Specialization name="Necromancer"/> or <Specialization name="Reaper"/>, your <Skill name="Harbinger Shroud"/> will not absorb the damage for you while inside.
- You can enter <Skill name="Harbinger Shroud"/> even at 0 Life Force since entering gives you 15% due to <Trait name="Corrupted Talent"/>.
- While in <Skill name="Harbinger Shroud"/>, you constantly gain <Effect name="Blight"/> and drain Life Force.
- All of your important Shroud skills are ranged. However, part of your damage comes from <Trait name="Doom Approaches"/> which has a small radius around you. Same goes for <Boon name="Quickness"/> uptime through <Trait name="Deathly Haste"/>.
- Your auto-attack <Skill name="Tainted Bolts"/> deals damage around your target.
- <Skill name="Dark Barrage"/> fires out 6 bolts. If you stand too far away, some bolts will miss the target.
- <Skill name="Devouring Cut"/> dashes you to your target and then damages enemies on impact. If you are already in melee range, you can cancel this skill right away and still deal damage. If above 5 <Effect name="Blight"/>, this attack will consume 5 stacks and deal extra damage.
- <Skill name="Voracious Arc"/> leaps you into the targeted area while evading, deals damage and <Control name="Daze"/> the enemy. If above 10 <Effect name="Blight"/>, this attack will consume 10 stacks and deal extra damage.
- <Skill name="Vital Draw"/> is the only Shroud skill you will not actively use in your rotation. However, it is a strong CC skill that will deal 300 break bar damage to enemies around you.

</Card>

</GridItem>

<GridItem sm="6">

<Card title="Elixirs">

- As a <Specialization name="Harbinger"/> you gain access to Elixirs as utility skills.
- Using an Elixir grants you Boons (that are shared with your allies when running <Trait name="Twisted Medicine"/>). Then the elixir will be thrown at your target location inflicting Conditions on your enemy.
- If you are in the splash area of the Elixir, you gain <Effect name="Blight"/>.
- If you are above the Blight threshold (5 for heal/utility, 10 for the elite), you will lose this amount of <Effect name="Blight"/> to enhance the damage of the Elixir.
- Using Elixirs will help us upkeep
- The most commonly used Elixirs are <Skill name="Elixir of Promise"/>, <Skill name="Elixir of Risk"/> and <Skill name="Elixir of Anguish"/> with <Skill name="Elixir of Promise"/> being the most interesting one for damage due to its <Condition name="Poisoned"/> application and the other 2 giving very useful boons.
- <Skill name="Elixir of Bliss"/> can help cleansing conditions while <Skill name="Elixir of Ignorance"/> acts as a stun-break. However keep in mind that delaying your Elixirs also means delaying your <Effect name="Blight"/> application.

</Card>

<Card title="Important Traits">

- <Trait name="Plague Sending"/> will transfer up to 2 conditions from you after entering <Skill name="Harbinger Shroud"/>. Always use <Skill name="Blood is Power"/> right before entering your Shroud to transfer the conditions for extra damage.
- <Trait name="Twisted Medicine"/> (<Boon name="Quickness"/> variant) shares the boons from Elixirs with the group helping to upkeep many different boons. It also converts 13% of your <Attribute name="Vitality"/> into <Attribute name="Concentration"/> which, in fractals, allows us to run without any additional <Attribute name="Concentration"/> gear for the <Boon name="Quickness"/> variant.
- <Trait name="Deathly Haste"/> (<Boon name="Quickness"/> variant) pulses <Boon name="Quickness"/> around you while in Shroud. Together with the Elixirs, this is your main way of keeping up this boon for your group.
- <Trait name="Dark Gunslinger"/> (DPS variant) reduces the cooldown of Pistol skills. It also converts 13% of your <Attribute name="Vitality"/> into <Attribute name="Expertise"/> which allows us to run with <Item name="Nightmare" type="Rune"/> and almost cap both <Condition name="Bleeding"/> and <Condition name="Torment"/> duration.
- <Trait name="Doom approaches"/> (DPS variant) pulses <Condition name="Torment"/> around you while in Shroud.

</Card>

<Card title="CC skills">

|                                                       |                                               |
| ----------------------------------------------------- | --------------------------------------------- |
| <Skill name="Vile Blast" size="big" disableText/>     | 100 damage                                    |
| <Skill name="Voracious Arc" size="big" disableText/>  | 100 damage                                    |
| <Skill name="Vital Draw" size="big" disableText/>     | 300 damage                                    |
| <Skill name="Wail of Doom" size="big" disableText/>   | 200 damage                                    |
| <Skill name="Charge" size="big" disableText/>         | 600/800/1000 damage depending on hitbbox size |
| <Skill name="Spectral Grasp" size="big" disableText/> | 150-750 damage (see situational skills)       |

</Card>

</GridItem>

</Grid>

<Divider text="Rotation"/>

<Grid>
<GridItem sm="6">
<Card title="General Information">

- Enter <Skill name="Harbinger Shroud"/> approx. every 20 seconds.
- You gain Life Force when units around you die or from some skills, namely <Skill name="Weeping Shots"/>, <Skill name="Vile Blast"/> and <Skill name="Devouring Darkness"/> as well as entering <Skill name="Harbinger Shroud"/>.
- Use <Skill name="Deathly Swarm"/> and <Skill name="Harbinger Shroud"/> (triggering <Trait name="Plague Sending"/>) to transfer Conditions you get from <Skill name="Blood is Power"/> and <Skill name="Plaguelands"/> to the boss.
- Use all 3 Elixirs off-cooldown to keep up Blight. They have the same cooldown. Use <Skill name="Elixir of Promise"/> last to ensure you are using it above the Blight threshold doubling the duration of the <Condition name="Poisoned"/> it applies.
- Try to stay on Pistol as much as possible. Ideally, you will never use a single auto-attack on Scepter. It is just for using <Skill name="Devouring Darkness"/> and <Skill name="Grasping Dead"/> before and after every other <Skill name="Harbinger Shroud"/>.

</Card>

<Card title="Loop">

After the Opener and your first Shroud Rotation is done, the loop will be:

1. Pistol Rotation
2. Weapon Swap
3. <Skill name="Devouring Darkness"/>
4. <Skill name="Grasping Dead"/>
5. <Skill name="Blood is Power"/>
6. <Skill name="Harbinger Shroud"/>
7. Shroud Rotation
8. <Skill name="Devouring Darkness"/>
9. <Skill name="Grasping Dead"/>
10. Weapon Swap
11. Pistol Rotation
12. <Skill name="Blood is Power"/>
13. <Skill name="Harbinger Shroud"/>
14. Shroud Rotation

</Card>

<Card title="Extra Information">

- Fill in any remaining gaps in the loop with Pistol auto-attacks.
- <Skill name="Blood is Power"/> will recharge slightly more often than you enter <Skill name="Harbinger Shroud"/>. Use extra charges in combination with <Skill name="Deathly Swarm"/>. Otherwise use <Skill name="Deathly Swarm"/> for <Skill name="Plaguelands"/> when it comes off-cooldown.
- <Skill name="Devouring Cut"/> has a cast-time but does its damage even if you cancel the skill right away.

</Card>
</GridItem>

<GridItem sm="6">

<Card title="Precast (at singularity)">

- Use as many Elixirs as possible to stack boons for yourself (and allies when running <Trait id="2220"/>).
- You can also use <Skill name="Harbinger Shroud"/> to pre-stack more <Boon name="Quickness"/> when running <Trait name="Deathly Haste"/>.

</Card>

<Card title="Opener">

1. <Skill name="Plaguelands"/>
2. <Skill name="Devouring Darkness"/>
3. Weapon swap
4. <Skill name="Vile Blast"/> (skip this if the boss has no breakbar)
5. <Skill name="Weeping Shots"/>
6. <Skill name="Blood is Power"/>
7. <Skill name="Harbinger Shroud"/>

</Card>

<Card title="Shroud Rotation">

8. <Skill name="Dark Barrage"/>
9. <Skill name="Voracious Arc"/>
10. <Skill name="Devouring Cut"/>
11. 5x <Skill name="Tainted Bolts"/>
12. <Skill name="Dark Barrage"/>
13. 5x <Skill name="Tainted Bolts"/>
14. <Skill name="Voracious Arc"/>
15. <Skill name="Devouring Cut"/>
16. <Skill name="Dark Barrage"/>
17. <Skill name="Exit Harbinger Shroud"/>

</Card>

<Card title="Pistol Rotation">

18. <Skill name="Weeping Shots"/>
19. <Skill name="Vile Blast"/>
20. <Skill name="Enfeebling Blood"/>
21. <Skill name="Elixir of Risk"/>
22. <Skill name="Elixir of Anguish"/>
23. <Skill name="Elixir of Promise"/>
24. <Skill name="Weeping Shots"/>

</Card>

</GridItem>
</Grid>
