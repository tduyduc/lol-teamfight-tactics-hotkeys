# LOL Teamfight Tactics Champion Hot Keys

_Teamfight Tactics champion hot keys_

_© 2019–2020 T.D. Stoneheart. All rights reserved. Source code available under GPLv3 license._

-----

## Disclaimer

The author **does not** assume any responsibility when you use this script, as it is not related to, endorsed by, or affiliated with Riot Games by any way.

-----

## What this does

As the name implies, this script lets you buy champions in _Teamfight Tactics_ using the keyboard in the similar fashion as _Dota Underlords_.

A demonstration video can be found [here](https://www.youtube.com/watch?v=ScW1dGrifGU).

-----

## How to use

To buy a champion, press a number key from <kbd>1</kbd> to <kbd>5</kbd>, i.e. <kbd>1</kbd> buys the first champion in the pool, <kbd>2</kbd> buys the second champion, &c. To lock or unlock the champion pool, press <kbd>`</kbd> _(grave accent)_ key.

To stop the script, use the system tray icon and select _Exit_.

When the game window is not active, number keys retain their original role.

Number keys will intercept in-game chat messages with those numbers, so you can use numpad keys for chatting without buying champions.

Technically, this script creates a keyboard hook that watches user key input and invoke the _"buy champion"_ function when one of the expected correct number keys is pressed. Hot keys created using AutoIt's built-in `HotKeySet()` function won't work in the game window, so a WinAPI keyboard hook must be used.

-----

## Known issues

None yet. Yay!

-----
