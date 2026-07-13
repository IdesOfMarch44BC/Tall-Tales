# Combat and Wounds

## The Shape of a Fight

Combat runs on the surge-and-Momentum engine described in *How the Game Works*; this chapter covers what happens when someone tries to hurt someone else. The loop is short: **attack** (do you hit?), **save** (does armor stop it?), and **wound** (what did it do, and where?).

A character is not a reservoir of health that drains. A character is a body that accumulates specific injuries until one of them stops them. You always know exactly what is wrong with you, a fight can turn on a single roll, and the difference between a scratch and a killing blow is which part of the body the strike found and how hard it landed. Fights are quick and consequential. The wound tables are where the consequences live.

------------------------------------------------------------------------

## Attacking

### To Hit

Your **Strike** (melee) and **Shoot** (ranged) are **target numbers**: the value each die must meet or beat to land a hit. A lower number is better. Weapons modify the number they are used with — a fine dueling pistol might grant Shoot –1; an unbalanced club, Strike +1.

To attack:

1.  Start with the weapon’s **Attack Dice** and apply bonuses or penalties to the attacker.

2.  Subtract the target’s **Defend**, including any cover bonus, from that pool.

3.  The final pool is a minimum of 1 die unless an effect says the attack cannot be attempted. Roll; each die meeting Strike or Shoot is a **hit**.

Defend subtracts dice rather than raising your target number. A well-defended foe shrinks your pool, so even an expert’s volley comes up thin against them; you overcome Defend through more attacks, larger pools, or effects that ignore it, never by needing better rolls. A pool reduced to its minimum of 1 die can still land a hit. No one is ever wholly untouchable.

### Damage and Severity

Each hit deals the weapon’s **Damage**, plus a bonus for every wound the target already carries:


|                                  |               |
|:---------------------------------|:--------------|
| **Each existing minor wound**    | +1 damage |
| **Each existing moderate wound** | +2 damage |
| **Each existing major wound**    | +4 damage |


An unhurt body absorbs blows that would fell a wounded one; a hurt body takes every new strike harder. A character carrying one major and two minor wounds suffers +6 damage before the attacking weapon’s own Damage is added. This is how a fight tips: slowly, then all at once.

Compare the damage total to the target’s two thresholds, which are set by class, deeds, and equipment:


| **Damage total**                          | **Severity** |
|:------------------------------------------|:-------------|
| Below Moderate threshold                  | **Minor**    |
| Moderate threshold or higher, below Major | **Moderate** |
| Major threshold or higher                 | **Major**    |


**Multiple hits.** Resolve hits from one attack one at a time in the attacker’s chosen order. Each wound that gets through can increase the damage of later hits from that attack. Roll Armor and Negation separately for every hit.

**Direct Damage.** A power or hazard written **Damage N Type** creates one automatic hit with Damage N of the named type; do not roll Strike or Shoot, but do add the target’s existing-wound bonus and allow applicable Armor and Negation. If the type is omitted, use the source’s obvious type. Damage voluntarily accepted as a printed cost bypasses saves. Damage from an ongoing status also bypasses saves after the wound that created it has already passed them.

**Bonuses and penalties.** “+1 die” changes the Attack Dice pool; “+1 Damage” changes Damage; “Strike –1” or “Shoot –1” improves a target number. Never use “+1 to hit” without saying whether it changes dice or the target number.

**Nonlethal attacks.** Before rolling an attack with an appropriate weapon, lose 1 Attack Die to declare it nonlethal. If its wound result would inflict Death, inflict Dying instead. Other effects, including maiming, still occur. An effect that permits nonlethal attacks “at no penalty” removes the lost die.

**Called shots.** Spend +1 Momentum and lose 1 Attack Die before rolling to name Head, Torso, one Arm, or one Leg. Every hit from that attack uses the named location instead of rolling d6. A called shot cannot also be nonlethal unless an effect explicitly permits both.

**Grapple and shove.** Spend 1 Momentum while adjacent and roll Athletics opposed by the target’s Athletics or Nimbleness. On a grapple success, the target becomes Grappled; the holder may drag them at half Move but also loses half Move. On a shove success, push the target 2" or make it prone. Size and traits modify these rolls where stated.

### Worked Attack

A Captain with **Shoot 3+** fires a revolver (**3 Attack Dice, Damage 4**) at a target with **Defend 1**, **Moderate 4**, **Major 8**, one existing minor wound, and riding leathers (**Armor 5+**).

1. The revolver’s 3 dice become 2 after Defend.
2. The dice show 3 and 5; both meet Shoot 3+, so the attack scores two hits.
3. Resolve the first hit. Damage 4 + 1 for the existing minor wound = 5, a moderate wound.
4. The target rolls Armor. On 5+, the hit stops. Otherwise roll location and the moderate Pierce effect, then record the wound.
5. Resolve the second hit afterward. If the first became a recorded moderate wound, the existing-wound bonus is now +3 total, so the second hit deals Damage 7.

This order is why a volley can turn sharply after its first wound gets through.

------------------------------------------------------------------------

## Armor and Negation

Before a wound takes effect, armor gets its say. Armor is written **X+/Y+**:

- **X+ is the Armor save** — common protection: plate, hide, grown bone, chassis.

- **Y+ is the Negation save** — rare protection: warding, spagyric resilience, the defense that should not have held and did.

When you take a wound — after severity is known, before location — determine which saves apply:

- Against **common damage** (Pierce, Slash, Blunt, Burn, Blast, Cold, Acid, Electricity, Toxic), roll Armor if worn and Negation if possessed.
- Against **planar damage** (Heavens, Machine, Shadow, Wild, Wyrd), ordinary Armor does not apply; roll Negation only.

A success on any applicable save stops the wound entirely: no location, effect, or stacking. An effect may explicitly bypass or permit a different save.

**Armor-Piercing (AP Z)** worsens the **Armor save** by Z. An Armor save of 3+ against an AP 2 weapon becomes 5+. Armor-Piercing does not affect the Negation save — that is the save armor-piercing cannot answer, and the reason Negation is prized. A save worsened past 6+ fails automatically.

An effect that **improves Armor by N** lowers the save target by N. A creature with no Armor treats its starting value as 7+, so improving Armor by 1 grants 6+ and improving it by 2 grants 5+. Armor can never improve beyond 2+. An effect that strips or worsens Armor raises the target number and can remove it entirely.

Severity does not change the save; a hit either gets through armor or it does not. Severity decides how bad the wound is once armor has failed. Heavy armor means you are wounded seldom, not gently.

------------------------------------------------------------------------

## The Wound Roll

If no save stops the wound, roll **1d6** for location and **1d4** for effect, then read the table for the attack’s damage type at the wound’s severity.


| **d6** | **Location** |
|:-------|:-------------|
| 1      | Head         |
| 2      | Torso        |
| 3      | Right Arm    |
| 4      | Left Arm     |
| 5      | Right Leg    |
| 6      | Left Leg     |


Record every wound with its severity, type, and location. Each one changes what the body can do and adds to the damage of the next hit.

If a result says **treat as a lower-severity wound**, or simply names a lower-severity wound, keep the location and reroll the effect on that type’s lower-severity table. Apply any additional effect stated after that instruction. Continue if the new result lowers severity again; record only the final severity plus applicable effects.

### Statuses

Wound effects apply statuses. Resolve start-of-surge statuses before reloading or rolling Momentum.

| Status | Rule |
|:--|:--|
| **Disabled** | You cannot take actions. Clear it only by the method named by the effect, usually spending 1 Momentum or receiving aid. |
| **Dazed** | Lose 1 die from your next action. Spending 1 Momentum clears Dazed before that action. Multiple Dazed effects do not stack. |
| **Fatigued** | Lose 1 die on physical Skill rolls and 1" Move. Rest or an effect that clears fatigue ends it. |
| **Bleeding (N)** | At the start of your side’s surge, take Damage N of the wound’s type. Spending 1 Momentum, adjacent aid, or Sawbone care staunches it unless the wound says otherwise. Use the highest Bleeding value rather than adding them. |
| **Burning (N)** | At the start of your side’s surge, take Damage N Burn. Spending 1 Momentum to smother it, adjacent aid, or immersion ends it. It may ignite nearby flammables when the fiction supports it. |
| **Suffocating (N)** | At the start of your side’s surge, take Damage N Toxic, bypassing saves, then increase N by 1. Breathing freely ends Suffocating immediately. A conscious creature can normally hold its breath for rounds equal to Athletics (minimum 1) before gaining Suffocating (1); an effect that says a creature begins to drown skips that grace period. |
| **Prone** | Attacks from adjacent creatures gain +1 Attack Die; ranged attacks from farther than 6" lose 1 Attack Die. Standing costs 1 Momentum and 2" of Move. |
| **Grappled** | Move 0. Escape with a 1-Momentum Athletics or Nimbleness action opposed by the holder’s Athletics. The holder may release you freely during any surge. |
| **Blinded** | Your attacks lose 2 Attack Dice; sight-based actions fail unless another sense can replace sight. Attackers gain +1 Attack Die against you. |
| **Surprised** | You cannot use Reactions. Surprised ends when your side begins its first surge or an effect alerts you sooner. |
| **Dying** | You are prone, Disabled, and will die at the end of your side’s next surge unless stabilized. Stabilization removes Dying but does not close the wound. |
| **Death** | You are dead immediately. Only an effect that explicitly changes a Death result can intervene. |

**Clearing effects.** Many minor and moderate effects last *until you spend 1 Momentum* — wiping blood from your eyes, tearing free of a weapon, shaking the ring from your ears. That clearing is an action costing 1 Momentum from your side. Closing a wound itself, rather than merely its effect, requires Sawbone powers, aid, or downtime.

### Recovery

Powers and care grant **Recovery N**. Spend those points immediately on one target; Recovery cannot be banked.

| Cost | Recovery effect |
|:--:|:--|
| 1 | Clear one transient effect that could normally be cleared by spending Momentum. |
| 2 | Close one minor wound. |
| 3 | Reduce one wound one step: major → moderate, moderate → minor, or minor → closed. |

Recovery does not remove Dying unless the effect also says **stabilize**, cannot reverse Death, and cannot restore a permanently lost body part without an effect that explicitly says it can. Unspent points from one Recovery effect are lost.

When Recovery reduces an existing wound, end that wound’s nonpermanent ongoing effects and record it at the new severity; do not roll a new effect. When a Reaction reduces an incoming wound before it finishes resolving, keep its type and location but roll a new effect on the lower-severity table.

**Rest and downtime.** At the encounter’s end, effects lasting “for the scene” end, but recorded wounds remain. A safe full night’s rest grants Recovery 2 once per day. A week of downtime with proper care reduces one wound one step. Major wounds and effects labeled lingering require trained care for that downtime reduction. Permanent maiming never recovers through time alone.

**Urgent care.** A result marked “permanent maiming without care” becomes permanent if trained treatment has not begun by the end of the victim’s next safe full rest, roughly 24 hours. Stabilization alone is not trained treatment. If care begins in time, the wound remains major or lingering and follows the normal downtime rules, but the threatened body part is not permanently lost.

### Troops, Frames, and Objects

Simple units and destructible objects use **Durability** instead of wounds. A standard troop profile is **Durability / Attack / Defend / Move**. Unless its power says otherwise, a troop rolls its Attack dice at **4+**, deals **Damage 3** of an appropriate type on each hit, and has no Armor or Negation.

For a Skill action or Alignment save not covered by its profile, a standard troop rolls **2 dice at 4+** and normally needs 1 success; use 1 die for an untrained or unreliable unit and 3 dice for a specialist. When circumstances call for morale—heavy losses, supernatural terror, an impossible order—the troop uses this same pool. On failure it is **routed**: it cannot attack and must use movement to seek safety. A controller may spend 1 Momentum and succeed on a 1-success Convince or Intimidate action to rally a routed troop within 10". A troop immune to fear or routing ignores morale tests.

Each unprevented weapon hit removes **1 Durability** from a simple unit; Direct Damage removes Durability equal to its Damage. At 0 Durability, the troop is defeated, the frame is disabled, or the object breaks as the fiction requires. Recovery restores Durability point for point only when an effect says it repairs or restores that kind of target. Named, important NPCs use the full wound rules.

The character who deployed a troop controls it unless the power says otherwise. Moving or attacking with one troop costs 1 Momentum. **Troop ×2** deploys two separate units, and each pays for its own actions. Using a Troop power deploys the unit within 2" of its controller but does not grant a free action. Defeated troops re-muster between encounters only when their power says they do.

------------------------------------------------------------------------

## Wound Tables: Pierce

*Bullets, arrows, thrusts, fangs, spines. Pierce stops and drops; through a small hole it finds what matters, and to the head or heart it kills.*

### Minor Pierce

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Glancing Hit.** No further effect. |
| Head | 3 | **Stuck.** You are grappled (melee) or dazed (ranged) until you spend 1 Momentum to get free of the weapon or line of fire. |
| Head | 4 | **Blinded.** You are blinded until you spend 1 Momentum to wipe the blood away. |
| Torso | 1–2 | **Glancing Hit.** No further effect. |
| Torso | 3 | **Winded.** Your next action this scene costs 1 additional Momentum. |
| Torso | 4 | **Stuck.** The weapon or bolt fouls you: –1 die on attacks until you spend 1 Momentum to clear it. |
| Arm *(Right or Left per the roll — note which; it matters for what you hold.)* | 1–2 | **Glancing Hit.** No further effect. |
| Arm *(Right or Left per the roll — note which; it matters for what you hold.)* | 3 | **Numbed.** –1 die on rolls using that arm until you spend 1 Momentum to shake it out. |
| Arm *(Right or Left per the roll — note which; it matters for what you hold.)* | 4 | **Fumbled.** You drop what that hand holds unless you spend 1 Momentum to keep your grip. |
| Leg | 1–2 | **Glancing Hit.** No further effect. |
| Leg | 3 | **Limping.** –2" Move until you spend 1 Momentum to walk it off. |
| Leg | 4 | **Staggered.** You cannot move during your side’s next surge unless you spend 1 Momentum. |

### Moderate Pierce

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Grazed.** Treat as a minor piercing wound (reroll on the Minor Head table). |
| Head | 2 | **Pierced.** No further effect. |
| Head | 3–4 | **Head Injury.** Gain an additional minor piercing wound with no wound effect (it still stacks damage). |
| Torso | 1 | **Grazed.** Treat as a minor piercing wound. |
| Torso | 2 | **Punched Through.** No further effect. |
| Torso | 3 | **Winded Hard.** –1 die on all rolls until you spend 1 Momentum to catch your breath. |
| Torso | 4 | **Bleeding.** Bleeding (1) until staunched. |
| Arm | 1 | **Grazed.** Treat as a minor piercing wound. |
| Arm | 2 | **Through the Meat.** No further effect. |
| Arm | 3 | **Weakened.** –1 die on all rolls using that arm for the rest of the scene (Momentum does not clear it; Recovery that reduces the wound does). |
| Arm | 4 | **Dropped and Fouled.** You drop what the hand holds and cannot use that arm until you spend 1 Momentum to pull the weapon free. |
| Leg | 1 | **Grazed.** Treat as a minor piercing wound. |
| Leg | 2 | **Through the Muscle.** No further effect. |
| Leg | 3 | **Hobbled.** –3" Move for the rest of the scene. |
| Leg | 4 | **Pinned.** You cannot move until you spend 1 Momentum to tear free, and drop prone if the shot was ranged. |

### Major Pierce

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Barely Ducked.** Pained, scarred, and disabled until you spend 1 Momentum to clear the disabled; then treat as a moderate piercing wound. |
| Head | 2 | **Dropped.** The round takes you off your feet: prone, disabled, and Dying. |
| Head | 3–4 | **Headshot.** Death. |
| Torso | 1 | **Cracked.** Treat as a moderate piercing wound, and you are disabled until you spend 1 Momentum. |
| Torso | 2 | **Punctured Lung.** Bleeding (2) and disabled; if the Bleeding is not stopped, Dying. |
| Torso | 3 | **Gut-Shot.** Prone, disabled, and Dying. |
| Torso | 4 | **Through the Heart.** Death. |
| Arm | 1 | **Shattered Joint.** Treat as a moderate piercing wound; that arm is useless until aid. |
| Arm | 2 | **Maimed.** The arm is crippled for the rest of the scene and drops everything; without proper care it is a permanent maiming. |
| Arm | 3 | **Pinned Through.** You are grappled in place (or to a surface behind you) and disabled until freed by spending 2 Momentum or by an ally. |
| Arm | 4 | **Torn Away.** The wound wrecks the arm and opens an artery: the limb is lost (permanent maiming), and you are Dying. |
| Leg | 1 | **Buckled.** Treat as a moderate piercing wound, and you fall prone. |
| Leg | 2 | **Crippled.** Move becomes 0 and you are prone until aid; without proper care it is a permanent maiming. |
| Leg | 3 | **Pinned.** Prone and grappled in place; disabled until freed by spending 2 Momentum or by an ally. |
| Leg | 4 | **Femoral.** The leg is wrecked and the great vein is open: the limb is lost (permanent maiming), prone, and you are Dying. |

## Wound Tables: Slash

*Sabers, hatchets, claws, glass, saw-edged frontier steel. Slash opens and bleeds; to a limb it takes the limb, and to the head or throat it is as final as any bullet.*

### Minor Slash

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Nicked.** No further effect. |
| Head | 3 | **Blood in the Eyes.** Blinded until you spend 1 Momentum to wipe it clear. |
| Head | 4 | **Ear or Scalp.** Loud and bloody: –1 die on Perceive (hearing) until you spend 1 Momentum to clear your head. |
| Torso | 1–2 | **Nicked.** No further effect. |
| Torso | 3 | **Opened.** A shallow cut: –1 die on Athletics-based actions until you spend 1 Momentum. |
| Torso | 4 | **Bleeding Light.** Bleeding (1) until you spend 1 Momentum; it clots readily. |
| Arm | 1–2 | **Nicked.** No further effect. |
| Arm | 3 | **Cut Tendon.** –1 die with that arm until you spend 1 Momentum to adjust your grip. |
| Arm | 4 | **Slashed Grip.** You drop what the hand holds unless you spend 1 Momentum. |
| Leg | 1–2 | **Nicked.** No further effect. |
| Leg | 3 | **Hamstrung Lightly.** –2" Move until you spend 1 Momentum. |
| Leg | 4 | **Cut Across the Shin.** –1 die on Move-based rolls until you spend 1 Momentum. |

### Moderate Slash

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Grazed.** Treat as a minor slashing wound. |
| Head | 2 | **Laid Open.** Bleeding (1) until you spend 1 Momentum to bind it. |
| Head | 3–4 | **Facial Wound.** Gain an additional minor slashing wound with no effect; the scar is permanent and remembered. |
| Torso | 1 | **Grazed.** Treat as a minor slashing wound. |
| Torso | 2 | **Opened Deep.** Bleeding (1) until bound. |
| Torso | 3 | **Cut Across.** –1 die on all physical rolls until aid. |
| Torso | 4 | **Gash and Gush.** Bleeding (2) until you spend 1 Momentum and an ally aids, or you receive Sawbone care. |
| Arm | 1 | **Grazed.** Treat as a minor slashing wound. |
| Arm | 2 | **Deep Cut.** You drop what the hand holds and take –1 die with that arm for the scene. |
| Arm | 3 | **Severed Tendons.** That arm is useless until aid. |
| Arm | 4 | **Nearly Off.** Bleeding (1) and the arm is useless until aided; if unaided by scene’s end, it is lost. |
| Leg | 1 | **Grazed.** Treat as a minor slashing wound. |
| Leg | 2 | **Deep Cut.** –3" Move for the scene. |
| Leg | 3 | **Hamstrung.** Move halved (round down), and you cannot leap until aid. |
| Leg | 4 | **Nearly Off.** Prone, Bleeding (1), Move 0 until aided; if unaided by scene’s end, the leg is lost. |

### Major Slash

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Deep Laceration.** Blinded (often permanently on one side) and disabled until you spend 1 Momentum; then treat as a moderate slashing wound. |
| Head | 2 | **Grievous.** A deep cut to the face and skull: prone, disabled, and Dying. |
| Head | 3–4 | **Throat Opened.** Death. |
| Torso | 1 | **Rent.** Treat as a moderate slashing wound; disabled until you spend 1 Momentum. |
| Torso | 2 | **Opened to the Bone.** Bleeding (2) and disabled; if the Bleeding is not stopped, Dying. |
| Torso | 3 | **Disemboweled.** Prone, disabled, and Dying. |
| Torso | 4 | **Cloven.** Death. |
| Arm | 1 | **Cut to the Bone.** Treat as a moderate slashing wound; the arm is useless until aid. |
| Arm | 2 | **Severed Tendons.** The arm hangs useless for the rest of the scene; without proper care it is a permanent maiming. |
| Arm | 3 | **Deep Gash.** You drop everything and take –2 dice with that arm; Bleeding (1) until bound. |
| Arm | 4 | **Severed.** The arm is struck off: the limb is lost (permanent maiming), and you are Dying. |
| Leg | 1 | **Cut to the Bone.** Treat as a moderate slashing wound; prone. |
| Leg | 2 | **Hamstrung Deep.** Move 0 and prone for the rest of the scene; without proper care it is a permanent maiming. |
| Leg | 3 | **Deep Gash.** Prone, Move halved, and Bleeding (1) until bound. |
| Leg | 4 | **Severed.** The leg is struck off: the limb is lost (permanent maiming), prone, and you are Dying. |

## Wound Tables: Blunt

*Fists, mauls, falls, kicks, rockfalls, the flat of a frame’s limb. Blunt seldom bleeds; it stuns and breaks. It kills by caving the skull or crushing the chest, and to the limbs it shatters rather than slays.*

### Minor Blunt

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Rung.** No further effect. |
| Head | 3 | **Dazed.** –1 die on your next action until you spend 1 Momentum to clear your head. |
| Head | 4 | **Ears Ringing.** –1 die on Perceive, and you cannot benefit from allies’ called warnings, until you spend 1 Momentum. |
| Torso | 1–2 | **Bruised.** No further effect. |
| Torso | 3 | **Winded.** Your next action costs 1 additional Momentum. |
| Torso | 4 | **Knocked Back.** Shoved 2" directly away and –1 die until you spend 1 Momentum to set your feet. |
| Arm | 1–2 | **Bruised.** No further effect. |
| Arm | 3 | **Deadened.** –1 die with that arm until you spend 1 Momentum. |
| Arm | 4 | **Knuckles Rapped.** You drop what the hand holds unless you spend 1 Momentum. |
| Leg | 1–2 | **Bruised.** No further effect. |
| Leg | 3 | **Dead Leg.** –2" Move until you spend 1 Momentum. |
| Leg | 4 | **Stumbled.** You cannot move during your side’s next surge unless you spend 1 Momentum, and drop prone if you were moving. |

### Moderate Blunt

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Glancing Knock.** Treat as a minor blunt wound. |
| Head | 2 | **Concussed.** –1 die on all rolls until aid or rest; spending 1 Momentum does not clear it. |
| Head | 3–4 | **Rattled.** Gain an additional minor blunt wound with no effect, and you are dazed (–1 die next action) until you spend 1 Momentum. |
| Torso | 1 | **Glancing Knock.** Treat as a minor blunt wound. |
| Torso | 2 | **Cracked Rib.** –1 die on all physical rolls until aid; every Move action costs 1 additional Momentum. |
| Torso | 3 | **Wind Driven Out.** Disabled until you spend 1 Momentum, then –1 die for the rest of the scene. |
| Torso | 4 | **Knocked Flat.** Prone, disabled until you spend 1 Momentum, and shoved 3". |
| Arm | 1 | **Glancing Knock.** Treat as a minor blunt wound. |
| Arm | 2 | **Fractured.** You drop what the hand holds; –2 dice with that arm until aid. |
| Arm | 3–4 | **Broken.** That arm is useless until aid, and a lingering injury without proper downtime care. |
| Leg | 1 | **Glancing Knock.** Treat as a minor blunt wound. |
| Leg | 2 | **Deep Bruise.** –3" Move for the scene. |
| Leg | 3–4 | **Broken.** Move 0, prone, cannot stand until aid; a lingering injury without downtime care. |

### Major Blunt

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Skull Rung.** Disabled until an ally aids or you spend 1 Momentum; then treat as a moderate blunt wound. |
| Head | 2 | **Cracked Skull.** Prone, disabled, and Dying. |
| Head | 3–4 | **Caved.** Death. |
| Torso | 1 | **Staved.** Treat as a moderate blunt wound; disabled until you spend 1 Momentum. |
| Torso | 2 | **Crushed Ribs.** Disabled; every action costs 1 additional Momentum; take Damage 1 Blunt at the start of your side’s surge until aided. If it triggers, become Dying. |
| Torso | 3 | **Caved Chest.** Prone, disabled, and Dying. |
| Torso | 4 | **Crushed Heart.** Death. |
| Arm | 1 | **Splintered.** Treat as a moderate blunt wound; the arm is useless until aid. |
| Arm | 2 | **Broken.** The arm hangs useless for the rest of the scene; without proper care it is a permanent maiming. |
| Arm | 3 | **Shattered.** You drop everything, the arm is useless, and you are disabled from shock until you spend 1 Momentum. |
| Arm | 4 | **Pulped.** The arm is destroyed beyond saving (permanent maiming) and the shock stops the heart’s rhythm: you are Dying. |
| Leg | 1 | **Splintered.** Treat as a moderate blunt wound; prone. |
| Leg | 2 | **Broken.** Move 0 and prone for the rest of the scene; without proper care it is a permanent maiming. |
| Leg | 3 | **Shattered.** Move 0, prone, and disabled from shock until you spend 1 Momentum. |
| Leg | 4 | **Pulped.** The leg is destroyed beyond saving (permanent maiming), prone, and the shock leaves you Dying. |

## Wound Tables: Burn

*Flame, steam, radiant heat, and burning fuel. Burn spreads and lingers: it blinds, it sears grip and footing, and its danger is the fire that is not out yet. Acid and electrical discharge use their own tables below. Where other wounds are a moment, a burn is a process. Note the **Burning (N)** status below.*


### Minor Burn

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Singed.** No further effect. |
| Head | 3 | **Smoke in the Eyes.** Blinded until you spend 1 Momentum to clear them. |
| Head | 4 | **Scorched.** Burning (1) until smothered. |
| Torso | 1–2 | **Singed.** No further effect. |
| Torso | 3 | **Smouldering.** Burning (1) until smothered. |
| Torso | 4 | **Seared.** –1 die on physical rolls until you spend 1 Momentum. |
| Arm *(Right or Left per the roll.)* | 1–2 | **Singed.** No further effect. |
| Arm *(Right or Left per the roll.)* | 3 | **Burned Grip.** You drop what the hand holds unless you spend 1 Momentum. |
| Arm *(Right or Left per the roll.)* | 4 | **Blistered.** –1 die with that arm until you spend 1 Momentum. |
| Leg | 1–2 | **Singed.** No further effect. |
| Leg | 3 | **Scalded.** –2" Move until you spend 1 Momentum. |
| Leg | 4 | **Smouldering.** Burning (1) until smothered. |

### Moderate Burn

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Scorched.** Treat as a minor burning wound. |
| Head | 2 | **Seared Face.** Burning (1) until smothered; the scar is permanent. |
| Head | 3–4 | **Smoke-Blind.** Blinded until aid; spending 1 Momentum reduces it to –2 dice on sight, no better. |
| Torso | 1 | **Scorched.** Treat as a minor burning wound. |
| Torso | 2 | **Set Alight.** Burning (2) until smothered. |
| Torso | 3 | **Deep Burn.** –1 die on all physical rolls until aid. |
| Torso | 4 | **Caustic Soak.** Burning (1), and your armor’s Armor save worsens by 1 until repaired (the caustic eats it). |
| Arm | 1 | **Scorched.** Treat as a minor burning wound. |
| Arm | 2 | **Charred Hand.** You drop what the hand holds and take –1 die with that arm for the scene. |
| Arm | 3 | **Set Alight.** Burning (2) until smothered. |
| Arm | 4 | **Contracted.** The arm seizes: useless until aid. |
| Leg | 1 | **Scorched.** Treat as a minor burning wound. |
| Leg | 2 | **Deep Burn.** –3" Move for the scene. |
| Leg | 3 | **Set Alight.** Burning (2) until smothered. |
| Leg | 4 | **Seized.** Move halved (round down) until aid. |

### Major Burn

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Face Aflame.** Blinded (often permanently on one side) and disabled until you spend 1 Momentum; then treat as a moderate burning wound. |
| Head | 2 | **Smoke-Choked.** You cannot breathe: prone, disabled, and Dying. |
| Head | 3–4 | **Immolated Head.** Death. |
| Torso | 1 | **Ablaze.** Treat as a moderate burning wound; disabled until you spend 1 Momentum. |
| Torso | 2 | **Engulfed.** Burning (3); if the Burning is not smothered, Dying. |
| Torso | 3 | **Cooked Through.** Prone, disabled, and Dying. |
| Torso | 4 | **Consumed.** Death. |
| Arm | 1 | **Charred to the Bone.** Treat as a moderate burning wound; the arm is useless until aid. |
| Arm | 2 | **Ruined.** The arm is useless for the scene; without proper care it is a permanent maiming. |
| Arm | 3 | **Ablaze.** You drop everything; Burning (2) until smothered; –2 dice with that arm. |
| Arm | 4 | **Burned Away.** The arm is destroyed (permanent maiming) and Burning (2) spreads across you: you are Dying. |
| Leg | 1 | **Charred to the Bone.** Treat as a moderate burning wound; prone. |
| Leg | 2 | **Ruined.** Move 0 and prone for the scene; without proper care it is a permanent maiming. |
| Leg | 3 | **Ablaze.** Prone, Move halved, and Burning (2) until smothered. |
| Leg | 4 | **Burned Away.** The leg is destroyed (permanent maiming), prone, and Burning (2) spreads across you: you are Dying. |

## Wound Tables: Blast

*Grenades, blasting charges, bursting Hearts, the concussive edge of energetics gone wrong. Blast throws and concusses: it hurls bodies, deafens, and ruptures from within, and against a group it is the wound that catches everyone. Blast wounds tend to move you — note the shoves — and its severe results rupture rather than pierce.*

### Minor Blast

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Rung.** No further effect. |
| Head | 3 | **Deafened.** –1 die on Perceive and no benefit from allies’ called warnings until you spend 1 Momentum. |
| Head | 4 | **Concussed Lightly.** –1 die on your next action until you spend 1 Momentum. |
| Torso | 1–2 | **Buffeted.** No further effect. |
| Torso | 3 | **Thrown Back.** Shoved 3" directly away; prone if you strike a solid obstacle. |
| Torso | 4 | **Winded.** Your next action costs 1 additional Momentum. |
| Arm *(Right or Left per the roll.)* | 1–2 | **Buffeted.** No further effect. |
| Arm *(Right or Left per the roll.)* | 3 | **Wrenched.** You drop what the hand holds unless you spend 1 Momentum. |
| Arm *(Right or Left per the roll.)* | 4 | **Numbed.** –1 die with that arm until you spend 1 Momentum. |
| Leg | 1–2 | **Buffeted.** No further effect. |
| Leg | 3 | **Knocked Down.** Prone; stand as normal. |
| Leg | 4 | **Staggered.** Shoved 2" and you cannot move during your side’s next surge unless you spend 1 Momentum. |

### Moderate Blast

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Glancing Concussion.** Treat as a minor blast wound. |
| Head | 2 | **Concussed.** –1 die on all rolls until aid or rest; spending 1 Momentum does not clear it. |
| Head | 3–4 | **Rattled.** Gain an additional minor blast wound with no effect, and you are disabled until you spend 1 Momentum. |
| Torso | 1 | **Glancing.** Treat as a minor blast wound. |
| Torso | 2 | **Hurled.** Shoved 5", prone, and –1 die until you spend 1 Momentum to rise and set your feet. |
| Torso | 3 | **Winded Hard.** Disabled until you spend 1 Momentum, then –1 die for the scene. |
| Torso | 4 | **Ruptured.** Take Damage 1 Blast at the start of your side’s surge until aided. |
| Arm | 1 | **Glancing.** Treat as a minor blast wound. |
| Arm | 2 | **Dislocated.** You drop what the hand holds; –2 dice with that arm until you spend 1 Momentum to set it (a loud, ugly action). |
| Arm | 3–4 | **Mangled.** The arm is useless until aid. |
| Leg | 1 | **Glancing.** Treat as a minor blast wound. |
| Leg | 2 | **Blown Off Balance.** Shoved 4", prone, –3" Move for the scene. |
| Leg | 3–4 | **Mangled.** Move 0 and prone until aid. |

### Major Blast

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Skull Rocked.** Disabled until an ally aids or you spend 1 Momentum; then treat as a moderate blast wound. |
| Head | 2 | **Brain Shook.** Prone, disabled, and Dying. |
| Head | 3–4 | **Head Ruptured.** Death. |
| Torso | 1 | **Staved.** Treat as a moderate blast wound; disabled until you spend 1 Momentum. |
| Torso | 2 | **Ruptured Deep.** Disabled; take Damage 1 Blast at the start of your side’s surge until aided. If it triggers, become Dying. |
| Torso | 3 | **Insides Torn.** Prone, disabled, and Dying. |
| Torso | 4 | **Blown Apart.** Death. |
| Arm | 1 | **Shattered.** Treat as a moderate blast wound; the arm is useless until aid. |
| Arm | 2 | **Mangled.** The arm is useless for the scene; without proper care it is a permanent maiming. |
| Arm | 3 | **Wrecked.** You drop everything, the arm is useless, and you are shoved 3" and disabled from shock until you spend 1 Momentum. |
| Arm | 4 | **Blown Off.** The arm is destroyed (permanent maiming), you are hurled 4" and prone, and the trauma leaves you Dying. |
| Leg | 1 | **Shattered.** Treat as a moderate blast wound; prone. |
| Leg | 2 | **Mangled.** Move 0 and prone for the scene; without proper care it is a permanent maiming. |
| Leg | 3 | **Wrecked.** Move 0, prone, shoved 3", and disabled from shock until you spend 1 Momentum. |
| Leg | 4 | **Blown Off.** The leg is destroyed (permanent maiming), you are hurled 4" and prone, and the trauma leaves you Dying. |

## Wound Tables: Cold

*Frost, supernatural winter, and exposure that steals heat faster than a body can replace it. Cold slows before it destroys. Unlike Shadow damage, it freezes flesh rather than draining spirit.*

**Chilled (N).** Reduce Move by N inches and subtract N dice from Athletics and Nimbleness. Chilled ends when the victim spends 1 Momentum beside meaningful heat, receives warming aid, or leaves the cold source. Use only the highest Chilled value.

| Severity | Location | d4 effects |
|:--|:--|:--|
| Minor | Head | **1–2 Cold-Stung:** no effect; **3 Streaming Eyes:** –1 die on sight-based Perceive until you spend 1 Momentum; **4 Numb Face:** –1 die on speech and social rolls until warmed. |
| Minor | Torso | **1–2 Cold-Stung:** no effect; **3 Shivering:** –1 die on the next physical action; **4 Chilled:** Chilled (1). |
| Minor | Arm | **1–2 Cold-Stung:** no effect; **3 Numb Fingers:** –1 die with that arm until warmed; **4 Frozen Grip:** drop what is held unless you spend 1 Momentum. |
| Minor | Leg | **1–2 Cold-Stung:** no effect; **3 Stiff Step:** –2" Move until warmed; **4 Iced Footing:** no movement during your side’s next surge unless you spend 1 Momentum. |
| Moderate | Head | **1 Frost-Nipped:** minor Cold wound; **2 Snow-Blind:** blinded until you spend 1 Momentum, then –1 sight die for the scene; **3 Confused:** –1 die on all rolls until aid; **4 Fading:** disabled until aided and warmed. |
| Moderate | Torso | **1 Frost-Nipped:** minor Cold wound; **2 Deep Shiver:** Chilled (2); **3 Breath Locked:** next action costs 1 additional Momentum; **4 Hypothermic:** –1 die on physical rolls until sustained warmth. |
| Moderate | Arm | **1 Frost-Nipped:** minor Cold wound; **2 Numbed Deep:** drop held item and –1 arm die for the scene; **3 Frozen Joint:** arm useless until warmed; **4 Frostbitten:** arm useless and a lingering injury without care. |
| Moderate | Leg | **1 Frost-Nipped:** minor Cold wound; **2 Stiffened:** –3" Move; **3 Frozen Joint:** Move 0 until warmed; **4 Frostbitten:** Move 0, prone, and a lingering injury without care. |
| Major | Head | **1 Frozen Daze:** moderate Cold wound and disabled; **2 Cold Sleep:** prone, disabled, and Dying; **3 Brain Frozen:** Death; **4 Shattered:** Death. |
| Major | Torso | **1 Frozen Through:** moderate Cold wound and disabled; **2 Heart Slowing:** prone and Dying; **3 Core Frozen:** prone, disabled, and Dying; **4 Frozen Solid:** Death. |
| Major | Arm | **1 Frozen Deep:** moderate Cold wound, arm useless; **2 Deadened:** permanent maiming without care; **3 Ice-Fractured:** arm useless and disabled; **4 Shattered Limb:** arm lost and Dying. |
| Major | Leg | **1 Frozen Deep:** moderate Cold wound and prone; **2 Dead Step:** permanent maiming without care; **3 Ice-Fractured:** Move 0, prone, and disabled; **4 Shattered Limb:** leg lost, prone, and Dying. |

## Wound Tables: Acid

*Corrosive blood, industrial acids, alchemical solvents, and spagyric caustics. Acid attacks protection as readily as flesh and keeps working until removed.*

**Corroding (N).** At the start of your side’s surge, worsen the current Armor save by N, to a maximum of 6+. This damage remains until the Armor is repaired, even after Corroding ends. If already at 6+ or unarmored, take Damage N Acid instead. Flushing with water or neutralizer as an action, or suitable aid, ends Corroding.

| Severity | Location | d4 effects |
|:--|:--|:--|
| Minor | Head | **1–2 Spattered:** no effect; **3 Stinging Eyes:** blinded until you spend 1 Momentum; **4 Etched:** –1 sight die for the scene. |
| Minor | Torso | **1–2 Spattered:** no effect; **3 Smoking Cloth:** Corroding (1); **4 Caustic Bite:** –1 die on the next physical action. |
| Minor | Arm | **1–2 Spattered:** no effect; **3 Slippery Grip:** drop held item unless you spend 1 Momentum; **4 Etched Hand:** –1 arm die until aid. |
| Minor | Leg | **1–2 Spattered:** no effect; **3 Burned Step:** –2" Move until aid; **4 Smoking Boot:** Corroding (1). |
| Moderate | Head | **1 Spattered:** minor Acid wound; **2 Face Etched:** –1 die on sight and social rolls, permanent scar; **3 Eyes Burned:** blinded until aid; **4 Fumes:** disabled until you spend 1 Momentum, then –1 die for the scene. |
| Moderate | Torso | **1 Spattered:** minor Acid wound; **2 Soaked:** Corroding (2); **3 Eaten Deep:** –1 die on physical rolls until aid; **4 Fuming Wound:** take Damage 1 Acid at the start of your side’s surge until flushed. |
| Moderate | Arm | **1 Spattered:** minor Acid wound; **2 Hand Eaten:** drop held item and –1 arm die; **3 Tendons Exposed:** arm useless until aid; **4 Dissolving:** Corroding (1), arm useless until flushed. |
| Moderate | Leg | **1 Spattered:** minor Acid wound; **2 Foot Eaten:** –3" Move; **3 Tendons Exposed:** Move halved; **4 Dissolving:** Corroding (1), Move 0 until flushed. |
| Major | Head | **1 Melted Surface:** moderate Acid wound, blinded and disabled; **2 Face Dissolved:** prone, disabled, and Dying; **3 Skull Opened:** Death; **4 Head Dissolved:** Death. |
| Major | Torso | **1 Eaten Deep:** moderate Acid wound and disabled; **2 Through the Chest:** Corroding (2) and disabled; if Corroding remains at the end of your side’s next surge, become Dying; **3 Organs Dissolving:** prone, disabled, and Dying; **4 Dissolved Through:** Death. |
| Major | Arm | **1 Stripped Deep:** moderate Acid wound, arm useless; **2 Ruined:** permanent maiming without care; **3 Dissolving Limb:** Corroding (2) and disabled; **4 Gone to Slurry:** arm lost and Dying. |
| Major | Leg | **1 Stripped Deep:** moderate Acid wound and prone; **2 Ruined:** permanent maiming without care; **3 Dissolving Limb:** Corroding (2), Move 0, prone, disabled; **4 Gone to Slurry:** leg lost, prone, and Dying. |

## Wound Tables: Electricity

*Lightning, jolt-lines, charged coils, defensive grids, and overdrawn Hearts. Electricity interrupts action, crosses conductors, and can stop the heart without leaving a large wound.*

**Charged.** Touching a conductor, standing water, exposed metal, or another Charged creature deals Damage 1 Electricity to both creatures and ends Charged. Spending 1 Momentum to ground safely also ends it. Conductive terrain must be identified before it matters.

| Severity | Location | d4 effects |
|:--|:--|:--|
| Minor | Head | **1–2 Sparked:** no effect; **3 Flash-Blind:** blinded until you spend 1 Momentum; **4 Ears Rung:** –1 Perceive die until you spend 1 Momentum. |
| Minor | Torso | **1–2 Sparked:** no effect; **3 Jolted:** next action costs 1 additional Momentum; **4 Charged:** gain Charged. |
| Minor | Arm | **1–2 Sparked:** no effect; **3 Spasm:** drop held item unless you spend 1 Momentum; **4 Nerve Jolt:** –1 arm die until you spend 1 Momentum. |
| Minor | Leg | **1–2 Sparked:** no effect; **3 Knee Buckled:** –2" Move until you spend 1 Momentum; **4 Muscle Lock:** no movement during your side’s next surge unless you spend 1 Momentum. |
| Moderate | Head | **1 Sparked:** minor Electricity wound; **2 Senses Blown:** –1 die on Perceive and ranged attacks; **3 Convulsed:** disabled until you spend 1 Momentum; **4 Memory Flash:** lose the planned action and choose anew after you spend 1 Momentum. |
| Moderate | Torso | **1 Sparked:** minor Electricity wound; **2 Thrown:** shoved 3" and prone; **3 Heart Flutter:** disabled until you spend 1 Momentum, then –1 die for the scene; **4 Arcing:** Charged and one adjacent creature takes a minor Electricity wound. |
| Moderate | Arm | **1 Sparked:** minor Electricity wound; **2 Grip Blown Open:** drop held item and –1 arm die; **3 Nerves Locked:** arm useless until aid; **4 Through the Gear:** arm useless and held metal item disabled until repaired. |
| Moderate | Leg | **1 Sparked:** minor Electricity wound; **2 Thrown Down:** prone and –3" Move; **3 Nerves Locked:** Move 0 until aid; **4 Grounded Through:** prone, Charged, and disabled. |
| Major | Head | **1 System Shock:** moderate Electricity wound and disabled; **2 Brain Seized:** prone, disabled, and Dying; **3 Arc Through Skull:** Death; **4 Flash-Charred:** Death. |
| Major | Torso | **1 System Shock:** moderate Electricity wound and disabled; **2 Heart Stopped:** prone and Dying; **3 Through the Core:** prone, Charged, disabled, and Dying; **4 Heart Burned Out:** Death. |
| Major | Arm | **1 Nerves Burned:** moderate Electricity wound, arm useless; **2 Dead Circuit:** permanent maiming without care; **3 Arc Explosion:** arm useless and disabled; **4 Blown Away:** arm destroyed and Dying. |
| Major | Leg | **1 Nerves Burned:** moderate Electricity wound and prone; **2 Dead Circuit:** permanent maiming without care; **3 Arc Explosion:** Move 0, prone, disabled; **4 Blown Away:** leg destroyed, prone, and Dying. |

## Wound Tables: Toxic

*Poison, venom, disease cultures, hostile spores, contaminated vapor, and alchemical toxins. Location records the point of entry or the system hit hardest.*

**Poisoned (N).** Subtract N dice from Alignment saves and physical rolls. At the end of your side’s surge, make a Wild save requiring N successes. Success reduces Poisoned by 1; failure deals Damage N Toxic. Antitoxin or Sawbone care reduces or ends it as stated. Use only the highest Poisoned value.

| Severity | Location | d4 effects |
|:--|:--|:--|
| Minor | Head | **1–2 Bitter Taste:** no effect; **3 Watering Eyes:** –1 Perceive die until you spend 1 Momentum; **4 Dizzy:** –1 die on the next action. |
| Minor | Torso | **1–2 Nauseated:** no effect; **3 Sickened:** –1 die on the next physical action; **4 Poisoned:** Poisoned (1). |
| Minor | Arm | **1–2 Local Sting:** no effect; **3 Numbed:** –1 arm die until aid; **4 Tremor:** drop held item unless you spend 1 Momentum. |
| Minor | Leg | **1–2 Local Sting:** no effect; **3 Weak-Kneed:** –2" Move until aid; **4 Cramping:** no movement during your side’s next surge unless you spend 1 Momentum. |
| Moderate | Head | **1 Low Dose:** minor Toxic wound; **2 Hallucinating:** –1 die on all rolls until aid; **3 Blind Sickness:** blinded until aid or antitoxin; **4 Seizure:** disabled until aided or you spend 1 Momentum. |
| Moderate | Torso | **1 Low Dose:** minor Toxic wound; **2 Poisoned:** Poisoned (1); **3 Violently Ill:** disabled until you spend 1 Momentum, then –1 die for the scene; **4 Heavy Dose:** Poisoned (2). |
| Moderate | Arm | **1 Low Dose:** minor Toxic wound; **2 Nerve Weakness:** drop held item and –1 arm die; **3 Paralyzed:** arm useless until aid; **4 Spreading Veins:** arm useless and Poisoned (1). |
| Moderate | Leg | **1 Low Dose:** minor Toxic wound; **2 Nerve Weakness:** –3" Move; **3 Paralyzed:** Move 0 until aid; **4 Spreading Veins:** Move 0 and Poisoned (1). |
| Major | Head | **1 Neurotoxic Crisis:** moderate Toxic wound and disabled; **2 Mind Fading:** prone and Poisoned (2); at the end of your side’s next surge, resolve the Poisoned save first, then become Dying if Poisoned remains; **3 Brain Death:** Death; **4 Instant Neurotoxin:** Death. |
| Major | Torso | **1 Systemic Crisis:** moderate Toxic wound and disabled; **2 Organ Failure:** Poisoned (2) and prone; at the end of your side’s next surge, resolve the Poisoned save first, then become Dying if Poisoned has not been reduced since this wound landed; **3 Blood Poisoned:** prone, disabled, and Dying; **4 Fatal Dose:** Death. |
| Major | Arm | **1 Necrotic Injection:** moderate Toxic wound, arm useless; **2 Dead Limb:** permanent maiming without care; **3 Spreading Paralysis:** arm useless, Poisoned (2), disabled; **4 Blackened Limb:** arm lost and Dying. |
| Major | Leg | **1 Necrotic Injection:** moderate Toxic wound and prone; **2 Dead Limb:** permanent maiming without care; **3 Spreading Paralysis:** Move 0, Poisoned (2), prone, disabled; **4 Blackened Limb:** leg lost, prone, and Dying. |

## Supernatural Wounds: The Five Planes

The five planes wound in their own grammars, and the tables below are read exactly like the physical ones — severity from thresholds, d6 location, d4 effect — but their harm follows the nature of the plane that dealt it, and their worst results kill in ways a body alone cannot explain. A weapon, effect, or creature that deals planar damage names its plane (Heavens, Machine, Shadow, Wild, or Wyrd); use that plane’s table.

Two conventions are shared across all five. First, the location die still applies — the planes strike a body somewhere, and where they strike shapes the wound — but location colors rather than confines spiritual harm. Second, planar wounds bypass ordinary Armor and test **Negation** instead; Armor-Piercing has no additional effect. Where a table says *save*, it means the relevant Alignment save described in the core rules.

### Heavens

*Radiant judgment, the searing regard of the law-that-is, the light that shows a thing for what it is. Heavens-damage burns the unworthy and binds the guilty; it collects, as the plane always does, in obligation and exposure. It falls hardest on those with much to answer for.*

**Minor Heavens**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Dazzled.** No effect. |
| Head | 3 | **Seen.** Blinded by light until you spend 1 Momentum. |
| Head | 4 | **Named.** You cannot lie until your side’s next surge. |
| Torso | 1–2 | **Warmed.** No effect. |
| Torso | 3 | **Weighed.** –1 die on your next action taken in bad faith (GM’s call); honest actions unaffected. |
| Torso | 4 | **Marked.** You shed faint light and cannot hide until you spend 1 Momentum. |
| Arm | 1–2 | **Warmed.** No effect. |
| Arm | 3 | **Stayed.** You drop a weapon raised to strike unless you spend 1 Momentum. |
| Arm | 4 | **Numb to Wrong.** –1 die with that arm on attacks (only) until you spend 1 Momentum. |
| Leg | 1–2 | **Warmed.** No effect. |
| Leg | 3 | **Rooted.** –2" Move until you spend 1 Momentum. |
| Leg | 4 | **Halted.** You cannot move toward a fleeing or helpless target during your side’s next surge unless you spend 1 Momentum. |

**Moderate Heavens**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Dazzled.** Minor Heavens wound. |
| Head | 2 | **Judged.** No effect, but the nearest onlooker learns one true wrong you have done. |
| Head | 3–4 | **Blinded by Truth.** Blinded until aid; spending 1 Momentum reduces it to –2 dice on sight. |
| Torso | 1 | **Warmed.** Minor Heavens wound. |
| Torso | 2 | **Seared.** –1 die on all rolls until you spend 1 Momentum. |
| Torso | 3 | **Bound.** You must keep any oath you swear this scene; breaking it immediately deals Damage 3 Heavens to you, bypassing saves. |
| Torso | 4 | **Exposed.** You shed light, cannot hide, and attacks against you ignore 1 Defend until aid. |
| Arm | 1 | **Warmed.** Minor Heavens wound. |
| Arm | 2 | **Withered Grip.** Drop what the hand holds; –1 die with that arm for the scene. |
| Arm | 3–4 | **Stayed Hand.** That arm cannot make attacks until you spend 1 Momentum and speak a true reason for fighting. |
| Leg | 1 | **Warmed.** Minor Heavens wound. |
| Leg | 2 | **Leaden.** –3" Move for the scene. |
| Leg | 3–4 | **Rooted in Place.** Move 0 until you spend 1 Momentum; you may not flee while any ally stands in danger. |

**Major Heavens**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Scoured.** Blinded and disabled until you spend 1 Momentum; then treat as a moderate Heavens wound. |
| Head | 2 | **Unmade Before the Light.** Prone, disabled, and Dying. |
| Head | 3–4 | **Judged and Found Wanting.** Death. *(Against a creature with nothing to answer for, the GM may reduce this to Dying — the light is not cruel.)* |
| Torso | 1 | **Seared Deep.** Moderate Heavens wound; disabled until you spend 1 Momentum. |
| Torso | 2 | **Heart Weighed.** Bleeding (2) of light; the first time it triggers, also become Dying unless aid or a true confession spoken aloud has stopped it. |
| Torso | 3 | **Struck Down.** Prone, disabled, and Dying. |
| Torso | 4 | **Consumed by Radiance.** Death. |
| Arm | 1 | **Withered.** Moderate Heavens wound; the arm is useless until aid. |
| Arm | 2 | **Struck Useless.** Arm useless for the scene; permanent maiming without care. |
| Arm | 3 | **Burned Clean.** Drop everything; –2 dice with that arm; disabled until you spend 1 Momentum. |
| Arm | 4 | **Ashed.** The arm is unmade to the elbow (permanent maiming) and the radiance floods you: you are Dying. |
| Leg | 1 | **Leaden.** Moderate Heavens wound; prone. |
| Leg | 2 | **Struck Down.** Move 0, prone; permanent maiming without care. |
| Leg | 3 | **Rooted.** Move 0, prone, disabled until an ally aids or you spend 2 Momentum. |
| Leg | 4 | **Ashed.** The leg is unmade to the knee (permanent maiming), prone, and the radiance floods you: you are Dying. |

### Machine

*The Material World’s answer: force applied with perfect literalness, the cold logic of stress and failure, systems seizing and breaking exactly as they must. Machine-damage does not rage; it processes. It jams, locks, and shears, and it collects in literalism — what it breaks stays broken until repaired, precisely.*

**Minor Machine**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Jarred.** No effect. |
| Head | 3 | **Ears Locked.** –1 die on Perceive until you spend 1 Momentum. |
| Head | 4 | **Stalled.** –1 die on your next action until you spend 1 Momentum. |
| Torso | 1–2 | **Jarred.** No effect. |
| Torso | 3 | **Seized.** Your next action costs 1 additional Momentum. |
| Torso | 4 | **Locked Up.** You cannot take the same action twice in a row until you spend 1 Momentum. |
| Arm | 1–2 | **Jarred.** No effect. |
| Arm | 3 | **Grip Locked.** You cannot drop or swap what the hand holds until you spend 1 Momentum. |
| Arm | 4 | **Deadened.** –1 die with that arm until you spend 1 Momentum. |
| Leg | 1–2 | **Jarred.** No effect. |
| Leg | 3 | **Gait Locked.** –2" Move until you spend 1 Momentum. |
| Leg | 4 | **Seized.** You cannot move during your side’s next surge unless you spend 1 Momentum. |

**Moderate Machine**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Jarred.** Minor Machine wound. |
| Head | 2 | **Senses Misaligned.** –1 die on all Perceive and ranged attacks until aid. |
| Head | 3–4 | **Logic Locked.** Gain an additional minor Machine wound with no effect, and you must repeat your previous action or spend 1 Momentum to choose freely. |
| Torso | 1 | **Jarred.** Minor Machine wound. |
| Torso | 2 | **Sheared.** –1 die on all physical rolls until aid. |
| Torso | 3 | **Systems Down.** Disabled until you spend 1 Momentum. |
| Torso | 4 | **Ground Gears.** Every action costs 1 additional Momentum until you spend 1 Momentum to reset. |
| Arm | 1 | **Jarred.** Minor Machine wound. |
| Arm | 2 | **Joint Seized.** Drop what the hand holds; the arm locks useless until you spend 1 Momentum. |
| Arm | 3–4 | **Sheared.** The arm is useless until aid. |
| Leg | 1 | **Jarred.** Minor Machine wound. |
| Leg | 2 | **Actuator Failed.** –3" Move for the scene. |
| Leg | 3–4 | **Seized Solid.** Move 0 until aid. |

**Major Machine**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Mind Jammed.** Disabled until an ally aids or you spend 1 Momentum; then treat as a moderate Machine wound. |
| Head | 2 | **Shut Down.** Prone, disabled, and Dying. |
| Head | 3–4 | **Skull Sheared.** Death. |
| Torso | 1 | **Sheared Deep.** Moderate Machine wound; disabled until you spend 1 Momentum. |
| Torso | 2 | **Core Failure.** Take Damage 1 Machine at the start of your side’s surge until aided. If it triggers, become Dying. |
| Torso | 3 | **Structural Collapse.** Prone, disabled, and Dying. |
| Torso | 4 | **Catastrophic Failure.** Death. |
| Arm | 1 | **Seized.** Moderate Machine wound; the arm useless until aid. |
| Arm | 2 | **Sheared Off Function.** Arm useless for the scene; permanent maiming without care. |
| Arm | 3 | **Locked and Wrecked.** Drop everything; –2 dice; disabled until you spend 1 Momentum. |
| Arm | 4 | **Sheared Off.** The arm is cut cleanly away as if machined (permanent maiming), and the shock leaves you Dying. |
| Leg | 1 | **Seized.** Moderate Machine wound; prone. |
| Leg | 2 | **Failed.** Move 0, prone; permanent maiming without care. |
| Leg | 3 | **Locked and Wrecked.** Move 0, prone, disabled until you spend 1 Momentum. |
| Leg | 4 | **Sheared Off.** The leg is cut cleanly away (permanent maiming), prone, and the shock leaves you Dying. |

### Shadow

*The plane of ambition, deception, and the price nobody names aloud. Shadow-damage does not simply hurt — it takes: warmth, will, memory, the light in a wound. It chills and drains and turns your own strength against you, and it collects in trust, spreading between those who stand too close. Shadow wounds resist ordinary Armor; Negation and the warded are its true defense.*

**Minor Shadow**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Chilled.** No effect. |
| Head | 3 | **Whispered To.** –1 die on your next social or Perceive roll until you spend 1 Momentum. |
| Head | 4 | **Doubt.** –1 die on your next action until you spend 1 Momentum to shake it off. |
| Torso | 1–2 | **Chilled.** No effect. |
| Torso | 3 | **Drained.** Your next action costs 1 additional Momentum. |
| Torso | 4 | **Cold Spot.** –1 die on saves until you spend 1 Momentum. |
| Arm | 1–2 | **Chilled.** No effect. |
| Arm | 3 | **Nerveless.** You drop what the hand holds unless you spend 1 Momentum. |
| Arm | 4 | **Weakened.** –1 die with that arm until you spend 1 Momentum. |
| Leg | 1–2 | **Chilled.** No effect. |
| Leg | 3 | **Leaden.** –2" Move until you spend 1 Momentum. |
| Leg | 4 | **Clutched.** You cannot move away from the source during your side’s next surge unless you spend 1 Momentum. |

**Moderate Shadow**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Chilled.** Minor Shadow wound. |
| Head | 2 | **Memory Taken.** You forget one recent fact or plan (GM chooses) until aid or rest. |
| Head | 3–4 | **Despair.** –1 die on all rolls until you spend 1 Momentum, and you cannot benefit from allies’ encouragement while it lasts. |
| Torso | 1 | **Chilled.** Minor Shadow wound. |
| Torso | 2 | **Life Drained.** –1 die on all rolls until aid; a creature that caused it gains Recovery 2. |
| Torso | 3 | **Hollowed.** Disabled until you spend 1 Momentum. |
| Torso | 4 | **Spreading Cold.** An ally adjacent to you takes a minor Shadow wound (torso) as it leaps. |
| Arm | 1 | **Chilled.** Minor Shadow wound. |
| Arm | 2 | **Deadened.** Drop what the hand holds; –1 die with that arm for the scene. |
| Arm | 3–4 | **Withered.** The arm hangs cold and useless until aid. |
| Leg | 1 | **Chilled.** Minor Shadow wound. |
| Leg | 2 | **Sapped.** –3" Move for the scene. |
| Leg | 3–4 | **Rooted in Cold.** Move 0 until aid. |

**Major Shadow**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Mind Clouded.** Disabled until an ally aids or you spend 1 Momentum; then treat as a moderate Shadow wound. |
| Head | 2 | **Soul-Chilled.** Prone, disabled, and Dying (a cold that stops the heart). |
| Head | 3–4 | **Unmade.** Death — and the body is not marked; it is simply emptied. |
| Torso | 1 | **Drained Deep.** Moderate Shadow wound; disabled until you spend 1 Momentum. |
| Torso | 2 | **Life Bleeding.** Bleeding (2) of warmth, not blood; the first time it triggers, also become Dying. A creature that caused it gains Recovery 1 each time it triggers. |
| Torso | 3 | **Hollowed Out.** Prone, disabled, and Dying. |
| Torso | 4 | **Snuffed.** Death. |
| Arm | 1 | **Withered.** Moderate Shadow wound; arm useless until aid. |
| Arm | 2 | **Deadened Cold.** Arm useless for the scene; permanent maiming without care (it does not warm again easily). |
| Arm | 3 | **Drained and Dropped.** Drop everything; –2 dice; disabled until you spend 1 Momentum. |
| Arm | 4 | **Withered to Ash.** The arm blackens and crumbles (permanent maiming) and the cold floods your chest: you are Dying. |
| Leg | 1 | **Sapped.** Moderate Shadow wound; prone. |
| Leg | 2 | **Deadened.** Move 0, prone; permanent maiming without care. |
| Leg | 3 | **Clutched Down.** Move 0, prone, disabled until you spend 1 Momentum. |
| Leg | 4 | **Withered to Ash.** The leg blackens and crumbles (permanent maiming), prone, and the cold floods you: you are Dying. |

### Wild

*Growth, physicality, vigor without measure — the plane that answers claims and overruns fences. Wild-damage does not wound so much as *overwhelm*: it inflames, it overgrows, it drives the body past its limits and then past its breaking. It collects in excess, and its worst results are the flesh made too much of itself.*

**Minor Wild**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Flushed.** No effect. |
| Head | 3 | **Reeling.** –1 die on your next action (senses overloaded) until you spend 1 Momentum. |
| Head | 4 | **Fever-Bright.** –1 die on Perceive until you spend 1 Momentum. |
| Torso | 1–2 | **Flushed.** No effect. |
| Torso | 3 | **Racing.** Your next action costs 1 additional Momentum as your body overrides you. |
| Torso | 4 | **Cramping.** –1 die on physical rolls until you spend 1 Momentum. |
| Arm | 1–2 | **Flushed.** No effect. |
| Arm | 3 | **Spasming.** You drop what the hand holds unless you spend 1 Momentum. |
| Arm | 4 | **Overtaxed.** –1 die with that arm until you spend 1 Momentum. |
| Leg | 1–2 | **Flushed.** No effect. |
| Leg | 3 | **Buckling.** –2" Move until you spend 1 Momentum. |
| Leg | 4 | **Locked.** You cannot move during your side’s next surge unless you spend 1 Momentum. |

**Moderate Wild**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Flushed.** Minor Wild wound. |
| Head | 2 | **Sensory Storm.** –1 die on all rolls until you spend 1 Momentum. |
| Head | 3–4 | **Overgrown.** Thorn, fur, or bark erupts wrongly: gain an additional minor Wild wound with no effect, and the growth is permanent until removed. |
| Torso | 1 | **Flushed.** Minor Wild wound. |
| Torso | 2 | **Inflamed.** –1 die on all physical rolls until aid. |
| Torso | 3 | **Convulsing.** Disabled until you spend 1 Momentum. |
| Torso | 4 | **Rioting Growth.** Take Damage 1 Wild at the start of your side’s surge until you spend 1 Momentum to master it or receive aid. |
| Arm | 1 | **Flushed.** Minor Wild wound. |
| Arm | 2 | **Seized.** Drop what the hand holds; –1 die with that arm for the scene. |
| Arm | 3–4 | **Overgrown Useless.** The arm knots with wild growth: useless until aid. |
| Leg | 1 | **Flushed.** Minor Wild wound. |
| Leg | 2 | **Cramped Solid.** –3" Move for the scene. |
| Leg | 3–4 | **Rooted.** Growth binds you: Move 0 until aid. |

**Major Wild**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Mind Overrun.** Disabled until an ally aids or you spend 1 Momentum; then treat as a moderate Wild wound. |
| Head | 2 | **Fever-Struck.** Prone, disabled, and Dying (the body burns itself out). |
| Head | 3–4 | **Overgrown Within.** Death — growth fills what should be hollow. |
| Torso | 1 | **Inflamed Deep.** Moderate Wild wound; disabled until you spend 1 Momentum. |
| Torso | 2 | **Rioting.** Take Damage 2 Wild at the start of your side’s surge until aided. If it triggers, become Dying. |
| Torso | 3 | **Convulsed.** Prone, disabled, and Dying. |
| Torso | 4 | **Burst.** Death — the flesh makes too much of itself, too fast. |
| Arm | 1 | **Overgrown.** Moderate Wild wound; arm useless until aid. |
| Arm | 2 | **Knotted.** Arm useless for the scene; permanent maiming without care. |
| Arm | 3 | **Rioting Growth.** Drop everything; –2 dice; disabled until you spend 1 Momentum. |
| Arm | 4 | **Consumed by Growth.** The arm is lost to wild overgrowth (permanent maiming) and the riot spreads inward: you are Dying. |
| Leg | 1 | **Cramped.** Moderate Wild wound; prone. |
| Leg | 2 | **Knotted.** Move 0, prone; permanent maiming without care. |
| Leg | 3 | **Rooted Down.** Move 0, prone, disabled until you spend 1 Momentum. |
| Leg | 4 | **Consumed by Growth.** The leg is lost to wild overgrowth (permanent maiming), prone, and the riot spreads inward: you are Dying. |

### Wyrd

*The Fey plane, the dreaming, chaos and curiosity and emotion unbound. Wyrd-damage is the least predictable: it warps sense and self, it makes the wrong thing true for a moment, and it collects in strangeness that lingers after the wound heals. It wounds the mind as readily as the body, and its worst results do not kill so much as *take you elsewhere* — which, for the living, is the same thing.*

**Minor Wyrd**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1–2 | **Swimming.** No effect. |
| Head | 3 | **Seeing Double.** –1 die on ranged attacks and Perceive until you spend 1 Momentum. |
| Head | 4 | **Elsewhere.** –1 die on your next action (your attention drifts to the dreaming) until you spend 1 Momentum. |
| Torso | 1–2 | **Tingling.** No effect. |
| Torso | 3 | **Unmoored.** Your next action costs 1 additional Momentum. |
| Torso | 4 | **Wrong-Footed.** –1 die on saves until you spend 1 Momentum. |
| Arm | 1–2 | **Tingling.** No effect. |
| Arm | 3 | **Not Quite Yours.** You drop what the hand holds unless you spend 1 Momentum. |
| Arm | 4 | **Phantom.** –1 die with that arm (it feels far away) until you spend 1 Momentum. |
| Leg | 1–2 | **Tingling.** No effect. |
| Leg | 3 | **Drifting.** –2" Move and your movement wavers until you spend 1 Momentum. |
| Leg | 4 | **Snared by a Dream.** You cannot move during your side’s next surge unless you spend 1 Momentum. |

**Moderate Wyrd**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Swimming.** Minor Wyrd wound. |
| Head | 2 | **Waking Dream.** You perceive one thing that is not there (GM’s choice) until you spend 1 Momentum to disbelieve. |
| Head | 3–4 | **Sense Unspooled.** –1 die on all rolls, and you cannot tell ally from enemy by sight, until aid or you spend 1 Momentum. |
| Torso | 1 | **Tingling.** Minor Wyrd wound. |
| Torso | 2 | **Flickering.** You phase half into the dreaming: –1 die on all rolls, but attacks against you also suffer –1 die, until aid. |
| Torso | 3 | **Unraveled.** Disabled until you spend 1 Momentum. |
| Torso | 4 | **Strangeness Spreads.** An ally within 6" takes a minor Wyrd wound (torso). |
| Arm | 1 | **Tingling.** Minor Wyrd wound. |
| Arm | 2 | **Estranged.** Drop what the hand holds; –1 die with that arm for the scene (it forgets it is yours). |
| Arm | 3–4 | **Elsewhere.** The arm phases out: useless until aid. |
| Leg | 1 | **Tingling.** Minor Wyrd wound. |
| Leg | 2 | **Half-Gone.** –3" Move for the scene. |
| Leg | 3–4 | **Caught Between.** Move 0 until aid; you are neither quite here nor there. |

**Major Wyrd**

| Location | d4 | Effect |
|:--|:--:|:--|
| Head | 1 | **Mind Unspooled.** Disabled until an ally aids or you spend 1 Momentum; then treat as a moderate Wyrd wound. |
| Head | 2 | **Lost in the Dreaming.** Prone, disabled, and Dying (the mind wanders and will not return unaided). |
| Head | 3–4 | **Taken.** Death — or, at the GM’s option, worse: the body remains, breathing, but the person is *gone into the Wyrd*, recoverable only as a story. |
| Torso | 1 | **Unraveled Deep.** Moderate Wyrd wound; disabled until you spend 1 Momentum. |
| Torso | 2 | **Coming Apart.** Take Damage 1 Wyrd at the start of your side’s surge until aided. If it triggers, become Dying. |
| Torso | 3 | **Scattered.** Prone, disabled, and Dying. |
| Torso | 4 | **Unwritten.** Death. |
| Arm | 1 | **Estranged.** Moderate Wyrd wound; arm useless until aid. |
| Arm | 2 | **Half-Gone.** Arm useless for the scene; permanent maiming without care (it does not always come all the way back). |
| Arm | 3 | **Flickering Wild.** Drop everything; –2 dice; disabled until you spend 1 Momentum. |
| Arm | 4 | **Gone Into the Dream.** The arm vanishes — simply is not there anymore (permanent maiming) — and the wrongness floods you: you are Dying. |
| Leg | 1 | **Half-Gone.** Moderate Wyrd wound; prone. |
| Leg | 2 | **Estranged.** Move 0, prone; permanent maiming without care. |
| Leg | 3 | **Caught Between.** Move 0, prone, disabled until you spend 1 Momentum. |
| Leg | 4 | **Gone Into the Dream.** The leg vanishes (permanent maiming), prone, and the wrongness floods you: you are Dying. |

## Downed, Dying, and Death

A character is **downed** whenever a wound leaves them unable to participate: usually Dying, Disabled with no available way to clear it, or unconscious in the fiction. Downed is a description, not an additional status; use the responsible wound’s rules to determine recovery.

A character becomes **Dying** when an effect names that status. They die at the end of their side’s **next surge** unless stabilized first. An adjacent character stabilizes them by spending 1 Momentum; specific wounds may require an additional method. Stabilization removes Dying but does not close or reduce the responsible wound.

**Death** is reserved. Only the most catastrophic results — a shot through the skull, a throat opened, and their equivalents across damage types — kill outright, with no interval to intervene. Every other grievous wound grants Dying instead, and Dying grants a chance: a round in which a companion with steady hands can still reach you.

Bleeding is the bridge between the two. At the start of the afflicted side’s surge, Bleeding deals its Damage before Momentum is rolled. If a wound says “if the Bleeding is not stopped, Dying,” the character becomes Dying after that first unstaunched trigger. The side can then use its surge to stabilize them.

------------------------------------------------------------------------

## Design Notes

**Wounds are information.** Because nothing drains a pool, every wound recorded on the sheet is a specific true fact about the body: a dropped weapon, a ringing ear, a leg that will not run. Both sides can see what is wrong and aim at it, and the fiction stays vivid. The stacking bonus (minor +1, moderate +2, major +4) is the nearest thing to a health total the game keeps, and it is emergent — the more hurt a body is, the harder the next hit lands, so fights reach a tipping point rather than a slow ebb.

**Armor is a wall.** The X+/Y+ saves make an armored character hard to wound, not soft when wounded — once a save fails, the wound table is the same for everyone. Armor-Piercing is feared because it does not chip away at protection; it removes the wall. Negation, untouched by Armor-Piercing, is the rare answer to the things that punch through plate.

**Every major can kill, but not equally.** A major wound always carries a chance of death, wherever it lands. On any major table, three of the four head faces and three of the four torso faces are lethal (Death or Dying), while one of the four limb faces is lethal — the strike that takes the limb clean off and opens the artery with it. So a major wound kills a little under half the time before armor and the Dying-round rescue are counted, and *where* it lands shapes *how* it kills: the head kills outright and fast, the torso mostly bleeds toward a death a companion can still prevent, and a limb kills only on the catastrophic severing. This keeps the location die meaningful — a called shot or focused volley to the head remains the clearest way to end a life — without ever letting a major wound feel safe.

**Dying carries most of the killing.** Instant Death is reserved for the worst two faces of the head and torso tables — the skull, the throat, the heart, and their kin. Everything else lethal routes through Dying and Bleeding, which means most deaths come with a round in which a companion can still reach the falling character. The frontier costs a body an arm far more often than a life; but a major wound is now always a moment where a life could be lost, and the Dying round is the drama that moment creates.

------------------------------------------------------------------------

## A Note on Damage Types in Play

Fourteen damage types now stand on one frame: the common types **Pierce**, **Slash**, **Blunt**, **Burn**, **Blast**, **Cold**, **Acid**, **Electricity**, and **Toxic**, plus the five planar types **Heavens**, **Machine**, **Shadow**, **Wild**, and **Wyrd**. Every one reads the same way — severity from thresholds, d6 for location, d4 for effect, the same Minor/Moderate/Major escalation, and majors that always carry a chance of death. What changes between them is character, not procedure:

- **Pierce** stops and drops, and kills clean through small holes.

- **Slash** opens, bleeds, and takes limbs.

- **Blunt** stuns and breaks; it kills by caving and crushing, and cripples the rest.

- **Burn** spreads and lingers through the Burning status; it is the wound that is not over when it lands.

- **Blast** throws and concusses, ruptures from within, and catches whole groups.

- **Cold** slows, numbs, freezes, and destroys neglected extremities.

- **Acid** corrodes protection and continues eating flesh until neutralized.

- **Electricity** interrupts action, arcs through conductors, and stops the heart.

- **Toxic** weakens resistance and physical action while poison, venom, spores, or disease spread systemically.

- **Heavens** judges and exposes, and falls hardest on the guilty.

- **Machine** jams, locks, and shears with perfect literalness.

- **Shadow** chills, drains, and spreads, and its worst simply empties a person.

- **Wild** inflames and overgrows, driving the flesh past its own limits.

- **Wyrd** unspools sense and self, and takes the gravely wounded *elsewhere*.

Weapons and creatures name their type; some name more than one (a flaming brand is Slash and Burn — roll the wound on whichever the attacker chooses, or the GM prefers). The planar types are rare in mortal hands and common at the edges of the map, which is exactly where the game intends the strangeness to live: a bandit’s pistol deals Pierce, but the thing in the Rust Belt that the bandits fled deals Shadow, and a body learns the difference only once.

------------------------------------------------------------------------

*The location grammar and the Dying/Death conventions are fixed across the complete common set. Sonic or thunder harm uses Blast; steam and radiant heat use Burn; pure force uses Blast; psychic or reality-warping harm uses Wyrd; life-draining or necrotic harm uses Shadow; uncontrolled mutation uses Wild. Add a new table only when an effect has a wound grammar genuinely distinct from these.*
