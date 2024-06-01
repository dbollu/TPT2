# True Neutral Tower

**TNT** (short for **T**rue **N**eutral **T**ower) is a BP that's slightly
inspired by Luna's "Infinity Assured Destroyer" (borf version). This
variant of IAD uses ultimate skills to add to the tower's crowd control
capabilities.

## The Blueprint

### Import Code

```
VVIxjtwwDPxKsA9QcemiJFXqVNcFKWSJsomVRYOk72AE+ftRtuXda2wNRQ7JGf27DWWFhbGq3L59+XP7LgYUfrx8/fn6+9UH1RDvbgiC0Ue7cRVW5VB+zeOBjytZSpDpBFgzVtTNHdFOIgtA6mBei6JMpFcLWmuEjjgsmDIyPMg+sdi3lCeSA8u6AH8mGtoA+6AwA49Q4+ZFGe/gbLhaG5eCdXBxCmjQKkrxI9FYwFlzk6fRjZjVTThOs9GrZfpMcZUuhx+IRN1a8Q1YDO8tHzBbVQqKVI1fFXjrI+O8FJjAco5ASG/BGqY9FKk2gla20DuwZxAUbQkuDOJ2hY66hO3vZUIo6WLxZPWFQnIJMlQxXVYOtivEe5MqcPJDIRPqMWvgmdgx5CaHh2qybaezJ2AY22nf5xGLWyxYxx7Ihd69YgLXDk8CdEf7rBc+Cy88EOdzOwYT+LKZZtCptdpd6RYEUxIzAl+Rs8GTK0FPIe/VvOzgystUUuO9HpbbXb4eXGKq4GSzJzPf/v7/AA==
```

### Module Loadout

Basic Attack, Neutral Crit, Critical Strike, Splash, Infinity Splash,
Attack Speed, Multishot, Basic Bouncing, Rapidfire, Quantum Speed,
Super Multishot, Super Bounce, Bash, Emergency Crit, Planned Strike,
Steini's Chained Ball, Google's Influence, High Mountain Gift, Neutral Focus,
Anti-Universal Projectiles, Anti-Universal Crit, Battery Foundation,
Simple Heal (min. tier and min. level),
Advanced Heal (min. tier and min. level), Power Conversion, Fire Armor,
Dispel, Advanced Shield, Defense Overload, Checkerboard Aura, Universal Block,
Refined Armor, Energy, Energy Regeneration, Energy Recycling, Energy Flow,
Low Tide, Something, Neutral Gift, Neutral Amplifier, Universal Shield,
Power Of The Cat, Knight's Boost of Power, Unfolding, Focused Multishot,
L.O.S.O. Drone System, Infinity Foundation, Infinity Shield, Infinity Energy,
Borf, Reboot

### Module Setup Explanation

LOSO Drone System and Something provide extra kills for maximum
crowd-controlling capabilities. Since these are ultimate active modules, they
are negatively impacted by Borf and therefore require some forms of CDR. The
Low Tide module will provide part of the required CDR.

With Low Tide hogging much of the tower's energy, we need Energy Recycling
and Power Conversion so the tower can spam all its skills.

Dispel is mostly setup for Defense Overload, much like in the original IAD.
However, Simple Heal and Advanced Heal are also here to keep a consistent
Defense Overload boost. ***MAKE SURE TO DOWNGRADE THOSE 2 MODULES ALL THE***
***WAY TO TIER 1 AND LEVEL 0*** so Emergency Crit can get more uptime.

Fire Armor is meant for early-mid Infinity, where we do not have yet brought
all era costs down to zero. It effectively neutralizes the threat of Fire
elementals exploding on the tower, which is very important because Fire
attacks **ignore shields** and the tower's HP is **much** lower than its
shield.

Power of the Cat is here as a safety net; its layers can recharge at a
consistent rate, so it's more reliable than Daigoparry in that department.

Attack Speed, Quantum Speed and Rapidfire are only here for projectile speed
since penalties to APS get shifted to projectile speed when we use Borf. This
is needed to counter wizard-types and Steini's CB's APS penalty.

Reboot is setup for Emergency Crit, and is going to be used regularly to keep
the tower at 1HP.

### Recommended Anvil Setup

For this blueprint you might want a lock on `Max Shield` on early Infinity
to deal with the few occasional hits. Obviously spend lots of yellow frags on
`CDR` to help blue modules proc Defense Overload more consistently. This also
helps with spamming the two "Super" skills for even more kills.

If you're worried about not being able to one-tap anymore, lock `Neutral DF`
and/or farm red frags for more `Neutral DF`. You can also try farming purple
frags for `Generic DF` though while both multipliers stack, the generic one
is much weaker.

## AI

### Import Code

```
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
```

### Requirements (Headquarters)

- 24+ action capacity per script (Mainloop is the main culprit here although
Skills comes very close at 20 actions)
- 6 script slots

### Configuration

You can tell the AI to stop towertesting at 1min by setting the `set_idle`
flag to `true`. This is useful for setting idle rewards without getting
diminishing returns due to longer runs.

## Changelog

- `0.1`: Introduced. Added BP code and documentation. Added this changelog.
- `0.2`: Removed Impetus, Dark Sacrifice, Shield Amplifier, Sun Energy and
Bulwark. Added Bash, Reboot, Simple Heal, Advanced Heal and Universal Block.
Added "human-readable" module loadout.
- `0.2.1`: More detailed explanation in the Module Setup section.
- `0.3`: Add complete AI (import code, requirements, config and scripts).