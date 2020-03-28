---
title: 'Captain Mai Trin Boss'
date: '2020-03-27'
image: './images/header.jpg'
group: 'T4'
api: 2932
bosses: 1
difficulties: [{ level: 95, ar: 141 }]
cycle: 'Day'
potions: [{ id: 50082 }]
sigils: [{ id: 24615 }, { id: 24868 }]
consumables: [78978]
---

<Grid>
<GridItem sm="8">
## Start  
  
Aggro the mobs and stack them on the corner. The *Champion Inquest Technician* applies a group-wide <Control name="daze"/> with his stunning shield, use <Boon name="stability"/>, blocks or invulnerables against it.

After you killed the mobs, use the Mistlock Singularity to reset cooldown then the teleporter to enter the boss area.
</GridItem>
<GridItem sm="4">
<Image src="./images/start.jpg" caption="The start area"/>
</GridItem>
</Grid>

---

## Mai Trin <Item id="50082" disableText/>

<Grid>
<GridItem sm="7">
Mai Trin is protected by ten stacks of *Captain's Shield*, each stack reducing her incoming damage by 10%. The only way to remove stacks is by pulling her into electric fields from Horriks alternating projectiles. Standing in the electric field will remove one stack per second from her. The fire field projectile from Horrik can be reflected and absorbed. You can easily recognize the projectile type from the icon above the targeted player.

The key is to stack on Mai Trin during the whole fight (beware the <Effect name="agony"/> from <Instability name="Social Awkwardness"/>), this way she will always be in an electric field, even if she teleports to the furthest player away.

Every 25% health, Mai Trin disappears and additional enemies will spawn while fiery cannons start shooting. Switch your damage to Horrik and deal 25% of his health to make Mai Trin return. Cleave the spawning mobs during downtimes.

Keep in mind that with each phase more cannons start shooting at you, the fight can get quite chaotic in the last phases. Luckily, Mai Trin won't have any protecting stacks below 25%, so make sure to finish her rather than Horrik (Killing Mai Trin finishes the fractal).

<Image src="./images/mai_trin.jpg" caption="Captain Mai Trin"/>
</GridItem>

<GridItem sm="5">
  
<Image src="./images/horrik.jpg" caption="First Mate Horrik"/>

<Tabs>
<Tab specialization="Revenant">
It is favorable to run <Skill name="Legendary Centaur Stance"/> for projectile absorbtion with <Skill name="Protective Solace"/> and condition cleanse with <Skill name=" Purifying Essence"/>. Recommended to use the Salvation / Invocation / Renegade trainline combo variant for more energy for the whole fight. Do not forget that <Skill name="Warding Rift"/> (Staff 3) can block Horrik's projectile if you stand into it!
</Tab>
</Tabs>

<Tabs>
<Tab specialization="soulbeast">
You can block Horrik's cannon projectile with <Skill name="Counterattack" specialization="ranger"/> (Greatsword 4).
</Tab>
</Tabs>
</GridItem>
</Grid>
