# Changelog


## 2025-09-18
- `a23edf4` Initial commit
- `b740e32` Initial upload
- `f997e18` added humanized code blocks for helpers
- `1cf59e3` updated README.md
- `87365c0` updated README.md
- `31f3df1` updated README.md
- `2640fe1` updated README.md
- `13c4649` added ARCHITECHTURE.md
- `6ac5f55` renamed plugins, merged autopots to autocombat
- `232509b` updated falcone manager
- `e9b98cf` added mob search in Manager NPC
- `dba9c5f` added autoloot plugin
- `dffd1fd` added autoloot menu
- `4ae4aab` updated item filter + weight limit for autoloot plugin
- `c8a08b7` added weight limit and item filter in menu
- `c3851bb` added FEATURES.md
- `d460b78` added ROADMAP.md
- `fae1e87` added autostorage plugin
- `18d6957` added teleport option for autocombat and autostorage
- `b581044` Update issue templates
- `c91a52c` Update issue templates
- `d79dc62` added other issues template
- `4e105e3` added status plugin
- `9e2faf2` added @ command aliases
- `d0e7192` added config.ylm, sponsor.md and FUNDING.yml
- `7fceb09` docs folder and moved files
- `8800f17` updated readme
- `1572f7b` unlock.md created
- `052a999` added unlockitems.txt
- `07394bf` added portal loader in base
- `6231122` added multimap graph routing
- `908d7ba` added pathing for local maps
- `cc223cd` multimap conectivity update
- `9b9c3fa` added high-level map executor
- `6d57d73` added portal db
- `80583bc` added cross-map router
- `81ce463` added setup installer
- `eb0245d` added plugin_api.hpp
- `d868bda` refactored
- `9cfc0e3` added GPL headers
- `82e42db` added map.cpp
- `35152de` updated headers
- `d3e30cb` updated loader
- `fbd1df1` updated CMakeList
- `e218f88` added developing_plugins doc
## 2025-09-19
- `eb27ffd` updated CMake
- `8b51261` updated main.ccp
- `3e0942b` FalconPM logs in terminal
- `ecb449d` updated
- `2ead70a` refactored
- `1383f2e` plugin
- `bbbed94` changes from the vps
- `eef19ae` updated files to working plugin, no more calls to global g_api
- `2308dc6` working hello plugin
- `7665232` added first in-game test
- `a3f6818` added rAtena's internal APIs and identifiers
- `bd9696d` before global declaration
## 2025-09-20
- `3ce0a6e` updated loader.cpp and plugins_api.h
- `fbbd7a2` updated autoroute
- `b9716c3` FalconPM is now fully hooked up and in production-grade ready.
- `fdf0add` plugins can now be fully loaded
- `457cc5d` loaded autoroute plugin
- `41defb7` loaded autoroute.so
- `11eb29b` updated autoroute
- `7223fc0` yml file added
- `5f59258` added peregrine bridge
- `18c4dae` bridge for @command now working
- `ca39c13` bridge file added
- `9837bcd` added bootstrap
- `0e5242b` atxy working
- `816c119` working atxy to a random location
- `0733362` auto walk random xy enabled
- `b4c49df` jitter & skipped step enabled
- `6764719` rAthner pathing enabled
## 2025-09-21
- `5c58cdf` added gat file
## 2025-09-20
- `793d7e5` Peregrine subsystem is now working
- `81d0664` AI system created
## 2025-09-21
- `4bef7ca` peregrine smart routing/pathing initialized
- `d73083c` remove portals from AI dir
- `f639ed1` smart routing
- `cd17817` refactored named for Peregrine System
- `c93af37` PeregrineAI now working..
- `864aa7e` Add moc_fild07.gat map file
- `cab09a9` humanized auto-routing finalized
## 2025-09-22
- `b0cfdc2` base for merlin AI added
## 2025-09-21
- `23e0ad6` merlin base added
## 2025-09-22
- `b64b07a` compiled but no map data
- `09e4ac7` auto attack enabled
- `2f276ef` bridge compiled to work with Merlin & Taita
- `26e7f7d` updated .cpp bridge
- `9320416` Merlin AI updated.
- `297f743` Merlin build suces.
- `ad7bd66` compiled but segmentation fault crash
## 2025-09-23
- `04cc24f` ctx > g_ctx core change.
- `af253fc` refactored
- `655b983` basicauto attack working
- `8c59ba5` loading but memory leak
- `8993b09` refactored merlin
- `29d9ae0` merlin now owns attack logic
- `0a7d034` merlin working but not using peregrine
- `bb98e4b` anti KS phase 1 implementation
- `0605bf4` before processed data update
- `7df5be8` merlin anti ks phase 1 working
- `9294c70` more debugging logs for merlin added
- `68fd2f7` at cmd bridge in autoattack
- `11ffaf7` last update
- `d75147a` merlin attk first mob
- `713fa6d` merlin updated
- `566b04e` merlin update
## 2025-09-24
- `7be2da3` .gat files added in db
## 2025-09-23
- `51f13b7` merlin update
- `9c22fdc` compiled without errors modified merlin
## 2025-09-24
- `a1fcf17` Merlin working perfectly but does not call Peregrine
- `0fdf1d7` Merline + Peregrine orchestration finalized.
- `df2a1e0` initial addition of menu system.
- `b76dd46` patched the core and infrastructure files successfully for the menu patch
- `7a0a4ba` lanner added
- `98809d0` lanner updated
- `cc906cb` lannel fully loaded
- `546785b` lanner fully working.
## 2025-09-25
- `4d510ba` working lanner
- `30b597a` Hunter module started.
- `0fc8f8d` hunter module update.
- `6f97497` Updated bootstrap: idempotent initialization
- `cee1864` one-shot guard / double-checked initialization guard for loader.cpp
- `37c9ef2` init guard
- `2533277` re-entry guard for falconpm.cpp
## 2025-09-26
- `08a17c7` init guard added
- `0f55111` Hunter initialized.
- `f731d29` hunter update
- `2460a25` Hunter system initialized without error / no tasks yet.
- `5baa4ff` Hunter system initialized without error / no tasks yet.
- `e6b6a94` Hunter dummy test
- `0cc26f5` Hunter system manual test.
## 2025-09-27
- `a9dcc17` added all skill related calls in bootstrap
## 2025-09-28
- `e61afd2` final push before migration
- `3bded04` lanner working, no delay.
- `fd88acd` lanner update
- `7003ed8` lanner+merlin now working.
- `8c629a7` lanner now fully working.
- `3a018a6` taita added update to check loot first before attacking
- `5f2d3a2` Taita fully working
- `9566c7c` Amur module fully working.
## 2025-09-29
- `5418177` conf window configured.
- `178a855` config working
- `449602b` lanner finalized.
- `239b610` all skills added to db
- `5314405` Saker now fully working.
- `74808dc` Saker now works when editing skills on the fly.
- `f7c220d` Saker cleaned up, removed dirs in rathena core dir except user yml conf.
- `ef9649b` Healing item submodule + confi menu entry added to Autoheal module.
- `acbcfcf` Healing menus now mirror Lanner’s formatting
- `a3a49f6` Healing menus now mirror Lanner’s formatting.
## 2025-09-30
- `a95e3cc` AutoHeal module now properly attached to Menu.
- `52f4627` Built FalconPM built-in item database for each search.
- `1f08407` Adding menu, search, rules, behavious and presets to autoloot module.
- `3d23faa` Autoloot module added to menu.
- `9243902` Enhanced autoloot with AI
- `c63cbe3` Added all 28,532 rAthena items in items database.
- `e63d443` Party system added.
- `932442c` Search module added.
## 2025-10-01
- `221913e` Data Plubing - Extended YAML loader for combat presets.
## 2025-09-30
- `0741b03` Hunter tasks started.
## 2025-10-01
- `e77d151` Monster Intelligence added
- `45aac67` Reworked autoroute: now uses one-time O(widthxheight).
- `a2d2b22` Monster combat tags updated.
- `4eb389c` Create main.yml
- `1b16c4c` Add publish-commit-summaries workflow
- `30b070c` all skills priest working


## 2025-10-04
- `fb5d595` Update project description in README.md


## 2025-10-04
- `45662c0` Update README to change 'framework' to 'platform'


## 2025-10-06
- `8aa1c9e` Add Discord notification workflow on push events


## 2025-10-06
- `0df8c5d` Update Discord commit notification to show last 5 commits


## 2025-10-06
- `e76c8fd` Refactor Discord commit notification message format


## 2025-10-06
- `36719c7` Enhance Discord commit message with URLs and formatting


## 2025-10-06
- `f5517da` Improve Discord commit message formatting


## 2025-10-06
- `e81a6fe` Update discord-commits.yml


## 2025-10-06
- `8537076` Update discord-commits.yml
