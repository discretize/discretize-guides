---
title: Power Willbender
rating: Good
role: Power Damage
profession: Guardian
specialization: Willbender
skills:
conditions:
  - Vulnerability
  - Blinded
  - Crippled
boons:
  - name: Quickness
    uptime: ~10%
    variant: group
  - name: Quickness
    uptime: ~25%
    variant: self
  - name: Might
    uptime: 2 stacks
    variant: party
code: ''
classification:
  - 3
  - 3
  - 3
  - 3
  - 3
date: 2022-01-11T02:53:58.478Z
Hidden: True
---

<Warning>

This build guide is not complete, gear and sections may chage regularly as we explore the new elite spec and spend more time playing it in fractals!

</Warning>

It has great burst options and deals high consistent damage while providing medium defiance bar damage and <Condition name="Vulnerability"/>. The build offers a unique party wide offensive buff by sharing <Skill name="bane signet"/> for 216 <Attribute name="Power"/> and also strong on-demand defensive support with <Skill id="30039"/> and other useful skills such as <Skill id="9251"/> and <Skill name="standyourground"/>. It benefits from slaying potions and slaying sigils such as <Item id="50082"/> and <Item name="Serpent Slaying" type="Sigil"/>.

<Divider text="Equipment"/>

<CharacterWithAr>  
<Character title="162 Agony Resistance" gear={{
  "profession": "Guardian",
  "weight": "Heavy",
  "gear": [
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 11645,
    "Armor": 2514,
    "Power": 4053,
    "Precision": 2363,
    "Toughness": 1243,
    "Vitality": 1000,
    "Ferocity": 1556,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 0.999047619047619,
    "Critical Damage": 2.5373333333333337,
    "Effective Power": 27600.641490421407,
    "Power DPS": 34955.14434424182,
    "Bleeding Damage": 108.875,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 401.78125,
    "Burning Stacks": 2.9,
    "Burning DPS": 1165.1656249999999,
    "Confusion Damage": 134.14375,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 127.5625,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 161.36249999999998,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 36120.30996924182,
    "Effective Health": 58259761.19402986,
    "Survivability": 29618.58728725463,
    "Effective Healing": 390,
    "Healing": 390
  },
    "runeId": 24836,
    "runeName": "Scholar",
    "infusions": [
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131
    ],
    "weapons": {
      "weapon1MainType": "Sword",
      "weapon1MainSigil1": "Force",
      "weapon1OffType": "Focus",
      "weapon1OffSigil": "Impact",
      "weapon2MainType": "Greatsword",
      "weapon2MainSigil1": "Force",
      "weapon2MainSigil2": "Impact"
    },
    "consumables": {
      "foodId": 91805,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
    "skills": {
      "heal": "Litany of Wrath",
      "utility1": "Flash Combo",
      "utility2": "Sword of Justice",
      "utility3": "Bane Signet",
      "elite": "Feel My Wrath"
    }
  }}
>

If you use <Trait name="Perfectinscriptions"/> you are lacking critical chance, therefore additional assassins pieces are required. You can of course mitigate this by increasing your <Attribute name="Agony Resistance"/>. You need at least <Attribute name="Agony Resistance" text="203 Agony Resistance"/> to compensate the lacking <Attribute name="Precision"/>. It is not recommended to run <Trait name="Righthandstrength"/> unless you have multiple <Specialization name="Guardian"/> or another source of <Boon name="Resolution"/>.

</Character>  
<Character title="203 Agony Resistance" gear={{
  "profession": "Guardian",
  "weight": "Heavy",
  "gear": [
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 11645,
    "Armor": 2604,
    "Power": 4110,
    "Precision": 2394,
    "Toughness": 1333,
    "Vitality": 1000,
    "Ferocity": 1556,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 333,
    "Healing Power": 0,
    "Agony Resistance": 222,
    "Condition Duration": 0,
    "Boon Duration": 0.222,
    "Critical Chance": 1.013809523809524,
    "Critical Damage": 2.5373333333333337,
    "Effective Power": 28004.967244363743,
    "Power DPS": 35467.2072648103,
    "Bleeding Damage": 108.875,
    "Bleeding Stacks": 0,
    "Bleeding DPS": 0,
    "Burning Damage": 401.78125,
    "Burning Stacks": 2.9,
    "Burning DPS": 1165.1656249999999,
    "Confusion Damage": 134.14375,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 127.5625,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 161.36249999999998,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 36632.3728898103,
    "Effective Health": 60345432.835820906,
    "Survivability": 30678.91857438785,
    "Effective Healing": 390,
    "Healing": 390
  },
    "infusions": [
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131, 37131, 37131, 37131,
      37131, 37131, 37131, 37131
    ],
    "weight": "Heavy",
    "runeId": 24836,
    "runeName": "Scholar",
    "weapons": {
      "weapon1MainType": "Sword",
      "weapon1MainSigil1Id": 24615,
      "weapon1OffType": "Focus",
      "weapon1OffSigilId": 24868,
      "weapon2MainType": "Greatsword",
      "weapon2MainSigil1Id": 24615,
      "weapon2MainSigil2Id": 24868
    },
    "consumables": {
      "foodId": 91805,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
    "skills": {
      "heal": "Litany of Wrath",
      "utility1": "Flash Combo",
      "utility2": "Sword of Justice",
      "utility3": "Bane Signet",
      "elite": "Feel My Wrath"
    }
  }}
>

It is not recommended to run <Trait name="Righthandstrength"/> unless you have multiple <Specialization name="Guardian"/> or another source of <Boon name="Resolution"/>.

</Character>  
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="16" traits1="Radiance" traits1SelectedIds="574,565,579" traits2Id="42" traits2="Zeal" traits2SelectedIds="634,653,2017" traits3Id="65" traits3="Willbender" traits3SelectedIds="2190,2210,2201"/>

<Card title="Virtues">

If you can reliably upkeep <Boon name="Aegis"/>, and you dont gain value from sharing <Skill name="Bane Signet"/> through <Trait name="Perfect Inscriptions"/>. You can drop the Radiance traitline for Virtues for more personal damage. Please note you will need to adjust your gear potentially to crit cap! Check the [gear optimizer](https://discretize.github.io/discretize-gear-optimizer) for more gear variants!

<Traits unembossed traits1="Virtues" traits1Selected="Unscathed Contender,Inspiring Virtue,Permeating Wrath"/>

</Card>

<Card title="CC skills">

|                                                 |            |
| ----------------------------------------------- | ---------- |
| <Skill id="9093"/>                              | 300 damage |
| <Skill id="9226"/> (after <Skill id="9147"/>)   | 150 damage |
| <Skill name="chainsoflight"/>                   | 250 damage |
| <Skill name="hammerofwisdom"/>                  | 200 damage |
| <Skill name="sanctuary"/>                       | 750 damage |
| <Skill name="Heavens Palm"/>                    | 400 damage (Knockdown) <br/> 150 damage (Knockback)|

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

|                                                        |                                                                                     |
| ------------------------------------------------------ | ----------------------------------------------------------------------------------- |
| <Skill id="9246" size="big" disableText/>              | A 1,200 range teleport to an ally.                                                  |
| <Skill name="Hallowed Ground" size="big" disableText/> | When <Boon name="Stability"/> is needed.                                            |
| <Skill id="9153" size="big" disableText/>              | When <Boon name="Stability"/> or a stunbreak is needed.                             |
| <Skill id="9125" size="big" disableText/>              | Deals an additional 200 defiance bar damage.                                        |
| <Skill id="9251" size="big" disableText/>              | A stationary reflect lasting for 10 seconds.                                        |
| <Skill id="9247" size="big" disableText/>              | A 1200 range teleport to an enemy.                                                  |
| <Skill name="Purging flames" size="big" disableText/>  | Cleanses conditions.                                                                |
| <Skill name="Sanctuary" size="big" disableText/>       | Huge CC and projectile destruction.                                                 |
| <Skill name="renewed focus" size="big" disableText/>   | Recharges all virtue skills, grants <Effect name="Invulnerability"/> for 3 seconds. |

</Card>
</GridItem>
</Grid>

<Divider text="Details"/>

As a <Specialization name="Dragonhunter" text="Power Dragonhunter"/> it is important to play <Trait name="perfectinscriptions"/> to be able to use the <Skill name="Banesignet"/> for 300 CC while also sharing the 216 <Attribute name="Power"/> buff with your allies. This enables everyone to deal more damage during critical parts of the fight when the boss is <Effect name="exposed"/>.

Generally it is important to apply <Boon name="Resolution"/> when you are about to burst for the <Trait name="retribution"/> modifier. Thanks to <Trait name="healersresolution"/> your heal skill applies long lasting <Trait name="retribution"/>. Since <Skill name="litanyofwrath"/> has a low cooldown it lines up well with your burst. You can also trigger a <Skill id="13677"/> by losing health below the 75% threshold to trigger <Trait id="648"/>, however you need to be careful to not die.

<Divider text="Rotation / Skill Usage"/>

<Grid>
<GridItem xs="12" sm="6">
<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt their rotation to the amount of time a group needs to finish a phase.\
For that reason you will find some general notes for skill usage here.
</Card>

<Card title="Precasting">

If you have a Mistlock Singularity present you can use these skills for precasts:

1.  Cast <Skill name="litany of wrath"/> for <Boon name="Resolution"/>

2.  Use <Skill name="Save yourselves"/> or <Skill name="hallowedground"/>

3.  Blast a fire field with <Skill name="Holy Strike"/>

4.  Use <Skill name="Feelmywrath"/>

5.  Use <Skill name="banesignet"/>

6.  Take mistlock

7.  Blast a fire field with <Skill name="Holy Strike"/> again

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Notes on skill usage:">

- Always start on sword

- Delay swapping to GS until the CC-bar is about to be broken. This is especially important at Ensolyss without instant CC.

- Always cast your <Skill name="whirlingwrath"/> inside the hitbox to get the additional hits. Ideal with adds around.

- Always cast your <Skill name="bindingblade"/> inside the hitbox to get the additional hits when adds are present. Can be abused at **Artsariiv**, **Arkk**, **Siax** and **Ensolyss**.

- Don't interrupt your GS auto-attack chain.

- In certain scenarios (precasting traps, starting with <Skill name="onewolfpack"/>) it can be beneficial to get your <Skill name="spearofjustice"/> out first.

- Don't waste your key skills on meaningless adds.

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Golem Rotation">

**Rotation:**

This is wrong, just seeing if new skills show

1.  <Skill name="banesignet" profession="guardian"/>

2.  <Skill name="Symbol of Blades" profession="guardian"/> (Sword 2)

3.  <Skill name="Shield of Wrath" profession="guardian"/> (Focus 5)

4.  <Skill name="Sword of Justice" profession="guardian"/>

5.  <Skill name="Rushing Justice" profession="guardian"/> (F1)

6.  <Skill name="Flash Combo" profession="guardian"/> 

7.  <Skill name="Zealotsdefense" profession="guardian"/> (Sword 3)

8.  <Skill name="Ray of Judgment" profession="guardian"/> (Focus 4)

9.  **Weapon Swap**

10. <Skill name="Symbol of Resolution" profession="guardian"/> (GS 4)

11. <Skill name="Whirling Wrath" profession="guardian"/> (GS 2)

12. <Skill name="Sword of Justice" profession="guardian"/>

14. <Skill name="Sword of Justice" profession="guardian"/>

15. <Skill name="Leap of Faith" profession="guardian"/> (GS 3)

16. <Skill name="Binding Blade" profession="guardian"/> (GS 5)

17. If the phase lasts longer than this, continue with the SC rotation.

</Card>
</GridItem>

<GridItem xs="12" sm="6">
<Card title="Golem Rotation">

<Video youtube="" caption=""/>
</Card>
</GridItem>
</Grid>

<Divider text="Underwater combat"/>

It is very much recommended to play <BuildLink build="Condi Firebrand" specialization="Firebrand"/> since it provides much better DPS compared to the <Specialization text="Power Willbender" name="Willbender"/>. If you still want to play <Specialization text="Power Willbender" name="Willbender"/> for whatever reason follow these rough guidelines.

- Open with <Skill name="refraction"/> for <Boon name="resolution"/>

- Cast <Skill name="purify"/> and swap to spear. Camp spear now.

- Priority list:

  1.  <Skill name="Zealots flurry"/> (Spear 2)

  2.  <Skill name="Symbol of spears"/> (Spear 4)

  3.  <Skill name="brilliance"/> (Spear 3)
