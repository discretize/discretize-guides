---
title: "Captain Mai Trin Boss"
date: "2018-04-17"
image: "./images/header.jpg"
group: "T4"
api: 2932
bosses: 1
difficulties: [{ level: 95, ar: 141 }]
cycle: "Day"
potions: [{ id: 50082 }]
sigils: [{ id: 24615 }, { id: 24868 }]
consumables: [78978]
---

## Start

<Grid>
<Column>  
Aggro the mobs and stack them on the corner. The *Champion Inquest Technician* applies a group-wide <Control name="daze"/> with his stunning shield, use <Boon name="stability"/>, blocks or invulnerables against it.

After you killed the mobs, use the teleporter to enter the boss area. If someone placed a portal at the start where you spawn (<Specialization name="mesmer"/> or <Item id="78978"/>), use `/gg` and take it to get back to the boss before the fight starts (this also skips the initial dialogue). If you do a portal on your own, always walk out of the interaction area after placing - otherwise it bugs and you can't take it yourself.

<Tips>
    <Tip specialization="mesmer">Put down a <Skill id="10197"/> at the start and open it after triggering Mai Trin before you `/gg`.</Tip>
</Tips>
</Column>
<Column width="6" compact>
<Image src="./images/start.jpg" title="The start area" compact/>
</Column>
</Grid>

---

## <Boss red/> Mai Trin <Item id="50082" text="false"/>

<Grid>
<Column>
Mai Trin is protected by ten stacks of *Captain's Shield*, each stack reducing her incoming damage by 10%. The only way to remove stacks is by pulling her into electric fields from Horriks alternating projectiles. Standing in the electric field will remove one stack per second from her. The fire field projectile from Horrik can be reflected and absorbed. You can easily recognize the projectile type from the icon above the targeted player.

The key is to stack on Mai Trin during the whole fight (beware the <Effect name="agony"/> from <Instability name="Social Awkwardness"/>), this way she will always be in an electric field, even if she teleports to the furthest player away.

Your <Specialization name="druid"/> should be able to stay in <Skill id="31869"/> most of the time and keep the party alive, although the amount of conditions and damage can make it difficult to hold the line. Immediately resurrect downed players.

Every 25% health, Mai Trin disappears and additional enemies will spawn while fiery cannons start shooting. Switch your damage to Horrik and deal 25% of his health to make Mai Trin return. Cleave the spawning mobs during downtimes.

Keep in mind that with each phase more cannons start shooting at you, the fight can get quite chaotic in the last phases. Luckily Mai Trin won't have any protecting stacks below 25%, so make sure to finish her quickly.
</Column>

<Column width="7" compact>
<Image src="./images/horrik.jpg" title="First Mate Horrik"/>
<Tips>
    <Tip specialization="mesmer">Use <Skill id="10302"/> against the multitude of projectiles.</Tip>
    <Tip specialization="druid">Trait <Trait id="1075"/> and use <Skill id="12489"/> for additional condition clears.
    Also change <Skill id="12497"/> to <Skill id="12495"/> to reduce incoming damage from spawning mobs every phase and use <Skill id="31496"/> against the cannons.</Tip>
    <Tip specialization="spellbreaker">You can run Spellbreaker to counter the enemy boons and destroy the snipers projectiles at 25% with <Skill id="45333"/>.</Tip>
</Tips>
</Column>
</Grid>

<Image src="./images/mai_trin.jpg" title="Captain Mai Trin"/>
