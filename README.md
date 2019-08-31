# LOL Teamfight Tactics Champion Hot Keys

_Teamfight Tactics champion hot keys_

_© 2019 T.D. Stoneheart. Some rights reserved. Source code available under GPLv3 license._

-----

## Disclaimer

The author **does not** assume any responsibility when you use this script, as it is not related to, endorsed by, or affiliated with Riot Games by any way.

-----

## Introduction & How to use

As the name implies, this script lets you buy champions in Teamfight Tactics using the keyboard in the same fashion as Dota Underlords.

To buy a champion, press a number key from <kbd>1</kbd> to <kbd>5</kbd>, i.e. <kbd>1</kbd> buys the first champion in the pool, <kbd>2</kbd> buys the second champion, &c.

To stop the script, use the system tray icon and select _Exit_.

When the game window is not active, number keys retain their original role.

Number keys will intercept chat messages with those numbers, so you can use numpad keys for chatting without buying champions.

Technically, this script creates a keyboard hook that watches user key input and invoke the "buy champion" function when one of the expected correct number keys is pressed. AutoIt's built-in `HotKeySet()` function won't work in the game window, so a WinAPI keyboard hook must be used.

-----

## Known issues

None yet. Yay!

-----
