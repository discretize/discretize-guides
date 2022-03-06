---
title: Condi Weaver
rating: Good
role: Condi Damage
profession: Elementalist
specialization: Weaver
skills:
  - 43638
  - 5542
  - 40183
conditions:
  - Burning
  - Vulnerability
  - Crippled
  - Bleeding
  - Chilled
code: "[&DQYfFRomOBV0AHQAcwBzADUXNRfLAMsAEhcSFwAAAAAAAAAAAAAAAAAAAAA=]"
classification:
  - 3
  - 4
  - 3
  - 4
  - 5
date: 2022-03-06T22:00:44.095Z
cmGuide: ""
---

<Warning>

This build performs best in [Sunqua Peak](/fractals/sunqua-peak). Outside of this fractal, it will fall behind <BuildLink build="Power Weaver" specialization="Weaver"/> due to its fairly slower damage ramp-up.

</Warning>

The **<Specialization text="Condi Weaver" name="Weaver"/>** is an unique build that can be played very effectively in [Sunqua Peak](/fractals/sunqua-peak), and will almost always outperform <BuildLink build="Power Weaver" specialization="Weaver"/> (if you find yourself in a slow group, this build can also be an attractive choice for ''slower'' encounters like Ensolyss and Arkk).

Condi <Specialization name="Weaver"/> can deal very high amounts of damage, and even rival [META](/guides/meta-explained) builds like <BuildLink build="Condi Soulbeast" specialization="Soulbeast"/> and <BuildLink build="Condi Firebrand" specialization="Firebrand"/> when played properly.

This build is naturally tanky due to its rotation, having easy access to skills that provide evasion frames with <Skill name="Earthen Vortex"/>, barrier with <Skill name="Lava Skin"/>, condition cleansing with <Skill name="Magnetic Wave"/> and even <Skill name="Obsidian Flesh"/>, a powerful skill that grants <Effect name="Invulnerability"/> against most attacks. It can also bring some group utility in the form of projectile destruction with <Skill name="Swirling Winds"/>.

The main downside of **<Specialization text="Condi Weaver" name="Weaver"/>** apart from the complexity of its rotation is the lack of unique party buffs and overall boon generation, apart from some <Boon name="Might"/> granted by placing fire fields and randomly blasting them.

<Divider text="Equipment"/>

<CharacterWithAr>

<Character title="162 Agony Resistance" gear={{
    "profession": "Elementalist",
    "title": "162 Ar",
    "weight": "Light",
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
      "Armor": 2210,
      "Power": 3272.6,
      "Precision": 2186,
      "Toughness": 1243,
      "Vitality": 1000,
      "Ferocity": 184.8,
      "Condition Damage": 2692,
      "Expertise": 748,
      "Concentration": 243,
      "Healing Power": 0,
      "Agony Resistance": 162,
      "Condition Duration": 0.7986666666666666,
      "Boon Duration": 0.162,
      "Critical Chance": 0.9147619047619048,
      "Critical Damage": 1.6232,
      "Burning Duration": 0.2,
      "Bleeding Duration": 0.2,
      "Effective Power": 9298.886304280046,
      "Power DPS": 9767.948339651894,
      "Bleeding Damage": 295.926,
      "Bleeding Stacks": 32.578266666666664,
      "Bleeding DPS": 9640.756141599999,
      "Burning Damage": 884.06925,
      "Burning Stacks": 25.782799999999998,
      "Burning DPS": 22793.7806589,
      "Confusion Damage": 349.18365000000006,
      "Confusion Stacks": 0,
      "Confusion DPS": 0,
      "Poison Damage": 314.46975,
      "Poison Stacks": 0,
      "Poison DPS": 0,
      "Torment Damage": 441.954,
      "Torment Stacks": 0,
      "Torment DPS": 0,
      "Damage": 42202.48514015189,
      "Effective Health": 56905362.07849641,
      "Survivability": 28930.02647610392,
      "Effective Healing": 390,
      "Healing": 390
    },
    "runeId": 24800,
    "runeName": "Elementalist",
    "infusions": [
      37130, 37130, 37130, 37130, 37130, 37130, 37130,
      37130, 37130, 37130, 37130, 37130, 37130, 37130,
      37130, 86113, 86113, 86113
    ],
    "weapons": {
      "weapon1MainType": "Sword",
      "weapon1MainSigil1": "Earth",
      "weapon1OffType": "Focus",
      "weapon1OffSigil": "Geomancy"
    },
    "consumables": {
      "foodId": 91876,
      "utilityId": 48917,
      "infusion": "Malign +9 Agony Infusion"
    },
    "skills": {
      "heal": "Signet of Restoration",
      "utility1": "Glyph of Elemental Power",
      "utility2": "Primordial Stance",
      "utility3": "Signet of Fire",
      "elite": "Weave Self"
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"gw2id": 5542, "type": "Skill"}]
}}>

Note that the build does not rely on precision as much as the <BuildLink build="Power Weaver" specialization="Weaver"/> variant and you can build your Agony Resistance around the 150 breakpoint. You should however aim for a fully +9 stated infusion gear setup for maximum <Item id="79722"/> stat conversion value. The stats shown are with 162 Agony Resistance. This build requires 15x <Item name="malignagonyinfusion"/> and 3x <Item name="spitefulagonyinfusion"/>.

</Character>

</CharacterWithAr>

<Divider text="Build"/>

<Grid>

<GridItem sm="7">

<Traits traits1="Fire" traits1Selected="Burning Precision, Burning Rage, Persisting Flames" traits2="Earth" traits2Selected="Serrated Stones, Strength of Stone, Written in Stone" traits3="Weaver" traits3Selected="Superior Elements, Weavers Prowess, Elements of Rage"/>

<Card title="Situational Traits">

|                                                              |                                                                                                   |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| <Trait name="Pyromancers Puissance" size="big" disableText/> | Can easily cover a large amount of <Boon name="Might"/> for your group at some personal DPS loss. |
| <Trait name="Masters Fortitude" size="big" disableText/>     | Provides a bit of tankiness in the form of extra vitality for minimal DPS loss.                   |

</Card>

<Card title="Defiance Bar Damage">

|                                                         |                                                 |
| ------------------------------------------------------- | ----------------------------------------------- |
| <Skill name="Gale" size="big" disableText/>             | 400 with <Control name="Knockdown"/>            |
| <Skill name="Polaric Leap" size="big" disableText/>     | 100 with <Control name="Daze"/>                 |
| <Skill name="Comet" size="big" disableText/>            | 200 with <Control name="Daze"/>                 |
| <Skill name="Freezing Gust" size="big" disableText/>    | 33/s (181,5) with <Condition name="Chilled"/>   |
| <Skill name="Shearing Edge" size="big" disableText/>    | 33/s (148,5) with <Condition name="Chilled"/>   |
| <Skill name="Gale Strike" size="big" disableText/>      | 125 with <Control name="Float"/>                |
| <Skill name="Magnetic Wave" size="big" disableText/>    | 15 / s (135) with <Condition name="Crippled"/>  |
| <Skill name="Earthen Vortex" size="big" disableText/>   | 15 / s (82,5) with <Condition name="Crippled"/> |
| <Skill name="Twin Strike" size="big" disableText/>      | 33 / s (181,5) with <Condition name="Chilled"/> |
| <Skill name="Tailored Victory" size="big" disableText/> | 250 with <Control name="Float"/>                |

**Conditions applied are calculated by taking the maximum condition duration into account.**

</Card>

</GridItem>

<GridItem sm="5">

<Card title="Situational Skills">

<Warning>

If you do want to switch any of your utilites in favor of one of the skills listed above, you should prioritise dropping <Skill name="Glyph of Elemental Power"/> before <Skill name="Primordial Stance"/> and <Skill name="Signet of fire"/>.

</Warning>

|                                                                   |                                                                                                                                                |
| ----------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Heal                                                              |
| <Skill name="Arcane Brilliance" size="big" disableText/>          | An additional <Boon name="Might"/> source from blasting fire fields. Overall provides less healing than <Skill name="Signet Of Restoration"/>. |
| <Skill name="Glyph of Elemental Harmony" size="big" disableText/> | A stronger alternative healing skill when you need to restore a large amount of health very quickly.                                           |
| <Skill name="Aquatic stance" size="big" disableText/>             | Another alternative healing skill affecting allies close to the target you strike.                                                             |
| Offensive                                                         |
| <Skill name="Glyph of Lesser Elementals" size="big" disableText/> | A rather unreliable alternative to <Skill name="Glyph of Elemental Power"/> due to the nature of the pet's AI. Use with caution.               |
| Defensive                                                         |
| <Skill name="Arcane Shield" size="big" disableText/>              | A stun break with the addition of 3 blocks.                                                                                                    |
| <Skill name="Armor of Earth" size="big" disableText/>             | Another stun break that provides extra <Boon name= "Protection"/> and <Boon name= "Stability"/>.                                               |
| <Skill name="Stone Resonance" size="big" disableText/>            | A strong skill providing a lot of barrier and extra <Boon name= "Stability"/>.                                                                 |
| <Skill name="Twist of Fate" size="big" disableText/>              | Yet another stun break with the addition of evade frames.                                                                                      |
| Utility                                                           |
| <Skill name="Lightning Flash" size="big" disableText/>            | A 900 units teleport for easy repositioning.                                                                                                   |
| <Skill name="Glyph of Renewal" size="big" disableText/>           | You can sacrifice some DPS for a powerful insta rez, can be very useful during "Dancing with Demons" runs.                                     |

</Card>

</GridItem>

</Grid>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem xs="12" sm="12">
<Card title="Disclaimer">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt a rotation to the amount of time a group needs to finish a phase.  
</Card>
</GridItem>

<GridItem xs="12" sm="12">
<Card title="Precasting">

### **Weaver Precast**

- Start on <Skill name="Fire Attunement"/>/<Skill name="Earth Attunement"/> and precast <Skill name="Glyph of ELemental Power"/>, <Skill name="Arcane Power"/>.
- Attune to <Skill name="Earth Attunement"/>/<Skill name="Fire Attunement"/> and precast <Skill name="Weave Self"/>.
- Take the _Mistlock Singularity_ and attune to <Skill name="Air Attunement"/>/<Skill name="Earth Attunement"/>.

It is recommended to use separate precast builds to get additional buffs like <Trait name="Elemental Surge"/>.

Precasting build template:

<Traits unembossed traits1="Arcane" traits1Selected=",Renewing Stamina, Elemental Lockdown, Elemental Surge" traits2="Air" traits2Selected="One with air, Raging Storm, Fresh Air" traits3="Weaver" traits3Selected=",Superior Elements, Weavers Prowess, Elements of Rage"/>

### **Extra Precast for [Sunqua Peak](/fractals/sunqua-peak)**

If you have an extra set of weapons (or legendary sigils), you can also precast the effects of <Item name="Doom"/> and <Item name="Leeching"/>. To do that:

- Switch to the sigils, fall below the stairs before the boss' arena to get in combat and switch to any attunement.
- Once you are out of combat, you can switch the sigils back to <Item name="Earth"/> and <Item name="Geomancy"/>.

</Card>
</GridItem>

<GridItem xs="12" sm="6">

<Card title="Rotation during Weave Self">

<Grid>
<GridItem sm="3">
<Skill name="Air Attunement" size="large" disableText/> <Skill name="Earth Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Weave Self"/>
2. <Skill name="Signet of Fire"/>
3. <Skill name="Gale Strike"/>
4. <Skill name="Magnetic Wave"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Air Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Flame Uprising"/>
2. <Skill name="Pyro Vortex"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Transmute Fire"/>
2. <Skill name="Cauterizing Strike"/>
3. <Skill name="Flamewall"/>

</GridItem>

<GridItem sm="3">
<Skill name="Earth Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Lava Skin"/>
2. <Skill name="Earthen Vortex"/>

</GridItem>

<GridItem sm="3">
<Skill name="Earth Attunement" size="large" disableText/> <Skill name="Earth Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Rust Frenzy"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Earth Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Flame Uprising"/>
2. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> =>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Searing Slash"/>
2. <Skill name="Transmute Fire"/>
3. <Skill name="Signet of Fire"/>

</GridItem>

<GridItem sm="3">
<Skill name="Air Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Pyro Vortex"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Air Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Flame Uprising"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Cauterizing Strike"/>
2. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> =>

</GridItem>

<GridItem sm="3">
<Skill name="Earth Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Searing Slash"/>
2. <Skill name="Transmute Fire"/>
3. <Skill name="Flamewall"/>
4. <Skill name="Earthen Vortex"/>

</GridItem>

<GridItem sm="3">
<Skill name="Water Attunement" size="large" disableText/> <Skill name="Earth Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Natural Frenzy"/>
2. <Skill name="Magnetic Wave"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Water Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Flame Uprising"/>
2. <Skill name="Signet of Fire"/>
3. <Skill name="Twin strike"/>
4. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> => <Skill name="Searing Slash"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Transmute Fire"/>
2. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> => <Skill name="Searing Slash"/>
3. <Skill name="Cauterizing Strike"/>
4. <Skill name="Flame Uprising"/>

</GridItem>
</Grid>

</Card>

</GridItem>

<GridItem xs="12" sm="6">

<Card title="Golem Rotation">
<Video youtube="H5ZyMQln6hw" caption="by Roul [SC]" />
</Card>

<Card title="Important Notes">

- <Skill name="Signet of Fire"/> is one of your most important DPS skills. Use it off cooldown!

- Make sure to always use <Skill name="Glyph of ELemental Power"/> in <Skill name="Fire Attunement"/>. If the boss is about to phase or die, your next best option is to use it in <Skill name="Earth Attunement"/>. If you find yourself is any other element, you should use it regardless, as it grants increased strike damage on your next few attacks.

- <Skill name="Primordial Stance"/> should be used during <Skill name="Earth Attunement" disableText/> <Skill name="Earth Attunement" disableText/> for maximum damage output. However, if the boss' breakbar is about to be broken or about to phase, you can also use it during <Skill name="Fire Attunement" disableText/> <Skill name="Earth Attunement" disableText/> or <Skill name="Fire Attunement" disableText/> <Skill name="Fire Attunement" disableText/>.

- Although it is important to finish auto attack chains, during <Skill name="Weave Self"/>, you should prioritize using your skills and entering <Skill name="Tailored Victory"/>, even if it means skipping some auto attacks. Maintaining the <Skill name="Fire Attunement" disableText/> buff of <Skill name="Weave Self"/> is most important.

- In the video, a 2nd <Skill name="Weave Self"/> rotation is shown, which is different from the 1st. However, due to the faster nature of fractal bosses, you will either phase the boss before you reach the 2nd rotation or there will be enough downtime to reset to the written rotation when <Skill name="Weave Self"/> is on cooldown.

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Rotation out of Weave Self">

<Grid>
<GridItem sm="3">
<Skill name="Earth Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Lava Skin"/>
2. <Skill name="Earthen Vortex"/>
3. <Skill name="Crystal Slash"/> => <Skill name="Crystalline Strike"/> => <Skill name="Crystalline Sunder"/>
4. <Skill name="Transmute Fire"/>
5. <Skill name="Flamewall"/>

</GridItem>

<GridItem sm="3">
<Skill name="Earth Attunement" size="large" disableText/> <Skill name="Earth Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Signet of Fire"/>
2. <Skill name="Rust Frenzy"/>
3. <Skill name="Crystal Slash"/> => <Skill name="Crystalline Strike"/> =>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Earth Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Crystalline Sunder"/>
2. <Skill name="Flame Uprising"/> + <Skill name="Magnetic Wave"/>
3. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> => <Skill name="Searing Slash"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Transmute Fire"/>
2. <Skill name="Cauterizing Strike"/>
3. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> => <Skill name="Searing Slash"/>
4. <Skill name="Flame Uprising"/>

</GridItem>

<GridItem sm="3">
<Skill name="Air Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Signet of Fire"/>
2. <Skill name="Pyro Vortex"/>
3. <Skill name="Charged Strike"/> => <Skill name="Polaric Slash"/> => <Skill id="45216"/>
4. <Skill name="Flamewall"/>
5. <Skill name="Transmute Fire"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Air Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> => <Skill name="Searing Slash"/>
2. <Skill name="Flame Uprising"/>
3. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> =>

</GridItem>

<GridItem sm="3">
<Skill name="Earth Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Searing Slash"/>
2. <Skill name="Lava Skin"/>
3. <Skill name="Earthen Vortex"/>
4. <Skill name="Crystal Slash"/> => <Skill name="Crystalline Strike"/> => <Skill name="Crystalline Sunder"/>
5. <Skill name="Transmute Fire"/>

</GridItem>

<GridItem sm="3">
<Skill name="Earth Attunement" size="large" disableText/> <Skill name="Earth Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Signet of Fire"/> + <Skill name="Magnetic Wave"/>
2. <Skill name="Rust Frenzy"/>
3. <Skill name="Crystal Slash"/> => <Skill name="Crystalline Strike"/> =>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Earth Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Crystalline Sunder"/>
2. <Skill name="Flame Uprising"/>
3. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> => <Skill name="Searing Slash"/> x2

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Transmute Fire"/>
2. <Skill name="Flamewall"/>
3. <Skill name="Cauterizing Strike"/>
4. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> => <Skill name="Searing Slash"/>
5. <Skill name="Flame Uprising"/>

</GridItem>

<GridItem sm="3">
<Skill name="Air Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Signet of Fire"/>
2. <Skill name="Pyro Vortex"/>
3. <Skill name="Charged Strike"/> => <Skill name="Polaric Slash"/> => <Skill id="45216"/>
4. <Skill name="Transmute Fire"/>

</GridItem>

<GridItem sm="3">
<Skill name="Fire Attunement" size="large" disableText/> <Skill name="Air Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> => <Skill name="Searing Slash"/>
2. <Skill name="Flame Uprising"/>
3. <Skill name="Fire strike"/> => <Skill name="Fire Swipe"/> =>

</GridItem>

<GridItem sm="3">
<Skill name="Earth Attunement" size="large" disableText/> <Skill name="Fire Attunement" size="large" disableText/>
</GridItem>
<GridItem sm="9">

1. <Skill name="Searing Slash"/>
2. <Skill name="Lava Skin"/>
3. <Skill name="Earthen Vortex"/>

</GridItem>
</Grid>

</Card>
</GridItem>
</Grid>
