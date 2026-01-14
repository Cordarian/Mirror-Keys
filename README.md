# Mirror-Keys
Mirror Keys emulates a [half-QWERTY keyboard](https://en.wikipedia.org/wiki/Half-keyboard), allowing users to reach every key on their keyboard with a single hand.

## Description
Mirror Keys allows for one-handed typing on a normal QWERTY keyboard. By holding the spacebar and typing a key, it types the opposite key on the keyboard, e.g., Space+F types the letter J and vice versa. This lets users reach every key on the keyboard with one hand, acting as an assistive technology program for users who can only type with one hand, or as a productivity tool so users can type while keeping their other hand on the mouse. Key combinations also work with the mirrored keys, e.g., Shift+Space+1 types an exclamation mark (!), and Control+Space+Comma (,) sends Control+C to copy selected text.

Your keyboard still works like a normal QWERTY keyboard when you aren’t holding the spacebar. The spacebar will only type a Space character when it's pressed and release alone, without mirroring another key, to prevent Spaces being added unnecessarily.

**NOTE:** When typing very quickly, a key might accidentally be mirrored if there isn’t enough of a delay between releasing the spacebar and pressing the next key. The window for this is very brief, but Mirror Keys can be paused from the menu bar or tray icon to not interfere with normal keyboard operations.

## Mirror Map
![Mirror Keys' mirror map window, showing a QWERTY keyboard with additional symbols to indicate what key will be sent when that key is pressed while holding the spacebar.](https://github.com/user-attachments/assets/a3a59e48-f4ca-4725-a450-63f680c01c2f)

To help new users learn the mirrored keyboard layout, Mirror Keys also includes a keyboard map that launches as its own resizable window. The key map launches automatically with the program, and can be pinned to stay on top of all other program windows; both of these settings can be turned off through the menu bar as you get more accustomed to using the mirrored keyboard.

## Input Modes
To help avoid strain from having to hold down Space, other input modes can be used to mirror.

### Tap Space to toggle mirroring
In this mode, Space works like a toggle button, similar to CapsLock. Press space once, and every key after that will be mirrored until the next time Space is pressed. To actually type a Space in this mode, double-tap the Space key.

### Tap Space to mirror next key
Similar to the above, but Space will only mirror the next key that’s pressed after Space, rather than staying on until Space is pressed again. To actually type a Space in this mode, double-tap the Space key.

### Double-tap key to mirror [BETA]
Rather than having to type space at all, this mode will mirror a key if it’s double-tapped. The duration for what counts as a double-tap can be adjusted in the Input Settings menu.

**NOTE**: Key combinations like Ctrl+C may behave strangely in this mode, since the unmirrored key is sent before being deleted and mirrored on the second tap, so unexpected key combinations may be sent before the intended one.

### Hold key to mirror [BETA]
As above, this mode does not require you to type the spacebar to mirror a key, but instead mirrors any key that’s held down. The hold duration can be adjusted in the Input Settings menu.

**NOTE**: Typing rapidly in this mode may invert the key sequence, e.g., drumming your fingers to type “asdf” will result in “fdsa”.

## Warning for screen reader users
Mirror Keys may interfere with your screen reader if your JAWS/NVDA key is set to Caps Lock, since Mirror Keys changes Caps Lock to work like the Enter/Return key. Make sure your screen reader key is set to Insert or another key before trying to run Mirror Keys.

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
