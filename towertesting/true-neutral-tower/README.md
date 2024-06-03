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
- 7 script slots

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
- `0.5`: Added missing Era script.
- `0.6`: Fixed PID not getting reset to 0 on restart.