---
layout: plugin

id: CrealityTemperature
title: Creality Temperature Fix
description: Fix to parse correctly temperatures from Creality printer
authors:
- Romain Odeval
- Jean-Christophe Heger
- Jason Prokopowich
license: AGPLv3

date: 2024-03-06

homepage: https://github.com/jprokopowich/OctoPrint-CrealityTemperature/
source: https://github.com/jprokopowich/OctoPrint-CrealityTemperature/
archive: https://github.com/jprokopowich/OctoPrint-CrealityTemperature/releases/latest/download/master.zip

# Set this to true if your plugin uses the dependency_links setup parameter to include
# library versions not yet published on pypi. SHOULD ONLY BE USED IF THERE IS NO OTHER OPTION!
#follow_dependency_links: false

tags:
- creality
- temperature
- e5p

compatibility:
  octoprint:
  - 1.3.0
  os:
  - linux
  - windows
  - macos
  - freebsd

  python: '>=2.7,<4'
---

Fix to parse correctly temperatures from Creality Ender 5 Plus printers.
Originally created by Jean-Christophe Heger on https://community.octoprint.org/t/temperature-info-not-parsed-correctly/3557/12

Tested on :
* CR-10S Pro
* CR-X
* Ender 5 Plus
