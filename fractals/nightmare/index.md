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
**DISCLAIMER** <br/>
Chrono is not easy for a beginner, so it'll take some time for you to learn this properly.     
*I believe in you.*

For these pug strategies I will always assume that this is the comp you'll be running: <Specialization name="chronomancer"/>, <Specialization name="Warrior"/>, <Specialization name="weaver"/>, <Specialization name="weaver"/>, <Specialization name="Holosmith"/>/<Specialization name="Dragonhunter"/>/<Specialization name="Soulbeast"/>

Since triple weaver is extremely hard to pull off in a group that is not organized due to the lack of CC, a <Specialization name="Dragonhunter"/>/<Specialization name="Holosmith"/>/Power<Specialization name="Soulbeast"/> helps shorten the CC gap and brings vulnerability to the fights.

<Specialization name="Druid"/> is bad, it does not do enough cc, it does no dps and post nerf spirits are subpar aka not worth using over another dps class.

The common misconception is that if you run with a druid no one in the group will ever die thanks to the heals, while this might be true in some cases, we've found that if the boss dies faster, it's far less likely that your group will wipe.  
Keep in mind that this has nothing to do with elitism or tryharding, most bosses become very hard to kill if you waste time, look at Arkk for example, at 30% after the triple beam attack, if the boss isn't dead by then it'll start spawning 3/4 mechanics at the same time that are hard to deal with if you're not experienced.

In this guide I am also going to assume that you're running the proper gear/food and that your chronomancer basics are solid, with an emphasis on not wasting your concentration proc when swapping weapons.

99CM is a fractal level that relies heavily on CC bars being broken
fast, there is little room for mistakes, especially while playing chrono.  
You should never pug this with a triple weaver comp, go for 2 <Specialization name="weaver"/> and an extra dps class that will help you break CC bars like <Specialization name="Dragonhunter"/>/<Specialization name="Holosmith"/>/Power <Specialization name="Soulbeast"/>.  
Your <Specialization name="Warrior"/> will have to help you CC as well. If your team does not help you with this, there's not really much you can do.
Regardless, don't flame them, if you want to improve try to record your gameplay and see if you could've done anything different to carry the fight harder.

**Pug**  
Build: Chaos  
Weapons: sword/shield pistol  
Skills: <Skill id="29519"/>

**100%-75%**  
Run in and wait for the boss to spawn, right before it becomes vulnerable use <Skill id="10191"/>+<Skill id="10190"/> to get some boons on youself , when the boss is vulnerable use <Skill id="10175"/> to proc passive <Skill id="10236"/> and then right before its first attack hits use your <Skill id="10192"/> to give Aegis to the group.

You're now ready to cc the boss.

**Be Fast**  
Get 1 clone up with sword 3, cast <Skill id="30643"/> and mid-cast use your <Skill id="29830"/>, proceed to use your <Skill id="10236"/> and then <Skill id="29519"/>.  
**Be Fast**

**First Knight**  
You have every cooldown available, quickly use your <Skill id="30643"/> on the add, use your wells, swap to get your concentration proc , <Skill id="10236"/> and wait for your group to kill it.

**75%-50%**  
Your passive <Skill id="10236"/> should be up a few seconds after the bubble ends, try to keep track of the internal cooldown in your mind.

Now this will sound a bit strange, but it's better if you don't fully break the cc bar during this phase, try to leave it at 10%/20% instead , get the boss to 50% HP and move to the next add.

**Second Knight**  
Use your <Skill id="30643"/> on this add as well (and <Skill id="10287"/> possibly), wait for your team and proceed to share boons once again and kill it.

**50%-25%**

This is where you want to break the CC bar instantly (since we left it at 10%/20% before).
This allows you to burst the boss hard to 25% and get to the last add before the fight gets annoying.

**Third Knight**  
**Be fast**  
If you have <Skill id="29830"/> : Use your <Skill id="29519"/> on it and press <Skill id="29830"/> in the middle of the cast so you can <Skill id="29519"/> both the add and the boss after (Also share some boons or cast wells inside <Skill id="29830"/>). Then proceed to destroy the add.

If you don't have <Skill id="29830"/> : <Skill id="29519"/> the add , share boons and whatnot and kill it.  
**Be fast**

**25%-0%**  
If you still have a <Skill id="29519"/>, Congratulations! It's your lucky day. <Skill id="29519"/> the boss, drop all the cc you have on it , share boons and kill it.

If not, use your <Skill id="30643"/> and make sure it hits the boss , <Skill id="10287"/>, pray that your team CC's as well and finish the boss.

**Tryhard**  
Exactly the same as Pug MAMA, except you won't have CS for the Third Add .
Simply Moa the third add instantly and ToT+F3 MAMA on the 25 – 0 phase.
</Tab>

<Tab specialization="warrior">
Already place your banners (the more the merrier) after killing the third Assault Knight of MAMA's pre-event. Help pre-stacking at Mistlock Singularity with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call to Arms" profession="Warrior"/>.

### <Instability name="No Pain, No Gain"/> <Specialization name="Spellbreaker"/> (Dagger/Axe Mace/Axe)

Start MAMA on Dagger/Axe. Use <Skill id="14402"/>, <Skill name="Breaching Strike" profession="Warrior"/>, <Skill name="Disrupting Stab" profession="Warrior"/>, block MAMA's spin attack with <Skill name="full counter" profession="Warrior"/> and continue with <Skill name="Skull Crack" profession="Warrior"/> (if <Skill id="14502"/> won't break MAMA's Defiance bar use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/>,
<Skill name="Dual Strike" profession="Warrior"/>, <Skill name="Whirling Axe" profession="Warrior"/>. For the Assault Knights every 25% use <Skill name="Skull Crack" profession="Warrior"/>, <Skill name="Pommel Bash" profession="Warrior"/> and <Skill id="14502"/> to break its Defiance bar and simultaneously remove its boons. As soon as MAMA is vulnerable use <Skill name="Skull Crack" profession="Warrior"/>, <Skill name="Breaching Strike" profession="Warrior"/>, Disrupting
Stab, block MAMA's spin attack with <Skill name="full counter" profession="Warrior"/> (if <Skill id="14502"/> won't break MAMA's Defiance bar use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/>, <Skill name="Dual Strike" profession="Warrior"/> and <Skill name="Whirling Axe" profession="Warrior"/>. At 25% utilize <Skill name="Winds of Disenchantment" profession="Warrior"/> for the last Assault Knight and
simultaneously keeping MAMA from reapplying boons.

<Message>
Attacks reliably triggering <Skill name="full counter" profession="Warrior"/>: *MAMA's AoE spin*, *MAMA's spinning arms* (33%), *MAMA's jump attack* (33%) and *MAMA's ground smash attack* (33%).
</Message>

### without <Instability name="No Pain, No Gain"/> <Specialization name="Warrior"/> (Standard Axe/Axe Mace/Mace)

Start MAMA on Mace/Mace. Tnstantly break MAMA's Defiance bar using <Skill id="14402"/>, <Skill name="Tremor" profession="Warrior"/>, <Skill name="Pommel Bash" profession="Warrior"/>, <Skill name="Skull Crack" profession="Warrior"/> (if <Skill id="14502"/> won't break MAMA's Defiance bar use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/> and continue with standard rotation on
Axe/Axe. Fast Hands allows you to quickly adapt to what is currently needed in the encounter and consumables like <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>. Keep an eye on MAMA's <Condition name="vulnerability"/> stacks and use <Skill name="crushing blow" profession="Warrior"/> if it runs low.
</Tab>

<Tab specialization="weaver">
Start the fight with <Skill id="5531"/> followed by the <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> opener if you have high damage or the <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> opener if you have low damage. Make sure to hit you <Skill name="Pyroclastic Blast"/> beside MAMAs hitbox since she will still be invulnerable while you cast it and as a projectile it despawn, if it does not hit the ground.

You should have a <Skill id="5624"/> available for each knight, hit them with <Skill id="5733"/> and <Skill id="5725"/> if ready (do not use <Skill id="5725"/> on MAMA if she is only 2-3% away from becoming invulnerable). You can pre cast <Skill id="5733"/> while the adds spawn. You will hit the knight as long as you are in his hitbox while finishing the cast even though you do not have him in target.

Make sure to place your weapons in places where you can pick the up again. The first set in the middle or the second add and the second <Skill id="5624"/> to the third add.

You can use <Skill id="5697"/> or <Skill id="5680"/> to reach the blue barrier faster, ideally while getting as many hits in the bosses hitbox as possible.
</Tab>

<Tab specialization="druid">
If you have problems with incoming damage, swap <Skill id="12497"/> with <Skill id="12495"/> to grant <Boon name="protection"/> to the party.
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
<Skill id="5738"/> is very strong against the groups of Krait.

Use <Skill id="5536"/> to teleport up to the altars.

You can pull both sides with <Skill id="5491"/> (for the right side, jump at the end of your [cast](https://www.youtube.com/watch?v=lNZEM9StauU)).

If the person who pulled your side ported up the other side to fast and the mobs come back use <Skill id="5683"/> and <Skill id="5686"/> to prevent them from reachin the circle before it is tabbed. Make sure you are attuned correctly for this in time.
</Tab>

<Tab specialization="warrior">
Exchange <Skill id="14502"/> for <Skill name="on my mark" profession="Warrior"/> and already swap to your weapon sets with Superior Sigil of Serpent Slaying.

### <Instability name="No Pain, No Gain"/> <Specialization name="Spellbreaker"/> (Standard Dagger/Axe Greatsword)

At the first set of altars draw the Elite Nightmare Hypnoss with <Skill name="on my mark" profession="Warrior"/> to the narrow corridor so that the Chronomancer can pull them together with <Skill name="Into the void" profession="Mesmer"/>. Assist in killing the Elite Nightmare Hypnoss and capturing one of the
altars. At the second set of altars, use <Skill name="Winds of Disenchantment" profession="Warrior"/> on your Chronomancer's <Skill name="temporal curtain" profession="Mesmer"/> and move close to the altar on the right side. Pull the Elite Nightmare Hypnoss occupying the altar to the mid by using <Skill name="on my mark" profession="Warrior"/>
and assist in killing them and capturing the mid altar respectively.

### without <Instability name="No Pain, No Gain"/> <Specialization name="Warrior"/> (Axe/Axe Greatsword)

At the first set of altars draw the Elite Nightmare Hypnoss with <Skill name="on my mark" profession="Warrior"/> to the narrow corridor so that the Chronomancer can pull them together with <Skill name="Into the void" profession="Mesmer"/> and disable them with <Skill name="Tremor" profession="Warrior"/>. Assist in killing the Elite Nightmare Hypnoss
and capturing one of the two altars. At the second set of altars, wait for your Chronomancer's <Skill name="temporal curtain" profession="Mesmer"/> and disable the Elite Nightmare Hypnoss with <Skill name="Tremor" profession="Warrior"/>. Immediately move close to the altar on the right side and pull the Elite
Nightmare Hypnoss occupying the altar to the mid by using <Skill name="on my mark" profession="Warrior"/>. Assist in killing the remaining Elite Nightmare Hypnoss and capture the mid altar respectively.
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
Build: Chaos     
Weapons: sword/shield- greatsword/staff     
Skills: <Skill id="21750"/>, <Skill id="29519"/>

You want to play GS or Staff on this boss because:

1. As soon as the boss spawns you can instantly share boons with either <Skill id="10221"/> or <Skill id="10216"/>.
2. You generate an extra clone that will be very useful for your <Skill id="29830"/> by using <Skill id="10310"/> or <Skill id="10333"/>.

**100%-66%**  
As soon as the boss spawns you will use <Skill id="10191"/> + <Skill id="10190"/> to get boons up and share using passive <Skill id="10236"/> (<Skill id="10221"/> or <Skill id="10216"/> depending on what you're running).

You will also use <Skill id="10333"/> or <Skill id="10310"/> to get the extra clone we talked about.

You're then going to swap to sword, use <Skill id="10173"/> to get an extra clone up and then quickly:

<Skill id="30643"/>(MID <Skill id="29830"/>) -> <Skill id="10236"/> -> <Skill id="29519"/>+<Skill id="10287"/>(the cc bar will be up by now) -> Both Wells -> <Skill id="29830"/> END -> <Skill id="10236"/>

**First Split**  
You will help your <Specialization name="Warrior"/> (or a <Specialization name="weaver"/>) kill his add in this phase and go back to the boss waiting for it to get vulnerable again.

**66%-33%**  
Cast your wells and <Skill id="10236"/> as soon as it's off cooldown, also try to distort (<Skill id="10192"/>) the circle attack so that your group can keep doing dps without having to dodge.

Generally pug's dps is low so it's likely that you will get another breakbar in this phase, if the boss' HP is above 40% I suggest you try to break it using your <Skill id="30643"/>+<Skill id="10287"/>, if it's below 40% try to dps the boss to 33% so that the breakbar will disappear.

**Second Split**  
You will help your <Specialization name="Warrior"/> (or a <Specialization name="weaver"/>) kill his add in this phase and go back to the boss waiting for it to get vulnerable again.

**33%-0%**  
When you get back to the boss you have to share with <Skill id="10236"/> and cast both wells, then there are 2 possibilities:

1. If you saw no cc bar on the 66 – 33 phase, the cc bar in this phase will be up very soon, so distance yourself from the boss, when its up cast <Skill id="30643"/> (make sure you're still in range), <Skill id="29519"/>, <Skill id="10287"/> and either <Skill id="10220"/> or <Skill id="10169"/> depending on what you're playing.
2. If you did cc during 66 – 33 , the next bar will be very delayed and you can simply share boons, wait and cc using <Skill id="30643"/>+<Skill id="29519"/>+<Skill id="10287"/> when the bar is up.

It's not always the same, so you need to become versatile because chrono does not work on a rotation basis, but if you keep these steps in mind you should be fine.

**Tryhard**  
The only difference here is that with good dps you will not get a breakbar during the 66 – 33 phase.  
Keep Moa and ToT for the 33 – 0 phase to instantly break the bar and kill the boss.  
If you do get a breakbar in phase 2 `\gg`->leave party and search for a better group.
</Tab>

<Tab specialization="warrior">
Set a personal Waypoint at one of the four places where Echoes of the Unclean will spawn at 66% (Warrior usually takes North). Help pre-stacking at Mistlock Singularity with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call to Arms" profession="Warrior"/>. If your group does one /gg at Siax, 
already place banners (the more the merrier). If not, just cast banners while running towards Siax. If additional Defiance bar damage is needed make use of <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>.

### <Instability name="No Pain, No Gain"/> <Specialization name="Spellbreaker"/> (Standard Dagger/Axe Greatsword)

Start channeling <Skill name="Winds of Disenchantment" profession="Warrior"/> while running towards Siax. Engage with <Skill id="14402"/>, <Skill id="14502"/>, <Skill id="14547"/>, <Skill name="Hundred Blades" profession="Warrior"/>, <Skill name="Whirlwind Attack" profession="Warrior"/> (cancel in Skorvald's hitbox by using weapon swap), <Skill name="Breaching Strike" profession="Warrior"/>, <Skill name="Dual Strike" profession="Warrior"/> and as soon as Siax begins
channeling Caustic Explosion use <Skill name="Disrupting Stab" profession="Warrior"/> (if <Skill id="14502"/> won't break Siax's Defiance bar use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/>, <Skill name="Whirling Axe" profession="Warrior"/>, <Skill name="Breaching Strike" profession="Warrior"/>, <Skill id="14547"/> and <Skill name="Hundred Blades" profession="Warrior"/>. At 66% use <Skill name="Rush" profession="Warrior"/> to close the gap to the Echo
of the Unclean (not affected by No Pain No Gain) and kill it with <Skill id="14547"/>, <Skill name="Hundred Blades" profession="Warrior"/> and <Skill name="Whirlwind Attack" profession="Warrior"/>. After killing the Echo of the Unclean immediately swap to Dagger/Axe, assist at any of the other Echoes of the Unclean if
necessary and strip Siax's boons by using <Skill name="Breaching Strike" profession="Warrior"/>, <Skill name="Disrupting Stab" profession="Warrior"/> and <Skill id="14502"/> and continue with standard rotation. Repeat for Echoes of the Unclean spawning at 33%.

<Message> 
Attacks reliably triggering <Skill name="full counter" profession="Warrior"/>: *Summon Nightmare Hallucination* (risky), *Tail Lash* and the *explosion of the Volatile Hallucinations*.
</Message>

### without <Instability name="No Pain, No Gain"/> <Specialization name="Warrior"/> (Standard Axe/Axe Greatsword)

Begin with <Skill id="14402"/>, <Skill name="Bladetrail" profession="Warrior"/>, <Skill id="14502"/>, <Skill id="14547"/>, <Skill name="Hundred Blades" profession="Warrior"/>, <Skill name="Whirlwind Attack" profession="Warrior"/> (cancel in Skorvald's hitbox by using weapon swap), <Skill name="Throw Axe" profession="Warrior"/>, <Skill name="Cyclone Axe" profession="Warrior"/>, <Skill name="Dual Strike" profession="Warrior"/>, <Skill id="14502"/>, <Skill name="Whirling Axe" profession="Warrior"/>. Use <Skill name="Rush" profession="Warrior"/> at 66% and 33% to close the gap to the Echo of the Unclean
and follow just follow standard rotation.
</Tab>

<Tab specialization="weaver">
 Start the fight with <Skill id="5531"/> followed by the <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> opener if you have high damage or the <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> opener if you have low damage. You want to start with this while the last Illusions turn hostile.

On the East and South _Echoes of the Unclean_, you can use <Skill id="5697"/> from <Skill id="5516"/> against the wall to deal enormous damage. On the second add spawn you can <Skill id="5697"/> at any location except east.

With normal group damage Siax should turn invulnerable at the end of your first <Skill id="5624"/>. Use <Skill id="5680"/> to reach your add fast. Place a <Skill id="5548"/> and use <Skill id="5697"/> to kill your add fast. If you are having trouble killing the add fast after the <Skill id="5548"/> nerf also hit it with <Skill id="5517"/>. It can be worth it depending on your group to attune to <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> while killing the add for additional skills and a faster <Trait id="2131"/>. Alternativle start with <Skill name="Eruption"/>, <Skill name="Lava Font"/>, <Skill id="5517"/> and <Skill id="5697"/> through the mob back to the boss (Only do it if you are sure your <Skill id="5697"/> will kill the mob. It feels really bad to reach the boss with your add surviving with less than 1% life).

Continue with <Skill id="5531"/> on Siax and restart in <Skill id="5492"/>.

If your group damage is too low to pick up your second <Skill id="5516"/> for the second add, place a <Skill id="5548"/> on it, attune to <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> and use <Skill id="41125"/> to kill it quickly.

Continue with <Skill id="5494" text="false"/>/<Skill id="5492" text="false"/> and <Skill id="5737"/> on Siax.

If you play with three weavers split your <Skill id="5737"/> so you have one each phase.

If you want to try hard play air instead of arcane, use <Skill id="21656" /> and pre cast <Skill id="5501"/> before the fight to have it ready fast enough in phase 2 and 3.
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
Build: Chaos     
Weapons: sword/shield - staff      
Skills: <Skill id="30305"/>, <Skill id="29519"/>     
The only "challenging" part about this boss for you is the opener as it will require a bit of good timing and mechanical skill, you can even practice this part alone on the boss if you want to.

**Pug**

**100%-66%**  
When the boss spawns, wait a few seconds for it to get vulnerable then:

1. Very quickly <Skill id="10191"/>+<Skill id="10190"/> to get boons up and <Skill id="10216"/> to proc passive <Skill id="10236"/>
2. Swap to sword and cast <Skill id="10337"/> on the boss
3. Go inside the bubble
4. <Skill id="30643"/> and while you cast it use <Skill id="29830"/>
5. <Skill id="10236"/> + both Wells
6. <Skill id="29519"/>+<Skill id="10287"/>
7. Share the rest of your boons and get read for the boss to do his orange circle attack and distort that using <Skill id="10192"/>

If you do this correctly, the 2 Phantasms from <Skill id="10216"/> will expire when you're inside your <Skill id="29830"/>, giving you 2 more clones to CC with using your <Skill id="10287"/>.

(Make sure you're not doing this rotation too fast or you will CC to soon missing the breakbar)

Don't use your <Skill id="29519"/> for the rest of this phase.

**66%-33%**  
(It gets easier now)  
As soon as you're back on the boss, Use <Skill id="10236"/> and after that both wells, then CC the boss with the help of your friends.  
Wait for the bubble, and when the next breakbar is up your <Skill id="29830"/> should be up as well.  
Simply do your whole rotation in <Skill id="29830"/> without forgetting to squeeze in <Skill id="29519"/> and <Skill id="30643"/> to CC the second bar.

**33%-0%**  
Use <Skill id="10236"/> and after that both wells, then CC the boss with the help of your friends. If you do not have friends remember that <Item id="8664"/>s, <Item id="8759"/>s and <Item id="8678"/>s will never betray you.

**Tryhard**  
Again, the opening on this fight is exactly the same as pug Enso.  
At 66% you will not have access to your <Skill id="29830" text="false"/> so you can use it for boons or keep it for 33% to double <Skill id="30643" text="false"/> / <Skill id="10236" text="false"/>.  
On the first bar at 66% you will want to <Skill id="30643" text="false"/> and <Skill id="10287" text="false"/> , and for the second one use <Skill id="29519" text="false"/> and <Skill id="10169" text="false"/>.  
You want to break both bars so that the boss will stay stunned during the whole phase so that you won't lose time by getting the bubble spawn ( Your group dps has to be high in order to achieve this).
</Tab>

<Tab specialization="warrior">
Place banners already on Ensolyss's platform if your group does one /gg before. Help pre-stacking at Mistlock Singularity with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call to Arms" profession="Warrior"/>. If additional Defiance bar damage is needed make use of <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>. During the altar capture phase at 66% and 33% 
<Skill id="14402"/> comes in very handy here to refill your adrenaline, endurance and health.

### <Instability name="No Pain, No Gain"/> <Specialization name="Spellbreaker"/> (Dagger/Axe Greatsword)

Start channeling <Skill name="Winds of Disenchantment" profession="Warrior"/> while Ensolyss is spawning. Open your rotation with <Skill name="Bladetrail" profession="Warrior"/>, <Skill id="14402"/>, <Skill id="14502"/>, <Skill id="14547"/>, <Skill name="Hundred Blades" profession="Warrior"/>, <Skill name="Whirlwind Attack" profession="Warrior"/> (cancel in Skorvald's hitbox by using weapon swap), <Skill name="Breaching Strike" profession="Warrior"/>, <Skill name="Dual Strike" profession="Warrior"/> and as
soon as Nightmare Devastation ends use <Skill name="Disrupting Stab" profession="Warrior"/> (if <Skill id="14502"/> won't break Ensolyss's Defiance bar use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/>, <Skill name="Whirling Axe" profession="Warrior"/>, <Skill name="Breaching Strike" profession="Warrior"/>, <Skill id="14547"/>, <Skill name="Hundred Blades" profession="Warrior"/> and
follow standard rotation. At 66% and 33% swap to Dagger/Axe and capture one of the five altars. After capturing all five altars remove Ensolyss's boons with <Skill id="14502"/> and <Skill name="Breaching Strike" profession="Warrior"/> or pre-cast <Skill name="Winds of Disenchantment" profession="Warrior"/> while Ensolyss is
returning. Once Ensolyss's Defiance bar appears, immediately use Disrupting Strike, <Item id="8677"/>, <Item id="8749"/>, <Skill id="14502"/> and continue standard rotation until the second Defiance bar appears. Break it with <Item id="8664"/>, <Item id="8677"/>,
<Item id="8749"/>, <Skill id="14502"/> and resume standard rotation.

<Message> 
Attacks reliably triggering <Skill name="full counter" profession="Warrior"/>: *Serpent Strike*, *Tail Lash*, *Lunge* (the dash), *Upswing* (either <Skill name="full counter" profession="Warrior"/> Ensolyss's Attack or Nightmare Hallucinations), *Tormenting Blast*, *Caustic Grasp* and *Charge of the Nightmare Hallucinations* below 15%.
</Message>

### without <Instability name="No Pain, No Gain"/> <Specialization name="Warrior"/> (Standard Axe/Axe Mace/Mace)

Begin the encounter on Axe/Axe with <Skill id="14402"/>, <Skill id="14502"/>, <Skill name="Eviscerate" profession="Warrior"/>, <Skill name="Whirling Axe" profession="Warrior"/>, <Skill name="Dual Strike" profession="Warrior"/>, <Skill name="Throw Axe" profession="Warrior"/>, <Skill name="Cyclone Axe" profession="Warrior"/> and immediately swap to Mace/Mace to break Ensolyss's Defiance bar with <Skill name="Tremor" profession="Warrior"/>, <Skill name="Pommel Bash" profession="Warrior"/> and <Skill name="Skull Crack" profession="Warrior"/>. Once Ensolyss's
Defiance bar is broken continue with standard rotation on Axe/Axe. At 66% and 33% swap to Mace/Mace and capture one of the five altars. As soon as Ensolyss returns attack with <Skill name="Mace Smash" profession="Warrior"/>, <Skill name="Mace Bash" profession="Warrior"/> and <Skill name="Pulverize" profession="Warrior"/> until the Defiance bar appears.
Immediately use <Skill name="Tremor" profession="Warrior"/>, <Skill name="Skull Crack" profession="Warrior"/> (if <Skill id="14502"/> won't break Ensolyss's Defiance bar use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/> and continue standard rotation until the second Defiance bar appears. Break it with Pommel
Bash, <Skill name="Skull Crack" profession="Warrior"/> and <Item id="8664"/>, <Item id="8677"/>, <Item id="8749"/>, <Skill id="14502"/> and resume standard rotation. Keep an eye on <Condition name="vulnerability"/> stacks and use <Skill name="crushing blow" profession="Warrior"/> if it runs low.
</Tab>

<Tab specialization="weaver">
Start the fight in <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> with <Skill id="5531"/> followed <Skill id="5528"/> while Ensolyss spawns, continue with <Skill id="5548"/> and <Skill id="5491"/> until <Skill id="5548"/> is ready again. Know cast your situational opener to hit as much damage as possible in the breakbar.

If your damage is low and he charges cast your second <Skill id="5501"/> in the middle of the platform after dodging his first charge. If all five players stand there he will teleport back into it.

If you have two or more weavers one should take <Skill id="5567"/> and switch weapons with the other weavers.

If you summond you <Skill id="5516"/> in phase one pick it up before the orbs spawn and keep it the whole orb phase.

Start the fight at 66% with the <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> opener. Use <Skill id="5531"/> if you have a <Skill id="5516"/> in hand.

Hit the second breakbar with either <Skill id="5733"/> or <Skill id="5721"/>.

After the orb phases, reopen in <Skill id="5495" text="false"/>/<Skill id="5492" text="false"/> and cast <Skill id="5528"/> about a second before the orb phase ends. Make sure to have your <Skill id="5501"/> either finished before the first <Control name="knockback"/> zone goes off or start it after making sure you won't get hit.

If you are close to either 66% or 33% and have your <Skill id="5516"/> in hand, you can use <Skill id="5697"/> through his hitbox to get as many hits as possible.

You can double attune <Skill id="5495" text="false"/>/<Skill id="5495" text="false"/> 2-3 second before the orb phase ends to restart the fight with <Trait id="2131"/> up.

Keep in mind that in the long break phases especially with double cc <Skill id="40183"/> is pretty strong.

**Record**  
The only difference to the normal run is that you want your dps to be good enough to prevent the charge in p1. Preventing the first bubble in p2 and preventing the port in p3. But with the last weaver nerfs all those marks are now very hard to hit.
</Tab>

<Tab specialization="druid">
Use <Skill id="43636"/> from your Rock Gazelle for the first defiance bar and <Skill id="31639"/> from your Electric Wyvern pet for the second defiance bar. Use consumables if your team is short of CC.
</Tab>    
</Tabs>
