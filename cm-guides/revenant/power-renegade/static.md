---
title: Renegade CM Guide
type: static
profession: Revenant
specialization: Renegade
disableBosses:
  - "- LightAi   - DarkAi"
date: 2023-03-21T12:50:48.300Z
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

- Suggested Boon Duration: `20%`.
- Suggested Traits:
  - <Trait name="Lasting Legacy"/> to maintain decent party <Boon name="Might"/> if needed.
  - <Trait name="Vindication"/> to maximize damage on good instability day.
  - <Trait name="Righteous Rebel"/> on bad instability day.
- Increase boon duration if you notice downtime in <Boon name="Alacrity"/>.
-----
- If <Instability name="Social Awkwardness"/> is present you can share <Boon name="Stability"/> at key moment in the fight via <Skill name="Inspiring Reinforcement" />.
  - In this case take <Trait name="SpiritBoon"/> to share a stack whenever you swap to <Skill name="LegendaryDwarfStance" />.
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
Take portal and cast your <Skill name="legendaryrenegadestance" /> summons then double swap back to <Skill name="legendaryrenegadestance" /> to reset your energy.
Precast <Skill name="Soulcleaves Summit" /> and prepare for p1.
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
Burst with <Skill name="citadelbombardment" /> and <Skill name="chillingisolation" /> while swapping to <Skill name="LegendaryAssassinStance" /> enabling <Skill name="impossible odds"/>.<br/>
Fit in another <Skill name="chillingisolation" /> if needed then prepare to kill your add in split.
<br/><br/><br/><br/><br/><br/><br/>
</CMInformation>
<IdealRotation>

1. On Boss (Precasted)
    1. <Skill name="darkrazorsdaring" />
    2. <Skill name="icerazorsire" />
    3. <Skill name="legendaryrenegadestance" />
    4. <Skill name="Soulcleaves Summit" />
2. <Skill name="citadelbombardment" />
3. <Skill name="chillingisolation" />
4. <Skill name="LegendaryAssassinStance" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Split 1">
----
Use <Skill name="deathstrike" /> to teleport to your add and cast <Skill name="shacklingwave" /> apply instant <Condition name="vulnerability"/> on it, then finish the add with <Skill name="chillingisolation" /> if needed.<br/>
Avoid the damaging orange AoE while coming back to mid, prepare for p2.
<InformationBlock title="Tips">
- With <Instability name="Outflanked"/>, move <Skill name="shacklingwave" /> into the start of p2.
- Ask your favourite <Specialization name="Soulbeast"/> to <Skill name="Flame trap"/> your add without <Instability name="Outflanked"/> .
- You can use a portal to get to your add faster instead of walking or using <Skill name="deathstrike" />.
</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="deathstrike" />
2. <Skill name="shacklingwave" />
2. <Skill name="chillingisolation" /> (into p2)

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 2">
----
Share <Boon name="alacrity"/> and <Boon name="might"/>.<br/>
Fit in <Skill name="chillingisolation" /> if possible and swap to <Skill name="LegendaryRenegadeStance" />.<br/>
Cast <Skill name="icerazorsire" /> in the middle of the hitbox and burst with <Skill name="citadelbombardment" /> and <Skill name="chillingisolation" /> inside the hitbox under <Effect name="exposed"/>.
- In need, you can cleave the adds while avoiding any damage with <Skill name="Unrelenting Assault" />.
(Careful to not cripple your <Specialization name="Dragonhunter"/> damage when <Skill name="bindingblade"/> is to be used.)

Cast another <Skill name="chillingisolation" /> if needed and at the end of the phase share <Boon name="might"/>.
Prepare for split.<br/>
</CMInformation>
<IdealRotation>

3. <Skill name="ordersfromabove" />
4. <Skill name="heroiccommand" /> (if needed)
5. <Skill name="LegendaryRenegadeStance" />
6. <Skill name="icerazorsire" />
6. <Skill name="citadelbombardment" />
7. <Skill name="chillingisolation" />
8. <Skill name="heroiccommand" />


</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Split 2">
----
Precast <Skill name="shacklingwave" /> to apply instant <Condition name="vulnerability"/> when the add spawn.<br/>
Cleave it with <Skill name="chillingisolation" /> and some auto attack then use <Skill name="deathstrike" /> to teleport to the boss at the start of the phase.
<InformationBlock title="Tips">
- With <Instability name="Outflanked"/>, move <Skill name="shacklingwave" /> into the start of p3.
- Ask your favourite <Specialization name="Soulbeast"/> to <Skill name="Flame trap"/> your add without <Instability name="Outflanked"/> .
- You can use a portal to get to your add or comeback to the boss faster instead of walking or using <Skill name="deathstrike" />.
</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="shacklingwave" />
2. <Skill name="chillingisolation" />
3. <Skill name="deathstrike" /> (into p3)

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 3">
----
Share <Boon name="alacrity"/> and <Boon name="might"/>.<br/>
Cast <Skill name="icerazorsire" /> in the middle of the hitbox, swap to <Skill name="LegendaryAssassinStance" /> and activate <Skill name="impossibleodds"/> to maximize <Skill name="icerazorsire" /> hits under <Trait name="Swift Termination"/>.<br/><br/>
Burst with <Skill name="citadelbombardment" /> and <Skill name="chillingisolation" /> inside the hitbox under <Effect name="exposed"/>.<br/>
- In need, you can cleave the adds while avoiding any damage with <Skill name="Unrelenting Assault" />.
(Careful to not cripple your <Specialization name="Dragonhunter"/> damage when <Skill name="bindingblade"/> is to be used.)

Fit in another <Skill name="chillingisolation" /> if needed.
</CMInformation>
<IdealRotation>

1. <Skill name="heroiccommand" />
2. <Skill name="ordersfromabove" />
3. <Skill name="icerazorsire" />
4. <Skill name="legendaryAssassinstance" />
6. <Skill name="citadelbombardment" />
7. <Skill name="chillingisolation" />

</IdealRotation>
</Phase>

<Boss name="ensolyss" video="lAIxOQlt_jI" timestamp="344" videoCreator="Inky" foodId="91805" utilityId="50082" legend1Id="41858" legend2Id="28134" weapon1MainAffix="Berserker" weapon1MainType="Sword" weapon1MainSigil1="Impact" weapon1MainInfusion1Id="37131" weapon1OffAffix="Berserker" weapon1OffType="Sword" weapon1OffSigil="Serpentslaying" weapon1OffInfusionId="37131" weapon2MainAffix="Berserker" weapon2MainType="Staff" weapon2MainSigil1="Severance" weapon2MainSigil2="Serpentslaying" weapon2MainInfusion1Id="37131" weapon2MainInfusion2Id="37131">

- Suggested Boon Duration: `20%`.
- Use <Trait name="Righteous Rebel"/>.
- Increase boon duration if you notice significant downtime in <Boon name="Alacrity"/>.
- Make sure a <Specialization name="Soulbeast"/> takes <Skill name="moastance" /> or take `35%` Boon Duration.
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
Precast your <Skill name="legendaryrenegadestance" /> summons when the boss is started.<br/>
Prepare for p1.
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
Precast <Skill name="surgeofthemists" /> before the boss is vulnerable.<br/>
Swap to <Skill name="legendaryassassinstance" /> at or below 10% energy to proc <Trait name="Charged Mists"/>.<br/><br/>
In <Effect name="exposed"/> burst with <Skill name="citadelbombardment" />, <Skill name="chillingisolation" />, <Skill name="shacklingwave" /> and <Skill name="deathstrike" /> under <Skill name="impossible odds"/>.
- Disable <Skill name="impossible odds"/> to fit in another <Skill name="chillingisolation" /> and reactive it to empty your energy fully.

Swap to <Skill name="legendaryrenegadestance" /> after the dome explosion.<br/>
Share <Boon name="Might"/>, <Boon name="Alacrity"/>, cast <Skill name="icerazorsire" /> and <Skill name="chillingisolation" />.<br/>
After the tail swipe burst with <Skill name="citadelbombardment" /> and any available sword skill depending of the % of the boss.

Swap to staff when the boss is phased, and prepare to capture North circle.
<InformationBlock title="Tips">
- You can tank the boss by staying in front of it after the dome explosion while your party go stack behind, watch out for the auto attack (a right handed dagger hit).<br/>By moving inside the hitbox to rejoin your party behind the boss, you will trigger the tail swipe attack which will delay the orange blast AoE by one auto.
</InformationBlock><br/><br/>
</CMInformation>
<IdealRotation>

1. On Boss (Precasted)
    1. <Skill name="darkrazorsdaring" />
    2. <Skill name="icerazorsire" />
2. <Skill name="surgeofthemists" />
4. <Skill name="legendaryassassinstance" />
3. <Skill name="chillingisolation" />
5. <Skill name="citadelbombardment" />
6. <Skill name="shacklingwave" />
7. <Skill name="deathstrike" />
8. <Skill name="chillingisolation" />
9. <Skill name="legendaryrenegadestance" />
14. <Skill name="ordersfromabove" />
15. <Skill name="heroiccommand" />
10. <Skill name="icerazorsire" />
11. <Skill name="chillingisolation" />
12. <Skill name="citadelbombardment" />


</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 2 and 3">
----
<InformationBlock title="Post capture">
When the phase start precast <Skill name="icerazorsire" /> to apply <Condition name="vulnerability"/> along side <Skill name="darkrazorsdaring" />, then wait to see <Skill name="moastance" /> on your buff bar to share <Boon name="alacrity"/>.<br/>
Cast <Skill name="soulcleavessummit" /> and share <Boon name="might"/> when you get 5 stack of Kalla's Fervor.
</InformationBlock>
<InformationBlock title="Phase's">
Precast <Skill name="surgeofthemists" /> and swap to <Skill name="legendaryassassinstance" />.<br/>
In <Effect name="exposed"/> burst with <Skill name="citadelbombardment" />, <Skill name="chillingisolation" />, <Skill name="shacklingwave" /> and <Skill name="deathstrike" /> under <Skill name="impossible odds"/>.
- Disable <Skill name="impossible odds"/> to fit in another <Skill name="chillingisolation" /> and reactive it to empty your energy fully.

Swap to <Skill name="legendaryrenegadestance" /> after the dome explosion.<br/>
Share <Boon name="Might"/>, <Boon name="Alacrity"/>, cast <Skill name="icerazorsire" /> and <Skill name="chillingisolation" />.<br/>
Burst with <Skill name="citadelbombardment" /> and any available sword skill depending of the % of the boss.<br/><br/>
Swap to staff when the boss is phased, and prepare go to North circle for the second capture mini-game.
</InformationBlock>
<InformationBlock title="Tips">
- If you do not play with a <Specialization name="Dragonhunter"/> (<Boon name="Aegis"/>) try to fit <Skill name="unrelentingassault"/> after <Skill name="citadelbombardment" /> to avoid the orange blast AoE.
</InformationBlock><br/><br/>
</CMInformation>
<IdealRotation>

1. Post Capture
    1. <Skill name="darkrazorsdaring" />
    2. <Skill name="icerazorsire" />
    3. <Skill name="ordersfromabove" /> with <Skill name="moastance" />
    4. <Skill name="soulcleavessummit" />
    5. <Skill name="heroiccommand" />
6. <Skill name="surgeofthemists" />
7. <Skill name="legendaryassassinstance" />
8. <Skill name="citadelbombardment" />
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

- Suggested Boon Duration: `35%`.
- Use <Trait name="righteousrebel" />.
- Increase boon duration if you notice downtime in <Boon name="Alacrity"/>.
-----
- Without <Instability name="Outflanked"/> you can share <Boon name="Stability"/> at key moment in the fight via <Skill name="Inspiring Reinforcement" />.
  - In this case take <Trait name="SpiritBoon"/> to share a stack whenever you swap to <Skill name="LegendaryDwarfStance" />.
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
Precast your <Skill name="legendaryrenegadestance" /> summons then double swap back to <Skill name="legendaryrenegadestance" />  to reset your energy.
- With <Instability name="Afflicted"/>, <Instability name="Vengeance"/> or <Instability name="FluxBomb"/> you can cast <Skill name="LegendaryDemonStance" /> skill <Skill name="Pain Absorption" /> while going back to <Skill name="legendaryrenegadestance" />.
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
Cast <Skill name="citadelbombardment" /> and <Skill name="surgeofthemists" /> when the boss becomes attackable.<br/>
Swap to <Skill name="legendarydwarfstance" /> at or below `10%` energy to proc <Trait name="Charged Mists"/>.<br/><br/>
In <Effect name="exposed"/>, burst with <Skill name="chillingisolation" />, <Skill name="shacklingwave" /> and <Skill name="deathstrike" /> under <Skill name="vengefulhammers" />.
<InformationBlock title="Tips">
- If you are not in voice for the starting count down, you can easily determine when to precast
watching the <Specialization name="Soulbeast" /> or <Specialization name="Dragonhunter" /> traps getting highlighted on the ground.
- In a slower party it is higher damage to cast <Skill name="citadelbombardment" /> after <Skill name="surgeofthemists" /> as you can profit from <Trait name="unsuspectingstrikes" /> in <Effect name="Exposed" />.
- At the end of p1 share <Boon name="Might"/> with <Skill name="heroiccommand" /> if the team didn't blast properly.
</InformationBlock>
</CMInformation>
<IdealRotation>

1. On Boss (Precasted) 
    1. <Skill name="darkrazorsdaring" />
    2. <Skill name="icerazorsire" />
    4. <Skill name="legendaryrenegadestance" />
2. <Skill name="citadelbombardment" />
3. <Skill name="surgeofthemists" />
4. <Skill name="legendarydwarfstance" />
4. <Skill name="chillingisolation" />
5. <Skill name="shacklingwave" />
6. <Skill name="deathstrike" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Split 1">
----
<InformationBlock title="Island 1">
Use <Skill name="chillingisolation" /> and share <Boon name="alacrity"/>.
- If your party is missing damage or without <Instability name="outflanked"/>, share <Boon name="stability"/> via <Skill name="inspiringreinforcement"/>.
</InformationBlock>
<InformationBlock title="Island 2">
Instant <Skill name="chillingisolation" /> and share <Boon name="might"/> afterward.<br/>
- Activate <Skill name="vengefulhammers" /> if you have too much energy.<br/>
If you didn't get <Effect name="stealth"/> from your <Specialization name="Scrapper" /> on the first island, share <Boon name="might"/> and jump over the anomaly while resuming the rotation.

</InformationBlock>
<InformationBlock title="Island 3">
Use <Skill name="inspiringreinforcement"/> to provide further <Boon name="stability"/>. Cast <Skill name="shacklingwave" /> to apply instant <Condition name="Vulnerability" /> followed by a <Skill name="chillingisolation" /> if needed.<br/>
- Swap to <Skill name="legendaryrenegadestance" /> going to the next island so that your legend cd is off cool down for p2.

</InformationBlock>
<InformationBlock title="Island 4">
Share <Boon name="might"/> and <Boon name="alacrity"/>.
Without <Instability name="outflanked"/> jump over the anomaly while casting <Skill name="citadelbombardment" /> and take portal to p2.
- If you have more than `50%` energy turn <Skill name="soulcleavessummit" /> on and off.

</InformationBlock>
</CMInformation>
<IdealRotation>

**Island 1**
1. <Skill name="chillingisolation" />
2. <Skill name="ordersfromabove" />
3. <Skill name="inspiringreinforcement" />

**Island 2**
1. <Skill name="chillingisolation" />
2. <Skill name="heroiccommand" />

**Island 3**
1. <Skill name="inspiringreinforcement" />
1. <Skill name="shacklingwave" />
2. <Skill name="legendaryrenegadestance" />

**Island 4**
1. <Skill name="heroiccommand" />
2. <Skill name="ordersfromabove" />
3. <Skill name="citadelbombardment" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 2">
----
Cast <Skill name="icerazorsire" /> to apply <Condition name="Vulnerability" /> and swap to <Skill name="legendarydwarfstance" />.
- Make sure to have `20%` energy at least starting the phase.

In <Effect name="exposed"/> under <Skill name="vengefulhammers" />, burst with <Skill name="chillingisolation" />, <Skill name="shacklingwave" /> and <Skill name="deathstrike" />.
Place your portal and finish the phase by sharing <Boon name="Might" /> and using <Skill name="chillingisolation" /> if needed.
<InformationBlock title="Tips">
- Start your burst with <Skill name="shacklingwave" /> if your party lack <Condition name="Vulnerability" /> application.
</InformationBlock>
</CMInformation>
<IdealRotation>

1. <Skill name="icerazorsire" />
3. <Skill name="legendarydwarfstance" />
4. <Skill name="chillingisolation" />
5. <Skill name="shacklingwave" />
6. <Skill name="deathstrike" />
7. <Skill name="chillingisolation" />
8. <Skill name="heroiccommand" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Split 2">
----
<InformationBlock title="Island 1">
Use <Skill name="chillingisolation" /> and share <Boon name="Alacrity" /> then take portal.
</InformationBlock>
<InformationBlock title="Island 2">
Share <Boon name="might" /> and <Boon name="stability" /> via <Skill name="inspiringreinforcement"/>.<br/>
Use <Skill name="chillingisolation" /> and swap to <Skill name="legendaryrenegadestance" /> before taking portal.
</InformationBlock>
<InformationBlock title="Island 3">
Cast <Skill name="shacklingwave" /> to apply instant <Condition name="Vulnerability" /> on the anomaly.<br/>
Fit in a <Skill name="chillingisolation" /> if needed then take portal.
</InformationBlock>
<InformationBlock title="Island 4">
Open your portal in the hitbox and share <Boon name="Might" /> if needed. Deal moderate damage to the anomaly via <Skill name="chillingisolation" /> and/or <Skill name="deathstrike" /> before taking portal.
- If your party lack damage it is advised to use <Skill name="citadelbombardment" /> while jumping over the anomaly.
</InformationBlock><br/><br/><br/><br/><br/><br/>
</CMInformation>
<IdealRotation>

**Island 1**
1. <Skill name="chillingisolation" />
2. <Skill name="ordersfromabove" />

**Island 2**
1. <Skill name="heroiccommand" />
2. <Skill name="inspiringreinforcement" />
3. <Skill name="chillingisolation" />
4. <Skill name="legendaryrenegadestance" />

**Island 3**
1. <Skill name="shacklingwave" />

**Island 4**
1. <Skill name="heroiccommand" />
2. <Skill name="chillingisolation" />
3. <Skill name="deathstrike" />

</IdealRotation>
</Phase>

<Phase>
<CMInformation title="Phase 3">
----
Share <Boon name="Might" /> and <Boon name="Alacrity" />.<br/>
Cast <Skill name="icerazorsire" /> to apply <Condition name="Vulnerability" /> and swap to <Skill name="legendarydwarfstance" />.<br/><br/>
In <Effect name="exposed"/>, burst with <Skill name="citadelbombardment" /> under <Skill name="vengefulhammers" />.<br/>
Finally use any available sword skills to finish the boss.
- Start your burst with <Skill name="shacklingwave" /> if your party lack <Condition name="Vulnerability" /> application.
- Don't <Skill name="shacklingwave" /> if the boss will instant die as the animation is too slow to be worth.
</CMInformation>
<IdealRotation>

1. <Skill name="heroiccommand" />
2. <Skill name="ordersfromabove" />
1. <Skill name="icerazorsire" />
3. <Skill name="legendarydwarfstance" />
4. <Skill name="citadelbombardment" />
5. <Skill name="shacklingwave" />
7. <Skill name="chillingisolation" />

</IdealRotation>
</Phase>

<Boss name="artsariiv" video="lAIxOQlt_jI" timestamp="68" videoCreator="Inky" foodId="91805" utilityId="9443" legend1Id="41858" legend2Id="28419" weapon1MainAffix="Berserker" weapon1MainType="Sword" weapon1MainSigil1="Impact" weapon1MainInfusion1Id="37131" weapon1OffAffix="berserker" weapon1OffType="Sword" weapon1OffSigil="Force" weapon1OffInfusionId="37131" weapon2MainAffix="Berserker" weapon2MainType="Staff" weapon2MainSigil1="Force" weapon2MainSigil2="Severance" weapon2MainInfusion1Id="37131" weapon2MainInfusion2Id="37131">

- Suggested Boon Duration: `35%`.
- Use <Trait name="righteousrebel" />.
- Increase boon duration if you notice downtime in <Boon name="Alacrity"/>.
-----
- Swap to <Item name="celerity" /> on Staff if you notice a drop in <Boon name="Quickness" />.
- Precast <Boon name="Resistance"/> via <Skill name="LegendaryDemonStance" /> skill <Skill name="Pain Absorption" />.

</Boss>

<Phase>
<CMInformation title="Precast">
----
<InformationBlock title="At the Mistlock">
Share <Boon name="Alacrity"/> and blast the fire field to gain <Boon name="Might"/>.<br/>
If you are on fire field duty use <Skill name="Soulcleaves Summit" />. Finally swap to <Skill name="LegendaryAssassinStance"/> to invoke your <Skill name="enchanted daggers"/> and swap back to <Skill name="legendaryrenegadestance" />.
</InformationBlock>
<InformationBlock title="On Boss">
Precast your <Skill name="legendaryrenegadestance" /> summons then swap to <Skill name="legendaryassassinstance" />.
<InformationBlock title="Tips">
- You can precast <Boon name="Resistance"/> via <Skill name="LegendaryDemonStance" /> skill <Skill name="Pain Absorption" />.
- Cast <Skill name="inspiringreinforcement" /> if your <Specialization name="Scrapper" /> doesn't precast <Skill name="defensefield" /> to share <Boon name="Stability" />.
</InformationBlock>
</InformationBlock>
</CMInformation>
<IdealRotation>


1.  <Skill name="renewingwave" />
2.  <Skill name="ordersfromabove" />
3.  Take _Mistlock Singularity_
4.  <Skill name="renewingwave" />
5.  <Skill name="ordersfromabove" />
6.  <Skill name="enchanteddaggers" />
----
1. <Skill name="Pain Absorption" />
2. <Skill name="legendarycentaurstance" />
3. <Skill name="Pain Absorption" /> (repeat)

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

