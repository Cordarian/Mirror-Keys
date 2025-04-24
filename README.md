# Mirror-Keys
Mirror Keys emulates a half-QWERTY keyboard, allowing users to reach every key on their keyboard with a single hand.

## Description
Mirror Keys allows for one-handed typing on a normal QWERTY keyboard. By holding the spacebar and typing a key, it types the opposite key on the keyboard, e.g., Space+F types the letter J and vice versa. This lets users reach every key on the keyboard with one hand, acting as a productivity tool so users can type while keeping their other hand on the mouse, or acting as an assistive technology program for users who can only type with one hand. Key combinations also work with the mirrored keys, e.g., Shift+Space+1 types an exclamation mark (!), and Control+Space+Comma (,) sends Control+c to copy selected text.

Your keyboard still works like a normal QWERTY keyboard when you aren’t holding the spacebar.

**NOTE:** When typing very quickly, a key might accidentally be mirrored if there isn’t enough of a delay between releasing the spacebar and pressing the next key. The window for this is very brief, but Mirror Keys can be paused from the menu bar or tray icon to not interfere with normal keyboard operations.

## Mirror Map
![A QWERTY keyboard with additional symbols on each key to indicate what key is sent when that key is pressed while holding the spacebar.](https://github.com/user-attachments/assets/a3a59e48-f4ca-4725-a450-63f680c01c2f)

To help new users learn the mirrored keyboard layout, Mirror Keys also includes a keyboard map that launches as its own resizable window. The key map launches automatically with the program, and can be pinned to stay on top of all other program windows; both of these settings can be turned off through the menu bar as you get more accustomed to using the mirrored keyboard.

## How does it work?

This stand-alone tool is written in AutoHotkey v2. You can download and run the .exe file by itself, or view the whole code in the .ahk file, which can be run without the .exe using [AutoHotkey](https://www.autohotkey.com/).

## Full Key Listing
**Caps Lock Note:** With Mirror Keys running, the Caps Lock key acts like the Enter/Return key **when the spacebar is not pressed** and as the apostrophe/quotation mark key (’/”) when the spacebar is pressed.

| To send this key… | …press this key while holding the spacebar |
| --- | --- |
| A | ; |
| B | N |
| C | , |
| D | K |
| E | I |
| F | J |
| G | H |
| H | G |
| I | E |
| J | G |
| K | D |
| L | S |
| M | V |
| N | B |
| O | W |
| P | Q |
| Q | P |
| R | U |
| S | L |
| T | Y |
| U | R |
| V | M |
| W | O |
| X | . |
| Y | T |
| Z | / |
| Backspace | Tab |
| Tab | [ or ] or \ |
| 1 | 0 |
| 2 | 9 |
| 3 | 8 |
| 4 | 7 |
| 5 | 6 |
| 6 | 5 |
| 7 | 4 |
| 8 | 3 |
| 9 | 2 |
| 0 | 1 |
| ` | - or = |
| ~ | + (Shift+=) |
| ! | ) (Shift+0) |
| @ | ( (Shift+9) |
| # | * (Shift+8) |
| $ | & (Shift+7) |
| % | ^ (Shift+6) |
| ^ | % (Shift+5) |
| & | $ (Shift+4) |
| * | # (Shift+3) |
| ( | @ (Shift+2) |
| ) | ! (Shift+1) |
| - | ` |
| _ | ~ (Shift+`) |
| ; | A |
| : | Shift+A |
| ' | CapsLock |
| " | Shift+CapsLock |
| , | C |
| < | Shift+C |
| . | X |
| > | Shift+X |
| / | Z |
| ? | Shift+Z |
| F1 | F12 |
| F2 | F11 |
| F3 | F10 |
| F4 | F9 |
| F5 | F8 |
| F6 | F7 |
| F7 | F6 |
| F8 | F5 |
| F9 | F4 |
| F10 | F3 |
| F11 | F2 |
| F12 | F1 |
