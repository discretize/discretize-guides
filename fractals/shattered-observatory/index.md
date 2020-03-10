---
title: 'Shattered Observatory'
date: '2020-02-21'
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

<Tabs>
<Tab specialization="Renegade">
**Legends**  
* <Skill name="Legendary Renegade Stance"/> and <Skill name="legendaryassassinstance"/>.

**Suggested Boon Duration** `80%`

Maintaining <Boon name="Alacrity"/> in this encounter does require higher boon duration due to the length of the fight, and the necessity for <Boon name="Alacrity"/> throughout the encounter. Increase your concentration if you notice downtime in <Boon name="Alacrity"/>.

---

**Precast**  
* Cast <Skill name="Ordersfromabove"/> for <Boon name="Alacrity"/> and <Skill name="Renewingwave"/> to blast, take the mistlock and repeat. The two casts of <Skill name="Ordersfromabove"/> overlap and grant twice the duration of <Boon name="Alacrity"/>. You can use <Skill name="DroptheHammer"/> for an additional blast.

**100-66%**  
* Precast <Skill name="Darkrazors Daring"/> when the <Specialization name="Weaver"/> is casting <Skill name="Meteorshower"/>.
* Cast <Skill name="Icerazors Ire"/> right before triggering the instance.
* Use <Skill name="Surge of the Mists"/> through Skorvald to break the defiance bar. Be aware of positioning to gain an extra hit.
* Weapon swap and change to <Skill name="legendaryassassinsstance"/>, this will grant you extra energy from the trait <Trait name="Charged Mists"/>.
* Activate <Skill name="Impossible Odds"/>, and use <Skill name="Citadel Bombardment"/> and <Skill name="Chilling Isolation"/>.
* Share <Boon name="Alacrity"/> with <Skill name="Orders from above"/> when the phase ends.

**1st Add**
* Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.
* Change to <Skill name="Legendary Renegade Stance"/>.
* Use <Skill name="Chilling Isolation"/>.

**2nd Add**  
* Cast <Skill name="Icerazors Ire"/> while the add is charging the knockback attack.
* Use <Skill name="Citadel Bombardment"/>, <Skill name="Chilling Isolation"/>, and <Skill name="Shackling Wave"/>.
* Change to <Skill name="legendaryassassinstance"/>.

**3rd Add**
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/>. 

**4th Add**  
* Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.
* Activate <Skill name="Impossible Odds"/>, and use <Skill name="Citadel Bombardment"/>, <Skill name="Chilling Isolation"/>, and <Skill name="Shackling Wave"/> on the add after the knockback attack.
* Deplete your energy as much as you can and change to <Skill name="Legendary Renegade Stance"/>.

**66-33%**
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Cast <Skill name="Soulcleaves Summit"/> and <Skill name="Icerazors Ire"/> immediately.
* Deplete your energy with <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/>.
* Change to <Skill name="legendaryassassinstance"/>.
* Activate <Skill name="Impossible Odds"/>, and use <Skill name="Citadel Bombardment"/>.
* Share <Boon name="alacrity"/> with <Skill name="Orders from Above"/> when the phase ends.

**Adds**
* Replicate the skill order mentioned above in the earlier add phase.

**33-0%**
* Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
* Cast <Skill name="Soulcleaves Summit"/> and <Skill name="Icerazors Ire"/> immediately.
* Deplete your energy with <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/>.
* Change to <Skill name="legendaryassassinstance"/>.
* Activate <Skill name="Impossible Odds"/>, and use <Skill name="Citadel Bombardment"/>.
* Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> until the encounter is finished.

---

**Annotation** 
* Cast <Skill name="Citadel Bombardment"/> right as you jump the shockwave of the 2nd and 4th add. This can save you some time with a good party.
* Be aware of positioning when sharing <Boon name="Alacrity"/> and <Boon name="Might"/> on the islands. Make sure everyone has landed before sharing.
* Cancel <Skill name="Surge of the Mists"/> once you are through the hitbox to gain time to do more damage in the first phase. 
</Tab>

<Tab specialization="Firebrand">
**tl;dr**
- Good teams = Scepter; Bad teams = sword. Play <Trait id="574"/>.
- Start every burn on sword/scepter

**Precast**

- Use <Skill name="Hallowed ground"/> to give a fire field and retal.
- Use <Skill name="Feelmywrath"/> and <Skill name="potenthaste"/> to give some quickness.
- Open <Skill name="tomeofjustice"/> and cast skill 5(Epilogue).
- Use <Skill name="banesignet"/> before taking the mistlock.
- Take the mistlock.
- You can precast <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss.
- You can also precast <Skill name="tomeofjustice"/> skill 4 and 5 just before starting the boss to max out burst.

**Burn phases**

CC using <Skill name="bane signet"/> and start burns on scepter/sword.

**Adds**

You can kill the first two adds with greatsword. Make sure, that you are on scepter/sword at the last add and you are not having cooldown on the weopen swap, or you DPS will suffer a lot. You can freely use GS on the first two adds. Swap to scepter/sword after that.

On last platform precast <Skill name="Feelmywrath"/> and <Skill name="banesignet"/> just before taking portal so that all players get are getting back to skorvald fully buffed and you can concentrate on your rotation.  
In cases where <Boon name="might"/> is lacking, you can use <Skill name="tomeofjustice"/> skill 4 to put down a fire field so that your team can blast it and get <Boon name="might"/> on platform 3 or 4. Make sure to not overstack the firefield with a symbol. Blast the firefield with <Skill name="shieldofwrath"/>.
</Tab>

<Tab specialization="Soulbeast">
**General**  
- In organized groups its worth it to take <Skill name="Frosttrap"/> over <Skill name="Signetofthewild"/>.
- In organized groups you can take warhorn and use <Trait name="Leaderofthepack"/>

**Precast**

Precast <Skill name="Frosttrap"/> on the boss like a <Specialization name="Dragonhunter"/> in disguise. Before blasting <Boon name="Might"/> cast your <Skill name="Frostspirit"/> and wait for it to loose some hp. Remember to share <Skill name="Moastance"/> and blast with <Skill name="Callofthewild"/>. Share <Skill name="One wolf pack"/> and take the mistlock.

Teleport your <Skill name="Frostspirit"/> down to the platform.

**Opening**

- <Skill id="5531"/> and <Skill name="Barrage"/>
- Swap to warhorn
- <Skill name="Onewolfpack"/>
- <Skill name="Frosttrap"/>, <Skill name="Sicem"/>
- <Skill name="hunterscall"/>
- <Skill name="Worldlyimpact"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/>

**Adds**  
Can use <Skill name="whirlingdefense"/> on the 2nd one. Swap to sword/warhorn and kill the adds with a mix of F1, F2 and AAs. Blast <Boon name="might"/> on the 3rd or 4th island.
Resummon <Skill name="Frostspirit"/> on the last island. Take FGS if available. Take the portal early to teleport <Skill name="Frostspirit"/> to you.

**66% and 33%**  
In these phases you wanna make sure all ticks of <Skill name="Whirlingdefense"/> hit while he's CCed: 
- <Skill id="5531"/>
- <Skill name="Onewolfpack"/>
- <Skill name="Frosttrap"/>, <Skill name="Sicem"/>
- <Skill name="hunterscall"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/>

Skip F3 in fast parties, because it has kind of a long cast time.

<Message>
<Skill name="Hunterscall"/> has a bit of an aftercast and you can cancel it earlier
</Message>
</Tab>

<Tab specialization="Berserker">
**Build variation**  
- Bad group with no cc: Mace/Mace
- If you are running with a lot of blue classes: Mace/Torch 
- If you are running in a meta comp: Mace/Warhorn or Mace/Mace depending on your CC coordination.

**Prestacking**
- Drop a fire field with <Skill name="Flames of war"/>.
- Use <Skill name="For great justice"/> as soon as you see <Skill name="Moa stance"/> on your bar.
- Blast with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call of Valor" profession="Warrior"/>.
- Blast 12 Stacks of might with <Skill name="Banner of Strength"/> and <Skill name="Banner of Discipline"/>.
- Take the mistlock.
- While approaching the boss drop both of your banners. 
- Precast <Skill name="Flames of war"/> for dps
- Precast <Skill name="Mending"/>

**100%-66%**
- <Skill name="Tremor"/> and <Skill name="Pommelbash"/>, <Skill name="Headbutt"/>
- Swap
- <Skill name="Berserk"/> and <Skill name="Decapitate"/>
- <Skill name="cycloneaxe"/>, <Skill name="Throw axe"/> and <Skill name="Decapitate"/>
- <Skill name="Dualstrike"/>, <Skill name="Throw axe"/> and <Skill name="Decapitate"/>
- If your party is not the fastest pick up your banners and redrop them on the main island. Put them slightly outside of the stack so you don't take a portal on accident.

**Islands**
- Swap to your warhorn or torch if you have it and use the blasts in firefields for <Boon name="might"/>.
- Don't use heavy cooldowns after island 3.
- On the last island shortly before the add dies use <Skill name="Mending"/> and open <Skill name="Berserk"/> already.

**66%-33%**
- Follow the standard fractal rotation.
- If your party does not phase skorvald without a dash, recast your banners. 
- Before you move to the first island pick your banners up and redrop them on the main island. Put them slightly outside of the stack so you don't take a portal on accident.

The rest of the fight follows accordingly.
</Tab>

<Tab specialization="weaver">
**Precast**
- Start on sword/Dagger and <Skill id="5506"/> and <Skill id="5635"/>
- Start on <Skill id="5495"/>/<Skill id="5492"/> and use <Skill id="5691"/> to provide a fire field and blast it with <Skill id="40709"/>. 
- Swap to <Skill id="5492"/>/<Skill id="5495"/> and the use <Skill id="5690"/>, <Skill id="21656"/> and <Skill id="5522"/> to blast your fire field..
- Use <Skill id="5506"/> and <Skill id="5635"/> and swap back to <Skill id="5734"/> and<Skill id="5539"/>
- Swap to staff and <Skill id="5494"/>/<Skill id="5492"/> and then use <Skill id="5516"/>.
- Take the mistlock.
- Go to the boss and use <Skill id="5531"/> on your <Skill id="5516"/> and then drop it. Use <Skill id="5501"/> on your staff . Then equip sword/dagger, swap to <Skill id="5494"/>/<Skill id="5494"/> and start the boss!



**100%**
- Use <Skill id="5737"/> right as the boss comes down.
- Use <Skill id="5687"/> to CC the boss and do your burst.

**Anomalies**
- Make sure to blast your fire fields and use <Skill id="5529"/> to travel faster between anomalies.
- Drop your <Skill id="5516"/> on the 4th platform before taking the portal back to the boss.
- Don't get knocked, jump/dodge the waves.
- Be on <Skill id="5494"/>/<Skill id="5494"/> while taking the portal back to the boss.

**66%**
- Start with <Skill id="5531"/> on your <Skill id="5516"/>, drop it.
- Use <Skill id="5737"/> and do your burst.

**Anomalies**
- Make sure to blast your fire fields and use <Skill id="5529"/> to travel faster between anomalies.

- Don't get knocked, jump/dodge the waves.
- Be on <Skill id="5494"/>/<Skill id="5494"/> while taking the portal back to the boss.
 

**33%**
- Use <Skill id="5687"/> to CC the boss and do your burst.
- Be on max melee range before the boss starts spinning, dont die like a scrub.

**Tryhard/Static run**
- Use <Skill id="44612"/> instead of <Skill id="40183"/> to get to <Skill id="5492"/>/<Skill id="5492"/> faster for the super quick burst phases(Also ez might).
- Make sure to drop the <Skill id="5516"/> on the 4th platform ASAP so that your <Specialization name="soulbeast"/> can pick it up before taking the portal
<Message>
One of the most important things in this fight is to keep up <Boon name="Might"/> and boons at the four _Elite Flux Anomalies_. To achieve this you need to be fast enough with your damage, hit your blasts correctly and not get hit by the shockwaves and knockbacks.
</Message>

<Video title="Video Guide by Tym" youtube="v=DaKI7Ccr_Ss"/>

</Tab>

<Tab specialization="Dragonhunter">
**tl;dr**
- Good teams = Scepter; Bad teams = sword. Play <Trait id="574"/>.
- Start every burn on sword/scepter

**Precast**

- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the boss and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- Use <Skill name="Feelmywrath"/>.
- Take the mistlock.
- You can precast <Skill id="29789"/> (LB4), <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss.

**Burn phases**

Your gameplay is heavily influenced by the dps your team can pull. If your team has very high dps (phases Skorvald >5s) you wanna precast <Skill name="Bane Signet"/> and fire everything you have as soon as you are getting in combat.

**Adds**

You can kill the first two adds with greatsword. You can use traps on the 2nd add, without having them on cooldown when you are back at Skorval. Make sure, that you are on scepter/sword at the last add and you are not having cooldown on the weopen swap, or you DPS will suffer a lot. You can freely use Traps and GS on the first two adds. Swap to scepter/sword after that.

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

<Tabs>
<Tab specialization="Renegade">
**Legends**  
* <Skill name="Legendary Renegade Stance"/> and <Skill name="Legendary Dwarf Stance"/>.

**Suggested Boon Duration** `80%`

Maintaining <Boon name="Alacrity"/> in this encounter does require higher boon duration due to the length of the fight, and the necessity for <Boon name="Alacrity"/> throughout the encounter. Increase your concentration if you notice downtime in <Boon name="Alacrity"/> during the phases.

---

**Precast**

- Cast <Skill name="Ordersfromabove"/> for <Boon name="Alacrity"/> and <Skill name="Renewingwave"/> to blast, take the mistlock and repeat. The two casts of <Skill name="Ordersfromabove"/> overlap and grant twice the duration of <Boon name="Alacrity"/>. You can use <Skill name="DroptheHammer"/> for an additional blast.

**100-66%**

- Precast <Skill name="Soulcleaves Summit"/> and <Skill name="Icerazors Ire"/> at Artsariiv's location after triggering the encounter.
- Manually change to <Skill name="Legendary Dwarf Stance"/> before Artsariiv becomes vulnerable.
- Use <Skill name="Shackling Wave"/>, and share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
- Share <Boon name="Might"/> with <Skill name="Heroic Command"/> before using the special action key to the corner.
- Weapon swap and use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> for the party.
- Change to <Skill name="Legendary Renegade Stance"/>, and precast <Skill name="Darkrazors Daring"/>, <Skill name="Icerazors Ire"/>, and <Skill name="Soulcleaves Summit"/> at the location where Artsarriv will appear.
- Use <Skill name="Surge of the Mists"/> to break the defiance bar. Use it with the special action key to gain additional hits.
- Weapon swap and change to <Skill name="Legendary Dwarf Stance"/>

**Add**

- Use <Skill name="Forced Engagement"/> and <Skill name="Shackling Wave"/> to break the adds defiance bar.

**66-33%**

- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/> when everyone is in the middle.
- Use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> for the large AoE attack.
- Change to <Skill name="Legendary Renegade Stance"/>, and use <Skill name="Soulcleaves Summit"/> and <Skill name="Citadel Bombardment"/>.
- Share <Boon name="might"/> with <Skill name="Heroic Command"/>.
- Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> to deplete your energy.
- Change to <Skill name="Legendary Dwarf Stance"/>, and use your special action key to the corner.
- Use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> at the corner.
- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
- Share <Boon name="might"/> with <Skill name="Heroic Command"/>.
- Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> for additional damage.
- Weapon swap to staff when phase ends.

**Add**

- Use <Skill name="Forced Engagement"/> on the first add.
- Use <Skill name="Surge of the Mists"/> on the second add.

**33-0%**

- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/> when everyone is in the middle.
- Use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> for the large AoE attack.
- Change to <Skill name="Legendary Renegade Stance"/>, and use <Skill name="Soulcleaves Summit"/> and <Skill name="Citadel Bombardment"/>.
- Share <Boon name="might"/> with <Skill name="Heroic Command"/>.
- Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> to deplete your energy.
- Change to <Skill name="Legendary Dwarf Stance"/>, and use your special action key to the corner.
- Use <Skill name="Inspiring Reinforcement"/> to grant <Boon name="Stability"/> at the corner.
- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
- Share <Boon name="might"/> with <Skill name="Heroic Command"/>.
- Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> for additional damage.

---

**Annotation**

- After using <Skill name="Inspiring Reinforcement"/>, make sure you gain the extra energy from <Trait name="Charged Mists"/> in the first phase.
- Time <Skill name="Inspiring Reinforcement"/> so that <Boon name="Stability"/> last long enough for the AoE attack in the middle.
- Use special action key while using <Skill name="Surge of the Mists"/> to break the defiance bar as quickly as possible.
- Be aware of energy management before changing to <Skill name="Legendary Renegade Stance"/> in the middle, to gain the extra energy from <Trait name="Charged Mists"/>.

</Tab>

<Tab specialization="Firebrand">
**General**
If your team does not have a <Specialization name="soulbeast"/> or a <Specialization name="dragonhunter"/>, you can take <Skill name="Wall of reflection"/> for omega reflects. If your team does have reflects then take <Skill name="standyourground"/>.

**Precast**
- Use <Skill name="Hallowed ground"/> to give a fire field and retal.
- Use <Skill name="Feelmywrath"/> and <Skill name="potenthaste"/> to give some quickness.
- Open <Skill name="tomeofjustice"/> and cast skill 5(Epilogue).
- Use <Skill name="banesignet"/> before taking the mistlock.
- Take the mistlock.
- You can precast <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss.
- You can also precast <Skill name="tomeofjustice"/> skill 4 and 5 just before starting the boss to max out burst.

**100%**

If you are not skipping the first Anomaly, you should place the <Skill name="Wall of reflection"/> in the middle since you are killing the anomaly in the middle when she is using her reflectable skill so it can be reflected by placing it in the middle.

If you are skipping the anomaly, use special action key to the corner as soon as the boss starts to move away from the middle, open <Skill name="tomeofcourage"/> and use skill 4 and 5.

When the boss reaches the corner use <Skill name="standyourground"/> to prevent your <Specialization name="soulbeast"/> to get interrupted during reflect.
Again it is recommended to start on scepter. Use your <Skill name="Bane Signet"/> to help with CC and boost the party dps as soon as Artsariiv arrives at the corners. Use it even if there is no CC-bar to improve your party dps. Always use <Skill name="Bindingblade"/> and <Skill name="Whirlingwrath"/> inside Artsariivs hitbox for big damage.

**Adds**

Help your team CCing with consumables. Do not waste your bane signet or <Skill name="Binding Blade"/> (GS5) for this. Use your special action key to quickly navigate to adds. Swap to scepter and camp it to be ready for the mid burst.

**Mid Burst**

Precast <Skill name="tomeofjustice"/> skill 4 and 5 to max out burst. Remember to use <Skill name="restoringreprieve"/> to give <Boon name="aegis"/> just before the boss slams in order to skip dodging it and cotinue to dps with the help of <Boon name="stability"/> from <Specialization name="renegade"/> and your <Boon name="aegis"/>.

**66% and 33%**

Start on scepter again. When Artsariiv arrives at the corners again, wait for her to throw the ball and then place your <Skill name="Wall of reflection"/> if there is no other reflect in team or <Skill name="standyourground"/> if there is.

</Tab>

<Tab specialization="Soulbeast">
Summon <Skill name="Frost Spirit"/> in middle before someone triggers her. While she is talking start your precast <Skill id="5531"/> and <Skill name="Barrage"/>. Use <Skill name="Maul"/> <Skill name="Hiltbash"/> and <Skill name="Maul"/> while she is still in the middle. Teleport to the corner and teleport <Skill name="Frost Spirit"/> to you.

Now go through this rotation:
- <Skill name="onewolfpack"/>, <Skill name="sicem"/>
- <Skill id="45743"/>, <Skill name="pathofscars"/> for insta CC
- <Skill name="Whirlingdefense"/> to reflect for omegadps

Use Consumables to CC the adds.

**66% and 33%**

- <Skill name="Maul"/> <Skill name="Hiltbash"/> <Skill name="Maul"/>
- <Skill id="41524"/> <Skill id="45743"/>
- Dodge (do not use sic em here)
- Special action key into the corner
- <Skill name="Maul"/> and <Skill name="sicem"/> into the cast
- <Skill name="Worldlyimpact"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/> to reflect again

If you dont skip anomalies you can just try to reflect and hope she targets someone close
or you could go for reflecting her spin attack.
</Tab>

<Tab specialization="berserker">
**General**  

If you run with a decent <Specialization name="soulbeast"/>, burn phases won't last long and your dps will be not be that cool, you have to focus on getting the banner placement right.

**Build variation**  
- Standard is Axe-Axe Mace-Mace
- Depending on the instabilities it can make sense to bring <Skill name="BerserkerStance"/>

**Prestacking**
- Drop a fire field with <Skill name="Flames of war"/>.
- Use <Skill name="For great justice"/> as soon as you see <Skill name="Moa stance"/> on your bar.
- Blast with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call of Valor" profession="Warrior"/>.
- Blast 12 Stacks of might with <Skill name="Banner of Strength"/> and <Skill name="Banner of Discipline"/>.
- Take the mistlock.
- While approaching the boss drop both of your banners. Depending on your group DPS you either place them in the middle or at the corner.
- Precast <Skill name="Flames of war"/> for dps
- Precast <Skill name="Mending"/>

**100% in mid**

- Use <Skill name="whirling axe"/> or <Skill name="Headbutt"/> to gain adrenalin fast.
- Depending on your team you wanna engage <Skill name="Berserk"/> before you use your special action key to get to Artsariiv. 
- Use <Skill name="Mending"/> to regain eventually lost health and <Trait name="peakperformance"/>. 
- Swap to your mace, be ready to <Skill id="14415"/> as soon as the breakbar appears.

**66% and 33%**

Pick up your banners and place them in the middle of the arena. Help your party to cc the adds, preferable by getting rid of the one in the middle, since you are there anyway. Replace your banners at the corner Artsariiv is going to jump to.

</Tab>

<Tab specialization="weaver">
**Precast**
- Start on sword/Dagger and <Skill id="5506"/> and <Skill id="5635"/>
- Start on <Skill id="5495"/>/<Skill id="5492"/> and use <Skill id="5691"/> to provide a fire field and blast it with <Skill id="40709"/>. 
- Swap to <Skill id="5492"/>/<Skill id="5495"/> and the use <Skill id="5690"/>, <Skill id="21656"/> and <Skill id="5522"/> to blast your fire field..
- Use <Skill id="5506"/> and <Skill id="5635"/> and swap back to <Skill id="5734"/> and<Skill id="5539"/>
- Swap to staff and <Skill id="5492"/>/<Skill id="5495"/> and then use <Skill id="5516"/>.
- Take the mistlock.
- As soon as someone catches an orb to start the boss use <Skill id="5531"/> on your <Skill id="5516"/> and then drop it. Use <Skill id="43762"/> , <Skill id="5548"/> and swap to<Skill id="5492"/>/<Skill id="5492"/> and use <Skill id="5501"/> on your staff . Then equip sword/dagger. This is a tight precast so make sure you practice it.

**100%**
- Use <Skill id="45313"/>,<Skill id="5557"/> and <Skill id="44451"/> when the boss is at the the middle. Then use Nova Launch to go the boss at the cornerwhen she moves and switch to <Skill id="5494"/>/<Skill id="5494"/> and use <Skill id="5737"/>.
- Use <Skill id="5687"/> to break the CC bar.

**Split Phase**
- Use <Skill id="44998"/> and <Skill id="5687"/>.
- Use >metal rod<. 

**66%**
- Start in <Skill id="5494"/>/<Skill id="5494"/> and do your burst in the middle.
- Blast your fire field for might in the middle.
- Use nova launch to go to the corner.
- Use <Skill id="5737"/> if off cd, else use <Skill id="5736"/> and deeps.

**33%**
- Start in <Skill id="5494"/>/<Skill id="5494"/> and do your burst in the middle.
- Blast your fire field for might in the middle.
- Use nova launch to go to the corner.
- Use <Skill id="5737"/> and do big deeps.

**Tryhard/Static**
- There are many ways to tryhard this encounter, which shall not be discussed here in depth.
- You can run <Skill id="44612"/>, start the precast on  <Skill id="5492"/>/ <Skill id="5494"/> and use  <Skill id="5548"/>, <Skill id="43762"/> and  <Skill id="5501"/> before the boss starts.
- Watch tym's video on 100 CM weaver rotations for more clarity.
<Message>
Advanced groups can let the second _Corporeal Reassignment_ trigger and /gg the third to save time. But if you failed the first nuke always make sure to kill the second _Temporal Anomaly_. Also sometimes there are communication issues, so if you have the third _Corporeal Reassignment_ always check if someone killed the _Temporal Anomaly_, before killing yourself.
</Message>

<Video title="Video Guide by Tym [1:49]" youtube="DaKI7Ccr_Ss"/>

</Tab>

<Tab specialization="dragonhunter">
**General**
If your team does not have a soulbeast, you can take <Skill name="Wall of reflection"/> for omega reflects. Kick your firebrand if he takes a wall/tome/shield. Use <Skill name="shieldofcourage"/> and <Skill name="shieldofwrath"/> strategically to block the knockbacking attacks.

**Precast**

- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the boss and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- Use <Skill name="Feelmywrath"/>.
- Take the mistlock.
- You can precast <Skill id="29789"/> (LB4), <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss in a coordinated team.

**100%**

If you are not skipping the first Anomaly, you should place the wall in the middle.
Again it is recommended to start on scepter. Use your <Skill name="Bane Signet"/> to help with cc and boost the party dps as soon as Artsariiv arrives at the corners. Use it even if there is no CC-Bar to improve your party dps. Always use <Skill name="Bindingblade"/> and <Skill name="Whirlingwrath"/> inside Artsariivs hitbox for big damage.

**Adds**

Help your team CCing with consumables. Do not waste your bane signet or <Skill name="Binding Blade"/> (GS5) for this. Use your special action key to quickly navigate to adds. Swap to scepter and camp it to be ready for the mid burst.

**66% and 33%**

When all adds are broken, your traps will be off cooldown again. Start on scepter again, use <Skill name="Shield of Wrath"/> to block the expanding AoE and fire everything you have.  
When Artsariiv arrives at the corners again immediately place your <Skill name="Wall of reflection"/>.

</Tab>
</Tabs>

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

<Tabs>
<Tab specialization="Renegade">
**Legends**  
* <Skill name="Legendary Renegade Stance"/> and <Skill name="legendaryassassinstance"/>.

**Suggested Boon Duration** `80%`

Maintaining <Boon name="Alacrity"/> in this encounter does require higher boon duration due to the length of the fight, and the necessity for <Boon name="Alacrity"/> throughout the encounter. Increase your concentration if you notice downtime in <Boon name="Alacrity"/>.

---

**Precast**

- Cast <Skill name="Ordersfromabove"/> for <Boon name="Alacrity"/> and <Skill name="Renewingwave"/> to blast, take the mistlock and repeat. The two casts of <Skill name="Ordersfromabove"/> overlap and grant twice the duration of <Boon name="Alacrity"/>. You can use <Skill name="DroptheHammer"/> for an additional blast.

**100-80%**

- Cast <Skill name="Soulcleaves Summit"/> on Arkk and auto attack until the Anomaly appear.
- Cast <Skill name="Icerazors Ire"/> on the Anomaly.
- Change to <Skill name="legendaryassassinstance"/>.
- Activate <Skill name="Impossible Odds"/>, and use <Skill name="Chilling Isolation"/> and <Skill name="Shackling Wave"/> to finish the Anomaly.
- Use <Skill name="Deathstrike"/> to quickly get back to Arkk.
- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
- Deplete your energy with <Skill name="Chilling Isolation"/>.
- Weapon swap and change to <Skill name="Legendary Renegade Stance"/> when the phase is finished.

**80-70%**

- Precast <Skill name="Darkrazors Daring"/>, <Skill name="Icerazors Ire"/>, and <Skill name="Soulcleaves Summit"/> at Arkk's location.
- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
- Use <Skill name="Surge of the Mists"/> with the special action key to break the defiance bar.
- Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.
- Weapon swap and change to <Skill name="legendaryassassinstance"/>.

**Archdiviner**

- Activate <Skill name="Impossible Odds"/>, and use <Skill name="Citadel Bombardment"/>, <Skill name="Chilling Isolation"/>, and <Skill name="Shackling Wave"/>.
- Use special action key if the defiance bar appear.
- Change to <Skill name="Legendary Renegade Stance"/> when the phase is finished.

**70-50%**

- Cast <Skill name="Soulcleaves Summit"/>, and <Skill name="Icerazors Ire"/>.
- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
- Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.
- Change to <Skill name="legendaryassassinstance"/>.
- Activate <Skill name="Impossible Odds"/>, and use <Skill name="Citadel Bombardment"/>, <Skill name="Chilling Isolation"/>, and <Skill name="Shackling Wave"/>.
- Weapon swap and change to <Skill name="Legendary Renegade Stance"/> when the phase is finished.

**50-40%**

- Precast <Skill name="Darkrazors Daring"/>, <Skill name="Icerazors Ire"/>, and <Skill name="Soulcleaves Summit"/> at Arkk's location.
- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
- Use <Skill name="Surge of the Mists"/> with the special action key to break the defiance bar.
- Share <Boon name="Might"/> with <Skill name="Heroic Command"/>.
- Weapon swap and change to <Skill name="legendaryassassinstance"/>.

**Gladiator**

- Activate <Skill name="Impossible Odds"/>, and use <Skill name="Citadel Bombardment"/>, <Skill name="Chilling Isolation"/>, and <Skill name="Shackling Wave"/>.
- Use special action key if the defiance bar appear.
- Change to <Skill name="Legendary Renegade Stance"/> when the phase is finished.

**40-30%**

- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/> in the middle.
- Cast <Skill name="Icerazors Ire"/> on the Anomaly.
- Use <Skill name="Chilling Isolation"/> and <Skill name="Shackling wave"/> to finish of the Anomaly.
- Weapon swap at the end of the phase.

**30-0%**

- Precast <Skill name="Darkrazors Daring"/>, <Skill name="Icerazors Ire"/>, and <Skill name="Soulcleaves Summit"/> at Arkk's location.
- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
- Use <Skill name="Surge of the Mists"/> with the special action key to break the defiance bar.
- Weapon swap and change to <Skill name="legendaryassassinstance"/>.
- Share <Boon name="Alacrity"/> with <Skill name="Orders from Above"/>.
- Activate <Skill name="Impossible Odds"/>, and use <Skill name="Citadel Bombardment"/>, <Skill name="Chilling Isolation"/>, and <Skill name="Shackling Wave"/> until the encounter is finished.

---

**Annotation**

- Kill the Anomaly in the 70-50% phase if your party struggles to survive without the Mistlock Singularity for the remainder of the encounter.
  - Use <Skill name="Icerazors Ire"/>, <Skill name="Chilling Isolation"/>, and <Skill name="Shackling Wave"/> to finish the Anomaly in this case.
- Weapon swap back to swords as early as you can in the phases where you break the defiance bar.
- Precast <Skill name="Darkrazors Daring"/> early enough to gain energy for <Skill name="Surge of the Mists"/> in the opening of 80-70%, 50-40%, and 30-0%.
  </Tab>

<Tab specialization="Firebrand">
**General**  
- Your goal is to start on scepter/sword at every 10% burn phase, thats why you need to consider weopenswaps carefully. 
- Pull adds in with GS5. 
- Cast <Skill name="Bane Signet"/> at mistlock, on all 3 CCs on Arkk and when 70-50% burst begins.
- The fastest way to do the orbs is to walk into the blue stuff and aa with scepter.
- Use <Skill name="binding blade"/> inside Arkks hitbox when adds are present.

**Precast**
- Use <Skill name="Hallowed ground"/> to give a fire field and retal.
- Use <Skill name="Feelmywrath"/> and <Skill name="potenthaste"/> to give some quickness.
- Open  <Skill name="tomeofjustice"/> and cast skill 5(Epilogue).
- Use <Skill name="banesignet"/> before taking the mistlock.
- Take the mistlock.
- You can precast <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss. 
- You can also precast <Skill name="tomeofjustice"/> skill 4 and 5 just before starting the boss to max out burst (Take the portal to boss with <Specialization name="soulbeast"/> instead of waiting for someone to trigger it).

**100%**

Use <Skill name="tomeofcourage"/> skill 4 and 5 to skip first fear.

**Split Phases**

Use <Skill name="binding blade"/> to pull mobs, open <Skill name="tomeofjustice"/> and use 3rd skill to pull mobs inside boss and 4th skill to put down fire field and use Nova Launch to blast it for <Boon name="might"/>.
</Tab>

<Tab specialization="Soulbeast">
**General**
- You can take <Skill name="trollunguent"/> for pushing the orbs inside the lightning
- In organized groups its worth it to take <Skill name="Frosttrap"/> over <Skill name="Signetofthewild"/>.
- In organized groups you can take longbow and use <Trait name="Leaderofthepack"/>
- Do not use <Skill name="Sicem"/> on 10% burns. 
- Push orbs with longbow inside the lightning. Use <Skill name="trollunguent"/> to stay alive.

**Precast**

Precast <Skill name="Frosttrap"/> on the boss like a <Specialization name="Dragonhunter"/> in disguise. Remember to share <Skill name="Moastance"/> and blast with <Skill name="Callofthewild"/>. Share <Skill name="One wolf pack"/> and take the mistlock.

If you have a portal to get there early, summon your <Skill name="Frost spirit"/>.

**Opening**

- <Skill id="5531"/>
- <Skill name="Frosttrap"/> so you have two of those ticking at the same time.
- <Skill name="Sicem"/>
- <Skill name="Barrage"/> <Skill name="Pointblankshot"/> <Skill name="Rapidfire"/>
- <Skill name="Worldlyimpact"/>
- <Skill name="Pathofscars"/> <Skill name="Whirling defense"/>
- <Skill id="45743"/> <Skill id="41524"/>

**10% burn phases**

Your dps will be low, because you do not want to use <Skill name="Sicem"/> there. You can either do <Skill name="Whirling defense"/> or <Skill name="Barrage"/> <Skill name="Pointblankshot"/> <Skill name="Rapidfire"/>.

**Archdiviner phase**

Pull one add with <Skill name="Path of scars"/>. This does not work reliable.  
The weaver should give you a <Skill name="conjurefierygreatsword"/> in the archdiviner phase. Take it and use <Skill name="Fierywhirl"/> in combination with the special action key to get all hits on the archdiviner.

Precast <Skill id="5531"/> when archdiviner is dead.

**Big burn phase**

- <Skill name="Barrage"/>
- <Skill name="onewolfpack"/> <Skill name="Sicem"/>
- <Skill name="Frosttrap"/>
- <Skill name="Pointblankshot"/> <Skill name="Rapidfire"/>
- <Skill name="Worldlyimpact"/>
- <Skill name="Pathofscars"/> <Skill name="Whirling defense"/>

**Gladiator phase**

You can use <Skill name="Sicem"/> and <Skill name="whirlingdefense"/> to kill him fast.

**10% burn phase**

Press random buttons, but no buttons with cooldowns.

**Last big burn phase**

Full rotation with everything off cooldown.
</Tab>

<Tab specialization="Warrior">
Usually the <Specialization name="Renegade"/> is responsible for slaying the Temmporal Anomaly, nonetheless pay 
close attention to it and assist if necessary. Dont forget to use `Nova Launch` to circumvent the effects of Arkk's _Solar Fury_ and _Solar Discharge_.

**Precast**

Use a <Item id="78978"/>, use special action key to get to the platform and gprecast <Skill id="14405"/>, <Skill id="14407"/>, <Skill id="14408"/> and a <Skill id="14419"/>. Take the portal back.

Help pre-stacking at Mistlock Singularity with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call of Valor" profession="Warrior"/>. Do not take the mistlock to early or you will need more than 1-2 hits to fill up your adrenalin. Also before taking the mistlock, use your special action key to not bug the cooldown reset out and precast <Skill name="mending"/>.

**Bloom phases**

If you are full hp, you can step into the lightning, auto attack your bloom until it gets pushed towards the pillar. Use a <Skill name="Throw axe"/> to finish your add. Use <Skill name="Mending"/> afterwards to regain health.

**Add phases**

Refresh your <Skill id="14405"/> and <Skill id="14407"/> at the archdiviner and gladiator adds by blasting a firefield.

---

**<Specialization name="Berserker"/>** (Standard Axe/Axe Axe/Mace)

<Message>
You run <Trait id="2049"/> and use <Skill id="14419"/> at 50% to keep up might!
</Message>
Use atleast <Skill id="14415"/> at every breakbar.

In better teams do not use your <Skill id="30185"/> in the 2nd and 4th phase. You want to save it for the longer 20% burns. In bad teams you do not need to put so much thought into it.

**<Specialization name="Warrior"/>** (Standard Axe/Axe Mace/Mace)

If your <Specialization name="Renegade"/> is a useless piece of shit, you can play Core to counter the lack of cc.

</Tab>

<Tab specialization="weaver">
**Precast**
- Start on sword/Dagger and <Skill id="5506"/> and <Skill id="5635"/>
- Start on <Skill id="5495"/>/<Skill id="5492"/> and use <Skill id="5691"/> to provide a fire field and blast it with <Skill id="40709"/>. 
- Swap to <Skill id="5492"/>/<Skill id="5495"/> and the use <Skill id="5690"/>, <Skill id="21656"/> and <Skill id="5522"/> to blast your fire field..
- Use <Skill id="5506"/> and <Skill id="5635"/> and swap back to <Skill id="5734"/> and<Skill id="5539"/>
- Swap to  <Skill id="5494"/>/<Skill id="5492"/> and then use <Skill id="5516"/>.
- Take the mistlock.

**Tryhard Precast**
- **Do this only if you are on voice with your static**.
- Use Nova Launch/portal to go the the platform early and use <Skill id="5531"/> on your <Skill id="5516"/> and then drop it. Use <Skill id="5501"/> on your staff . Then equip sword/dagger and shout on voice to start the boss. This is a tight precast so make sure you practice it otherwise staff weaver RIP.
### **100%**
- Go <Skill id="5494"/>/<Skill id="5494"/> as soon as the boss starts and use <Skill id="5531"/> on your <Skill id="5516"/> and then drop it and follow with <Skill id="5737"/>  and the usual burst.

**Solar Bloom**
- For this phase start on <Skill id="5494"/>/<Skill id="5492"/> and auto attack the bloom once and then attune <Skill id="5494"/>/<Skill id="5494"/> to trigger <Trait id="222"/> on the bloom to push it into the pillar. This is the fastest way to do your bloom.

**80% and 50%**
- <Skill id="43803"/> -> <Skill id="43074"/> -> <Skill id="5529"/> -> <Skill id="45313"/> -> <Skill id="44451"/> -> <Skill id="5557"/>.

**70%**
- Use <Skill id="5737"/> and the usual burst.

**40%**
- Precast <Skill id="5516"/> as the phase is starting and use <Skill id="5531"/> and <Skill id="5697"/> with Nova Launch inside the hitbox and the drop it.

**30%**
- Pick up the <Skill id="5516"/> and open with <Skill id="5531"/> and the drop it. Use <Skill id="5737"/> and follow with the usual burst.
 
<Video title="Video Guide by Tym [3:32]" youtube="DaKI7Ccr_Ss"/>

</Tab>

<Tab specialization="Dragonhunter">
**General**  
- Good teams: start on scepter/sword, so that you are on scepter/sword during the bloom phase.
- Bad teams: start on greatsword and do SC rotation
- Your goal is to start on scepter/sword at every 10% burn phase, thats why you need to consider weopenswaps carefully. 
- Pull adds in with GS5. 
- Cast <Skill name="Bane Signet"/> early, so you get more dps time. 
- The fastest way to do the orbs is to walk into the blue stuff and aa with scepter. Use <Skill name="Wings of Resolve"/> to regain health. 
- Use <Skill name="binding blade"/> inside Arkks hitbox when adds are present.

**Precast**

- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the boss and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- Use <Skill name="Feelmywrath"/>.
- Take the mistlock.
- You can precast <Skill id="29789"/> (LB4), <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss if you are using a portal.

</Tab>
</Tabs>
