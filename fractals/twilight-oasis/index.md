### Start
<Grid>
<Column>
Use <Effect name="stealth"/> to skip past the initial Sunspears (as well as any further groups of Sunspears) and head for the first of the Sand Binders.
</Column>

<Column>
<Tips>
    <Tip specialization="mesmer">You can give easy party <Effect name="stealth"/> with <Skill id="10245"/> and <Trait id="674"/> at the cost of a elite skill slot.</Tip>    
    <Tip specialization="thief">Use the smoke field from <Skill id="13113"/> or <Skill id="14184"/> or simply cast <Skill id="13117"/> to stack <Effect name="stealth"/>.</Tip>
    <Tip specialization="ranger">Use <Skill id="31568"/> from your Smokescale pet to stack <Effect name="stealth"/>.</Tip>
</Tips>
</Column>
</Grid>


## <Boss/> First Sandbinder
<Grid>
<Column>
Treat each Sandbinder like any immobile boss and attack accordingly. Keep in mind that <Control name="pull"/> abilities will cancel any attack it is currently executing.

<Boon name="aegis"/> is not really helpful here as the *Tornadoes* quickly remove it.
</Column>

<Column>
<Tips>
    <Tip specialization="mesmer">Use <Skill id="10363"/> to cancel the Sanderbiner's attacks.</Tip>
    <Tip specialization="ranger">Run an offhand axe for the <Control name="pull"/> from <Skill id="12638"/>.</Tip>
</Tips>
</Column>
</Grid>

---

## <Boss/> Priestess Amala (Basic)
Next up you will encounter Priestess Amala for the first time, bring her to 75% health and she wipes your party to praise Joko.

She uses the *Scythe Slash* attack (causes <Control name="knockback"/>) and a basic version of her 9-part attack chain applying <Condition name="bleeding"/> with each AoE.

---

## "Storm the Rooftops!"
Now that you're awakened, you gain access to a new special action skill which launches you high into the air and breaks <Control name="stun"/>. It doesn't have a cooldown out of combat so do not get infight during skips if possible.

Jump up to the roof on the right-hand side and kill the three Sandbinders on the roofs. The first two are copies of the Sandbinder you fought at the beginning, the third one also uses Dwayna's *Lightning Storm* (strafe sideways from allies to avoid it).

You can assign one player to trigger the checkpoint before the second Sandbinder using [this route](https://gfycat.com/ShrillVictoriousAbalone), `/gg` after the first one and resurrect to reset cooldowns. It is also possible to skip the tornado between the second and third Sandbinder using [this portal skip](https://gfycat.com/ShrillVictoriousAbalone).

Use `/gg` after killing all three Sandbinders to resurrect at end area. Clear the mobs there and Priestess AMal will spawn. 

---

## <Boss red/> Priestess Amala
Stack <Boon name="might"/> and be ready to dodge the initial <Control name="knockback"/> after activating the encounter.

### Permanent Mechanics
| | |
| -- | -- |
| **Breakbars** | A breakbar will occur at 85, 65, 45, 25 and 5% health. Amala will cancel any ability and teleport to the middle, break her bar or she deals high damage to the team and recovers health. |
| **Scythe Slash** | A small AoE centered around Amala that will <Control name="knockback"/> players hit by it. |
| **Scythe Combo** (below 85% health) | A 9-part attack chain dealing AoE in a fixed pattern, depending on the current god incorporation. |
| **Energy Wave** (below 85% health) | This attack is telegraphed by a small AoE on the ground, which then erupts into a large shockwave after 2.5 seconds. This can be avoided by either dodging, blocking or using sak. |

### Lyssa <Label>100%-85%</Label>
First off, figure out which out of all the clones is the real Amala and ping her for the other players.
There are a few tells to help you:

- Amala herself is the only Legendary rank enemy, other clones are above level 80
- She uses *Scythe Slash* when someone is in melee range
- When she uses her *Moa Signet*, the <Skill id="29519"/> icon will appear above her

The player targeted by the *Moa Signet* should use sak the moment it completes to prevent others from being transformed.

When Amala drops below 95% health she will begin teleporting around, making new clones whenever she does so. Using the change target key (usually `TAB`) will automatically target her if she is in your line of sight. Try to step around the purple portals on the ground so you avoid being teleported up in the air.

Break Amala's defiance bar to continue to the next phase.

#### Priestess of Lyssa
Amala turns invulnerable and leaves a *Priestess of Lyssa* behind who uses the same purple portals and Moa signet. Burst her down quickly to avoid taking high enrage damage from her clones. 

### Melandru <Label>85%-65%</Label>
The biggest danger of this phase is the *Earth Elemental*, which has a multitude of control effects it applies in AoEs. While killing it is possible this is hardly an effective option, so you can either get the player it fixates on to run off the party stack, or use blocks and evades as necessary to avoid its attacks. Be aware that its *Boulder Throw* projectile can be reflected.

In this phase, Amala's **Scythe Combo** AoEs apply a small <Control name="knockback"/>, but many of them can be avoided by stacking directly on her. Make sure to dodge the *Eruption* (delayed AoE appearing below random players) and ring-shaped attacks, as they <Control name="knockdown"/> as well.

#### Priestess of Melandru
This priestess will cast a rectangular AoE between herself and Amala, avoid running over them so they don't <Control name="knockback"/> you away from the priestess' alcove. The priestess will also use Avatar of Melandru to gain <Boon name="stability"/> and inflict <Condition name="immobile"/>. Similar to Amala, two smaller *Earth Elementals* will spawn to to protect her.

### Dwayna <Label>65%-45%</Label>
Amala will periodically gain <Boon name="swiftness"/>, <Boon name="aegis"/>, <Boon name="protection"/> and <Boon name="might"/> (10x) throughout this phase, with one application every 10 seconds. Additionally, at this stage of the fight all members of the party are given the Determination buff - should you slay the Priestess of Dwayna, all party members will be revived.

In this phase, Amala's **Scythe Combo** AoEs apply a short <Control name="daze"/> and a stack of <Condition name="bleeding"/>.

There are far more attacks that occur directly on top of Amala in this phase, but there is less incoming CC so they can be healed through in general. The group will still need to spread out during the *Lightning Storm* attack as it cannot be blocked with <Boon name="aegis"/>.

After Amala drops to 60% health, she will start summoning five tornadoes. Much like the ones summoned by the Sandbinders, they will draw your character toward their center and apply damage and <Condition name="blind"/> to those inside of their AoE.

#### Priestess of Dwayna
The Priestess of Dwayna only has one attack which cannot be interrupted: a different iteration of the Lightning Strikes attack. Unlike Amala's, these strikes will land randomly, so the best way to deal with them is to remain near the edge of the alcove where you're less likely to be hit. Also be aware that when engaged the priestess gains <Boon name="retaliation"/>, <Boon name="protection"/> and <Boon name="regeneration"/>.

### Grenth <Label>45%-25%</Label>
Amala will periodically gain <Boon name="swiftness"/> and <Boon name="might"/> (15x) during this phase while dealing <Condition name="poison"/>, <Condition name="torment"/> and <Condition name="chilled"/> with her scythe attack chain.

This is another phase that for the most part can be stacked and healed through, as it has very little CC involved. The biggest danger of this phase however is the *Claim Soul* attack, recognizable by a small orange AoE - it is unblockable and will immediately send you into downed state.

At 40% health, Amala summons an arrangement of *Spectral Walls* that box you into the middle. Touching these walls will <Condition name="fear"/> you away from Amala.

#### Priestess of Grenth
The next priestess applies <Condition name="bleeding"/>, <Condition name="crippled"/>, <Condition name="poison"/>, <Condition name="torment"/> and <Condition name="chilled"/> but shouldn't be a problem to kill.

### Balthazar <Label>25%-5%</Label>
During this phase, Amala will periodically receive <Boon name="protection"/>, <Boon name="swiftness"/> and <Boon name="might"/> (10x).

While for the most part Amala's attacks can be healed through this phase, some of her attacks are devastating as they have large telegraphs like *Meteor Strike* and *Wings of Rage*. As such, try to reposition out of AoEs as necessary.

Do not try to tank her *Fire Arrows* (telegraphed by a circle AoE on top of her with arrows pointing out) as this does extreme damage if you're hit by each subsequent arrow AoE.

#### Priestess of Balthazar
This priestess doesn't do much outside of calling down small meteors which <Control name="stun"/> and apply <Condition name="burning"/> and <Condition name="weakness"/> on impact. Her life is tied to the four *Veteran Sunspear Warriors* that flank her, control those with CC and kill them to eliminate the priestess.

### "Perish With Me Traitors!" <Label>5%-0%</Label>
For the final 5% health, Amala will continue to use all of the attacks from the Balthazar phase with additional small meteors striking the surrounding area. Finish her off to complete the fractal.
