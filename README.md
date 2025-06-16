# Alcoholic Aeronautics
![logo.png](https://raw.githubusercontent.com/CharleRoger/AlcoholicAeronautics/main/logo.png)
![header.png](https://raw.githubusercontent.com/CharleRoger/AlcoholicAeronautics/main/header.png)

This is a mod for Kerbal Space Program which adds a collection of low-tech liquid rocket engines which burn ethanol, based loosely on the real early history of rocketry. The intent is to provide an alternate liquid-fuelled start to the tech tree, giving slightly slower early progression with a bit more depth. This mod was designed primarily to fit into the chemical-based technological progression of Chemical Propulsion, another one of my mods, but plays just fine as a stand-alone.

## Features
### Parts
The mod contains nine engines which fall into three technological generations. If there is enough interest, two or three extra engines may be added in the future.
![engines.png](https://raw.githubusercontent.com/CharleRoger/AlcoholicAeronautics/main/engines.png)
#### First generation
These engines cannot be throttled or shut down and have no intrinsic gimbal. Instead, an external housing with graphite jet vanes used to divert the exhaust can be optionally added for a small cost and mass. They also require an additional 1% of the total volumetric propellant flow rate in MonoPropellant, emulating the use of hydrogen peroxide in generating steam to drive the gas generator. Before external monopropellant tanks are unlocked, each first-generation engine is constrained by the amount of monopropellant it holds in its internal tank.
- **AA-1 "Rummer" Ethanol Engine** — Based on the A-4/V-2 and Soviet derivative RD-100 used in the R-1 missile.
- **AA-3 "Charka" Ethanol Engine** — Based on the RD-103, the final Soviet version derived from the V-2, used in the R-5 missile.
- **AA-6 "Highball" Ethanol Engine** — Based on the A-6/A-7 built for the Jupiter-C and subsequent Mercury-Redstone Launch Vehicle which propelled the first American astronauts (and an astrochimp) into space.
- **AA-6-4 "Old Fashioned" Ethanol Engine** — A cluster of four AA-6 engines, entirely fictional.
#### Second generation
Monopropellant is no longer required and the engines become more specialised. Some engines have proper gimballing
- **AA-15 "Shot" Ethanol Engine** — Based on the XLR11 used in the Bell X-1 experimental aircraft and later the North American X-15 while the XLR99 was not yet ready.
- **AA-15-2 "Double" Ethanol Engine** — A pair of AA-15 engines with a common boattail, as they appeared on the X-15.
- **AA-21 "Flute" Ethanol Engine** — Based loosely on the XLR71-NA-1 developed for the Navaho missile, but later scrapped in favour of the kerosene-fuelled XLR83-NA-1.
#### Third generation
Engines with a bit more versatility and slightly more impressive performance, so ethanol does not become totally useless once classic LFO engines are unlocked.
- **AA-28 "Teku" Ethanol Engine** — Based on the RS-88 which was originally designed to use ethanol, but better known due to a hypergolic variant used as the launch escape motor of Boeing's CST-100 Starliner.
- **AA-28-V "Chalice" Ethanol Engine** — A vacuum-optimised variant of the AA-28 with two nozzle extension variants.
### Other changes
Ethanol and Ethanol/Oxidizer subtypes are added to the fuel switch provided by CryoTanks, which I assume you must already be using if you have any interest in a mod like this. In order to support an ethanol-first tech progression, early liquid and solid rocket engines and fuel tanks are rearranged in the tech tree and some minor changes are made to the Mk1 Command Pod.

## Dependencies
- [ModuleManager (4.2.3)](https://github.com/sarbian/ModuleManager)
- [B9PartSwitch (2.20.0)](https://github.com/blowfishpro/B9PartSwitch)
- [Community Resource Pack (112.0.1)](https://github.com/UmbraSpaceIndustries/CommunityResourcePack)
- [CryoTanks (1.6.6)](https://github.com/post-kerbin-mining-corporation/CryoTanks)

## License and attribution
Alcoholic Aeronautics by Charles Rogers is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

This mod makes extensive use of assets from other mods distributed under open licenses, which I have modified to varying degrees:
- RD-100 by Alcentar for RealEnginesPack (GPLv2)
- A-7 by passinglurker for CobaltWolf's Bluedog Design Bureau (CC BY-NC-SA 4.0)
- XLR-11 by Alvin Meng for Astral Manufactures (CC BY-NC-SA 4.0)
- RS-88 by Zorg for DylanSemrau/SofieBrink/Zorg's Boring Crew Services (CC BY-NC-SA 4.0)
