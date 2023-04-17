# Changelog  
  
| modName    | Oh Scrap! (OHS)                                                    |
| ---------- | ----------------------------------------------------------------- |
| license    | GPL-2.0                                                           |
| author     | severedsolo and zer0Kerbal                                        |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/192360-*/) |
| github     | (https://github.com/zer0Kerbal/OhScrap)                           |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/OhScrap)              |
| spacedock  | (https://spacedock.info/mod/2364)                                 |
| ckan       | OhScrap                                                           |

## Version 2.2.99.0-prerelease - `<允许降落伞损坏>` edition

* Released
  * 20 Dec 2022
  * for Kerbal Space Program 1.12.4
  * by zer0Kerbal

### Summary 2.2.99.0

* Maintenance release
  * Recompile for 1.12.4
  * <OhScrap.dll> v2.2.1.79 --> v2.2.99.97
  * only major code changes are for localization
  * OhScrap! windows are now afraid of `F2`
* Localization
  * English
  * Simplified Chinese (简体中文) courtesy of [ZhaoFJx](https://github.com/ZhaoFJx)
* Create hero logo/cover
* FIX:
  * [Bug]: FAR Parachute Incompability Due to Wrong MM Config
  * thank you to [T2Fat2Fl](https://github.com/T2Fat2Fly)
  * [Bug]: Incorrect mod settings descriptions/labels
  * [BUG]: make it so when battery is repaired it will have 1 ec
* Updated documentation
* *Experimental*
  * <RealAntennasFailureModule.cfg.0> v1.0.0.0
    * thank you. requested by [Gordon Dry](https://github.com/Gordon-Dry)
    * currently disabled

### Credit

* Finally proper credit given to
  * [Zelda](https://forum.kerbalspaceprogram.com/index.php?/profile/66411-*/) for ideas and support. The legend is real!
  * [eightiesboi](https://forum.kerbalspaceprogram.com/index.php?/profile/133828-*/) for ideas, support and testing!

### Code 2.2.99.0

* Recompile
  * KSP 1.12.4
  * .NET 4.7.2
  * C# 8.0
* <OhScrap.dll> v2.2.1.79 --> v2.2.99.100
* onGUI
  * GUI Hide on `<F2>`
* start of localization
  * us-en.cfg
* *Experimental*
  * <RealAntennasFailureModule.cfg.0> v1.0.0.0
    * thank you. requested by [Gordon Dry](https://github.com/Gordon-Dry)
    * currently disabled
    * temporarily removed (on hold)
      * Failure Sounds
      * Light Failure
      * Decoupler Failures
      * New settings
      * part failure sounds and settings
        * settings:
        * five soundfx selections
        * soundOn or Off on part failure
        * set to 0 for random sound
    * new GameData/OhScrap/Sounds
      * includes License.md (one file for all sound assets)
    * nine new sound clips
* closes #21 - OhScrap window doesn't get hidden when F2 is pressed
* closes #44 - 2.2.1.0 beta: radially attach in VAB - annoying sound mix of FirePager and PhoneVibrator
* closes #74 - [Bug 🐞]: Incorrect mod settings descriptions/labels
* closes #76 - [Bug 🐞]: FAR Parachute Incompability Due to Wrong MM Config
* closes #81 - [BUG]: when battery is repaired it has 0 ec
* updates #19 - audible alarm on failure
* updates #78 - [Request]: RealAntennaFailureModule

### Localization 2.2.99.0

* Initial code localization
* Create
  * Localization/
    * English
      * <en-us.cfg> v1.1.0.0
    * Simplified Chinese (简体中文)
      * <zh-cn.cfg> v1.1.0.0
      * thank you to [ZhaoFJx](https://github.com/ZhaoFJx)
      * added strings after submitted
    * [readme.md] v2.1.1.0
    * [quickstart.md] v1.0.1.0
* updates #54 - Localization - Master
* closes #55 - English <en-us.cfg>
* closes #63 - Simplified Chinese (简体中文) <zh-cn.cfg>
* closes #82 - [MISSING] #OHS-UPFME-BeyondRepair
* closes #80 - [BUG] debug PAW menu doesn't list what

### Documentation 2.2.99.0

* Add
  * [ManualInstallation.md] v1.1.7.0
  * [Attribution.md] v1.0.6.0
  * [404.md] v1.0.3.1
  * [Disclaimer.md] v1.0.0.0
  * [LegalMumboJumbo.md] v1.0.5.0
  * [Localizations.md] v1.1.3.1
  * [Marketing.md] v1.0.0.0
  * [Notices.md] v1.0.0.0
  * [PartInvoice.md] v1.1.3.1
  * [Why.md] v1.1.0.0
  * [_config.yml]
* closes #23 - Wiki
* closes #75 - Check Links in documentation

### Update License 2.0.99.0

* Updated License: GPL-2.0 + CC NC-BY-SA 4.0
  * was: Expat-MIT + CC NC-BY-SA 4.0

## Status 2.0.99.0

* Issues
  * closes #50 - OhScrap! (OHS) 2.2.99.0-prerelease `<允许降落伞损坏>`
  * closes #51 - 2.2.99.0 Verify Legal Mumbo Jumbo
  * closes #52 - 2.2.99.0 Update Documentation
  * closes #53 - 2.2.99.0 Update Social Media
  * closes #20 - Localization - duplicated
  * closes #22 - Dependancy check - duplicated
  * closes #25 - Localization - duplicated
  * closes #26 - Localization - duplicated
  * closes #27 - Localization - duplicated
  * updates #36 - update the ModWrappers

---

## Version - 2.2.0.0 `<Final Countdown...>`

* Released
  * 19 Jul 2021
  * for Kerbal Space Program 1.12.1
  * by zer0Kerbal

### Code

* recompile for KSP 1.12.1
* use .NET 4.7.2
* use C# 9.0
* update to Version.tt [v2.0.0.0]
* pull upstream changes from severedsolo (thank you)
* [OhScrap.dll] v2.2.1.79

### Update

* usual spring cleaning and automation
* folder structure
* to modern back-end automation

---

## Version = 2.1.1.1 `<More ways to Fail, and more Kerbals allowed to fix it (part II)>`

* Released
  * 02 Jun 2021
  * for Kerbal Space Program 1.9.1
  * by zer0Kerbal

### Repair 2.1.1.1

* fix Icon.ping (issue #11) by moving it where it should be
* other minor housekeeping items

### Update 2.1.1.1

* changelog to modern KerbalChangeLog standards

### Changed 2.1.1.1

* Back end  
  * add auto JSON  
  * update automation to latest version  
  * start working with yaclog-KSP (thank you cineboxandrew!)

---

## Version 2.1.1.0 `<More ways to Fail, and more Kerbals allowed to fix it>`

* folder restructuring
* improved workflow
* added 'Validate AVC .version files' workflow by @ DasSkelett (thank you @HebaruSan)
* added CONTRIBUTING.md
* added htm versions of Readme.md CONTRIBUTING.md to root
* included Readme.htm in future release
* internal automation updates

### Allow 'Mechanics' from USI to affect effets

* suggested by @dirk
* current code allowed Engineers (and only Engineers) a bonus to repairs
* adjusted code to allow any Kerbal with the "FailureRepairSkill" to receive a bonus to repairs
* FailureRepairSkill is a Stock skill that all Engineers have
* added a patch that adds FailureRepairSkill to USI MKS Mechanics
* easy to add "FailureRepairSkill" to other careers if requested by users

### New parts can fail!

* Implement engine under-thrust/under-Isp failures in a way that doesn't depend on thrust limiter.
* thank you to @bfrobin446
* ~~code from TestFlight~~ (thank you @Agathorn @linuxgurugamer et al)
* ~~section covering this code (CC BY-NC-SA 4.0) inserted into license file~~  

### Speed up new code

* thank you to @Lisias
* reset repository/code to 2.1.0.0
* updated to faster version of new EngineModuleWrapper.cs
* new code subject to GitHub ToS and to existing OhScrap License (MIT)

### Post Beta changes

* [BUG 2.1.0.0b] corrected 'Engineer' patch (was adding, not modifying FailureRepairSkill)
* [BUG 2.1.0.0a] Icon.png moved from /Plugins/ -> /Plugins/Textures/ to correct 
* [BUG 2.1.0.0c] moved "/GameData/OhScrap/PluginData/DefaultSettings.cfg" -> "/GameData/OhScrap/Plugins/PluginData/DefaultSettings.cfg"
* [BUG 2.1.0.0d] split game.settings into two columns for readability and allow for future expansion
* [BUG 2.1.0.0d] added bool ColoredPAW = treu to game.settings for future use
* [BUG 2.1.0.0e] corrected with a ^t (Alternators)
* [BUG 2.1.0.0f] added in tooltips and descriptive text

### Bug Status

* [D][NEW][BUG 2.1.0.0a] Texture resolution is not valid for compression: 'GameData\OhScrap\Plugins\Icon.png' - consider changing the image's width and height to enable compression
* [D][NEW][BUG 2.1.0.0b] ExperienceSystemConfig: Experience trait 'Engineer' already exists, and trying to add a duplicate Effect of 'FailureRepairSkill'
* [D][NEW][BUG 2.1.0.0c] "/GameData/OhScrap/PluginData/DefaultSettings.cfg" not found
* [D][NEW][BUG 2.1.0.0d] Too much information in Game.Settings page that it needs to scroll; needs reorganization
* [D][NEW][BUG 2.1.0.0e] typo: game.settings Alernators
* [WIP][NEW][BUG 2.1.0.0f] game.settings could use better/more explanation for what the settings are for

---

## Version - 2.1.0.0-release `<new maintainer, same great taste!>`

* recompile for KSP 1.9.1
* recompile with .NET 4.8
* folder restructure
* added version.tt / AssemblyVersion.tt
* adjust .csprog to zer0Kerbal
* adjust autobuild/deploy process to zer0Kerbal
* added Logger.cs
* use Version.Number from tt processes
* adjusted log path from /severedsolo/OhScrap/Logs/ to /OhScrap/Logs/

---

## Version = 2.0.1.0

* Fix NRE Spam and Slowdown

---

## Version 2.0.0.1

* Fix bad JSON in .version file

---

## Version = 2.0.0.0

* Recompile against KSP 1.8 / .NET 4.2.7
* Resized icon so KSP can properly compress it when using half res textures
* Added Alternator Failures
* Added Landing Gear Failures
* Support MADLAD's Install Validator

---

## Version 1.7.1.0

* Fix SRBs constantly spamming message app on failure

---

## Version 1.7.0.0

* Fixed RCS thrusters being allowed to fail when RCS is turned on
* Parachutes will now only fail while deployed
* Fixed an NRE that could occur when other mods apply MM patches after the Failure Module has attached itself to a part.
* Failure Modules will now cache all modules they need to interact with, instead of grabbing them on each FailPart() call.
* timeBetweenChecksRocketsSpace has now been split into timeBetweenChecksLocalSpace (Homeworld or its Moons) and timeBetweenChecksDeepSpace (everywhere else)
* timeBetweenChecksLocalSpace reduced to 20 minutes
* timeBetweenChecksDeepSpace increased to every roughly every 7.5 hours.
* Fixed an issue where SRBs would not post failures to the Messages App or Log they had happened.

---

## Version 1.6.3.0

* Force Editor Ship cache to refresh when it gets itself into an invalid state.

---

## Version 1.6.2.0

* Fixed issue where Editor Ship was being cached before it had any parts.
* UI will now point out that the Editor Ship has no parts, rather than just reporting Safety Rating 0.

---

## Version 1.6.1.0

* Fixed Typos in ParachuteFailureModule.cfg

---

## Version 1.6.0.0

* SEVEREDSOLO: Fixed DivideByZero exception in Editor when no FailureModules were actually present on the craft.
* SEVEREDSOLO: Removed unnecessary onEditorShipModified event. All Safety Ratings are now calculated in Update() instead.
* ALL OTHER CHANGES BY NIPPERYSLIPPLES
* Remote tech antennas can now fail, will only do so when deployed (you can pack backups) and will show as properly malfunctioned when they are failed.
* Antenna Failures no longer happen if commnet is disabled (they previously happened, but did nothing except add highlight).
* Minor performance improvements in several Failure Modules.
* Fixed repairs not being available in some situations.
* Mod will no longer Spam NRE's if FAR is installed and Control Surface Failures are enabled.
* Added ModWrapper class to facilitate FAR and RemoteTech compatibility.
* AntennaFailureModule will no longer be added to parts if RemoteTech is installed.
* ControlSurfaceFailureModule will no longer be added to parts if FAR is installed.
* Added support for FAR and FAR's implementation of RealChute. See https://github.com/severedsolo/OhScrap/pull/18 for details.

---

## Version 1.5.1.2

* Changed the license in the Github repo back to MIT

---

## Version = 1.5.1.1

* Rerelease due to not shipping the DLL

---

## Version = 1.5.1.0

* Recompiled against KSP 1.6.1
* Fixed SRBs rolling 4-5 times before launch (which was leading to the abnormally high failure rates)
* Fixed all parts automatically being tested because apparently vessel.speed is not relative to the vessel.....
* Fixed SRB safety ratings not really reflecting the parts likelyhood to fail.
* Fixed invalid characters in EngineFailureModule patch
* Fixed Space Engine (Terrier etc) always having a Safety Rating of 1 and simultaneously being physically capable of failing.
* Logger will create Logs directory if it doesn't exist
* Slightly reduced baseFailureChance of SRBs

---

## Version = 1.5.0.0

* Recompiled against KSP 1.6.0 (1.5.x should continue to work fine)
* Fixed issue where failure rolls would be spammed in prelaunch
* Exposed baseFailureChance and expectedLifetime for Space Engines in the MM config for EngineFailureModule
* Added bash script to automate release build process (only relevant if you are compiling from source, but it's in the Github Repo so mentioned it here)

---

## Version = 1.4.2.0

* Fixed SRBs being allowed to fail during KRASH simulations (for real this time)

---

## Version = 1.4.1.0

* Fixed SRBs being allowed to fail during KRASH simulations

---

## Version = 1.4.0.0

* CKAN USERS ONLY: Kerbal Changelog by Benjamin Kerman is now a required dependency
* MANUALLY INSTALLED USERS: Kerbal Changelog by Benjamin Kerman is bundled as an optional (but recommended) mod.
* Recompile against KSP 1.5.1
* Failures will no longer be calculated per part. Instead, we'll take into account the overall reliability of the vessel, and use that to determine failure rates. (Ie, if you stick a bunch of really good parts on your rocket, and one really crappy one, the rocket will still be less prone to fail than one with all crappy parts). A really cool side effect of this, is that if you stage away your bad parts, your vessel will become more reliable overall (ie, you can have a bad launch vehicle, but a tried and tested payload, and once the launch vehicle is gone, the payload will be uber reliable).
* Failures will be rolled for constantly (but rate limited) instead of just on loading the vessel. At the moment, it's every 10 seconds in atmosphere for the first two minutes, every 2.5 minutes after that while in atmosphere (known as "plane mode") and every 30 kerbal minutes out of the atmosphere - to simulate the fact that things are much more likely to go wrong on launch.
* All of the above parameters can be edited in DefaultSettings.cfg which is located at OhScrap/PluginData
* Parts can only fail if they are actually in use (ie engines firing, Reaction wheels turning, etc) - this may have been technically in the last version, but I found a bunch of places where it wasn't actually turned on.
* Overall rebalance of the reliability system
* Remote Repair has been reduced to a 20% chance of success, EVA to 40% and engineers will give a 10%*their level boost to the repair chance (so a Lv5 Engineer will give you a 90% chance of repair on EVA).
* MASSIVE code cleanup - handling the failures on a per vessel, rather than per part basis means less garbage, better performance and easier for me to maintain etc. I've also moved a BUNCH of duplicated code into their own common methods.
  * Parts that have not been tested/launched can now be recovered. The tradeoff for this is that those parts will receive NO bonuses for recovery. Ie, it will still have the failure rate of a "fresh off the factory line" part.
  * Parts that have not been tested/launched can now be recovered. The tradeoff for this is that those parts will receive NO bonuses for recovery. Ie, it will still have the failure rate of a "fresh off the factory line" part.
  * Randomisation is gone. Parts will have standard failure rates.
  * Safety Rating system now runs from 1-10 rather than 1-5
* Safety Ratings are now relative rather than absolute (ie it's linked to the parts base reliability, not a fixed number)
* Mod will log to the OhScrap/Logs folder
* "Extra Logging" option will show you every roll and a guess at the probability of a part failing in the next 2 minutes/15 minutes/30 days (depending on the Vessels Situation). Note that this can be inaccurate in some situations.
* You can also see this information in the UI by creating an empty text file called debug.txt in the Oh Scrap Directory (all lower case if your OS cares about such things)
  * Probably a bunch of other stuff I'm not remembering right now.
* Added option to override Stage Recovery and recover parts but no funds. Please note this is highly experimental and may not even work at all.

---
