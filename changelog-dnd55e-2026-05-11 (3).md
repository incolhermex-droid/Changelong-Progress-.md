# 📜 Changelog — DnD 5.5e All-in-One BEYOND
> **Repository:** [Yoonmoonsik/dnd55e](https://github.com/Yoonmoonsik/dnd55e) · **Branch:** `main`

## May 11, 2026

### 🟢 Add SLevel 1, 2 Draconic Sorcery Spells #220

[`ae458d6`](https://github.com/Yoonmoonsik/dnd55e/commit/ae458d675b1fdc9bd3bc063239b1ae5a8c07d183) · *yoonmoonsik*

Fixed issues in the passive/feature data structure affecting how actor abilities are registered and resolved in the 5.5e system.

Adjusted generated rule data to ensure proper integration with core combat and class feature handling systems.

---

### 🔴 fix #223

[`cb553f4`](https://github.com/Yoonmoonsik/dnd55e/commit/cb553f46cb2ffa1faaa30c19a8805f3ab72ed2c1) · *yoonmoonsik*

Added missing VOW_OF_ENMITY status definition and linked it to base BOOST system data.

Fixed VOW_OF_ENMITY_RECAST by restoring proper display name, icon, and removing incorrect stack/type and status flags.

Updated localization entry for “Vow of Enmity” to properly reference the new status handle.

---

### 🔴 Merge pull request #221 from incolhermex-droid/patch-8

[`8e96759`](https://github.com/Yoonmoonsik/dnd55e/commit/8e96759f513fde5991fe0bbcb4e918d698c71281) · *Yoonmoonsik*

Fixed Latin Spanish localization for “Inspired Movement” passive description.

Corrected wording to properly reflect that affected allies no longer provoke Opportunity Attacks when moving.

---

### 🔴 Merge pull request #222 from incolhermex-droid/patch-9

[`3bf098f`](https://github.com/Yoonmoonsik/dnd55e/commit/3bf098fc5839e308b48c96a202cfbe42d7a51171) · *Yoonmoonsik*

Fixed Spanish localization for “Inspired Movement” passive description.

Clarified wording to correctly state that affected allies do not provoke Opportunity Attacks when using the feature.

---

### 🔴 fix #224

[`8f380ec`](https://github.com/Yoonmoonsik/dnd55e/commit/8f380ec0ba608fd32fdaa41065b9ab95ad46bfc6) · *yoonmoonsik*

Fixed Phantom Steed status application duration inconsistency by correcting ApplyStatus duration value from 10 to 100.

Synchronized runtime and generated spell data to ensure consistent status duration across SpellData and Generated definitions.

---

### 🔴 Update fix 1.0.4 spanish.xml

[`66157bd`](https://github.com/Yoonmoonsik/dnd55e/commit/66157bd351d6e8fe533def19966674c2431b5b09) · *incolhermex-droid*

Fixed Spanish localization for Inspired Movement description.

Updated wording to correctly state that affected allies do not provoke Opportunity Attacks when moving under the feature.

---

### 🔵 Update latinSpanish.xml

[`503bd84`](https://github.com/Yoonmoonsik/dnd55e/commit/503bd844d88b518ac8563985517eaaef0b9e042c) · *incolhermex-droid*

Fixed Latin American Spanish localization for Inspired Movement passive description.

Corrected translation to properly state that affected allies do not provoke Opportunity Attacks when using the feature.

---

## May 10, 2026

### ⚪ 4.3.12.11

[`bd03744`](https://github.com/Yoonmoonsik/dnd55e/commit/bd03744cacddee44de3bacb31222abb50b19b3ae) · *yoonmoonsik*

Version bump to 4.3.12.11. 

Updates the mod's internal MD5 checksum and Version64 identifier in `meta.lsx` to reflect the latest build.

---

### 🔴 Merge pull request #213 from incolhermex-droid/patch-6

[`19be047`](https://github.com/Yoonmoonsik/dnd55e/commit/19be0470cb7fe17f33157253a34c54b30466eee8) · *Yoonmoonsik*

Added Latin Spanish localization entries for the **Elven Accuracy** feat, including its name (*Precisión Élfica*) and full description. 

Players using the Spanish localization will now see correct translations for this feat's passive reroll mechanic on Dexterity, Intelligence, Wisdom, or Charisma attack rolls made with Advantage.

---

### 🔴 Merge pull request #214 from incolhermex-droid/patch-7

[`dcd67c7`](https://github.com/Yoonmoonsik/dnd55e/commit/dcd67c79dcda302deb5d23bf1aece4cee2eb466e) · *Yoonmoonsik*

Updated the Castilian Spanish localization (`spanish.xml`) with two fixes: the **Goliath** race description now correctly includes the carry weight bonus from Giant Ancestry, and **Elven Accuracy** feat entries (*Precisión Élfica*) have been added with their name and full passive description.

---

### 🔴 fix #209

[`45f43be`](https://github.com/Yoonmoonsik/dnd55e/commit/45f43be527cd002436b010ae1c87e95232debd0d) · *yoonmoonsik*

Fixed the College of Dance “Inspiring Movement” description to correctly state that allied movement no longer provokes Opportunity Attacks.

Updated related localization, spell data references, and generated target data to reflect the corrected tooltip behavior.

---

## May 8, 2026

### 🔵 Update 1.0.3 spanish.xml

[`caee4b7`](https://github.com/Yoonmoonsik/dnd55e/commit/caee4b711295951a9329e19b9c90c3959153c9a8) · *incolhermex-droid*

Updated Spanish localization entries for Elven Accuracy and Goliath racial traits.

Clarified Goliath carry weight increase wording and corrected missing translation details in the Spanish localization file.

---

### 🔵 Update1.0.3 latinSpanish.xml

[`1c9558c`](https://github.com/Yoonmoonsik/dnd55e/commit/1c9558cdf3088e32ffff711cc7d637e5b7f320fe) · *incolhermex-droid*

Updated Latin American Spanish localization for Elven Accuracy.

Fixed missing feat description text and corrected localization formatting in the Spanish translation files.

---

### 🔴 fix #202

[`fa8c917`](https://github.com/Yoonmoonsik/dnd55e/commit/fa8c9178c6cb2ec7ac6269b36002c3fc4abf9deb) · *yoonmoonsik*

Updated Latin American Spanish localization for Elven Accuracy and related description entries.

Fixed missing translation text and corrected formatting issues in the localization XML file.

---

### 🔴 fix #208

[`4a8a291`](https://github.com/Yoonmoonsik/dnd55e/commit/4a8a291889b30144d6a8e0c7c3e4651bff88c18c) · *yoonmoonsik*

Fixed Fount of Moonlight status effects by adding Radiant damage resistance to the associated boost data.

Updated generated status entries to properly apply the intended defensive effect during gameplay.

---

### 🔴 fix #206

[`fc07c9a`](https://github.com/Yoonmoonsik/dnd55e/commit/fc07c9aa6b81005007eeea14c633e09987f56328) · *yoonmoonsik*

Reworked Elven Accuracy to use a dedicated interrupt-based reroll system instead of passive boost handling.

Added proper advantage condition checks, reroll prompts, and updated related localization entries for the feat.

---

## May 7, 2026

### 🔴 Merge pull request #204 from incolhermex-droid/patch-5

[`5bafced`](https://github.com/Yoonmoonsik/dnd55e/commit/5bafced0b120919cb3054a7e81b5ecc3f272e1e8) · *Yoonmoonsik*

Updated Latin American Spanish localization for Human racial traits and related feature descriptions.

Added missing translations for Versatile, Skillful, Keen Senses, and updated attack replacement wording for cantrip casting.

---

### 🔵 Update1.0.2 latinSpanish.xml

[`dbbf0b1`](https://github.com/Yoonmoonsik/dnd55e/commit/dbbf0b18c039c9e32a75aef3b3f3043f0a5c6f22) · *incolhermex-droid*

Updated Latin American Spanish localization for Human racial traits and combat-related feature descriptions.

Added missing translations for Versatile, Skillful, Keen Senses, and cantrip attack replacement functionality.

---

## May 6, 2026

### ⚪ 4.3.12.9

[`5a8c740`](https://github.com/Yoonmoonsik/dnd55e/commit/5a8c74012b9a826ec565beb6aad5a909ebc1d318) · *yoonmoonsik*

Added support for replacing one attack during the Attack action with a cantrip cast.

Updated related localization entries and passive descriptions to reflect the new combat interaction behavior.

---

### ⚪ QoL Invoke Duplicity

[`f33a415`](https://github.com/Yoonmoonsik/dnd55e/commit/f33a415af27eaefb511f676d3e948272633a5487) · *yoonmoonsik*

Added QoL improvements to Invoke Duplicity by enabling character-based AoE condition handling for the spell target.

Updated generated spell target data to improve duplicate placement and targeting behavior consistency.

---

### 🔴 fix #201

[`0ca69e7`](https://github.com/Yoonmoonsik/dnd55e/commit/0ca69e7ac166cb348339c7d67c0b73798d29dc29) · *yoonmoonsik*

Fixed incorrect application conditions for the Stunning Strike passive effect.

Updated Monk interrupt handling and passive trigger data to improve combat consistency and prevent invalid activation states.

---

### 🔴 fix #200

[`aef7e65`](https://github.com/Yoonmoonsik/dnd55e/commit/aef7e656adc844b88283da4540f771a613343370) · *yoonmoonsik*

Added support for choosing between grappling or pushing targets after an Unarmed Strike hit.

Implemented new interrupt handling and passive trigger logic to support the updated combat interaction flow.

---

### 🔴 fix #199

[`86e7a74`](https://github.com/Yoonmoonsik/dnd55e/commit/86e7a74ade745fb7c251c4956de7c10a5afccd2a) · *yoonmoonsik*

Fixed an issue with the **Dual Wielder** feat where the off-hand attack spell was incorrectly available regardless of weapon type. 

Added proper requirement conditions so the bonus attack only unlocks when the source is a dual-wielder equipped with a melee weapon.

---

## May 5, 2026

### 🔴 fix #169

[`10881ae`](https://github.com/Yoonmoonsik/dnd55e/commit/10881ae8cb307c3a044baffff36e6910c6f370a2) · *yoonmoonsik*

Fixed **Wrath of the Sea** (Circle of the Sea Druid Wild Shape) not applying its once-per-turn cooldown correctly. 

Added a first-turn status (`WILDSHAPE_SEA_FIRSTTURN`) that grants a free-cost cast of the ability on the turn Wild Shape is entered, resolving the interaction with the turn tracking system.

---

### 🔴 fix #196

[`420be40`](https://github.com/Yoonmoonsik/dnd55e/commit/420be406cc150e196762f8ca838fdd258e24b894) · *yoonmoonsik*

Resolved a reported bug affecting combat spell or passive behavior. 

Internal stat and condition logic was adjusted to correct the broken interaction flagged in issue #196.

---

### 🔴 fix #191

[`72f0667`](https://github.com/Yoonmoonsik/dnd55e/commit/72f06679083e90cfec4ade889d5111f61feeea97) · *yoonmoonsik*

Addressed the bug reported in issue #191. 

Corrected faulty stat entries or spell logic causing an unintended behavior in combat or character mechanics.

---

### ⚪ 4.3.12.7

[`3e43c6b`](https://github.com/Yoonmoonsik/dnd55e/commit/3e43c6b7a1b0986c475482abc5c59c61fa60debf) · *yoonmoonsik*

Version bump to 4.3.12.7. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 Merge pull request #192 from incolhermex-droid/patch-4

[`883cec3`](https://github.com/Yoonmoonsik/dnd55e/commit/883cec324a90eea6ae41e075ca813f5b7939fd96) · *Yoonmoonsik*

Merged community contribution from `incolhermex-droid` (patch-4). 

Integrates fixes or localization updates submitted via pull request #192.

---

## May 4, 2026

### 🔵 Update1 spanish.xml

[`0f8fbcf`](https://github.com/Yoonmoonsik/dnd55e/commit/0f8fbcf9a073b45a89560ed3b7414aa37c0e2272) · *incolhermex-droid*

Updated the Castilian Spanish localization file with new or corrected translation entries. 

Part of the ongoing community effort to keep the Spanish translation up to date with mod content.

---

## May 3, 2026

### ⚪ 4.3.12.6

[`6995399`](https://github.com/Yoonmoonsik/dnd55e/commit/6995399f4c8682f25a29982d47de920e51d3ca17) · *yoonmoonsik*

Version bump to 4.3.12.6. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix #170

[`a08b7f6`](https://github.com/Yoonmoonsik/dnd55e/commit/a08b7f6ec643a8896da670b2ac0f8f16c9a225b7) · *yoonmoonsik*

Fixed the bug reported in issue #170. 

Corrected a broken passive, spell, or trigger condition causing incorrect behavior in the affected mechanic.

---

### 🔴 fix #172

[`8fd9a30`](https://github.com/Yoonmoonsik/dnd55e/commit/8fd9a30137091d7f7246f83d8e4c23851d3effb4) · *yoonmoonsik*

Fixed the bug reported in issue #172. 

Adjusted stat definitions or spell conditions to resolve the unintended interaction or missing functionality.

---

### 🔴 fix #174

[`ba279c2`](https://github.com/Yoonmoonsik/dnd55e/commit/ba279c2e7d510cdaf1ea072ee630bf0e0082f503) · *yoonmoonsik*

Fixed the bug reported in issue #174. 

Corrected faulty logic in the relevant spell, passive, or status effect.

---

## April 29, 2026

### ⚪ 4.3.12.5

[`94fc0c3`](https://github.com/Yoonmoonsik/dnd55e/commit/94fc0c32e043b9e559728d06bbd7416849664c2a) · *yoonmoonsik*

Version bump to 4.3.12.5. 

Updates internal build metadata in `meta.lsx`.

---

### 🟣 updtae Spanish language

[`f63b668`](https://github.com/Yoonmoonsik/dnd55e/commit/f63b668b686c7401870e6cdaa2e3682fd3aca853) · *yoonmoonsik*

Updated the Spanish localization file with new translation entries to cover recently added or modified mod content.

---

### 🔴 fix holyavenger aura

[`4678db8`](https://github.com/Yoonmoonsik/dnd55e/commit/4678db86754ca3e19ee0f2acb540b1f4a99135c5) · *yoonmoonsik*

Fixed the **Holy Avenger** weapon aura not functioning correctly. 

Corrected the aura's passive trigger or boost logic so it properly applies its radiant damage bonus and advantage on saving throws against spells to nearby allies.

---

### ⚪ 4.3.12.3

[`ad2d8ff`](https://github.com/Yoonmoonsik/dnd55e/commit/ad2d8ffabcb7ee0462597ef8e2c2825225b4020f) · *yoonmoonsik*

Version bump to 4.3.12.3. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix Charger_Push

[`50ba4b9`](https://github.com/Yoonmoonsik/dnd55e/commit/50ba4b904a75ac2cc57b3d032e1a4fdfe7b14786) · *yoonmoonsik*

Fixed the **Charger** feat's push effect not working as intended. 

Corrected the shove/push spell logic triggered after a Dash action charge attack so it correctly knocks back targets.

---

### 🔴 minor fix

[`4324315`](https://github.com/Yoonmoonsik/dnd55e/commit/4324315092a6c6d128df2c67a4b9bc2bd933b2b4) · *yoonmoonsik*

Applied a minor correction to a stat entry, condition, or flag that was causing a small unintended behavior in the mod.

---

### 🟢 add tooltips

[`26990fa`](https://github.com/Yoonmoonsik/dnd55e/commit/26990fa10f0043974190f9102f1ffa5da5e0e867) · *yoonmoonsik*

Added missing tooltips to various abilities, spells, or passives. 

Players will now see proper in-game descriptions when hovering over the affected mechanics.

---

### 🔴 fix #163

[`ee9168c`](https://github.com/Yoonmoonsik/dnd55e/commit/ee9168cc211e024f2e6ae6acbfcd6a026b9a4d42) · *yoonmoonsik*

Fixed the bug reported in issue #163. 

Resolved a faulty interaction in the relevant spell, passive, or status that was causing unintended behavior.

---

### 🔴 fix #155

[`f6284fb`](https://github.com/Yoonmoonsik/dnd55e/commit/f6284fb0e7972e49d4091eb11c47590af1537da8) · *yoonmoonsik*

Additional fix for issue #155. 

Addressed a remaining edge case in the previously reported mechanic.

---

## April 28, 2026

### ⚪ 4.3.12.2

[`7a0b0aa`](https://github.com/Yoonmoonsik/dnd55e/commit/7a0b0aada1e90443ab857c15accb4ea5c843fe09) · *yoonmoonsik*

Version bump to 4.3.12.2. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix #155

[`f901f9c`](https://github.com/Yoonmoonsik/dnd55e/commit/f901f9c1df4bf3ffd2610533dc1c21be076fea33) · *yoonmoonsik*

Fixed the bug reported in issue #155. Corrected a broken spell, passive, or status interaction flagged by the community.

---

### 🔴 fix #156

[`fdfb861`](https://github.com/Yoonmoonsik/dnd55e/commit/fdfb86168a5b99c2fbef4ebd62b9f4545bd78083) · *yoonmoonsik*

Fixed the bug reported in issue #156. 

Adjusted the relevant stat or spell logic to restore expected behavior.

---

### 🔴 minor fixes

[`d8533f7`](https://github.com/Yoonmoonsik/dnd55e/commit/d8533f7cc65a7823d8e37f7068831267547e3161) · *yoonmoonsik*

Applied several small corrections across multiple stat entries or spell definitions to address miscellaneous reported issues.

---

## April 27, 2026

### ⚪ 4.3.12.1

[`bc3df0a`](https://github.com/Yoonmoonsik/dnd55e/commit/bc3df0aeef4c9cb98d25bf2e2922897e50a56929) · *yoonmoonsik*

Version bump to 4.3.12.1. 

Updates internal build metadata in `meta.lsx`.

---

### ⚪ 4.3.12

[`dfde6c3`](https://github.com/Yoonmoonsik/dnd55e/commit/dfde6c3ec98664a3f7f1e49573e3036631f05268) · *yoonmoonsik*

Version bump to 4.3.12. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix #154

[`e937cc2`](https://github.com/Yoonmoonsik/dnd55e/commit/e937cc20b9c4337221932735cac2934cee2432a3) · *yoonmoonsik*

Fixed the bug reported in issue #154. 

Corrected the relevant spell or passive stat logic causing the unintended behavior.

---

### 🟢 add Dhampir and Kalashtar

[`3b6475b`](https://github.com/Yoonmoonsik/dnd55e/commit/3b6475bce93f1d79b0da0f08f6bcf47e214d2e81) · *yoonmoonsik*

Added **Dhampir** and **Kalashtar** as playable lineages. 

Implements their unique racial traits — Dhampir's vampiric bite and Spider Climb, and Kalashtar's telepathic abilities and psychic resistance — as defined in the 2024 D&D rules.

---

## April 26, 2026

### ⚪ 4.3.11

[`cb3a0f5`](https://github.com/Yoonmoonsik/dnd55e/commit/cb3a0f5d221f3793d84eb51066594c1edd68cb04) · *yoonmoonsik*

Version bump to 4.3.11. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix #133

[`c85ec9e`](https://github.com/Yoonmoonsik/dnd55e/commit/c85ec9e58d6894a68fd7163b01f571780da5a2f3) · *yoonmoonsik*

Fixed the bug reported in issue #133. 

Corrected a broken passive or spell interaction that was causing incorrect behavior for the affected mechanic.

---

### 🟢 add new druid subclass: Circle of Dreams

[`852a9b7`](https://github.com/Yoonmoonsik/dnd55e/commit/852a9b700dd02ec47b0cf292d20b4ca2a11df2dd) · *yoonmoonsik*

Added the **Circle of Dreams** as a new Druid subclass. 

Implements its full feature set including Balm of the Summer Court (healing pool), Hearth of Moonlight and Shadow (short rest camp bonus), and Hidden Paths (teleportation via the Feywild).

---

### ⚪ 4.3.10.4

[`c055548`](https://github.com/Yoonmoonsik/dnd55e/commit/c055548237908aa60dbb75e9a7c12927b92e7a68) · *yoonmoonsik*

Version bump to 4.3.10.4. 

Updates internal build metadata in `meta.lsx`.

---

### 🔵 update spanish

[`f12da2a`](https://github.com/Yoonmoonsik/dnd55e/commit/f12da2a34a871e4cfdd65ec2838ed12de42e62e8) · *yoonmoonsik*

Updated the Spanish localization file with corrections or new entries to reflect the latest mod content changes.

---

### 🔴 fix #149

[`b9a2f13`](https://github.com/Yoonmoonsik/dnd55e/commit/b9a2f13be1f06ab034857e93bb477ffa1f4342ea) · *yoonmoonsik*

Fixed the bug reported in issue #149. 

Adjusted the relevant spell or passive condition to restore expected functionality.

---

### 🔴 fix #144

[`1cafa1b`](https://github.com/Yoonmoonsik/dnd55e/commit/1cafa1b002e620311d538e32a7942df7e28c70c1) · *yoonmoonsik*

Fixed the bug reported in issue #144. 

Corrected a broken interaction in the affected mechanic's stat or trigger logic.

---

### 🔴 fix #148

[`f2f249d`](https://github.com/Yoonmoonsik/dnd55e/commit/f2f249d6dd0d2b77954cffd21d4b085899da11de) · *yoonmoonsik*

Fixed the bug reported in issue #148. 

Resolved the reported unintended behavior by adjusting the relevant spell, passive, or condition entry.

---

## April 24, 2026

### ⚪ 4.3.10.2

[`03c4832`](https://github.com/Yoonmoonsik/dnd55e/commit/03c4832d0c79d7b6c14bd56b0e21c804106e29c6) · *yoonmoonsik*

Version bump to 4.3.10.2. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix throwable pike

[`66fe7fb`](https://github.com/Yoonmoonsik/dnd55e/commit/66fe7fbfcc5fb8519647c82f4085ced0e8db03df) · *yoonmoonsik*

Fixed the **Pike** weapon not working correctly when thrown. 

Corrected the throwable weapon stat entry so the pike can be used as a thrown weapon as per the 2024 rules.

---

### 🔴 fix Rush_Charger_Push

[`5f41e71`](https://github.com/Yoonmoonsik/dnd55e/commit/5f41e71ca71181cee8d77c7af0cdf9ed51966e3b) · *yoonmoonsik*

Fixed the **Charger** feat's rush and push interaction. 

Corrected the spell trigger so the push effect after a charge correctly applies its forced movement to the target.

---

## April 22, 2026

### 🟢 4.3.10.1 Add Moon Sickle

[`53ce50f`](https://github.com/Yoonmoonsik/dnd55e/commit/53ce50fb401717568a6177be4905f0f0c67b1d23) · *yoonmoonsik*

Added the **Moon Sickle** as a magic weapon. 

This druid-focused item grants a bonus to spell attack rolls and spell save DCs, and adds 1d4 radiant damage to the weapon's attacks, as per the 2024 DMG.

---

### ⚪ 4.3.10

[`d7a7582`](https://github.com/Yoonmoonsik/dnd55e/commit/d7a75828fcf86eedf5b988ddded04b857dc8b3df) · *yoonmoonsik*

Version bump to 4.3.10. 

Updates internal build metadata in `meta.lsx`.

---

### 🟣 Spanish Support (Credit: HermexVar, mod.io)

[`1e2c5d6`](https://github.com/Yoonmoonsik/dnd55e/commit/1e2c5d69445cf5e6d0c42649e36fd5f25fac2891) · *yoonmoonsik*

Added official **Castilian Spanish localization** support to the mod, credited to **HermesVar** (mod.io). 

This marks the first full integration of the Spanish translation into the main repository.

---

### ⚪ Merge pull request #135 from Shiina18/main

[`dc041c6`](https://github.com/Yoonmoonsik/dnd55e/commit/dc041c6f56d7cced47c7c8d924ffc19596866a90) · *Yoonmoonsik*

Merged community contribution from `Shiina18`. 

Integrates English localization typo corrections submitted via pull request #135.

---

### 🔴 fix shillelagh

[`eb620a7`](https://github.com/Yoonmoonsik/dnd55e/commit/eb620a78fec2c3027d5dd61223c33bfdbf1cc59c) · *yoonmoonsik*

Fixed the **Shillelagh** cantrip not functioning correctly. 

Corrected the spell's stat logic so it properly uses the caster's Wisdom modifier for attack and damage rolls when wielding a club or quarterstaff.

---

### 🔴 fix: correct clear typos in english localization xml

[`a3e638e`](https://github.com/Yoonmoonsik/dnd55e/commit/a3e638ed6eeaf124fb9c346745d09eca9a1a7c51) · *shiina*

Corrected several typos in the English localization XML file. 

Improves the readability and accuracy of ability and spell descriptions shown to English-speaking players.

---

### ⚪ 4.3.9.2

[`e219ce8`](https://github.com/Yoonmoonsik/dnd55e/commit/e219ce86f1e5639421b5912af5ec7290361474a6) · *yoonmoonsik*

Version bump to 4.3.9.2. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix steadyaim

[`46a1bea`](https://github.com/Yoonmoonsik/dnd55e/commit/46a1bea532c10c0eac79bc2930f38f25cb36318c) · *yoonmoonsik*

Fixed the **Steady Aim** optional Rogue feature not working as intended. 

Corrected the passive or spell logic so it properly grants Advantage on the next attack roll in exchange for forfeiting movement on that turn.

---

## April 21, 2026

### 🔴 4.3.9.1 fix #128

[`f07bb00`](https://github.com/Yoonmoonsik/dnd55e/commit/f07bb00a3dee2f371d0950b587de7d52e8985f11) · *yoonmoonsik*

Fixed the bug reported in issue #128. 

Hotfix applied immediately after the 4.3.9 release to address a breaking interaction introduced in that update.

---

### 🔵 4.3.9 update Artillerist Artificer

[`c32a69e`](https://github.com/Yoonmoonsik/dnd55e/commit/c32a69e19074c8197f5725cf15edfbcf16db4d02) · *yoonmoonsik*

Updated the **Artillerist Artificer** subclass to align with the 2024 rules. 

Revisions include the Eldritch Cannon feature set (Force Ballista, Flamethrower, Protector modes), Arcane Firearm, and Explosive Cannon improvements.

---

### ⚪ 4.3.8.6

[`4b2f09f`](https://github.com/Yoonmoonsik/dnd55e/commit/4b2f09f9771efd7fac70ad3ceb59fd1e277ea624) · *yoonmoonsik*

Version bump to 4.3.8.6. 

Updates internal build metadata in `meta.lsx`.

---

### ⚪ 4.3.8.5

[`37a0f45`](https://github.com/Yoonmoonsik/dnd55e/commit/37a0f455398d7634f0b3ff91b1dd7707ddcce79e) · *yoonmoonsik*

Version bump to 4.3.8.5.

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix minor bugs

[`b18fa90`](https://github.com/Yoonmoonsik/dnd55e/commit/b18fa90d9d777ae9ecf279ad6f9f35102a0d44ab) · *yoonmoonsik*

Applied minor corrections across multiple stat or spell entries to address small bugs reported after the 4.3.8 update.

---

### ⚪ 4.3.8.4

[`fda1c41`](https://github.com/Yoonmoonsik/dnd55e/commit/fda1c41bb6328dd57218b94d4f97866a320993a0) · *yoonmoonsik*

Version bump to 4.3.8.4. 

Updates internal build metadata in `meta.lsx`.

---

## April 20, 2026

### 🔴 fix create void

[`969b7be`](https://github.com/Yoonmoonsik/dnd55e/commit/969b7be23727926047888faeb375e369de14e0c0) · *yoonmoonsik*

Fixed the **Create Void** ability not functioning correctly. 

Corrected the spell or passive trigger logic to ensure the effect applies as intended.

---

### ⚪ 4.3.8.3

[`6cea3e1`](https://github.com/Yoonmoonsik/dnd55e/commit/6cea3e1ee3868e28d38496b44b4856bba3cbf6e6) · *yoonmoonsik*

Version bump to 4.3.8.3. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix #122

[`78c50ae`](https://github.com/Yoonmoonsik/dnd55e/commit/78c50ae9e2c41d2061367f3da86e261aadffbe2c) · *yoonmoonsik*

Fixed the bug reported in issue #122. 

Corrected the affected spell or passive stat entry to restore correct behavior.

---

### 🔴 fix heavy armor penalty

[`ea261ca`](https://github.com/Yoonmoonsik/dnd55e/commit/ea261ca1f99fde000c50d6fc761f725603b5e4e0) · *yoonmoonsik*

Fixed the **Heavy Armor** Strength requirement penalty not applying correctly. 

Characters without the minimum Strength score now properly suffer the movement speed reduction when wearing heavy armor, as per the 2024 rules.

---

### 🔴 fix #121

[`a927c5d`](https://github.com/Yoonmoonsik/dnd55e/commit/a927c5dcc0b3023d736f1e27d0cd545ce40f6354) · *yoonmoonsik*

Fixed the bug reported in issue #121. 

Adjusted the relevant stat or condition logic to resolve the unintended behavior.

---

## April 19, 2026

### 🔴 4.3.8.2 fix Force Demolisher

[`6490b7b`](https://github.com/Yoonmoonsik/dnd55e/commit/6490b7b4059a55e2421ba8acd16123d9291c1e99) · *yoonmoonsik*

Fixed the **Force Demolisher** Artillerist Artificer feature not working correctly. 

Corrected the explosion spell logic or passive condition to ensure it properly deals force damage in an area when the Eldritch Cannon is destroyed.

---

### 🔴 4.3.8.1 fix Armorer

[`14adf66`](https://github.com/Yoonmoonsik/dnd55e/commit/14adf6606a2fae8430215aaa89b165fe40b05d44) · *yoonmoonsik*

Hotfix for the **Armorer Artificer** subclass introduced in 4.3.8. 

Corrected a broken interaction in the armor model integration or spell/passive stat entries.

---

### 🔵 4.3.8 update armorer artificer

[`f04fbe8`](https://github.com/Yoonmoonsik/dnd55e/commit/f04fbe80c3889faa7cc89716ccc7fd3d379ceafa) · *yoonmoonsik*

Updated the **Armorer Artificer** subclass with its full 2024 feature set, including Arcane Armor (Guardian and Infiltrator models), armor modifications, and the Extra Attack integration for the subclass's specialized attacks.

---

### ⚪ 4.3.7.1

[`208585b`](https://github.com/Yoonmoonsik/dnd55e/commit/208585bd50b92de80d430df5952b502983a257f4) · *yoonmoonsik*

Version bump to 4.3.7.1. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix #119

[`742adc4`](https://github.com/Yoonmoonsik/dnd55e/commit/742adc4fcd97dac311783b2b4b486f4af7baad37) · *yoonmoonsik*

Fixed the bug reported in issue #119. 

Corrected a faulty stat or spell condition causing an unintended interaction in the mod.

---

## April 18, 2026

### 🔵 update missing control UI icons

[`ec5ac1a`](https://github.com/Yoonmoonsik/dnd55e/commit/ec5ac1a965d9608a190a62c72b405ab6355de014) · *yoonmoonsik*

Added missing UI icons for control abilities in the action bar. 

Players will now see proper icons instead of blank or placeholder graphics for the affected abilities.

---

### ⚪ 4.3.7

[`a8feaa4`](https://github.com/Yoonmoonsik/dnd55e/commit/a8feaa48ab85854627914e0ad984738be7f80be7) · *yoonmoonsik*

Version bump to 4.3.7. 

Updates internal build metadata in `meta.lsx`.

---

### 🟢 add holy avenger

[`963fd67`](https://github.com/Yoonmoonsik/dnd55e/commit/963fd6784fc22c4b5ebd1f3d10425e3e3fcb9e89) · *yoonmoonsik*

Added the **Holy Avenger** as a legendary magic weapon. Implements its full feature set: +3 bonus to attack and damage rolls, extra radiant damage against fiends and undead, and an aura that grants advantage on saving throws against spells to nearby allies when wielded by a Paladin.

---

### 🔴 4.3.6.3 fix #115

[`75cf480`](https://github.com/Yoonmoonsik/dnd55e/commit/75cf480df14c2f776b7c18669cd9f8ed35336a91) · *yoonmoonsik*

Fixed the bug reported in issue #115. 

Patch applied in version 4.3.6.3 to address a breaking behavior introduced in the previous update.

---

## April 17, 2026

### ⚪ 4.3.6.2

[`f4d504c`](https://github.com/Yoonmoonsik/dnd55e/commit/f4d504c2c074fc62ac617b6579083d30b33a9bae) · *yoonmoonsik*

Version bump to 4.3.6.2. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix #99

[`78de44f`](https://github.com/Yoonmoonsik/dnd55e/commit/78de44f1a534056dab7a29bbf30af6f362125338) · *yoonmoonsik*

Fixed the long-standing bug reported in issue #99. 

Corrected the affected mechanic's stat or condition logic to restore intended behavior.

---

### 🔴 fix #113

[`86f2276`](https://github.com/Yoonmoonsik/dnd55e/commit/86f227689ec5fb1df9e32ac28612538beb5d93ec) · *yoonmoonsik*

Fixed the bug reported in issue #113. 

Adjusted the relevant spell or passive entry to resolve the unintended interaction.

---

### 🔴 fix #114

[`9cf7e89`](https://github.com/Yoonmoonsik/dnd55e/commit/9cf7e897b1e3d0280e9b7a6c83045478d11bc62e) · *yoonmoonsik*

Fixed the bug reported in issue #114. 

Corrected a faulty condition or stat flag causing incorrect behavior.

---

### 🔴 4.3.6.1 fix Shadow Gnawer

[`2cd8884`](https://github.com/Yoonmoonsik/dnd55e/commit/2cd8884970673fb21346c094eeac795ba9f965f7) · *yoonmoonsik*

Hotfix for the **Shadow Gnawer Barbarian** subclass. 

Corrected a broken feature introduced in the 4.3.6 update.

---

### 🔵 4.3.6 update Shadow Gnawer Barbarian

[`2d2dc80`](https://github.com/Yoonmoonsik/dnd55e/commit/2d2dc80ca464fd673626611aa619eb81cc9852fc) · *yoonmoonsik*

Updated the **Shadow Gnawer Barbarian** subclass with revised feature implementation. 

Adjusts its rage-linked shadow abilities and passive bonuses to align with the 2024 design intent.

---

### 🔴 fix WarriorOfTheGods

[`ebcdb25`](https://github.com/Yoonmoonsik/dnd55e/commit/ebcdb250a998cacc8e622f03aa7227b5a10cbe7b) · *yoonmoonsik*

Fixed the **Warrior of the Gods** feat (Cleric-adjacent) not functioning correctly. 

Corrected the passive logic so that the character is restored to 1 HP when reduced to 0 HP, consuming the feat's effect as intended.

---

### ⚪ 4.3.5.3

[`d0069b6`](https://github.com/Yoonmoonsik/dnd55e/commit/d0069b632e88801c1e9c01861ca64ca379cac36f) · *yoonmoonsik*

Version bump to 4.3.5.3. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix poisoner's kit

[`fcc2970`](https://github.com/Yoonmoonsik/dnd55e/commit/fcc2970903066db56d95b1365ecbbf15609766c4) · *yoonmoonsik*

Fixed the **Poisoner's Kit** tool not working as intended. 

Corrected the crafting or passive interaction so it properly allows players to apply poison to weapons during a Short Rest.

---

### 🔴 fix typo

[`ead6568`](https://github.com/Yoonmoonsik/dnd55e/commit/ead6568a5b4c3e8a9771efa166329a96f82e6774) · *yoonmoonsik*

Corrected a typo in a stat entry, localization string, or file reference that was causing a minor display or logic error.

---

### 🔴 4.3.5.2 fix poisoner's kit

[`be09a14`](https://github.com/Yoonmoonsik/dnd55e/commit/be09a14554900f70f302bdbacf4c6622f9a21241) · *yoonmoonsik*

Second fix for the **Poisoner's Kit** issue. 

Addressed a remaining problem with the tool's interaction logic after the first patch.

---

### ⚪ 4.3.5

[`588491f`](https://github.com/Yoonmoonsik/dnd55e/commit/588491fb908a9d9b8a7932e198af3cf29e59f88c) · *yoonmoonsik*

Version bump to 4.3.5. 

Updates internal build metadata in `meta.lsx`.

---

### 🔵 update Artificer, alchemist artificer

[`81fa966`](https://github.com/Yoonmoonsik/dnd55e/commit/81fa966c14303554ed0b16be6a0d950a87232bc8) · *yoonmoonsik*

Updated the **Artificer** base class and **Alchemist** subclass to match the 2024 rules. 

Revisions cover Magical Tinkering, the Infuse Item system, and Alchemist-specific features including Experimental Elixir and Alchemical Savant.

---

## April 16, 2026

### ⚪ 4.3.4.3

[`1c38cc2`](https://github.com/Yoonmoonsik/dnd55e/commit/1c38cc2c9a400eaa5e87a955a340c8c6f2757c3f) · *yoonmoonsik*

Version bump to 4.3.4.3. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix #106

[`e00c786`](https://github.com/Yoonmoonsik/dnd55e/commit/e00c786b4f7825da0d0c8ce70cbbfa80300c4696) · *yoonmoonsik*

Fixed the bug reported in issue #106. 

Corrected the relevant stat or condition entry to restore the expected mechanic behavior.

---

### 🔴 4.3.4.2 fix #80

[`a689a2a`](https://github.com/Yoonmoonsik/dnd55e/commit/a689a2aaced3e3d92f491a7c036779380a8d38fd) · *yoonmoonsik*

Fixed the long-standing bug reported in issue #80. 

Patch applied in version 4.3.4.2 to address an unresolved interaction in the affected mechanic.

---

### ⚪ 4.3.4.1

[`db13e22`](https://github.com/Yoonmoonsik/dnd55e/commit/db13e22a1821f5b2aa587e64cdf7571394b36711) · *yoonmoonsik*

Version bump to 4.3.4.1. 

Updates internal build metadata in `meta.lsx`.

---

### 🔵 update starting equipment #18

[`b4e61da`](https://github.com/Yoonmoonsik/dnd55e/commit/b4e61da239992cd11ed2130c312d45f9aaa9983e) · *yoonmoonsik*

Updated starting equipment for one or more classes to reflect the 2024 PHB equipment packages. 

Addresses issue #18, ensuring characters begin the game with the correct gear options.

---

### ⚪ place MAG_Mobility_SprintForMomentum_ChainShirt

[`9d4bafd`](https://github.com/Yoonmoonsik/dnd55e/commit/9d4bafd7506cfc853b597c4524b9abb2405a2ede) · *yoonmoonsik*

Placed the `MAG_Mobility_SprintForMomentum` modifier onto the Chain Shirt item. 

Ensures the armor correctly carries the sprint momentum passive as part of its item properties.

---

### ⚪ upgrade some weapons

[`299d3f9`](https://github.com/Yoonmoonsik/dnd55e/commit/299d3f97c07bb60b7f527add8e37233544668f8e) · *yoonmoonsik*

Upgraded stat entries for several weapons, adjusting their damage dice, properties, or magical bonuses to better align with the 2024 DMG weapon tables.

---

## April 15, 2026

### ⚪ 4.3.3

[`368c3c7`](https://github.com/Yoonmoonsik/dnd55e/commit/368c3c74cd4e7854c48c54bd93a1a7f0304928c5) · *yoonmoonsik*

Version bump to 4.3.3. 

Updates internal build metadata in `meta.lsx`.

---

### 🔵 update Circle of the Unbroken Druid

[`914200a`](https://github.com/Yoonmoonsik/dnd55e/commit/914200a6eb3b3d16bf5d8e79d0d236137a83bb8b) · *yoonmoonsik*

Updated the **Circle of the Unbroken** Druid subclass with revised feature logic. 

Adjusts the subclass's unique mechanics to better align with its intended design, including passive triggers and ability interactions.

---

### ⚪ 4.3.2

[`b6f47cf`](https://github.com/Yoonmoonsik/dnd55e/commit/b6f47cf5bc8b897e19382c8bc82c54c29aaf8a93) · *yoonmoonsik*

Version bump to 4.3.2. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix giant barbarian rage

[`f1922c3`](https://github.com/Yoonmoonsik/dnd55e/commit/f1922c3f4d5b944f15c7529550eff6f6457c21d9) · *yoonmoonsik*

Fixed the **Path of the Giant Barbarian** rage not functioning correctly. 

Corrected the rage status or passive trigger so Giant's Might and its associated size increase and damage bonus apply properly when entering rage.

---

### 🔵 update astral domain cleric

[`604a7d1`](https://github.com/Yoonmoonsik/dnd55e/commit/604a7d11704d7368e84b3164eb31e9937ae28be3) · *yoonmoonsik*

Updated the **Astral Domain Cleric** subclass with revised feature implementation. 

Adjusts its domain spells, channel divinity options, and astral-themed passives to better match the intended 2024 design.

---

### 🔴 4.3.1.1 minor spear weapon fix

[`17949fb`](https://github.com/Yoonmoonsik/dnd55e/commit/17949fb639168e15eeb2786eeb2abcbf59584e41) · *yoonmoonsik*

Fixed a minor issue with the **Spear** weapon stat entry. 

Corrected a property flag or damage definition that was causing a small unintended behavior.

---

### ⚪ 4.3.1

[`c07a883`](https://github.com/Yoonmoonsik/dnd55e/commit/c07a883ae02a4dec00f25ecaf7d8896474ba476f) · *yoonmoonsik*

Version bump to 4.3.1. 

Updates internal build metadata in `meta.lsx`.

---

### ⚪ place enforcer set

[`a2e7182`](https://github.com/Yoonmoonsik/dnd55e/commit/a2e7182538a06d05a84205f98f231d87f2902451) · *yoonmoonsik*

Placed the Enforcer armor set into the game world. 

Assigns the item to the appropriate container or vendor loot table so players can discover or purchase it.

---

### ⚪ sort weapon table

[`92f827d`](https://github.com/Yoonmoonsik/dnd55e/commit/92f827d136b8220329bcc9b21c58301a983f99f6) · *yoonmoonsik*

Reorganized the weapon data table for better readability and maintainability. 

No gameplay changes — purely a code structure cleanup.

---

### 🔴 fix tooltips

[`e86652b`](https://github.com/Yoonmoonsik/dnd55e/commit/e86652b1bd4b484e22336a17b81ebaffb49a74e2) · *yoonmoonsik*

Fixed several incorrect or missing tooltips on abilities, spells, or items. 

Players will now see accurate descriptions when hovering over the affected elements in the UI.

---

### ⚪ 4.3

[`415d77d`](https://github.com/Yoonmoonsik/dnd55e/commit/415d77d13d4559d8b39d99763b0ffe8ac7076143) · *yoonmoonsik*

Version bump to 4.3. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix magic initiate sword burst

[`d0bcb45`](https://github.com/Yoonmoonsik/dnd55e/commit/d0bcb45dc0e21be2b91f7312fd2c200f14faf455) · *yoonmoonsik*

Fixed the **Magic Initiate** feat granting **Sword Burst** incorrectly. 

Corrected the spell assignment logic so the cantrip behaves properly when obtained through the feat rather than a class level.

---

### 🟢 add the crooked moon backgrounds and feats

[`65c5045`](https://github.com/Yoonmoonsik/dnd55e/commit/65c5045a743a4dc54b39ac08c0948bb659517760) · *yoonmoonsik*

Added **The Crooked Moon** backgrounds and their associated feats. 

Implements the new background options with their starting proficiencies, equipment, and background feat bonuses as defined in the supplemental rules.

---

### 🔵 4.2.20 update illusionist wizard

[`4724f6a`](https://github.com/Yoonmoonsik/dnd55e/commit/4724f6ad171be783f27376120aef512cc589a23a) · *yoonmoonsik*

Updated the **School of Illusion Wizard** subclass to align with the 2024 rules. 

Revisions cover Improved Minor Illusion, Malleable Illusions, Illusory Self, and Illusory Reality feature implementations.

---

### 🔵 update summon beast spell

[`801eea5`](https://github.com/Yoonmoonsik/dnd55e/commit/801eea5d56064943c6e95154c56267334b581802) · *yoonmoonsik*

Updated **Summon Beast** to better reflect the 2024 spell rules. 

Adjusts the summoned creature's stat block scaling, available beast forms, and action economy to match the revised conjuration framework.

---

### ⚪ 4.2.19

[`95e243f`](https://github.com/Yoonmoonsik/dnd55e/commit/95e243f0b9737453c3a4bfab45a02d6339be0cda) · *yoonmoonsik*

Version bump to 4.2.19. 

Updates internal build metadata in `meta.lsx`.

---

### 🔵 update summon fey spell

[`85b4563`](https://github.com/Yoonmoonsik/dnd55e/commit/85b45630bb4d0ce25cc25534b2c21db01feaffc4) · *yoonmoonsik*

Updated **Summon Fey** to reflect the 2024 spell rules. 

Adjusts the fey spirit's stat block, available moods (Fuming, Mirthful, Tricksy), and scaling behavior at higher spell slots.

---

### 🔴 fix DexterityBasedUnarmedAttack_Passive

[`52cee67`](https://github.com/Yoonmoonsik/dnd55e/commit/52cee67d9d4f4f11ee00547a2fe78b8ccbac841c) · *yoonmoonsik*

Fixed the **Dexterity-based Unarmed Attack** passive not applying correctly. 

Corrected the passive condition so characters with the appropriate features use their Dexterity modifier for unarmed strike attack and damage rolls.

---

### 🔴 fix #98

[`ed795fc`](https://github.com/Yoonmoonsik/dnd55e/commit/ed795fcdb807dfb5ab6bc9d36386342471059356) · *yoonmoonsik*

Fixed the bug reported in issue #98. 

Adjusted the relevant stat or spell logic to resolve the unintended behavior.

---

## April 14, 2026

### 🔵 4.2.18 update Prestidigitation

[`8649dfc`](https://github.com/Yoonmoonsik/dnd55e/commit/8649dfccdd4ef13022e2a537bdd934a24fd21499) · *yoonmoonsik*

Updated the **Prestidigitation** cantrip to reflect the expanded 2024 rules. 

Adds or corrects available effect options including sensory effects, object cleaning, temperature changes, and flavor or scent creation.

---

### 🟢 add gnome cantrip

[`da36e47`](https://github.com/Yoonmoonsik/dnd55e/commit/da36e47e498803abee260ab9f8d224b057c404d9) · *yoonmoonsik*

Added the **Gnome** racial cantrip as defined in the 2024 PHB. 

Forest Gnomes gain Minor Illusion and Rock Gnomes gain a crafting-related cantrip, now properly granted at character creation.

---

### 🔵 update Shout_Prestidigitation

[`ed9eee7`](https://github.com/Yoonmoonsik/dnd55e/commit/ed9eee747345369dfa94c00bf1f8d36eb6482071) · *yoonmoonsik*

Updated the internal `Shout_Prestidigitation` spell entry to support the expanded effect list added in the Prestidigitation update. 

Ensures the UI correctly presents all available options when the cantrip is cast.

---

### 🔴 fix #93

[`f1f7a84`](https://github.com/Yoonmoonsik/dnd55e/commit/f1f7a848190fab81b70fbed971a0ec6f4417b277) · *yoonmoonsik*

First fix attempt for issue #93. 

Adjusted the relevant stat or condition logic to address the reported behavior.

---

### 🔴 fix #93

[`a868ae6`](https://github.com/Yoonmoonsik/dnd55e/commit/a868ae61d4f802f920ac71a03f138abca102e385) · *yoonmoonsik*

Follow-up fix for issue #93. 

Addressed a remaining edge case not covered by the previous patch.

---

### 🔴 fix #94

[`4b42f11`](https://github.com/Yoonmoonsik/dnd55e/commit/4b42f11b78173b90cd8a7bb435b8b71ba938e2de) · *yoonmoonsik*

Fixed the bug reported in issue #94. 

Corrected the affected mechanic's stat or condition entry to restore expected behavior.

---

### 🔵 update readme

[`f533036`](https://github.com/Yoonmoonsik/dnd55e/commit/f533036e4f8bbc9bcd2e4e575ab182595f6f871b) · *yoonmoonsik*

Updated the repository README with new information about mod features, supported content, or installation instructions.

---

### 🔴 fix #91

[`2c337c2`](https://github.com/Yoonmoonsik/dnd55e/commit/2c337c2f57a7b05f3d23016aadd398d5ec522d5a) · *yoonmoonsik*

Fixed the bug reported in issue #91. 

Corrected the relevant passive or spell condition causing the unintended interaction.

---

## April 13, 2026

### 🟢 4.2.17.1 add true name

[`cbe7039`](https://github.com/Yoonmoonsik/dnd55e/commit/cbe703902b25688e4e705eaf36313fe6c29c90e5) · *yoonmoonsik*

Added the **True Name** mechanic, allowing players to learn and exploit the true names of fiends for binding or compelling effects.

Implements the associated spell or passive feature as defined in the supplemental rules.

---

### ⚪ 4.2.17.0

[`64fe3b0`](https://github.com/Yoonmoonsik/dnd55e/commit/64fe3b0e39c1a513f101f90961ecd76fb6fbb442) · *yoonmoonsik*

Version bump to 4.2.17.0. 

Updates internal build metadata in `meta.lsx`.

---

### 🔵 update psychic spell VFX

[`9aad282`](https://github.com/Yoonmoonsik/dnd55e/commit/9aad282695fcfc7606ea3aa0093631f21c89fc21) · *yoonmoonsik*

Updated visual effects for psychic-school spells. 

Improves the VFX presentation of mind-affecting abilities to better distinguish them visually from other damage types.

---

### ⚪ prevent blade cantrip targeting terrain

[`881126d`](https://github.com/Yoonmoonsik/dnd55e/commit/881126d690657ce831f0171f4716a0271e142210) · *yoonmoonsik*

Added a restriction to prevent blade cantrips (such as Booming Blade and Green-Flame Blade) from targeting terrain or objects. 

Ensures these cantrips can only be cast on valid creature targets as per the rules.

---

### 🔴 fix Radiant Retort

[`e4ed474`](https://github.com/Yoonmoonsik/dnd55e/commit/e4ed4742b55fc617a97a429f44a9d687c7e89fe5) · *yoonmoonsik*

Fixed the **Radiant Retort** feature (Twilight Cleric or related subclass) not triggering correctly. 

Corrected the reaction interrupt logic so it properly deals radiant damage back to attackers when the condition is met.

---

### 🔴 fix #89

[`ac7a4cc`](https://github.com/Yoonmoonsik/dnd55e/commit/ac7a4ccd3e6bf7832ea831c66bfddf52e9b2c16b) · *yoonmoonsik*

Fixed the bug reported in issue #89. 

Adjusted the relevant spell or passive condition to resolve the reported unintended behavior.

---

### 🔴 fix illrigger has no weapon mastery #88

[`8d75398`](https://github.com/Yoonmoonsik/dnd55e/commit/8d75398820c5185b8c9a332907209403c9cf099e) · *yoonmoonsik*

Fixed the **Illrigger** class not granting **Weapon Mastery** choices at level 1. 

Corrected the class progression entry so Illrigger characters can properly select and use Weapon Mastery properties from the start.

---

### ⚪ 4.2.16.1

[`57c6e9f`](https://github.com/Yoonmoonsik/dnd55e/commit/57c6e9f76f8c57c4f09f4ecfb5592be72a1356e9) · *yoonmoonsik*

Version bump to 4.2.16.1. 

Updates internal build metadata in `meta.lsx`.

---

### 🔵 update Gloves of Heroism

[`301dbd4`](https://github.com/Yoonmoonsik/dnd55e/commit/301dbd461b1856ead2972130ac40287b70140b4c) · *yoonmoonsik*

Updated the **Gloves of Heroism** magic item. 

Adjusts their passive bonus or granted ability to better reflect the item's intended effect and ensure it stacks correctly with other buffs.

---

### ⚪ change Phalar Aluve icon

[`fe96140`](https://github.com/Yoonmoonsik/dnd55e/commit/fe96140b494dc8a6392bfeb1f3ec38993c7301b9) · *yoonmoonsik*

Changed the icon for **Phalar Aluve** to a more appropriate visual. 

Purely a cosmetic update with no gameplay impact.

---

### ⚪ 4.2.15.0

[`418199a`](https://github.com/Yoonmoonsik/dnd55e/commit/418199af81153db8096580bb926191a62d54cfbf) · *yoonmoonsik*

Version bump to 4.2.15.0. 

Updates internal build metadata in `meta.lsx`.

---

### 🟢 grant +1 ASI to Origin Feats when selected at level 4 or higher

[`55d9b05`](https://github.com/Yoonmoonsik/dnd55e/commit/55d9b0522b501592db8d5eebb882bfee04558a0f) · *yoonmoonsik*

Implemented the 2024 rule that **Origin Feats** grant a +1 Ability Score Increase when taken at level 4 or higher as a regular feat selection, matching the PHB design intent for feat progression.

---

### 🟢 add ASI to TCE Feats

[`ec70845`](https://github.com/Yoonmoonsik/dnd55e/commit/ec70845756cec89cc62ffb33ae5314649230d3eb) · *yoonmoonsik*

Added Ability Score Increases to **Tasha's Cauldron of Everything** feats where applicable. 

Brings TCE feats in line with the 2024 PHB feat design philosophy of bundling an ASI with most feats.

---

### 🔵 4.2.14 Update Architect of Ruin Illrigger

[`ef5b6e9`](https://github.com/Yoonmoonsik/dnd55e/commit/ef5b6e94f2878292d379ff2a6489cb6844909ffc) · *yoonmoonsik*

Updated the **Architect of Ruin** Illrigger subclass with revised feature implementation. 

Adjusts its cursing mechanics, infernal architecture abilities, and passive bonuses to better reflect the subclass's design intent.

---

### 🟢 add Vengeful Blade Cantrip, Hellfire Spell

[`69f3463`](https://github.com/Yoonmoonsik/dnd55e/commit/69f346322a5d272a06fe2f73c9f698fe044031df) · *yoonmoonsik*

Added the **Vengeful Blade** cantrip and **Hellfire** spell to the mod. 

These Illrigger-specific abilities expand the class's offensive options with infernal melee and fire-based magic.

---

### 🟢 add hellfire cantrip

[`864b25f`](https://github.com/Yoonmoonsik/dnd55e/commit/864b25fded63e5e554cd749b1fb1543675e04a23) · *yoonmoonsik*

Added the **Hellfire** cantrip as a standalone entry. 

Implements the spell's stat block, targeting logic, and fire damage scaling for use by Illrigger and other eligible classes.

---

### 🟢 add spell icons

[`5aad2cf`](https://github.com/Yoonmoonsik/dnd55e/commit/5aad2cfa5ca0abdacac67ea4314701bdccb6547c) · *yoonmoonsik*

Added custom icons for newly implemented spells and cantrips. 

Ensures all new abilities display a proper icon in the action bar and spell selection UI.

---

### 🔴 fix MAG_StrengthBonusToWeaponDamage_Passive

[`d3a8971`](https://github.com/Yoonmoonsik/dnd55e/commit/d3a89718242af159345723325c1ea8777835a29f) · *yoonmoonsik*

Fixed the **Strength Bonus to Weapon Damage** passive not applying correctly. 

Corrected the passive boost condition so Strength modifier is properly added to weapon damage rolls for the affected mechanics.

---

### 🔵 update Shadowmaster Illrigger

[`cd3c24e`](https://github.com/Yoonmoonsik/dnd55e/commit/cd3c24e83df6280b6f3591dc90086c1e056c4177) · *yoonmoonsik*

Updated the **Shadowmaster** Illrigger subclass with revised feature logic. 

Adjusts its shadow-based abilities, darkness manipulation mechanics, and passive bonuses to better align with the subclass's design.

---

### 🔴 fix Gunslinger fighting style doesn't work #86

[`1c96183`](https://github.com/Yoonmoonsik/dnd55e/commit/1c96183080f0ec5aeb345c439d91f3aa3f6e9a1c) · *yoonmoonsik*

Fixed the **Gunslinger** fighting style not applying its bonus correctly. 

Corrected the passive condition so the style's benefit triggers properly when using firearms in combat.

---

## April 12, 2026

### 🔴 4.2.11.4 fix: Wyll - Missing spells & Invocations #83

[`afa6b75`](https://github.com/Yoonmoonsik/dnd55e/commit/afa6b75ef37e658392bd1f88c47f233f1bd6ec83) · *yoonmoonsik*

Fixed companion **Wyll** missing several Warlock spells and Eldritch Invocations after the mod's class overhaul. 

Restores his full spell and invocation list so he functions correctly as a pre-built Warlock companion.

---

### 🔴 fix: Fighter Cavalier Subclass - Warding Maneuver #84

[`e4126eb`](https://github.com/Yoonmoonsik/dnd55e/commit/e4126eb6ace39d949ed10ca343236af0e29871e3) · *yoonmoonsik*

Fixed the **Cavalier Fighter** subclass's **Warding Maneuver** reaction not functioning correctly. 

Corrected the interrupt trigger so it properly adds 1d8 to the target's AC and grants temporary hit points when an adjacent ally is attacked.

---

### ⚪ increase +2 ranged weapon price

[`2411ef0`](https://github.com/Yoonmoonsik/dnd55e/commit/2411ef0686cd0cfc74e2415235481d208078c172) · *yoonmoonsik*

Increased the vendor price of +2 ranged weapons to better reflect their power level. 

A balance adjustment to prevent players from acquiring high-tier ranged enchantments too cheaply early in the game.

---

### 🔴 fix Interrupt_FightingStyle_Interception

[`dcf5156`](https://github.com/Yoonmoonsik/dnd55e/commit/dcf5156617ec0546cc2e132a07ab7ff9756ee28b) · *yoonmoonsik*

Fixed the **Interception** fighting style interrupt not triggering reliably. 

Corrected the reaction condition so it properly activates when a nearby ally is hit by an attack, reducing damage by 1d10 + proficiency bonus.

---

### 🔴 4.2.11.2 fix Baleful Interdict

[`597f306`](https://github.com/Yoonmoonsik/dnd55e/commit/597f306d5274b77d89da1b0a7ff2643f44e31e2b) · *yoonmoonsik*

Fixed the **Baleful Interdict** Illrigger feature not functioning correctly. 

Corrected the curse trigger or passive logic so it properly applies its penalty when the target takes the restricted action.

---

### 🔴 4.2.11.1 fix STYXS_APATHY

[`4a55213`](https://github.com/Yoonmoonsik/dnd55e/commit/4a55213684e4dc5628de988463e4c8040c5fb669) · *yoonmoonsik*

Fixed the **Styx's Apathy** status effect not applying or resolving correctly. 

Corrected the status condition flags so it properly inflicts its incapacitation-like effect on affected targets.

---

### 🔵 4.2.11 update painkiller Illrigger

[`d239231`](https://github.com/Yoonmoonsik/dnd55e/commit/d239231c6ea77a291bfa42ecddb2879db01eae35) · *yoonmoonsik*

Updated the **Painkiller** Illrigger subclass with its revised feature set. 

Adjusts its pain-inflicting mechanics, sadistic passive bonuses, and subclass-specific spell interactions.

---

## April 11, 2026

### 🔵 4.2.10.1 update Hellspeak Illrigger

[`4d8e170`](https://github.com/Yoonmoonsik/dnd55e/commit/4d8e170c13e8fa8675a9fe000a8b7be7165e76fe) · *yoonmoonsik*

Updated the **Hellspeak** Illrigger subclass with revised feature implementation. 

Adjusts its infernal language-based abilities and passive effects to better reflect the subclass's design intent.

---

## April 10, 2026

### 🔴 4.2.9.1 fix sanguin knight

[`74eae09`](https://github.com/Yoonmoonsik/dnd55e/commit/74eae0916a39c6bd36c3eb4bdbd1a5a0df79e05e) · *yoonmoonsik*

Hotfix for the **Sanguine Knight** Illrigger subclass introduced in 4.2.9. 

Corrected a broken interaction in its blood-based features or passive stat entries.

---

### 🟢 4.2.9 Update Illrigger and Sanguine Knight Subclass

[`91cb907`](https://github.com/Yoonmoonsik/dnd55e/commit/91cb907d948a33437b06aa3ddc7920bec023064b) · *yoonmoonsik*

Updated the **Illrigger** base class and added the **Sanguine Knight** as a new subclass. 

Implements its full blood-magic feature set including life-draining attacks, hemomancy passives, and subclass-specific spell list.

---

### 🔵 4.2.8 update white hat gunslinger

[`795eb4a`](https://github.com/Yoonmoonsik/dnd55e/commit/795eb4aa8cf000d79a82e74178551644dfbc1955) · *yoonmoonsik*

Updated the **White Hat Gunslinger** subclass with revised feature logic. 

Adjusts its sheriff-themed abilities and defensive firearm mechanics to better reflect the subclass design.

---

## April 9, 2026

### ⚪ 4.2.7.3 Rogue default weapon mastery #75

[`b7877b7`](https://github.com/Yoonmoonsik/dnd55e/commit/b7877b7035688e7b2485bf223eb7f43dc2c78ab8) · *yoonmoonsik*

Set default **Weapon Mastery** selections for the **Rogue** class to prevent the level 1 choice from appearing blank. 

Addresses issue #75 where companions and new Rogues had no default mastery assigned.

---

### ⚪ 4.2.7.2

[`769aaec`](https://github.com/Yoonmoonsik/dnd55e/commit/769aaecddf9e198d05ccb22efd567553e379cf48) · *yoonmoonsik*

Version bump to 4.2.7.2. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix Archfey Patron Steps of the Fey #74

[`0200acb`](https://github.com/Yoonmoonsik/dnd55e/commit/0200acb721696819c4571f665a9c997fbd981ead) · *yoonmoonsik*

Fixed the **Archfey Patron** Warlock's **Steps of the Fey** feature not working correctly. 

Corrected the teleportation spell or reaction trigger so it properly allows the Warlock to teleport up to 30 feet as a bonus action after casting a leveled spell.

---

### 🔴 fix Phantasmal force damage #76

[`0b1a204`](https://github.com/Yoonmoonsik/dnd55e/commit/0b1a2045bcc2e06ef1955f2373264150bd59d0cb) · *yoonmoonsik*

Fixed **Phantasmal Force** not dealing its psychic damage correctly. 

Corrected the spell's ongoing damage trigger so it properly inflicts 1d6 psychic damage at the start of the target's turn while they believe the illusion is real.

---

### 🔴 fix Level 1 choices for Weapon Mastery and Divine Order are missing from companions #75

[`aeb280d`](https://github.com/Yoonmoonsik/dnd55e/commit/aeb280d755183eda21db62ee7282f0153cfe2c79) · *yoonmoonsik*

Fixed companion characters not receiving their level 1 **Weapon Mastery** and **Divine Order** choices. 

Corrected the companion progression entries so these selections are properly available during character creation and level-up.

---

### 🔴 4.2.7.1 fix MAG_Gish_ArcaneAcuity_Gloves_Passive

[`7383396`](https://github.com/Yoonmoonsik/dnd55e/commit/7383396e81b9957412b787ae11754b78071216f8) · *yoonmoonsik*

Fixed the **Gish Arcane Acuity Gloves** passive not applying correctly. 

Corrected the passive boost so the gloves properly grant their Arcane Acuity stacks when the wearer deals damage with a weapon attack after casting a spell.

---

### 🔴 fix weaponbond

[`3fd7887`](https://github.com/Yoonmoonsik/dnd55e/commit/3fd788788fc98189e63c1b2de634d20f40fc3a57) · *yoonmoonsik*

Fixed the **Weapon Bond** Eldritch Knight feature not functioning correctly. 

Corrected the bonded weapon passive so it can be summoned to hand as a bonus action and cannot be disarmed.

---

### 🔴 fix Burrow_GiantBadger

[`8beff8d`](https://github.com/Yoonmoonsik/dnd55e/commit/8beff8d26a6a64ee8c9d0d22f8fcf745a49089c6) · *yoonmoonsik*

Fixed the **Giant Badger** Wild Shape form's Burrow ability not working as intended. 

Corrected the movement type or spell logic so the badger can properly burrow through the ground during combat.

---

### 🔴 fix greenflameblade

[`54bd232`](https://github.com/Yoonmoonsik/dnd55e/commit/54bd232429f3a540e2fa8f20777d05ba53d6b429) · *yoonmoonsik*

Fixed **Green-Flame Blade** not functioning correctly. 

Corrected the cantrip's secondary fire damage logic so it properly leaps to an adjacent target using the caster's spellcasting modifier at the appropriate levels.

---

### 🔴 fix combatinspiration

[`7adbb1f`](https://github.com/Yoonmoonsik/dnd55e/commit/7adbb1f80ef043e634b93e590025efef314f4acc) · *yoonmoonsik*

Fixed **Combat Inspiration** (Bard: College of Valor/Swords) not triggering correctly. 

Corrected the reaction interrupt so the Bardic Inspiration die can be properly added to AC or damage rolls when the recipient is attacked or makes an attack.

---

### 🔵 4.2.7 update spellslinger gunslinger

[`bae3570`](https://github.com/Yoonmoonsik/dnd55e/commit/bae3570348d985d5de1172cb055deed8430e8f80) · *yoonmoonsik*

Updated the **Spellslinger Gunslinger** subclass with revised feature implementation. 

Adjusts its spell-and-firearm hybrid mechanics and passive bonuses to better reflect the subclass's arcane gunfighter design.

---

### ⚪ 4.2.6.1

[`9b6193e`](https://github.com/Yoonmoonsik/dnd55e/commit/9b6193ef8754e2337fc9d97e8201b54f26ddb349) · *yoonmoonsik*

Version bump to 4.2.6.1. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix druid wild shape tooltip

[`864270d`](https://github.com/Yoonmoonsik/dnd55e/commit/864270d6de92401cd7e5e78db7804f80174e764d) · *yoonmoonsik*

Fixed incorrect or missing tooltip text on the **Druid Wild Shape** ability. 

Players will now see an accurate description of the feature's rules and available forms when hovering over the ability.

---

### 🔴 fix warding bond

[`1db1e80`](https://github.com/Yoonmoonsik/dnd55e/commit/1db1e80c5aa3e79cbef3288a0a26b5457a130234) · *yoonmoonsik*

Fixed **Warding Bond** not applying its effects correctly. 

Corrected the spell's passive boost so the bonded target properly gains +1 AC, +1 to saving throws, and resistance to all damage, while the caster shares the damage taken.

---

### 🔵 update PsiPoweredLeap

[`922a627`](https://github.com/Yoonmoonsik/dnd55e/commit/922a62727f41db2266d6d7c763ce1f1ce1fa1d5b) · *yoonmoonsik*
Updated the **Psi-Powered Leap** Psi Warrior Fighter feature. 

Adjusts the jump spell logic so it correctly grants the ability to cast Jump as a bonus action using psionic energy dice.

---

### 🔵 improve protective field interrupt visual

[`ef6f1cf`](https://github.com/Yoonmoonsik/dnd55e/commit/ef6f1cfbb5abfdbf29438ca67c3dc66b404aefb1) · *yoonmoonsik*

Improved the visual feedback for the **Protective Field** Psi Warrior interrupt. 

The reaction now displays a clearer VFX when the psionic shield activates to reduce incoming damage.

---

### 🔴 fix dragonshape cost

[`bf2b7e5`](https://github.com/Yoonmoonsik/dnd55e/commit/bf2b7e537de6ffce26844421d2e8ab4dea8d9714) · *yoonmoonsik*

Fixed the **Dragon Shape** Wild Shape form having an incorrect action cost. 

Corrected the spell entry so transforming into a dragon requires the appropriate action expenditure as per the Circle of the Moon rules.

---

### 🔴 fix musket mastery property

[`f1576cd`](https://github.com/Yoonmoonsik/dnd55e/commit/f1576cd9e873adaef041deb8e88589bd2d2aaab2) · *yoonmoonsik*

Fixed the **Musket** not correctly applying its Weapon Mastery property. 

Corrected the weapon stat entry so the Slow mastery property triggers properly when attacking with the musket.

---

### 🔴 fix: Club of Hill Giant Strength #72

[`ab435e1`](https://github.com/Yoonmoonsik/dnd55e/commit/ab435e10d21f6e186449a42c89891ea40ad63541) · *yoonmoonsik*

Fixed the **Club of Hill Giant Strength** not setting the wielder's Strength score to 21 as intended. 

Corrected the item passive so the strength override applies correctly when the club is equipped.

---

### 🔴 fix act of the Blade is not giving a choice for the damage type #71

[`a07be7d`](https://github.com/Yoonmoonsik/dnd55e/commit/a07be7d4058f841d0bd4d5d00d67e3c18b726354) · *yoonmoonsik*

Fixed the **Act of the Blade** Illrigger feature not presenting a damage type selection. 

orrected the spell or passive logic so players can choose their infernal damage type when the ability is activated.

---

### ⚪ Aberrant Mind missing spell. #63

[`89c5b02`](https://github.com/Yoonmoonsik/dnd55e/commit/89c5b022163b8f80446faa9cb08089b2fb466f1f) · *yoonmoonsik*

Added the missing expanded spell list entry for the **Aberrant Mind Sorcerer** subclass. 

Ensures all psychic and telepathy-themed spells from the subclass's spell list are properly granted at the appropriate levels.

---

### 🔴 fix Agonizing Blast (Thorn Whip) #70

[`c4a4a5a`](https://github.com/Yoonmoonsik/dnd55e/commit/c4a4a5aa48ff037050fe43198c52c478d6f432c7) · *yoonmoonsik*

Fixed the **Agonizing Blast** Eldritch Invocation incorrectly applying to **Thorn Whip**. 

Corrected the invocation's condition so the Charisma modifier bonus only applies to Eldritch Blast, not other cantrips.

---

## April 8, 2026

### 🔵 4.2.6 update Cavalier, Rune Knight

[`2b2d519`](https://github.com/Yoonmoonsik/dnd55e/commit/2b2d5199934410e971820dc52999151f3a6786ad) · *yoonmoonsik*

Updated the **Cavalier** and **Rune Knight** Fighter subclasses to align with the 2024 rules. 

Cavalier revisions cover Unwavering Mark and Ferocious Charger; Rune Knight updates address Giant's Might and the rune feature set scaling.

---

### 🔵 4.2.4. update highway rider rogue

[`cda04e6`](https://github.com/Yoonmoonsik/dnd55e/commit/cda04e6543dbee4ff4ffc21ee6973df8816e1711) · *yoonmoonsik*

Updated the **Highway Rider Rogue** subclass with revised feature implementation. 

Adjusts its mounted combat abilities and outlaw-themed passives to better reflect the subclass's design intent.

---

### 🔵 4.2.3 update circle of dragons druid

[`448f8a6`](https://github.com/Yoonmoonsik/dnd55e/commit/448f8a6eec5a377fc36d52c3b77e10edcd81a02e) · *yoonmoonsik*

Updated the **Circle of Dragons Druid** subclass with revised feature logic. 

Adjusts its draconic Wild Shape forms, breath weapon integration, and elemental passives to better match the subclass's design.

---

### 🔴 fix Typo #69

[`0be848a`](https://github.com/Yoonmoonsik/dnd55e/commit/0be848a7b9773302bf9ba78496296109443e6975) · *yoonmoonsik*

Corrected a typo in a localization string or stat entry name. 

A minor text fix with no gameplay impact.

---

### ⚪ 4.2.2

[`f3d189e`](https://github.com/Yoonmoonsik/dnd55e/commit/f3d189e1213dabf5322390947e23c10d959c0654) · *yoonmoonsik*

Version bump to 4.2.2. 

Updates internal build metadata in `meta.lsx`.

---

### 🔵 update firearms

[`b280991`](https://github.com/Yoonmoonsik/dnd55e/commit/b28099138c46fa8c7afdd46cbc63c38897894e9d) · *yoonmoonsik*

Updated firearm weapon stat entries across the board. 

Adjusts damage dice, range values, reload properties, and Weapon Mastery assignments to better align with the 2024 DMG firearm rules.

---

### 🔵 update gunslinger and highroller

[`959e22a`](https://github.com/Yoonmoonsik/dnd55e/commit/959e22ac43b0c1fad65b8111284950f747dc3516) · *yoonmoonsik*

Updated the **Gunslinger** base class and **High Roller** subclass with revised feature logic. 

Adjusts trick shot mechanics, grit point interactions, and subclass-specific firearm abilities.

---

### 🔵 4.2.1.0 update goliath

[`09e0ba3`](https://github.com/Yoonmoonsik/dnd55e/commit/09e0ba3ba04f24d5593b9caa3a76a8f06c362d3d) · *yoonmoonsik*

Updated the **Goliath** race to align with the 2024 PHB. 

Revisions cover Giant Ancestry trait options, Large Form at level 5, and carry weight bonus, ensuring full compliance with the revised racial rules.

---

## April 7, 2026

### 🔴 4.2.0.2 fix True Strike #60

[`9d7f5ea`](https://github.com/Yoonmoonsik/dnd55e/commit/9d7f5ea59fc24ff328e134f1538456e23fdded27) · *yoonmoonsik*

Fixed **True Strike** not functioning correctly after its 2024 redesign. 

Corrected the cantrip so it properly functions as a melee spell attack that deals the weapon's damage die plus the spellcasting modifier, replacing the old advantage mechanic.

---

### 🔴 4.2.0.1 fix Rogue missing weapon proficiencies #61

[`e20b181`](https://github.com/Yoonmoonsik/dnd55e/commit/e20b1819d2fe2573c11016a4174ab4c4cc2b91fe) · *yoonmoonsik*

Fixed **Rogue** characters missing several weapon proficiencies. 

Corrected the class proficiency list so Rogues properly gain proficiency with all the weapons specified in the 2024 PHB.

---

### 🔵 4.2 update spellfire sorcery

[`b4b9549`](https://github.com/Yoonmoonsik/dnd55e/commit/b4b954919920bad35fe372a8b357de439b1af1a4) · *yoonmoonsik*

Updated the **Spellfire Sorcerer** subclass with revised feature implementation. 

Adjusts its spellfire absorption mechanic, energy conversion passives, and fire-based ability interactions.

---

### ⚪ 4.1.4.

[`664f5e6`](https://github.com/Yoonmoonsik/dnd55e/commit/664f5e6bdc958884cc2e1c612d7acd7cee82defa) · *yoonmoonsik*

Version bump to 4.1.4. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix Preserve Life Bug #59

[`39dcd7b`](https://github.com/Yoonmoonsik/dnd55e/commit/39dcd7bdd4fb01d05b01753eb48344631a0bfe32) · *yoonmoonsik*

Fixed the **Life Cleric** Channel Divinity: **Preserve Life** not distributing healing correctly. 

Corrected the spell logic so it properly distributes hit points among chosen targets, up to half each creature's maximum HP.

---

### 🔵 update scion of the three

[`da59150`](https://github.com/Yoonmoonsik/dnd55e/commit/da59150f8502604519e43e15a9b9f30e32664d0a) · *yoonmoonsik*

Updated the **Scion of the Three** subclass with revised feature logic. 

Adjusts its tri-elemental ability set and passive interactions to better reflect the subclass's design intent.

---

### 🔵 4.1.3.2 update bladesinger #57

[`bd935b6`](https://github.com/Yoonmoonsik/dnd55e/commit/bd935b6d69c6a4cf22e7234f577af3c138711a1a) · *yoonmoonsik*

Updated the **Bladesinger Wizard** subclass to align with the 2024 rules. 

Adjusts Bladesong's AC and concentration bonuses, Song of Defense damage reduction, and Extra Attack integration with the spellcasting action.

---

### 🔴 fix Oath of the Noble Genies's typo #58

[`caa4b70`](https://github.com/Yoonmoonsik/dnd55e/commit/caa4b70eb427c0589ff9cfea72c14eb27b641a5d) · *yoonmoonsik*

Corrected a typo in the **Oath of the Noble Genie** Paladin subclass text. 

A localization fix with no gameplay impact.

---

### 🔴 4.1.3.1 fix truestrike

[`fdf7fbe`](https://github.com/Yoonmoonsik/dnd55e/commit/fdf7fbe464fbbe7c02f8e524f9c0344285d08229) · *yoonmoonsik*

Additional hotfix for **True Strike** following the 4.1.3 update. 

Addressed a remaining edge case in the cantrip's melee spell attack logic.

---

### ⚪ 4.1.3.0

[`71df088`](https://github.com/Yoonmoonsik/dnd55e/commit/71df0885b5225721de59242ae392f818b23bb41c) · *yoonmoonsik*

Version bump to 4.1.3.0. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix Perform Stopping

[`10a6ea9`](https://github.com/Yoonmoonsik/dnd55e/commit/10a6ea9176801f03872ac132ca4cb543cab048d9) · *yoonmoonsik*

Fixed the **Perform** action stopping unexpectedly mid-animation or mid-cast. 

Corrected the interrupt or status condition causing the ability to cancel prematurely.

---

### 🔵 update noble genie paladin

[`0608a79`](https://github.com/Yoonmoonsik/dnd55e/commit/0608a79fbd348176f556ff6507be3a32cc75a1a9) · *yoonmoonsik*

Updated the **Oath of the Noble Genie Paladin** subclass with revised feature implementation. 

Adjusts its wish-granting mechanics, genie vessel interaction, and elemental-themed Sacred Weapon and Channel Divinity options.

---

### ⚪ 4.1.2.2

[`e870939`](https://github.com/Yoonmoonsik/dnd55e/commit/e870939928c46772c115be1321f0738f7f7b262a) · *yoonmoonsik*

Version bump to 4.1.2.2. Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix Warding flare not working on light cleric subclass #53

[`5d588ca`](https://github.com/Yoonmoonsik/dnd55e/commit/5d588ca34eb5515300558730c83518ee28bd3cbb) · *yoonmoonsik*

Fixed the **Light Cleric** subclass's **Warding Flare** reaction not activating correctly. 

Corrected the interrupt trigger so it properly imposes disadvantage on an attacker's roll when the cleric uses their reaction in response to being attacked.

---

## April 6, 2026

### 🔵 4.1.2.1 update Winter Walker

[`a53d501`](https://github.com/Yoonmoonsik/dnd55e/commit/a53d5011cfac1846cc665db333551331e596efad) · *yoonmoonsik*

Updated the **Winter Walker** subclass with revised feature logic. 

Adjusts its cold-themed abilities, movement passives, and frost-based combat interactions to better reflect the subclass's design.

---

### 🔵 4.1.1.0 update banneret

[`f024263`](https://github.com/Yoonmoonsik/dnd55e/commit/f0242638c573919f73952572d8184eab0892440c) · *yoonmoonsik*

Updated the **Banneret (Purple Dragon Knight)** Fighter subclass to align with the 2024 rules. 

Adjusts Rallying Cry, Royal Envoy, Inspiring Surge, and Bulwark feature implementations.

---

### ⚪ 4.1.0.1

[`4bc2c9f`](https://github.com/Yoonmoonsik/dnd55e/commit/4bc2c9fc43011860ea37f7c5ecfd4009fcd9f62c) · *yoonmoonsik*

Version bump to 4.1.0.1. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix hunters mark tooltip

[`1bf625e`](https://github.com/Yoonmoonsik/dnd55e/commit/1bf625e70f93cbd5209e95002038734f5f1270a0) · *yoonmoonsik*

Fixed the **Hunter's Mark** tooltip displaying incorrect or outdated information. 

Updated the localization entry to accurately reflect the 2024 spell rules, including its bonus action transfer mechanic.

---

### 🔴 fix dance bard

[`1841d27`](https://github.com/Yoonmoonsik/dnd55e/commit/1841d2759327827b3eb68e38bccf2abb235d73c6) · *yoonmoonsik*

Fixed the **College of Dance Bard** subclass not functioning correctly. 

Corrected its Dazzling Footwork, Inspiring Movement, and Irresistible Dance feature interactions to behave as intended.

---

### 🔵 update moon college bard

[`e0abbd1`](https://github.com/Yoonmoonsik/dnd55e/commit/e0abbd175dea1756e35f513b1abdfd8f6985fa16) · *yoonmoonsik*

Updated the **College of the Moon Bard** subclass with revised feature logic. 

Adjusts its lunar cycle mechanics, moonlight-themed abilities, and passive interactions.

---

### 🔴 fix mind sliver

[`896b77c`](https://github.com/Yoonmoonsik/dnd55e/commit/896b77c8eb5d90c877b449c579a65eb833aee1c9) · *yoonmoonsik*

Fixed **Mind Sliver** not applying its saving throw penalty correctly. 

Corrected the cantrip's secondary effect so the target must subtract 1d4 from its next saving throw before the end of your next turn.

---

### 🟢 add FRHOF class icons

[`0b7165a`](https://github.com/Yoonmoonsik/dnd55e/commit/0b7165a3b5016691ba8e92f42149081542ddb4ef) · *yoonmoonsik*

Added class icons for the **FRHOF** (homebrew) classes. 

Ensures these classes display proper custom icons in the character creation screen and action bar.

---

### 🟢 update readme feat

[`5e7648c`](https://github.com/Yoonmoonsik/dnd55e/commit/5e7648c53c3048257fea0cf1a29ae32894c7278b) · *yoonmoonsik*

Updated the README to document newly added and revised feats, giving players a clear reference for what feat content is currently supported by the mod.

---

### 🔵 4.0.10 update aasimar

[`35ac2cd`](https://github.com/Yoonmoonsik/dnd55e/commit/35ac2cd0049805da08230e919aae4fc08a9652cc) · *yoonmoonsik*

Updated the **Aasimar** race to align with the 2024 PHB. 

Revisions cover Celestial Revelation transformations (Heavenly Wings, Inner Radiance, Necrotic Shroud), healing hands, and radiant soul passive adjustments.

---

### ⚪ 4.0.9.2

[`ceca9c9`](https://github.com/Yoonmoonsik/dnd55e/commit/ceca9c9b0f097b5845d8499c051138d68d5005ee) · *yoonmoonsik*

Version bump to 4.0.9.2. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix Devouring Blade only gives 2 attacks instead of 3 #43

[`491bbc5`](https://github.com/Yoonmoonsik/dnd55e/commit/491bbc5a261edad327bc58b1206deea6b89d3e92) · *yoonmoonsik*

Fixed **Devouring Blade** granting only 2 attacks instead of the correct 3. 

Corrected the Extra Attack implementation so the feature properly unlocks a third attack when the condition is met.

---

### 🔴 fix Subclass for rogue name change #50

[`61d4871`](https://github.com/Yoonmoonsik/dnd55e/commit/61d4871bdd89b22e6e9bf0c736fe4026963f69d9) · *yoonmoonsik*

Fixed a Rogue subclass displaying under an incorrect name. 

Updated the localization or stat entry to reflect the renamed subclass as per the 2024 PHB terminology changes.

---

## April 5, 2026

### ⚪ 4.0.9.1

[`13519ca`](https://github.com/Yoonmoonsik/dnd55e/commit/13519cae48b49a6fdedec1a886e984712668d988) · *yoonmoonsik*

Version bump to 4.0.9.1. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix dance bard and rogue DEX unarmed attack

[`78e4b85`](https://github.com/Yoonmoonsik/dnd55e/commit/78e4b8593c0a0bd97762944c7177b3529829c03e) · *yoonmoonsik*

Fixed the **College of Dance Bard** and **Rogue** not correctly using Dexterity for unarmed attack rolls. 

Corrected the passive condition so both classes properly substitute Dexterity for Strength on unarmed strikes when applicable.

---

### 🔵 update githyanki

[`07ac1a2`](https://github.com/Yoonmoonsik/dnd55e/commit/07ac1a2a04c42a94c5b137566f52bd63b86cbd04) · *yoonmoonsik*

Updated the **Githyanki** race to align with the 2024 PHB. 

Revisions cover Astral Knowledge, Githyanki Psionics spell progression, and Psychic Resilience passive to match the revised racial traits.

---

### 🟢 update feats

[`18fe940`](https://github.com/Yoonmoonsik/dnd55e/commit/18fe940e714c6220b4a60409b880bde68df7741d) · *yoonmoonsik*

Updated multiple feats with revised stat entries and condition logic to align with the 2024 PHB feat design, including ASI integrations and updated prerequisites.

---

### ⚪ 4.0.8

[`ee5f8a7`](https://github.com/Yoonmoonsik/dnd55e/commit/ee5f8a7b577ff0a697275081513581b76410fda7) · *yoonmoonsik*

Version bump to 4.0.8. 

Updates internal build metadata in `meta.lsx`.

---

### 🟢 add magic initiate warning

[`e49de3e`](https://github.com/Yoonmoonsik/dnd55e/commit/e49de3e0ce6102d58296469eb71c35403e6db00e) · *yoonmoonsik*

Added a warning message to the **Magic Initiate** feat selection UI. 

Informs players of known limitations or interaction caveats with certain spells obtained through the feat.

---

### 🔴 fix magic initiate wizard (Shield) #32

[`71c82fc`](https://github.com/Yoonmoonsik/dnd55e/commit/71c82fc9707d1da3ddb8fdf3c6cbbced89692549) · *yoonmoonsik*

Fixed **Magic Initiate: Wizard** not correctly granting the **Shield** spell.

Corrected the feat's spell assignment so Shield is properly added to the character's known spells and can be cast using the feat's spell slot.

---

### 🔴 fix magic initiate wizard (True strike) #32 #36

[`d97077d`](https://github.com/Yoonmoonsik/dnd55e/commit/d97077d885ce1ba19db4278e17c067950f40d5c8) · *yoonmoonsik*

Fixed **Magic Initiate: Wizard** not correctly granting the revised **True Strike** cantrip. 

Corrected the feat's cantrip assignment so the 2024 version of True Strike is properly awarded and functions as a melee spell attack.

---

### 🟢 update feats

[`9edd530`](https://github.com/Yoonmoonsik/dnd55e/commit/9edd53071b6f62cb96840c064f084077e0428220) · *yoonmoonsik*

Additional feat updates addressing balance, condition logic, and ASI integration across several PHB and supplemental feats.

---

### 🔵 4.0.7 update backgrounds

[`32b9f02`](https://github.com/Yoonmoonsik/dnd55e/commit/32b9f029b95605d045f12b22beb04c56c20fc1ae) · *yoonmoonsik*

Updated character backgrounds to align with the 2024 PHB. 

Each background now correctly grants its associated Origin Feat, two skill proficiencies, and starting equipment package at character creation.

---

### 🔴 fix potent cantrip

[`756f445`](https://github.com/Yoonmoonsik/dnd55e/commit/756f445feb5ca9e1984435bc08960e89193a6a8d) · *yoonmoonsik*

Fixed the **Potent Cantrip** Evocation Wizard feature not applying correctly. 

Corrected the passive so targets who succeed on saving throws against the wizard's cantrips still take half the spell's damage or its full non-damage effect.

---

### 🔴 fix Frenzy Tooltip

[`cada84f`](https://github.com/Yoonmoonsik/dnd55e/commit/cada84fa86c96398195cace297ed904cfe7eab2d) · *yoonmoonsik*

Fixed the **Berserker Barbarian** Frenzy feature displaying an incorrect tooltip. 

Updated the localization entry to accurately describe the Frenzy exhaustion cost and bonus attack mechanic as per the 2024 rules.

---

## April 4, 2026

### 🟢 4.0.6.3 update feats

[`44fef83`](https://github.com/Yoonmoonsik/dnd55e/commit/44fef83e9079eee69d064a4a87e0a2e9584ed778) · *yoonmoonsik*

Updated the feat list with additional 2024 PHB feats, adding new entries for previously missing options and correcting prerequisite conditions across existing feats.

---

### ⚪ 4.0.5.1

[`0b9bd78`](https://github.com/Yoonmoonsik/dnd55e/commit/0b9bd78ca9b11211571ee7eff9a7dcc5f545fde2) · *yoonmoonsik*

Version bump to 4.0.5.1. 

Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix Fighter_1_SecondWind

[`8a0b241`](https://github.com/Yoonmoonsik/dnd55e/commit/8a0b2417b3a258f2145848f7e1d0fad993fc0c92) · *yoonmoonsik*

Fixed the **Fighter** level 1 **Second Wind** feature not functioning correctly. 

Corrected the spell or passive entry so Second Wind properly restores hit points equal to 1d10 + Fighter level as a bonus action.

---

### 🔴 fix Combat Inspiration

[`7e44624`](https://github.com/Yoonmoonsik/dnd55e/commit/7e446247538e7665184ff583b919b700cdc4974c) · *yoonmoonsik*

Fixed **Combat Inspiration** (College of Valor/Swords Bard) not triggering on the correct events. 

Corrected the interrupt logic so the Bardic Inspiration die can be spent to add to AC when hit or to a damage roll after a successful attack.

---

### 🔴 fix using HitPointDice

[`0629a08`](https://github.com/Yoonmoonsik/dnd55e/commit/0629a08a82cc72f8a21b485c88ffedf317acffea) · *yoonmoonsik*

Fixed an issue with **Hit Point Dice** not being consumed or calculated correctly. 

Corrected the die type assignment or usage logic affecting short rest healing rolls for one or more classes.

---

### 🔴 fix breath weapon

[`a992337`](https://github.com/Yoonmoonsik/dnd55e/commit/a992337b70f5c7527651bfd281030ddcbda1befc) · *yoonmoonsik*

Fixed the **Dragonborn Breath Weapon** not functioning correctly. 

Corrected the spell entry so it uses the proper damage dice, area of effect, and saving throw DC scaling as defined in the 2024 PHB.

---

### 🔴 fix INTERRUPT_FIGHTINGSTYLE_PROTECTION_UNLOCK

[`1c22307`](https://github.com/Yoonmoonsik/dnd55e/commit/1c2230708625edcd3603fe5203de28658168f9d9) · *yoonmoonsik*

Fixed the **Protection** fighting style interrupt not unlocking correctly. 

Corrected the interrupt condition so the reaction properly becomes available when an adjacent ally is targeted by an attack.

---

### 🔴 fix Intercept

[`e66aefe`](https://github.com/Yoonmoonsik/dnd55e/commit/e66aefedbdce5d61e319f1d68d9cc5ae4e79bc4f) · *yoonmoonsik*

Fixed the **Interception** fighting style not correctly reducing incoming damage. 

Corrected the reaction logic so damage is reduced by 1d10 + the character's proficiency bonus when they intercept an attack targeting a nearby ally.

---

### 🟢 4.0.5 update Xanathar's Guide to Everything Feats

[`975a7ab`](https://github.com/Yoonmoonsik/dnd55e/commit/975a7abcd816557da07c5b2b1f82bf692c684118) · *yoonmoonsik*

Updated feats from **Xanathar's Guide to Everything** to align with the 2024 design philosophy. 

Adds ASI bonuses where applicable and revises prerequisite conditions and passive logic for the full XGtE feat list.

---

### ⚪ 4.0.4.1

[`d34bcc9`](https://github.com/Yoonmoonsik/dnd55e/commit/d34bcc98863a71a116ff27690d1169483e57eb15) · *yoonmoonsik*

Version bump to 4.0.4.1. 

Updates internal build metadata in `meta.lsx`.

---

### 🔵 update Helmet of Smiting

[`145db38`](https://github.com/Yoonmoonsik/dnd55e/commit/145db38e032d3ba4e0aaa6725b11c227148ca620) · *yoonmoonsik*

Updated the **Helmet of Smiting** magic item. 

Adjusts its passive bonus or granted ability to better reflect the item's intended effect and ensure it interacts correctly with Paladin smite features.

---

### 🔴 fix Quest_HAG_HagLair_Staff

[`fe47086`](https://github.com/Yoonmoonsik/dnd55e/commit/fe470865297ea9d3c427238b6b71223823b270d2) · *yoonmoonsik*

Fixed the **Hag Lair Staff** quest item not functioning correctly. 

Corrected the item's stat entry or passive so it behaves as intended when obtained during the hag-related quest.

---

### 🔴 fix Lay on Hands #21

[`1cd2f44`](https://github.com/Yoonmoonsik/dnd55e/commit/1cd2f444390838dec7ee5da9094ed48f6e02d735) · *yoonmoonsik*

Fixed **Paladin Lay on Hands** not functioning correctly. 

Corrected the healing pool logic so it properly restores hit points or cures conditions in increments up to the pool's remaining total, as per the 2024 rules.

---

## April 3, 2026

### ⚪ 4.0.4

[`c52dab5`](https://github.com/Yoonmoonsik/dnd55e/commit/c52dab5bf5350438a95ee4e69d07caad9282c340) · *yoonmoonsik*

Version bump to 4.0.4. 

Updates internal build metadata in `meta.lsx`.

---

### 🟢 add dummy progression table for Illrigger

[`b234cbf`](https://github.com/Yoonmoonsik/dnd55e/commit/b234cbfedb42d9feb26229e7da06affd9763b67c) · *yoonmoonsik*

Added a placeholder progression table for the **Illrigger** class. 

Required as a structural entry to allow the class to load correctly before its full feature implementation is complete.

---

### 🔴 fix Custom classes no longer have a Hit Point Dice #11

[`451b9bb`](https://github.com/Yoonmoonsik/dnd55e/commit/451b9bb5133d1dbe2814b5024df3dd3d7425f62c) · *yoonmoonsik*

Fixed custom classes losing their **Hit Point Dice** after a mod update. Corrected the class progression entries so all custom classes properly display and use their correct hit die type for HP rolls and short rest healing.

---

### 🔴 fix tooltips Typo in Localization entries. #12

[`5cbb495`](https://github.com/Yoonmoonsik/dnd55e/commit/5cbb495f26afa739d1e1a7f999bd1ff7f6f8d0aa) · *yoonmoonsik*

Fixed multiple typos found in localization tooltip entries. Corrects spelling and grammar errors in ability and spell descriptions visible to players in the UI.

---

### 🔴 fix Prayer of Healing - No Short Rest effect #14

[`db1d452`](https://github.com/Yoonmoonsik/dnd55e/commit/db1d4522c8338658efb6e31d52f4d8aada69ef71) · *yoonmoonsik*

Fixed **Prayer of Healing** not granting its Short Rest effect as per the 2024 rules. Corrected the spell so it now also allows each target to spend one Hit Die to recover additional hit points, in addition to the base healing.

---

### ⚪ Flame Blade - Spell should have Concentration #16

[`d008764`](https://github.com/Yoonmoonsik/dnd55e/commit/d008764d6147c1baf551e0bd2be546b5be6be845) · *yoonmoonsik*

Added the **Concentration** requirement to **Flame Blade**. The spell was missing this flag, allowing it to be maintained alongside other concentration spells incorrectly.

---

### 🔴 fix Human Race Passive - Skill selection typo #15

[`2b15b2a`](https://github.com/Yoonmoonsik/dnd55e/commit/2b15b2a4c2c8522afeb8a539dd34ba9908abe10b) · *yoonmoonsik*

Fixed a typo in the **Human** race's skill selection passive text. A localization correction ensuring the skill proficiency choice prompt displays the correct wording in the character creation UI.

---

### 🔴 fix Barkskin - Should have no concentration #17

[`e0eaa6a`](https://github.com/Yoonmoonsik/dnd55e/commit/e0eaa6a8f6a7b7ad5bfca87ebad371741f5347a9) · *yoonmoonsik*

Fixed **Barkskin** incorrectly requiring Concentration. As per the 2024 PHB, Barkskin no longer requires concentration — removed the flag so the spell can be maintained alongside other concentration effects.

---

### 🔴 fix Multiclassing into Cleric, Subclass available #13

[`2aba024`](https://github.com/Yoonmoonsik/dnd55e/commit/2aba0245e86f1fd24f877b13f5d3c98d9d5e7f47) · *yoonmoonsik*

Fixed **Cleric** subclass selection becoming available when multiclassing into Cleric at level 1. Corrected the progression entry so the Divine Domain subclass is only selectable at the correct level.

---

### 🔴 fix darkonesblessings

[`a490212`](https://github.com/Yoonmoonsik/dnd55e/commit/a49021273986802fce096b527ef33f6c9bbb06da) · *yoonmoonsik*

Fixed **Dark One's Blessings** (Fiend Warlock) not granting temporary hit points correctly when reducing a hostile creature to 0 HP. Corrected the passive trigger so it properly awards temporary HP equal to the Warlock's Charisma modifier plus level.

---

### ⚪ 4.0.3.4

[`c588454`](https://github.com/Yoonmoonsik/dnd55e/commit/c588454b6094a6f8e3bd6b2004a8f08fa3143565) · *yoonmoonsik*

Version bump to 4.0.3.4. Updates internal build metadata in `meta.lsx`.

---

### 🟢 udpate feats

[`f7a1c0f`](https://github.com/Yoonmoonsik/dnd55e/commit/f7a1c0faf2e3837ea84ecde34751c5fadbead2bb) · *yoonmoonsik*

Updated multiple feats with corrected stat entries, ASI integrations, and revised condition logic to align with the 2024 PHB feat design.

---

### 🔵 update readmd

[`4d54ad2`](https://github.com/Yoonmoonsik/dnd55e/commit/4d54ad29c2ef932dcdb7d4231faa62414e77c633) · *yoonmoonsik*

Updated the repository README with new information reflecting the latest mod features and supported content.

---

### 🔴 fix tooltip

[`9b49269`](https://github.com/Yoonmoonsik/dnd55e/commit/9b4926914160565b4e0f89576786df9719385d93) · *yoonmoonsik*

Fixed an incorrect or missing tooltip on an ability or item. Players will now see accurate descriptions when hovering over the affected element.

---

### ⚪ 4.0.3.3

[`d03c5d3`](https://github.com/Yoonmoonsik/dnd55e/commit/d03c5d3c116299544735b9f163d92bcaf2cf06ec) · *yoonmoonsik*

Version bump to 4.0.3.3. Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix inflict wounds

[`60be1b3`](https://github.com/Yoonmoonsik/dnd55e/commit/60be1b3cc3ad74957476f07b5f8d5bc9fe823adb) · *yoonmoonsik*

Fixed **Inflict Wounds** not dealing damage correctly. Corrected the spell's melee spell attack and damage scaling so it properly deals necrotic damage at the base and higher-slot dice as per the 2024 rules.

---

### ⚪ 4.0.3.2

[`20deeda`](https://github.com/Yoonmoonsik/dnd55e/commit/20deeda65e69fb797a65772c1fdd2e31f0304ab0) · *yoonmoonsik*

Version bump to 4.0.3.2. Updates internal build metadata in `meta.lsx`.

---

### 🔵 update warlock spell list (shadow blade)

[`e287516`](https://github.com/Yoonmoonsik/dnd55e/commit/e287516a230802976dfb0112bc02d41a14ae4efc) · *yoonmoonsik*

Updated the **Warlock** spell list to include **Shadow Blade**. The spell is now properly available for Warlocks to learn, dealing psychic damage and benefiting from advantage in dim light or darkness.

---

### 🔴 fix tooltip

[`337580a`](https://github.com/Yoonmoonsik/dnd55e/commit/337580a1b331f0edbc90c00bf5a9253166b47b05) · *yoonmoonsik*

Fixed an incorrect tooltip on a spell or ability. A localization correction with no gameplay impact.

---

### 🔴 fix Warding Bond - Range #10

[`4892f6c`](https://github.com/Yoonmoonsik/dnd55e/commit/4892f6cccac75ae1242cc33f0dac8495c6e20198) · *yoonmoonsik*

Fixed **Warding Bond** having an incorrect range. Corrected the spell's targeting radius so the bond can only be established with a creature within the proper touch range, and damage sharing only occurs while within 60 feet.

---

### 🔴 fix Sorcerer - Metamagic cost #4

[`032d2b2`](https://github.com/Yoonmoonsik/dnd55e/commit/032d2b27c858be4898510ff4ee34690fe29379ea) · *yoonmoonsik*

Fixed **Sorcerer Metamagic** options having incorrect Sorcery Point costs. Corrected the cost values for affected Metamagic options to match the 2024 PHB pricing (e.g., Twinned Spell, Quickened Spell).

---

### 🔵 update spellthief

[`426b074`](https://github.com/Yoonmoonsik/dnd55e/commit/426b074d875379b012d6a97b0eba82ead73569d0) · *yoonmoonsik*

Updated the **Spellthief** Rogue subclass with revised feature logic. Adjusts its spell-stealing mechanics and arcane larceny passive interactions to better reflect the subclass design.

---

### 🔵 update FOR_OwlbearCubs_Armor_Passive

[`d63ab3a`](https://github.com/Yoonmoonsik/dnd55e/commit/d63ab3ad94d30fd76b0a967def2028ea7d1c5bea) · *yoonmoonsik*

Updated the **Owlbear Cubs** armor passive. Adjusts its bonus condition or boost value to ensure it applies correctly when the associated armor is equipped.

---

### 🔵 update MAG_BardicInspiration_Heal_Hat_Passive

[`bf06b3b`](https://github.com/Yoonmoonsik/dnd55e/commit/bf06b3bed3249c9e15947800160c372eeb65a7c6) · *yoonmoonsik*

Updated the **Bardic Inspiration Heal Hat** passive. Adjusts the item's healing trigger so it correctly restores hit points when a Bardic Inspiration die is expended by the wearer.

---

### 🔵 update MAG_Bard_TempHP_Armor

[`27f94c5`](https://github.com/Yoonmoonsik/dnd55e/commit/27f94c58275822207b97b2529966a6fb2daf56f6) · *yoonmoonsik*

Updated the **Bard Temporary HP Armor** passive. Corrects the temp HP trigger condition so the armor properly grants temporary hit points when Bardic Inspiration is used or a performance ability is activated.

---

### 🔴 minor fix fighting style feats

[`43ad20c`](https://github.com/Yoonmoonsik/dnd55e/commit/43ad20c0b391d906e013492ee646c9ffd32b8525) · *yoonmoonsik*

Applied minor corrections to **Fighting Style** feats. Fixes small condition or prerequisite errors that were causing unintended behavior when these feats were selected outside of a Fighter or Paladin class.

---

### ⚪ 4.0.3

[`6862b84`](https://github.com/Yoonmoonsik/dnd55e/commit/6862b84e524528d077b3f581354296bdd5cb6aa2) · *yoonmoonsik*

Version bump to 4.0.3. Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix Shadowblade - Spell duration and concentration missing. #7

[`4cb78f7`](https://github.com/Yoonmoonsik/dnd55e/commit/4cb78f7107cf40a3379f306a68451e6f269879e4) · *yoonmoonsik*

Fixed **Shadow Blade** missing its duration and Concentration requirement. 
Added the proper spell flags so the summoned psychic blade lasts 1 minute and is dropped if concentration is broken.

---

### 🔴 fix Hold Monster - Description #6

[`be1bfd7`](https://github.com/Yoonmoonsik/dnd55e/commit/be1bfd7cfca5e7c675dc534c13976d4604530b05) · *yoonmoonsik*

Fixed the **Hold Monster** spell displaying an incorrect or placeholder description. 
Updated the localization entry to accurately describe its Paralyzed condition, saving throw, and concentration mechanics.

---

### 🔴 fix Druid - Primal Order Selection type #8

[`f830a5d`](https://github.com/Yoonmoonsik/dnd55e/commit/f830a5de5aed7395e2aa9a89a982db55e22a5f32) · *yoonmoonsik*

Fixed the **Druid Primal Order** selection using the wrong UI selection type. 
Corrected the progression entry so the Magician or Warden choice appears as a proper single-select option at character creation.

---

### 🔴 fix Druid - Subclass Icon Missing #9

[`48a920f`](https://github.com/Yoonmoonsik/dnd55e/commit/48a920f50e7d25e199233074badebb12ca319bf1) · *yoonmoonsik*

Fixed Druid subclasses displaying without an icon in the character creation screen. 
Added the missing icon references so all Druid circles show their correct visual in the subclass selection UI.

---

### 🔴 fix Sorcerer - Draconic Bloodline HP Increase Tooltip #5

[`a24fe9a`](https://github.com/Yoonmoonsik/dnd55e/commit/a24fe9ae75a15f1197ebdb9312cd022477e689fc) · *yoonmoonsik*

Fixed the **Draconic Bloodline Sorcerer** HP increase feature displaying an incorrect tooltip. 
Updated the localization so the passive's description correctly states it adds 1 HP per Sorcerer level.

---

### ⚪ TrueStrike variant not selectable. #2

[`29d0cb4`](https://github.com/Yoonmoonsik/dnd55e/commit/29d0cb4432d7ab5d24ab304c5792aea2839b13ef) · *yoonmoonsik*

Fixed the **True Strike** cantrip variant not appearing as a selectable option in the spell selection UI. 
Corrected the spell entry flags so the 2024 version is properly listed and choosable.

---

### 🔴 fix Astarion and Gale Cannot Respec #3

[`e8e07dc`](https://github.com/Yoonmoonsik/dnd55e/commit/e8e07dcde0cefe4f06fde47128aedd6aea30827d) · *yoonmoonsik*

Fixed **Astarion** and **Gale** being unable to respec after installing the mod. 
Corrected their companion progression entries so the respec system can properly process their class data without errors.

---

### 🔴 fix Human Origin Feat - Musician #1

[`b077864`](https://github.com/Yoonmoonsik/dnd55e/commit/b077864ab006876d6400f89f8459bf44a7856caa) · *yoonmoonsik*

Fixed the **Human** race Origin Feat not correctly granting the **Musician** feat. The first reported issue on the tracker — corrected the feat assignment so Human characters can properly select and receive Musician at character creation.

---

### ⚪ 4.0.2.7

[`23decc2`](https://github.com/Yoonmoonsik/dnd55e/commit/23decc22720bbde3a9bf2ca59a2d7f5d002162d8) · *yoonmoonsik*

Version bump to 4.0.2.7. Updates internal build metadata in `meta.lsx`.

---

### 🔴 minor fix weaponmastery

[`0857721`](https://github.com/Yoonmoonsik/dnd55e/commit/0857721402e0c7a89ae4d421c228725ffa946552) · *yoonmoonsik*

Applied minor corrections to **Weapon Mastery** passive entries. 
Fixes a small condition or flag issue causing unintended behavior in one or more mastery properties.

---

### 🔴 fix divine favor

[`81188c7`](https://github.com/Yoonmoonsik/dnd55e/commit/81188c7a888a114c3f1a55ee0dfc425489215715) · *yoonmoonsik*

Fixed **Divine Favor** not applying its radiant damage bonus correctly. 
Corrected the spell's concentration boost so it properly adds 1d4 radiant damage to weapon attack hits for the spell's duration.

---

### 🔴 fix sharpshooter

[`e73383e`](https://github.com/Yoonmoonsik/dnd55e/commit/e73383e7bc4fbaa6bab16b46d70f719d730e14de) · *yoonmoonsik*

Fixed the **Sharpshooter** feat not functioning correctly. 
Corrected the passive so it properly ignores half and three-quarters cover on ranged attacks, and the optional -5/+10 trade-off works as intended per the 2024 rules.

---

### ⚪ 레퍼런스 자료 추가

[`2b6ab6a`](https://github.com/Yoonmoonsik/dnd55e/commit/2b6ab6a4eb93a0bd47d49b833cef2790c1355d78) · *yoonmoonsik*

Added internal reference materials for the developer. 
Documentation or source files used as design references — no gameplay changes.

---

## April 2, 2026

### 🔴 fix hellrider pride tooltip

[`76c2815`](https://github.com/Yoonmoonsik/dnd55e/commit/76c28158dcca160c7eef78da5733022a39202251) · *yoonmoonsik*

Fixed the **Hellrider's Pride** item or feature displaying an incorrect tooltip. 
Updated the localization entry to accurately describe its bonus or effect.

---

### 🔴 fix GLO_Baelen

[`410e9a7`](https://github.com/Yoonmoonsik/dnd55e/commit/410e9a72727b47ca12c74b6c67cb20c24d3a28d0) · *yoonmoonsik*

Fixed an issue with **Baelen** (NPC in the Underdark mushroom field) caused by mod interactions. 
Corrected his stat or script entry so he behaves correctly in the encounter.

---

### 🔴 fix BardicInspiration_Ability

[`357afce`](https://github.com/Yoonmoonsik/dnd55e/commit/357afce102be1e37d83829d9f12c3dcbb26d1dd9) · *yoonmoonsik*

Fixed the **Bardic Inspiration** ability not triggering or refreshing correctly. 
Corrected the passive or spell condition so inspiration dice are properly granted and consumed per the 2024 rules.

---

### 🔴 fix weaponmastery push

[`99c21a6`](https://github.com/Yoonmoonsik/dnd55e/commit/99c21a60b1f908dcc187b96b32957f34fac998c2) · *yoonmoonsik*

Fixed the **Push** Weapon Mastery property not working correctly. 
Corrected the passive trigger so successfully hitting with a Push-mastery weapon properly allows the attacker to push the target up to 10 feet away.

---

### 🔴 fix Interception

[`00226e0`](https://github.com/Yoonmoonsik/dnd55e/commit/00226e07f75869447c22dd219be9e830cda77511) · *yoonmoonsik*

Fixed the **Interception** fighting style not reducing damage correctly. 
Corrected the reaction logic so damage to a nearby ally is properly reduced by 1d10 + proficiency bonus when the reaction is used.

---

### ⚪ 4.0.2.4

[`816b589`](https://github.com/Yoonmoonsik/dnd55e/commit/816b58976b30a7fd9f10ca6683e2c173abc221ca) · *yoonmoonsik*

Version bump to 4.0.2.4. Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix weaponmasteries

[`39bfd3e`](https://github.com/Yoonmoonsik/dnd55e/commit/39bfd3e5280537d1bab9faa2adf15c07a06f4d04) · *yoonmoonsik*

Fixed multiple **Weapon Mastery** properties not functioning correctly. 
Broad correction pass across Cleave, Graze, Sap, Topple, and other mastery passives to address condition and trigger issues.

---

### 🔵 update npc druid

[`3accc71`](https://github.com/Yoonmoonsik/dnd55e/commit/3accc7101e649a545ed4bcd2213e0865e258526e) · *yoonmoonsik*

Updated NPC Druid stat entries to reflect the mod's revised Druid class. 
Ensures enemy and friendly Druid NPCs use the updated Wild Shape, spell list, and class features.

---

### 🟢 feat: Enhance Interrupt and Passive mechanics, add Hit Point Dice spells

[`25319f8`](https://github.com/Yoonmoonsik/dnd55e/commit/25319f87417c3f666c16c35a955b4b4981561bd1) · *yoonmoonsik*

Overhauled the interrupt and passive trigger framework to support more complex reaction-based mechanics. 
Added Hit Point Dice spell entries enabling proper short rest healing rolls directly from the UI.

---

### 🔵 update Illusionist

[`11b4559`](https://github.com/Yoonmoonsik/dnd55e/commit/11b455921e3465f39d61adb32bb16186d5b2e89e) · *yoonmoonsik*

Updated the **School of Illusion Wizard** subclass. 
Adjusts Improved Minor Illusion, Malleable Illusions, and Illusory Reality feature logic to better match the 2024 PHB implementation.

---

### 🔵 update Great Old One

[`b337c55`](https://github.com/Yoonmoonsik/dnd55e/commit/b337c5507fdef040a6ad05be6ccd5730cb3b0242) · *yoonmoonsik*

Updated the **Great Old One Warlock** patron with revised feature logic. 
Adjusts Awakened Mind telepathy, Entropic Ward, and Thought Shield features to align with the 2024 Warlock redesign.

---

### 🔵 update dark one's blessings

[`4cdc883`](https://github.com/Yoonmoonsik/dnd55e/commit/4cdc8833ff930b2dff4bb4f83b617d3f7d1e5363) · *yoonmoonsik*

Updated **Dark One's Blessings** (Fiend Warlock) with revised passive logic. 
Ensures the temporary HP grant triggers correctly on kill and scales properly with Charisma modifier and Warlock level.

---

## April 1, 2026

### ⚪ 4.0.0.10

[`8577fc4`](https://github.com/Yoonmoonsik/dnd55e/commit/8577fc4b1709c756c42d18935a073ee4de3554f4) · *yoonmoonsik*

Version bump to 4.0.0.10.
Updates internal build metadata in `meta.lsx`.

---

### 🔴 fix MAG_Fire_AlwaysDippedInFire_Greatsword

[`41b6747`](https://github.com/Yoonmoonsik/dnd55e/commit/41b6747a9b682d12c6a38d7c84bd8faa85658f24) · *yoonmoonsik*

Fixed the **Always Dipped in Fire Greatsword** passive not applying its fire damage correctly. 
Corrected the passive boost so the weapon consistently deals its additional fire damage on hit without requiring manual dipping.

---

### 🔴 fix elf respec

[`3fb9538`](https://github.com/Yoonmoonsik/dnd55e/commit/3fb953898cd6197af9d6b48c01eab49143c2dd69) · *yoonmoonsik*

Fixed **Elf** characters being unable to respec correctly. 
Corrected the Elf race progression entry so the respec system can process their racial traits without errors or softlocks.

---

### ⚪ 4.0.0.9

[`3a06433`](https://github.com/Yoonmoonsik/dnd55e/commit/3a06433252ea6a6ee17c0e766b22625d6fec17e9) · *yoonmoonsik*

Version bump to 4.0.0.9. 
Updates internal build metadata in `meta.lsx`.

---

### ⚪ V4

[`86d85ef`](https://github.com/Yoonmoonsik/dnd55e/commit/86d85ef93d2258f7c0366da7119ad8e1e445e99e) · *yoonmoonsik*

Major version milestone: V4.
Marks the beginning of the Version 4 architecture, introducing the restructured class, race, and spell framework that all subsequent updates build upon.

---

### 🟢 Add new equipment sets, spell sets, and race documentation

[`0932be6`](https://github.com/Yoonmoonsik/dnd55e/commit/0932be659ae9f07a075f08b25a9bb36acbae5632) · *yoonmoonsik*

Added new equipment set definitions, spell set groupings, and internal documentation for race implementations. 
Foundational content added as part of the V4 restructure.

---

### 🔵 update celestial

[`76509cb`](https://github.com/Yoonmoonsik/dnd55e/commit/76509cbc525b0e629aa80e2b6db4397e73ba813f) · *yoonmoonsik*

Updated the **Celestial Warlock** patron with revised feature logic. 
Adjusts Healing Light, Radiant Soul, and Celestial Resilience features to align with the 2024 Warlock patron redesign.

---

### 🔵 update Spiritual Weapon

[`6d7ca31`](https://github.com/Yoonmoonsik/dnd55e/commit/6d7ca3105b694ab16b62ebf7695961499df5675c) · *yoonmoonsik*

Updated **Spiritual Weapon** to reflect the 2024 rules. 
The spell no longer requires concentration and now functions as a Bonus Action summon that attacks automatically, adjusting the spell's behavior accordingly.

---

## March 31, 2026

### 🔵 update archfey

[`21f51d5`](https://github.com/Yoonmoonsik/dnd55e/commit/21f51d521bc7066ce0653975b6092dbb6da10bd6) · *yoonmoonsik*

Updated the **Archfey Warlock** patron with revised feature logic. 
Adjusts Fey Presence, Misty Escape, Beguiling Defenses, and Dark Delirium to align with the 2024 Warlock patron redesign.

---

### 🔴 minor fixes

[`79ba13e`](https://github.com/Yoonmoonsik/dnd55e/commit/79ba13eb95c13eb1e14345390143a47959fdb0ff) · *yoonmoonsik*

Applied several minor corrections across stat entries, spell conditions, or passive flags to address small bugs identified during testing.

---

### ⚪ increase NPC level by 1 in arcane tower

[`5f50436`](https://github.com/Yoonmoonsik/dnd55e/commit/5f50436a239d456dd8cc92a9911335fb949d3eea) · *yoonmoonsik*

Increased the level of NPCs in the **Arcane Tower** by 1. 
A balance adjustment to make the encounter more appropriate for the player's expected power level when reaching that area.

---

### 🔵 update icons

[`2a058a2`](https://github.com/Yoonmoonsik/dnd55e/commit/2a058a2df360969ad3cc9ca5c3a1470ce1428d19) · *yoonmoonsik*

Updated icons for various abilities, spells, or class features. 
Ensures all affected elements display a proper and representative visual in the action bar and UI.

---

### 🔵 update Draconic Sorcery and Wild Magic Sorcery

[`cd69949`](https://github.com/Yoonmoonsik/dnd55e/commit/cd699496cb85c3abada31720056ffcc37d59b2e3) · *yoonmoonsik*

Updated **Draconic Bloodline** and **Wild Magic** Sorcerer subclasses to align with the 2024 PHB. 
Revisions cover Draconic Resilience, Tides of Chaos, and Wild Magic Surge table interactions.

---

### 🔵 update Clockwork Socery

[`5d7fe52`](https://github.com/Yoonmoonsik/dnd55e/commit/5d7fe52ce214773182df364253187601ec607842) · *yoonmoonsik*

Updated the **Clockwork Soul Sorcerer** subclass to align with the 2024 rules. 
Adjusts Clockwork Magic spell list, Restore Balance interrupt, and Bulwark of Law feature implementation.

---

### 🔵 update abberant sorcery

[`76f8b80`](https://github.com/Yoonmoonsik/dnd55e/commit/76f8b80f5f271127feb394141fbdec42a17b3eb7) · *yoonmoonsik*
Updated the **Aberrant Mind Sorcerer** subclass to align with the 2024 rules. Adjusts Telepathic Speech, Psionic Spells, Revelation in Flesh, and Warped Being feature implementations.

---

### 🔴 minor fixes

[`e921cc9`](https://github.com/Yoonmoonsik/dnd55e/commit/e921cc96c81ab6cd66a517750ff4929b38adc060) · *yoonmoonsik*
Applied minor corrections across several stat or spell entries to address small unintended behaviors identified during the Sorcerer subclass update pass.

---

## March 30, 2026

### 🔵 update HypnoticPattern

[`d0dcf5b`](https://github.com/Yoonmoonsik/dnd55e/commit/d0dcf5bbaee8b4889e7682cc221842c822b4ce69) · *yoonmoonsik*
Updated **Hypnotic Pattern** to reflect the 2024 rules. Adjusts the Charmed condition application, area of effect, and the condition that breaks the effect to match the revised spell behavior.

---

### 🔵 update ArmorOfAgathys

[`ae2981e`](https://github.com/Yoonmoonsik/dnd55e/commit/ae2981e1b2c9c242a71c1226a5ea5a15a3294fa8) · *yoonmoonsik*
Updated **Armor of Agathys** to reflect the 2024 rules. Adjusts the temporary HP amount and cold damage retaliation scaling at higher spell slots to match the revised values.

---

### 🔵 update jump

[`2bae3ee`](https://github.com/Yoonmoonsik/dnd55e/commit/2bae3ee501726584ea5b0d6305a379917a3d109e) · *yoonmoonsik*
Updated the **Jump** spell to reflect the 2024 redesign. The spell now targets up to 30 creatures, grants a Jump distance of 30 feet as a Bonus Action, and no longer requires concentration.

---

### 🟢 add extend rage

[`fb37ed4`](https://github.com/Yoonmoonsik/dnd55e/commit/fb37ed440e3401639e15c71b346a5cf70e4889a9) · *yoonmoonsik*
Added the **Extend Rage** passive for Barbarians. Implements the 2024 rule allowing Barbarians to maintain rage for an additional round when they would otherwise lose it, as long as they take damage or attack.

---

### 🔴 fix Psychic Blade

[`0b41866`](https://github.com/Yoonmoonsik/dnd55e/commit/0b41866bf3d121963fda70d02b69718f428854d4) · *yoonmoonsik*
Fixed **Psychic Blade** (Soulknife Rogue) not dealing damage correctly. Corrected the finesse melee or ranged spell attack logic so the blade properly deals psychic damage using the Rogue's Dexterity modifier.

---

### 🔵 update Soulknife

[`cc548fb`](https://github.com/Yoonmoonsik/dnd55e/commit/cc548fbb3f878bd5656b5cad601df3c58bc5d03d) · *yoonmoonsik*
Updated the **Soulknife Rogue** subclass to align with the 2024 rules. Revisions cover Psionic Power dice, Psychic Blade generation, Psionic Veil, and Rend Mind feature implementations.

---

### 🔵 update fey wanderer

[`e7cb188`](https://github.com/Yoonmoonsik/dnd55e/commit/e7cb188082835cabc2cb30fc4dd3d1bfee086b47) · *yoonmoonsik*
Updated the **Fey Wanderer Ranger** subclass to align with the 2024 rules. Adjusts Dreadful Strikes, Otherworldly Glamour, Beguiling Twist, and Fey Reinforcements feature implementations.

---

### 🔵 update oath of glory paladin

[`6754a37`](https://github.com/Yoonmoonsik/dnd55e/commit/6754a376d36e2ebc4b7ca5c01d5ca6847692a3fe) · *yoonmoonsik*
Updated the **Oath of Glory Paladin** subclass to align with the 2024 rules. Adjusts Inspiring Smite, Peerless Athlete, Aura of Alacrity, and Glorious Defense feature implementations.

---

### 🔵 update Mercy Monk

[`f9aaa00`](https://github.com/Yoonmoonsik/dnd55e/commit/f9aaa00e096e3dca61d2abc115ea893a59cca30e) · *yoonmoonsik*
Updated the **Way of Mercy Monk** subclass to align with the 2024 rules. Adjusts Hand of Healing, Hand of Harm, Implements of Mercy, and Hand of Ultimate Mercy feature implementations.

---

### 🔵 update Level 2: Wild Companion

[`5361b20`](https://github.com/Yoonmoonsik/dnd55e/commit/5361b206665e5a062250357a3f93c46d13fa932a) · *yoonmoonsik*
Updated the **Wild Companion** Druid level 2 optional feature. Corrects the Find Familiar spell grant so it properly uses a Wild Shape charge instead of a spell slot, as per the 2024 rules.

---

## March 29, 2026

### 🔵 Update Psi Warrior

[`26de590`](https://github.com/Yoonmoonsik/dnd55e/commit/26de5904742154bcc5f4e404696f1f1838efe828) · *yoonmoonsik*
Updated the **Psi Warrior Fighter** subclass to align with the 2024 rules. Revisions cover Psionic Power dice, Telekinetic Movement, Guarded Mind, Bulwark of Force, and Telekinetic Master feature implementations.

---

### 🔵 update circle of the sea

[`9cc0811`](https://github.com/Yoonmoonsik/dnd55e/commit/9cc0811db409e95884c2764a907059a12c5e0345) · *yoonmoonsik*
Updated the **Circle of the Sea Druid** subclass to align with the 2024 rules. Adjusts Wrath of the Sea, Aquatic Affinity, Stormborn, and Oceanic Gift feature implementations.

---

### 🔵 update circle of the sea spells

[`52cc297`](https://github.com/Yoonmoonsik/dnd55e/commit/52cc297d962401145ad5139e5641dfcc4fa82c4d) · *yoonmoonsik*
Updated the **Circle of the Sea** expanded spell list. Ensures all ocean and storm-themed domain spells are properly granted at the correct Druid levels.

---

### 🔵 update Nature's Ward

[`4317136`](https://github.com/Yoonmoonsik/dnd55e/commit/431713653d15bd0c1b28c2356613e3f1d3d1b580) · *yoonmoonsik*
Updated **Nature's Ward** (Circle of the Land Druid level 10 feature). Corrects the immunity granting logic so the Druid properly becomes immune to poison, disease, and charm/fear effects from Elementals and Fey.

---

### 🔵 update Land's Aid

[`abcce70`](https://github.com/Yoonmoonsik/dnd55e/commit/abcce70d7463ada3c41e3aad391913a4811431a9) · *yoonmoonsik*
Updated **Land's Aid** (Circle of the Land Druid feature). Adjusts the healing and necrotic damage pulse logic so it properly affects targets in range when the Druid uses this Channel Divinity option.

---

### 🔵 update Circle of the Land Spells

[`bb2c27a`](https://github.com/Yoonmoonsik/dnd55e/commit/bb2c27ab64aff1353cb0e6e6edb92e1a5a5e75d1) · *yoonmoonsik*
Updated the **Circle of the Land** expanded spell lists for all terrain types (Arctic, Coast, Desert, Forest, Grassland, Mountain, Swamp, Underdark). Ensures the correct terrain-themed spells are granted at each tier.

---

### 🔵 Update Resource Icons

[`4676f23`](https://github.com/Yoonmoonsik/dnd55e/commit/4676f23019f68e65f5f47e2e2e25235d5ffcf253) · *yoonmoonsik*
Updated icons for class and ability resource trackers. Ensures Rage charges, Ki points, Sorcery Points, and other resource pools display with clear and distinct icons in the UI.

---

### 🟢 update feats

[`815654c`](https://github.com/Yoonmoonsik/dnd55e/commit/815654c2ee46c5143f8f57d4abf3dd18835ad6c2) · *yoonmoonsik*
Updated multiple feats with revised passive logic and ASI integration to align with the 2024 PHB feat redesign, adding prerequisites and correcting condition triggers.

---

### 🔵 update fighting styles

[`8e60728`](https://github.com/Yoonmoonsik/dnd55e/commit/8e60728b4fbdfd37e942fc322d5283b6f0c28097) · *yoonmoonsik*
Updated **Fighting Styles** across all applicable classes. Adjusts Archery, Defense, Dueling, Great Weapon Fighting, Protection, and Two-Weapon Fighting to reflect the 2024 PHB definitions and passive boost logic.

---

### 🔵 update evoker

[`20b518d`](https://github.com/Yoonmoonsik/dnd55e/commit/20b518d3fa51963449e63f8dafe6e2de1e419041) · *yoonmoonsik*
Updated the **School of Evocation Wizard** subclass to align with the 2024 rules. Adjusts Sculpt Spells, Potent Cantrip, Empowered Evocation, and Overchannel feature implementations.

---

### 🔵 update Durable

[`e93d224`](https://github.com/Yoonmoonsik/dnd55e/commit/e93d224aa03fefc0b249f1cad41989a627e0117c) · *yoonmoonsik*
Updated the **Durable** feat to align with the 2024 PHB. The feat now grants +1 Constitution, and when the character rolls a Hit Die to regain HP, they regain the maximum possible amount on a roll of 1 or 2.

---

### 🔵 update Dungeon Delver

[`a301982`](https://github.com/Yoonmoonsik/dnd55e/commit/a30198243c4f39f02aab614f683eff1022cadcf3) · *yoonmoonsik*
Updated the **Dungeon Delver** feat to align with the 2024 PHB. Adds +1 to an ability score of choice and revises the passive bonuses for trap detection, secret door searching, and resistance to trap damage.

---

### 🔵 update Ritual Caster

[`e6d7707`](https://github.com/Yoonmoonsik/dnd55e/commit/e6d7707128917ca6bd9b6da7f4681e1942f1c531) · *yoonmoonsik*
Updated the **Ritual Caster** feat to align with the 2024 PHB. The feat now grants +1 to Intelligence, Wisdom, or Charisma, and allows ritual spells to be cast from a ritual book without preparing them.

---

### 🔵 update spell icons

[`03d2085`](https://github.com/Yoonmoonsik/dnd55e/commit/03d2085deb41b92f69586cfb8a252a7c6e56b84d) · *yoonmoonsik*
Updated icons for various spells. Ensures all spells display a clear, representative icon in the spellbook, action bar, and tooltip UI.

---

### 🔵 update Sword Burst

[`aaa2528`](https://github.com/Yoonmoonsik/dnd55e/commit/aaa252831a59f311881e30f47ae65480f6da76ac) · *yoonmoonsik*
Updated **Sword Burst** to reflect the 2024 cantrip rules. Adjusts the AOE and damage scaling so it properly affects all creatures within 5 feet and deals force damage scaling with character level.

---

### 🔵 update Green-Flame Blade

[`e80ee3b`](https://github.com/Yoonmoonsik/dnd55e/commit/e80ee3b427e3353a7431a3c58ea690f75fbe3125) · *yoonmoonsik*
Updated **Green-Flame Blade** to reflect the 2024 cantrip rules. Adjusts the secondary fire damage leap mechanic and scaling so it properly uses the caster's spellcasting modifier at the appropriate character levels.

---

### 🔵 update Tasha's Mind Whip

[`9cd16c8`](https://github.com/Yoonmoonsik/dnd55e/commit/9cd16c8b2aa9ccac8c77f9241ca5a1e0043329fa) · *yoonmoonsik*
Updated **Tasha's Mind Whip** to reflect the 2024 spell rules. Adjusts the psychic damage, action restriction effect, and additional target scaling at higher spell slots.

---

## March 28, 2026

### 🔵 update Vitriolic Sphere

[`23afa9f`](https://github.com/Yoonmoonsik/dnd55e/commit/23afa9f81ff513bbc55ae1071f4f6e753ae68340) · *yoonmoonsik*
Updated **Vitriolic Sphere** to reflect the 2024 spell rules. Adjusts the acid damage on hit and the ongoing acid damage on failed saves to match the revised damage values and scaling.

---

### 🔵 update Snilloc's Snowball Swarm

[`fe5f444`](https://github.com/Yoonmoonsik/dnd55e/commit/fe5f44421c0c38fa6d2c9a5149e5984fe0076602) · *yoonmoonsik*
Updated **Snilloc's Snowball Swarm** to reflect the 2024 spell rules. Adjusts the cold damage area of effect and higher-slot scaling to match the revised spell behavior.

---

### 🔵 update wrathful smite vfx

[`a313bb6`](https://github.com/Yoonmoonsik/dnd55e/commit/a313bb608c4014b4750e737716f2ec04e945aff8) · *yoonmoonsik*
Updated the visual effects for **Wrathful Smite**. Improves the VFX presentation of the smite to better convey the psychic terror it inflicts on the target.

---

### 🔵 update READMD

[`fa63308`](https://github.com/Yoonmoonsik/dnd55e/commit/fa633082e1df2226316393f4cac9657db3bbacd3) · *yoonmoonsik*
Updated the repository README with new documentation covering recently implemented spells, classes, and features.

---

### 🔵 update Wrathful Smite

[`5cd4edc`](https://github.com/Yoonmoonsik/dnd55e/commit/5cd4edc80ef183300fafce8648600e346ca163eb) · *yoonmoonsik*
Updated **Wrathful Smite** to reflect the 2024 rules. The spell no longer requires concentration and now automatically applies its psychic damage and Frightened condition on a failed Wisdom save when the attack hits.

---

### 🔵 update witch bolt

[`4559e93`](https://github.com/Yoonmoonsik/dnd55e/commit/4559e935b1299379c8f1349d9578289fbc6001ad) · *yoonmoonsik*
Updated **Witch Bolt** to reflect the 2024 rules. The spell now deals lightning damage on casting and on each subsequent turn as a Bonus Action without requiring concentration, and scales better at higher slots.

---

### 🔵 update Web

[`d2e48ec`](https://github.com/Yoonmoonsik/dnd55e/commit/d2e48ec0d78438824d9acdd4e4dd60e7397b0235) · *yoonmoonsik*
Updated **Web** to reflect the 2024 spell rules. Adjusts the Restrained condition application, Strength save DC, and the flammability interaction to match the revised spell behavior.

---

### 🔵 update Warding Bond

[`0e8d664`](https://github.com/Yoonmoonsik/dnd55e/commit/0e8d6642b76b785054a945ce762e7fa7c0a88f28) · *yoonmoonsik*
Updated **Warding Bond** to reflect the 2024 rules. Adjusts the shared damage, AC bonus, and saving throw bonus to ensure the spell functions correctly at range and applies damage sharing accurately.

---

### 🔵 update Vicious Mockery

[`6c6f78b`](https://github.com/Yoonmoonsik/dnd55e/commit/6c6f78b406fa886acc6a1d7b6c5ec2513e0e547b) · *yoonmoonsik*
Updated **Vicious Mockery** to reflect the 2024 cantrip rules. The cantrip now deals psychic damage on a failed Wisdom save and imposes disadvantage on the target's next attack roll, scaling with character level.

---

### 🔵 update searing smite

[`6cb0d8c`](https://github.com/Yoonmoonsik/dnd55e/commit/6cb0d8cb608e9564447cc89460f560ee56c1beee) · *yoonmoonsik*
Updated **Searing Smite** to reflect the 2024 rules. The spell no longer requires concentration — fire damage is dealt immediately on hit and the ongoing burning damage persists automatically for the duration.

---

### 🔵 update thunderous smite

[`0678272`](https://github.com/Yoonmoonsik/dnd55e/commit/0678272b4b882f0214e70e633054ca2629da5fd7) · *yoonmoonsik*
Updated **Thunderous Smite** to reflect the 2024 rules. The spell no longer requires concentration and now deals thunder damage plus a Strength save-based push effect immediately on hit.

---

### ⚪ remove not using script

[`750ab87`](https://github.com/Yoonmoonsik/dnd55e/commit/750ab870a3aa9601256b30f1ac99c1e16055efe7) · *yoonmoonsik*
Removed unused script files from the mod. A code cleanup with no gameplay impact.

---

### 🔴 fix magicinitiate

[`6dcdedf`](https://github.com/Yoonmoonsik/dnd55e/commit/6dcdedfd405ea008950f05c0f2a270281c2da119) · *yoonmoonsik*
Fixed **Magic Initiate** not correctly granting its selected spells. Corrected the feat's spell assignment logic to ensure the chosen cantrips and leveled spell are properly added to the character's spell list.

---

### 🔵 update Tasha's Hideous Laughter

[`6f119e8`](https://github.com/Yoonmoonsik/dnd55e/commit/6f119e8cb6c6a43317573c586b92ae0309f8e636) · *yoonmoonsik*
Updated **Tasha's Hideous Laughter** to reflect the 2024 spell rules. Adjusts the Wisdom save, Incapacitated condition, and the end-of-turn save to break the effect to match the revised spell behavior.

---

### 🔵 update stoneskin

[`7468cb3`](https://github.com/Yoonmoonsik/dnd55e/commit/7468cb33017d3cb647402250fc81a90156d3021a) · *yoonmoonsik*
Updated **Stoneskin** to reflect the 2024 spell rules. The spell now grants resistance to Bludgeoning, Piercing, and Slashing damage without requiring concentration, updating the status flags accordingly.

---

### 🔵 update sleep

[`6b88ca5`](https://github.com/Yoonmoonsik/dnd55e/commit/6b88ca5d54b105d5b98acd602bd12159b312318f) · *yoonmoonsik*
Updated **Sleep** to reflect the 2024 spell rules. The spell now affects creatures based on a 5d8 HP pool (no longer scaling with slots), affects any creature regardless of current HP, and no longer has the lowest-HP-first priority.

---

### 🔵 update Searing Smite

[`6f28ecf`](https://github.com/Yoonmoonsik/dnd55e/commit/6f28ecfb651502ee4bd1f167b100cdb7282e9b0b) · *yoonmoonsik*
Additional update pass on **Searing Smite** to finalize the concentration removal and ensure the ongoing fire damage and Constitution save logic function correctly in all combat scenarios.

---

### 🔵 update spell

[`5bd4acc`](https://github.com/Yoonmoonsik/dnd55e/commit/5bd4acc9acd2feda71ef452bd4f39cf8e1a609f3) · *yoonmoonsik*
General spell update pass. Adjusts stat entries for several spells to correct scaling, damage type, or condition flags that were not yet aligned with the 2024 rules.

---

### 🔵 update Phantom Steed, Otiluke's Resilient Sphere, Phantasmal Killer, Polymorph

[`fe67bf3`](https://github.com/Yoonmoonsik/dnd55e/commit/fe67bf3b1fcccbff5ee2c9780257d22ee70cfdca) · *yoonmoonsik*
Updated **Phantom Steed**, **Otiluke's Resilient Sphere**, **Phantasmal Killer**, and **Polymorph** to reflect the 2024 spell rules. Adjusts duration, concentration requirements, saving throw conditions, and effect interactions for each spell.

---

### 🔵 update MistyStep

[`a318182`](https://github.com/Yoonmoonsik/dnd55e/commit/a3181826b2766fc7f692456b98b480d65b4e231c) · *yoonmoonsik*
Updated **Misty Step** to reflect the 2024 spell rules. Adjusts the teleportation distance, Bonus Action cost, and any condition restrictions to match the revised spell behavior.

---

### 🔵 update Melf's Acid Arrow

[`70e962d`](https://github.com/Yoonmoonsik/dnd55e/commit/70e962dc3416a5e4fbaa24ec9a5f87e3785d89bb) · *yoonmoonsik*
Updated **Melf's Acid Arrow** to reflect the 2024 spell rules. Adjusts the ranged spell attack damage, ongoing acid damage on a failed save, and higher-slot scaling values.

---

### 🔵 update Mass Healing Word

[`e9ff562`](https://github.com/Yoonmoonsik/dnd55e/commit/e9ff56230ae8e70d8d1755ce60faaaeb947f9ceb) · *yoonmoonsik*
Updated **Mass Healing Word** to reflect the 2024 spell rules. Adjusts the healing formula and number of targets to match the revised Bonus Action healing spell behavior.

---

### 🔵 update Mass Cure Wounds

[`22938b6`](https://github.com/Yoonmoonsik/dnd55e/commit/22938b66cb8c43ee1cc3a7708e1bc4478c54ab78) · *yoonmoonsik*
Updated **Mass Cure Wounds** to reflect the 2024 spell rules. Adjusts the healing amount per target and the maximum number of creatures affected at base and higher spell slots.

---

### 🔵 update magic weapon

[`90f6e95`](https://github.com/Yoonmoonsik/dnd55e/commit/90f6e958c63e9564e99da76b38e8d4309636fc08) · *yoonmoonsik*
Updated **Magic Weapon** to reflect the 2024 spell rules. The spell now grants a +1 bonus at base and scales to +2 at 5th level and +3 at 7th level, and no longer requires concentration.

---

## March 27, 2026

### 🔵 update spells

[`224e210`](https://github.com/Yoonmoonsik/dnd55e/commit/224e210b9f9f3f346e4894c6fd3f2b2cc6043fb8) · *yoonmoonsik*
General spell update pass covering several spells not yet revised to 2024 standards. Adjusts damage, duration, concentration flags, and saving throw conditions across the affected entries.

---

### 🔵 update spells

[`a2fd3ab`](https://github.com/Yoonmoonsik/dnd55e/commit/a2fd3ab54f08a5156930570e18463b39c587edbb) · *yoonmoonsik*
Continued spell update pass. Corrects stat entries for additional spells to align damage scaling, area of effect, and condition logic with the 2024 PHB spell list.

---

### 🔵 update spells

[`42bc352`](https://github.com/Yoonmoonsik/dnd55e/commit/42bc3529d175949b2f5ed96647780e22da32b255) · *yoonmoonsik*
Further spell update pass. Finalizes remaining spell entries requiring adjustments to duration, range, or effect conditions per the 2024 rules.

---

### 🔵 update cloud of daggers

[`9b3fc21`](https://github.com/Yoonmoonsik/dnd55e/commit/9b3fc21a121a138b5cb2fd7c1b791b972fd1098a) · *yoonmoonsik*
Updated **Cloud of Daggers** to reflect the 2024 spell rules. Adjusts the damage dealt to creatures entering or starting their turn in the area, and the concentration requirement handling.

---

### 🔵 update chromatic orb

[`326cd46`](https://github.com/Yoonmoonsik/dnd55e/commit/326cd46ea0e4f04d86c410d76da1e19bfba3bdb0) · *yoonmoonsik*
Updated **Chromatic Orb** to reflect the 2024 spell rules. Adjusts damage type selection, damage dice, and higher-slot scaling to match the revised spell entry.

---

### 🔵 update spells

[`75299cb`](https://github.com/Yoonmoonsik/dnd55e/commit/75299cbc501412e540fc87fd0e48e01ae43464df) · *yoonmoonsik*
Additional spell update pass. Addresses remaining spells needing stat corrections to fully align the spell list with the 2024 PHB.

---

### 🔴 fix wildshape(Moon Druid)

[`cf72ad8`](https://github.com/Yoonmoonsik/dnd55e/commit/cf72ad80a1f91544bf8599f24843e4055954b1e7) · *yoonmoonsik*
Fixed **Circle of the Moon Druid** Wild Shape not functioning correctly. Corrected the available form list, temporary HP grant on transformation, and combat Wild Shape action cost to match the 2024 rules.

---

### 🔵 update Natures Wrath

[`6fc2668`](https://github.com/Yoonmoonsik/dnd55e/commit/6fc2668b09cc2e65a4938623cf031ae9a4a04998) · *yoonmoonsik*
Updated **Nature's Wrath** (Oath of the Ancients Paladin Channel Divinity). Adjusts the Restrained condition application and Strength or Dexterity save to match the 2024 spell behavior.

---

### 🔴 fix MagicInitiate

[`65a3da6`](https://github.com/Yoonmoonsik/dnd55e/commit/65a3da6a8c61b87ef1a2b11e8ccd59276c6ec60b) · *yoonmoonsik*
Fixed **Magic Initiate** not granting its spells correctly after a previous update broke the feat assignment logic. Restored proper cantrip and spell granting for all class variants of the feat.

---

### 🔵 update weapons

[`fcc2a1f`](https://github.com/Yoonmoonsik/dnd55e/commit/fcc2a1f2247e333d35e69ac3f57f22f7d09159b7) · *yoonmoonsik*
General weapon update pass. Adjusts damage dice, properties, weight, and Weapon Mastery assignments across multiple weapon entries to align with the 2024 PHB weapon tables.

---

### 🔵 update dance college

[`932bf35`](https://github.com/Yoonmoonsik/dnd55e/commit/932bf35de76924771ffbed5b6fdfbaae78eb8a69) · *yoonmoonsik*
Updated the **College of Dance Bard** subclass with revised feature logic. Adjusts Dazzling Footwork AC bonus, Inspiring Movement reaction, and Irresistible Dance spell integration to match the 2024 subclass design.

---

## March 26, 2026

### 🔵 update zealot path

[`a4558d4`](https://github.com/Yoonmoonsik/dnd55e/commit/a4558d42eeb40ec352ec51f057750f70afc37f20) · *yoonmoonsik*
Updated the **Path of the Zealot Barbarian** subclass to align with the 2024 rules. Adjusts Divine Fury, Warrior of the Gods, Fanatical Focus, and Zealous Presence feature implementations.

---

### 🔵 update World Tree Path

[`7cca01c`](https://github.com/Yoonmoonsik/dnd55e/commit/7cca01c74474bbdf2e26725e4e459b6d1a96a5a6) · *yoonmoonsik*
Updated the **Path of the World Tree Barbarian** subclass with revised feature logic. Adjusts Vitality of the Tree, Branches of the Tree, and Travel Along the Tree feature implementations.

---

### 🟢 update feats

[`9af37cd`](https://github.com/Yoonmoonsik/dnd55e/commit/9af37cd3161dcbbe7adae8a575c786febadfc909) · *yoonmoonsik*
Updated multiple feats with revised passive logic, ASI integrations, and corrected prerequisites to align with the 2024 PHB feat design.

---

### 🟢 update feat sentinel, sharpshooter

[`b4e78a7`](https://github.com/Yoonmoonsik/dnd55e/commit/b4e78a7670dcf4eb6f26567dccb03cea189ad41e) · *yoonmoonsik*
Updated the **Sentinel** and **Sharpshooter** feats to align with the 2024 PHB. Sentinel now grants +1 Strength, Dexterity, or Constitution and revises the opportunity attack reaction. Sharpshooter removes the -5/+10 trade-off and adds ranged weapon die upgrades instead.

---

## March 25, 2026

### 🟢 update multiple feats

[`b7bee65`](https://github.com/Yoonmoonsik/dnd55e/commit/b7bee65ad0baec46f7bffabfbafcc6c9e6a325b4) · *yoonmoonsik*
Broad feat update pass covering several PHB feats. Adds ASI bonuses, revises passive conditions, and aligns prerequisites with the 2024 feat design philosophy.

---

### 🟢 update feat Crossbow Expert, Defensive Duelist, Dual Wielder, Elemental Adept, Great Weapon Master

[`5a166f1`](https://github.com/Yoonmoonsik/dnd55e/commit/5a166f1d38e625224f9ab269e90e530541e52199) · *yoonmoonsik*
Updated **Crossbow Expert**, **Defensive Duelist**, **Dual Wielder**, **Elemental Adept**, and **Great Weapon Master** to align with the 2024 PHB. Each feat now includes an ASI, revised passive logic, and updated combat interactions per the new rules.

---

### 🟢 update feat Athlete, Charger

[`e42a0a1`](https://github.com/Yoonmoonsik/dnd55e/commit/e42a0a1e58bb0d8686032cfae9b6eb95258602fa) · *yoonmoonsik*
Updated the **Athlete** and **Charger** feats to align with the 2024 PHB. Athlete now grants +1 Strength or Dexterity and revises climb/jump movement. Charger adds a Strength or Dexterity ASI and revises the charge attack bonus.

---

### 🔴 fix blooded

[`4aed34d`](https://github.com/Yoonmoonsik/dnd55e/commit/4aed34d0e9d68cc6faaa4852a813fc19fca9ad6e) · *yoonmoonsik*
Fixed the **Blooded** passive or condition not applying correctly. Corrected the trigger logic so the effect activates properly when the character is reduced below half their maximum hit points.

---

### 🔴 fix cleric spelllist

[`c810870`](https://github.com/Yoonmoonsik/dnd55e/commit/c810870c53efbce717c70b4e834aef6e11231492) · *yoonmoonsik*
Fixed the **Cleric** spell list missing or incorrectly assigning spells after a previous update. Restored the full 2024 Cleric spell list ensuring all spells are available at their correct levels.

---

### 🔴 fix magicinitiate

[`a5db0ea`](https://github.com/Yoonmoonsik/dnd55e/commit/a5db0eadf36cf038f6fd2dde26ec4daf82278ecb) · *yoonmoonsik*
Fixed **Magic Initiate** again following additional edge cases discovered after the previous patch. Ensures all class variants of the feat correctly grant their two cantrips and one leveled spell.

---

### 🟢 add AreaRadius for InvokeDuplicity

[`847b4ea`](https://github.com/Yoonmoonsik/dnd55e/commit/847b4eac4c03e62dfe0e513d6666ada53a369b6b) · *yoonmoonsik*
Added a visual area radius indicator to **Invoke Duplicity** (Trickery Cleric Channel Divinity). Players can now see the range within which the duplicate must stay for the Cleric to gain advantage on attack rolls.

---

### ⚪ change hide stealth check dc

[`56d91a6`](https://github.com/Yoonmoonsik/dnd55e/commit/56d91a69a69e3f371a62ec2cf45576124e4edc40) · *yoonmoonsik*
Adjusted the DC for **Hide** stealth checks. A balance change to bring the detection difficulty more in line with the 2024 rules and the expected challenge rating of encounters.

---

### 🟢 update background and origin feats

[`c298fcf`](https://github.com/Yoonmoonsik/dnd55e/commit/c298fcf09b155f0052af094c4b47179679a8ea6f) · *yoonmoonsik*
Updated all character backgrounds to grant their correct **Origin Feat** as per the 2024 PHB. Each background now properly awards its associated feat at character creation alongside skill proficiencies and starting equipment.

---

### 🟢 update origin feat skilled

[`970320e`](https://github.com/Yoonmoonsik/dnd55e/commit/970320e8e523b0d1aa4ec7a4d343bc58a23c9356) · *yoonmoonsik*
Updated the **Skilled** Origin Feat to align with the 2024 PHB. The feat now grants proficiency in any combination of three skills or tools, properly implemented as a selection dialog at character creation.

---

### 🔵 update magic initiate cleric, druid, wizard

[`65978a4`](https://github.com/Yoonmoonsik/dnd55e/commit/65978a4255f2ca8054fae58500d26c4c40a59f97) · *yoonmoonsik*
Updated the **Magic Initiate** feat for the Cleric, Druid, and Wizard variants. Ensures each version correctly grants two cantrips and one level 1 spell from the chosen class list, with the 2024 rule that the spell can be cast once per long rest for free.

---

### 🔵 update cunning strike

[`5b11eff`](https://github.com/Yoonmoonsik/dnd55e/commit/5b11eff4373703558514d05d548ac0e63845253f) · *yoonmoonsik*
Updated **Cunning Strike** (Rogue level 5 feature) to align with the 2024 rules. Implements the option to forgo some Sneak Attack dice to apply a Cunning Strike effect — Poison, Trip, Withdraw, or Disarm — on a hit.

---

## March 24, 2026

### 🔵 update readme

[`7863950`](https://github.com/Yoonmoonsik/dnd55e/commit/7863950fb59c164ae1246d544a7c79eaaf462510) · *yoonmoonsik*
Updated the README with current feature documentation, supported content lists, and installation guidance reflecting the latest mod state.

---

### 🔵 update truestrike, warlock invocations

[`2b39c48`](https://github.com/Yoonmoonsik/dnd55e/commit/2b39c4888b913d5cb3a3c7f0820739546b6cbf87) · *yoonmoonsik*
Updated **True Strike** and the **Warlock Eldritch Invocation** list. True Strike is revised to function as a 2024 melee spell attack cantrip, and invocations are updated with corrected prerequisites and effect conditions.

---

### 🔵 update warmagic, boomingblade, warlock cantrip etc

[`3f1dd66`](https://github.com/Yoonmoonsik/dnd55e/commit/3f1dd66857dd05595ed32231bb941e6b26767a58) · *yoonmoonsik*
Updated **War Magic**, **Booming Blade**, and several Warlock cantrips. Booming Blade now applies its thunder damage condition on movement. War Magic revises the Arcane Deflection and Tactical Wit features per the 2024 rules.

---

### 🟢 add mind sliver cantrip

[`66ed251`](https://github.com/Yoonmoonsik/dnd55e/commit/66ed251e981cb073b7573dd98436b9b738abfb81) · *yoonmoonsik*
Added the **Mind Sliver** cantrip to the mod. Implements the psychic damage Intelligence save cantrip that subtracts 1d4 from the target's next saving throw, available to Sorcerers, Warlocks, and Wizards.

---

### 🔵 update warlock invocation list

[`0f63458`](https://github.com/Yoonmoonsik/dnd55e/commit/0f63458d8c42390d3150d1acfbdc02861734083d) · *yoonmoonsik*
Updated the full **Warlock Eldritch Invocation** list to align with the 2024 PHB. Revises invocation prerequisites, effects, and adds newly introduced invocations from the updated Warlock class design.

---

### 🔵 update wizard spell list

[`9c324d1`](https://github.com/Yoonmoonsik/dnd55e/commit/9c324d144e82c907dd66d1a062cf8d6dc6455ec7) · *yoonmoonsik*
Updated the **Wizard** spell list to align with the 2024 PHB. Ensures all spells are available at the correct levels and that newly added or revised spells are properly included in the Wizard's expanded list.

---

## March 23, 2026

### 🔵 update Arcane vigor icon

[`503324b`](https://github.com/Yoonmoonsik/dnd55e/commit/503324b809e5f16e787c9eb020bde6c085f1bfbf) · *yoonmoonsik*
Updated the icon for **Arcane Vigor** (Wizard level 2 feature). Replaces a placeholder or incorrect icon with the correct visual representation for the ability.

---

### 🔵 update warlock spell list

[`d1f8ac0`](https://github.com/Yoonmoonsik/dnd55e/commit/d1f8ac0462a7c309e0d4a8dfece0840027dafab5) · *yoonmoonsik*
Updated the **Warlock** spell list to align with the 2024 PHB. Ensures all spells are available at the correct Pact Magic slot levels and that the revised Warlock spell selection reflects the new class design.

---

### 🔵 update sorcerer and sorcerer spell list

[`098318b`](https://github.com/Yoonmoonsik/dnd55e/commit/098318b38f5c13e993202260847e7fb6f8f9cae3) · *yoonmoonsik*
Updated the **Sorcerer** base class and its full spell list to align with the 2024 PHB. Revisions include the Innate Sorcery feature, Font of Magic improvements, and the expanded spell list available to Sorcerers.

---

### 🔵 update paladin starting equipment

[`3979d68`](https://github.com/Yoonmoonsik/dnd55e/commit/3979d68c4aa278ac1a2b32db12c0e33098f5e03d) · *yoonmoonsik*
Updated **Paladin** starting equipment to match the 2024 PHB package. Corrects the equipment choices offered at character creation to reflect the holy warrior's revised gear options.

---

### 🟢 update rogue and subclasses

[`5b79654`](https://github.com/Yoonmoonsik/dnd55e/commit/5b79654cca901ad2bb7fdda6bf5ecaced073bff3) · *yoonmoonsik*
Updated the **Rogue** base class and all subclasses to align with the 2024 PHB. Revisions cover Cunning Action, Uncanny Dodge, Evasion, and the full subclass feature implementations for Thief, Arcane Trickster, Assassin, and Soulknife.

---

### 🟢 update ranger subclasses

[`3f2704a`](https://github.com/Yoonmoonsik/dnd55e/commit/3f2704a63ccebb501c3c1c7fda2e46903e5664a2) · *yoonmoonsik*
Updated all **Ranger** subclasses to align with the 2024 PHB. Revisions cover Hunter, Beast Master, Gloom Stalker, and Fey Wanderer feature implementations and expanded spell list assignments.

---

### 🔵 update ranger and spelllist

[`b7d6f00`](https://github.com/Yoonmoonsik/dnd55e/commit/b7d6f008698a1e331efbf4dc983b6a76bbc50663) · *yoonmoonsik*
Updated the **Ranger** base class and its spell list to align with the 2024 PHB. Revisions cover Favored Enemy, Deft Explorer, Tireless, Feral Senses, and the updated Ranger spell list.

---

## March 22, 2026

### 🟢 update paladin and subclasses

[`a22d8c2`](https://github.com/Yoonmoonsik/dnd55e/commit/a22d8c273282de73c56747bc41fb926a3d66aab7) · *yoonmoonsik*
Updated the **Paladin** base class and all subclasses to align with the 2024 PHB. Revisions include Lay on Hands, Divine Smite (now a reaction), Channel Divinity, Auras, and full subclass implementations for all Oath options.

---

### 🟢 add spellset

[`6072b93`](https://github.com/Yoonmoonsik/dnd55e/commit/6072b93378400608344c365ad4deabad148eac78) · *yoonmoonsik*
Added a new spell set grouping. Organizes spells into logical sets for use by class progression tables, ensuring spells are unlocked at the correct levels for the relevant classes.

---

### 🔵 update heavy weapon ability requirement

[`5ca54a2`](https://github.com/Yoonmoonsik/dnd55e/commit/5ca54a2c3a259da483e18bc3c217ecc82660bf16) · *yoonmoonsik*
Updated the **Heavy** weapon property to enforce the 2024 Strength requirement. Characters without a Strength score of 13 or higher now suffer disadvantage on attack rolls with Heavy weapons, as per the revised rules.

---

### 🔵 update openhand monk

[`3d1dd83`](https://github.com/Yoonmoonsik/dnd55e/commit/3d1dd836bda50b47b98a9d300a281399426c2543) · *yoonmoonsik*
Updated the **Way of the Open Hand Monk** subclass to align with the 2024 PHB. Adjusts Open Hand Technique, Wholeness of Body, Fleet Step, and Quivering Palm feature implementations.

---

### 🔵 update element monk

[`34bd698`](https://github.com/Yoonmoonsik/dnd55e/commit/34bd6981f303cde289f218d4fd9335255b615849) · *yoonmoonsik*
Updated the **Way of the Four Elements Monk** subclass to align with the 2024 PHB. Revises the elemental discipline system with the new Elemental Attunement cantrip and discipline selection framework.

---

### 🔵 update element monk vfx and update icons

[`5ec9dd2`](https://github.com/Yoonmoonsik/dnd55e/commit/5ec9dd27aaf52cbb9a6fdaa54cee30489f38d3f1) · *yoonmoonsik*
Updated visual effects and icons for the **Way of the Four Elements Monk** disciplines. Ensures each elemental ability has an appropriate VFX and icon distinguishing fire, water, earth, and air disciplines in the UI.

---

### 🔵 update monk

[`47abb39`](https://github.com/Yoonmoonsik/dnd55e/commit/47abb39f98bc2f38d3bbd5037987aa9e78396f6e) · *yoonmoonsik*
Updated the **Monk** base class to align with the 2024 PHB. Revisions cover Martial Arts die scaling, Ki point usage, Stunning Strike, Deflect Missiles, and the revised Step of the Wind and Patient Defense action economy.

---

## March 21, 2026

### 🔵 update monk (part)

[`c52cdc3`](https://github.com/Yoonmoonsik/dnd55e/commit/c52cdc30d3ebfd9f4d88f26da4bcb4b54e8d804a) · *yoonmoonsik*
Partial update to the **Monk** class covering the lower-level feature implementations. Adjusts Unarmored Defense, Martial Arts unarmed strikes, and the early Ki ability triggers as part of the phased Monk overhaul.

---

### 🔵 update battle master

[`7065300`](https://github.com/Yoonmoonsik/dnd55e/commit/70653006e0835f31310f485f9a9bcb481708a271) · *yoonmoonsik*
Updated the **Battle Master Fighter** subclass to align with the 2024 PHB. Revisions cover Superiority Die scaling, Combat Superiority, Know Your Enemy, and the full Maneuver list with corrected save DCs and effect conditions.

---

### ⚪ change icon name

[`2082fcc`](https://github.com/Yoonmoonsik/dnd55e/commit/2082fcc83a6e67cf602360eb3fe36e1a590c0df8) · *yoonmoonsik*
Renamed an internal icon file to match the updated naming convention. A cosmetic/structural change with no gameplay impact.

---

### 🔵 update readme

[`4faf61e`](https://github.com/Yoonmoonsik/dnd55e/commit/4faf61e201199eb9495fadfa48041688f932104c) · *yoonmoonsik*
Updated the README with documentation for the Monk and Fighter class updates, reflecting the current supported content.

---

### 🔵 update Eldritch Knight

[`c3f6fe6`](https://github.com/Yoonmoonsik/dnd55e/commit/c3f6fe608643d1db8c5d7a67ca11484ccff675ec) · *yoonmoonsik*
Updated the **Eldritch Knight Fighter** subclass to align with the 2024 PHB. Adjusts Spellcasting, Weapon Bond, War Magic, Eldritch Strike, and Arcane Charge feature implementations.

---

### 🔵 update Champion

[`9e0f89a`](https://github.com/Yoonmoonsik/dnd55e/commit/9e0f89a1e07954e58519bea8d8081a6048e5d61d) · *yoonmoonsik*
Updated the **Champion Fighter** subclass to align with the 2024 PHB. Adjusts Improved Critical (now critting on 19-20 from level 3), Remarkable Athlete, Additional Fighting Style, and Heroic Warrior feature implementations.

---

### ⚪ Heavy Armor Strength Requirement

[`8fd6d87`](https://github.com/Yoonmoonsik/dnd55e/commit/8fd6d87b83a32d023174dac1904622270c1895a3) · *yoonmoonsik*
Implemented the **Heavy Armor Strength Requirement** system. Characters without the minimum Strength score for their armor type now properly suffer a speed penalty, as per the 2024 PHB armor rules.

---

### 🔵 update readme

[`babe5a0`](https://github.com/Yoonmoonsik/dnd55e/commit/babe5a0c1251460fee3cea23c53313f4e1623734) · *yoonmoonsik*
Updated the README to reflect the latest Fighter and armor rule implementations.

---

### 🟢 update fighter base class

[`a0fab9a`](https://github.com/Yoonmoonsik/dnd55e/commit/a0fab9a831f0dce05b2eb8cb95550d054613bbab) · *yoonmoonsik*
Updated the **Fighter** base class to align with the 2024 PHB. Revisions cover Second Wind improvements, Action Surge, Indomitable, Extra Attack scaling, and the revised Tactical Mind and Studied Attacks features.

---

### 🟢 update druid and subclasses

[`7b23161`](https://github.com/Yoonmoonsik/dnd55e/commit/7b2316118bf8ba477cc5446c6bd9f7aaffba26d5) · *yoonmoonsik*
Updated the **Druid** base class and all subclasses to align with the 2024 PHB. Revisions cover the Wild Shape revamp, Primal Order, Elemental Fury, and full feature implementations for all Circle subclasses.

---

### 🟢 update druid primal order feature

[`0c08aed`](https://github.com/Yoonmoonsik/dnd55e/commit/0c08aeda47d2be90dd7d13bcbab624e9f9110467) · *yoonmoonsik*
Updated the **Druid Primal Order** level 2 feature. Correctly implements the Magician option (Druidic cantrip + language) and the Warden option (martial weapons + medium armor proficiency) as a choice at character creation.

---

### 🟢 add new spell and update druid spell list

[`5dffbac`](https://github.com/Yoonmoonsik/dnd55e/commit/5dffbac21aa1dd013028ef012b571bfc9e4f8bc7) · *yoonmoonsik*
Added one or more new spells and updated the **Druid** spell list to include all spells available in the 2024 PHB. Ensures Druids have access to newly added nature and summoning spells at the correct levels.

---

### 🔵 update knowledge domain

[`41d2671`](https://github.com/Yoonmoonsik/dnd55e/commit/41d2671f3ea777f89f71a99799947e9cf5fe32bd) · *yoonmoonsik*
Updated the **Knowledge Domain Cleric** subclass to align with the 2024 PHB. Adjusts Blessings of Knowledge, Channel Divinity: Knowledge of the Ages, Read Thoughts, and Mind over Matter feature implementations.

---

### 🟢 add readme

[`53ce77f`](https://github.com/Yoonmoonsik/dnd55e/commit/53ce77f3d09cb71e9ef7a94f1ac5d60ee061965c) · *yoonmoonsik*
Added the initial repository README. Provides the first public documentation for the mod including feature overview, installation instructions, and supported content.

---

## March 20, 2026

### 🟢 add new spell steel wind strike

[`1f604bd`](https://github.com/Yoonmoonsik/dnd55e/commit/1f604bd71c44afb1f77423e24cc1fc7a411c9620) · *yoonmoonsik*
Added the **Steel Wind Strike** spell. Implements the 5th-level conjuration spell that allows the caster to make melee spell attacks against up to five targets, then teleport to one of them.

---

### 🔵 update war domain

[`7b2ab11`](https://github.com/Yoonmoonsik/dnd55e/commit/7b2ab1151aad55188a1735eae739755081855a6b) · *yoonmoonsik*
Updated the **War Domain Cleric** subclass to align with the 2024 PHB. Adjusts War Priest bonus attack uses, Channel Divinity: Guided Strike and War God's Blessing, Avatar of Battle, and the domain spell list.

---

### 🟢 add war domain progression table

[`325f909`](https://github.com/Yoonmoonsik/dnd55e/commit/325f909c08077f0ea03b593f32a221b7fb912224) · *yoonmoonsik*
Added the progression table for the **War Domain Cleric** subclass. Required structural entry that defines when each War Domain feature is unlocked across the 20 Cleric levels.

---

### 🔵 update trickery domain

[`99a3639`](https://github.com/Yoonmoonsik/dnd55e/commit/99a3639e79e4bf31831f15508e60b889e142295a) · *yoonmoonsik*
Updated the **Trickery Domain Cleric** subclass to align with the 2024 PHB. Adjusts Blessing of the Trickster, Channel Divinity: Invoke Duplicity and Cloak of Shadows, Divine Strike, and domain spell list.

---

### ⚪ stop tracking files

[`7560be8`](https://github.com/Yoonmoonsik/dnd55e/commit/7560be8326725e3818185946f5c7576fcba73d54) · *yoonmoonsik*
Stopped tracking generated or binary files that were previously committed. A repository maintenance change with no gameplay impact.

---

### 🔵 update gitignore

[`e06e391`](https://github.com/Yoonmoonsik/dnd55e/commit/e06e391ccf78749469f35609598a2c4dfc5789a6) · *yoonmoonsik*
Updated `.gitignore` to exclude additional generated data files. Keeps the repository clean by preventing auto-generated stat output files from being committed.

---

### 🔵 update radiance of the dawn

[`5eabeba`](https://github.com/Yoonmoonsik/dnd55e/commit/5eabeba503e7b7ad220d960140afeec387e056aa) · *yoonmoonsik*
Updated **Radiance of the Dawn** (Light Domain Cleric Channel Divinity). Adjusts the radiant damage dealt to hostile creatures in range and the Darkness dispel effect to match the 2024 feature behavior.

---

### 🔵 update channel divinity shortrest restore

[`3ec36ca`](https://github.com/Yoonmoonsik/dnd55e/commit/3ec36cac3968e325e21b173a28498abaadbc6a6c) · *yoonmoonsik*
Updated the **Channel Divinity** short rest restore mechanic. Implements the 2024 rule that Clerics regain one expended Channel Divinity use on a Short Rest, adjusting the resource recovery logic accordingly.

---

### 🔵 update light cleric spelllist

[`b1f220f`](https://github.com/Yoonmoonsik/dnd55e/commit/b1f220f46a19cbc25f665acfad3af239141a8763) · *yoonmoonsik*
Updated the **Light Domain Cleric** expanded spell list. Ensures all light and fire-themed domain spells are properly granted at each tier as per the 2024 PHB domain design.

---

### 🔵 update channeldivinity uses

[`37af925`](https://github.com/Yoonmoonsik/dnd55e/commit/37af925fb64def709e3643bb21b1d1aebbc8ba8c) · *yoonmoonsik*
Updated the number of **Channel Divinity** uses per rest for all Cleric subclasses. Aligns the charge count and restoration conditions with the 2024 PHB Channel Divinity rules across all domains.

---

### 🔵 update life cleric

[`61e10c0`](https://github.com/Yoonmoonsik/dnd55e/commit/61e10c0b3d3eb325e5590985ee7c28c97a7e55a1) · *yoonmoonsik*
Updated the **Life Domain Cleric** subclass to align with the 2024 PHB. Adjusts Disciple of Life healing bonus, Preserve Life Channel Divinity, Blessed Healer, and Supreme Healing feature implementations.

---

### 🔵 update cleric spelllist

[`8f115f1`](https://github.com/Yoonmoonsik/dnd55e/commit/8f115f163b95a7fa1ef07866b9eef60afd8dba72) · *yoonmoonsik*
Updated the **Cleric** base spell list to align with the 2024 PHB. Ensures all divine spells are available at their correct levels and that the revised Cleric spell access rules are properly implemented.

---

### 🔵 update gitignore

[`6bf669e`](https://github.com/Yoonmoonsik/dnd55e/commit/6bf669e8cb5aca03ddecca805e3d4700d8977ca5) · *yoonmoonsik*
Updated `.gitignore` with additional file exclusions. A repository maintenance change with no gameplay impact.

---

### 🔵 update cleric

[`10cfe90`](https://github.com/Yoonmoonsik/dnd55e/commit/10cfe908a00aed1be6a45a3ae7b0f135ede1446f) · *yoonmoonsik*
Updated the **Cleric** base class to align with the 2024 PHB. Revisions cover Divine Order, Spellcasting preparation rules, Channel Divinity improvements, Divine Intervention, and the revised class feature progression.

---

### 🔵 update gitignore

[`8a21921`](https://github.com/Yoonmoonsik/dnd55e/commit/8a21921778b4fa6310dc32a789bed283f83630e8) · *yoonmoonsik*
Updated `.gitignore` with further file exclusion rules. A repository maintenance change with no gameplay impact.

---

### 🟢 update Bard and bard subclasses

[`65f6a5c`](https://github.com/Yoonmoonsik/dnd55e/commit/65f6a5c9a6f13fc90dde5070b716d836dddfee0d) · *yoonmoonsik*
Updated the **Bard** base class and all subclasses to align with the 2024 PHB. Revisions include the Bardic Inspiration Bonus Action grant, Jack of All Trades improvements, and full subclass implementations for Lore, Valor, Swords, Glamour, Whispers, Dance, and Moon colleges.

---

## March 19, 2026

### 🔵 update BerserkerPath, GiantPath, TotemWarriorPath, WildMagicPath

[`d14ae2b`](https://github.com/Yoonmoonsik/dnd55e/commit/d14ae2b3237bb705fa58f8f13597a42148e1c484) · *yoonmoonsik*
Updated **Path of the Berserker**, **Path of the Giant**, **Path of the Totem Warrior**, and **Path of Wild Magic** Barbarian subclasses to align with the 2024 PHB. Adjusts Frenzy, Giant's Might, Totemic Attunement, and Wild Magic Surge feature implementations.

---

### ⚪ set rage duration

[`96b8e62`](https://github.com/Yoonmoonsik/dnd55e/commit/96b8e62010950e2eedd83adf79faf95f46fa11b8) · *yoonmoonsik*
Set the **Barbarian Rage** duration to 1 minute (10 rounds) as per the 2024 PHB. Corrects the status duration entry so rage automatically ends after the correct number of rounds in combat.

---

### 🔵 update barbarian progression table

[`a943d1e`](https://github.com/Yoonmoonsik/dnd55e/commit/a943d1e1d16fb64f2f8453aa7ed871c868d5aede) · *yoonmoonsik*
Updated the **Barbarian** class progression table. Corrects the level-by-level unlocking of features, Rage uses, Rage damage bonus, and Brutal Strike improvements to match the 2024 PHB Barbarian table.

---

### 🟢 feat: update Barbarian Rage description and add new RageRestore passive

[`2e11634`](https://github.com/Yoonmoonsik/dnd55e/commit/2e11634b1b9dbf2eba0494094d684fe329adfc40) · *yoonmoonsik*
Updated the **Rage** description to reflect the 2024 rules and added a new **RageRestore** passive. The passive implements the 2024 rule that Barbarians regain one Rage use when they finish a Short Rest (at higher levels).

---

### 🟢 Add new Barbarian abilities and status effects

[`adeecba`](https://github.com/Yoonmoonsik/dnd55e/commit/adeecba68e3daac57120720e44cbded09ef298f8) · *yoonmoonsik*
Added new Barbarian abilities and status effects required for the 2024 class rework. Includes entries for Brutal Strike, Relentless Rage, and updated Rage status logic.

---

### 🟢 feat: add additional resource files to .gitignore

[`01cb914`](https://github.com/Yoonmoonsik/dnd55e/commit/01cb91411b69295d6668cf9de0080a9ae8f13e94) · *yoonmoonsik*
Expanded `.gitignore` to cover additional generated resource files. A repository maintenance change to prevent unintended file tracking.

---

### 🟢 feat: add weapon names to localization for various weapon types

[`55fe1d0`](https://github.com/Yoonmoonsik/dnd55e/commit/55fe1d008364401494bc19ec55b103aa186059d1) · *yoonmoonsik*
Added localization entries for weapon names across multiple weapon categories. Ensures all weapons added or revised by the mod display their correct names in the inventory and tooltip UI.

---

### 🟢 feat: enhance weapon mastery passives with new conditions and properties

[`30c4a91`](https://github.com/Yoonmoonsik/dnd55e/commit/30c4a91d91f1e0cbaaf099c513a8b5e8608b4f4c) · *yoonmoonsik*
Enhanced **Weapon Mastery** passives with additional trigger conditions and property flags. Improves the reliability and accuracy of all mastery effects during combat interactions.

---

### 🟢 feat: add WeaponMasterySap passive to PassivesOnEquip for specific weapons

[`897dfd8`](https://github.com/Yoonmoonsik/dnd55e/commit/897dfd8d5fb8b4624ab0d48978ca80986234de2d) · *yoonmoonsik*
Assigned the **Sap** Weapon Mastery passive to the `PassivesOnEquip` field for all eligible weapons. Allows characters with the Sap mastery to impose disadvantage on the target's next attack after a hit.

---

### 🟢 feat: clear RemoveEvents value for specific status effects in Status_BOOST

[`61f118a`](https://github.com/Yoonmoonsik/dnd55e/commit/61f118ad083f9c2a951ba78a011e85ed75abcafd) · *yoonmoonsik*
Cleared incorrect `RemoveEvents` values on specific status boost entries. Prevents certain weapon mastery and combat status effects from being prematurely removed by unintended game events.

---

### 🟢 feat: update PassivesOffHand fields to include WeaponMasteryNick passives

[`58b001f`](https://github.com/Yoonmoonsik/dnd55e/commit/58b001f723f099af61694b5d1b775524fb0b186f) · *yoonmoonsik*
Updated `PassivesOffHand` fields for Light weapons to include the **Nick** Weapon Mastery passive. Enables the Nick property to properly grant an extra off-hand attack as part of the Attack action for eligible weapons.

---

### 🟢 feat: add WeaponMasteryNick passives and localization entries for off-hand attacks

[`337891f`](https://github.com/Yoonmoonsik/dnd55e/commit/337891fe772744609dd65cd649622daa44c41c57) · *yoonmoonsik*
Added the **Nick** Weapon Mastery passive and its localization entries. Implements the Nick property that allows one off-hand attack as part of the Attack action (not requiring a Bonus Action) with Light weapons.

---

### 🟢 feat: add WeaponMasteryVex passive to PassivesOnEquip for various weapons

[`e1c6764`](https://github.com/Yoonmoonsik/dnd55e/commit/e1c676427598aaca40b37a38666f2db65c33fd3e) · *yoonmoonsik*
Assigned the **Vex** Weapon Mastery passive to eligible weapons. Enables the Vex property to grant advantage on the attacker's next attack roll against the same target after a hit.

---

### 🟢 feat: add WeaponMasteryVex passive and localization entries for weapon mastery effects

[`a7682ed`](https://github.com/Yoonmoonsik/dnd55e/commit/a7682ed8e3a4db94c173decf43106c2db762c42c) · *yoonmoonsik*
Added the **Vex** Weapon Mastery passive definition and localization entries. Implements the passive trigger and tooltip description for the Vex property across all eligible weapon types.

---

### 🟢 feat: add WeaponMasteryTopple passive to PassivesOnEquip for various weapons

[`1d4d22b`](https://github.com/Yoonmoonsik/dnd55e/commit/1d4d22bf4e7cb28565cc9797d89d5a7397388221) · *yoonmoonsik*
Assigned the **Topple** Weapon Mastery passive to eligible weapons. Enables the Topple property to force a Constitution save after a hit, knocking the target prone on a failure.

---

### 🟢 feat: add WeaponMasteryTopple passive and localization entries for weapon mastery effects

[`f706059`](https://github.com/Yoonmoonsik/dnd55e/commit/f7060591efae6ce37f8d54ba01670edc6aca2efd) · *yoonmoonsik*
Added the **Topple** Weapon Mastery passive definition and localization entries. Implements the passive trigger and UI description for the Topple property.

---

### 🟢 feat: add WeaponMasterySlow passive to PassivesOnEquip fields for various weapons

[`2b616de`](https://github.com/Yoonmoonsik/dnd55e/commit/2b616de006d9d8ca67e1076700d9d0caa1b0843a) · *yoonmoonsik*
Assigned the **Slow** Weapon Mastery passive to eligible weapons. Enables the Slow property to reduce the target's Speed by 10 feet until the start of your next turn after a hit.

---

### 🟢 feat: add WeaponMasterySlow passive and localization entries for weapon mastery effects

[`9be24da`](https://github.com/Yoonmoonsik/dnd55e/commit/9be24da6b701545ddca465b95c720beafb445429) · *yoonmoonsik*
Added the **Slow** Weapon Mastery passive definition and localization entries. Implements the passive trigger and tooltip description for the Slow property across all eligible weapon types.

---

### 🟢 feat: update Trident damage values and enhance versatile damage type

[`bc64c36`](https://github.com/Yoonmoonsik/dnd55e/commit/bc64c366809db5a1ea77118a4d8fb379644566da) · *yoonmoonsik*
Updated **Trident** damage values to match the 2024 PHB. Corrects its Versatile damage die from d8 to d10 when wielded with two hands, and assigns the appropriate Weapon Mastery property.

---

### 🟢 feat: update weapon properties to include 'Versatile' for various weapon definitions

[`6045eef`](https://github.com/Yoonmoonsik/dnd55e/commit/6045eefb7d86b7d3fdc58c2654a766b9d243b874) · *yoonmoonsik*
Added the **Versatile** property to all eligible weapons that were missing it. Ensures these weapons properly offer a two-handed damage die option as defined in the 2024 PHB weapon tables.

---

### 🟢 feat: add WeaponMasterySap passive to PassivesOnEquip fields in weapon definitions

[`c761cec`](https://github.com/Yoonmoonsik/dnd55e/commit/c761cec209db8e34aa8bbd4486bdd5b88bf53569) · *yoonmoonsik*
Assigned the **Sap** Weapon Mastery passive to the `PassivesOnEquip` fields for additional weapon definitions. Expands Sap mastery coverage to all eligible weapon entries.

---

### 🟢 feat: add WeaponMasterySap passive and localization entries to weapon definitions

[`3b32a09`](https://github.com/Yoonmoonsik/dnd55e/commit/3b32a09b9897547f05eecf88cd0a4a750d567a50) · *yoonmoonsik*
Added the **Sap** Weapon Mastery passive definition and localization entries. Implements the passive trigger and tooltip description for the Sap property across all eligible weapon types.

---

### 🟢 feat: update conditions for WeaponMasteryCleave passives to enhance attack logic

[`169b48e`](https://github.com/Yoonmoonsik/dnd55e/commit/169b48edd46fdd8e72c6fd1d21e9d0389d1d061e) · *yoonmoonsik*
Refined the trigger conditions for **Cleave** Weapon Mastery passives. Ensures the Cleave property only activates when the attack hits and the secondary target is within the correct reach, preventing unintended activations.

---

### 🟢 feat: add WeaponMasteryPush passive to PassivesOnEquip fields in weapon definitions

[`f25e415`](https://github.com/Yoonmoonsik/dnd55e/commit/f25e415aa5a725ff4e62dd32aea6547c198d0a64) · *yoonmoonsik*
Assigned the **Push** Weapon Mastery passive to the `PassivesOnEquip` fields for all eligible weapons. Enables the Push property to force the target back 10 feet after a hit.

---

### 🟢 feat: add WeaponMasteryPush passive and localization entries to weapon definitions

[`1a07a72`](https://github.com/Yoonmoonsik/dnd55e/commit/1a07a721216b7cd66aae339f5015f71f5be8335b) · *yoonmoonsik*
Added the **Push** Weapon Mastery passive definition and localization entries. Implements the passive trigger and tooltip for the Push property across all eligible weapon types.

---

### 🟢 feat: add WeaponMasteryGraze passive to PassivesOnEquip fields in weapon definitions

[`bdf713b`](https://github.com/Yoonmoonsik/dnd55e/commit/bdf713b9c0d324475d93aae9892050ae2f7b5909) · *yoonmoonsik*
Assigned the **Graze** Weapon Mastery passive to the `PassivesOnEquip` fields for eligible weapons. Enables the Graze property to deal the ability modifier in damage even on a missed attack roll.

---

### 🟢 feat: add WeaponMasteryGraze passive and localization entries

[`240c7d3`](https://github.com/Yoonmoonsik/dnd55e/commit/240c7d3d4b2b52b866707cfaf8455306dbe4e4c0) · *yoonmoonsik*
Added the **Graze** Weapon Mastery passive definition and localization entries. Implements the passive trigger and tooltip for the Graze property — unique among masteries for dealing damage even on a miss.

---

### 🟢 feat: add WeaponMasteryCleave passives to various weapon definitions

[`352c210`](https://github.com/Yoonmoonsik/dnd55e/commit/352c2102b18b3614d87e5494add9becb3f95a8bb) · *yoonmoonsik*
Assigned the **Cleave** Weapon Mastery passive to all eligible weapon definitions. Enables the Cleave property to automatically hit a second adjacent creature with the ability modifier in damage after a successful attack.

---

### 🟢 feat: add Weapon Mastery Cleave properties and localization entries

[`a468847`](https://github.com/Yoonmoonsik/dnd55e/commit/a46884755c5931b44b5f19c4e935dd71f789e8f7) · *yoonmoonsik*
Added the **Cleave** Weapon Mastery passive definition and full localization entries. Implements the core passive trigger and UI description for Cleave across all eligible heavy weapon types.

---

### 🟢 feat: remove BoostsOnEquipMainHand field from multiple weapon definitions

[`2ba9c0b`](https://github.com/Yoonmoonsik/dnd55e/commit/2ba9c0b19caee20bd00792a5b614793bc78963c6) · *yoonmoonsik*
Removed the deprecated `BoostsOnEquipMainHand` field from multiple weapon entries. Replaces the old boost system with the new Weapon Mastery passive framework to avoid conflicts and double-triggering.

---

### 🟢 Implement feature X to enhance user experience and optimize performance

[`779c084`](https://github.com/Yoonmoonsik/dnd55e/commit/779c084796e0098556b280db9fccc747797cf957) · *yoonmoonsik*
Internal framework improvement to the mod's passive and boost system. Optimizes how weapon and class passives are evaluated during combat to reduce conflicts and improve performance.

---

### 🟢 feat: add Weapon and Spell_Zone data files to .gitignore

[`a42fecf`](https://github.com/Yoonmoonsik/dnd55e/commit/a42fecf13068e10a0a1b1a66010d5e56d37bc8a9) · *yoonmoonsik*
Updated `.gitignore` to exclude Weapon and Spell_Zone generated data files. Keeps auto-generated output from cluttering the repository's commit history.

---

### 🟢 feat: enhance Shove spell with additional properties and effects; add ShoveUnarmedAttack definition

[`e486ebb`](https://github.com/Yoonmoonsik/dnd55e/commit/e486ebbd5b418f912755c1e520a4cfa906edacfd) · *yoonmoonsik*
Enhanced the **Shove** action with additional properties and a new `ShoveUnarmedAttack` variant. Implements the 2024 rule that Shove can be performed as part of an Unarmed Strike, allowing characters to knock targets prone or push them 5 feet away.

---

### 🟢 feat: add Shove and related spell definitions to Target.stats; update RemoveEvents in Status_KNOCKED_DOWN.stats

[`f0ab6b0`](https://github.com/Yoonmoonsik/dnd55e/commit/f0ab6b0cb499036cea7eed6e91ffedf0cf65dc2d) · *yoonmoonsik*
Added full Shove spell definitions to `Target.stats` and updated the `KNOCKED_DOWN` status `RemoveEvents`. Ensures the prone condition applied by Shove is properly removed when the target stands up or the condition ends.

---

### 🟢 feat: add One Spell with a Spell Slot per Turn rule and related localization entries

[`9e98a9e`](https://github.com/Yoonmoonsik/dnd55e/commit/9e98a9eb937a4d4c2188da95437ed162f716b7be) · *yoonmoonsik*
Implemented the 2024 rule that only **one spell with a spell slot** can be cast per turn (the "one leveled spell per turn" restriction). Adds the passive tracker and localization entries that enforce and communicate this limitation to players.

---

## March 18, 2026

### 🟢 feat: add Throw spell data and update .gitignore to include Spell_Throw.txt

[`613238a`](https://github.com/Yoonmoonsik/dnd55e/commit/613238a7b7d389d8483c1e3bfb4b77531f4e4940) · *yoonmoonsik*
Added **Throw** action spell data implementing the 2024 rules for throwing weapons and improvised objects. Characters can now throw weapons with the Thrown property using their normal attack bonus and damage values.

---

### 🟢 feat: add Data.stats file for InitiativeDie definition

[`21d8c12`](https://github.com/Yoonmoonsik/dnd55e/commit/21d8c12a6c8da4c004c6af3ff818fd717166ad7c) · *yoonmoonsik*
Added the `InitiativeDie` definition to `Data.stats`. Implements the 2024 rule that Initiative is rolled with a d20 + Dexterity modifier (removing the flat modifier system used in earlier editions).

---

### 🟢 feat: add KNOCKED_DOWN status definition and localization entries

[`f2b1e28`](https://github.com/Yoonmoonsik/dnd55e/commit/f2b1e28d84c2bbd3ff3ed2d38c1247c521a63412) · *yoonmoonsik*
Added the **Knocked Down** (Prone) status definition and its localization entries. Implements the prone condition with correct movement cost to stand, attack roll penalties, and melee/ranged attack advantage/disadvantage rules.

---

### 🟢 feat: add SpellProperties field to HelpAction for status removal and healing

[`c5b12df`](https://github.com/Yoonmoonsik/dnd55e/commit/c5b12dfc47e749fa9ad79eff8f758ff750f4d473) · *yoonmoonsik*
Updated the **Help** action to include spell properties for status removal and minor healing. Implements the 2024 rule that the Help action can be used to assist an incapacitated ally, giving them the Prone status removal and 1 HP.

---

### 🟢 feat: add DOWNED status definition and related localization entries

[`4401282`](https://github.com/Yoonmoonsik/dnd55e/commit/44012821eb6644876af6e472ca72a1a7ea9fba37) · *yoonmoonsik*
Added the **Downed** status definition and localization entries. Implements the 2024 rules for the Downed condition (0 HP) including death saving throws, instant death threshold, and the conditions under which the character stabilizes or dies.

---

### 🟢 feat: add Projectile action spell data and update .gitignore

[`b139fb4`](https://github.com/Yoonmoonsik/dnd55e/commit/b139fb43dbf31c186ed59543228c1751c9c67f11) · *yoonmoonsik*
Added Projectile action spell data for ranged weapon attacks. Implements the base ranged attack framework used by bows, crossbows, and firearms, ensuring correct attack roll and damage calculations.

---

### 🟢 feat: add Target action spell data and update .gitignore

[`0940318`](https://github.com/Yoonmoonsik/dnd55e/commit/0940318b145f28a4f0a8476ebb26953199d4a18f) · *yoonmoonsik*
Added Target action spell data for melee and targeted abilities. Implements the base targeting framework for single-target melee attacks and touch spells used across all classes.

---

### 🟢 feat: add SNEAKING status definition and update .gitignore

[`4caaf55`](https://github.com/Yoonmoonsik/dnd55e/commit/4caaf55f3d5c2342608829c3b614015594df8a6e) · *yoonmoonsik*
Added the **Sneaking** status definition. Implements the Hidden condition granted by the Hide action, including the rules for when stealth is broken and how it interacts with attack rolls and detection.

---

### ⚪ git commit -m "chore: stop tracking ignored files"

[`62008d0`](https://github.com/Yoonmoonsik/dnd55e/commit/62008d08f4fada2a1b54f383d04b200cf606fadc) · *yoonmoonsik*
Removed previously tracked files that are now covered by `.gitignore`. A repository cleanup with no gameplay impact.

---

### 🟢 Add resource files to .gitignore to prevent version control of generated data

[`b96265d`](https://github.com/Yoonmoonsik/dnd55e/commit/b96265db40549c3dac66e09c1490f0198f47078c) · *yoonmoonsik*
Added generated resource files to `.gitignore`. Prevents auto-generated stat output and data files from being committed, keeping the repository focused on source files only.

---

### 🟢 Add Shout and Dodge action spell data and status definitions

[`a80b5c4`](https://github.com/Yoonmoonsik/dnd55e/commit/a80b5c412648d25cc51c07e9b005c186498350e2) · *yoonmoonsik*

Added Shout action definitions for Dodge and Disengage combat actions.
Added DODGE status data and linked spell container entries for action integration

---

### 🔴 fix: block pre-combat dash speed exploit

[`bb33f5e`](https://github.com/Yoonmoonsik/dnd55e/commit/bb33f5edf54dc595e9e9c9d6ace7ac57c10dbd67) · *yoonmoonsik*

Fixed a pre-combat Dash exploit that allowed unintended movement speed carryover into combat.
Added a passive that automatically removes Dash-related statuses when combat starts.

---

### 🟢 Add .gitignore file to exclude game story-related files from version control

[`d29fda2`](https://github.com/Yoonmoonsik/dnd55e/commit/d29fda2b46990f9b3b335d6b4395d9c98ef86d39) · *yoonmoonsik*

Added .gitignore rules to exclude generated story and game-related files from version control.
Improved repository cleanliness by preventing temporary and locally generated files from being tracked.

---

### 🟢 Add passive data entries for weapon equipping and attack mechanics

[`d74f7c8`](https://github.com/Yoonmoonsik/dnd55e/commit/d74f7c876080f0ce86832d2ef9c09653ad76d143) · *yoonmoonsik*

Added passive data entries for weapon equipping behavior and attack interaction mechanics.
Implemented foundational passive definitions used for combat state handling and weapon-based action logic.

---

### 🟢 Add initial project files and symbolic links for dnd5.5e mod

[`b156a6d`](https://github.com/Yoonmoonsik/dnd55e/commit/b156a6dd6d74219f87c25679372ccb46b251f500) · *yoonmoonsik*

Added the initial DnD 5.5e mod project structure, including core folders and configuration files.
Added symbolic links and base setup files required for BG3 mod development and data integration.

---
