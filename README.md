<!--lint disable awesome-git-repo-age-->

# Awesome FrSky ETHOS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources, Lua scripts, widgets, tools, and community projects for [FrSky ETHOS](https://www.frsky-rc.com/ethos/) — the operating system for FrSky's next-generation RC transmitters.

ETHOS is the modern operating system powering FrSky transmitters including the X20, X20S, X20 Pro, X18, X18S, X14, X14S, Twin X, Twin X Lite, and more. It features a touch-screen interface, Lua scripting support, and a rich widget system.

## Contents

- [Official Resources](#official-resources)
- [Lua Widgets](#lua-widgets)
  - [Telemetry & Dashboards](#telemetry--dashboards)
  - [Battery & Power](#battery--power)
  - [GPS & Mapping](#gps--mapping)
  - [Flight Modes & Status](#flight-modes--status)
  - [Gauges & Instruments](#gauges--instruments)
  - [Turbine & Jet](#turbine--jet)
- [Lua Scripts & Tools](#lua-scripts--tools)
- [Flight Controller Integration](#flight-controller-integration)
  - [Rotorflight](#rotorflight)
  - [DSM & Spektrum](#dsm--spektrum)
- [Layouts](#layouts)
- [Sound Packs](#sound-packs)
- [Desktop Tools](#desktop-tools)
- [Tutorials & Documentation](#tutorials--documentation)
- [Localization](#localization)
- [Community](#community)

## Official Resources

- [FrSky ETHOS](https://www.frsky-rc.com/ethos/) - Official ETHOS product page with firmware downloads and release notes.
- [ETHOS Suite](https://www.frsky-rc.com/ethos/) - Official companion app for managing transmitters, models, and firmware updates.
- [FrSkyRC/ETHOS-Feedback-Community](https://github.com/FrSkyRC/ETHOS-Feedback-Community) - Official feedback and bug tracking repository maintained by FrSky. Includes Lua code examples and community discussions.

## Lua Widgets

### Telemetry & Dashboards

- [vprheli/ETHOS-Lua](https://github.com/vprheli/ETHOS-Lua) - Collection of Lua widgets for FrSky ETHOS transmitters including telemetry displays and utility widgets.
- [robthomson/dashx-ethos](https://github.com/robthomson/dashx-ethos) - DashX telemetry dashboard for ETHOS with a clean, configurable multi-sensor display.
- [robthomson/omp-ofs3-dashboard](https://github.com/robthomson/omp-ofs3-dashboard) - OFS3 telemetry dashboard for ETHOS, purpose-built for OMP Hobby helicopters.
- [wmayvis/FrSky-Lua](https://github.com/wmayvis/FrSky-Lua) - Collection of different ETHOS Lua widget releases.
- [lthole/Ethos-Status-widget](https://github.com/lthole/Ethos-Status-widget) - Widget for displaying the status of a source with color-coded indicators.

### Battery & Power

- [BladeScraper-Designs/Ethos_BattSelector](https://github.com/BladeScraper-Designs/Ethos_BattSelector) - Battery selection and alerts widget with per-model pack tracking and voltage warnings.
- [RollingGecko/lua_avrLiX](https://github.com/RollingGecko/lua_avrLiX) - Average battery cell voltage calculation and display widget.

### GPS & Mapping

- [yaapu/EthosMappingWidget](https://github.com/yaapu/EthosMappingWidget) - Mapping widget for ETHOS with real-time GPS position display on offline maps.
- [PD5DJ/H4LGPSMAP](https://github.com/PD5DJ/H4LGPSMAP) - Hobb4life GPS map widget with path trace and home position tracking.

### Flight Modes & Status

- [andreaskuhl/cflmode](https://github.com/andreaskuhl/cflmode) - Color-coded flight mode display widget for quick visual flight mode identification.
- [andreaskuhl/3stated](https://github.com/andreaskuhl/3stated) - Widget for textual and color display of 3-state source values (switches, variables).
- [robthomson/RF2STATUS](https://github.com/robthomson/RF2STATUS) - Rotorflight 2 flight status widget displaying armed state, flight mode, and telemetry.

### Gauges & Instruments

- [PD5DJ/AdvGauge](https://github.com/PD5DJ/AdvGauge) - Advanced gauge widget with configurable min/max ranges, color zones, and needle display.
- [aviat40/ETHOS-Lua](https://github.com/aviat40/ETHOS-Lua) - Example Lua widget implementations for learning and reference, covering common widget patterns.

### Turbine & Jet

- [GIB2A/ETHOS-LUA-XICOY-JetCat-KingTech-and-JetMunt](https://github.com/GIB2A/ETHOS-LUA-XICOY-JetCat-KingTech-and-JetMunt) - Turbine telemetry widget for Xicoy ProHub with RPM, EGT, pump voltage, and fuel level display. Supports Basic/Expert configuration and themes.

## Lua Scripts & Tools

- [dronecontrol-ru/ethos-lua-scripts](https://github.com/dronecontrol-ru/ethos-lua-scripts) - Collection of general-purpose Lua scripts for FrSky ETHOS.
- [strgaltdel/FrSky-Ethos-VirtualSwitch](https://github.com/strgaltdel/FrSky-Ethos-VirtualSwitch) - Script to use the bottom toggles as multi-functional virtual switches.
- [andreaskuhl/soundsq](https://github.com/andreaskuhl/soundsq) - Widget for playing sequential voice announcements from sound files.
- [strgaltdel/Ethos-Uni-Receiver](https://github.com/strgaltdel/Ethos-Uni-Receiver) - Lua scripts for configuring universal receiver firmware from ETHOS.
- [Jedsters/Ethos-Lua](https://github.com/Jedsters/Ethos-Lua) - Collection of tools and scripts for use with FrSky ETHOS.
- [spoke2570/F3K_Fluff](https://github.com/spoke2570/F3K_Fluff) - F3K sport flyer widget with task timing and scoring for soaring competitions.
- [MiRe-CZ/gpsF3XTracker-for-Ethos](https://github.com/MiRe-CZ/gpsF3XTracker-for-Ethos) - GPS-based F3X tracker tool for RC glider slope racing (F3F).
- [AERCHeli/AERC_RF_Widgets](https://github.com/AERCHeli/AERC_RF_Widgets) - Collection of Rotorflight and ETHOS widgets from the AERC Heli community.

## Flight Controller Integration

### Rotorflight

- [rotorflight/rotorflight-lua-ethos-suite](https://github.com/rotorflight/rotorflight-lua-ethos-suite) - Official Rotorflight Lua configuration suite for ETHOS. Full flight controller setup and tuning directly from your transmitter.
- [rotorflight/rotorflight-lua-ethos](https://github.com/rotorflight/rotorflight-lua-ethos) - Rotorflight Lua scripts for ETHOS with telemetry display and configuration pages.
- [flounderscore/rotorflight-flight-log](https://github.com/flounderscore/rotorflight-flight-log) - Flight logger for ETHOS transmitters in combination with Rotorflight.
- [jimmy6616/Rotorflight-Frsky-Setup](https://github.com/jimmy6616/Rotorflight-Frsky-Setup) - Step-by-step instructions for FrSky ETHOS initial radio and Rotorflight configurator setup.

### DSM & Spektrum

- [frankiearzu/DSMTools](https://github.com/frankiearzu/DSMTools) - DSM forward programming tools for EdgeTX and ETHOS. Configure Spektrum receivers directly from your FrSky transmitter.

## Layouts

- [BladeScraper-Designs/Ethos_Layouts](https://github.com/BladeScraper-Designs/Ethos_Layouts) - Custom layout Lua scripts for ETHOS with alternative screen arrangements and widget placements.

## Sound Packs

- [oilytin/ETHOS-portal-sound-pack](https://github.com/oilytin/ETHOS-portal-sound-pack) - GLaDOS/Portal-themed sound pack for ETHOS. Adds personality to announcements with voice lines from the Portal game series.

## Desktop Tools

- [Ceeb182/ConvertToETHOSBMPformat](https://github.com/Ceeb182/ConvertToETHOSBMPformat) - Image converter tool to create BMP files in the format required by ETHOS for model images and backgrounds.
- [andrewfernie/EthosLogAnalyzer](https://github.com/andrewfernie/EthosLogAnalyzer) - Desktop application for analyzing and visualizing telemetry log files recorded by FrSky ETHOS transmitters.
- [RobertDarc/Frsky-telemetrie-DIY-sensor-module](https://github.com/RobertDarc/Frsky-telemetrie-DIY-sensor-module) - DIY telemetry sensor module (C++) for use with FrSky X20 and ETHOS.

## Tutorials & Documentation

- [strgaltdel/Ethos-lua-tutorial-en](https://github.com/strgaltdel/Ethos-lua-tutorial-en) - English-language Lua scripting tutorial for ETHOS covering widget development from basics to advanced topics.
- [jimmy6616/Ethos-Rotorflight](https://github.com/jimmy6616/Ethos-Rotorflight) - Guide for adjusting Rotorflight PIDs using an FrSky ETHOS transmitter.

## Localization

- [mgsanna/Ethos-ITALIA](https://github.com/mgsanna/Ethos-ITALIA) - Italian translation, localization, and documentation for FrSky ETHOS.

## Community

- [FrSky ETHOS Feedback Community](https://github.com/FrSkyRC/ETHOS-Feedback-Community/discussions) - Official GitHub Discussions for ETHOS feedback, questions, and feature requests.
- [FrSky RC Group on RCGroups](https://www.rcgroups.com/forums/showthread.php?3637147-FrSky-ETHOS) - Active community thread on RCGroups discussing ETHOS updates, tips, and tricks.
- [FrSky Official Facebook Group](https://www.facebook.com/groups/fraborsky) - FrSky community on Facebook.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. See the [LICENSE](LICENSE) file for details.
