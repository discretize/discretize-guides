---
potions:
  - id: 50082
hasCM: false
cycle: Day
layout: src/layouts/Fractal.astro
date: "2023-08-27T18:22:00.747Z "
title: Captain Mai Trin Boss
image: images/header_old.jpg
group: T4
api: 2932
bosses: 1
difficulties:
  - level: 95
    ar: 141
sigils:
  - id: 24615
  - id: 24868
consumables:
  - 78978
record: {}
long_description: ""
description: Horrik, unleash the cannons!
---

<Grid>
<GridItem sm="12">

## Start

Aggro the mobs and stack them on the corner. Use <Boon name="Stability" />, blocks or skills that make you invulnerable to counter the _Champion Inquest Technician_'s attack that applies a group-wide <Control name="Daze"/>. 

After all the enemies are dead, use the _Mistlock Singularity_ to reset cooldowns and interact with the teleporter to enter the boss area.

</GridItem>

<GridItem sm="8">

<Tabs>
<Tab specialization="Weaver">
You can precast <Skill name="Conjure Fiery Greatsword"/> without it despawning early by placing a portal utilizing <Item id="78978"/> near the Mistlock Singularity and using it to return to the Mistlock Singularity for the precast before Mai Trin starts talking.
</Tab>
</Tabs>
</GridItem>

<GridItem sm="4">
![Starting area](images/start.jpg)
</GridItem>
</Grid>

---

## Mai Trin <Item id="50082" disableText/>

<Grid>
<GridItem sm="7">
When you enter the arena, there is a hard <Attribute name="Agony Resistance" /> check, resulting in being instantly downed if you do not have the minimum requirement.

Mai Trin is protected by ten stacks of [Captain’s Shield](https://wiki.guildwars2.com/wiki/Captain%27s_Shield), each stack reducing her incoming damage by 10%. The only way to remove stacks is by pulling her into electric fields from Horrik's _Electric Blast_. Standing in the electric field will remove one stack per second from her.You can easily recognize it from the icon above the targeted player (see image) and the telegraphed electric fields on the ground. 
![Electric Blast](fractals/captain-mai-trin-boss/images/Electric_blast.png)
 Horrik's other projectile attack, _Cannon Blast_ which deals damage and inflicts <Condition name="Burning" /> on targets can be reflected and absorbed. 

The key is to stack on Mai Trin during the whole fight: this way she will always be in an electric field, even if she teleports to the furthest player away.

Every 25% health, Mai Trin disappears and additional enemies spawn while fiery cannons shoot. Change your target to Horrik and bring him down by 25% of his health to bring Mai Trin back. Use <Control name="Pull"/> abilities to stack the adds together and cleave them down.

Keep in mind that with each phase, more cannons start shooting at you. The fight can get quite chaotic in the last phases. Luckily, Mai Trin won't have any protective stacks below 25%, so focus your damage on her. It is vital to bring reflections and <Boon name="Stability"/> to counter the elite adds that spawn after Mai Trin disappears at 25%. Killing Mai Trin finishes the fractal, therefore there is no incentive to kill Horrik before that _unless you are going for the **Horrik's Horror** achievement (see below)_ . 
<Achievement name="Horrik's Horror">
  Defeat Mai Trin's 2nd-in-command.
 _"Horrik hits hard, but you hit harder."_
</Achievement>


<Tabs>
<Tab specialization="Revenant">
It is favorable to run <Skill name="Legendary Centaur Stance"/> for projectile absorption with <Skill name="Protective Solace"/> and condition cleanse with <Skill name=" Purifying Essence"/>. Alternatively, if more protection isn't needed, you can run <Skill name="Legendary Dwarf Stance"/> to give <Boon name="Stability"/> with <Skill name="Inspiring Reinforcement"/>. Do not forget that <Skill name="Warding Rift"/> (Staff 3) can block Horrik's projectile if you stand into it!
</Tab>

<Tab specialization="Soulbeast">
You can block Horrik's cannon projectile with <Skill name="Counterattack"/> (Greatsword 4).
</Tab>

<Tab specialization="Berserker">
Play Greatsword with <Skill name="blood reckoning"/> for maximum cleave with double <Skill name="arcdivider"/>.
</Tab>

<Tab specialization="Firebrand">
Bring <Skill name="mantraofliberation"/> and <Skill name="wallofreflection"/>. Coordinate with your <Specialization name="Renegade"/>! Use your pulls on <Skill name="Blazing Edge"/> and <Skill name="Chapter 3: Heated Rebuke"/> to stack up the additional adds.
</Tab>
</Tabs>

</GridItem>

<GridItem sm="5">

![First mate Horrik](images/horrik.jpg)
![Captain Mai Trin](images/mai_trin.jpg)

</GridItem>
</Grid>
