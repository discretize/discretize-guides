---
title: Condi Deadeye
rating: Meta
role: Condi Damage
author: MagicBot.1570
profession: Thief
specialization: Deadeye
conditions:
  - name: Vulnerability
    uptime: 20 stacks
  - name: Weakness
  - name: Immobilize
  - name: Poisoned
  - name: Bleeding
  - name: Torment
cmGuide: ''
classification:
  - 3
  - 5
  - 3
  - 2
  - 5
compositions:
  - name: _CRGB
code: '[&DQUsPhwbOh8MAYUAIBcAAD4BAAAvAQAAPRYAAAAAAAAAAAAAAAAAAAAAAAA=]'
date: 2022-03-20T17:41:23.631Z
archive: false
hidden: false
---

<Warning>

This build is strong in full condi groups ([team comps](/guides/effective-comp)). In terms of DPS, it is unlikely to fall behind any other specialization, whether they be running a power or condi build, as it has very high sustained DPS on single targets.

Lastly, a condi build will always have a tendency to interfere with a power composition, as it is not meant to have a higher upfront or burst damage, but both of these builds will do a lot of burst damage as well. It is worth mentioning that _Venom Skills_ are very strong in that regard, and precasting them on the _Mistlock Singularity_ will allow for a very high burst, quite uncommon for condi builds but very valuable.

</Warning>

The **<Specialization text="Condi Deadeye" name="Deadeye"/>** is quite a selfish build, that will not provide your party with any form of support. Instead, the value of this build comes almost entirely from the pure damage that it will bring, which is inflated by the **<Specialization text="Condi Soulbeast" name="Soulbeast"/>**'s <Skill id="40498"/>, on top of Venom Skills which can be precast on the _Mistlock Singularity_, and casted again as soon as your allies have consumed them by attacking the target. Consequently, the **<Specialization text="Condi Deadeye" name="Deadeye"/>** is able to apply a tremendous amount of <Condition name="Poisoned"/> and <Condition name="Bleeding"/> instances, as well as an non-negligible amount of <Condition name="Torment"/>. As such, it is necessary to be running with a <Item id="44944"/> as it will become very valuable in bursting phases. Lastly, <Skill id="13132"/> can bring up to 750 Defiance Bar damage, if used at the proper moment, meaning if all instances of this ability are consumed when the boss is vulnerable to this type of damage (up to five stacks, one per player).

This build possesses a decent amount of self-sustain, due to <Trait id="2111"/>, but it will suffer greatly from a <Boon name="Quickness"/> deficit. However, it won't suffer too much from a lack of <Boon name="Alacrity"/> due to the nature of _Initiative_.

Overall, this build is an excellent pick if taken as an alt class: it is meant for players who enjoy high-risk, high-reward rotations. Played correctly, it is excellent in PuGs on single-target bosses such as the ones from Challenge Mode Fractals, most notably Sorrowful Spellcaster (Light Ai) and Ensolyss, or any boss with little to no phases, as well as multiple add phases, such as the ones from Shattered Observatory.
A playlist of videos showcasing the **<Specialization text="Condi Deadeye" name="Deadeye"/>** and the **<Specialization text="Condi Daredevil" name="Daredevil"/>** can be found on [Magic's channel](https://www.youtube.com/playlist?list=PLC8zIP7qMiNPQAHWjt_V_B_EtGaJaGJaM). It is currently incomplete, but you will find benchmarks, CM boss kills, and some T4 gameplay in organized groups.

We do not recommend running these builds in Shattered Observatory for new players or beginners, as positioning is most important there, and jumping <Skill name="shadowstrike"/> becomes an issue due to Cosmic Energy (low gravity). Extensive details for the build can be found at the bottom of the page.

<Divider text="Equipment"/>

<CharacterWithAr>  
<Character title="162 Agony Resistance" gear={{
    "profession": "Thief",
    "weight": "Medium",
    "gear": [
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper",
      "Viper"
    ],
  "attributes": {
    "Health": 11645,
    "Armor": 2361,
    "Power": 2923,
    "Precision": 1876,
    "Toughness": 1243,
    "Vitality": 1000,
    "Ferocity": 150,
    "Condition Damage": 2525,
    "Expertise": 853,
    "Concentration": 423,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.7686666666666666,
    "Boon Duration": 0.282,
    "Critical Chance": 0.6671428571428571,
    "Critical Damage": 1.6,
    "Poison Duration": 0.33,
    "Effective Power": 9646.035455995714,
    "Power DPS": 6277.165930162787,
    "Bleeding Damage": 365.97656249999994,
    "Bleeding Stacks": 33.60466666666667,
    "Bleeding DPS": 12298.520390624999,
    "Burning Damage": 881.5078124999999,
    "Burning Stacks": 0.8843333333333333,
    "Burning DPS": 779.5467421874998,
    "Confusion Damage": 345.97968749999995,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 415.20937499999997,
    "Poison Stacks": 29.2,
    "Poison DPS": 12124.113749999999,
    "Torment Damage": 437.14687499999997,
    "Torment Stacks": 16.802333333333333,
    "Torment DPS": 7345.087509374999,
    "Damage": 38824.43432235029,
    "Effective Health": 60793466.00331675,
    "Survivability": 30906.693443475724,
    "Effective Healing": 390,
    "Healing": 390
  },
    "runeId": 24848,
    "runeName": "Nightmare",
    "infusions": [
      37130, 37130, 37130, 37130, 37130, 37130, 37130,
      37130, 37130, 37130, 37130, 37130, 37130, 37130,
      37130, 37130, 37130, 37130
    ],
    "weapons": {
      "weapon1MainType": "Pistol",
      "weapon1MainSigil1": "bursting",
      "weapon1OffType": "Dagger",
      "weapon1OffSigil": "earth"
    },
    "consumables": {
      "foodId": 91878,
      "utility": "tuning-icicle",
      "infusion": "Malign +9 Agony Infusion"
    },
    "skills": {
      "heal": "Hide in Shadows",
      "utility1": "Mercy",
      "utility2": "Skale Venom",
      "utility3": "Spider Venom",
      "elite": "Shadow Meld"
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}]
}}>

Note that there are two slightly different variants of this build: one is meant for bosses with very short phases such as Ensolyss or Light Ai; the other one is meant for longer fights, where you will need to sustain damage for a longer period of time. This will also depend on your group. It will always be better to use the latter with people you do not know well, or in situations where your party doesn't bring enough damage.
The <Item name="afflicted"/> is a viable, more accessible alternative.
If healing isn't an issue, this is the perfect build to use <Item name="writofmasterfulmalice"/> over <Item name="tuningicicle"/> ! <Skill name="signetofmalice"/> is also the strongest personal-healing ability you can bring to maintain your health over 90%, if you feel you don't need <Skill name="hideinshadows"/>.

The <Skill name="skelkvenom"/> is a much better option to support your party as it brings a tremendous amount of party heal.
It's recommended to run a shortbow for additional movement during downtime and <Item name="doom"/> precasts, as well as <Boon name="might"/> blasts on the _Mistlock Singularity_. You will also want a Pistol with <Item id="24639"/> to help CC during Artsariiv splits.

</Character>  
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1="Trickery" traits1Selected="Burst of Agility,Pressure Striking,Deadly Ambush" traits2="Deadly Arts" traits2Selected="Deadly Ambition,Panic Strike,Potent Poison" traits3="Deadeye" traits3Selected="One in the Chamber,Payback,Maleficent Seven"/>

</GridItem>

<GridItem sm="5">

<Card title="Situational Skills">

|                                                           |                                                                                                    |
| --------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| <Skill id="13026" size="big" disableText/>                | A situational damage ability, to take over <Skill name="devourervenom"/> on stationary targets.    |
| <Skill name="infiltratorssignet" size="big" disableText/> | A quick shadowstep. Beginner-friendly alternative, which can be used for a bit more survivability. |
| <Skill name="signetofmalice" size="big" disableText/>     | Highest sustained healing.                                                                         |
| <Skill name="skelkvenom" size="big" disableText/>         | Best party healing.                                                                                |

</Card>
<Card title="Defiance Bar Damage">

|                          |                                          |
| ------------------------ | ---------------------------------------- |
| <Skill id="13132"/>      | up to 750 damage                         |
| <Skill name="Headshot"/> | 200 damage (260 with <Item id="24639"/>) |

</Card>
</GridItem>
</Grid>

<Divider text="Build Variants"/>

### High-Burst Variant

This variant is meant for short-duration fights or bosses with short phases; without any Cantrip slotted, take <Trait name="maliciousintent"/> over <Trait name="oneinthechamber"/>. Take <Skill id="13026"/> over <Skill name="devourervenom"/> on Ensolyss, Skorvald or Artsariiv, or <Skill name="mercy"/> with <Trait name="oneinthechamber"/> if group DPS is not high enough not to run out of _Initiative_. <Skill name="mercy"/> can still be taken over <Skill name="devourervenom"/> as a safety net. <Skill name="hideinshadows"/> becomes a necessity because of the lack of stealth applications.

<Grid>
<GridItem sm="4">
<Skills heal="Hide in Shadows" utility1="Devourer Venom" utility2="Skale Venom" utility3="Spider Venom" elite="Basilisk Venom" unembossed/>
</GridItem>

<GridItem sm="8">
<Traits traits1="Deadeye" traits1Selected="Malicious Intent,Payback,Maleficent Seven" unembossed/>
</GridItem>
</Grid>

### No Pain, No Gain Variant

<p>
<Trait id="1277"/> over <Trait id="1190"/> on <Instability name="No Pain, No Gain"/> days, or for some more support.
</p>

<Grid>
<GridItem sm="4">
<Skills heal="Hide in Shadows" utility1="Mercy" utility2="Skale Venom" utility3="Spider Venom" elite="Shadow Meld" unembossed/>
</GridItem>

<GridItem sm="8">
<Traits traits1="Trickery" traits1Selected="Burst of Agility,Bountiful Theft,Deadly Ambush" unembossed/>
</GridItem>
</Grid>

<Divider text="Details"/>

Watching videos of players performing the rotation for this build, one might think that it is easy to play; after all, the **<Specialization text="Thief" name="Thief"/>** tends to have spammy rotations, for the same reason mentioned before. The _Initiative_ system allows for multiple, redundant casts of the same ability, during the entire duration of the fight. It is easy to see that one ability will always perform better than other ones, based on the ratio of damage dealt over _Initiative_ points spent. Here are a the main reasons as to why this rotation isn't actually as easy as it looks, as well as some tips to master the rotation, depending on the encounter.

- The **<Specialization text="Condi Deadeye" name="Deadeye"/>** has three primary damaging abilities: <Skill id="50466"/>, <Skill id="59526"/>, and <Skill id="13010"/>. Due to the nature of <Skill id="13010"/> (which has to be casted to enable <Skill id="59526"/>), this rotation becomes very tricky, as it forces your character to Shadowstep Backwards: this is because the intention behind designing the Pistol/Dagger setup was probably to make a kiting kit, and it was never really meant to be a Best in Slot DPS kit. One way to bypass this is to **jump** during, or immediately after casting <Skill id="13010"/>. Not only is it an inconvenience for the rotation, but it also lowers your DPS slightly, as there will be a small, but significant delay where you will still be up in the air, unable to make your next move. It is necessary to jump <Skill id="13010"/> sometimes, such as when Dark Ai pulses AoEs in a set ring pattern, so as not to lose too much health, and fall into Downstate far away from your friends.
- <Skill name="shadowstrike"/> can see its range alleviated by positioning the camera at a steep angle, above your character, and running inside of the hitbox. The latter reduces the porting range to approximately 400 units, while combining the two reduces the range to about 180 units (courtesy of [Darkz](https://youtu.be/lYSjF4Q7zZA)).
- The rotation requires a good sense of timing, as do pretty much all **<Specialization text="Deadeye" name="Deadeye"/>** builds, to maximize your DPS: timing some abilities incorrectly, such as <Skill id="41372"/> (which will consume your Malice in exchange for some _Initiative_ points), can have dramatic consequences for the rest of the fight: you might end up being completely unable to use any ability whatsoever, because you have run out of _Initiative_ points to spend. Not being able to use abilities keeps your Malice bar too low, and this chain reaction can leave you powerless to do anything, until you can use <Skill name="mercy"/> or <Skill name="deadeyesmark"/> again.
- Missing an ability like <Skill name="shadowstrike"/> or hitting nothing but thin air with <Skill name="repeater"/>, both of which might happen from being out of range, will unnecessarily use up some of your _Initiative_, and might delay your <Trait id="2111"/> which could cause some issues for the rest of the fight, like not filling up your _Initiative_ bar at the proper moment.
- It is important to learn the rotation by heart, if you do not fully understand the _Malice_ mechanic. abilities such as <Skill id="50466"/> are only enabled when you are under the effect of <Effect name="Stealth"/>; notably, the latter has additional effects when Malice is consumed, so it is important _not_ to use <Skill name="mercy"/> before, or while casting it. Specifically, <Skill name="mercy"/> should always be used upon completing the <Skill id="50466"/>, so as not to interfere with <Effect name="stealth"/>-application skills like the random F2 Stolen skills (<Skill name="stealtime"/>, ...), <Skill name="hideinshadows"/> or <Skill name="shadowmeld"/>.
- Stolen abilities (<Skill name="stealhealth"/>, <Skill name="stealstrength"/>...) should _not_ be used if you have less than four _Malice_ points, as four of them ought to be consumed to provide you with <Effect name="Stealth"/>, enabling <Skill id="50466"/>.
- <Trait id="2078"/> is a key trait will lower the cooldown of all of your Utility Skills by 20% of their total cooldown after killing a _Marked_ target. Targets can be _Marked_ with <Skill name="deadeyesmark"/>. A good way to reset your <Skill name="deadeyesmark"/> in order to reapply it to a new foe is to run <Skill name="mercy"/>. It is absolutely essential to run this trait on every CM boss, as it will allow you to precast additional **<Skill name="preparethousandneedles"/>** on Ensolyss, or more _Venom Skills_ on all of the other bosses. We also recommend <Skill name="mercy"/> on bosses such as MAMA, Siax, Skorvald, Artsariiv and Arkk so as not to run out of initiative, and allow for more procs of <Trait id="2078"/>. Note that <Skill name="deadeyesmark"/> will always reset upon your _Marked_ target's death.
- Lastly, it should be noted that <Trait id="2136"/> is a crucial trait for longer fights, as the use of a cantrip like <Skill name="shadowmeld"/> or <Skill name="Mercy"/> will allow you to use a second Stolen ability, on top of the one that the <Skill name="deadeyesmark"/> gives you every twenty seconds or so.

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem sm="6">
<Card title="Rotation">

<Warning>

**Make sure to only press <Skill name="mercy"/> _after_ completing <Skill name="malicioussneakattack"/> !**
</Warning>

1.  <Skill name="deadeyesmark"/>
2.  <Skill name="Shadow Strike"/> (Pistol 3) + <Skill name="Skale Venom"/> + <Skill name="Spider Venom"/>
3.  Optional Immediate **Jump** after <Skill name="Shadow Strike"/>
4.  **<Skill name="Repeater"/> Three times** (Pistol 3)
5.  **One Stealth Ability**
6.  <Skill name="malicioussneakattack"/>

<Warning>

**Stealth abilities priority: <Skill name="stealtime"/> > <Skill name="hideinshadows"/> > <Skill name="shadowmeld"/> > <Skill name="cloakanddagger"/> (only if <Skill name="deadeyesmark"/> is coming off cooldown).**

</Warning>

**Repeat from 2.** Use <Skill name="deadeyesmark"/>, <Skill name="skalevenom"/> and <Skill name="spidervenom"/> whenever these abilities go off cooldown.
</Card>
</GridItem>

<GridItem sm="6">
<Card title="Golem rotation">

<Video youtube="-Rk0Lu8QpbU" caption="by Incera"/>
</Card>

<Card title="Precasting">

All Damaging Venom Skills should be casted on the _Mistlock Singularity_: <Skill name="Skale Venom"/>, <Skill name="Spider Venom"/> and <Skill name="Devourer Venom"/>. On stationary bosses which can be manually activated, instead of precasting <Skill name="Devourer Venom"/>, you can instead go to the spawn location and precast <Skill name="preparethousandneedles"/>. All you have to do then is to activate the Preparation when the boss becomes vulnerable, and cast it again as it will be off cooldown. This is possible on Skorvald, Artsariiv, Arkk, MAMA and Ensolyss with the use of a <Item name="White Mantle Portal Device"/>, or on Siax without. It is also possible on the Sorrowful Spellcaster (Light & Dark Ai), but with a 1/4 chance of success.

- On Dark Ai, make sure to precast venoms on your <Skill id="13082"/> minions, as every boon and special ability effect currently on you will be stripped upon starting the encounter.
- Spam <Skill name="clusterbomb"/> for <Boon name="might"/> blasts on the _Mistlock Singularity_.

</Card>
</GridItem>
</Grid>
