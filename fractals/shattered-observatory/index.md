---
title: "Shattered Observatory"
date: "2018-04-17"
image: "./images/header.jpg"
group: "Challenge Mode"
api: 3458
bosses: 3
difficulties: [{ level: 100, ar: 150 }]
record: { time: "9:56", by: { name: "Snow Crows", tag: "SC" }, youtube: [{ id: "cLTNHl_A28I", name: "Van Gherwen", specialization: "Chronomancer" }, { id: "phbHkROKlm8", name: "Muto", specialization: "Berserker" }, { id: "ME2QF0X_NJo", name: "hint", specialization: "Tempest" }, { id: "RLkDIlMEx8U", name: "Roul", specialization: "Dragonhunter" }]}
cycle: "Day"
potions: [{ id: 50082, description: "against Arkk" }]
sigils: [{ id: 24615 }, { id: 24868 }]
consumables: [78978, 8759, 8678, 8732]
---

## <Boss/> Skorvald the Shattered <Label>5,551,340 HP</Label>

<Grid>
<Column>
Skorvald the Shattered is the first boss in the Shattered Observatory fractal. Be sure to take the *Mistlock Singularity* after accepting the Harbringer's challenge, stack <Boon name="might"/> on the platform below and start the encounter by activating the orb in the center of the platform.
</Column>
<Column width="5" compact>
<Image src="./images/skorvald.jpg" title="Skorvald the Shattered" compact/>
</Column>
</Grid>

<Mechanics>
| | |
| --- | --- |
| **Solar Bolt** | Skorvald often throws a red orb which splits into three after each bounce. Every orb leaves a <Condition name="burning"/> field which deals high damage. |
| **Horizon Strike** | He marks orange triangles around him and blasts them counter-clockwise which deals high damage and <Control name="knockback"/>. The orange zones themselves dont deal any damage but explode in order, practice the pattern and move into the first triangle after it is gone. Followed by Crimsown Dawn. |
| **Crimson Dawn** | Blasts the entire platform only excluding a small triangle behind him. Deals high damage. |
| **Radiant Fury** | Applies <Condition name="blind"/> and <Condition name="burning"/> to all players it hits and damages allies around them. Recognizable by diminishing red circles around every player, dodge when they collapse. Also sends out a **Solar Discharge** shockwave with <Control name="stun"/> from Skorvald. |
| **Warp & Spiral Strike** | Skorvard teleports to the target location and executes a spinning strike which damages players and applies <Control name="knockback"/>. Also sends out a volley of bolts. Noticeable by a large bomb icon above a player. |
| **Punishing Kick & Cranial Cascade** | Both attacks release a blast of chaotic mists with high damage and <Control name="knockback"/>. *Punishing Kick* generates a line in front of him, *Cranial Cascade* a cascading triangle. |
| **Rush** | **Only below 66% health.** Skorvald fixates on a player and charges through him from one edge of the platform to the other. |
| **Focused Rage** | **Only below 66% health.** Basically a larger version of *Cranial Cascade *. Skorvald marks a player with a cross-hair and blasts a large orange cone for high damage and <Control name="knockback"/>. The marked player should turn Skorvald away from other players, during the last second of the animation he does not follow the target anymore and it is safe to step out. |
| **Solar Bloom** | **Only below 50% health.** Solar Blooms spawn on the platform which need to be knocked back by damaging them. They fixate on the closest player and explode for high area damage and <Control name="knockback"/>, keep them away from the party. |
| **Beaming Smile** | **Only below 50% health.** Skorvald teleports to a random location and summons three large and deadly laser beams. Move out to prevent instant death. He also projects a white beam onto players inflicting <Condition name="fear"/> and <Condition name="blind"/> if you face him upon triggering - simply turn away to avoid it. |
| **Solar Cyclone** | **Only below 33% health.** Skorvald starts spinning counter-clockwise and releases conical shockwaves similar to *Cranial Cascade *. There are small safe-spots between each shockwave, learn to stand inside them to avoid the high damage and interrupts. |
| **Combustion Rush** | **Only below 33% health.** Elite Flux Anomalies start charging through players and <Control name="knockback"/>, indicated by a large arrow on the platform. |
</Mechanics>

<Grid>
<Column width="4" compact>
<Image src="./images/elite-flux-anomaly.jpg" title="An Elite Flux Anomaly" compact/>
</Column>
<Column>
### Tactic
The key to the fight is fast crowd control, as breaking Skorvald's defiance bar prevents most of the mechanics. Immediately break it at the begin and bring him down to 66% health.

At 66% and 33%, Skorvald becomes immune to damage and the party has to kill four _Elite Flux Anomalies_ to proceed. They spawn on the islands in the Southwest, Southeast, Northeast and Northwest and have to be killed subsequently in that order - the party can use air turbulences to travel between the islands. The Anomalies dont have much health (170.244 HP) but knock players back with shockwaves. Pay attention to the emotes and position yourself between the Anomaly and a wall.

It is worth placing a <Item id="78978"/> portal on the main platform and opening it immediately when you reach the 4th Anomaly  to deal more damage to Skorvald before he continues his attacks, especially at 33%.

Below 33% health, Skorvald goes berserk and starts his rotating _Solar Cyclone_ attack. Keep your <Boon name="stability"/> skills for this part. Practice the safe spots and keep the _Solar Blooms_ away from the party, a Druid is the perfect candidate for this job with staff auto-attack but be ready to dodge if it explodes in party range.

After about 30 seconds, Skorvald starts a huge laser beam attack (_Beaming Smile_) and regains his defiance bar, if he is not dead yet break the bar and finish him.
</Column>
</Grid>

<Tabs>
<Tab name="Mesmer">
If you don't have a <Specialization name="spellbreaker"/>, run <Skill id="10267"/> for the entire fractal due to the <Instability name="No Pain, No Gain"/> mistlock instability. Alternatively you can use <Skill id="10185"/> which also grants permanent <Boon name="protection"/> to the party upon sharing, but don't use it before a <Skill id="29830"/>, otherwise the cooldown will be too long for the next set of boons.<br/>Keep in mind that the third hit of you auto-attack chain (and from your <Skill id="10173"/> clone) remove a boon as well.
</Tab>

<Tab name="spellbreaker">
Time <Skill id="45252"/> to remove two boons from the bosses every 20 seconds.
</Tab>

<Tab name="weaver">
Use <Skill id="21656"/> if you have less than two weavers, run air to try hard or have might troubles, then make sure to blast on the first and fourth island.  

Use the standard Air Opener with a precast <Skill id="5516"/> from the mistlock. If you group damage is normal you should finish the first phase in <Skill id="5492" text="false"/>/<Skill id="5492" text="false"/> with a <Skill id="5624"/> in hand. Drop the hammer, use <Skill id="5680"/> to get faster to the air tubulence. Attune <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> and start casting <Skill id="5528"/> before jumping in the air turbulence, you will finish casting it mid air. Attune <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/> and use <Skill id="5548"/>. Stay in <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/> and finish the anomaly with <Skill id="5491"/> if it is not dead already.

NEVER cast <Skill id="5548"/> on the first anomaly before at least one player is on the island, since the anomaly will then cast the fire aoe, that might kill players before they can move after the air turbulence.

Cast <Skill id="5548"/> and <Skill id="43762"/> on the second anomaly while she evades, attune to <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> and begin to cast <Skill id="5552"/> so that it instantly hits, when the evade ends. You will have to jump above the shockwave. Hit the anomaly with <Skill id="41125"/>. If it is not dead attune <Skill id="5492" text="false"/>/<Skill id="5494" text="false"/> and cast a new <Skill id="5548"/>. Attune to <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> before taking the next air turbulence.

Start with <Skill id="5528"/> on the third anomaly followed by <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/> and <Skill id="5548"/>. If the mesmer places his wells on this island follow this by two dodge to avoid getting knocked out of the wells. Attune to <Skill id="5492" text="false"/>/<Skill id="5492" text="false"/> before leaving the island.

If all might blasts were correct and you group fast enough you should have 25 stacks of might now, all boons and elements of rage for 8 secs. 

Place a <Skill id="5548"/> on the last anomaly and take the portal back to Skorvald while summening your <Skill id="5516"/>. The warrior will kill the last anomaly with the weaver fonts. Keep the last anomaly in your target to time your burst according to how fast it dies. Start your cast in this order: <Skill id="5531"/> => <Skill id="5501"/> => <Skill id="5737"/>. Ideally <Skill id="5737"/> finishes casting in the second Skorvald becomes vulnerable again. Continue with <Skill id="5548"/>, <Skill id="41125"/>, <Skill id="5624"/>, <Skill id="5725"/>, <Skill id="5492" text="false"/>/<Skill id="5492" text="false"/>, <Skill id="5539"/> x3, 1x <Skill id="5726"/> chain. You can place a <Skill id="5548"/> and cast maybe two additional <Skill id="5491"/> before Skorvald ports. 

If everything went well Skorvald will be at 33% and you can repeat from <Skill id="5680"/>. If you didn't have enough damage start with pre casting <Skill id="5528"/> and so on in the middle after the second charge.

One of the most important things in this fight is to keep up might and boons at the four anomalies. To achieve this you need to be fast enough with your damage, hit your blasts correct and not get hit by the knockdowns.

For the try hard version take three air weavers. The advantage of this composition is that your mesmer can run inspiration domination, which increases alacrity uptime and allows you to nuke again 3-5 seconds faster, with the disadvantage that you really have to look after might. But for daily runs you will probably lose those seconds at the adds or to the nerfed weaver damage and have your cds ready for the nuke anyway. The time difference is maybe 8-10 seconds under ideal circumstances.

</Tab>

<Tab name="druid">
Combine <Trait id="1038"/> with <Skill id="12569"/> for party <Boon name="stability"/> below 33% health.
</Tab>

</Tabs>


---

## Intermediate part

<Grid>
<Column>
After Skorvald is dead, take the portal to the East and take the left portal in the control center area. You can activate a <Item id="78786"/> to walk during the cutscene and save some time.

You gain a new special action key: `Nova Launch`. For the moment, it is a 2100-range teleport with stunbreak that blocks the next attack (1.75s <Boon name="aegis"/>). Its cooldown refreshes after you bounce a _Globolla Marble_.

You will encounter several glass mobs on the way to the second boss, there are no differences to the regular Shattered Observatory. After the first group of mobs, you will have to bounce a white _Globolla Marble_ nine times with your head to progress.

If you have a spare <Item id="78978"/> or <Item id="44642"/>, you can skip directly to Artsarriv using [this cut](https://www.youtube.com/watch?v=QBvKQu9EqEc), otherwise use your `Nova Launch` on the next platform to jump to the elite mob and kill it to proceed to Artsariiv.
</Column>
<Column width="6" compact>
<Image src="./images/way_to_artsariiv.jpg" title="The way to Artsariiv" compact/>
</Column>
</Grid>

---

## <Boss/> Artsariiv <Label>5,962,266 HP</Label>

<Grid>
<Column>
The second boss of the fractal is Artsariiv. The encounter gets activated by bouncing a *Globolla Marble* into her, be sure to prepare <Boon name="might"/> and skills in the northwest beforehand.

Artsariiv summons copies which split into smaller clones upon death, they use martial art skills, <Control name="knockdown"/>, shoot shocking projectiles and apply a lot of damaging conditions. Discuss whether you kill all adds (safe tactic) or not.

Assign a player for the _Globolla Marble_ bouncing (typically the <Specialization name="warrior"/>) and a backup in case the main bouncer gets _Corporal Reassignment_.

You will need a lot of crowd control skills, consumables like <Item id="8759"/> and <Item id="8678"/> are very strong here.

**Use your `Nova Launch` special action key to quickly move around the platform, the <Boon name="aegis"/> from it counters nearly all mechanics.**
</Column>
<Column width="6" compact>
<Image src="./images/artsariiv.jpg" title="Artsariiv: The second boss" compact/>
</Column>
</Grid>

<Mechanics>
<Grid>
<Column>
| | |
| --- | --- |
| **Beaming Smile** | Similar to Skorvald below 50% health, Artsariiv generates three large laser beams and projects a white beam onto players which inflicts high damage, <Condition name="blind"/> and <Condition name="fear"/>. Turn away from the source to prevent application. |
| **Astral Surge** | Artsariiv spawns a lot of small point blank area of effects (PBAoE) on the ground which deal medium damage, try to stay out of them when the inner circle reaches the outer. |
| **Corporal Reassignment** (*Doom*) | Designates a player for timed explosion, recognizable by a red skull above the target and a large notification message. The player must seek containment inside the white bubble in the center area or will kill himself and allies.<br/>The white bubble is only available after the respawning **Temporal Anomaly** is killed.<br/> *This is the highest priority for any damage dealer.* |
| **Solar Discharge** | From time to time, Artsariiv switches her location and moves to another corner. When doing so, she jumps over the platform and emerges a single *Solar Discharge* shockwave which applies <Control name="knockdown"/>. This ability can be jumped over. |
| **Red Marble** | Artsariiv throws a lot of red orbs during the fight, watch out for a large *Red Marble* surrounded by red orbs - it deals <Control name="knockdown"/> and deals medium damage. Unfortunately reacting in close melee range is nearly impossible. You can utilize reflects against the various orbs. |
| **Slam** | Deals <Control name="knockback"/> and deals damage in a short range around Artsariiv. Recognizable by an orange circle around her, simply dodge it. |
| **Mib Ring** | Artsariiv herself and all her clones during the intermediate phases create a purple miasma field inside their hitboxes, dont stand too close to avoid damage. |
| **Globolla Marble** | **Only below 66% health.** Artsariiv throws a huge, white *Globolla Marble* which needs to be bounced back to her. The next position of the marble is always indicated by a large white circle, the next but one position by a smaller white circle.<br/>Use `Nova Launch` to travel between the locations as it refreshes after each bounce. Usually the <Specialization name="warrior"/> soloes this mechanic, but other players should keep an eye on it and serve as a backup in case the main bouncer gets *Corporal Reassignment*.
</Column>

<Column width="4" compact>
<Image src="./images/so-doom.jpg" title="A player doomed to explode"/>
<Image src="./images/so-temporal-anomaly.jpg" title="A Temporal Anomaly"/>
</Column>
</Mechanics>
</Grid>

### Tactic

Immediately after the fight starts, Artsariiv channels her huge triple-laser attack _Beaming Smile_ (similar to Skorvald at low health). Do not get caught within those lasers and turn away from her to prevent <Condition name="blind"/> and <Condition name="fear"/>.

Kill the first _Temporal Anomaly_ to spawn a containment for _Corporal Reassignment_ and cleave the first set of clones. When you feel safe enough, move northwest to Artsariiv, break her defiance bar and bring her down to 66% health.

At 66% and 33% health, Artsariiv splits up into five and nine clones respectively. Those clones can't be damaged and only despawn when their defiance bar is broken. All party members get resurrected afterwards, so don't waste time on dead players.

The central clone has the highest priority as it shoots additional damaging orbs. Also pay attention to the single _Globolla Marble_ during the CC phase, if it isn't bounced it deals medium damage to the party.

After the CC phases are over, Artsariiv reappears in the middle of the platform and conjures an _Obliterate_ attack and multiple orange void zones which need to be dodged. She also does her _Beaming Smile_ attack similar to the start of the fight. Kill the respawned _Temporal Anomaly_ and clones (optional) before switching to her again.

Below 66% health, Artsariiv throws a large _Globolla Marble_ from time to time which needs to be bounced back to her over nine locations. Failing to bounce usually results in a party wipe, choose a reliable player beforehand to solo this (usually the least important profession - <Specialization name="warrior"/>).

After the fight is over, take the portal in the North and move forward to get to Arkk.

<Tabs>
<Tab name="Mesmer">
From this fight on, you can use `Nova Launch` immediately before sharing boons to spread <Boon name="aegis"/> and prevent dangerous boss mechanics. Note that you can pre-stack clones on Artsariiv with <Skill id="10173"/>.
</Tab>

<Tab name="spellbreaker">
Leave a <Skill id="45333"/> and place your banners before you leave for marble bouncing.
</Tab>

<Tab name="weaver">
**Nuke**

For the nuke strategy you want to damage Artsariiv to 66% life before the first doom explodes. To achieve this you stack might in the middle and pull from the other side from which she will go, to make sure the **Beaming Smile** will be away from that spot.

Pre cast <Skill id="5528"/> and <Skill id="5548"/> in the middle. You can hit Artsariiv with one <Skill id="5491"/> before you have to `Nova Launch` to the first spot, to avoid being hit by the **Beaming Smile**.

Now summon your <Skill id="5516"/> followed by <Skill id="5531"/>, then cast <Skill id="5548"/> and <Skill id="43762"/>  on Artsariivs landing spot followed by attuning to <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/>. Follow this with <Skill id="5737"/> and your normal air opener. You can use <Skill id="5567"/> here for more burst and better range options (<Instability name="Social Akwardness"/>). You want to time <Skill id="5548"/> here so that you finish your <Skill id="5737"/> cast, the instant after you land having jumped over Artsariivs shockwave.

After all the nerfs the nuke window is pretty tight and you will only succeed if your whole party does everything correct. If either the boons the cc or damage is late slightly, the doom will explode.

Advanced groups can let the second anomaly explode and gg the third to save time. But if you failed the first nuke always make sure to kill the second anomaly. Also sometimes there are communication issues, so if you have the third doom always look, if someone killed the anomaly, before killing yourself.

**Normal**

If your group damage is low you can use <Skill id="5501"/> two times per phase, precast the first one in the middle in <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/>. **Always** place at least a <Skill id="5548"/> on the *Temporaly Anomaly* before using `Nova Launch` to the boss. You can already attune to <Skill id="5494"/> at the Anomaly and burst it with <Skill id="41125"/> before resuming on the boss with <Skill id="5737"/>.

**CC Consumables are strongly adviced for this fight.**

In the first phase three <Item id="8749"/>s or one <Item id="8749"/> and a <Item id="8664"/> will break an add. In the second Phase one <Item id="8664"/> or two <Item id="8749"/>s will break an add. The reason you want the consumables for fast cc is this: If your cc phase is fast enough, your boons will still be up when the boss becomes vulnerable again, leading to much higher damage, shorter fights and less chance to wipe to bad instabilites.

So use `Nova Launch` to either your assigned add or the add no is at and break it fast. Switch to <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> and pre cast in the middle <Skill id="5528"/>, <Skill id="5501"/>, <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/>, <Skill id="5548"/>, <Skill id="43762"/> and so on.

Also keep in mind if you do not go for the nuke in phase one that this is the first boss where you can use the `Nova Launch` to get all <Skill id="5697"/> in the bosses hitbox.

</Tab>

<Tab name="druid">
se <Skill id="31496"/> against the multitude of projectiles, especially against the the orb attacks from the two Elites at the beginning and from Artsariiv before her *Slam* attack.
</Tab>

</Tabs>


---

## <Boss red/> Arkk <Item id="50082" text="false"/><Label>9,942,250 HP</Label>

<Grid>
<Column>
Arkk is the third and final boss of the fractal. An attentive player may have noticed the `Nova Launch` special action key became even stronger now, doing medium damage, a 200 <Control name="launch"/> and executing a Blast finisher. Thanks to this, other crowd control skills are negligible for this fight.

In contrast to the other enemies in this fractal, Arkk belongs to Scarlet's army and <Item id="50082"/> works against him (_confirmed as of 2018/02/06 patch_).

Arkk himself has no melee attacks, but a lot of abilities which can make the fight rather chaotic for inexperienced groups. However, all damage can be avoided and therefore a healer is not mandatory. More party DPS means less boss mechanics.

Stack <Boon name="might"/> (you can use `Nova Launch`) and renew your _Mistlock Singularity_ before activating the orb to teleport to Arkk.

</Column>
<Column width="6" compact>
<Image src="./images/arkk.jpg" title="Arkk: The final boss" compact/>
</Column>
</Grid>

<Mechanics>
<Grid>
<Column>
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
</Column>

<Column width="4" compact>
<Image src="./images/so-arkk-eye.jpg" title="The Blinding Radiance ability"/>
<Image src="./images/so-arkk-solar.jpg" title="Arkk preparing Solar Fury"/>
<Image src="./images/so-arkk-green.jpg" title="Temporal Realignment"/>
</Column>
</Grid>
</Mechanics>

### Tactic

Immediately when the fight starts, turn away as Arkk uses his _Blinding Radiance_ ability. Always prioritize the respawning _Temporal Anomalies_, you only have a short time window to kill them before the player designated for _Corporal Reassignment_ explodes. The doomed person can see a white circle collapsing below the Temporal Anomaly, the moment it completes the explosion goes off.

A lot of the mechanics can occur at the same time, practice to avoid every single one.

Before triggering the Solar Bloom phases, you might want to wait for another Temporal Anomaly/Corporal Reassignment combination to prevent chaos during the intermediate phase.

#### Solar Blooms <Label>80%, 50%, 30%</Label>

When Arkk reaches 80% health, he gains <Effect name="invulnerability"/> and players have to kite four _Solar Blooms_ into the pillars in the corners to destroy them.

A common strategy is to assign four players to the spawning locations in the North, East, South and West, as the Solar Blooms fixate on the closest player a few seconds after their spawn. Players take aggro of their designated Solar Bloom and kite them clockwise to the next pillar on the right. You can also use direct damage skills to push back the Blooms.

<Image src="./images/so-solar-bloom.jpg" title="Solar Blooms fixate on the closest player"/>

The fifth, remaining player should be a DPS ready to take out a possibly spawning _Temporal Anomaly_ during the phase. This player must also be ready to join the player with the green circle.

After every Solar Bloom phase, Arkk's defiance bar has to be broken immediately or he kills all players. Use your `Nova Launch` ability for an additional <Control name="launch"/> if you are short of crowd control skills.

#### Elite Bosses <Label>70%, 40%</Label>

At 70% and 40% of Arkk's health, the party gets teleported to another dimension where you have to fight the _Elite Archdiviner_ from the [Cliffside Fractal](https://discretize.eu/fractals/cliffside) and the _Elite Brazen Gladiator_ from the [Chaos Isles Fractal](https://discretize.eu/fractals/chaos-isles) respectively.

Both bosses behave similar to their real version and are surrounded by four mobs (Cultists/Golems). Try to kill the adds before finishing the boss as they follow you back to Arkk. Remember the party-wide <Control name="daze"/> if the third auto-attack of the Gladiator hits someone. The _Elite Brazen Gladiator_ also does his huge pull attack below 50% health, prepare your `Nova Launch` skill to break his breakbar then.

#### Final phase <Label><40%</Label>

Below 40% health, random platforms start disappearing temporarily. Due to this mechanic, space is very limited and resurrecting a downed player is nearly impossible.
Sometimes _Temporal Anomalies_ spawn on vanished platforms which makes the fight even more challenging.

The most important thing is to keep calm. Remember that every single ability can be avoided, `Nova Launch` the _Solar Fury_ orbs, jump or dodge through the _Starburst Cascade_ and _Solar Stomp_ attacks, turn away from the _Blinding Radiance_ and move accordingly to the _Horizon Strike_ pattern. Keep a cool head and finish the fight!

<Tabs>
<Tab name="Mesmer">
Trait <Trait id="751"/> and place <Skill id="10186"/> inside Arkk to reflect the orbs from *Solar Fury*. Remember to use `Nova Launch` immediately before sharing boons to spread <Boon name="aegis"/> and help against mechanics like *Solar Fury*.<br/>Use <Skill id="10363"/> to pull mobs together at 70% and 40% (other party members can use `Nova Launch` to <Control name="launch"/> mobs closer to the center).
</Tab>

<Tab name="spellbreaker">
<Skill id="45160"/> and <Skill id="45333"/> can be used to reflect the orbs from *Solar Fury* if timed correctly.
</Tab>

<Tab name="weaver">
Start in <Skill id="5492" text="false"/>/<Skill id="5495" text="false"/> with <Skill id="5531"/> followed <Skill id="5548"/> and <Skill id="43762"/>. Attune to <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> and cast <Skill id="5737"/> while turned away to avoid the *Blinding Radiance* <Condition name="fear"/>. Continue with <Skill id="5501"/>.  

Always place a <Skill id="5548"/> on the Temporal Anomaly and use <Skill id="5539"/> as backup. If you aim your <Skill id="41125"/> correctly, it hits the boss and the anomaly. The same is true for <Skill id="5528"/> in half the spawn positions.

If your damage is good enough, you can skip the second and fourth anomaly by nuking the boss to 70% and 40%. With good damage and fast Orb phases you can also skip the fifth anomaly by nuking the boss from 30% to zero. Never cast <Skill id="5737"/> or <Skill id="5501"/> during the intermediate phases, instead wait and reopen with them on Arkk.

The ideal way to finish your orb fast, is by standing at 45 degrees to it and hitting it with two auto attacks.

Precast <Skill id="5548"/> and <Skill id="43762"/> at the end of the orb phases on Arkk, followed by <Skill id="5501"/>. 

If you have a <Condition name="vulnerability"/> source you will be able to also pre cast <Skill id="5736"/> each phase before the <Skill id="5501"/>.

If you have no <Condition name="vulnerability"/> the cast order is <Skill id="5737"/>,  from 100-80%, <Skill id="5737"/> from 70-50%, <Skill id="5736"/> 40-30% and <Skill id="5737"/> 30-0% (With lower damage this might vary.).

Note that you can abuse <Skill id="5697"/> and get all hits into Arkk by using `Nova Launch` on yourself immediately after starting the whirl.

Keep in mind that your `Nova Launch` does damage now, so make sure you always hit the boss and or adds if you are forced to use it.
</Tab>

<Tab name="druid">
You can consider running a more defensive setup with <Skill id="12495"/> for <Boon name="protection"/>, but not even that can help if you ignore mechanics.
</Tab>

</Tabs>


