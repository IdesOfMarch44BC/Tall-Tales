# Combat and Wounds

## The Shape of a Fight

Combat runs on the surge-and-Momentum engine described in *How the Game Works*; this chapter covers what happens when someone tries to hurt someone else. The loop is short: **attack** (do you hit?), **save** (does armor stop it?), and **wound** (what did it do, and where?).

A character is not a reservoir of health that drains. A character is a body that accumulates specific injuries until one of them stops them. You always know exactly what is wrong with you, a fight can turn on a single roll, and the difference between a scratch and a killing blow is which part of the body the strike found and how hard it landed. Fights are quick and consequential. The wound tables are where the consequences live.

------------------------------------------------------------------------

## Attacking

### To Hit

Your **Strike** (melee) and **Shoot** (ranged) are **target numbers**: the value each die must meet or beat to land a hit. A lower number is better. Weapons modify the number they are used with — a fine dueling pistol might grant Shoot $`-1`$; an unbalanced club, Strike $`+1`$.

To attack:

1.  Take the pool of dice set by the weapon (its **Attack Dice**).

2.  **Subtract the target’s Defend** from that pool, to a minimum of 1 die.

3.  Roll. Each die meeting your Strike or Shoot number is a **hit**.

Defend subtracts dice rather than raising your target number. A well-defended foe shrinks your pool, so even an expert’s volley comes up thin against them; you overcome Defend through more attacks, larger pools, or effects that ignore it, never by needing better rolls. A pool reduced to its minimum of 1 die can still land a hit. No one is ever wholly untouchable.

### Damage and Severity

Each hit deals the weapon’s **Damage**, plus a bonus for every wound the target already carries:

<div class="center">

|                                  |               |
|:---------------------------------|:--------------|
| **Each existing minor wound**    | $`+1`$ damage |
| **Each existing moderate wound** | $`+2`$ damage |
| **Each existing major wound**    | $`+4`$ damage |

</div>

An unhurt body absorbs blows that would fell a wounded one; a hurt body takes every new strike harder. A character carrying one major and two minor wounds suffers $`+6`$ damage before the attacking weapon’s own Damage is added. This is how a fight tips: slowly, then all at once.

Compare the damage total to the target’s two thresholds, which are set by class, deeds, and equipment:

<div class="center">

| **Damage total**                          | **Severity** |
|:------------------------------------------|:-------------|
| Below Moderate threshold                  | **Minor**    |
| Moderate threshold or higher, below Major | **Moderate** |
| Major threshold or higher                 | **Major**    |

</div>

------------------------------------------------------------------------

## Armor and Negation

Before a wound takes effect, armor gets its say. Armor is written **X+/Y+**:

- **X+ is the Armor save** — common protection: plate, hide, grown bone, chassis.

- **Y+ is the Negation save** — rare protection: warding, spagyric resilience, the defense that should not have held and did.

When you take a wound — after its severity is known, before you roll location — roll a d6 for each save you possess. A success on *either* the Armor save or the Negation save stops the wound entirely: no location, no effect, no stacking. Both are rolled because they answer different threats and either can save you.

**Armor-Piercing (AP Z)** worsens the **Armor save** by Z. An Armor save of 3+ against an AP 2 weapon becomes 5+. Armor-Piercing does not affect the Negation save — that is the save armor-piercing cannot answer, and the reason Negation is prized. A save worsened past 6+ fails automatically.

Severity does not change the save; a hit either gets through armor or it does not. Severity decides how bad the wound is once armor has failed. Heavy armor means you are wounded seldom, not gently.

------------------------------------------------------------------------

## The Wound Roll

If no save stops the wound, roll **1d6** for location and **1d4** for effect, then read the table for the attack’s damage type at the wound’s severity.

<div class="center">

| **d6** | **Location** |
|:-------|:-------------|
| 1      | Head         |
| 2      | Torso        |
| 3      | Right Arm    |
| 4      | Left Arm     |
| 5      | Right Leg    |
| 6      | Left Leg     |

</div>

Record every wound with its severity, type, and location. Each one changes what the body can do and adds to the damage of the next hit.

### Statuses

Wound effects apply statuses. The ones that recur across every table:

Disabled.  
You cannot take actions until the disabled status is cleared (usually by spending a Momentum, sometimes only by aid).

Bleeding (N).  
At the start of each of your activations, take N damage. Bleeding continues until staunched — by spending a Momentum, by an ally’s aid, or by Sawbone care — and unstopped Bleeding is the most common road to the Dying status.

Dying.  
You will die at the end of your side’s **next** round unless the effect causing the Dying status is removed before then — by stabilizing, by aid, by Sawbone care, or by any means a specific wound entry names. A Dying character is out of the fight: prone, unable to act, and running out of time. This is the game’s usual result for a grievous wound, and it is survivable if a companion reaches you.

Death.  
The character is killed outright, with no interval to intervene. Only the most catastrophic wound results — a shot through the skull and its equivalents — inflict Death directly. Everything short of that grants Dying instead, and a chance.

**Clearing effects.** Many minor and moderate effects last *until you spend a Momentum* — wiping blood from your eyes, tearing free of a weapon, shaking the ring from your ears. That clearing is an action costing 1 Momentum from your side. Closing a wound itself, rather than merely its effect, requires Sawbone cards, aid, or downtime.

------------------------------------------------------------------------

## Wound Tables: Pierce

*Bullets, arrows, thrusts, fangs, spines. Pierce stops and drops; through a small hole it finds what matters, and to the head or heart it kills.*

### Minor Pierce

**Head**

- **Glancing Hit.** No further effect.

- **Stuck.** You are grappled (melee) or dazed (ranged) until you spend a Momentum to get free of the weapon or line of fire.

- **Blinded.** You are blinded until you spend a Momentum to wipe the blood away.

**Torso**

- **Glancing Hit.** No further effect.

- **Winded.** Your next action this scene costs 1 additional Momentum.

- **Stuck.** The weapon or bolt fouls you: –1 die on attacks until you spend a Momentum to clear it.

**Arm** *(Right or Left per the roll — note which; it matters for what you hold.)*

- **Glancing Hit.** No further effect.

- **Numbed.** –1 die on rolls using that arm until you spend a Momentum to shake it out.

- **Fumbled.** You drop what that hand holds unless you spend a Momentum to keep your grip.

**Leg**

- **Glancing Hit.** No further effect.

- **Limping.** –2" Move until you spend a Momentum to walk it off.

- **Staggered.** You cannot move this activation unless you spend a Momentum.

### Moderate Pierce

**Head**

- **Grazed.** Treat as a minor piercing wound (reroll on the Minor Head table).

- **Pierced.** No further effect.

- **Head Injury.** Gain an additional minor piercing wound with no wound effect (it still stacks damage).

**Torso**

- **Grazed.** Treat as a minor piercing wound.

- **Punched Through.** No further effect.

- **Winded Hard.** –1 die on all rolls until you spend a Momentum to catch your breath.

- **Bleeding.** Bleeding (1) until staunched.

**Arm**

- **Grazed.** Treat as a minor piercing wound.

- **Through the Meat.** No further effect.

- **Weakened.** –1 die on all rolls using that arm for the rest of the scene (a Momentum does not clear it; healing does).

- **Dropped and Fouled.** You drop what the hand holds and cannot use that arm until you spend a Momentum to pull the weapon free.

**Leg**

- **Grazed.** Treat as a minor piercing wound.

- **Through the Muscle.** No further effect.

- **Hobbled.** –3" Move for the rest of the scene.

- **Pinned.** You cannot move until you spend a Momentum to tear free, and drop prone if the shot was ranged.

### Major Pierce

**Head**

- **Barely Ducked.** Pained, scarred, and disabled until you spend a Momentum to clear the disabled; then treat as a moderate piercing wound.

- **Dropped.** The round takes you off your feet: prone, disabled, and Dying.

- **Headshot.** Death.

**Torso**

- **Cracked.** Treat as a moderate piercing wound, and you are disabled until you spend a Momentum.

- **Punctured Lung.** Bleeding (2) and disabled; if the Bleeding is not stopped, Dying.

- **Gut-Shot.** Prone, disabled, and Dying.

- **Through the Heart.** Death.

**Arm**

- **Shattered Joint.** Treat as a moderate piercing wound; that arm is useless until aid.

- **Maimed.** The arm is crippled for the rest of the scene and drops everything; without proper care it is a permanent maiming.

- **Pinned Through.** You are grappled in place (or to a surface behind you) and disabled until freed by spending 2 Momentum or by an ally.

- **Torn Away.** The wound wrecks the arm and opens an artery: the limb is lost (permanent maiming), and you are Dying.

**Leg**

- **Buckled.** Treat as a moderate piercing wound, and you fall prone.

- **Crippled.** Move becomes 0 and you are prone until aid; without proper care it is a permanent maiming.

- **Pinned.** Prone and grappled in place; disabled until freed by spending 2 Momentum or by an ally.

- **Femoral.** The leg is wrecked and the great vein is open: the limb is lost (permanent maiming), prone, and you are Dying.

------------------------------------------------------------------------

## Wound Tables: Slash

*Sabers, hatchets, claws, glass, saw-edged frontier steel. Slash opens and bleeds; to a limb it takes the limb, and to the head or throat it is as final as any bullet.*

### Minor Slash

**Head**

- **Nicked.** No further effect.

- **Blood in the Eyes.** Blinded until you spend a Momentum to wipe it clear.

- **Ear or Scalp.** Loud and bloody: –1 die on Perceive (hearing) until you spend a Momentum to clear your head.

**Torso**

- **Nicked.** No further effect.

- **Opened.** A shallow cut: –1 die on Athletics-based actions until you spend a Momentum.

- **Bleeding Light.** Bleeding (1) until you spend a Momentum; it clots readily.

**Arm**

- **Nicked.** No further effect.

- **Cut Tendon.** –1 die with that arm until you spend a Momentum to adjust your grip.

- **Slashed Grip.** You drop what the hand holds unless you spend a Momentum.

**Leg**

- **Nicked.** No further effect.

- **Hamstrung Lightly.** –2" Move until you spend a Momentum.

- **Cut Across the Shin.** –1 die on Move-based rolls until you spend a Momentum.

### Moderate Slash

**Head**

- **Grazed.** Treat as a minor slashing wound.

- **Laid Open.** Bleeding (1) until you spend a Momentum to bind it.

- **Facial Wound.** Gain an additional minor slashing wound with no effect; the scar is permanent and remembered.

**Torso**

- **Grazed.** Treat as a minor slashing wound.

- **Opened Deep.** Bleeding (1) until bound.

- **Cut Across.** –1 die on all physical rolls until aid.

- **Gash and Gush.** Bleeding (2) until you spend a Momentum and an ally aids, or you receive Sawbone care.

**Arm**

- **Grazed.** Treat as a minor slashing wound.

- **Deep Cut.** You drop what the hand holds and take –1 die with that arm for the scene.

- **Severed Tendons.** That arm is useless until aid.

- **Nearly Off.** Bleeding (1) and the arm is useless until aided; if unaided by scene’s end, it is lost.

**Leg**

- **Grazed.** Treat as a minor slashing wound.

- **Deep Cut.** –3" Move for the scene.

- **Hamstrung.** Move halved (round down); you cannot charge or leap until aid.

- **Nearly Off.** Prone, Bleeding (1), Move 0 until aided; if unaided by scene’s end, the leg is lost.

### Major Slash

**Head**

- **Deep Laceration.** Blinded (often permanently on one side) and disabled until you spend a Momentum; then treat as a moderate slashing wound.

- **Grievous.** A deep cut to the face and skull: prone, disabled, and Dying.

- **Throat Opened.** Death.

**Torso**

- **Rent.** Treat as a moderate slashing wound; disabled until a Momentum is spent.

- **Opened to the Bone.** Bleeding (2) and disabled; if the Bleeding is not stopped, Dying.

- **Disemboweled.** Prone, disabled, and Dying.

- **Cloven.** Death.

**Arm**

- **Cut to the Bone.** Treat as a moderate slashing wound; the arm is useless until aid.

- **Severed Tendons.** The arm hangs useless for the rest of the scene; without proper care it is a permanent maiming.

- **Deep Gash.** You drop everything and take –2 dice with that arm; Bleeding (1) until bound.

- **Severed.** The arm is struck off: the limb is lost (permanent maiming), and you are Dying.

**Leg**

- **Cut to the Bone.** Treat as a moderate slashing wound; prone.

- **Hamstrung Deep.** Move 0 and prone for the rest of the scene; without proper care it is a permanent maiming.

- **Deep Gash.** Prone, Move halved, and Bleeding (1) until bound.

- **Severed.** The leg is struck off: the limb is lost (permanent maiming), prone, and you are Dying.

------------------------------------------------------------------------

## Wound Tables: Blunt

*Fists, mauls, falls, kicks, rockfalls, the flat of a frame’s limb. Blunt seldom bleeds; it stuns and breaks. It kills by caving the skull or crushing the chest, and to the limbs it shatters rather than slays.*

### Minor Blunt

**Head**

- **Rung.** No further effect.

- **Dazed.** –1 die on your next action until you spend a Momentum to clear your head.

- **Ears Ringing.** –1 die on Perceive, and you cannot benefit from allies’ called warnings, until you spend a Momentum.

**Torso**

- **Bruised.** No further effect.

- **Winded.** Your next action costs 1 additional Momentum.

- **Knocked Back.** Shoved 2" directly away and –1 die until you spend a Momentum to set your feet.

**Arm**

- **Bruised.** No further effect.

- **Deadened.** –1 die with that arm until you spend a Momentum.

- **Knuckles Rapped.** You drop what the hand holds unless you spend a Momentum.

**Leg**

- **Bruised.** No further effect.

- **Dead Leg.** –2" Move until you spend a Momentum.

- **Stumbled.** You cannot move this activation unless you spend a Momentum, and drop prone if you were moving.

### Moderate Blunt

**Head**

- **Glancing Knock.** Treat as a minor blunt wound.

- **Concussed.** –1 die on all rolls until aid or rest; a Momentum does not clear it.

- **Rattled.** Gain an additional minor blunt wound with no effect, and you are dazed (–1 die next action) until you spend a Momentum.

**Torso**

- **Glancing Knock.** Treat as a minor blunt wound.

- **Cracked Rib.** –1 die on all physical rolls until aid; every Move action costs an extra Momentum.

- **Wind Driven Out.** Disabled until you spend a Momentum, then –1 die for the rest of the scene.

- **Knocked Flat.** Prone, disabled until you spend a Momentum, and shoved 3".

**Arm**

- **Glancing Knock.** Treat as a minor blunt wound.

- **Fractured.** You drop what the hand holds; –2 dice with that arm until aid.

- **Broken.** That arm is useless until aid, and a lingering injury without proper downtime care.

**Leg**

- **Glancing Knock.** Treat as a minor blunt wound.

- **Deep Bruise.** –3" Move for the scene.

- **Broken.** Move 0, prone, cannot stand until aid; a lingering injury without downtime care.

### Major Blunt

**Head**

- **Skull Rung.** Stunned (cannot act) until an ally aids or you spend a Momentum; then treat as a moderate blunt wound.

- **Cracked Skull.** Prone, disabled, and Dying.

- **Caved.** Death.

**Torso**

- **Staved.** Treat as a moderate blunt wound; disabled until a Momentum is spent.

- **Crushed Ribs.** Disabled, every action costs +1 Momentum, and you take 1 damage each activation (internal); if this internal damage is not stopped by aid, Dying.

- **Caved Chest.** Prone, disabled, and Dying.

- **Crushed Heart.** Death.

**Arm**

- **Splintered.** Treat as a moderate blunt wound; the arm is useless until aid.

- **Broken.** The arm hangs useless for the rest of the scene; without proper care it is a permanent maiming.

- **Shattered.** You drop everything, the arm is useless, and you are disabled from shock until you spend a Momentum.

- **Pulped.** The arm is destroyed beyond saving (permanent maiming) and the shock stops the heart’s rhythm: you are Dying.

**Leg**

- **Splintered.** Treat as a moderate blunt wound; prone.

- **Broken.** Move 0 and prone for the rest of the scene; without proper care it is a permanent maiming.

- **Shattered.** Move 0, prone, and disabled from shock until you spend a Momentum.

- **Pulped.** The leg is destroyed beyond saving (permanent maiming), prone, and the shock leaves you Dying.

------------------------------------------------------------------------

## Wound Tables: Burn

*Flame, acid, storage-acid splash, spagyric caustics, the discharge of an overdrawn Heart. Burn spreads and lingers: it blinds, it sears grip and footing, and its danger is the fire that is not out yet. Where other wounds are a moment, a burn is a process. Note the **Burning (N)** status below.*

**Burning (N).** At the start of each of your activations, take N damage as the fire or caustic continues to work, and it may spread (GM’s discretion) to adjacent flammables or, on a fresh wound roll, worsen. Burning ends when you spend a Momentum to smother it, an ally aids, or you reach water. Unlike Bleeding, Burning cannot be ignored between activations without spreading.

### Minor Burn

**Head**

- **Singed.** No further effect.

- **Smoke in the Eyes.** Blinded until you spend a Momentum to clear them.

- **Scorched.** Burning (1) until smothered.

**Torso**

- **Singed.** No further effect.

- **Smouldering.** Burning (1) until smothered.

- **Seared.** –1 die on physical rolls until you spend a Momentum.

**Arm** *(Right or Left per the roll.)*

- **Singed.** No further effect.

- **Burned Grip.** You drop what the hand holds unless you spend a Momentum.

- **Blistered.** –1 die with that arm until you spend a Momentum.

**Leg**

- **Singed.** No further effect.

- **Scalded.** –2" Move until you spend a Momentum.

- **Smouldering.** Burning (1) until smothered.

### Moderate Burn

**Head**

- **Scorched.** Treat as a minor burning wound.

- **Seared Face.** Burning (1) until smothered; the scar is permanent.

- **Smoke-Blind.** Blinded until aid; a Momentum reduces it to –2 dice on sight, no better.

**Torso**

- **Scorched.** Treat as a minor burning wound.

- **Set Alight.** Burning (2) until smothered.

- **Deep Burn.** –1 die on all physical rolls until aid.

- **Caustic Soak.** Burning (1), and your armor’s Armor save worsens by 1 until repaired (the caustic eats it).

**Arm**

- **Scorched.** Treat as a minor burning wound.

- **Charred Hand.** You drop what the hand holds and take –1 die with that arm for the scene.

- **Set Alight.** Burning (2) until smothered.

- **Contracted.** The arm seizes: useless until aid.

**Leg**

- **Scorched.** Treat as a minor burning wound.

- **Deep Burn.** –3" Move for the scene.

- **Set Alight.** Burning (2) until smothered.

- **Seized.** Move halved (round down) until aid.

### Major Burn

**Head**

- **Face Aflame.** Blinded (often permanently on one side) and disabled until you spend a Momentum; then treat as a moderate burning wound.

- **Smoke-Choked.** You cannot breathe: prone, disabled, and Dying.

- **Immolated Head.** Death.

**Torso**

- **Ablaze.** Treat as a moderate burning wound; disabled until a Momentum is spent.

- **Engulfed.** Burning (3); if the Burning is not smothered, Dying.

- **Cooked Through.** Prone, disabled, and Dying.

- **Consumed.** Death.

**Arm**

- **Charred to the Bone.** Treat as a moderate burning wound; the arm is useless until aid.

- **Ruined.** The arm is useless for the scene; without proper care it is a permanent maiming.

- **Ablaze.** You drop everything; Burning (2) until smothered; –2 dice with that arm.

- **Burned Away.** The arm is destroyed (permanent maiming) and Burning (2) spreads across you: you are Dying.

**Leg**

- **Charred to the Bone.** Treat as a moderate burning wound; prone.

- **Ruined.** Move 0 and prone for the scene; without proper care it is a permanent maiming.

- **Ablaze.** Prone, Move halved, and Burning (2) until smothered.

- **Burned Away.** The leg is destroyed (permanent maiming), prone, and Burning (2) spreads across you: you are Dying.

------------------------------------------------------------------------

## Wound Tables: Blast

*Grenades, blasting charges, bursting Hearts, the concussive edge of energetics gone wrong. Blast throws and concusses: it hurls bodies, deafens, and ruptures from within, and against a group it is the wound that catches everyone. Blast wounds tend to move you — note the shoves — and its severe results rupture rather than pierce.*

### Minor Blast

**Head**

- **Rung.** No further effect.

- **Deafened.** –1 die on Perceive and no benefit from allies’ called warnings until you spend a Momentum.

- **Concussed Lightly.** –1 die on your next action until you spend a Momentum.

**Torso**

- **Buffeted.** No further effect.

- **Thrown Back.** Shoved 3" directly away; prone if you strike a solid obstacle.

- **Winded.** Your next action costs 1 additional Momentum.

**Arm** *(Right or Left per the roll.)*

- **Buffeted.** No further effect.

- **Wrenched.** You drop what the hand holds unless you spend a Momentum.

- **Numbed.** –1 die with that arm until you spend a Momentum.

**Leg**

- **Buffeted.** No further effect.

- **Knocked Down.** Prone; stand as normal.

- **Staggered.** Shoved 2" and you cannot move this activation unless you spend a Momentum.

### Moderate Blast

**Head**

- **Glancing Concussion.** Treat as a minor blast wound.

- **Concussed.** –1 die on all rolls until aid or rest; a Momentum does not clear it.

- **Rattled.** Gain an additional minor blast wound with no effect, and you are disabled until you spend a Momentum.

**Torso**

- **Glancing.** Treat as a minor blast wound.

- **Hurled.** Shoved 5", prone, and –1 die until you spend a Momentum to rise and set your feet.

- **Winded Hard.** Disabled until you spend a Momentum, then –1 die for the scene.

- **Ruptured.** Internal damage: take 1 damage each activation until aid.

**Arm**

- **Glancing.** Treat as a minor blast wound.

- **Dislocated.** You drop what the hand holds; –2 dice with that arm until you spend a Momentum to set it (a loud, ugly action).

- **Mangled.** The arm is useless until aid.

**Leg**

- **Glancing.** Treat as a minor blast wound.

- **Blown Off Balance.** Shoved 4", prone, –3" Move for the scene.

- **Mangled.** Move 0 and prone until aid.

### Major Blast

**Head**

- **Skull Rocked.** Stunned (cannot act) until an ally aids or you spend a Momentum; then treat as a moderate blast wound.

- **Brain Shook.** Prone, disabled, and Dying.

- **Head Ruptured.** Death.

**Torso**

- **Staved.** Treat as a moderate blast wound; disabled until a Momentum is spent.

- **Ruptured Deep.** Internal damage 1 each activation, disabled; if not stopped by aid, Dying.

- **Insides Torn.** Prone, disabled, and Dying.

- **Blown Apart.** Death.

**Arm**

- **Shattered.** Treat as a moderate blast wound; the arm is useless until aid.

- **Mangled.** The arm is useless for the scene; without proper care it is a permanent maiming.

- **Wrecked.** You drop everything, the arm is useless, and you are shoved 3" and disabled from shock until you spend a Momentum.

- **Blown Off.** The arm is destroyed (permanent maiming), you are hurled 4" and prone, and the trauma leaves you Dying.

**Leg**

- **Shattered.** Treat as a moderate blast wound; prone.

- **Mangled.** Move 0 and prone for the scene; without proper care it is a permanent maiming.

- **Wrecked.** Move 0, prone, shoved 3", and disabled from shock until you spend a Momentum.

- **Blown Off.** The leg is destroyed (permanent maiming), you are hurled 4" and prone, and the trauma leaves you Dying.

------------------------------------------------------------------------

## Supernatural Wounds: The Five Planes

The five planes wound in their own grammars, and the tables below are read exactly like the physical ones — severity from thresholds, d6 location, d4 effect — but their harm follows the nature of the plane that dealt it, and their worst results kill in ways a body alone cannot explain. A weapon, effect, or creature that deals planar damage names its plane (Heavens, Machine, Shadow, Wild, or Wyrd); use that plane’s table.

Two conventions are shared across all five. First, the location die still applies — the planes strike a body somewhere, and where they strike shapes the wound — but several planar effects are as much of the mind or spirit as the flesh, and the location colors rather than confines them. Second, planar wounds interact with **Negation**, not ordinary Armor, more often than physical wounds do: a warded traveler may shrug off a Shadow-wound that would unmake an unprotected one, and Armor-Piercing does nothing against the planes. Where a table says *save*, it means the relevant Alignment save described in the core rules.

### Heavens

*Radiant judgment, the searing regard of the law-that-is, the light that shows a thing for what it is. Heavens-damage burns the unworthy and binds the guilty; it collects, as the plane always does, in obligation and exposure. It falls hardest on those with much to answer for.*

**Minor Heavens**

- **Head:** (1–2) **Dazzled.** No effect. (3) **Seen.** Blinded by light until you spend a Momentum. (4) **Named.** You cannot lie until your next activation.

- **Torso:** (1–2) **Warmed.** No effect. (3) **Weighed.** –1 die on your next action taken in bad faith (GM’s call); honest actions unaffected. (4) **Marked.** You shed faint light and cannot hide until you spend a Momentum.

- **Arm:** (1–2) **Warmed.** No effect. (3) **Stayed.** You drop a weapon raised to strike unless you spend a Momentum. (4) **Numb to Wrong.** –1 die with that arm on attacks (only) until you spend a Momentum.

- **Leg:** (1–2) **Warmed.** No effect. (3) **Rooted.** –2" Move until you spend a Momentum. (4) **Halted.** You cannot move toward a fleeing or helpless target this activation unless you spend a Momentum.

**Moderate Heavens**

- **Head:** (1) **Dazzled.** Minor Heavens wound. (2) **Judged.** No effect, but the nearest onlooker learns one true wrong you have done. (3–4) **Blinded by Truth.** Blinded until aid; a Momentum reduces it to –2 dice on sight.

- **Torso:** (1) **Warmed.** Minor Heavens wound. (2) **Seared.** –1 die on all rolls until you spend a Momentum. (3) **Bound.** You must keep any oath you swear this scene; breaking it costs you an automatic wound (GM). (4) **Exposed.** You shed light, cannot hide, and attacks against you ignore 1 Defend until aid.

- **Arm:** (1) **Warmed.** Minor Heavens wound. (2) **Withered Grip.** Drop what the hand holds; –1 die with that arm for the scene. (3–4) **Stayed Hand.** That arm cannot make attacks until you spend a Momentum and speak a true reason for fighting.

- **Leg:** (1) **Warmed.** Minor Heavens wound. (2) **Leaden.** –3" Move for the scene. (3–4) **Rooted in Place.** Move 0 until you spend a Momentum; you may not flee while any ally stands in danger.

**Major Heavens**

- **Head:** (1) **Scoured.** Blinded and disabled until you spend a Momentum; then treat as a moderate Heavens wound. (2) **Unmade Before the Light.** Prone, disabled, and Dying. (3–4) **Judged and Found Wanting.** Death. *(Against a creature with nothing to answer for, the GM may reduce this to Dying — the light is not cruel.)*

- **Torso:** (1) **Seared Deep.** Moderate Heavens wound; disabled until a Momentum is spent. (2) **Heart Weighed.** Bleeding (2) of light; if not stopped by aid or a true confession spoken aloud, Dying. (3) **Struck Down.** Prone, disabled, and Dying. (4) **Consumed by Radiance.** Death.

- **Arm:** (1) **Withered.** Moderate Heavens wound; the arm is useless until aid. (2) **Struck Useless.** Arm useless for the scene; permanent maiming without care. (3) **Burned Clean.** Drop everything; –2 dice with that arm; disabled until a Momentum. (4) **Ashed.** The arm is unmade to the elbow (permanent maiming) and the radiance floods you: you are Dying.

- **Leg:** (1) **Leaden.** Moderate Heavens wound; prone. (2) **Struck Down.** Move 0, prone; permanent maiming without care. (3) **Rooted.** Move 0, prone, disabled until an ally aids or you spend 2 Momentum. (4) **Ashed.** The leg is unmade to the knee (permanent maiming), prone, and the radiance floods you: you are Dying.

### Machine

*The Material World’s answer: force applied with perfect literalness, the cold logic of stress and failure, systems seizing and breaking exactly as they must. Machine-damage does not rage; it processes. It jams, locks, and shears, and it collects in literalism — what it breaks stays broken until repaired, precisely.*

**Minor Machine**

- **Head:** (1–2) **Jarred.** No effect. (3) **Ears Locked.** –1 die on Perceive until you spend a Momentum. (4) **Stalled.** –1 die on your next action until you spend a Momentum.

- **Torso:** (1–2) **Jarred.** No effect. (3) **Seized.** Your next action costs 1 additional Momentum. (4) **Locked Up.** You cannot take the same action twice in a row until you spend a Momentum.

- **Arm:** (1–2) **Jarred.** No effect. (3) **Grip Locked.** You cannot drop or swap what the hand holds until you spend a Momentum. (4) **Deadened.** –1 die with that arm until you spend a Momentum.

- **Leg:** (1–2) **Jarred.** No effect. (3) **Gait Locked.** –2" Move until you spend a Momentum. (4) **Seized.** You cannot move this activation unless you spend a Momentum.

**Moderate Machine**

- **Head:** (1) **Jarred.** Minor Machine wound. (2) **Senses Misaligned.** –1 die on all Perceive and ranged attacks until aid. (3–4) **Logic Locked.** Gain an additional minor Machine wound with no effect, and you must repeat your previous action or spend a Momentum to choose freely.

- **Torso:** (1) **Jarred.** Minor Machine wound. (2) **Sheared.** –1 die on all physical rolls until aid. (3) **Systems Down.** Disabled until you spend a Momentum. (4) **Ground Gears.** Every action costs 1 additional Momentum until you spend a Momentum to reset.

- **Arm:** (1) **Jarred.** Minor Machine wound. (2) **Joint Seized.** Drop what the hand holds; the arm locks useless until you spend a Momentum. (3–4) **Sheared.** The arm is useless until aid.

- **Leg:** (1) **Jarred.** Minor Machine wound. (2) **Actuator Failed.** –3" Move for the scene. (3–4) **Seized Solid.** Move 0 until aid.

**Major Machine**

- **Head:** (1) **Mind Jammed.** Disabled until an ally aids or you spend a Momentum; then treat as a moderate Machine wound. (2) **Shut Down.** Prone, disabled, and Dying. (3–4) **Skull Sheared.** Death.

- **Torso:** (1) **Sheared Deep.** Moderate Machine wound; disabled until a Momentum. (2) **Core Failure.** Take 1 damage each activation (systemic) until aid; if not stopped, Dying. (3) **Structural Collapse.** Prone, disabled, and Dying. (4) **Catastrophic Failure.** Death.

- **Arm:** (1) **Seized.** Moderate Machine wound; the arm useless until aid. (2) **Sheared Off Function.** Arm useless for the scene; permanent maiming without care. (3) **Locked and Wrecked.** Drop everything; –2 dice; disabled until a Momentum. (4) **Sheared Off.** The arm is cut cleanly away as if machined (permanent maiming), and the shock leaves you Dying.

- **Leg:** (1) **Seized.** Moderate Machine wound; prone. (2) **Failed.** Move 0, prone; permanent maiming without care. (3) **Locked and Wrecked.** Move 0, prone, disabled until a Momentum. (4) **Sheared Off.** The leg is cut cleanly away (permanent maiming), prone, and the shock leaves you Dying.

### Shadow

*The plane of ambition, deception, and the price nobody names aloud. Shadow-damage does not simply hurt — it takes: warmth, will, memory, the light in a wound. It chills and drains and turns your own strength against you, and it collects in trust, spreading between those who stand too close. Shadow wounds resist ordinary Armor; Negation and the warded are its true defense.*

**Minor Shadow**

- **Head:** (1–2) **Chilled.** No effect. (3) **Whispered To.** –1 die on your next social or Perceive roll until you spend a Momentum. (4) **Doubt.** –1 die on your next action until you spend a Momentum to shake it off.

- **Torso:** (1–2) **Chilled.** No effect. (3) **Drained.** Your next action costs 1 additional Momentum. (4) **Cold Spot.** –1 die on saves until you spend a Momentum.

- **Arm:** (1–2) **Chilled.** No effect. (3) **Nerveless.** You drop what the hand holds unless you spend a Momentum. (4) **Weakened.** –1 die with that arm until you spend a Momentum.

- **Leg:** (1–2) **Chilled.** No effect. (3) **Leaden.** –2" Move until you spend a Momentum. (4) **Clutched.** You cannot move away from the source this activation unless you spend a Momentum.

**Moderate Shadow**

- **Head:** (1) **Chilled.** Minor Shadow wound. (2) **Memory Taken.** You forget one recent fact or plan (GM chooses) until aid or rest. (3–4) **Despair.** –1 die on all rolls until you spend a Momentum, and you cannot benefit from allies’ encouragement while it lasts.

- **Torso:** (1) **Chilled.** Minor Shadow wound. (2) **Life Drained.** –1 die on all rolls until aid; the source (if a creature) heals what it took. (3) **Hollowed.** Disabled until you spend a Momentum. (4) **Spreading Cold.** An ally adjacent to you takes a minor Shadow wound (torso) as it leaps.

- **Arm:** (1) **Chilled.** Minor Shadow wound. (2) **Deadened.** Drop what the hand holds; –1 die with that arm for the scene. (3–4) **Withered.** The arm hangs cold and useless until aid.

- **Leg:** (1) **Chilled.** Minor Shadow wound. (2) **Sapped.** –3" Move for the scene. (3–4) **Rooted in Cold.** Move 0 until aid.

**Major Shadow**

- **Head:** (1) **Mind Clouded.** Disabled until an ally aids or you spend a Momentum; then treat as a moderate Shadow wound. (2) **Soul-Chilled.** Prone, disabled, and Dying (a cold that stops the heart). (3–4) **Unmade.** Death — and the body is not marked; it is simply emptied.

- **Torso:** (1) **Drained Deep.** Moderate Shadow wound; disabled until a Momentum. (2) **Life Bleeding.** Bleeding (2) of warmth, not blood; if not stopped by aid or Negation, Dying, and the source heals each time it ticks. (3) **Hollowed Out.** Prone, disabled, and Dying. (4) **Snuffed.** Death.

- **Arm:** (1) **Withered.** Moderate Shadow wound; arm useless until aid. (2) **Deadened Cold.** Arm useless for the scene; permanent maiming without care (it does not warm again easily). (3) **Drained and Dropped.** Drop everything; –2 dice; disabled until a Momentum. (4) **Withered to Ash.** The arm blackens and crumbles (permanent maiming) and the cold floods your chest: you are Dying.

- **Leg:** (1) **Sapped.** Moderate Shadow wound; prone. (2) **Deadened.** Move 0, prone; permanent maiming without care. (3) **Clutched Down.** Move 0, prone, disabled until a Momentum. (4) **Withered to Ash.** The leg blackens and crumbles (permanent maiming), prone, and the cold floods you: you are Dying.

### Wild

*Growth, physicality, vigor without measure — the plane that answers claims and overruns fences. Wild-damage does not wound so much as *overwhelm*: it inflames, it overgrows, it drives the body past its limits and then past its breaking. It collects in excess, and its worst results are the flesh made too much of itself.*

**Minor Wild**

- **Head:** (1–2) **Flushed.** No effect. (3) **Reeling.** –1 die on your next action (senses overloaded) until you spend a Momentum. (4) **Fever-Bright.** –1 die on Perceive until you spend a Momentum.

- **Torso:** (1–2) **Flushed.** No effect. (3) **Racing.** Your next action costs 1 additional Momentum as your body overrides you. (4) **Cramping.** –1 die on physical rolls until you spend a Momentum.

- **Arm:** (1–2) **Flushed.** No effect. (3) **Spasming.** You drop what the hand holds unless you spend a Momentum. (4) **Overtaxed.** –1 die with that arm until you spend a Momentum.

- **Leg:** (1–2) **Flushed.** No effect. (3) **Buckling.** –2" Move until you spend a Momentum. (4) **Locked.** You cannot move this activation unless you spend a Momentum.

**Moderate Wild**

- **Head:** (1) **Flushed.** Minor Wild wound. (2) **Sensory Storm.** –1 die on all rolls until you spend a Momentum. (3–4) **Overgrown.** Thorn, fur, or bark erupts wrongly: gain an additional minor Wild wound with no effect, and the growth is permanent until removed.

- **Torso:** (1) **Flushed.** Minor Wild wound. (2) **Inflamed.** –1 die on all physical rolls until aid. (3) **Convulsing.** Disabled until you spend a Momentum. (4) **Rioting Growth.** Take 1 damage each activation as flesh overgrows until you spend a Momentum to master it or receive aid.

- **Arm:** (1) **Flushed.** Minor Wild wound. (2) **Seized.** Drop what the hand holds; –1 die with that arm for the scene. (3–4) **Overgrown Useless.** The arm knots with wild growth: useless until aid.

- **Leg:** (1) **Flushed.** Minor Wild wound. (2) **Cramped Solid.** –3" Move for the scene. (3–4) **Rooted.** Growth binds you: Move 0 until aid.

**Major Wild**

- **Head:** (1) **Mind Overrun.** Disabled until an ally aids or you spend a Momentum; then treat as a moderate Wild wound. (2) **Fever-Struck.** Prone, disabled, and Dying (the body burns itself out). (3–4) **Overgrown Within.** Death — growth fills what should be hollow.

- **Torso:** (1) **Inflamed Deep.** Moderate Wild wound; disabled until a Momentum. (2) **Rioting.** Take 2 damage each activation as the body devours itself; if not stopped by aid, Dying. (3) **Convulsed.** Prone, disabled, and Dying. (4) **Burst.** Death — the flesh makes too much of itself, too fast.

- **Arm:** (1) **Overgrown.** Moderate Wild wound; arm useless until aid. (2) **Knotted.** Arm useless for the scene; permanent maiming without care. (3) **Rioting Growth.** Drop everything; –2 dice; disabled until a Momentum. (4) **Consumed by Growth.** The arm is lost to wild overgrowth (permanent maiming) and the riot spreads inward: you are Dying.

- **Leg:** (1) **Cramped.** Moderate Wild wound; prone. (2) **Knotted.** Move 0, prone; permanent maiming without care. (3) **Rooted Down.** Move 0, prone, disabled until a Momentum. (4) **Consumed by Growth.** The leg is lost to wild overgrowth (permanent maiming), prone, and the riot spreads inward: you are Dying.

### Wyrd

*The Fey plane, the dreaming, chaos and curiosity and emotion unbound. Wyrd-damage is the least predictable: it warps sense and self, it makes the wrong thing true for a moment, and it collects in strangeness that lingers after the wound heals. It wounds the mind as readily as the body, and its worst results do not kill so much as *take you elsewhere* — which, for the living, is the same thing.*

**Minor Wyrd**

- **Head:** (1–2) **Swimming.** No effect. (3) **Seeing Double.** –1 die on ranged attacks and Perceive until you spend a Momentum. (4) **Elsewhere.** –1 die on your next action (your attention drifts to the dreaming) until you spend a Momentum.

- **Torso:** (1–2) **Tingling.** No effect. (3) **Unmoored.** Your next action costs 1 additional Momentum. (4) **Wrong-Footed.** –1 die on saves until you spend a Momentum.

- **Arm:** (1–2) **Tingling.** No effect. (3) **Not Quite Yours.** You drop what the hand holds unless you spend a Momentum. (4) **Phantom.** –1 die with that arm (it feels far away) until you spend a Momentum.

- **Leg:** (1–2) **Tingling.** No effect. (3) **Drifting.** –2" Move and your movement wavers until you spend a Momentum. (4) **Snared by a Dream.** You cannot move this activation unless you spend a Momentum.

**Moderate Wyrd**

- **Head:** (1) **Swimming.** Minor Wyrd wound. (2) **Waking Dream.** You perceive one thing that is not there (GM’s choice) until you spend a Momentum to disbelieve. (3–4) **Sense Unspooled.** –1 die on all rolls, and you cannot tell ally from enemy by sight, until aid or you spend a Momentum.

- **Torso:** (1) **Tingling.** Minor Wyrd wound. (2) **Flickering.** You phase half into the dreaming: –1 die on all rolls, but attacks against you also suffer –1 die, until aid. (3) **Unraveled.** Disabled until you spend a Momentum. (4) **Strangeness Spreads.** An ally within 3 tiles takes a minor Wyrd wound (torso).

- **Arm:** (1) **Tingling.** Minor Wyrd wound. (2) **Estranged.** Drop what the hand holds; –1 die with that arm for the scene (it forgets it is yours). (3–4) **Elsewhere.** The arm phases out: useless until aid.

- **Leg:** (1) **Tingling.** Minor Wyrd wound. (2) **Half-Gone.** –3" Move for the scene. (3–4) **Caught Between.** Move 0 until aid; you are neither quite here nor there.

**Major Wyrd**

- **Head:** (1) **Mind Unspooled.** Disabled until an ally aids or you spend a Momentum; then treat as a moderate Wyrd wound. (2) **Lost in the Dreaming.** Prone, disabled, and Dying (the mind wanders and will not return unaided). (3–4) **Taken.** Death — or, at the GM’s option, worse: the body remains, breathing, but the person is *gone into the Wyrd*, recoverable only as a story.

- **Torso:** (1) **Unraveled Deep.** Moderate Wyrd wound; disabled until a Momentum. (2) **Coming Apart.** You flicker between here and elsewhere: at the start of each activation take 1 damage as pieces stay behind; if not stopped by aid, Dying. (3) **Scattered.** Prone, disabled, and Dying. (4) **Unwritten.** Death.

- **Arm:** (1) **Estranged.** Moderate Wyrd wound; arm useless until aid. (2) **Half-Gone.** Arm useless for the scene; permanent maiming without care (it does not always come all the way back). (3) **Flickering Wild.** Drop everything; –2 dice; disabled until a Momentum. (4) **Gone Into the Dream.** The arm vanishes — simply is not there anymore (permanent maiming) — and the wrongness floods you: you are Dying.

- **Leg:** (1) **Half-Gone.** Moderate Wyrd wound; prone. (2) **Estranged.** Move 0, prone; permanent maiming without care. (3) **Caught Between.** Move 0, prone, disabled until a Momentum. (4) **Gone Into the Dream.** The leg vanishes (permanent maiming), prone, and the wrongness floods you: you are Dying.

------------------------------------------------------------------------

## Downed, Dying, and Death

A character is **downed** when a wound takes them out of the fight without killing them: a torso or head major that stuns, a leg major that pins them prone, or an accumulation the GM judges has finished them for the scene. A downed character cannot act until the responsible effect is cleared or aid arrives.

A character becomes **Dying** when a wound effect names that status. They will die at the end of their side’s **next** round unless the effect is removed first. Removing it means **stabilizing**: an ally spends an action adjacent to them to halt the wound (Sawbone cards and care do this and more). A Dying character stabilized in time survives, though what they carry out of the fight — a lost arm, a cracked skull, a scarred artery — is the wound table’s lasting mark on them.

**Death** is reserved. Only the most catastrophic results — a shot through the skull, a throat opened, and their equivalents across damage types — kill outright, with no interval to intervene. Every other grievous wound grants Dying instead, and Dying grants a chance: a round in which a companion with steady hands can still reach you.

Bleeding is the bridge between the two. Several major wounds inflict Bleeding rather than Dying directly; left unstopped, Bleeding drains a body until it is downed and then Dying. A wound that reads “if the Bleeding is not stopped, Dying” becomes lethal only if no one — including the wounded character spending a Momentum — staunches it in time.

------------------------------------------------------------------------

## Design Notes

**Wounds are information.** Because nothing drains a pool, every wound recorded on the sheet is a specific true fact about the body: a dropped weapon, a ringing ear, a leg that will not run. Both sides can see what is wrong and aim at it, and the fiction stays vivid. The stacking bonus (minor $`+1`$, moderate $`+2`$, major $`+4`$) is the nearest thing to a health total the game keeps, and it is emergent — the more hurt a body is, the harder the next hit lands, so fights reach a tipping point rather than a slow ebb.

**Armor is a wall.** The X+/Y+ saves make an armored character hard to wound, not soft when wounded — once a save fails, the wound table is the same for everyone. Armor-Piercing is feared because it does not chip away at protection; it removes the wall. Negation, untouched by Armor-Piercing, is the rare answer to the things that punch through plate.

**Every major can kill, but not equally.** A major wound always carries a chance of death, wherever it lands. On any major table, three of the four head faces and three of the four torso faces are lethal (Death or Dying), while one of the four limb faces is lethal — the strike that takes the limb clean off and opens the artery with it. So a major wound kills a little under half the time before armor and the Dying-round rescue are counted, and *where* it lands shapes *how* it kills: the head kills outright and fast, the torso mostly bleeds toward a death a companion can still prevent, and a limb kills only on the catastrophic severing. This keeps the location die meaningful — a called shot or focused volley to the head remains the clearest way to end a life — without ever letting a major wound feel safe.

**Dying carries most of the killing.** Instant Death is reserved for the worst two faces of the head and torso tables — the skull, the throat, the heart, and their kin. Everything else lethal routes through Dying and Bleeding, which means most deaths come with a round in which a companion can still reach the falling character. The frontier costs a body an arm far more often than a life; but a major wound is now always a moment where a life could be lost, and the Dying round is the drama that moment creates.

------------------------------------------------------------------------

## A Note on Damage Types in Play

Eight damage types now stand on one frame: **Pierce**, **Slash**, **Blunt**, **Burn**, **Blast**, and the five planar types **Heavens**, **Machine**, **Shadow**, **Wild**, and **Wyrd**. Every one reads the same way — severity from thresholds, d6 for location, d4 for effect, the same Minor/Moderate/Major escalation, and majors that always carry a chance of death (3/4 to the head, 3/4 to the torso, 1/4 to a limb). What changes between them is character, not procedure:

- **Pierce** stops and drops, and kills clean through small holes.

- **Slash** opens, bleeds, and takes limbs.

- **Blunt** stuns and breaks; it kills by caving and crushing, and cripples the rest.

- **Burn** spreads and lingers through the Burning status; it is the wound that is not over when it lands.

- **Blast** throws and concusses, ruptures from within, and catches whole groups.

- **Heavens** judges and exposes, and falls hardest on the guilty.

- **Machine** jams, locks, and shears with perfect literalness.

- **Shadow** chills, drains, and spreads, and its worst simply empties a person.

- **Wild** inflames and overgrows, driving the flesh past its own limits.

- **Wyrd** unspools sense and self, and takes the gravely wounded *elsewhere*.

Weapons and creatures name their type; some name more than one (a flaming brand is Slash and Burn — roll the wound on whichever the attacker chooses, or the GM prefers). The planar types are rare in mortal hands and common at the edges of the map, which is exactly where the game intends the strangeness to live: a bandit’s pistol deals Pierce, but the thing in the Rust Belt that the bandits fled deals Shadow, and a body learns the difference only once.

------------------------------------------------------------------------

*The location grammar and the Dying/Death conventions are now fixed across all eight types; further exotic types (poison-as-its-own-type, cold, sonic) can be built on the identical frame should the setting call for them.*
