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
xVhdb6s6Fv0vfT1XGjBlVEY6D5AEJ5yEFpLY4Kv7gO1OaGKnzKFAktH895FJ0wKlbXrUc0ulSkH+2B9rr702/73I2c+77CG/+NefF+5hd2BjL+Nwac3Ws29oZC6vN3qaYDOnwKrswLZtmxgxfhA8suvHrWzbdtwthdZdjKuCQEuP5U5Mt77gdrqmwDxw6BbcDqY3Y79iUmhkoe394WUYR+qu9IFEYRbvzQ010B2Fyx8cigcyNzcE77Q4aJ3h/Fg1f8/s0xPYykY/pQPzjgIr77l/wgDSIiA2FC4nMbAKZoQp3QaObZtbgk3BpFhPJS85tDLSumeC1R0j7Jc0clImxYGCyydfh+Ow5ADtpzIVMd5pSevekTOAfkm3vhZjU3PsiXUT9Ptg21bDDnRJsK/ztq2j0bovR2gfB+/vdRc9e4X/M8G7nFW75/1bniZR0Nw7lJkk6u8/i6sFAaggkadyJm4hWvMoFMwQRVy14j1v5nt2MJcLEfxzORKjoeSCSrRP8KwgwNIoELIZI3u1VMG4joH1wKC7TyK/pHdmRrfBNQG7MpZuPpWi4ANzS9p2jgaRkxHXWlMDFZ38Ozet3xOoLhmChi1RKmIDaaSNuajPjzk2ZYLNjI83N33xaOXcub9ihrNPolDcLCaHGxFeo2HrnXaz+hvj3+uzqZHIK+LIM6dbX2NSFKSy1hTolapTBqxiKr2Sguqz8zK4WWjNtQNnpTLTXuPdxdcUWmvFMbG0Stp3x9gX3LUyAned+LOe+GcLEgWrOQ7zTr7t9/F5/3fgc3LknGdbOHAzPkYFhyL//VzUxKOvUcM+k4fe3tfbY4Qv+MDxVN6G8NlfZoQlsz9Ui7NGbRw4tKo2Dpa9OEiAyOl49s7e82r41Ac5Ng8vct/yPfj2m3ObnpXbut9dteuvXvP9+8UfF71pFo4XNg47ygLzyfUEm1pP+/UYFJsI+CXHpjaUqmzCe4qRptxP6nc8p8BTLVyVUkEA0touiSrB4b9jYOl02w6tPc9bLhxtql3oVzWiIFIUSRSaDUe8uuIkTyleFhRbG46PSiY20L7DEnNmOILCqiBjr6RyWTBDHDhEDx/N6iBy8jgSgt2Zl6zLCD1qZzUJiiD0tjHWxVTqJRmjnMzNg+r4TLY7/gD7KR+YFTW4YKnb6TChTrdhRh23w/JhybGXk0BUFLomiSbF7bhdxfbistWdasNg5B+WozkBrlJvDxSEOoXLggHVobwOIzuHBApBYaAqJeMS7Rlw898bu8GdcLKHID0vdkPDv08wysnATMmYpFT6gji/NYaaV6Kfw9HszBh6BwZRTpv2QcUM1auwbxBtA/aDX2k0I/xUrSfh3lOxeYcgO41/rb2EkW3bi439g0PLUGEjUZrxx0p+U78+++PW//XTPFCTCXthml8l+KP9+t054agpZTtkNbnhXRmD1++xDScjb+uB4fHs97TJ5jVt4p/0U03QkncJeqgIuh2j0VX77JpVrxt9ckuNsExw3CLfYx7NTkWIgndy8hIudU46VVK1e1Pwfv8aqSUO12rWu3uuIh75IsGP/jpplwXS2AgzLpcqPhsSrbpsUBG8y6dS1+k4zBhIS/7Jd4yixzu2vs4g2sfS0lVVNzVRnfPqJeZc46QNnu7SGUDZKbYQdrqadNccCkDmZkZlKG7bWPCJtNY8mhVUIp2PvZS+56v98Dw/qFy/yoi70zn3BLs5h6vOLP42RZzmoGJxFXdZMsa+lkREqPsJRJdtbO1ObLkn2Cup0cLZ4B/qqd7G1SD4fFyNtidcuRsu3SIGaJNA9H68P3rP+AlbGY2cnOC6U0Qnmn1WO+hAsDjt+9UYb5Iay9WsyxVtPqlJ+3NteO6KGyatQnX328jXCNaathgxFi3usXV0fObchuPeWqqo4WccipKmv8gdW7+sBS9Us7UJiKrnrVfSpV9Sw9uw6jW9/sr7j6qREL3AVAyskkLl7+VnxbnN32vNasW50aff4bWa6S/+uIB9M8i6PUr1qJkX6uSlBOiok9RVLVtLoC44VBRwClvP582X7bP7ebM7n3Q+a75NNY355fVJu6N4PlObri8tFx87BoHiEKv1c3X2SCHm0HWd4J2IjXCfYF9N4cEjkhQLpMdwKXvf3BN2q1ONiQmuwo6SOaXTY3CX3mK0n27TqjP5frsJ0WOFqk7tHsVp5KVT6ZfM6Co8VCiUs62fUsfp3dcZQ3UqBSCRd4hx9WV2O8AUPAr3Ma7Oiff4uZN/GU5cgt09h6tz7D2t/br4RjzlEO1HsNe//rWfN78q5YN64zQ319TwO1SG8gTze34Wfk9rvwwHE6LyBkzBjNk5WGiu/zo8SDPlY7Qn4TkxJkUcheqbwtfZC0nG5PKc+I6IFHvV5r4ID8MYi7PqzAZuxlbfv1/89b//Aw==
```

### Requirements (Headquarters)

- 23+ action capacity per script (Mainloop is the main culprit here although
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