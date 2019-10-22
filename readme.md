
epic -- Enhanced Programmer for Ingame Control

[![Build Status](https://travis-ci.org/thomasrudin-mt/epic.svg?branch=master)](https://travis-ci.org/thomasrudin-mt/epic)

# Overview

Create missions/quests ingame with programmable blocks

<img src="./screenshot.png"/>

## Status

WIP but usable

## Blocks

### MVP

* [x] Chat-message
* [x] Delay (conditional)
* [x] No-Op
* [x] Waypoint (conditional)
* [x] Teleport
* [x] Mob
* [x] Command
* [x] Branch-multiple
* [x] Call function
* [x] Mesecon emitter
* [x] Set gravity
* [x] Remove items
* [x] Remove mobs
* [x] Add item
* [x] lock/unlock section
* [x] Save state (savepoint)
* [x] Set epic timeout
* [x] Epic: main-function
* [x] Epic: cleanup-function
* [x] Epic: exit-on flags: leave/die/timeout
* [x] Epic executor: timeout
* [x] Set sky
* [x] Set sound (loop, once)
* [x] Clear sound
* [x] Mesecon receiver (conditional)

### TODO

* [ ] Inventory whitelist
* [ ] Check priv (conditional)
* [ ] Set day/night ratio
* [ ] Formspec message
* [ ] General: permissions/checks for non-admin placement
* [ ] Epic: Autostart block (with range)

# Settings

* **epic.log_executor** (bool) logs executor internals to the action log
* **epic.hud.offsetx** (float) hud x offset
* **epic.hud.offsety** (float) hud y offset

# Licenses

* default_steel_block.png / epic_node_bg.png / epic_mese_crystal.png
  * CC BY-SA 3.0 https://github.com/minetest/minetest_game

* 16x16 Icons in `textures/*`
  * CC BY-SA 3.0 http://www.small-icons.com/packs/16x16-free-toolbar-icons.htm
  * CC BY-SA 3.0 http://www.small-icons.com/packs/16x16-free-application-icons.htm
