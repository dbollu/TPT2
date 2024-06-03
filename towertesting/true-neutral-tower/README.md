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

- 23+ action capacity per script (Mainloop is the main culprit here although
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
- `0.4`: Fixed bug that caused an infinite loop in the Mainloop script.
Removed unnecessary initialization in the Mainloop script.