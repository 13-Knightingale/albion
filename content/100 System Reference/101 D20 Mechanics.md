## Rolling A Check
A d20 check is required when a PC chooses to take an action and:

- the overall outcome of that action is uncertain
<br />

- the PC is able to meaningfully influence that outcome
- there are consequences for failing to achieve that outcome

> [!warning|noicon] If there are no consequences for failure, even for a difficult challenge, there is no reason to make a check, as a PC could reattempt it over and over again until they succeed.

To perform a d20 check (*often simply referred to as 'a check'*):

1. The DM determines what the [[101 D20 Mechanics#Target Number (TN)|target number]] (*TN*) for the check will be.
   *The DM does not necessarily need to reveal it at this stage*
<br />

2. The DM and PC determine which [[101 D20 Mechanics#Proficiency Dice|proficiency die]] to roll, based on factors such as the action chosen, desired outcome and the approach taken to manifest it.
3. The PC (*or any of their allies*) may spend their inspiration to grant themselves [[101 D20 Mechanics#Advantage & Disadvantage|advantage]] on the check (*they may spend more than one if desired*).
4. Finally, the PC may activate powers, utilise equipment or trigger other effects that cause fundamental alterations to their check (*i.e. increasing the rank of their proficiency die*).
5. Once all steps are complete, the PC rolls the d20 along with their proficiency die. They add the values shown on the dice together, and inform the DM of their total result.
6. The DM will then compare the PC's result to the target number. If it is equal to or greater than the TN, the PC succeeds at the check. 
<br />

$$
d20 + Proficiency => TN
$$

Based on the proficiency involved (*and any powers used*), the DM will narrate the outcome of the action, including any consequences caused by failing to reach the TN.

> [!tip|noicon] Certain action types have clear mechanical effects that apply when a check is succeeded or failed (*i.e. casting a spell*). In those instances, the DM may still narrate beyond these designated elements, providing the initial action is carried out as originally intended.

## Target Number (TN)
When a PC takes an action that requires a check, the chances of successfully performing that action are represented by a target number.

Usually, this value is decided by the DM, evaluating how much difficulty the PC may face and whether there are any other factors that would further increase (*or decrease*) the overall likelihood of succeeding the check.

Alternatively, a target number may be provided by other sources, depending on the action being taken. The most common examples are the defensive characteristics of an enemy, or the result of an check made by an opponent (*i.e. to win an arm wrestle or public debate*).

|                 | **TN** |                                                        |
| :-------------: | :----: | :----------------------------------------------------- |
|   **Routine**   |   5    | *Commonfolk can achieve this on a regular basis*       |
| **Challenging** |   10   | *A task difficult to accomplish without concentration* |
| **Adventurous** |   15   | *Training and skill are often required to succeed*     |
|   **Heroic**    |   20   | *The pinnacle of natural effort and mental accuity*    |
|  **Legendary**  |   25   | *Once in a lifetime feats inspiring myth and bardsong* |
|   **Godlike**   |   30   | *Labours unsuitable for those of mortal heritage*      |
## Proficiency Dice
Almost all categories of action provide the PC with an secondary die to roll when making a check (*alongside the d20*), further improving the likelihood of success. 

Referred to collectively as proficiency dice, many take on an individual moniker, based upon the part of the system they relate to (*i.e. the initiative die, the crafting die, the spell die*).

The rank (*size*) of a proficiency die is determined by a variety of factors which are often related to the action's context (*i.e. skill competency, campsite comfort, weapon lethality*).

> [!faq|noicon] Proficiency dice are not influenced by effects that may grant advantage or disadvantage, and do not cause nor alter critical boons or banes.
#### Teamwork
When a PC is making a check, other PCs may be able to join in or help them succeed, providing they are able to influence the outcome of the check (*as determined by the DM*).

This can be done in one of two ways:

A ***group*** check occurs when many PCs can take part in the same action, at the same time (*i.e. pushing a large boulder*). One PC is nominated as the 'leader', and rolls their check as normal, whilst every other PC involved (*i.e. helping push*) only rolls their relevant proficiency die. The values of all these proficiency dice are added together, and combined with the leader's check, to achieve a final result.
<br />

$$
d20 + SUM[Proficiency] => TN
$$
<br />

A ***supported*** check occurs when only one PC is able to take the action, but other PCs may take secondary actions that could help improve the primary check (*i.e. a PC climbs a ladder, whilst others hold it steady*). All supporting PCs roll their proficiency die, and if any of their values are greater than the proficiency die rolled in the primary check, the PC making the primary check may choose to use the higher value instead.
<br />

$$
d20 + MAX[Proficiency] => TN
$$<br />

## Advantage & Disadvantage
Certain powers, conditions, or equipment allow a PC to make a check with advantage. Others impose restrictions, causing their checks to be made with disadvantage.

If either of these effects are applied to a check, the PC rolls an additional d20 and compares the values shown across both dice:
- If rolling with advantage, the PC may take the highest value as their result

$$
MAX[d20] + Proficiency => TN
$$

- If rolling with disadvantage, the PC must take the lowest value as their result

$$
MIN[d20] + Proficiency => TN
$$


> [!success|noicon] These mechanics are 'stackable', meaning a PC may roll more than one additional d20 per check (*if subject to multiple effects*), before determining their result.

It is not possible for both advantage and disadvantage to influence the same check, at the same time. On occasions where opposing effects are applied, they are 'cancelled out' (*on a one-for-one basis*), until only advantage or disadvantage remains, or neither.

## Critical Rolls
When performing a check, if a PC rolls a 'natural' 20 (*the value on the d20 dice, before any modifiers are added*), they receive a critical boon. When this occurs, the PC gains one [[103 Motivations#122 Inspiration|inspiration]]. 

Rolling a 'natural' 1 is known as a critical bane. In these cases, the DM gains one [[103 Motivations#123 Despair|despair]].

Certain checks may also trigger additional beneficial effects if a critical boon is rolled, or potential negative consequences on a critical bane (*these will be explicitly noted*).

>[!warning|noicon] A critical boon does not guarantee that a check succeeds (*the total result must still reach the target number*). However, inspiration is still awarded, regardless of the the outcome. Likewise, even if a PC succeeds a check with a natural 1, the DM will recieve despair.

#### Critical Hit
A special type of critical boon occurs during [[108 Combat#173 Making An Attack|combat]]. When a PC (*or NPC*) make an attack that causes damage, rolling a 'natural' 20 is known as a critical hit.

When a PC achieves a critical hit, they may choose to forgo receiving inspiration, and instead, double the damage that would be dealt to their target from that attack.

As NPCs cannot gain inspiration, the DM must always choose to increase their damage.

Critical Hits are exceptionally dangerous, being the primary cause of PC [[104 Vitality#Death|death]].