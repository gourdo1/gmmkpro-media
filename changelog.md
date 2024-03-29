# [gourdo1's](mailto:gourdo1@outlook.com) GMMK Pro layouts -- Changelog

## 2023
    May  12 - Fix for stuck Encoder button
    Apr  10 - Updated firmware for compatibility with latest QMK v20.5
## 2022
    Dec  26 - Increased key debounce time to 8ms to reduce chatter issues.
    Aug   8 - Added [FN]0 as a config option (for ISO layouts only) to extend CapsLock RGB highlights to extended alpha keys.
            - Moved 'system numlock off' warning from base layer to FN and Numpad layers to improve Mac compatibility.
            - Fixed [FN]B and [FN]N shortcuts not working on numpad layer.
    July 31 - Added [FN]B as additional shortcut to bootloader mode (e.g. in case ISO flashed to ANSI keyboard).
    July 20 - Added toggle-able AutoCorrect with 400 word English dictionary; Uses Pascal Getreuer's implementation.
    July 19 - Fixed toggle menu rendering on ISO layouts.
    July 18 - Replaced 'double tap left-shift for Capslock' TapDance with custom code. No longer interferes with left-shift key.
    July  1 - (Partial) fix for ISO layouts not displaying config screen properly.
    June 29 - MAJOR UPDATE - Added persistent, toggle-able settings:
            - Open a text editor and hit [FN]` (tilde) to see what you can toggle.
            - Added toggle for forcing CTRL- & SHIFT-SPACE to function like regular SPACE ([FN]8).
            - Eliminated delays on numpad engage and ESC key (replaced tapdances with custom code).
            - Initial ISO layout support.
    June 28 - Changed RGB backlight timeout indicator to use [FN] F-key row exclusively.
    June 22 - Expanded the list of symbols that DON'T interrupt Caps Word to include: backspace, delete, all numbers, all
               symbols above number keys as well as dash, underscore, colon, semicolon, quote, double quote, grave and tilde.
            - Caps Word no longer applies shift to any non-alpha keys.
    June 16 - Tweaked starting background color so hue steps properly align to solid RGB colors.
    May  31 - QMK added native CapsWord, so switched to built-in function with custom 10sec idle timeout.
    May  30 - Due to a folder restructure by the QMK team, keymaps are now located in 'rev1' folder paths.
            - Fixed EEPROM reset function [FN][ESC] (QMK Q2 update fix).
    May  24 - Completed a refactor of RGB background effects:
            - There are now 24 effect modes accessible by hitting Fn-Up or Down arrow keys.
            - RGB backlight effects expanded to include framebuffer effects and reactive keypress modes.
            - Effect mode and custom background HSV values are now stored in EEPROM so they persist after power off.
    May  17 - Numpad layer now uses Spacebar as Enter for rapid number entry.
            - Added single-handed shortcut for WinKey-L (lock Windows): [FN]L
    May  14 - Added Single-handed shortcut for Ctrl-Alt-Delete: [FN]/
    May  14 - Added shortcut: [FN][Encoder press] puts PC to Sleep.
    May   5 - Added paddle game; Accessible via [FN]P. Hit [FN]P again or double tap [ESC] to exit.
    Apr  11 - Added multi-monitor app moving shortcuts: [FN] ],[ (square brackets) to move current app window to next monitor.
            - Added [FN][ESC] to clear EEPROM.
            - Added [FN]R to toggle N-key Rollover.
    Apr   7 - Added a few handy domain shortcuts:
               [FN]. for .com, [FN]O for outlook.com, [FN]Y for yahoo.com, [FN]H for hotmail.com, [FN]G for gmail.com
    Mar  16 - VIA support enabled. See: https://www.caniusevia.com/
    Mar  15 - Added Mouse Keys to numpad layer. Mouse Keys allow you to control the mouse without taking your hand off the keyboard.
    Feb  26 - Added double tap [ESC] to revert to base layer.
    Feb  25 - Caps Word enabled: To capitalize the next word only, press and release left and right shift at the same time.
    Feb  17 - Added exponential encoder - quick repeated volume up doubles increase; quick repeated volume down triples decrease.
    Feb   4 - Added RGB backlight saturation: [FN]Q & [FN]E
    Feb   1 - Tweaks to Numpad layer keymap.
    Jan  27 - Tweaks to keymap affecting Del, Ins, Home, Print, Scroll, Pause.
    Jan  24 - Turned off modded spacebar keys (CTRL- & SHIFT-space act like space).
    Jan  20 - Enabled LTO to reduce firmware size.
    Jan  18 - Completed first set of tweaks to RGB backlighting effects and FN layer.
    Jan   4 - First build uploaded to GitHub based on Jonavin's ANSI GMMK Pro layout.
