## Rolling A Check
A d20 check is required when a PC chooses to take an action and:

- the overall outcome of that action is uncertain
- the PC is able to meaningfully influence that outcome
- there are consequences for failing to achieve that outcome

> [!warning|noicon] If there are no consequences for failure, even for a difficult challenge, there is no reason to make a check, as a PC could reattempt it over and over again until they succeed.

To perform a d20 check (*often simply referred to as 'a check'*):

1. The PC describes the action they wish to perform, their intended goal and what approach they will take to manifest that outcome.
2. Assuming the action requires a check, the DM determines what the [[101 D20 Mechanics#Target Number (TN)|target number]] (*TN*) will be (*otherwise, narration continues as normal*).
3. The DM informs the PC of the TN, including the consequences of failing the check, if they would be obvious to the PC prior to taking the action.

> [!tip|noicon] The DM may choose to hide the TN in some instances (*i.e. combat*) in order to improve immersion and gameplay enjoyment. 

4. Providing the PC still wishes to proceed, they determine which [[101 D20 Mechanics#Proficiency Dice|proficiency die]] to roll, based on their chosen action (*and DM guidance*).
5. Anyone in the party may then spend their [[104 Motivations#122 Inspiration|inspiration]] to grant [[101 D20 Mechanics#Advantage & Disadvantage|advantage]] to the PC making the check (*more than once if desired*).
6. Finally, the PC may activate [[201 Character Creation#Powers|powers]] or utilise [[106 Inventory#Equipping Gear|equipment]], triggering effects that fundamentally alter their check (*i.e. increasing the rank of their proficiency die*).
7. Once all steps are complete, the PC rolls the d20 along with their proficiency die. They add the values shown on the dice together, and inform the DM of their total result.
8. The DM will then compare the PC's result to the target number. If it is equal to or greater than the TN, the PC succeeds at the check, and achieves their goal.
<br />
$$
d20 + Proficiency => TN
$$
<br />

Based on the proficiency involved (*and any powers used*), the DM will narrate the outcome of the action, including any consequences caused by failing to reach the TN.

> [!tip|noicon] Certain action types have clear mechanical effects that apply when a check is succeeded or failed (*i.e. casting a spell*). In those instances, the DM may still narrate beyond these designated elements, providing the initial action is carried out as originally intended.

<br />

## Target Number (TN)
When a PC takes an action that requires a check, the chances of successfully performing that action are represented by a target number.

Usually, this value is decided by the DM, evaluating how much difficulty the PC may face and whether there are any other factors that would further increase (*or decrease*) the overall likelihood of succeeding the check.

<br />

|                 | **TN** |                                                        |
| :-------------: | :----: | :----------------------------------------------------- |
|   **Routine**   |   5    | *Commonfolk can achieve this on a regular basis*       |
| **Challenging** |   10   | *A task difficult to accomplish without concentration* |
| **Adventurous** |   15   | *Training and skill are often required to succeed*     |
|   **Heroic**    |   20   | *The pinnacle of natural effort and mental accuity*    |
|  **Legendary**  |   25   | *Once in a lifetime feats inspiring myth and bardsong* |
|   **Godlike**   |   30   | *Labours unsuitable for those of mortal heritage*      |
<br />

Alternatively, a target number may be provided by other sources, depending on the action being taken. The most common examples are the [[102 Characteristics#Defences|defensive]] characteristics of an enemy, or the result of a check made by an opponent (*i.e. to win an arm wrestle or public debate*).

<br />

## Proficiency Dice
Almost all categories of action provide the PC with an secondary die to roll when making a check (*alongside the d20*), further improving the likelihood of success. 

Referred to collectively as proficiency dice, many take on an individual moniker, based upon the part of the system they relate to (*i.e. the ability die, the crafting die, the spell die*).

The rank (*size*) of a proficiency die is determined by a variety of factors which are often related to the action's context (*i.e. skill competency, campsite comfort, weapon lethality*).

> [!faq|noicon] Proficiency dice are not influenced by effects that may grant advantage or disadvantage, and do not cause nor alter critical rolls.

<br />

#### Teamwork
When a PC is making a check, other PCs may be able to join in or help them succeed, providing they are able to influence the outcome. 

There are two forms of teamwork:

If multiple PCs can take part in the same action, at the same time (*i.e. pushing a large boulder*), they may attempt a **group** check. Each additional PC rolls (*only*) their proficiency die, combining the values rolled with the original check, to achieve a final result.
<br />
$$
d20 + SUM[Proficiency] => TN
$$
<br />

If only one PC is able to take the action, but other PCs are still able to influence the outcome (*i.e. a PC climbs a ladder, whilst another holds it steady*), they may perform a **supported** check. All PCs involved roll their relevant proficiency die, with the highest value being added to the d20, to achieve a final result.
<br />
$$
d20 + MAX[Proficiency] => TN
$$
<br />

## Advantage & Disadvantage
Certain [[201 Character Creation#Powers|powers]], [[108 Combat#Conditions|conditions]] or [[106 Inventory#Equipping Gear|equipment]] allow a PC to make a check with advantage. Others impose restrictions, causing their checks to be made with disadvantage.

If either of these effects are applied to a check, the PC rolls an additional d20 and compares the values shown across both dice:

If rolling with advantage, the PC may take the highest value as their result.
<br />
$$
MAX[d20] + Proficiency => TN
$$
<br />

If rolling with disadvantage, the PC must take the lowest value as their result.
<br />
$$
MIN[d20] + Proficiency => TN
$$
<br />


> [!success|noicon] These mechanics are 'stackable', meaning a PC may roll more than one additional d20 per check (*if subject to multiple effects*), before determining their result.

It is not possible for both advantage and disadvantage to influence the same check, at the same time. On occasions where opposing effects are applied, they are 'cancelled out' (*on a one-for-one basis*), until only advantage or disadvantage remains, or neither.

<br />

## Critical Rolls
When performing a check, if a PC rolls a 'natural' 20 (*the value on the d20 die, before any modifiers are added*), they gain one [[104 Motivations#122 Inspiration|inspiration]]. This can be spent immediately (*i.e. affecting the check currently in progress*), if there are means and motive to do so.

>[!warning|noicon] A critical roll does not guarantee that a check succeeds (*the total result must still reach the target number*). However, inspiration is always awarded, regardless of the outcome.

<br />

#### Critical Hit
If a PC (*or NPC*) rolls a 'natural' 20 whilst making an attack that causes damage (*reduces HP*), they may immediately spend their inspiration to perform a critical hit.

When a PC triggers a critical hit, the damage that would be dealt to their target is doubled.

> [!warning] Although NPCs cannot gain inspiration, they may still trigger critical hits.

Critical hits are exceptionally dangerous, being the primary cause of PC [[103 Vitality#Death|death]].