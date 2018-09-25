---
title: 'Shattered Observatory'
date: '2018-09-12'
image: './images/header.jpg'
group: 'Challenge Mode'
api: 3458
bosses: 3
difficulties: [{ level: 100, ar: 150 }]
record:
  {
    time: '9:56',
    by: { name: 'Snow Crows', tag: 'SC' },
    youtube:
      [
        {
          id: 'cLTNHl_A28I',
          name: 'Van Gherwen',
          specialization: 'Chronomancer',
        },
        { id: 'phbHkROKlm8', name: 'Muto', specialization: 'Berserker' },
        { id: 'ME2QF0X_NJo', name: 'hint', specialization: 'Tempest' },
        { id: 'RLkDIlMEx8U', name: 'Roul', specialization: 'Dragonhunter' },
      ],
  }
cycle: 'Day'
potions: [{ id: 50082, description: 'against Arkk' }]
sigils: [{ id: 24615 }, { id: 24868 }]
consumables: [78978, 8759, 8678, 8732]
---

## Skorvald the Shattered <Label>5,551,340 HP</Label>

<Grid>
<GridItem sm="7">
Skorvald the Shattered is the first boss in the Shattered Observatory fractal. Be sure to take the *Mistlock Singularity* after accepting the Harbringer's challenge, stack <Boon name="might"/> on the platform below and start the encounter by activating the orb in the center of the platform.
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
The key to the fight is fast crowd control, as breaking Skorvald's Defiance bar prevents most of the mechanics. Immediately break it at the start and bring him down to 66% health.

At 66% and 33%, Skorvald becomes immune to damage and the party has to kill four _Elite Flux Anomalies_ to proceed. They spawn on the islands in the Southwest, Southeast, Northeast and Northwest and have to be killed subsequently in that order - the party can use air turbulences to travel between the islands. The Anomalies dont have much health (170.244 HP) but knock players back with shockwaves. Pay attention to the animations and position yourself between Anomaly and wall.

It is worth placing a <Item id="78978"/> portal on the main platform and opening it immediately when you reach the 4th _Elite Flux Anomaly_ to deal more damage to Skorvald before he continues his attacks, especially at 33%. **_Do not take the portal back to the boss before the add has landed its first jump. Otherwise it will leap out of all the damage zones and not die in time for your nuke._**

Below 33% health, Skorvald goes berserk and starts his rotating _Solar Cyclone_ attack. Keep your <Boon name="stability"/> skills for this part. Practice the safe spots and keep the _Solar Blooms_ away from the party, a <Specialization name="Druid"/> is the perfect candidate for this job with staff auto-attack but be ready to dodge if it explodes in party range.

After about 30 seconds, Skorvald starts a huge laser beam attack (_Beaming Smile_) and regains his Defiance bar, if he is not dead yet break the bar and finish him.
</GridItem>
</Grid>

<Tabs>
<Tab specialization="chronomancer">
**DISCLAIMER** <br/>
<Specialization name="chronomancer"/> is not easy for a beginner, so it'll take some time for you to learn this properly.     
*I believe in you.*

For these PUG strategies I will always assume that this is the composition you'll be running: <Specialization name="chronomancer"/>, <Specialization name="Warrior"/>, <Specialization name="weaver"/>, <Specialization name="weaver"/>, <Specialization name="Holosmith"/>/<Specialization name="Dragonhunter"/>/<Specialization name="Soulbeast"/>

Since triple <Specialization name="weaver"/> is extremely hard to pull off in a group that is not organized due to the lack of crowd control, a <Specialization name="Dragonhunter"/>/<Specialization name="Holosmith"/>/Power<Specialization name="Soulbeast"/> helps shorten the crowd control gap and brings <Condition name="vulnerability"/> to the fights.

<Specialization name="Druid"/> is bad, it does not do enough crowd control, it does almost no damage and post nerf spirits are subpar aka not worth using over another DPS profession.

The common misconception is that if you run with a <Specialization name="Druid"/> no one in the group will ever die thanks to the heals, while this might be true in some cases, we've found that if the boss dies faster, it's far less likely that your group will wipe.  
Keep in mind that this has nothing to do with elitism or try-hard, most bosses become very hard to kill if you waste time, look at Arkk for example, at 30% after the triple beam attack, if Arkk isn't dead by then he'll start spawning 3/4 mechanics at the same time that are hard to deal with if you're not experienced.

In this guide I am also going to assume that you're running the proper gear/food and that your <Specialization name="Chronomancer"/> basics are solid, with an emphasis on not wasting your concentration proc when swapping weapons.

**PUG Version**

Build: Chaos <br/>
Weapons: Sword – Shield / Pistol <br/>
Skills: <Skill id="21750"/>, <Skill id="10377"/>

Since PUGs are notoriously bad at using crowd control, you'll be opening this fight with this sequence:

<Skill id="30643"/> (MID <Skill id="29830"/>)> <Skill id="10287"/> -> <Skill id="10377"/> -> <Skill id="29830"/> END -> <Skill id="30643"/>+<Skill id="10287"/>-> SWAP -><Skill id="10229"/> <br/>
and then Signet + wells without casting a phantasm, since you'll be using that
on the first island along with a distort (<Skill id="10192"/>) to share <Boon name="Aegis"/> and prevent getting hit
by the stomp attack from the first _Elite Flux Anomaly_.

**66%**

Islands are pretty straightforward. You ALWAYS want to cast wells before other skills, so that people won't miss them.

1. [passive <Skill name="Signet of Inspiration"/> + <Skill id="10192"/>] <br/>
2. [<Skill id="30814"/> > Swap > <Skill name="Signet of Inspiration"/> + <Skill id="30643"/>] <br/>
3. [<Skill id="29856"/> > Swap > passive <Skill name="Signet of Inspiration"/>] <br/>
4. [Swap > <Skill name="Signet of Inspiration"/> > <Skill id="30643"/> (before everyone takes the portal)] <br/>

When you're back on the platform it'll be simple for you, use your <Skill id="10377"/>, wait for Skorvald to do his 3 attacks and then you can <Skill id="29830"/> your wells and <Skill name="Signet of Inspiration"/>, while not forgetting to swap weapons to proc your concentration sigil (im assuming your group dps is slow enough to have your <Skill id="29830"/> up in this phase) .

When the Defiance bar is back up use your <Skill id="30643"/> and <Skill id="10287"/> with possibly more than one clone to crowd control as much as you can because your group will be too busy tunneling on their arc dps to see who is gonna win the ego war, hence forgetting to crowd control.

Here we go again

**33%**

Follow the same steps above and remember to shatter and use a phantasm to activate passive <Skill name="Signet of Inspiration"/> when you get back to Skorvald before he does his knockback attack at the end so you can share some <Boon name="stability"/>.

**Try-hard**

**Disclaimer** <br/>
This guide is aimed for 5 players that are already very solid individually but want to take it to the next step in fractal encounters.<br/>
These are also strategies aimed for smooth and fast daily runs, not speedrunning records.<br/>
Do not attempt these strategies while in a PUG (for your own mental safety).

Compositions:  
<Specialization name="chronomancer"/>, <Specialization name="Warrior"/>, <Specialization name="weaver"/>, <Specialization name="weaver"/>, <Specialization name="weaver"/>  
<Specialization name="chronomancer"/>, <Specialization name="Warrior"/>, <Specialization name="weaver"/>, <Specialization name="weaver"/>, <Specialization name="soulbeast"/> (More CC, more <Condition name="vulnerability"/>, <Skill id="12497"/>)

Chaos/Inspiration

This fight is almost exactly 1:1 with the PUG strategy .

The only difference being that in an organized group,
the damage should be so high that you will not get your <Skill id="29830"/> back up at 66%, hence you should do double
Quick Well and <Skill name="Signet of Inspiration"/> on the 2nd Island after 33%.
</Tab>

<Tab specialization="warrior">
Help pre-stacking by using <Skill name="Charge" profession="Warrior"/> and <Skill name="Call to Arms" profession="Warrior"/> at Mistlock Singularity. While running towards Skorvald already place both banners.

---

### <Instability name="No Pain, No Gain" size="large"/> <Specialization name="Spellbreaker" size="large"/> **(Standard Dagger/Axe Greatsword)**

Immediately use <Skill name="Winds of Disenchantment" profession="Warrior"/> on Skorvald (prevents the first application of boons from <Instability name="No Pain, No Gain"/>) and assist breaking Skorvald's Defiance bar with <Skill id="14402"/>, <Skill name="Disrupting Stab" profession="Warrior"/> (if Defiance bar wont be broken with <Skill id="14502"/>, use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/>.

Continue with standard rotation:

- <Skill name="Breaching Strike" profession="Warrior"/>
- <Skill name="Dual Strike" profession="Warrior"/>
- <Skill name="Whirling Axe" profession="Warrior"/>
- <Skill id="14547"/>
- <Skill name="Hundred Blades" profession="Warrior"/>
- <Skill name="Whirlwind Attack" profession="Warrior"/>
- <Skill name="Bladetrail" profession="Warrior"/>
- <Skill name="Rush" profession="Warrior"/>
- <Skill id="14502"/>
- <Skill id="14547"/>
- <Skill name="Hundred Blades" profession="Warrior"/>
- <Skill name="Whirlwind Attack" profession="Warrior"/> (cancel in Skorvald's hitbox by using weapon swap)
- <Skill name="Breaching Strike" profession="Warrior"/>
- <Skill name="Disrupting Stab" profession="Warrior"/>
- <Skill id="14502"/>
- <Skill name="Dual Strike" profession="Warrior"/>.

Elite Flux Anomalies (66% and 33%) are not affected by <Instability name="No Pain, No Gain"/>. Take the portal at the last Elite Flux Anomaly and pre cast <Skill name="Winds of Disenchantment" profession="Warrior"/> on Skorvald. If <Skill name="Winds of Disenchantment" profession="Warrior"/> is still on cooldown (66%), use <Skill name="Disrupting Stab" profession="Warrior"/> and <Skill name="Breaching Strike" profession="Warrior"/> as soon as Skorvald is vulnerable. Make sure one of your DPS stays behind to kill the fourth Elite Flux Anomaly.

Refresh your banners before the 33% phase and as always try to adapt your rotation to what is currently needed.

<Message> 
Attacks reliably triggering <Skill name="full counter" profession="Warrior" size="large"/>: _Horizon Strike_, _Rush_, _Punishing Kick & Cranial Cascade_, _Solar Cyclone_ and _Combustion Rush_.
</Message>

---

### **without** <Instability name="No Pain, No Gain" size="large"/> <Specialization name="Warrior" size="large"/> **(Standard Axe/Axe Mace/Mace)**

Start on Mace/Mace (<Skill id="14402"/>, <Skill name="Tremor" profession="Warrior"/>, <Skill name="Pommel Bash" profession="Warrior"/>, <Skill name="Skull Crack" profession="Warrior"/>, <Skill id="14502"/>) and continue with standard rotation.

Keep an eye on Skorvald's <Condition name="vulnerability"/> stacks and use <Skill name="crushing blow" profession="Warrior"/> if it runs low.

Keep in mind that you have to kill the 4th Elite Flux Anomalies (66% and 33%) before using the portal to Skorvald's platform.
</Tab>

<Tab specialization="weaver">
  
**PUG Version**
  
Use <Skill id="21656"/> and make sure to blast on the first and fourth island during 66% and 33% phase if you have less than two weavers, run air to try-hard or have trouble maintaining 25 stacks of <Boon name="Might"/>.

Use the standard Air Opener with a pre-cast <Skill id="5516"/> from taking the Mistlock Singularity for high damage groups or the Earth/Fire Opener with low damage groups. If your group damage is mediocre you should finish the first phase in <Skill id="5492" disableText/>/<Skill id="5492" disableText/> with a <Skill id="5624"/> in your hands. Drop the hammer, use <Skill id="5680"/> to get faster to the air tubulence. Attune <Skill id="5495" disableText/>/<Skill id="5492" disableText/> and start casting <Skill id="5528"/> before jumping in the air turbulence, you will finish casting it mid air. Attune <Skill id="5492" disableText/>/<Skill id="5495" disableText/> and use <Skill id="5548"/>. Stay in <Skill id="5492" disableText/>/<Skill id="5495" disableText/> and finish the _Elite Flux Anomaly_ with <Skill id="5491"/> if it is not dead already.

NEVER cast <Skill id="5548"/> on the first _Elite Flux Anomaly_ before at least one player is on the island, since it will cast the fire aoe that might kill players before they can move after using the air turbulence.

Cast <Skill id="5548"/> and <Skill id="43762"/> already on the second _Elite Flux Anomaly_ while it is evading, attune to <Skill id="5494" disableText/>/<Skill id="5492" disableText/> and begin to cast <Skill id="5552"/> so that it instantly hits, when the evade ends. You will have to jump over the shockwave. Hit the _Elite Flux Anomaly_ with <Skill id="41125"/>. If it is not dead yet attune <Skill id="5492" disableText/>/<Skill id="5494" disableText/> and cast a new <Skill id="5548"/>. Attune to <Skill id="5495" disableText/>/<Skill id="5492" disableText/> before taking the next air turbulence. If you are the first on the island or still have <Boon name="Aegis"/> you can also cast <Skill name="Meteor Shower"/>. This is only worth it, if you can channel the skill without being interupted for at least half of its duration.

Start with <Skill id="5528"/> on the third _Elite Flux Anomaly_ followed by <Skill id="5492" disableText/>/<Skill id="5495" disableText/> and <Skill id="5548"/>. If the <Specialization name="Chronomancer"/> places his wells on this island dodge twice to avoid getting knocked out of the wells. Attune to <Skill id="5492" disableText/>/<Skill id="5492" disableText/> before leaving the island.

If all <Boon name="Might"/> blasts were correct and your group is fast enough you should have 25 stacks of <Boon name="Might"/> now, all other boons and <Trait name="Elements of Rage"/> for 8 secs.

Place a <Skill id="5548"/> on the last _Elite Flux Anomaly_ and take the portal back to Skorvald (not before the initial jump attack has ended or it will leap out of the <Skill id="5548"/>s) while summening your <Skill id="5516"/> (you can also hit the Anomaly with <Skill id="5517"/> before porting if it still has to much health). Usually the <Specialization name="Warrior"/> or one of the DPS will kill the last Anomaly with the help of your <Skill id="5548"/>. Keep the last Anomaly in your target to time your burst according to how fast it dies. Start your cast in this order: <Skill id="5531"/> -> <Skill id="5501"/> -> <Skill id="5737"/>. Ideally, <Skill id="5737"/> is finished casting the second Skorvald becomes vulnerable again. Continue with <Skill id="5548"/>, <Skill id="41125"/>, <Skill id="5624"/>, <Skill id="5725"/>, <Skill id="5492" disableText/>/<Skill id="5492" disableText/>, <Skill id="5539"/> x3, 1x <Skill id="5726"/> chain. You can place another <Skill id="5548"/> and cast maybe two additional <Skill id="5491"/> before Skorvald starts charging over the platform.

If everything goes smoothly, Skorvald will be at 33%. Repeat the aforementioned starting from <Skill id="5680"/>. Otherwise start by pre-casting <Skill id="5528"/> in the middle after Skorvald's second charge and continue your rotation accordingly.
<Message>
One of the most important things in this fight is to keep up <Boon name="Might"/> and boons at the four _Elite Flux Anomalies_. To achieve this you need to be fast enough with your damage, hit your blasts correctly and not get hit by the shockwaves and knockbacks.
</Message>

**Try-hard**

For the try-hard version you want to play with three air <Specialization name="Weaver"/>. The advantage of this composition is that your <Specialization name="Chronomancer"/> can use Inspiration Domination, which increases <Boon name="Alacrity"/> uptime and allows you to burst again 3-5 seconds earlier. The disadvantage is that you constantly have to keep an eye on your groups <Boon name="Might"/> uptime. But for normal daily runs you will probably have your burst skills ready anyways since you most likely lose those 3-5 seconds during the 66% or 33% split or due to the nerfed <Specialization name="Weaver"/> damage. Under ideal circumstances the time difference is between 8-10 seconds.
</Tab>

<Tab specialization="druid">
Combine <Trait id="1038"/> with <Skill id="12569"/> for party <Boon name="stability"/> below 33% health.
</Tab>
</Tabs>

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

<Grid>
<GridItem sm="8">
The second boss of the fractal is Artsariiv. The encounter gets activated by bouncing a *Globolla Marble* into her, be sure to prepare <Boon name="might"/> and skills in the northwest beforehand.

Artsariiv summons copies which split into smaller clones upon death, they use martial arts skills, <Control name="knockdown"/>, shoot shocking projectiles and apply a lot of damaging conditions. Discuss whether you kill all adds (safe tactic) or not.

Assign a player for the _Globolla Marble_ bouncing (typically the <Specialization name="warrior"/>) and a backup in case the main bouncer gets _Corporal Reassignment_.

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
| **Globolla Marble** | **Only below 66% health.** Artsariiv throws a huge, white *Globolla Marble* which needs to be bounced back to her. The next position of the marble is always indicated by a large white circle, the next but one position by a smaller white circle.<br/>Use `Nova Launch` to travel between the locations as it refreshes after each bounce. Usually the <Specialization name="warrior"/> soloes this mechanic, but other players should keep an eye on it and serve as a backup in case the main bouncer gets *Corporal Reassignment*.
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

Below 66% health, Artsariiv throws a large _Globolla Marble_ from time to time which needs to be bounced back to her over nine locations. Failing to bounce usually results in a party wipe, choose a reliable player beforehand to solo this (usually the least important profession - <Specialization name="warrior"/>).

After the fight is over, take the portal in the North and move forward to get to Arkk.

<Tabs>
<Tab specialization="chronomancer">
From this fight on, you can use `Nova Launch` immediately before sharing boons to spread <Boon name="aegis"/> and prevent dangerous boss mechanics. Note that you can pre-stack clones on Artsariiv with <Skill id="10173"/>.

**PUG Version**  
Build: Chaos/Inspiration <Trait id="751"/>  
Weapons: Sword - Shield / Focus  
Skills: <Skill id="30305"/>,<Skill id="10377"/>

**In this guide I am assuming that your group dps is low enough to get your <Skill id="29830"/> back at 66% and 33%**

When the fight begins you will be facing the middle of the platform waiting for Artsariiv to cast _Beaming Smile_ so that you can move in and kill the 2 adds that spawned.

Use <Skill id="10191"/> and <Skill id="10190"/> to get some boons on yourself and proc the passive <Skill name="Signet of Inspiration"/> by using your <Skill id="10282"/> phantasm (targeting the boss // make sure it's not invulnerable anymore) near your group to share boons at the beginning.

Then, while the Artsariiv is bouncing to her corner, swap to shield and do a sword 3 to get a clone up , then quickly cast as follows:

<Skill id="30643"/> (MID <Skill id="29830"/>) -> <Skill id="10377"/>-> <Skill name="Signet of Inspiration"/> -> <Skill id="29856"/>-><Skill id="29830"/> END-> <Skill id="30643"/> -><Skill id="29856"/> + <Skill id="30814"/> + <Skill name="Signet of Inspiration"/>

This is because you want to crowd control Artsariiv as much and as fast as possible with the double <Skill id="30643"/>.  
To increase the group's chance of survival you should also place a <Skill id="10186"/> between Artsariiv and the group, so that the orb autoattacks will be reflected.

**66%**

**DO NOT SKIP THIS STEP**  
After the crowd control phase is over , even before Artsariiv is vulnerable (when shes in the middle of the platform), you have to <Skill id="10191"/> <Skill id="10190"/> and share with <Skill name="Signet of Inspiration"/>. We do this because <Specialization name="Weaver"/>s will start casting <Skill id="5501"/> here and if they dont have any <Boon name="quickness"/> while doing so, they'll right click your name and report you for botting.  
**DO NOT SKIP THIS STEP**

Then go to the next corner and do all your <Skill id="29830"/> rotation on the boss, including <Skill id="10282"/> in <Skill id="29830"/> (without forgetting to <Skill id="10186"/> between the group and the boss to reflect) as your <Specialization name="Warrior"/> will be jumping for the marbles.
(Dont forget to heal your group with <Skill id="30305"/>, dont use it in a selfish way or they will go down) .

Repeat the same for 33%
-In the last phase you can use your <Skill id="10377"/> out of <Skill id="29830"/> , if <Skill id="29830"/> is not back up yet.

**Try-hard**  
In the beginning of the encounter we use the "nuke" strategy that you can see in our speedrun videos. The point is that you completely skip the first _Temporal Anomaly_ by phasing Artsariiv (66%) before the explosion. Even if you don't make it because something prevented you to deal proper damage, I believe tanking the first _Corporal Reassignment_ is still worth it, you'll just have to kill the _Temporal Anomaly_ in the next phases.

**100%**  
1: Stack 3 clones on Artsariiv before activating it (Using <Skill id="10173"/> or <Skill id="10310"/>).  
2: Activate Artsariiv.  
3: The entire group uses special action to the corner.  
4: <Skill id="29830"/> everything while keeping <Skill id="30643"/>+<Skill id="10287"/> as the last skill you will cast in <Skill id="29830"/> so you can do a 2nd one to crowd control Artsariiv at start.

If the Defiance bar is broken slowly you will fail. ( Your <Specialization name="Warrior"/> / <Specialization name="Soulbeast"/> will help you out here)

**66%(middle)**

Do NOT forget to <Skill name="Signet of Inspiration"/> before Artsariiv is even vulnerable, your <Specialization name="Weaver"/>s need <Boon name="quickness"/> to cast <Skill name="Meteor Shower"/>. You can also heal the group with your wells here as everyone will be stacked together.

**66%(corner)**  
Special action to the corner the boss is moving to.  
You can use your <Skill id="10377"/> here outside of <Skill id="29830"/>, along with your <Skill name="Signet of Inspiration"/> and eveything else that isn't on cooldown.  
Protect your team by placing a <Skill id="10186"/>(Traited) between them and Artsariiv to reflect the ball autoattacks.

**33%(middle)**  
Since you will have your <Skill id="29830"/> up here, while staying close to the group you should <Skill name="Signet of Inspiration"/> + <Skill id="10282"/>(passive <Skill name="Signet of Inspiration"/>) inside <Skill id="29830"/> while staying in range of your team. Keep everything else for the next part.

**33%(corner)**  
Simply spam all of your cooldowns, <Skill id="30305"/>, reflect and kill Artsariiv as the <Specialization name="Warrior"/> will be bouncing the orbs.
</Tab>

<Tab specialization="warrior">
Place banners at the corner of the platfrom where Artsariiv is going to be and help pre-stacking with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call to Arms" profession="Warrior"/> at Artsariiv.

---

### <Instability name="No Pain, No Gain" size="large"/> <Specialization name="Spellbreaker" size="large"/> **(Standard Dagger/Axe Greatsword)**

Use <Skill id="14402"/> as soon as the fight starts and already remove Artsariiv's boons with <Skill name="Disrupting Stab" profession="Warrior"/> and <Skill name="Breaching Strike" profession="Warrior"/> while Artsariiv is channeling _Beaming Smile_.

#### Initial phase

- Ignoring _Corporal Reassignment_: use `Nova Launch` to the corner where the fight is about to take place and block _Solar Discharge_ with <Skill name="full counter" profession="Warrior"/>. <Skill name="Breaching Strike" profession="Warrior"/>, <Skill name="Disrupting Stab" profession="Warrior"/> (if Defiance bar won't be broken with <Skill id="14502"/>, use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/>, <Skill name="Dual Strike" profession="Warrior"/>, <Skill name="Whirling Axe" profession="Warrior"/>, <Skill name="Breaching Strike" profession="Warrior"/>, <Skill id="14502"/>, <Skill id="14547"/>, <Skill name="Hundred Blades" profession="Warrior"/>, <Skill name="Whirlwind Attack" profession="Warrior"/>, <Skill name="Bladetrail" profession="Warrior"/> and <Skill name="Rush" profession="Warrior"/>.
- With _Corporal Reassignment_: stay in the center and assist with the _Temporal Anomaly_. everything else stays the same as aforementioned.

66% and 33% use consumables (<Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/> / <Item id="8677"/> / <Item id="8749"/>) to break Defiance bar of the 5 / 9 clones.
Use <Skill name="Breaching Strike" profession="Warrior"/>, <Skill name="Disrupting Stab" profession="Warrior"/> <Skill id="14502"/> and <Skill name="Dual Strike" profession="Warrior"/> as soon as Artsariiv is attackable, dodge the large _AoE circle_ and immediately use <Skill name="Whirling Axe" profession="Warrior"/>.

#### 66%

- Ignoring _Corporal Reassignment_: use `Nova Launch` to the corner where Artsariiv is about to be and block _Solar Discharge_ with <Skill name="full counter" profession="Warrior"/> and continue usual rotation unless you have been assigned to do the marble bounce.
- With _Corporal Reassignment_: stay in the center and assist with the _Temporal Anomaly_. If you are assigned to do marble bounce and are doomed, call for a backup and stay in the shelter close to the center and wait for _Corporal Reassignment_ to run out. The backup always only has to cover the first circle, you reach the second circle just in time with `Nova Launch`. Otherwise use `Nova Launch` to get to Artsariiv, position yourself already at the first
  circle for the marble which always spawns close to Artsariiv, allowing you to still attack. Note that you only have a very small window between first and second bounce to strip her of boons unless you have <Skill name="Winds of Disenchantment" profession="Warrior"/> ready.

#### 33%

- Ignoring _Corporeal Reassignment_: place both your banners at Artsariiv. Continue your usual rotation unless you have been assigned to do the marble bounce or you are doomed (/gg as doomed).
- With _Corporeal Reassignment_: Same as 66%.

<Message> 
Attacks reliably triggering <Skill name="full counter" profession="Warrior" size="large"/>: *Astral Surge*, *Solar Discharge* and *Slam*.
</Message>

---

### **without** <Instability name="No Pain, No Gain" size="large"/> <Specialization name="Warrior" size="large"/> **(Standard Axe/Axe Mace/Mace)**

Use <Skill id="14402"/> as soon as the fight starts and already attack while Artsariiv is channeling _Beaming Smile_.

#### Initial phase

- Ignoring _Corporeal Reassignment_: Swap to Mace/Mace and use `Nova Launch` to get to the corner where the fight is about to take place and jump over _Solar Discharge_.
- With _Corporeal Reassignment_: stay in the center and assist with the _Temporal Anomaly_. Éverything else stays the same as aforementioned.

66% and 33% use consumables (<Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>) to break Defiance bar of the 5 and 9 clones respectively.
Use <Skill id="14502"/>, <Skill name="Eviscerate" profession="Warrior"/>, <Skill name="Cyclone Axe" profession="Warrior"/>, <Skill name="Throw Axe" profession="Warrior"/> and <Skill name="Dual Strike" profession="Warrior"/> as soon as Artsariiv is attackable, dodge the large AoE circle and immediately use <Skill name="Whirling Axe" profession="Warrior"/>.

#### 66%

- Ignoring _Corporeal Reassignment_: use `Nova Launch` to the corner where Artsariiv is about to be and avoid getting hit by _Solar Discharge_. Continue usual rotation unless you have been assigned to do the marble bounce.
- With _Corporeal Reassignment_: stay in the center and assist with the _Temporal Anomaly_. If you are assigned to do marble bounce and are doomed, call for a backup and stay in the shelter close to the center and wait for _Corporeal
  Reassignment_ to run out. The backup always only has to cover the first circle, you reach the second circle just in time with `Nova Launch`. Otherwise use `Nova Launch` to get to Artsariiv, position yourself already at the first circle for
  the marble which always spawns close to Artsariiv, allowing you to still attack her.

#### 33%

- Ignoring _Corporeal Reassignment_: use `Nova Launch` to the corner where Artsariiv is about to be and avoid _Solar Discharge_. Place both your banners at Artsariiv and continue your usual rotation unless you have been assigned to do the marble bounce or you are doomed (/gg as doomed).
- With _Corporeal Reassignment_: Same as 66%.
  </Tab>

<Tab specialization="weaver">

**PUG Version**

If your group damage is low you can use <Skill id="5501"/> two times per phase, pre-cast the first one in the middle in <Skill id="5495" disableText/>/<Skill id="5492" disableText/>. **Always** place at least a <Skill id="5548"/> on the _Temporaly Anomaly_ before using `Nova Launch` to Artsariiv. You can already attune to <Skill id="5494"/> at the _Temporaly Anomaly_ and burst it with <Skill id="41125"/> before continuing with <Skill id="5737"/> on Artsariiv.

**crowd control Consumables are strongly recommended for this encounter.**

In the first phase three <Item id="8749"/>s or one <Item id="8749"/> and a <Item id="8664"/> break a clones Defiance bar. In the second phase one <Item id="8664"/> or two <Item id="8749"/>s break a clones Defiance bar. The reason you want the consumables for fast crowd control is this: If your crowd control phase is fast enough, your boons will still be up when Artsariiv becomes vulnerable again, leading to much higher damage, shorter fights and less chance to wipe to bad instabilites.

So use `Nova Launch` to either your assigned clone or the clone no is at and break its Defiance bar fast. Switch to <Skill id="5495" disableText/>/<Skill id="5492" disableText/> and pre cast in the middle <Skill id="5528"/>, <Skill id="5501"/>, <Skill id="5492" disableText/>/<Skill id="5495" disableText/>, <Skill id="5548"/>, <Skill id="43762"/> and so on (If your <Specialization name="Chronomancer"/> is daydreaming and you have no <Boon name="Quickness"/> skip <Skill id="5501"/> unless you were very fast in the middle).

Also keep in mind if you do not go for the nuke in phase one that this is the first boss where you can use the `Nova Launch` to get all <Skill id="5697"/> in the bosses hitbox.

**Try-hard**

For the nuke strategy you want to damage Artsariiv to 66% before the the initial _Corporeal Reassignment_ triggers. To achieve this you stack <Boon name="Might"/> in the middle and have Artsariiv channel _Beaming Smile_ in the opposite direction of where she will go afterwards, to make sure you won't get hit by it.

Pre-cast <Skill id="5528"/> and <Skill id="5548"/> in the middle. (You can hit Artsariiv with one <Skill id="5491"/> before you have to `Nova Launch` to the first spot), to avoid being hit by _Beaming Smile_.

Now summon your <Skill id="5516"/> followed by <Skill id="5531"/>, then cast <Skill id="5548"/> and <Skill id="43762"/> on Artsariivs landing spot followed by attuning to <Skill id="5494" disableText/>/<Skill id="5492" disableText/>. Follow this with <Skill id="5737"/> and your normal air opener. (You can use <Skill id="5567"/> here for more burst and better range options (<Instability name="Social Awkwardness"/>)). You want to time <Skill id="5548"/> here so that you finish your <Skill id="5737"/> cast, right after jumping over _Solar Discharge_. Or if you trust your <Specialization name="chronomancer"/> you can skip the jump for more damage. The ideal opener should look like [this](https://www.youtube.com/watch?v=uzaqKzCfWJ8).

After all the nerfs the nuke window is pretty tight and you will only succeed if your whole party does everything correct. If either the boons, the crowd control or damage is slightly late, _Corporeal Reassignment_ will trigger.

Note: Advanced statics will not need 3 <Skill id="5516"/> for the nuke in phase 1 and can keep it for higher damage in phase 2. Especially if your whole group has `Fractal God` you can manage the nuke without a single <Skill id="5516"/> in phase 1.

If your damage is particular high use <Skill name="Firestorm"/> in phase 2, to have <Skill name="Lightning Storm"/> ready in phase 3.

Advanced groups can let the second _Corporeal Reassignment_ trigger and gg the third to save time. But if you failed the first nuke always make sure to kill the second _Temporal Anomaly_. Also sometimes there are communication issues, so if you have the third _Corporeal Reassignment_ always check if someone killed the _Temporal Anomaly_, before killing yourself.
</Tab>

<Tab specialization="druid">
Use <Skill id="31496"/> against the multitude of projectiles, especially against the the orb attacks from the two Elites at the beginning and from Artsariiv before her *Slam* attack.
</Tab>
</Tabs>

---

## Arkk <Item id="50082" disableText/><Label>9,942,250 HP</Label>

<Grid>
<GridItem sm="8">
Arkk is the third and final boss of the fractal. An attentive player may have noticed the `Nova Launch` special action key became even stronger now, doing medium damage, a 200 <Control name="launch"/> and executing a Blast finisher. Thanks to this, other crowd control skills are negligible for this fight.

In contrast to the other enemies in this fractal, Arkk belongs to Scarlet's army and <Item id="50082"/> works against him (_confirmed as of 2018/02/06 patch_).

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

<Tabs>
<Tab specialization="mesmer">
Build: Chaos     
Weapons: sword-shield/focus     
Skills: <Skill id="30305"/>, <Skill id="10377"/>

Think of Arkk as a golem that becomes invulnerable once in a while, if your <Specialization name="Chronomancer"/> basics are solid, your uptimes should not be a problem.

Regardless of that, there are a few things you should keep in mind:

**PUG Version**

1. You always want to start on shield before crowd control phases (after the orb mechanics)
   so you can use your <Skill id="30643"/> + <Skill id="10287"/> and swap instantly to share boons.
2. You should ALWAYS pull at least 2 of the 4 adds that spawn with the Elite Archdiviner (70%) and the Elite Brazen Gladiator (40%) since they deal a lot of damage to the group.
3. You should use your <Skill id="29830"/> at the start of the fight and at 50%, and at 30% you can pre-cast your <Skill id="10377"/> outside of <Skill id="29830"/> so your group will have <Boon name="quickness"/> instantly after coming back from the pillars.
4. This is helpful if you have time: use your <Skill id="10186"/> on Arkk's hitbox to reflect the orb attacks ( keep in mind you still need to pull adds so dont use it if you're about to phase after _Force of the Nightmare_)
5. Don't forget to INSTANTLY use <Skill id="10191"/>-<Skill id="10190"/> when the fight starts and <Skill id="10282"/> to proc passive <Skill name="Signet of Inspiration"/>, only then begin your rotation.(you don't want your <Specialization name="Weaver"/>s to wait a long time to get <Boon name="quickness"/> or they will start flaming you).

**Try-hard**  
Exactly the same as PUG Arkk.

This encounter is generally more intense for your <Specialization name="Weaver"/>s, as they have to manage cooldowns properly while dodging mechanics that one-shot them. Please be patient if they start cursing in voice chat. Always keep a positive mental attitude.
</Tab>

<Tab specialization="warrior">
Place banners already on Arkk's platform if your group does one /gg before. Help pre-stacking at Mistlock Singularity with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call to Arms" profession="Warrior"/>. Usually one of the DPS is responsible for slaying the Temmporal Anomaly, nonetheless pay 
close attention to it and assist if necessary. Dont forget to use `Nova Launch` to circumvent the effects of Arkk's _Solar Fury_ and _Solar Discharge_.

---

### <Instability name="No Pain, No Gain" size="large"/> <Specialization name="Spellbreaker" size="large"/> **(Standard Dagger/Axe Greatsword)**

Start pre-casting <Skill name="Winds of Disenchantment" profession="Warrior"/> while teleporting to Arrk's platform and follow standard rotation. At 80%, 50% and 30%, respectively, swap to Dagger/Axe as soon as Arkk turns invulernable and position yourself at one of the sides where a Solar Bloom is about to spawn. Since your attacks are solely melee, its recommended to already position yourself close to the designated pillar (its common to push Solar Blooms clockwise) and just wait for it to come to you so you can easily push it into the pillar with a single attack. Once Arkk starts channeling _Force of the Nightmare_, use `Nova Launch` on Arkk to add additional Defiance bar damage, remove boons immediately with <Skill name="Breaching Strike" profession="Warrior"/>, <Skill name="Disrupting Stab" profession="Warrior"/> and <Skill id="14502"/> and continue with the usual rotation. Conserve your <Skill name="Winds of Disenchantment" profession="Warrior"/> for when Arkk returns to the platform after 40% to remove Arkk's boons and counter the _Solar Fury_ (you dont want the last remaining platform close to Arkk (_Disappearing Platforms_} covered in burning oil). For the Elite Archdiviner (70%) and the Elite Brazen Gladiator (40%) stay on Dagger/Axe for immediate boon removal on them as well as on Arkk afterwards.

<Message> 
Attacks reliably triggering <Skill name="full counter" profession="Warrior" size="large"/>: *Focused Rage*, *Horizon Strike* and *Diffractive Edge*.
</Message>

---

### **without** <Instability name="No Pain, No Gain" size="large"/> <Specialization name="Warrior" size="large"/> **(Axe/Axe Greatsword)**

Start on Axe/Axe and just follow the standard rotation. At 80%, 50% and 30% position yourself at one of the sides where a Solar Bloom is about to spawn. Since your attacks are solely melee, its recommended to already position yourself
close to the designated pillar (its common to push Solar Blooms clockwise) and just wait for it to come to you so you can easily push it into the pillar with a single attack. Once Arkk starts channeling Force of the Nightmare, use Nova
Launch on Arkk to add additional Defiance bar damage and continue with the standard rotation.
</Tab>

<Tab specialization="weaver">
Start in <Skill id="5492" disableText/>/<Skill id="5495" disableText/> with <Skill id="5531"/> followed <Skill id="5548"/> and <Skill id="43762"/>. Attune to <Skill id="5494" disableText/>/<Skill id="5492" disableText/> and cast <Skill id="5737"/> while turned away to avoid the _Blinding Radiance_ <Condition name="fear"/>. Continue with <Skill id="5501"/>.

Always place a <Skill id="5548"/> on the _Temporal Anomaly_ and use <Skill id="5539"/> as backup. If you aim your <Skill id="41125"/> correctly, it hits both Arkk and the _Temporal Anomaly_. The same is true for <Skill id="5528"/> in half of the spawn positions.

If your damage is good enough, you can skip the second and fourth _Temporal Anomaly_ by nuking Arkk to 70% and 40%. With good damage and fast Solar Bloom phases you can also skip the fifth _Temporal Anomaly_ by nuking Arkk from 30% to 0. Never cast <Skill id="5737"/> or <Skill id="5501"/> during the intermediate phases, instead wait and reopen with them on Arkk.

The ideal way to finish Solar Blooms fast, is by standing at 45 degrees to it and hitting it with two auto attacks.

Pre-cast <Skill id="5548"/> and <Skill id="43762"/> at the end of the Solar Bloom phases on Arkk, followed by <Skill id="5501"/>.

If you have a secondary <Condition name="vulnerability"/> source you will be able to also pre-cast <Skill id="5736"/> each phase before the <Skill id="5501"/>.

If you don't have a secondary source for <Condition name="vulnerability"/> the cast order is <Skill id="5737"/>, from 100-80%, <Skill id="5737"/> from 70-50%, <Skill id="5736"/> 40-30% and <Skill id="5737"/> 30-0% (With lower damage this might vary.).

Note that you can abuse <Skill id="5697"/> and get all hits into Arkk by using `Nova Launch` on yourself immediately after starting the whirl.

Keep in mind that your `Nova Launch` does damage now, so make sure you always hit the boss and or adds if you are forced to use it.

Also since Arkk has extremly long break phases (10 sec), <Skill id="40183"/> is very strong in the 20% and 30% phases.
</Tab>

<Tab specialization="druid">
You can consider running a more defensive setup with <Skill id="12495"/> for <Boon name="protection"/>, but not even that can help if you ignore mechanics.
</Tab>
</Tabs>
