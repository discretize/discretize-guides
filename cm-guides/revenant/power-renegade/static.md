---
title: Renegade CM Guide
type: static
profession: Revenant
specialization: Renegade
disableBosses:
  - "- LightAi   - DarkAi"
date: 2023-03-20T13:16:32.300Z
---

<Boss name="mama" video="lAIxOQlt_jI" timestamp="235" videoCreator="Inky" foodId="43360" utilityId="50082" legend1Id="41858" legend2Id="28134" weapon1MainAffix="Berserker" weapon1MainType="Sword" weapon1MainSigil1="Impact" weapon1MainInfusion1Id="37131" weapon1OffAffix="Berserker" weapon1OffType="Sword" weapon1OffSigil="Force" weapon1OffInfusionId="37131" weapon2MainAffix="Berserker" weapon2MainType="Staff" weapon2MainSigil1="Severance" weapon2MainSigil2="Impact" weapon2MainInfusion1Id="37131" weapon2MainInfusion2Id="37131">

- Suggested Boon Duration: `20%`.
- Use <Trait name="Lasting Legacy"/> to maintain decent party <Boon name="Might"/>.
- Increase boon duration if you notice downtime in <Boon name="Alacrity"/>.
- Swap to <Item name="Celerity"/> on Staff if you notice a drop in <Boon name="Quickness"/>.
-----
- If <Instability name="Social Awkwardness"/> is present you can share <Boon name="Stability"/> at key moment in the fight via <Skill name="Inspiring Reinforcement" />.
  - In this case take <Trait name="SpiritBoon"/> to share a stack whenever you swap to <Skill name="LegendaryDwarfStance" />.
-----
- If <Instability name="No Pain, No Gain"/> is present take <Item name="absorption"/> on both weapon sets.
-----
- If <Instability name="Afflicted"/>, <Instability name="Vengeance"/> or <Instability name="FluxBomb"/> is present you can precast <Boon name="Resistance"/> via <Skill name="LegendaryDemonStance" /> skill <Skill name="Pain Absorption" />.

</Boss>

<Phase>
<CMInformation title="Precast">
----
<InformationBlock title="At the Mistlock">
Share <Boon name="Alacrity"/> and blast the fire field to gain <Boon name="Might"/>.<br/>
If you are on fire field duty use <Skill name="Soulcleaves Summit" />. Finally swap to <Skill name="LegendaryAssassinStance"/> to invoke your <Skill name="enchanted daggers"/> and swap back to <Skill name="legendaryrenegadestance" />.
</InformationBlock>
<InformationBlock title="On Boss">
Cast your <Skill name="legendaryrenegadestance" /> summons on the north/north-east side of the invisible hitbox to prevent entering in combat too early.
</InformationBlock>
</CMInformation>
<IdealRotation>

1.  <Skill name="renewingwave" />
2.  <Skill name="ordersfromabove" />
3.  Take _Mistlock Singularity_
4.  <Skill name="renewingwave" />
5.  <Skill name="ordersfromabove" />
6.  <Skill name="enchanteddaggers" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 1">
----
Before mama becomes vulnerable precast <Skill name="citadelbombardment" />.<br/>
Cast <Skill name="surgeofthemists" /> under <Skill name="impossibleodds" /> then swap to <Skill name="legendaryrenegadestance" />.<br/>
On sword, cast <Skill name="chillingisolation" /> and <Skill name="deathstrike" /> into <Effect name="exposed"/> and prepare for knight 1.
<InformationBlock title="Tips">
- In a slower party it is higher damage to cast <Skill name="citadelbombardment" /> after <Skill name="surgeofthemists" /> as you can profit from <Trait name="Unsuspecting Strikes"/> in <Effect name="exposed"/>.
- If your party is missing damage on the adds keep <Skill name="deathstrike" /> for knight 1.<br/><br/><br/><br/><br/><br/>
</InformationBlock>
</CMInformation>
<IdealRotation>

1. On Boss (Precasted)
    1. <Skill name="darkrazorsdaring" />
    2. <Skill name="icerazorsire" />
    3. <Skill name="legendaryassassinstance" />
2. <Skill name="citadelbombardment" />
3. <Skill name="surgeofthemists" />
4. <Skill name="chillingisolation" />
3. <Skill name="legendaryrenegadestance" />
5. <Skill name="deathstrike" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Knight 1">
----
<InformationBlock>
Precast <Skill name="shacklingwave" /> to instantly apply <Condition name="vulnerability"/> and <Condition name="Immobile"/> on the add.<br/>
Share <Boon name="Alacrity"/> and cast <Skill name="chillingisolation" /> into <Effect name="exposed"/> then precast <Skill name="Icerazors Ire"/> into p2.<br/><br/>
</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="shacklingwave" />
2. <Skill name="ordersfromabove" />
3. <Skill name="chillingisolation" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 2">
----
<InformationBlock>
Burst the phase with <Skill name="chillingisolation" /> and <Skill name="citadelbombardment" />.<br/>
Share <Boon name="Might"/> then prepare for knight 2.
</InformationBlock>
<InformationBlock title="Tips">
- If your party is missing damage you may want to fit another <Skill name="chillingisolation" />. In this case you will want to <Skill name="legendaryassassinstance" /> swap earlier.
</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="icerazorsire" />
3. <Skill name="chillingisolation" />
4. <Skill name="citadelbombardment" />
5. <Skill name="heroiccommand" />
6. <Skill name="chillingisolation" /> (Knight 2)


</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Knight 2">
----
<InformationBlock>
If available instant cast <Skill name="chillingisolation" /> before the add is visible.<br/>
Precast <Skill name="Darkrazors Daring"/> to break the add.
- Swap to <Skill name="legendaryassassinstance" /> at or below 10% energy to proc <Trait name="Charged mists"/>.

Cast <Skill name="shacklingwave" /> to apply instant <Condition name="vulnerability"/> while dealing moderate damage and fit in another <Skill name="chillingisolation" /> if needed.<br/><br/>
Share <Boon name="Might"/> and <Boon name="Alacrity"/> before p3 starts.
</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="darkrazorsdaring" />
2. <Skill name="legendaryassassinstance" />
1. <Skill name="shacklingwave" />
2. <Skill name="chillingisolation" />
3. <Skill name="heroiccommand"/>
2. <Skill name="ordersfromabove" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 3">
----
Burst with <Skill name="citadelbombardment" />, <Skill name="deathstrike" /> and <Skill name="chillingisolation" /> under <Skill name="impossible odds"/> then swap to <Skill name="LegendaryRenegadeStance"/>.
<InformationBlock title="Tips">
- If you do not have a way to avoid damage in this phase, you can use <Skill name="Unrelenting Assault" /> after <Skill name="citadelbombardment" /> as it is a two seconds evade.

</InformationBlock>
</CMInformation>
<IdealRotation>

3. <Skill name="citadelbombardment" />
4. <Skill name="deathstrike" />
5. <Skill name="chillingisolation" />
6. <Skill name="LegendaryRenegadeStance"/>


</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Knight 3">
----
<InformationBlock>
Precast <Skill name="Darkrazors Daring"/> to break the add and use <Skill name="Breakrazors Bastion"/> if needed.<br/>
Cast <Skill name="shacklingwave" /> to apply instant <Condition name="vulnerability"/> and <Condition name="Immobile"/>.<br/>
Deal moderate damage with <Skill name="chillingisolation" />, share <Boon name="might"/> then weapon swap to staff.<br/><br/><br/>
</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="darkrazorsdaring" />
2. <Skill name="shacklingwave" />
2. <Skill name="chillingisolation" />
3. <Skill name="heroiccommand" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 4">
----
Precast <Skill name="icerazorsire" /> and use <Skill name="Warding Rift"/> to mitigate the knock back shockwaves.<br/>
Cast <Skill name="surgeofthemists"/> to break the boss and profit from <Item name="Severance"/>.<br/>
In <Effect name="exposed"/> burst with <Skill name="citadelbombardment" /> under <Skill name="impossible odds"/>.<br/>
- Share <Boon name="alacrity"/> and <Boon name="might"/> whenever possible.<br/>

Keep dealing damage with auto attack and <Skill name="Menders Rebuke"/> until the boss dies.

<InformationBlock title="Tips">
- If the party is missing damage, you will have time to burst again with <Skill name="chillingisolation" />, <Skill name="shacklingwave" /> and <Skill name="deathstrike" />.
</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="icerazorsire" />
2. <Skill name="heroiccommand" />
3. <Skill name="ordersfromabove" />
1. <Skill name="surgeofthemists" />
2. <Skill name="citadelbombardment" />
3. <Skill name="legendaryassassinstance" />
4. <Skill name="Menders Rebuke"/>

</IdealRotation>
</Phase>

<Boss name="siax" video="lAIxOQlt_jI" timestamp="290" videoCreator="Inky" foodId="43360" utilityId="50082" legend1Id="41858" legend2Id="28134" weapon1MainAffix="Berserker" weapon1MainType="Sword" weapon1MainSigil1="Impact" weapon1MainInfusion1Id="37131" weapon1OffAffix="Berserker" weapon1OffType="Sword" weapon1OffSigil="Serpentslaying" weapon1OffInfusionId="37131" weapon2MainAffix="Berserker" weapon2MainType="Staff" weapon2MainSigil1="Severance" weapon2MainSigil2="Serpentslaying" weapon2MainInfusion1Id="37131" weapon2MainInfusion2Id="37131">

- Suggested Boon Duration: `20%`
- Traits - Take <Trait name="Lasting Legacy"/>
- Increase boon duration if you notice downtime in <Boon name="Alacrity"/>.

</Boss>

<Phase>
<CMInformation title="Precast">

<InformationBlock title="Overview">

</InformationBlock>
<InformationBlock title="At The Mistlock">
</InformationBlock>
</CMInformation>
<IdealRotation>

1.  <Skill name="renewingwave" />
2.  <Skill name="ordersfromabove" />
3.  Take _Mistlock Singularity_
4.  <Skill name="renewingwave" />
5.  <Skill name="ordersfromabove" />
6.  <Skill name="enchanteddaggers" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 1">
<InformationBlock title="Overview">
</InformationBlock>
</CMInformation>
<IdealRotation>

1. Precast
    1. <Skill name="darkrazorsdaring" />
    2. <Skill name="icerazorsire" />
    3. <Skill name="legendaryassassinstance" />
2. <Skill name="citadelbombardment" />
3. <Skill name="chillingisolation" />
4. <Skill name="legendaryrenegadestance" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Split 1">
<InformationBlock>

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="shacklingwave" />
2. <Skill name="chillingisolation" />
3. <Skill name="deathstrike" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 2">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="icerazorsire" />
2. <Skill name="citadelbombardment" />
3. <Skill name="ordersfromabove" />
4. <Skill name="heroiccommand" />
5. <Skill name="legendaryassassinstance" />


</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Split 2">
<InformationBlock>

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="shacklingwave" />
2. <Skill name="chillingisolation" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 3">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="deathstrike" />
2. <Skill name="chillingisolation" />
3. <Skill name="heroiccommand" />
4. <Skill name="legendaryrenegadestance" />
5. <Skill name="icerazorsire" />
6. <Skill name="citadelbombardment" />
7. <Skill name="chillingisolation" />

</IdealRotation>
</Phase>

<Boss name="ensolyss" video="lAIxOQlt_jI" timestamp="344" videoCreator="Inky" foodId="91805" utilityId="50082" legend1Id="41858" legend2Id="28134" weapon1MainAffix="Berserker" weapon1MainType="Sword" weapon1MainSigil1="Impact" weapon1MainInfusion1Id="37131" weapon1OffAffix="Berserker" weapon1OffType="Sword" weapon1OffSigil="Serpentslaying" weapon1OffInfusionId="37131" weapon2MainAffix="Berserker" weapon2MainType="Staff" weapon2MainSigil1="Severance" weapon2MainSigil2="Serpentslaying" weapon2MainInfusion1Id="37131" weapon2MainInfusion2Id="37131">

- Suggested Boon Duration: `20%`
- Increase boon duration if you notice significant downtime in <Boon name="Alacrity"/>.
- Make sure a <Specialization name="Soulbeast"/> takes <Skill name="moastance" />
</Boss>

<Phase>
<CMInformation title="Precast">

<InformationBlock title="Overview">

</InformationBlock>
<InformationBlock title="At The Mistlock">
</InformationBlock>
</CMInformation>
<IdealRotation>

1.  <Skill name="renewingwave" />
2.  <Skill name="ordersfromabove" />
3.  Take _Mistlock Singularity_
4.  <Skill name="renewingwave" />
5.  <Skill name="ordersfromabove" />
6.  <Skill name="enchanteddaggers" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 1">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. Precast
    1. <Skill name="darkrazorsdaring" /> at 60 Energy
    2. <Skill name="icerazorsire" />
2. <Skill name="surgeofthemists" />
3. <Skill name="chillingisolation" />
4. <Skill name="legendaryassassinstance" />
5. <Skill name="citadelbombardment" />
6. <Skill name="shacklingwave" />
7. <Skill name="deathstrike" />
8. <Skill name="chillingisolation" />
9. <Skill name="legendaryassassinstance" />
10. <Skill name="icerazorsire" />
11. <Skill name="chillingisolation" />
12. <Skill name="citadelbombardment" />
13. <Skill name="chillingisolation" />


</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 2+3">
<InformationBlock>

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="darkrazorsdaring" />
2. <Skill name="icerazorsire" />
3. <Skill name="soulcleavessummit" />
4. <Skill name="ordersfromabove" /> with <Skill name="moastance" />
5. <Skill name="heroiccommand" />
6. <Skill name="surgeofthemists" />
7. <Skill name="legendaryassassinstance" />
8. <Skill name="chillingisolation" />
9. <Skill name="shacklingwave" />
10. <Skill name="deathstrike" />
11. <Skill name="legendaryrenegadestance" />
12. <Skill name="icerazorsire" />
13. <Skill name="chillingisolation" />
14. <Skill name="ordersfromabove" />
15. <Skill name="heroiccommand" />
16. <Skill name="citadelbombardment" />

</IdealRotation>
</Phase>

<Boss name="skorvald" video="lAIxOQlt_jI" timestamp="" videoCreator="Inky" foodId="43360" utilityId="9443" legend1Id="41858" legend2Id="28419" weapon1MainAffix="Berserker" weapon1MainType="Sword" weapon1MainSigil1="Impact" weapon1MainInfusion1Id="37131" weapon1OffAffix="Berserker" weapon1OffType="Sword" weapon1OffSigil="Force" weapon1OffInfusionId="37131" weapon2MainAffix="Berserker" weapon2MainType="Staff" weapon2MainSigil1="Impact" weapon2MainSigil2="Force" weapon2MainInfusion1Id="37131" weapon2MainInfusion2Id="37131">

- Suggested Boon Duration: `35%`

</Boss>

<Phase>
<CMInformation title="Precast">

<InformationBlock title="Overview">

</InformationBlock>
<InformationBlock title="At The Mistlock">
</InformationBlock>
</CMInformation>
<IdealRotation>


1.  <Skill name="renewingwave" />
2.  <Skill name="ordersfromabove" />
3.  Take _Mistlock Singularity_
4.  <Skill name="renewingwave" />
5.  <Skill name="ordersfromabove" />
6.  <Skill name="enchanteddaggers" />


</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 1">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. Precast 
    1. <Skill name="darkrazorsdaring" />
    2. <Skill name="icerazorsire" />
    3. <Skill name="legendarydwarfstance" />
    4. <Skill name="legendaryrenegadestance" />
2. <Skill name="citadelbombardment" />
3. <Skill name="surgeofthemists" />
4. <Skill name="chillingisolation" />
5. <Skill name="shacklingwave" />
6. <Skill name="deathstrike" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Split 1">
<InformationBlock title="Island 1">

</InformationBlock>
<InformationBlock title="Island 2">

</InformationBlock>
<InformationBlock title="Island 3">

</InformationBlock>
<InformationBlock title="Island 4">

</InformationBlock>
</CMInformation>
<IdealRotation>

**Island 1**
1. <Skill name="inspiringreinforcement" />
2. <Skill name="ordersfromabove" />
3. <Skill name="chillingisolation" />

**Island 2**
1. <Skill name="chillingisolation" />
2. <Skill name="heroiccommand" />

**Island 3**
1. <Skill name="inspiringreinforcement" />
2. <Skill name="legendaryrenegadestance" />
1. <Skill name="shacklingwave" />
3. <Skill name="chillingisolation" />

**Island 4**
1. <Skill name="heroiccommand" />
2. <Skill name="ordersfromabove" />
3. <Skill name="citadelbombardment" />
4. <Skill name="chillingisolation" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 2+3">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="icerazorsire" />
2. <Skill name="heroiccommand" />
3. <Skill name="legendarydwarfstance" />
4. <Skill name="chillingisolation" />
5. <Skill name="shacklingwave" />
6. <Skill name="deathstrike" />
7. <Skill name="chillingisolation" />

</IdealRotation>
</Phase>

<Boss name="artsariiv" video="lAIxOQlt_jI" timestamp="68" videoCreator="Inky" foodId="91805" utilityId="9443" legend1Id="41858" legend2Id="28419" weapon1MainAffix="Berserker" weapon1MainType="Sword" weapon1MainSigil1="Impact" weapon1MainInfusion1Id="37131" weapon1OffAffix="berserker" weapon1OffType="Sword" weapon1OffSigil="Force" weapon1OffInfusionId="37131" weapon2MainAffix="Berserker" weapon2MainType="Staff" weapon2MainSigil1="Force" weapon2MainSigil2="Severance" weapon2MainInfusion1Id="37131" weapon2MainInfusion2Id="37131">

- Suggested Boon Duration: `35%`
- Lower boon duration when possible.

</Boss>

<Phase>
<CMInformation title="Precast">

<InformationBlock title="Overview">

</InformationBlock>
<InformationBlock title="At The Mistlock">
</InformationBlock>
</CMInformation>
<IdealRotation>

1. Precast <Boon name="Resistance" /> with <Skill name="painabsorption" />
1.  <Skill name="renewingwave" />
2.  <Skill name="ordersfromabove" />
3.  Take _Mistlock Singularity_
4.  <Skill name="renewingwave" />
5.  <Skill name="ordersfromabove" />
6.  <Skill name="enchanteddaggers" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 1">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. Precast
    1. <Skill name="darkrazorsdaring" />
    2. <Skill name="icerazorsire" />
    3. <Skill name="legendarydwarfstance" />
2. <Skill name="citadelbombardment" />
3. <Skill name="chillingisolation" />
4. <Skill name="legendaryrenegadestance" />
5. <Skill name="shacklingwave" />
6. <Skill name="deathstrike" />
7. <Skill name="unrelentingassault" />
8. Weapons Swap

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Split 1">
<InformationBlock>

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="darkrazorsdaring" />
2. <Skill name="surgeofthemists" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 2+3">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="ordersfromabove" />
2. <Skill name="heroiccommand" />
3. <Skill name="icerazorsire" />
4. <Skill name="shacklingwave" />
5. <Skill name="chillingisolation" />+
6. <Skill name="deathstrike" />
7. <Skill name="legendarydwarfstance" />
7. <Skill name="inspiringreinforcement" />
8. <Skill name="unrelentingassault" />
9. <Skill name="citadelbombardment" />
10. <Skill name="chillingisolation" />
11. <Skill name="heroiccommand" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Split 2">
<InformationBlock>

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="Winters Bite"/> (Axe 3)
2. <Skill id="45743"/> (F2)
3. <Skill name="Point Blank Shot"/> (Longbow 4)

</IdealRotation>
</Phase>

<Boss name="arkk" video="lAIxOQlt_jI" timestamp="133" videoCreator="Inky [dT]" foodId="43360" utilityId="50082" legend1Id="41858" legend2Id="28134" weapon1MainAffix="Berserker" weapon1MainType="Sword" weapon1MainSigil1="Impact" weapon1MainInfusion1Id="37131" weapon1OffAffix="Berserker" weapon1OffType="Sword" weapon1OffSigil="Force" weapon1OffInfusionId="37131" weapon2MainAffix="Berserker" weapon2MainType="Staff" weapon2MainSigil1="Force" weapon2MainSigil2="Severance" weapon2MainInfusion1Id="37131" weapon2MainInfusion2Id="37131">
  

- Suggested Boon Duration: `35%`
- If <Instability name="No Pain, No Gain"/> is present remember to take <Item id="33756"/> on Staff.

</Boss>

<Phase>
<CMInformation title="Precast">

<InformationBlock title="Overview">

</InformationBlock>
<InformationBlock title="At The Mistlock">
</InformationBlock>
</CMInformation>
<IdealRotation>

1.  <Skill name="renewingwave" />
2.  <Skill name="ordersfromabove" />
3.  Take _Mistlock Singularity_
4.  <Skill name="renewingwave" />
5.  <Skill name="ordersfromabove" />
6.  <Skill name="enchanteddaggers" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 1 100%-80%">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="icerazorsire" />
2. <Skill name="chillingisolation" />
2. <Skill name="legendaryassassinstance" />
3. <Skill name="citadelbombardment" />
4. <Skill name="shacklingwave" />
5. <Skill name="deathstrike" />
6. <Skill name="chillingisolation" />
7. Weapon Swap

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 2 80%-70%">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

2. <Skill name="icerazorsire" />
3. <Skill name="surgeofthemists" />
4. <Skill name="ordersfromabove" />
5. <Skill name="citadelbombardment" />
6. <Skill name="chillingisolation" />
7. <Skill name="shacklingwave" />
8. <Skill name="deathstrike" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Archdiviner">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="chillingisolation" />
2. <Skill name="heroiccommand" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 3 70%-50%">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="icerazorsire" />
3. <Skill name="ordersfromabove" />
2. <Skill name="legendaryassassinstance" />
5. <Skill name="chillingisolation" />
4. <Skill name="citadelbombardment" />
5. <Skill name="shacklingwave" />
6. <Skill name="deathstrike" />
7. <Skill name="legendaryrenegadestance" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 4 50%-40%">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="icerazorsire" />
2. <Skill name="surgeofthemists" />
3. <Skill name="ordersfromabove" />
4. <Skill name="heroiccommand" />
5. <Skill name="chillingisolation" />
6. <Skill name="shacklingwave" />


</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Gladiator">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="chillingisolation" />
2. <Skill name="deathstrike" />
3. <Skill name="heroiccommand" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 5 40%-30%">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="icerazorsire" />
2. <Skill name="ordersfromabove" />
2. <Skill name="legendaryrenegadestance" />
5. <Skill name="chillingisolation" />
4. <Skill name="citadelbombardment" />
5. <Skill name="shacklingwave" />
6. <Skill name="deathstrike" />
7. <Skill name="legendaryrenegadestance" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 6 30%-0%">
<InformationBlock title="Overview">

</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="soulcleavessummit" />
2. <Skill name="icerazorsire" />
3. <Skill name="heroiccommand" />
4. <Skill name="legendaryassassinstance" />
5. <Skill name="chillingisolation" />
4. <Skill name="citadelbombardment" />
5. <Skill name="shacklingwave" />
6. <Skill name="deathstrike" />
</IdealRotation>
</Phase>

