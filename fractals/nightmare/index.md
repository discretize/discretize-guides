---
title: 'Nightmare'
date: '2020-03-15'
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

## MAMA <Label>5,200,519 HP</Label>
|  |  |
| -- | -- |
| Encounter duration | 53s |
| Sigils | <Item name="impact"/> <Item name="Force"/> |
| Food | <Item id="43360"/> <Item name="powerfulpotionofslayingscarletsarmies"/>|
| CC-bar MAMA | 1800 |
| CC-bar adds | 800 |

Stack <Boon name="might"/>, <Boon name="Quickness"/> and <Boon name="Alacrity"/> before jumping down. In organized teams use a <Item name="watchworkportaldevice"/> to teleport from the mistlcok to siax.

The duration of the encounter heavily relies on how quickly your party can break the defiance bars throughout the fight, in addition to the amount of damage your party can generate in each phase. This is an average clear time and can be reached by organized teams as well as pick up groups. The class outlines below will be suitable for faster and slower kills as well.

MAMA will arise, after being invulnerable for a few seconds its first attack will be a _spinning <Control name="knockback"/>_. This one should be interrupted by CCing the boss fast enough. The consecutive spin attacks should be taken care of by the <Specialization name="Firebrand"/> as long as there is not to much AoE, that potentially removes <Boon name="Aegis"/> is around. This spin attack always hits on the _second_ spin animation.

Apart from that, turn away from your party members shortly before the _Vomit Toxin_ hits (orange cone), otherwise you will 'infect' party members in front of you with it.

Every 25%, MAMA gets <Effect name="invulnerability"/> and an _Assault Knight_ (similar to the knights before) will spawn. Quickly break their defiance bar and burst them down as MAMA will continue it's attacks.

When MAMA reaches 33%, it conjures a large _Nightmare Miasma_ field around it which deals enormous damage. It will also become mobile, start jumping to players, offloading shockwaves which <Control name="knockdown"/> and attacking with <Control name="stun"/> cones. It is especially important to immediately kill the last _Assault Knight_ at 25% health.

Fast crowd control and animation knowledge are the keys to this fight.

<Tabs>

<Tab specialization="Firebrand">
### **General**
- Use <Skill name="banesignet"/> at 100% and 50% and 25%.
- Open <Skill name="tomeofjustice"/> and use 3rd skill to cc adds.
- Use <Skill name="restoringreprieve"/> to give aegis for spins.

### **Precast**
- Use <Skill name="Hallowed ground"/> to give a fire field and <Boon name="Retaliation"/>.
- Use <Skill name="Feelmywrath"/> and <Skill name="potenthaste"/> to give some <Boon name="Quickness"/>.
- Open  <Skill name="tomeofjustice"/> and cast skill 5 (Epilogue).
- Use <Skill name="banesignet"/> before taking the mistlock.
- Take the mistlock.
- You can also precast <Skill name="tomeofjustice"/> skill 4 and 5 just before starting the boss to max out burst.

</Tab>

<Tab specialization="Soulbeast">
Dont play <Specialization name="Soulbeast"/> on this boss. Its garbage. 

---

**Precast**  
- Remember to share <Skill name="Moastance"/> and blast with <Skill name="Callofthewild"/>.
- Before you cast <Skill id="5531"/> and <Skill name="Barrage"/> on MAMA: share <Skill name="One wolf pack"/> with <Trait name="leaderofthepack"/> and then swap back to <Trait name="oppressivesuperiority"/>. 

**Opening**

You wanna do a modified Greatsword rotation: 
- <Skill name="Maul"/> and <Skill name="Sicem"/> during the cast
- <Skill name="Worldly impact"/>
- <Skill name="Path of scars"/>
- <Skill name="Whirling defense"/>
- if it is not phased yet you should ragequit.

**1st Add**
- Help CCing with <Skill id="45743"/> 
- autoattack the add to death with your sword.

**2nd phase**

When you go back back to MAMA swap to GS and use:
- <Skill name="Maul"/>
- <Skill name="hiltbash"/>
- <Skill name="Maul"/>
- <Skill id="41524"/> (dont use <Skill name="Sicem"/> here)

**2nd Add**
- Help CCing with <Skill id="45743"/> 
- Use a mix of <Skill name="Maul"/> and autoattacks to kill it.

**3rd phase**

In phase 3 you do same rotation as in p1 (although you can do the full gs rotation if you have hilt bash off cd).  
MAMA should phase while you're casting your <Skill name="Whirling defense"/>, then do <Skill name="Monarchs Leap"/> for free evade away from the poison field and to get to the add faster.

**3rd Add**  
- Swap to GS as soon as possible.
- Do the same thing as before. Save your <Skill id="45743"/>.

**4th phase**
- Help with cc by doing <Skill name="Hilt bash"/> and <Skill id="45743"/> 
- Normal GS rotation.

</Tab>

<Tab specialization="Weaver">
### **Precast**
- Start on sword/Dagger and <Skill id="5506"/> and <Skill id="5635"/>
- Start on <Skill id="5495"/>/<Skill id="5492"/> and use <Skill id="5691"/> to provide a fire field and blast it with <Skill id="40709"/>. 
- Swap to <Skill id="5492"/>/<Skill id="5495"/> and then use <Skill id="5690"/>, <Skill id="21656"/> and <Skill id="5522"/> to blast your fire field..
- Use <Skill id="5506"/> and <Skill id="5635"/> and swap back to <Skill id="5734"/> and<Skill id="5539"/>
- Use <Skill id="44612"/> instead of <Skill id="40183"/> for faster groups.
- Swap to <Trait id="294"/> instead of <Trait id="1510"/> for self sufficient might. Recommended in Pugs every time.
- Swap to staff and <Skill id="5494"/>/<Skill id="5492"/> and then use <Skill id="5516"/>. 
- Take the mistlock.
- Go to the boss using <Skill id="5697"/> on your <Skill id="5516"/> and then drop it. Use <Skill id="5501"/> on your staff . Then equip sword/dagger, swap to <Skill id="5494"/>/<Skill id="5494"/> and start the boss!

### **100%**
- Cast <Skill id="5737"/> just before boss becomes vulnerable.
- <Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/> -> <Skill id="44612"/> -><Skill id="5557"/> -> <Skill id="44451"/> -> <Skill id="5691"/>.
- If the CC Bar is not broken when you use <Skill id="44612"/> then do <Skill id="5691"/> -> <Skill id="44451"/> -><Skill id="5557"/> so that you might get <Skill id="5557"/> in the breakbar.
- Use <Skill id="5539"/> as soon as MAMA is broken.

### **Knight**
- Use <Skill id="44998"/>  and auto attack on <Skill id="5494"/>/<Skill id="5492"/>.
- Throw your <Skill id="5516"/> where the 2nd knight spawns.
- At 25% use <Skill id="5697"/> towards the boss through the knight and swap to <Skill id="5494"/>/<Skill id="5494"/>.

### **75%**
- Use <Skill id="5531"/> at the middle even if MAMA is not there because it will port there anyway and drop your <Skill id="5516"/>.
- <Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/> -> <Skill id="5539"/> -><Skill id="44612"/> -><Skill id="5557"/> -> <Skill id="44451"/> -> <Skill id="5691"/>.
- Swap directly to <Skill id="5494"/>/<Skill id="5494"/> using <Skill id="44612"/> buff and continue to auto attack till MAMA phases again.

### **Knight**
- Use <Skill id="44998"/>  and pick up <Skill id="5516"/>. 
- Use <Skill id="5517"/> and auto attack on <Skill id="5494"/>/<Skill id="5494"/> till the knight is about to die.
- When the knight is about to die use <Skill id="5697"/> towards MAMA.

### **50%**
- Use <Skill id="5531"/>  and drop your <Skill id="5516"/>. Then use <Skill id="5687"/> to CC.
- <Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/> -> <Skill id="5539"/> -><Skill id="44612"/> -><Skill id="5557"/> -> <Skill id="44451"/> -> <Skill id="5691"/>.
- Swap directly to <Skill id="5494"/>/<Skill id="5494"/> using <Skill id="44612"/> buff and continue to auto attack till MAMA phases again.

### **Knight**
- Use <Skill id="44998"/>  and auto attack on <Skill id="5494"/>/<Skill id="5494"/> till the knight is about to die.

### **25%**
- Use <Skill id="5737"/>  it before MAMA jumps in the air after that dodge INTO her, stand behind her to evade the two spins of her spinspin-slam attack and start your burst; this should not be necessary if the cc is good
- <Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/> -> <Skill id="5539"/> -><Skill id="44612"/> -><Skill id="5691"/> -> <Skill id="44451"/> -><Skill id="5557"/>.
- Swap directly to <Skill id="5494"/>/<Skill id="5494"/> using <Skill id="44612"/> buff and continue to auto attack till MAMA phases again.


</Tab>

<Tab specialization="Dragonhunter">
**General**
- Do not use traps on the adds
- Strategically cast your <Skill name="banesignet"/> 
- Start on Scepter/Sword
- Use <Skill name="binding blade"/> inside MAMAs hitbox, when the small adds are coming close
- Check with your team if you are using <Skill name="Feelmywrath"/>

**Precast**

- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the first add and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- (Use <Skill name="Feelmywrath"/> - depends on your precast)
- Take the mistlock.
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

<Tab specialization="firebrand">
Use <Skill name="Binding Blade"/> and <Skill name="tomeofjustice"/> to pull adds.

Use tome of courage skill 4 to give resistance.
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

## Siax the Corrupted <Label>6,138,797 HP</Label>
|  |  |
| -- | -- |
| Encounter duration | 40s |
| Sigils | <Item name="impact"/> <Item name="serpentslaying"/> |
| Food | <Item id="43360"/> <Item name="powerfulpotionofslayingscarletsarmies"/>|
| CC | 2000 |


Stack <Boon name="might"/>, <Boon name="Quickness"/> and <Boon name="Alacrity"/> before approaching the red orb and starting the fight. In organized teams use a <Item name="watchworkportaldevice"/> to teleport from the mistlcok to siax.

The duration of the encounter heavily relies on how much damage your group can generate in each phase and how quickly you can finish the adds. This is a rather fast clear time and can be reached by organized teams. Pick up groups might have a hard time reaching this duration, however the class-outlines below are still suitable for slower kills.

During the fight, break his defiance bar (2000 CC damage) as fast as possible to interrupt his _Caustic Explosion_ skill. Siax will wipe your party if you fail to interrupt it with enough crowd control. Pay attention to his bouncing orb barrages, the _Vomit Toxin_ and the exploding _Volatile Hallucinations_ (below 75% health). Do not stand in the red PBAoE when the inner circle reaches the outer to avoid spawning a _Nightmare Hallucination_. Watch your buffs: the <Specialization name="Firebrand"/> should give you <Boon name="Aegis"/>, which blocks this attack and requires no further action from your side.

When Siax reaches 66% health, he gains <Effect name="invulnerability"/> and four _Echoes of the Unclean_ will spawn in the North, East, South and West which need to be killed quickly to interrupt his _Caustic Explosions_. The same occurs at 33%, though the adds will have their spawning positions shifted clockwise.

Assign players to each add before the fight starts by setting waypoints. In PuGs the <Specialization name="firebrand"/> and <Specialization name="renegade"/> will usually focus on one mob together due to their lower DPS.

<Image src="./images/siax.jpg" caption="Siax the Corrupted"/>

<Tabs>

<Tab specialization="Firebrand">
Ideally you should be precasting quickness with <Skill name="moastance"/> from <Specialization name="soulbeast"/> and play <Specialization name="dragonhunter"/> with  <Skill name="feelmywrath"/> instead of  <Skill name="dragonsmaw"/>.
**Precast**
- Use <Skill name="Hallowed ground"/> to give a fire field and retal.
- Use <Skill name="Feelmywrath"/> and <Skill name="potenthaste"/> to give some quickness.
- Open  <Skill name="tomeofjustice"/> and cast skill 5(Epilogue).
- Use <Skill name="banesignet"/> before taking the mistlock.
- Take the mistlock.
- You can also precast <Skill name="tomeofjustice"/> skill 4 and 5 just before starting the boss to max out burst.
- 
**General**
- Use <Skill name="banesignet"/> for cc.
- Help killing champs at split with scepter if u kills yours early.
- Give aegis with <Skill name="restoringreprieve"/> for red AoE.
- Use your <Skill name="Binding Blade"/> inside Siax' hitbox to get 5 additional hits. This is the reson why <Specialization name="Guardian"/> is very strong at this boss. Do not miss this.
- Save some <Skill id="9168"/> for a quicker add kill

</Tab>

<Tab specialization="Soulbeast">
### **General**
- You can take <Skill name="Bearstance"/> for condi cleanse instead of <Skill name="Wehealasone"/>.
- In organized groups its worth it to take <Skill name="Frosttrap"/> over <Skill name="Signetofthewild"/>.
- In organized groups you can take longbow and use <Trait name="Leaderofthepack"/>

---

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
- Use <Skill id="12622"/> to get to the add quickly. 
- Kill it with  <Skill name="Path of scars"/> and <Skill name="Whirling defense"/>. If your group sucks, you can save your important dps skills and kill the mob with a mix of AA and F1/F2s. The weaver should help you anyway.

**Phase 2**  
- Use <Skill name="onewolfpack"/> in the middle. 
- AA as as all your skills are on CD.

**2nd Add**  
- Use longbow here. <Skill name="pointblankshot"/> and <Skill name="rapidfire"/> 
- The remaining damage should be dealt by the <Specialization name="Dragonhunter"/> with a <Skill name="Swordofjustice"/>.
- If you are using GS do GS2, 5, 2, F1, F2 to kill the add.

**Phase 3**

Longbow:
- <Skill name="Barrage"/> on Siax
- <Skill name="Frost trap"/>
- <Skill name="Path of scars"/> and <Skill name="Whirling defense"/>

Greatsword:
- <Skill name="Worldlyimpact"/> 
- <Skill name="Path of scars"/> and <Skill name="Whirling defense"/>
</Tab>

<Tab specialization="weaver">
### **Precast**
- Start on sword/Dagger and <Skill id="5506"/> and <Skill id="5635"/>
- Start on <Skill id="5495"/>/<Skill id="5492"/> and use <Skill id="5691"/> to provide a fire field and blast it with <Skill id="40709"/>. 
- Swap to <Skill id="5492"/>/<Skill id="5495"/> and then use <Skill id="5690"/>, <Skill id="21656"/> and <Skill id="5522"/> to blast your fire field..
- Use <Skill id="5506"/> and <Skill id="5635"/> and swap back to <Skill id="5734"/> and<Skill id="5539"/>

- Swap to staff and <Skill id="5494"/>/<Skill id="5492"/> and then use <Skill id="5516"/>. 
- Take the mistlock.
- Go to the middle using <Skill id="5697"/>, use <Skill id="5531"/> on your <Skill id="5516"/> and then drop it. Use <Skill id="5501"/> on your staff . Then equip sword/dagger, swap to <Skill id="5494"/>/<Skill id="5494"/> and start the boss!

### **General**
- For slower groups you will use <Skill id="5737"/> at 100% and 33%.
- For faster groups use <Skill id="5737"/> at 66%.

### **100%**
- Use <Skill id="5737"/> (assuming slower group) as soon as the boss starts.
- <Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/> -> <Skill id="5687"/> -> <Skill id="5539"/> -><Skill id="40183"/> -> <Skill id="44451"/> -> <Skill id="45313"/> -><Skill id="5557"/>.
- Dont use your second <Skill id="45313"/> as you need it for the echo.


### **Echo**
- Cast <Skill id="45313"/> and swap to <Skill id="5494"/>/<Skill id="5492"/>
- Cast <Skill id="5516"/> where the second echo spawns, use <Skill id="5517"/> and the go behind the echo and use <Skill id="5697"/> towards the middle while swapping to <Skill id="5494"/>/<Skill id="5494"/> at the same time.

### **66%**
- Cast <Skill id="5531"/> and <Skill id="5737"/>(If you did not use it at 100%) just before siax gets vulnerable.   
- <Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/>  -> <Skill id="5539"/> -><Skill id="40183"/> -> <Skill id="44451"/> -> <Skill id="45313"/> -><Skill id="5557"/>.
- Continue auto attack chain till siax phases(or repeat the rotation if the dps is super low).
### **Echo**
- Same as previous echo.
### **33%**
- Cast <Skill id="5531"/> and <Skill id="5737"/>(If you used it at 100%) just before siax gets vulnerable.   
- <Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/>  -> <Skill id="5539"/> -><Skill id="40183"/> -> <Skill id="44451"/> -> <Skill id="45313"/> -><Skill id="5557"/>.

### **Tryhard/Coordinated groups**
- Run <Skill id="5624"/> instead of <Skill id="5539"/> with <Trait id="328"/> traiit. Precast your first <Skill id="5624"/> before taking mistlock.
- Use <Skill id="5737"/> at 66%.

</Tab>

<Tab specialization="Dragonhunter">
**tl;dr**
- Use your <Skill name="Binding Blade"/> inside Siax' hitbox to get 5 additional hits. This is the reson why <Specialization name="guardian"/> is very strong at this boss. Do not miss this.
- Save some <Skill id="9168"/> for a quicker add kill. 
- It is benefical to take a sword here to quickly blink to the add.
- Use <Skill name="Wings of resolve"/> to navigate around and keep your HP up.
- Use <Skill name="Bane Signet"/> to help with CC and buff your party.
- Use <Skill name="shieldofwrath"/> and <Skill name="Shieldofcourage"/> to block the expanding AoEs.
- Check with your team if you take <Skill name="Feelmywrath"/>

---

**Precast**

- Precast your Traps (<Skill id="30364"/> and <Skill id="30273"/>) on the boss and force your team to `/gg`.
- Use <Skill name="Empower"/> to help with might. Blast the fire field with <Skill name="Holy Strike"/> and <Skill name="Mighty blow"/>.
- Take the mistlock.
- You can precast <Skill id="29789"/> (LB4), <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss if you are using a portal.

**100%-66%**

Your gameplay is heavily influenced by the dps your team can pull. If your team has very high dps (phases Siax in >5s) you wanna precast <Skill name="Bane Signet"/> and fire everything you have as soon as you are getting in combat.  
No matter what group you are running with, start on scepter/sword! If you are running in a PuG or just clear it daily, it is benefical to delay your traps slightly, to fit more of the hits into the cc bar. In a fast team save <Skill name="bindingblade"/> for the 2nd phase when the adds spawn, if not use it. Just make sure to press it when the adds are in range for big dps.

**1st Add**

- Use <Skill name="spearofjustice"/> on your add for the modifier from <Trait name="biggamehunter"/>. 
- <Skill name="Whirling wrath"/> and a couple AA to kill it.
- Use <Skill name="wingsofresolve"/>, <Skill name="Symbol of blades"/> and <Skill name="Leapoffaith"/> for movement.

**66%-33%**

Nothing extraordinary, all information from 100-66 and tl;dr are still valid. Try to end on scepter/sword.

**2nd Add**

- Use <Skill name="spearofjustice"/> on your add for the modifier from <Trait name="biggamehunter"/>. 
- Kill it with a symbol and AAs.
- In fast runs you might wanna save a <Skill name="Swordofjustice"/>.

**33%-0%**

Nothing extraordinary, all information from 100-66 and tl;dr are still valid. Try to end on scepter/sword.

</Tab>  
</Tabs>

---

## Ensolyss of the Endless Torment <Label>14,059,890 HP</Label>
|  |  |
| -- | -- |
| Encounter duration | 1:55min |
| Sigils | <Item name="impact"/> <Item name="serpentslaying"/> |
| Food | <Item id="41569"/> <Item name="powerfulpotionofslayingscarletsarmies"/>|
| CC | 2000 |

<Grid>
<GridItem>
Walk through the teleporter and trigger Ensolyss once after defeating Siax to gain the new checkpoint and use `/gg` to reset all cooldowns. Stack <Boon name="might"/>, <Boon name="Quickness"/> and <Boon name="Alacrity"/> before starting the fight. Good teams will use a <Item id="78978"/> to teleport to the boss. When you start the fight don't stand in the center area of the platform or you will receive a <Control name="knockback"/>. Right after he looses his <Effect name="invulnerability"/> there is a CC bar. This bar is only breakable for approximately one second. Time your CC wise. 

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

<Tab specialization="Firebrand">
### **Precast**
- Use <Skill name="Hallowed ground"/> to give a fire field and retal.
- Use <Skill name="Feelmywrath"/> and <Skill name="potenthaste"/> to give some quickness.
- Open  <Skill name="tomeofjustice"/> and cast skill 5 (Epilogue).
- Use <Skill name="banesignet"/> before taking the mistlock.
- Take the mistlock.
- You can precast  <Skill id="9097"/> (Sw2) and <Skill id="9090"/> (Sc2) on the boss. 
- You can also precast <Skill name="tomeofjustice"/> skill 4 and 5 just before starting the boss to max out burst.
### **100%**
- Use <Skill name="tomeofjustice"/> skill 4 and 5 when the boss is invulnerable.
- Use <Skill name="banesignet"/> as soon as boss is going to become vulnerable
- Use <Skill name="restoringreprieve"/> to give aegis for first slam so that u can continue to dps while jumping.
### **Capture Phase**
- Use <Skill name="restoringreprieve"/> and <Skill name="tomeofresolve"/> to heal <Skill name="frostspirit"/>.
### **66%**
- Use <Skill name="tomeofjustice"/> skill 4 to put a fire field before the boss comes back so that it can be blasted for <Boon name="Might"/>.
- Give <Boon name="aegis"/> with <Skill name="restoringreprieve"/> for red AoE attack.
### **33%**
- If your group has high dps then you can burst the boss while its in the middle. This is done by delaying the cc long enough (till the boss is ~28%) and then using <Skill name="banesignet"/> to break the bar. This is only worth if you have high DPS.
### **General**
- Use <Skill name="banesignet"/> on all CCs.
- Give <Boon name="aegis"/> for slams.
### **Tryhard**
- If you have an organised group with a <Specialization name="Soulbeast"/> then you have the option to play <Specialization name="Dragonhunter"/>.
- Precast all your <Boon name="Quickness"/> with <Skill name="moastance"/> from <Specialization name="soulbeast"/> at the mistlock and change to <Specialization name="dragonhunter"/>
- <Specialization name="soulbeast"/> takes <Skill name="moastance"/> . and uses it at the start of each phase. That should give you just enough <Boon name="Quickness"/> for each phase which is enough for high dps parties. 
</Tab>

<Tab specialization="Soulbeast">
In no <Specialization name="Firebrand"/> comp you wanna play <Skill name="Moastance"/> over <Skill name="Signet of the wild"/>. Use <Skill name="Moastance"/> at the beginning of each phase. Regardless what group you are playing with, you should be playing <Trait name="Leaderofthepack"/>. Longbow is superior to greatsword.

**Opening**  
- Right after Ensolyss spawns: <Skill id="5531"/> and <Skill name="Barrage"/>
- <Skill id="45743"/>, <Skill name="Pointblankshot"/> for insta CC
- <Skill name="onewolfpack"/>, <Skill name="sicem"/>
- <Skill name="rapidfire"/>
- <Skill name="worldlyimpact"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/>
- Pick up <Skill name="conjurelightninghammer"/> and use <Skill id="5725"/>
- AA with <Skill name="conjurelightninghammer"/> until its phased or your <Skill name="pathofscars"/> is back up

**Orb phases**

Use <Skill name="We heal as one"/> to keep up <Boon name="alacrity"/>. 

**66% and 33%**  
- <Skill name="onewolfpack"/>
- <Skill id="5531"/> if available and <Skill name="Barrage"/>
- <Skill name="sicem"/>
- <Skill id="45743"/> and <Skill name="pointblankshot"/>
- <Skill name="Rapidfire"/>
- <Skill name="worldlyimpact"/>
- <Skill name="pathofscars"/> and <Skill name="Whirlingdefense"/>
- Pick up <Skill name="conjurelightninghammer"/> and use <Skill id="5725"/>
- AA with <Skill name="conjurelightninghammer"/> until its phased or your <Skill name="pathofscars"/> is back up

</Tab>

<Tab specialization="weaver">
### **Precast**
- Start on sword/Dagger and <Skill id="5506"/> and <Skill id="5635"/>
- Start on <Skill id="5495"/>/<Skill id="5492"/> and use <Skill id="5691"/> to provide a fire field and blast it with <Skill id="40709"/>. 
- Swap to <Skill id="5492"/>/<Skill id="5495"/> and then use <Skill id="5690"/>, <Skill id="21656"/> and <Skill id="5522"/> to blast your fire field..
- Use <Skill id="5506"/> and <Skill id="5635"/> and swap back to <Skill id="5734"/> and<Skill id="5539"/>

- Swap to staff and <Skill id="5494"/>/<Skill id="5492"/> and then use <Skill id="5516"/>. 
- Take the mistlock.
- Go to the middle using <Skill id="5697"/>, use <Skill id="5531"/> on your <Skill id="5516"/> and then drop it. Use <Skill id="5501"/> on your staff . Then equip sword/dagger, swap to <Skill id="5494"/>/<Skill id="5494"/> and start the boss. Its better to get seomeone else to start the boss for you since u might get knocked in the middle.
### **100%**
- <Skill id="5737"/> -> <Skill id="5687"/> -><Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/> ->  <Skill id="5539"/> -><Skill id="40183"/> -> <Skill id="44451"/> -> <Skill id="45313"/> -><Skill id="5557"/>.
- Compplete AA chains and repeat burst till the boss phases.

### **Capture Phase**
-Just don't die.

### **66%**
- Before the boss become vulnerable, cast <Skill id="5691"/> and <Skill id="21656"/> so that your party gets some might.
- <Skill id="5737"/> -> <Skill id="5687"/> -><Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/> -> Complete auto attack chain on <Skill id="5492"/>/<Skill id="5494"/> ->  <Skill id="5539"/> -><Skill id="40183"/> -> <Skill id="5516"/>(Where you will go in the capture phase) -> <Skill id="5517"/> -> <Skill id="5531"/> ->  <Skill id="44451"/> -> <Skill id="45313"/> -><Skill id="5557"/>.
- Complete auto attack chains and get as much damage as you can in the exposed duration.
### **33%**
- Cast <Skill id="5531"/> on the <Skill id="5516"/> and drop it.
- <Skill id="5737"/> -> <Skill id="5687"/> -><Skill id="43803"/> -> <Skill id="45313"/> -> <Skill id="5529"/> -> <Skill id="43074"/> ->  <Skill id="5539"/> -><Skill id="40183"/> -> <Skill id="44451"/> -> <Skill id="45313"/> -><Skill id="5557"/>.
- Complete auto attack chains and get as much damage as you can in the exposed duration.

</Tab>

</Tabs>
