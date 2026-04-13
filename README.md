# Astrophage — A KSP Mod Inspired by *Project Hail Mary*

A Kerbal Space Program mod that adds **Astrophage**, the alien microorganism propellant from *Project Hail Mary*, to your game.

---

## What This Mod Adds

### Astrophage Resource
A new fuel type — **Astrophage** — an alien microorganism that stores staggering amounts of energy. One gram can melt an entire metric ton of steel. In the novel, 2,074,000 kg of astrophage powered a spacecraft on a continuous-thrust interstellar voyage of 11.9 light-years to Tau Ceti.

### IX-PHM "Hail Mary" Astrophage Propulsion System
An engine type used when placing down the "Dawn" engine, which can be changed to the "IX-PHM" engine, with stats befitting an interstellar drive:

| Stat | Value |
|------|-------|
| **Vacuum ISP** | 1,500,000 s  |
| **Sea Level ISP** | 100,000 s |
| **Thrust** | 600 kN VAC, 40 kN ASL |
| **Mass** | 0.4 t |
| **Cost** | 144,380 funds |
| **Tech Node** | Ion Propulsion |

For comparison: the stock Dawn has 4,200s ISP / 2 kN thrust, and the LV-N has 800s ISP / 60 kN thrust. The Hail Mary drive is in another league entirely.

### Fuel Tank Switching
All fuel tanks gain **Astrophage** as a fuel type option via B9PartSwitch:
- LF/OX tanks, LF-only tanks, MonoPropellant tanks, and Xenon tanks all get an Astrophage option
- Works with CryoTanks and other B9PartSwitch-based mods (appends to existing switcher)
- Also works in stock installs with only B9PartSwitch (creates new switcher)

### Plume Details
As in the movie of *Project Hail Mary*, the engine produces a transparent exhaust plume. But details in the lab scene show an ever so slightly purple effect? So I made it so it's transparent, at least when tested with the waterfall mod.

---

## Lore Notes (from *Project Hail Mary*)

- Astrophages breed with a **doubling time of 8 minutes** when exposed to IR light from a celestial body with a CO₂-rich atmosphere
- They store energy absorbed from stars and release it as directed infrared photons
- The Hail Mary spacecraft used 2,062,236 kg of astrophage to travel from Earth to Tau Ceti (11.9 ly), arriving with just 11,764 kg remaining
- The ship could perform orbital insertion from ~40,000 km altitude with a 1-minute burn

*(Breeding mechanics are referenced in flavor text but not implemented as a game mechanic to keep the mod simple.)*

---

## Dependencies

**Required:**
- [ModuleManager](https://forum.kerbalspaceprogram.com/topic/50533-18x-112x-module-manager/) (4.x)
- [B9PartSwitch](https://forum.kerbalspaceprogram.com/topic/140541-18x-112x-b9partswitch/) (for fuel tank switching)

I recommend downloading mods with [CKAN](https://github.com/KSP-CKAN/CKAN/releases) instead of manually.

**Compatible With:**
- CryoTanks (fuel switching integrates seamlessly)
- Community Tech Tree
- Any mod that uses B9PartSwitch for fuel switching

---

## Installation

1. Copy the `GameData/Astrophage` folder into your KSP `GameData` directory
2. Ensure ModuleManager and B9PartSwitch are installed
3. (Recommended) Install Waterfall for the purple plume effect

Your `GameData` folder should look like:
```
GameData/
  Astrophage/
    Astrophage.version
    Parts/
    Patches/
    Resources/
    Waterfall/
  B9PartSwitch/
  ModuleManager.x.x.x.dll
  Squad/
  ...
```

---

## Gameplay Tips

- Even a small amount of astrophage goes an **incredibly** long way. A 100-unit tank (500 kg) on a 2-ton probe gives over 3,200 km/s of delta-v — enough for any mission in the stock Kerbol system many times over.
- Use sparingly for realistic-feeling interplanetary missions, or load up for interstellar adventures with mods like Outer Planets Mod or Kcalbeloh System.
- The engine works at sea level but is **far** more efficient in vacuum. Plan your burns for space. Small crafts *could* use it in atmosphere, but the TWR ramps up extremely quickly, which will have you burn up in the atmosphere.
- The high cost (200 funds/unit for fuel, 150,000 for the engine, 400,000 to unlock) provides a natural gameplay gate.
- The engine on a very small craft pulls a **lot** of Gs, be careful with crews missions that are small, and probes which don't have tons of reaction wheels.

---

## License

This mod is released for personal and community use.
