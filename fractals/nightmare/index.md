---
title: 'Nightmare'
date: '2019-10-29'
image: './images/ensolyss_crazy.jpg'
group: 'Challenge Mode'
api: 3177
bosses: 3
difficulties: [{ level: 99, ar: 150 }]
record:
  {
    time: '8:36',
    by: { name: 'Snow Crows/Quantify', tag: 'SC/qT' },
    youtube:
      [
        { id: 'YHmwhZc-sMU', name: 'Roul', specialization: 'Firebrand' },
        { id: 'lZlb1jy_rPg', name: 'Decados', specialization: 'Warrior' },
        { id: 'VZ5xR6WcqSk', name: 'Nukkuu', specialization: 'Weaver' },
        { id: 'gRpvNsOBnCo', name: 'Elu', specialization: 'Soulbeast' },
        { id: '3XIv-XHxDHk', name: 'Deathly', specialization: 'Renegade' },
      ],
  }
cycle: 'Day'
potions: [{ id: 50082 }]
sigils: [{ id: 24615 }, { id: 24868 }, { id: 24658, description: 'after MAMA' }]
consumables: [43360, 8759, 8678, 8764, 8801, 78978, 12486]
---

## Assault Knights <Item id="50082" disableText/><Label>426,071 HP</Label>

Stack <Boon name="might"/> before jumping down. Kill the three _Assault Knights_ (Red, Blue and Green), each of them has the same set of abilities: a PBAoE <Control name="knockdown"/> and an AoE <Control name="pull"/> which covers the entire room except the knight's position, both can be dodged.

Break their defiance bars, kill them to awaken MAMA and use `/gg` to reset your cooldowns.

<Image src="./images/mama.jpg" caption="MAMA: The first boss"/>

## MAMA <Item id="50082" disableText/><Label>5,200,519 HP</Label>

Stack <Boon name="might"/>, <Boon name="Quickness"/> and <Boon name="Alacrity"/> before jumping down. 

MAMA will arise, after being invulnerable for a few seconds its first attack will be a _spinning <Control name="knockback"/>_. This one should be interrupted by CCing the boss fast enough. The consecutive spin attacks should be taken care of by the <Specialization name="Firebrand"/> as long as there is not to much AoE, that potentially removes <Boon name="Aegis"/> is around. This spin attack always hits on the _second_ spin animation.

Apart from that, turn away from your party members shortly before the _Vomit Toxin_ hits (orange cone), otherwise you will 'infect' party members in front of you with it.

Every 25%, MAMA gets <Effect name="invulnerability"/> and an _Assault Knight_ (similar to the knights before) will spawn. Quickly break their defiance bar and burst them down as MAMA will continue it's attacks.

When MAMA reaches 33%, it conjures a large _Nightmare Miasma_ field around it which deals enormous damage. It will also become mobile, start jumping to players, offloading shockwaves which <Control name="knockdown"/> and attacking with <Control name="stun"/> cones. It is especially important to immediately kill the last _Assault Knight_ at 25% health.

Fast crowd control and animation knowledge are the keys to this fight.

<Tabs>
<Tab specialization="Renegade">
WIP
</Tab>

<Tab specialization="Firebrand">
WIP
</Tab>

<Tab specialization="Soulbeast">
Dont play <Specialization name="Soulbeast"/> on this boss. Its garbage. 


**Precast**  
Remember to share <Skill name="Moastance"/> and blast with <Skill name="Callofthewild"/>. Before you cast <Skill id="5531"/> and <Skill name="Barrage"/> you wanna share <Skill name="One wolf pack"/> with <Trait name="leaderofthepack"/> and then swap back to <Trait name="oppressivesuperiority"/>. 

**Opening**  
You wanna do a modified Greatsword rotation: 
- <Skill name="Maul"/> and <Skill name="Sicem"/> during the cast
- <Skill name="Worldly impact"/>
- <Skill name="Path of scars"/>
- <Skill name="Whirling defense"/>
- if it is not phased yet you should ragequit.

**1st Add**  
Help CCing with <Skill id="45743"/> and autoattack the add to death with your sword.

**2nd phase**  
When you go back back to MAMA swap to gs and use:
- <Skill name="Maul"/>
- <Skill name="hiltbash"/>
- <Skill name="Maul"/>
- <Skill id="41524"/> (dont use <Skill name="Sicem"/> here)

**2nd Add**  
Help CCing with <Skill id="45743"/> and use a mix of <Skill name="Maul"/> and autoattacks to kill it.

**3rd phase**  
In phase 3 you do same rotation as in p1 (although you can do the full gs rotation if you have hilt bash off cd).
MAMA should phase while you're casting your <Skill name="Whirling defense"/>, then do <Skill name="Monarchs Leap"/> for free evade away from the poison field and to get to the add faster.

**3rd Add**  
On this add you wanna swap to gs as soon as possible. Do the same thing as before. Save your <Skill id="45743"/>.

**4th phase**  
In this phase you can help with cc by doing <Skill name="Hilt bash"/> and <Skill id="45743"/> otherwise just normal gs rotation.

</Tab>

<Tab specialization="Weaver">
WIP
</Tab>

<Tab specialization="warrior">
**Organized**

You can precast banners with the help of a <Item id="44642"/>. Open the portal on the slope (not at the flat area around the mistlock, but before), hop in, precast the banners and take your portal back. You are now free to run the dps setup for short fights.
<Skills heal="blood reckoning" utility1="outrage" utility2="throw bolas" utility3="Signet of might" elite="headbutt"/>
Remember to swap to <Trait id="2049"/>. 

**General**

Help pre-stacking at Mistlock Singularity with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call to Arms" profession="Warrior"/>. It is highly encouraged to go core warrior for CC. You can stay berserker if you are willing to counter the lack of cc with consumables. 

---

### <Specialization name="Warrior"/> (Standard Axe/Axe Mace/Mace)

Start MAMA on Mace/Mace. Instantly break MAMA's Defiance bar using <Skill id="14402"/>, <Skill name="Tremor" profession="Warrior"/>, <Skill name="Pommel Bash" profession="Warrior"/>, <Skill name="Skull Crack" profession="Warrior"/> (if <Skill id="14502"/> won't break MAMA's Defiance bar use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/> and continue with standard rotation on Axe/Axe.

Fast Hands allows you to quickly adapt to what is currently needed in the encounter and consumables like <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>.

Keep an eye on MAMA's <Condition name="vulnerability"/> stacks and use <Skill name="crushing blow" profession="Warrior"/> if it runs low.
</Tab>

<Tab specialization="Dragonhunter">
**General**

- You can precast traps on the adds and force your team to gg.
- Do not use traps on the adds
- Strategically cast your bane signet 
- Start on Scepter/Sword
</Tab>

</Tabs>

---

<Grid>
<GridItem sm="8">
## First set of altars <Item id="50082" disableText/><Item id="24658" disableText/>
Swap your weopen set to <Item name="Impact"/> and <Item name="Serpentslaying"/>. You need to cap two altars to continue. Pull the two groups of Krait back to the passage and kill all enemies there. Start capping the altars as soon as possible, but keep in mind that standing inside puts <Effect name="agony"/> on yourself. Only enemy Krait counteract the capping here, you can ignore the Hallucinations.    
Learn the *Red Orb* patterns as they can quickly kill you, *Blue Orbs* will heal you for a large amount of health (even with Agony).    
On a side note, more players do not cap an altar faster. More than one person standing inside is redundant.
</GridItem>
<GridItem sm="4">
<Image src="./images/altars.jpg" caption="The altars"/>
</GridItem>
</Grid>

## Second set of altars <Item id="50082" disableText/><Item id="24658" disableText/>

Again, pull all enemies to the center (wait for the <Specialization name="Firebrand"/> to cast <Skill id="9147"/>) and kill them there. The mobs at the left altar (West) can be aggroed with a simple projectile, the mobs on the right side (East) need to be pulled with <Skill id="14381"/> (Longbow), <Skill id="14575"/>, <Skill id="5491"/> (Staff) or by teleporting up and jumping down.

Both side altars can easily be capped by a single person after another player has pulled down the mobs. Please note that you have to wait until the mobs are down before teleporting elsewhere to prevent them from running back.

Contrary to the first set of altars, respawning _Veteran Hallucinations_ counteract capping here. Use <Control name="pull"/> to grab them out of the central altar and always have a positive amount of players inside.

After you capped all three altars, use `/gg` immediately if someone in the party needs it, then you can continue up to the 2nd boss. Before the ramp up, a group of Krait will attack you - simply keep walking to skip them. Use dodges, evades or invulnerables to get through the cascading orbs and disable them by walking through the orb at the top of the ramp.

Usually a single person with high mobility (<Specialization name="Warrior"/>, <Specialization name="Dragonhunter"/>, <Specialization name="Soulbeast"/>, <Specialization name="Weaver"/>) and <Item name="endlesschoyapinatatonic"/> or <Item id="49940"/> skips to Siax while the rest of the party stays dead. Trigger Siax and wait for Siax to appear, then `/gg` aswell.

<Tabs>
<Tab specialization="weaver">
<Skill id="5738"/> is very strong against the groups of Krait.

Use <Skill id="5536"/> to teleport up to the altars.

You can pull both sides with <Skill id="5491"/> (for the right side, jump at the end of your [cast](https://www.youtube.com/watch?v=lNZEM9StauU)).

If the person who pulled your side ported up the other side to fast and the mobs come back use <Skill id="5683"/> and <Skill id="5686"/> to prevent them from reachin the circle before it is tabbed. Make sure you are attuned correctly for this in time.
</Tab>

<Tab specialization="warrior">
Exchange <Skill id="14502"/> for <Skill name="on my mark" profession="Warrior"/> and already swap to your weapon sets with Superior Sigil of Serpent Slaying.

At the first set of altars draw the Elite Nightmare Hypnoss with <Skill name="on my mark" profession="Warrior"/> to the narrow corridor so that the <Specialization name="Firebrand"/> can pull them together with <Skill name="Binding Blade"/> and disable them with <Skill name="Tremor" profession="Warrior"/>. Assist in killing the Elite Nightmare Hypnoss and capturing one of the two altars. 

At the second set of altars, wait for your <Specialization name="Firebrand"/> to pull them together with <Skill name="Binding Blade"/> and disable the Elite Nightmare Hypnoss with <Skill name="Tremor" profession="Warrior"/>. Immediately move close to the altar on the right side and pull the Elite Nightmare Hypnoss occupying the altar to the mid by using <Skill name="on my mark" profession="Warrior"/>. Assist in killing the remaining Elite Nightmare Hypnoss and capture the mid altar respectively.
</Tab>
<Tab specialization="dragonhunter">
Use <Skill name="Binding Blade"/> and <Skill name="Dragonsmaw"/> excessively to pull as many mobs as possible. 

At the second set of altars use your <Skill name="Huntersverdict"/> to pull out the Elite Nightmare Hypnoss occupying the center circle. Make sure, that there are no projectil blocking Skills from enemies present.
</Tab>
</Tabs>

---

## Siax the Corrupted <Item id="50082" disableText/><Item id="24658" disableText/><Label>6,138,797 HP</Label>
Stack <Boon name="might"/>, <Boon name="Quickness"/> and <Boon name="Alacrity"/> before approaching the red orb and starting the fight.

During the fight, break his defiance bar (2000 CC damage) as fast as possible to interrupt his _Caustic Explosion_ skill. Siax will wipe your party if you fail to interrupt it with enough crowd control. Pay attention to his bouncing orb barrages, the _Vomit Toxin_ and the exploding _Volatile Hallucinations_ (below 75% health). Do not stand in the red PBAoE when the inner circle reaches the outer to avoid spawning a _Nightmare Hallucination_. Watch your buffs: the <Specialization name="Firebrand"/> should give you <Boon name="Aegis"/>, which blocks this attack and requires no further action from your side.

When Siax reaches 66% health, he gains <Effect name="invulnerability"/> and four _Echoes of the Unclean_ will spawn in the North, East, South and West which need to be killed quickly to interrupt his _Caustic Explosions_. The same occurs at 33%, though the adds will have their spawning positions shifted clockwise.

Assign players to each add before the fight starts by setting waypoints. The <Specialization name="firebrand"/> and <Specialization name="renegade"/> will usually focus on one mob together due to their lower DPS.

<Image src="./images/siax.jpg" caption="Siax the Corrupted"/>

<Tabs>
<Tab specialization="Renegade">
WIP
</Tab>

<Tab specialization="Firebrand">
WIP
</Tab>

<Tab specialization="Soulbeast">
**General**
- You can take <Skill name="Bearstance"/> for condi cleanse instead of <Skill name="Wehealasone"/>.
- In organized groups its worth it to take <Skill name="Frosttrap"/> over <Skill name="Signetofthewild"/>.
- In organized groups you can take longbow and use <Trait name="Leaderofthepack"/>

**Precast**  
Precast <Skill name="Frosttrap"/> on the boss like a <Specialization name="Dragonhunter"/> in disguise. Remember to share <Skill name="Moastance"/> and blast with <Skill name="Callofthewild"/>. Share <Skill name="One wolf pack"/> and take the mistlock.

**Opening**  
You wanna do following opening: 
- Summon <Skill name="Frostspirit"/> as he triggers
- <Skill name="Frosttrap"/> so you have two of those ticking at the same time.
- <Skill name="Sicem"/> 
- <Skill name="Barrage"/>
- CC: <Skill id="45743"/> and <Skill name="Pointblankshot"/>
- <Skill name="Rapidfire"/>
- You shouldnt use <Skill name="Whirling defense"/> in phase 1.
 
**1st Add**  
Use <Skill id="12622"/> to get to the add quickly. Kill it with  <Skill name="Path of scars"/> and <Skill name="Whirling defense"/>. If your group sucks, you can save your important dps skills and kill the mob with a mix of AA and F1/F2s. The weaver should help you anyway.

**Phase 2**  
Use <Skill name="onewolfpack"/> in the middle. AA as as all your skills are on CD.

**2nd Add**  
Use longbow here. <Skill name="pointblankshot"/> and <Skill name="rapidfire"/> should do the trick. The remaining damage should be dealt by the <Specialization name="Dragonhunter"/> with a <Skill name="Swordofjustice"/>.

If you are using GS do GS2, 5, 2, F1, F2 to kill the add.

**Phase 3**  
Longbow:
- <Skill name="Barrage"/> on Siax
- <Skill name="Frost trap"/>
- <Skill name="Path of scars"/> and <Skill name="Whirling defense"/>

Greatsword:
- <Skill name="Worldlyimpact"/> 
- <Skill name="Path of scars"/> and <Skill name="Whirling defense"/>
</Tab>

<Tab specialization="warrior">
**Organized**

You can precast banners if the bossfight will be below 55 seconds. Open a <Item id="44642"/> at the boss to start the fight faster after precasting. You are now free to run the dps setup for short fights.
<Skills heal="blood reckoning" utility1="outrage" utility2="throw bolas" utility3="Signet of might" elite="headbutt"/>
- Remember to swap to <Trait id="2049"/>. 
- Use <Skill name="Whirling Axe"/> to gain Adrenalin and engage <Skill name="Berserk"/> as soon as possible. 
- Use <Skill name="Headbutt"/> to CC and break the stun with <Skill name="Outrage"/>. Use this combo asap to keep up <Skill name="Berserk"/>. 
- Use <Skill name="Throw Bolas"/> before casting <Skill name="Whirling Axe"/> to maximize dps. 
- Use <Skill name="Blood reckoning"/> on cooldown.
- Use a Rifle to kill your add without loosing time. Use <Skill name="gunflame"/>, <Skill name="volley"/> and a couple autos to get the job done. A greatsword also works out great.

**General**

Help pre-stacking at Mistlock Singularity with <Skill name="Charge" profession="Warrior"/> and <Skill name="Call to Arms" profession="Warrior"/>. 

If additional Defiance bar damage is needed make use of <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>.

Kill your add as fast as possible and return to the boss. You do not wanna miss the time the boss is invulnerable or your dps will suffer. 
</Tab>

<Tab specialization="weaver">
Start the fight with <Skill id="5531"/> followed by the <Skill id="5494" disableText/>/<Skill id="5492" disableText/> opener if you have high damage or the <Skill id="5495" disableText/>/<Skill id="5492" disableText/> opener if you have low damage. You want to start with this while the last Illusions turn hostile.

On the East and South _Echoes of the Unclean_, you can use <Skill id="5697"/> from <Skill id="5516"/> against the wall to deal enormous damage. On the second add spawn you can <Skill id="5697"/> at any location except east.

With normal group damage Siax should turn invulnerable at the end of your first <Skill id="5624"/>. Use <Skill id="5680"/> to reach your add fast. Place a <Skill id="5548"/> and use <Skill id="5697"/> to kill your add fast. If you are having trouble killing the add fast after the <Skill id="5548"/> nerf also hit it with <Skill id="5517"/>. It can be worth it depending on your group to attune to <Skill id="5495" disableText/>/<Skill id="5492" disableText/> while killing the add for additional skills and a faster <Trait id="2131"/>. Alternativle start with <Skill name="Eruption"/>, <Skill name="Lava Font"/>, <Skill id="5517"/> and <Skill id="5697"/> through the mob back to the boss (Only do it if you are sure your <Skill id="5697"/> will kill the mob. It feels really bad to reach the boss with your add surviving with less than 1% life).

Continue with <Skill id="5531"/> on Siax and restart in <Skill id="5492"/>.

If your group damage is too low to pick up your second <Skill id="5516"/> for the second add, place a <Skill id="5548"/> on it, attune to <Skill id="5494" disableText/>/<Skill id="5492" disableText/> and use <Skill id="41125"/> to kill it quickly.

Continue with <Skill id="5494" disableText/>/<Skill id="5492" disableText/> and <Skill id="5737"/> on Siax.

If you play with three weavers split your <Skill id="5737"/> so you have one each phase.

If you want to try hard play air instead of arcane, use <Skill id="21656" /> and pre cast <Skill id="5501"/> before the fight to have it ready fast enough in phase 2 and 3.
</Tab>

<Tab specialization="Dragonhunter">
**General**
- Use your <Skill name="Binding Blade"/> inside Siax' hitbox to get 5 additional hits. This is the reson why dragonhunter is very strong at this boss. Do not miss this.
- Save some <Skill id="9168"/> for a quicker add kill. 
- It is benefical to take a sword here to quickly blink to the add.
- Use <Skill name="Wings of resolve"/> to navigate around and keep your HP up.
- Use <Skill name="Bane Signet"/> to help with CC and buff your party.
</Tab>  
</Tabs>

---

## Ensolyss of the Endless Torment <Item id="50082" disableText/><Item id="24658" disableText/><Label>14,059,890 HP</Label>

<Grid>
<GridItem>
Walk through the teleporter and trigger Ensolyss once after defeating Siax to gain the new checkpoint and use `/gg` to reset all cooldowns. Stack <Boon name="might"/>, <Boon name="Quickness"/> and <Boon name="Alacrity"/> before starting the fight. Go into the arena; when you start the fight don't stand in the center area of the platform on activation or you will receive a <Control name="knockback"/>.

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
<Tab specialization="Renegade">
WIP
</Tab>

<Tab specialization="Firebrand">
WIP
</Tab>

<Tab specialization="Soulbeast">
utilities we heal as one frost spirit signet of the wild/moa stance sicem and one wolf pack
you should run stance share here
weapons sword axe and a longbow
if you have good group and the fb goes dh with fmw you should take moa stance for quickness and use it at the start of every phase. If this is not the case you should use signet of the wild
as he's spawning u wanna do fgs5 and lb 5 then do f2 and lb4 for insta cc owp sicem and lb2 f3 axe 4 5 and if you have a kind weaver who uses lh you should pick it up and use lh 4 after finish axe 5
then do lh autos until you can do axe 4 again
by this time he should be phased
for orbs you can use we heal as one for more alacrity, other than that just dont die
for the start of p2 and p3 you do one wolf pack (fgs 5 atleast 1 of these phases the weaver should give an fgs) lb5 sic'em lb4 f2 to help with cc then lb2 axe 45 take the lh if there is one and use lh4 and autos


</Tab>

<Tab specialization="warrior">

### <Specialization name="Berserker"/> (Standard Axe/Axe Mace/Mace)
There are some interesting weopen choices: if your team manages CC you can take an offhand torch for more dps. 

Remember to swap back to <Trait id="1977"/>. Use Headbutt and <Skill name="Berserk"/> asap to break him before the first dome appears. Spam your <Skill id="30851"/> like usual. It should phase right after your <Skill name="berserk"/> runs out. 

**66% and 33%**

Pick up your banners and swap to your off set. After everyone capped their circle, try to blast a fire field with your banners.

Opening:
- <Skill name="crushing blow" profession="Warrior"/> to stack <Condition name="vulnerability"/>
- <Skill name="Mending"/>
- <Skill name="Tremor"/>
- <Skill name="Headbutt"/>
- <Skill name="Berserk"/>

---

### <Specialization name="Warrior"/> (Standard Axe/Axe Mace/Mace)

Begin the encounter on Axe/Axe with <Skill id="14402"/>, <Skill id="14502"/>, <Skill name="Eviscerate" profession="Warrior"/>, <Skill name="Whirling Axe" profession="Warrior"/>, <Skill name="Dual Strike" profession="Warrior"/>, <Skill name="Throw Axe" profession="Warrior"/>, <Skill name="Cyclone Axe" profession="Warrior"/> and immediately swap to Mace/Mace to break Ensolyss's Defiance bar with <Skill name="Tremor" profession="Warrior"/>, <Skill name="Pommel Bash" profession="Warrior"/> and <Skill name="Skull Crack" profession="Warrior"/>.

Once Ensolyss's
Defiance bar is broken continue with standard rotation on Axe/Axe. At 66% and 33% swap to Mace/Mace and capture one of the five altars.

As soon as Ensolyss returns attack with <Skill name="Mace Smash" profession="Warrior"/>, <Skill name="Mace Bash" profession="Warrior"/> and <Skill name="Pulverize" profession="Warrior"/> until the Defiance bar appears.

Immediately use <Skill name="Tremor" profession="Warrior"/>, <Skill name="Skull Crack" profession="Warrior"/> (if <Skill id="14502"/> won't break Ensolyss's Defiance bar use <Item id="8664"/>, <Item id="8677"/> and <Item id="8749"/>), <Skill id="14502"/> and continue standard rotation until the second Defiance bar appears. Break it with <Skill name="Pommel Bash"/>, <Skill name="Skull Crack" profession="Warrior"/> and <Item id="8664"/>, <Item id="8677"/>, <Item id="8749"/>, <Skill id="14502"/> and resume standard rotation.

Keep an eye on <Condition name="vulnerability"/> stacks and use <Skill name="crushing blow" profession="Warrior"/> if it runs low.
</Tab>

<Tab specialization="weaver">
Start the fight in <Skill id="5495" disableText/>/<Skill id="5492" disableText/> with <Skill id="5531"/> followed <Skill id="5528"/> while Ensolyss spawns, continue with <Skill id="5548"/> and <Skill id="5491"/> until <Skill id="5548"/> is ready again. Know cast your situational opener to hit as much damage as possible in the breakbar.

If your damage is low and he charges cast your second <Skill id="5501"/> in the middle of the platform after dodging his first charge. If all five players stand there he will teleport back into it.

If you have two or more weavers one should take <Skill id="5567"/> and switch weapons with the other weavers.

If you summond you <Skill id="5516"/> in phase one pick it up before the orbs spawn and keep it the whole orb phase.

Start the fight at 66% with the <Skill id="5495" disableText/>/<Skill id="5492" disableText/> opener. Use <Skill id="5531"/> if you have a <Skill id="5516"/> in hand.

Hit the second breakbar with either <Skill id="5733"/> or <Skill id="5721"/>.

After the orb phases, reopen in <Skill id="5495" disableText/>/<Skill id="5492" disableText/> and cast <Skill id="5528"/> about a second before the orb phase ends. Make sure to have your <Skill id="5501"/> either finished before the first <Control name="knockback"/> zone goes off or start it after making sure you won't get hit.

If you are close to either 66% or 33% and have your <Skill id="5516"/> in hand, you can use <Skill id="5697"/> through his hitbox to get as many hits as possible.

You can double attune <Skill id="5495" disableText/>/<Skill id="5495" disableText/> 2-3 second before the orb phase ends to restart the fight with <Trait id="2131"/> up.

Keep in mind that in the long break phases especially with double cc <Skill id="40183"/> is pretty strong.

**Record**  
The only difference to the normal run is that you want your dps to be good enough to prevent the charge in p1. Preventing the first bubble in p2 and preventing the port in p3. But with the last weaver nerfs all those marks are now very hard to hit.
</Tab>

</Tabs>
