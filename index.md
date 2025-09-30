---
layout: default
title: Falcon Plugin Manager
---

## 2025-09-30
- `4637851` Modify commit section generation to omit author
- `99593c9` Update commit summary format in workflow file
- `3a643da` Update publish-commit-summaries.yml
- `5e15d23` Modify publish-commit-summaries workflow description
- `1e5b6f6` Refactor GitHub Actions workflow for commit summaries
- `3922fe5` Refactor publish-commit-summaries workflow
- `12299fa` Modify commit range to include all commits
- `e8bb00a` Modify publish-commit-summaries workflow
- `48b85fc` Enhance commit summary workflow for changelog
- `f0b9d82` Add workflow to publish commit summaries to gh-pages
## 2025-09-29
- `a3a49f6` Healing menus now mirror Lanner’s formatting.
- `acbcfcf` Healing menus now mirror Lanner’s formatting
- `ef9649b` Healing item submodule + confi menu entry added to Autoheal module.
- `f7c220d` Saker cleaned up, removed dirs in rathena core dir except user yml conf.
- `74808dc` Saker now works when editing skills on the fly.
- `5314405` Saker now fully working.
- `239b610` all skills added to db
- `449602b` lanner finalized.
- `178a855` config working
- `5418177` conf window configured.
## 2025-09-28
- `9566c7c` Amur module fully working.
- `5f2d3a2` Taita fully working
- `3a018a6` taita added update to check loot first before attacking
- `8c629a7` lanner now fully working.
- `7003ed8` lanner+merlin now working.
- `fd88acd` lanner update
- `3bded04` lanner working, no delay.
- `e61afd2` final push before migration
## 2025-09-27
- `a9dcc17` added all skill related calls in bootstrap
## 2025-09-26
- `0cc26f5` Hunter system manual test.
- `e6b6a94` Hunter dummy test
- `5baa4ff` Hunter system initialized without error / no tasks yet.
- `2460a25` Hunter system initialized without error / no tasks yet.
- `f731d29` hunter update
- `0f55111` Hunter initialized.
- `08a17c7` init guard added
## 2025-09-25
- `2533277` re-entry guard for falconpm.cpp
- `37c9ef2` init guard
- `cee1864` one-shot guard / double-checked initialization guard for loader.cpp
- `6f97497` Updated bootstrap: idempotent initialization
- `0fc8f8d` hunter module update.
- `30b597a` Hunter module started.
- `4d510ba` working lanner
## 2025-09-24
- `546785b` lanner fully working.
- `cc906cb` lannel fully loaded
- `98809d0` lanner updated
- `7a0a4ba` lanner added
- `b76dd46` patched the core and infrastructure files successfully for the menu patch
- `df2a1e0` initial addition of menu system.
- `0fdf1d7` Merline + Peregrine orchestration finalized.
- `a1fcf17` Merlin working perfectly but does not call Peregrine
## 2025-09-23
- `9c22fdc` compiled without errors modified merlin
- `51f13b7` merlin update
## 2025-09-24
- `7be2da3` .gat files added in db
## 2025-09-23
- `566b04e` merlin update
- `713fa6d` merlin updated
- `d75147a` merlin attk first mob
- `11ffaf7` last update
- `68fd2f7` at cmd bridge in autoattack
- `9294c70` more debugging logs for merlin added
- `7df5be8` merlin anti ks phase 1 working
- `0605bf4` before processed data update
- `bb98e4b` anti KS phase 1 implementation
- `0a7d034` merlin working but not using peregrine
- `29d9ae0` merlin now owns attack logic
- `8993b09` refactored merlin
- `8c59ba5` loading but memory leak
- `655b983` basicauto attack working
- `af253fc` refactored
- `04cc24f` ctx > g_ctx core change.
## 2025-09-22
- `ad7bd66` compiled but segmentation fault crash
- `297f743` Merlin build suces.
- `9320416` Merlin AI updated.
- `26e7f7d` updated .cpp bridge
- `2f276ef` bridge compiled to work with Merlin & Taita
- `09e4ac7` auto attack enabled
- `b64b07a` compiled but no map data
## 2025-09-21
- `23e0ad6` merlin base added
## 2025-09-22
- `b0cfdc2` base for merlin AI added
## 2025-09-21
- `cab09a9` humanized auto-routing finalized
- `864aa7e` Add moc_fild07.gat map file
- `c93af37` PeregrineAI now working..
- `cd17817` refactored named for Peregrine System
- `f639ed1` smart routing
- `d73083c` remove portals from AI dir
- `4bef7ca` peregrine smart routing/pathing initialized
## 2025-09-20
- `81d0664` AI system created
- `793d7e5` Peregrine subsystem is now working
## 2025-09-21
- `5c58cdf` added gat file
## 2025-09-20
- `6764719` rAthner pathing enabled
- `b4c49df` jitter & skipped step enabled
- `0733362` auto walk random xy enabled
- `816c119` working atxy to a random location
- `0e5242b` atxy working
- `9837bcd` added bootstrap
- `ca39c13` bridge file added
- `18c4dae` bridge for @command now working
- `5f59258` added peregrine bridge
- `7223fc0` yml file added
- `11eb29b` updated autoroute
- `41defb7` loaded autoroute.so
- `457cc5d` loaded autoroute plugin
- `fdf0add` plugins can now be fully loaded
- `b9716c3` FalconPM is now fully hooked up and in production-grade ready.
- `fbbd7a2` updated autoroute
- `3ce0a6e` updated loader.cpp and plugins_api.h
## 2025-09-19
- `bd9696d` before global declaration
- `a3f6818` added rAtena's internal APIs and identifiers
- `7665232` added first in-game test
- `2308dc6` working hello plugin
- `eef19ae` updated files to working plugin, no more calls to global g_api
- `bbbed94` changes from the vps
- `1383f2e` plugin
- `2ead70a` refactored
- `ecb449d` updated
- `3e0942b` FalconPM logs in terminal
- `8b51261` updated main.ccp
- `eb27ffd` updated CMake
## 2025-09-18
- `e218f88` added developing_plugins doc
- `fbd1df1` updated CMakeList
- `d3e30cb` updated loader
- `35152de` updated headers
- `82e42db` added map.cpp
- `9cfc0e3` added GPL headers
- `d868bda` refactored
- `eb0245d` added plugin_api.hpp
- `81ce463` added setup installer
- `80583bc` added cross-map router
- `6d57d73` added portal db
- `9b9c3fa` added high-level map executor
- `cc223cd` multimap conectivity update
- `908d7ba` added pathing for local maps
- `6231122` added multimap graph routing
- `07394bf` added portal loader in base
- `052a999` added unlockitems.txt
- `1572f7b` unlock.md created
- `8800f17` updated readme
- `7fceb09` docs folder and moved files
- `d0e7192` added config.ylm, sponsor.md and FUNDING.yml
- `9e2faf2` added @ command aliases
- `4e105e3` added status plugin
- `d79dc62` added other issues template
- `c91a52c` Update issue templates
- `b581044` Update issue templates
- `18d6957` added teleport option for autocombat and autostorage
- `fae1e87` added autostorage plugin
- `d460b78` added ROADMAP.md
- `c3851bb` added FEATURES.md
- `c8a08b7` added weight limit and item filter in menu
- `4ae4aab` updated item filter + weight limit for autoloot plugin
- `dffd1fd` added autoloot menu
- `dba9c5f` added autoloot plugin
- `e9b98cf` added mob search in Manager NPC
- `232509b` updated falcone manager
- `6ac5f55` renamed plugins, merged autopots to autocombat
- `13c4649` added ARCHITECHTURE.md
- `2640fe1` updated README.md
- `31f3df1` updated README.md
- `87365c0` updated README.md
- `1cf59e3` updated README.md
- `f997e18` added humanized code blocks for helpers
- `b740e32` Initial upload
- `a23edf4` Initial commit
