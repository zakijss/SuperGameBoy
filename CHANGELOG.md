# Changelog

## v1.4 (2026-11-19)

- The live layer quits while a game or app runs and starts again a few seconds after you return to
  the menu. Games get back the 33 MB of memory it holds. Before, it stayed in memory and only
  stopped drawing.
- A boot logo for Easy Logotweak, shown at power-on before Onion starts: Super GAME BOY ++ over
  the logo wall, between the theme's top and bottom bars. It is in the full zip, in
  `App/EasyLogoTweak/logos`.
- A RetroArch menu theme: the logo wall in cool grey behind the menu, the theme's glass bars and
  rules, white entries, the selected entry in light red and cyan titles. It is in the full zip, in
  `RetroArch/.retroarch/assets/rgui`. The README says how to switch to it.
- SGB Live's line in Apps says how much memory the live wallpaper uses.

## v1.3 (2026-11-19)

- The save-and-shut-down screen, the low-battery screen, the switches in Tweaks and Package
  Manager, the four-line pop-up menu and the game switcher's arrows are in the theme's look. Onion's
  own art no longer shows on any of them.
- Below 5 % the empty battery icon has a red outline.
- Icons for the blueMSX and SquirrelJME cores.
- Pictures for the Ports genre folders: Action, Arcade, FPS and its four collections, Platform,
  Puzzle games, Racing, Reflex, RPG and Space. They are in the full zip, in `Roms/PORTS/Imgs`.
- SGB Live in Apps turns the live wallpaper off and on again.
- Battery saver: below 20 % the live wallpaper stops, and it comes back once the battery is at
  25 %.
- Fix: the live layer started at boot even when another theme was active, and stayed in memory. It
  now starts only with this theme and stops when you choose another one. After choosing the theme,
  restart or open SGB Live.

## v1.2.1 (2026-11-08)

- Fix: the red text (the list counter and the selected name in grid view) is lighter, so it stays
  readable on red glass at half brightness.

## v1.2 (2026-11-08)

- The theme folder is now `Silky Remix SUPER GAME BOY++ by ZJSS`, named as Onion's theme repository
  asks. If you had v1.1, delete `Themes/Silky Remix SUPER GAME BOY++ modded by ZJSS` after
  installing.
- The icons are also an icon pack of their own, `SUPER GAME BOY++ by ZJSS`.
- The theme and the icon pack can be installed from MiniMart.

## v1.1 (2026-11-07)

- The game switcher's top bar shows the Super GAME BOY ++ logo, on two lines so it clears the play
  time.
- Fix: after you closed a game, the Games tile could keep the plain art instead of the game's
  screenshot, because the theme read the screenshot while Onion was still writing it. It now waits
  for the complete file.
- The theme's readme describes the two sounds and the two waves of lit logos.

## v1.0 (2026-11-07)

First release: the logo wall with its two waves, frosted glass, the live Games and Apps tiles,
pixel-art icons, the battery percentage and the sounds.
