---
title: 'Shattered Observatory'
date: '2020-03-18'
image: './images/header.jpg'
group: 'Challenge Mode'
api: 3458
bosses: 3
difficulties: [{ level: 100, ar: 150 }]
record:
  {
    time: '9:56',
    by: { name: 'Snow Crows/Quantify', tag: 'SC/qT' },
    youtube:
      [
        { id: 'MVR0ay8hn2E', name: 'Roul', specialization: 'Firebrand' },
        { id: 'VzK-hqgyTCQ', name: 'Breke', specialization: 'Warrior' },
        { id: 'IG_30poYaR0', name: 'Nukkuu', specialization: 'Weaver' },
        { id: '9vPGsgxCZDA', name: 'Sangi', specialization: 'Soulbeast' },
        { id: '8228gHSt_PM', name: 'Deathly', specialization: 'Renegade' },
      ],
  }
cycle: 'Day'
potions: [{ id: 50082, description: 'against Arkk' }]
sigils: [{ id: 24615 }, { id: 24868 }]
consumables: [78978, 8759, 8678, 8732]
---

## Skorvald the Shattered <Label>5,551,340 HP</Label>

|                    |                                                           |
| ------------------ | --------------------------------------------------------- |
| Encounter duration | 1:35min                                                   |
| Sigils             | <Item name="impact"/> <Item name="force"/>                |
| Food               | <Item id="41569"/> <Item name="superiorsharpeningstone"/> |
| CC                 | 2200                                                      |

<Grid>
<GridItem sm="7">
Skorvald the Shattered is the first boss in the Shattered Observatory fractal. Be sure to take the *Mistlock Singularity* after accepting the Harbringer's challenge, stack <Boon name="might"/>, <Boon name="quickness"/> and <Boon name="Alacrity"/> on the platform below and start the encounter by activating the orb in the center of the platform.
</GridItem>

<GridItem sm="5">
<Image src="./images/skorvald.jpg" caption="Skorvald the Shattered"/>
</GridItem>
</Grid>

|                                      |                                                                                                                                                                                                                                                                                                                                                                                  |
| ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Solar Bolt**                       | Skorvald often throws a red orb which splits into three after each bounce. Every orb leaves a <Condition name="burning"/> field which deals high damage.                                                                                                                                                                                                                         |
| **Horizon Strike**                   | He marks orange triangles around him and blasts them counter-clockwise which deals high damage and <Control name="knockback"/>. The orange zones themselves dont deal any damage but explode in order, practice the pattern and move into the first triangle after it is gone. Followed by Crimsown Dawn.                                                                        |
| **Crimson Dawn**                     | Blasts the entire platform only excluding a small triangle behind him. Deals high damage.                                                                                                                                                                                                                                                                                        |
| **Radiant Fury**                     | Applies <Condition name="blind"/> and <Condition name="burning"/> to all players it hits and damages allies around them. Recognizable by diminishing red circles around every player, dodge when they collapse. Also sends out a **Solar Discharge** shockwave with <Control name="stun"/> from Skorvald.                                                                        |
| **Warp & Spiral Strike**             | Skorvard teleports to the target location and executes a spinning strike which damages players and applies <Control name="knockback"/>. Also sends out a volley of bolts. Noticeable by a large bomb icon above a player.                                                                                                                                                        |
| **Punishing Kick & Cranial Cascade** | Both attacks release a blast of chaotic mists with high damage and <Control name="knockback"/>. _Punishing Kick_ generates a line in front of him, _Cranial Cascade_ a cascading triangle.                                                                                                                                                                                       |
| **Rush**                             | **Only below 66% health.** Skorvald fixates on a player and charges through him from one edge of the platform to the other.                                                                                                                                                                                                                                                      |
| **Focused Rage**                     | **Only below 66% health.** Basically a larger version of _Cranial Cascade _. Skorvald marks a player with a cross-hair and blasts a large orange cone for high damage and <Control name="knockback"/>. The marked player should turn Skorvald away from other players, during the last second of the animation he does not follow the target anymore and it is safe to step out. |
| **Solar Bloom**                      | **Only below 50% health.** Solar Blooms spawn on the platform which need to be knocked back by damaging them. They fixate on the closest player and explode for high area damage and <Control name="knockback"/>, keep them away from the party.                                                                                                                                 |
| **Beaming Smile**                    | **Only below 50% health.** Skorvald teleports to a random location and summons three large and deadly laser beams. Move out to prevent instant death. He also projects a white beam onto players inflicting <Condition name="fear"/> and <Condition name="blind"/> if you face him upon triggering - simply turn away to avoid it.                                               |
| **Solar Cyclone**                    | **Only below 33% health.** Skorvald starts spinning counter-clockwise and releases conical shockwaves similar to _Cranial Cascade _. There are small safe-spots between each shockwave, learn to stand inside them to avoid the high damage and interrupts.                                                                                                                      |
| **Combustion Rush**                  | **Only below 33% health.** Elite Flux Anomalies start charging through players and <Control name="knockback"/>, indicated by a large arrow on the platform.                                                                                                                                                                                                                      |

<Grid>
<GridItem sm="3">
<Image src="./images/elite-flux-anomaly.jpg" caption="An Elite Flux Anomaly"/>
</GridItem>
<GridItem sm="9">
### Tactic
The key to the fight is fast crowd control, as breaking Skorvald's Defiance bar prevents most of the mechanics. Immediately break it at the start and bring him down to 66% health. Please note, that you cannot _precast_ CC here. Your CC affects Skorvald, as soon as his HP bar appears in the top right corner.

At 66% and 33%, Skorvald becomes immune to damage and the party has to kill four _Elite Flux Anomalies_ to proceed. They spawn on the islands in the Southwest, Southeast, Northeast and Northwest and have to be killed subsequently in that order - the party can use air turbulences to travel between the islands. The Anomalies dont have much health (170.244 HP) but knock players back with shockwaves. Pay attention to the animations and position yourself between Anomaly and wall.

It is worth placing a <Item id="78978"/> portal on the main platform and opening it immediately when you reach the 4th _Elite Flux Anomaly_ to deal more damage to Skorvald before he continues his attacks, especially at 33%. **_Do not take the portal back to the boss before the add has landed its first jump. Otherwise it will leap out of all the damage zones and not die in time for your nuke._**

Below 33% health, Skorvald goes berserk and starts his rotating _Solar Cyclone_ attack. Keep your <Boon name="stability"/> skills for this part. Practice the safe spots and keep the _Solar Blooms_ away from the party, but be ready to dodge if it explodes in party range.

After about 30 seconds, Skorvald starts a huge laser beam attack (_Beaming Smile_) and regains his Defiance bar, if he is not dead yet break the bar and finish him.
</GridItem>

</Grid>


---

## Intermediate part

<Grid>
<GridItem sm="8">
After Skorvald is dead, take the portal to the East and take the left portal in the control center area. You can activate a <Item id="78786"/> to walk during the cutscene and save some time.

You gain a new special action key: `Nova Launch`. For the moment, it is a 2100-range teleport with stunbreak that blocks the next attack (1.75s <Boon name="aegis"/>). Its cooldown refreshes after you bounce a _Globolla Marble_.

You will encounter several glass mobs on the way to the second boss, there are no differences to the regular Shattered Observatory. After the first group of mobs, you will have to bounce a white _Globolla Marble_ nine times with your head to progress.

If you have a spare <Item id="78978"/> or <Item id="44642"/>, you can skip directly to Artsarriv using [this cut](https://www.youtube.com/watch?v=dirYlXZMCc4), otherwise use your `Nova Launch` on the next platform to jump to the elite mob and kill it to proceed to Artsariiv.
</GridItem>

<GridItem sm="4">

<Image src="./images/way_to_artsariiv.jpg" caption="The way to Artsariiv"/>

</GridItem>

</Grid>

---

## Artsariiv <Label>5,962,266 HP</Label>

|                    |                                                           |
| ------------------ | --------------------------------------------------------- |
| Encounter duration | 1:30min                                                   |
| Sigils             | <Item name="impact"/> <Item name="force"/>                |
| Food               | <Item id="41569"/> <Item name="superiorsharpeningstone"/> |
| CC Artsariiv       | 2100                                                      |
| 1. Add phase each  | 650                                                       |
| 2. Add phase each  | <375                                                      |

<Grid>
<GridItem sm="8">
The second boss of the fractal is Artsariiv. The encounter gets activated by bouncing a *Globolla Marble* into her, be sure to prepare <Boon name="might"/> and skills in the northwest beforehand.

Artsariiv summons copies which split into smaller clones upon death, they use martial arts skills, <Control name="knockdown"/>, shoot shocking projectiles and apply a lot of damaging conditions. Discuss whether you kill all adds (safe tactic) or not.

Assign a player for the _Globolla Marble_ bouncing (typically the <Specialization name="renegade"/>) and a backup in case the main bouncer gets _Corporal Reassignment_.

You will need a lot of crowd control skills, consumables like <Item id="8759"/> and <Item id="8678"/> are very strong here.

**Use your `Nova Launch` special action key to quickly move around the platform, the <Boon name="aegis"/> from it counters nearly all mechanics.**

</GridItem>

<GridItem sm="4">

<Image src="./images/artsariiv.jpg" caption="Artsariiv: The second boss"/>

</GridItem>

</Grid>

<Grid>
<GridItem sm="9">
| | |
| --- | --- |
| **Beaming Smile** | Similar to Skorvald below 50% health, Artsariiv generates three large laser beams and projects a white beam onto players which inflicts high damage, <Condition name="blind"/> and <Condition name="fear"/>. Turn away from the source to prevent application. |
| **Astral Surge** | Artsariiv spawns a lot of small point blank area of effects (PBAoE) on the ground which deal medium damage, try to stay out of them when the inner circle reaches the outer. |
| **Corporal Reassignment** (*Doom*) | Designates a player for timed explosion, recognizable by a red skull above the target and a large notification message. The player must seek containment inside the white bubble in the center area or will kill himself and allies.<br/>The white bubble is only available after the respawning **Temporal Anomaly** is killed.<br/> *This is the highest priority for any damage dealer.* |
| **Solar Discharge** | From time to time, Artsariiv switches her location and moves to another corner. When doing so, she jumps over the platform and emerges a single *Solar Discharge* shockwave which applies <Control name="knockdown"/>. This ability can be jumped over. |
| **Red Marble** | Artsariiv throws a lot of red orbs during the fight, watch out for a large *Red Marble* surrounded by red orbs - it deals <Control name="knockdown"/> and deals medium damage. Unfortunately reacting in close melee range is nearly impossible. You can utilize reflects against the various orbs. |
| **Slam** | Deals <Control name="knockback"/> and deals damage in a short range around Artsariiv. Recognizable by an orange circle around her, simply dodge it. |
| **Mib Ring** | Artsariiv herself and all her clones during the intermediate phases create a purple miasma field inside their hitboxes, dont stand too close to avoid damage. |
| **Globolla Marble** | **Only below 66% health.** Artsariiv throws a huge, white *Globolla Marble* which needs to be bounced back to her. The next position of the marble is always indicated by a large white circle, the next but one position by a smaller white circle. This part is typically soloed by the <Specialization name="Renegade"/>. Strip boons if <Instability name="No pain no gain"/> is present before you hop to the second circle. Dont forget to assign a backup. <br/>Use `Nova Launch` to travel between the locations as it refreshes after each bounce. The backup only needs to stand inside the first blue circle. The main bouncer can take over after that. Note: There is enough time to do the first blue circle, launch into the containment chamber and bounce into the second circle. This however is not recommended for inexperienced players.
</GridItem>

<GridItem sm="3">
<Image src="./images/so-doom.jpg" caption="A player doomed to explode"/>
<Image src="./images/so-temporal-anomaly.jpg" caption="A Temporal Anomaly"/>
</GridItem>
</Grid>

### Tactic

Immediately after the fight starts, Artsariiv channels her huge triple-laser attack _Beaming Smile_ (similar to Skorvald at low health). Do not get caught within those lasers and turn away from her to prevent <Condition name="blind"/> and <Condition name="fear"/>.

Kill the first _Temporal Anomaly_ to spawn a containment for _Corporal Reassignment_ and cleave the first set of clones. When you feel safe enough, move northwest to Artsariiv, break her defiance bar and bring her down to 66% health.

At 66% and 33% health, Artsariiv splits up into five and nine clones respectively. Those clones can't be damaged and only despawn when their defiance bar is broken. All party members get resurrected afterwards, so don't waste time on dead players.

The central clone has the highest priority as it shoots additional damaging orbs. Also pay attention to the single _Globolla Marble_ during the CC phase, if it isn't bounced it deals medium damage to the party.

After the crowd control phases are over, Artsariiv reappears in the middle of the platform and conjures an _Obliterate_ attack and multiple orange void zones which need to be dodged. She also does her _Beaming Smile_ attack similar to the start of the fight. Kill the respawned _Temporal Anomaly_ and clones (optional) before switching to her again.

Below 66% health, Artsariiv throws a large _Globolla Marble_ from time to time which needs to be bounced back to her over nine locations. Failing to bounce usually results in a party wipe, choose a reliable player beforehand to solo this (usually the profession with the least amount of damage <Specialization name="Renegade"/>).

After the fight is over, take the portal in the North and move forward to get to Arkk.

---

## Arkk <Item id="50082" disableText/><Label>9,942,250 HP</Label>

|                    |                                                                         |
| ------------------ | ----------------------------------------------------------------------- |
| Encounter duration | 2:00min                                                                 |
| Sigils             | <Item name="impact"/> <Item name="force"/>                              |
| Food               | <Item id="41569"/> <Item name="powerfulpotionofslayingscarletsarmies"/> |
| CC                 | 1800                                                                    |

<Grid>
<GridItem sm="8">
Arkk is the third and final boss of the fractal. An attentive player may have noticed the `Nova Launch` special action key became even stronger now, doing medium damage, a 200 <Control name="launch"/> and executing a Blast finisher. Thanks to this, other crowd control skills are negligible for this fight.

In contrast to the other enemies in this fractal, Arkk belongs to Scarlet's army and <Item id="50082"/> works against him.

Arkk himself has no melee attacks, but a lot of abilities which can make the fight rather chaotic for inexperienced groups. However, all damage can be avoided and therefore a healer is not mandatory. More party DPS means less boss mechanics.

Stack <Boon name="might"/> (you can use `Nova Launch`) and renew your _Mistlock Singularity_ before activating the orb to teleport to Arkk.

</GridItem>
<GridItem sm="4">
<Image src="./images/arkk.jpg" caption="Arkk: The final boss"/>
</GridItem>
</Grid>

<Grid>
<GridItem sm="9">
| | |
| --- | --- |
| **Blinding Radiance** | Similar to the other bosses, Arkk has the white beam ability which damages players facing him and inflicts <Condition name="blind"/> and <Condition name="fear"/>. It is easily recognizable by a large eye icon above Arkk. If you have problems receiving damage despite looking away, try to wiggle left/right while turned away to minimize the risk. |
| **Solar Fury & Solar Discharge** | Arkk prepares this ability by conjuring a large red orb above his head. When the orbs disappears (after ~4 seconds), he launches bouncing orbs towards every player, leaving a <Condition name="burning"/> fire field after each bounce. At the same time, he emerges a stunning *Solar Discharge* shockwave which needs to be dodged or jumped over.<br/>The orbs from this attack can be **reflected** to prevent the fire zones on the floor from spawning. **If your party has no reflects, every player needs to use `Nova Launch` the moment he throws the orbs to block the fire zones. This is especially important below 40% and can easily wipe your team if one player fails to do so.**  |
| **Corporal Reassignment** (*Doom*) | The same mechanic as on Artsariiv. Designates a player for timed explosion, the party has to kill a **Temporal Anomaly** (56k HP) to spawn a containment for the target. |
| **Temporal Realignment** (*Green*) | Similar to the green circle mechanic on *Vale Guardian*. Designates a player to take 80% of their health in damage, split between any nearby allies. Try to have at least three players inside the green circle. **If no other player is inside the circle upon collapsing, it detonates the whole party.** |
| **Focused Rage** | Similar to Skorvald, Arkk marks a player with a crosshair and blasts the area with damage and a <Control name="knockback"/>. If you are marked, turn Arkk away from the other party members and the white containment bubble and move out during the last second of the animation. |
| **Horizon Strike & Diffractive Edge** | Again, a mechanic taken from Skorvald. Arkk marks orange triangles around him and blasts them counter-clockwise. The first triangle is always the first to be blasted.<br/>*Diffractive Edge* is basically the same ability, it just blasts all triangles at the same time but leaves a small safe spot behind Arkk. |
| **Starburst Cascade** | **Only below 60% health.** Arkk sends out a wave of cascading energy across the platform, applying <Control name="float"/> to every player caught inside. This ability can be jumped over. |
| **Disappearing Platforms** | **Only below 40% health.** In the final phase of the fight, random platforms temporarily disappear. If you fall through the ground, you will get teleported to above and start falling down - use your `Nova Launch` to get back into the fight. |
| **Solar Stomp** | **Only below 40% health.** Arkk vanishes in dust evading all attacks, when he reappears he stomps the ground, damages nearby enemies, executes a <Control name="knockback"/> and sends out a volley of bolts. Be careful to not let it push you off the platform. |
| **Rolling Chaos** | **Only below 40% health.** Recognizable by a small red arrow emanating from Arkk. Launches a rolling red marble in the designated direction which deals high damage. |
| **Beaming Smile / DDR** | **Only below 30% health.** Similar to the previous bosses, Arkk summons three large laser beams while simultaneously projecting the white beams onto players. Move out and turn away. |
</GridItem>

<GridItem sm="3">
<Image src="./images/so-arkk-eye.jpg" caption="The Blinding Radiance ability"/>
<Image src="./images/so-arkk-solar.jpg" caption="Arkk preparing Solar Fury"/>
<Image src="./images/so-arkk-green.jpg" caption="Temporal Realignment"/>
</GridItem>
</Grid>

### Tactic

Immediately when the fight starts, turn away as Arkk uses his _Blinding Radiance_ ability. Always prioritize the respawning _Temporal Anomalies_, you only have a short time window to kill them before the player designated for _Corporal Reassignment_ explodes. The doomed person can see a white circle collapsing below the Temporal Anomaly, the moment it completes the explosion goes off.

A lot of the mechanics can occur at the same time, practice to avoid every single one.

Before triggering the Solar Bloom phases, you might want to wait for another Temporal Anomaly/Corporal Reassignment combination to prevent chaos during the intermediate phase.

#### Solar Blooms <Label>80%, 50%, 30%</Label>

When Arkk reaches 80% health, he gains <Effect name="invulnerability"/> and players have to kite four _Solar Blooms_ into the pillars in the corners to destroy them.

A common strategy is to assign four players to the spawning locations in the North, East, South and West, as the Solar Blooms fixate on the closest player a few seconds after their spawn. Players take aggro of their designated Solar Bloom and kite them clockwise to the next pillar on the right. You can also use direct damage skills to push back the Blooms.

<Image src="./images/so-solar-bloom.jpg" caption="Solar Blooms fixate on the closest player"/>

The fifth, remaining player should be a DPS ready to take out a possibly spawning _Temporal Anomaly_ during the phase. This player must also be ready to join the player with the green circle.

After every Solar Bloom phase, Arkk's defiance bar has to be broken immediately or he kills all players. Use your `Nova Launch` ability for an additional <Control name="launch"/> if you are short of crowd control skills.

#### Elite Bosses <Label>70%, 40%</Label>

At 70% and 40% of Arkk's health, the party gets teleported to another dimension where you have to fight the _Elite Archdiviner_ from the [Cliffside Fractal](https://discretize.eu/fractals/cliffside) and the _Elite Brazen Gladiator_ from the [Chaos Isles Fractal](https://discretize.eu/fractals/chaos-isles) respectively.

Both bosses behave similar to their real version and are surrounded by four mobs (Cultists/Golems). Try to kill the adds before finishing the boss as they follow you back to Arkk. Remember the party-wide <Control name="daze"/> if the third auto-attack of the Gladiator hits someone. The _Elite Brazen Gladiator_ also does his huge pull attack below 50% health, prepare your `Nova Launch` skill to break his breakbar then.

#### Final phase <Label><40%</Label>

Below 40% health, random platforms start disappearing temporarily. Due to this mechanic, space is very limited and resurrecting a downed player is nearly impossible.
Sometimes _Temporal Anomalies_ spawn on vanished platforms which makes the fight even more challenging.

The most important thing is to keep calm. Remember that every single ability can be avoided, `Nova Launch` the _Solar Fury_ orbs, jump or dodge through the _Starburst Cascade_ and _Solar Stomp_ attacks, turn away from the _Blinding Radiance_ and move accordingly to the _Horizon Strike_ pattern. Keep a cool head and finish the fight!
