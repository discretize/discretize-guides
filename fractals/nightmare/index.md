---
title: 'Nightmare'
date: '2018-09-12'
image: './images/ensolyss_crazy.jpg'
group: 'Challenge Mode'
api: 3177
bosses: 3
difficulties: [{ level: 99, ar: 150 }]
record:
  {
    time: '8:36',
    by: { name: 'Snow Crows', tag: 'SC' },
    youtube:
      [
        {
          id: 'WS3chFLSyiM',
          name: 'Van Gherwen',
          specialization: 'Chronomancer',
        },
        { id: 'TOautynEh6o', name: 'Muto', specialization: 'Berserker' },
        { id: '_E6695pbGu8', name: 'Roul', specialization: 'Tempest' },
        { id: 'CsTSgY5gyUI', name: 'Breke', specialization: 'Tempest' },
        { id: 'gP1yv1Pffzg', name: 'Derpy', specialization: 'Druid' },
      ],
  }
cycle: 'Day'
potions: [{ id: 50082 }]
sigils: [{ id: 24615 }, { id: 24868 }, { id: 24658, description: 'after MAMA' }]
consumables: [43360, 8759, 8678, 8764, 8801, 78978]
---

## Assault Knights <Item id="50082" disableText/><Label>426,071 HP</Label>

Stack <Boon name="might"/> before jumping down. Kill the three _Assault Knights_ (Red, Blue and Green), each of them has the same set of abilities: a PBAoE <Control name="knockdown"/> and an AoE <Control name="pull"/> which covers the entire room except the knight's position, both can be dodged.

Break their defiance bars, kill them to awaken MAMA and use `/gg` to reset your cooldowns.

<Image src="./images/mama.jpg" caption="MAMA: The first boss"/>

## MAMA <Item id="50082" disableText/><Label>5,200,519 HP</Label>

Stack <Boon name="might"/> before jumping down. (Now that the mistlock resets cooldowns, <Specialization name="chronomancer"/> can prestack boons and use the mistlock)

MAMA will arise, after being invulnerable for a few seconds its first attack will be a _spinning <Control name="knockback"/>_. The first one should be blocked with <Boon name="aegis"/> from the <Specialization name="mesmer"/> as the <Specialization name="elementalist"/>s will be busy casting <Skill id="5501"/>, learn to dodge the consecutive spinning attacks. It always hits on the _second_ spin animation.

Apart from that, turn away from your party members shortly before the _Vomit Toxin_ hits (orange cone), otherwise you will 'infect' party members in front of you with it.

Every 25%, MAMA gets <Effect name="invulnerability"/> and an _Assault Knight_ (similar to the knights before) will spawn. Quickly break their defiance bar and burst them down as MAMA will continue it's attacks.

When MAMA reaches 33%, it conjures a large _Nightmare Miasma_ field around it which deals enormous damage. It will also become mobile, start jumping to players, offloading shockwaves which <Control name="knockdown"/> and attacking with <Control name="stun"/> cones. It is especially important to immediately kill the last _Assault Knight_ at 25% health.

Fast crowd control and animation knowledge are the keys to this fight.

<Tabs>
<Tab specialization="chronomancer">
If you don't have a <Specialization name="spellbreaker"/>, run <Skill id="10267"/> for the entire fractal due to the <Instability name="No Pain, No Gain"/> mistlock instability.    
        Keep in mind that the third hit of you auto-attack chain (and from your <Skill id="10173"/> clone) remove a boon as well.    
        Also run <Skill id="29519"/> for the stronger defiance bars. Use it immediately on the last assault knight spawning at 25% of MAMA's health.    
        Time your distortions for key attacks like MAMA's spinning and triple shockwave.
</Tab>

<Tab specialization="spellbreaker">
For the entire fractal, remember to place your banners at the boss before doing `/gg` as they will continue to exist through death. This way, you can keep them up permanently even without <Boon name="alacrity"/>.    
        Time <Skill id="45252"/> to remove two boons from the bosses every 20 seconds.
</Tab>

<Tab specialization="weaver">
Depending on your group composition and damage start either in <Skill id="5494" disableText/>/<Skill id="5492" disableText/> with <Skill id="5737"/> (high damage, fast CC) or in <Skill id="5495" disableText/>/<Skill id="5492" disableText/> with <Skill id="5528"/> (low damage).    
        You should have a <Skill id="5624"/> available for each knight, hit them with <Skill id="5733"/> and <Skill id="5725"/> if ready (do not use <Skill id="5725"/> on MAMA if she is only 2-3% away from becoming invulnerable).
</Tab>

<Tab specialization="druid">
If you have problems with incoming damage, swap <Skill id="12497"/> with <Skill id="12495"/> to grant <Boon name="protection"/> to the party.    
        <Skill id="31639"/> from your Electric Wyvern pet deals enormous defiance bar damage to the bosses, they all have a large hitbox.
</Tab>
</Tabs>

---

<Grid>
<GridItem sm="8">
## First set of altars <Item id="50082" disableText/><Item id="24658" disableText/>
You need to cap two altars to continue. Pull the two groups of Krait back to the passage and kill all enemies there. Start capping the altars as soon as possible, but keep in mind that standing inside puts <Effect name="agony"/> on yourself. Only enemy Krait counteract the capping here, you can ignore the Hallucinations.    
Learn the *Red Orb* patterns as they can quickly kill you, *Blue Orbs* will heal you for a large amount of health (even with Agony).    
On a side note, more players do not cap an altar faster. More than one person standing inside is redundant.
</GridItem>
<GridItem sm="4">
<Image src="./images/altars.jpg" caption="The altars"/>
</GridItem>
</Grid>

## Second set of altars <Item id="50082" disableText/><Item id="24658" disableText/>

Again, pull all enemies to the center (wait for the <Specialization name="mesmer"/> to cast <Skill id="10186"/>) and kill them there. The mobs at the left altar (West) can be aggroed with a simple projectile, the mobs on the right side (East) need to be pulled with <Skill id="14381"/> (Longbow), <Skill id="5491"/> (Staff) or by teleporting up and jumping down.

Both side altars can easily be capped by a single person after another player has pulled down the mobs. Please note that you have to wait until the mobs are down before teleporting elsewhere to prevent them from running back.

Contrary to the first set of altars, respawning _Veteran Hallucinations_ counteract capping here. Use <Control name="pull"/> to grab them out of the central altar and always have a positive amount of players inside.

After you capped all three altars, use `/gg` immediately if someone in the party needs it, then you can continue up to the 2nd boss. Before the ramp up, a group of Krait will attack you - simply keep walking to skip them. Use dodges, evades or invulnerables to get through the cascading orbs and disable them by walking through the orb at the top of the ramp.

<Tabs>
<Tab specialization="chronomancer">
Use <Skill id="10363"/> to pull mobs together.    
        You can <Skill id="10200"/> and aggro the Krait at the eastern altar during <Skill id="29830"/> if you're fast. Afterwards teleport up to one of the altars as soon as someone pulled the mobs down.
</Tab>

<Tab specialization="weaver">
<Skill id="5738"/> is very strong against the groups of Krait. Use <Skill id="5536"/> to teleport up to the altars. You can pull both sides with <Skill id="5491"/> (for the right side, jump at the end of your cast).
</Tab>
</Tabs>

---

## Siax the Corrupted <Item id="50082" disableText/><Item id="24658" disableText/><Label>6,138,797 HP</Label>

After the interaction with the red orb in the center of the area, quickly move back to the _Mistlock Singularity_ to avoid aggro from the spawning enemies and stack <Boon name="might"/>. (Now that the mistlock resets cooldowns, <Specialization name="chronomancer"/> can prestack boons and use the mistlock)

During the fight, break his defiance bar (2000 CC damage) as fast as possible to interrupt his _Caustic Explosion_ skill. Siax will wipe your party if you fail to interrupt it with enough crowd control. Pay attention to his bouncing orb barrages, the _Vomit Toxin_ and the exploding _Volatile Hallucinations_ (below 75% health). Do not stand in the red PBAoE when the inner circle reaches the outer to avoid spawning a _Nightmare Hallucination_.

When Siax reaches 66% health, he gains <Effect name="invulnerability"/> and four _Echoes of the Unclean_ will spawn in the North, East, South and West which need to be killed quickly to interrupt his _Caustic Explosions_. The same occurs at 33%, though the adds will have their spawning positions shifted clockwise.

Assign players to each add before the fight starts by setting waypoints. The <Specialization name="mesmer"/> and <Specialization name="druid"/> will usually focus on one mob together due to their lower DPS.

<Image src="./images/siax.jpg" caption="Siax the Corrupted"/>

<Tabs>
<Tab specialization="chronomancer">
Share <Boon name="aegis"/> with your party when the *Nightmare Hallucination* PBAoE goes off or too many *Volatile Hallucinations* explode on the party.    
        With <Skill id="21750"/> you can recast your phantasms on the *Echo of the Unclean* to deal more damage.
</Tab>

<Tab specialization="weaver">
 Start in <Skill id="5495" disableText/>/<Skill id="5492" disableText/> with <Skill id="5528"/> while the last Illusions turn hostile.    
        On the East and South *Echoes of the Unclean*, you can use <Skill id="5697"/> from <Skill id="5516"/> against the wall to deal enormous damage. On the second add spawn you can <Skill id="5697"/> at any location.    
        With normal group damage Siax should turn invulnerable at the end of your first <Skill id="5624"/>. Place a <Skill id="13339"/> and use <Skill id="5697"/> to kill your add in about two seconds.    
        Continue with <Skill id="5531"/> on Siax and restart in <Skill id="5492"/>.    
        If your group damage is too low to pick up your second <Skill id="5516"/> for the second add, place a <Skill id="13339"/> on it, attune to <Skill id="5494" disableText/>/<Skill id="5492" disableText/> and use <Skill id="41125"/> to kill it quickly.    
        Continue with <Skill id="5494" disableText/>/<Skill id="5492" disableText/> and <Skill id="5737"/> on Siax.
</Tab>

<Tab specialization="druid">
If you have problems with the incoming damage, swap <Skill id="12497"/> with <Skill id="12495"/> to grant <Boon name="protection"/> to the party.    
        If you have trouble with the orbs leaving toxic trails, position yourself away from the boss to keep them from the melee area as he throws them on the furthest player (especially recommended if you party has low DPS).
</Tab>    
</Tabs>

---

## Ensolyss of the Endless Torment <Item id="50082" disableText/><Item id="24658" disableText/><Label>14,059,890 HP</Label>

<Grid>
<GridItem>
Walk through the teleporter and trigger Ensolyss once after defeating Siax to gain the new checkpoint and use `/gg` to reset all cooldowns. Stack <Boon name="might"/> next to the mistlock. (Now that the mistlock resets cooldowns, <Specialization name="chronomancer"/> can prestack boons and use the mistlock). Go into the arena, when you start the fight don't stand in the center area of the platform on activation or you will receive a <Control name="knockback"/>.

Nearly all of Ensolyss' attacks do a <Control name="knockback"/> or <Control name="pull"/>, learn to dodge or walk out of every attack. The most dangerous one is his shockwave-shatter combo, he smashes down a stunning yellow shockwave (like MAMA below 33% health), spawns hallucinations on each players position and shatters them after two seconds.

Again, the key to this fight is fast crowd control. Break his defiance bar quickly to interrupt his high damage attacks. Always stack around the center area and do not try to follow him to the edge as he will simply teleport back most of the time.
</GridItem>
<GridItem>
<Image src="./images/ensolyss.jpg" caption="Ensolyss: The final boss"/>
</GridItem>
</Grid>

### Orb phases <Label>66%, 33%</Label>

At 66% and 33%, Ensolyss will teleport to the middle and gain <Effect name="invulnerability"/>. Your party will need to split up and cap five altars, similar to the ones before.  
_Red Orbs_ and stunning shockwaves emerge from the middle, learn the patterns to avoid any damage. Try to catch the _Blue Orbs_ as they heal you for a significant amount. Note that _Blue Orbs_ only spawn at 66% if all altars are capped as fast as possible.

After the orb phases, the defiance bar needs to be broken immediately to prevent Ensolyss from knocking everyone off the platform. His defiance bar will recover shortly after being broken for the first time, break it a second time (especially at 33% health) to further prevent his attacks and deal more damage thanks to <Item id="24868"/> and <Trait id="1502"/>.

Below 66%, Ensolyss gains a new ability where he smashes two quarters of the platform subsequently and knocks everyone inside the **orange** areas off the platform, similar to the skill immediately after the orb phases. It it safe to stand inside the **purple** areas.

Below 33%, he may summon a special shockwave which travels inwards to him (contrary to the ones before) and deal enormous damage to everyone near him. With enough crowd control and DPS this should never occur.

### Final phase <Label><15%</Label>

When Ensolyss reaches 15% health, he will stop using his usual attacks, but only a small bubble in the middle will protect you from his deathly rain. Krait will charge through the middle (indicated by large arrows on the ground) and make positioning harder, kill Ensolyss quickly to finish the fractal.

<Tabs>
<Tab specialization="chronomancer">
Use <Skill id="29519"/> with <Skill id="29830"/> at 100%, 66% and 33%.
</Tab>

<Tab specialization="weaver">
Start in <Skill id="5495" disableText/>/<Skill id="5492" disableText/> with <Skill id="5528"/> while Ensolyss spawns, make sure that your <Skill id="13339"/> and <Skill id="43762"/> hit in the same second as Ensolyss becomes vulnerable.    
        Use <Skill id="5733"/> from your <Skill id="5624"/> for CC.    
        You can share <Skill id="5516"/> with another <Specialization name="weaver"/> as you can only use one per phase anyway.    
        Cast your second <Skill id="5501"/> in the middle of the platform after dodging his first charge. If all five players stand there he will teleport back into it.    
        After the orb phases, reopen in <Skill id="5495" disableText/>/<Skill id="5492" disableText/> and cast <Skill id="5528"/> about a second before the orb phase ends. Make sure to have your <Skill id="5501"/> either finished before the first <Control name="knockback"/> zone goes off or start it after making sure you won't get hit.
</Tab>

<Tab specialization="druid">
Use <Skill id="43636"/> from your Rock Gazelle for the first defiance bar and <Skill id="31639"/> from your Electric Wyvern pet for the second defiance bar. Use consumables if your team is short of CC.
</Tab>    
</Tabs>
