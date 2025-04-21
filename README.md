### Kerbalism Compatibility Overhaul

**Made by Wigglearms, with a patch by jessicest**
*Thanks to all the amazing people who have helped develop Kerbalism and to jessicest for a SSPXr patch!*

*Kerbalism Compatibility Overhaul (KCO)* is a modular patch suite for Kerbal Space Program that expands and enhances Kerbalism's realism, while integrating it more smoothly with other popular mods.

#### Patches and Compatibility:

**Default Kerbalism**:
- Completely overhauls/provides the default resource distributions, including Ore. Feedback on balancing is welcome!
- Allows Oxidizer to be extracted from Eve's oceans.
- Adds an Oxidizer Decomposition process to converters which produces Water and Hydrogen from Oxidizer.
- The previous change, along with Eve's CarbonDioxide atmosphere makes it a refueling haven - if you're up for the challenge.
- Allows Ammonia to be mined from ices in planetary crusts.

**CryoTanks**:
- Replaces the default Sabatier process with one which produces the more realistic LCH4 instead, giving Methane engines the benefit of easy ISRU.
- Adds a new Hydrocarbon Synthesis process to converters to allow for (slow, complicated, and late-game) off-world LiquidFuel production. Refueling your planes on Laythe? Use this process.
- Unfortunately, cryotank cooling Electric Charge consumption still isn't reflected in the planner. Any help is appreciated!

**Far Future Technologies**:
- Converts the Antimatter Facility and Nuclear Smelter to use Kerbalism processes.

**Near Future Electrical**:
Kerbalism's original support for this mod is outdated - this includes patches to support renamed parts. Changes include:
- Re-adds radiation emitters to Fission Reactors and RTGs.
- Restores the Nuclear Reprocessor to full functionality including Kerbalism processes
- Converts the RTGs to use Kerbalism's RTG mechanics.
- Revamps/provides Uraninite distributions.

**Near Future Propulsion**:
- Allows Lithium to be mined from planetary crusts.
- Provides Lithium resource distributions.

**SimpleConstruction!**:
- Splits Ore into two resources - Rock and Ore. Rock represents non-metallic regolith, while Ore represents regolith which can be processed into space-grade metal.
- Provides Rock resource distributions.
- Replaces the Molten Regolith Electrolysis process with one that consumes Rock instead of Ore.
- Adds an Ore Refiner process to converters which smelts Ore into Metal, replacing SimpleConstruction's implementation.
- Allows laboratory parts (supports the stock lab and labs from SSPX, Mk2 Expansion, and Mk3 Expansion) to be configured with a part workshop. This replaces SimpleConstruction's Metal to RocketParts converters and was pretty interesting to design - each workshop can support multiple Kerbals, and each supported Kerbal contributes to the conversion speed. Note that Kerbals now "fidget" consuming a tiny amount of Electric Charge, but this allows them to work properly assembling parts in the labs.

**Stockalike Station Parts Expansion Redux**:
- Resolves an oversight by providing proper Kerbalism science support for the small telescope and its lab-attached variant. Now with animation integration!
- Cleans up the logistics modules and fixes some subtype switching, though I can't seem to do anything about the decals not working.
- Includes a patch by jessicest (https://github.com/Kerbalism/Kerbalism/pull/896) to add habitats to pressurized structural parts.

## Current Version: v1.0.0

**Download**: **[GitHub]** - **[CKAN]** - **[SpaceDock]**
**KSP Version**: **Tested only on 1.12.5** in a heavily modded save (That's probably bad, I know)
**Dependencies**: **Requires [Kerbalism] and its dependencies**
**Support**: **[Discord]** - **[FAQ]** - **[GitHub Issues]** - **[KSP Forums]**
**License**: **[Unlicense]** (public domain)

**Future Plans**:
Resource distributions/Harvesting to Asteroids and Comets
No other plans the moment, unless I can figure out how to fix the cryotank planners or cause Kerbalism processes to produce heat for SystemHeat.

## Using KCO

**Download from [GitHub], [SpaceDock], or use [CKAN]**

All patches are sorted into folders by mod, so if you aren't using one or more of these mods simply disable or remove their sub-folders from this mod. While (probably) not required for functionality, removing unneeded patches may reduce loading times, etc.

## More Mods
- **[CompatibilityPatchesPlus]**: Not compatible enough? Browse this collection of small Module Manager patches to enhance your other mods!
- **[SSPXHatchConnector]**: If you've ever wanted to build surface bases with SSPX but run into trouble with their vertically-oriented IVAs, this mod lets you attach parts to their external airlock hatches, allowing FreeIVA-compatable connections between the buildings of your bases.

## Disclaimer and license

This mod is released under the [Unlicense], which means it's in the public domain. *Although I wouldn't mind being credited in derivative works :)*
