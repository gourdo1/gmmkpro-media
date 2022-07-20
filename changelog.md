# [gourdo1's](mailto:gourdo1@outlook.com) GMMK Pro layouts -- Changelog

## 2022

    July 19 - Fixed toggle menu rendering on ISO layouts
    July 18 - Fixed left-shift not working properly in games. Now the 'double tap left shift for capslock' works as expected: Either [FN][Winkey] (or [FN]5) will disable it and it shouldn't interfere with use of left-shift in games any longer.
    July 1  - (Partial) fix for ISO layouts not displaying config screen properly
    June 29 - MAJOR UPDATE
            - Persistent, toggle-able customizations. Open a text editor and hit [FN]` (tilde) to see what you can change in real-time without using VIA or compiling your own QMK firmware.
            - Added toggle for forcing CTRL- & SHIFT-SPACE to function like regular SPACE ([FN]8)
            - Eliminated delays on numpad engage and ESC key (replaced tapdances with custom code)
            - Initial ISO layout support
    June 28 - Changed RGB backlight timeout indicator to use [FN] F-key row exclusively
    June 22 - expanded the list of symbols that DON'T interrupt Caps Word to include backspace, delete, all numbers, all symbols above number keys as well as dash, underscore, colon, semicolon, quote, double quote, grave and tilde. Also, Caps Word no longer applies shift to any non-alpha keys
    June 16 - tweaked starting background color so hue steps properly align to solid RGB colors
    May  31 - QMK added native CapsWord, so switched to built-in function with custom 10sec idle timeout
    May  30 - Due to a folder restructure by the QMK team, keymap is now located here: https://github.com/qmk/qmk_firmware/tree/master/keyboards/gmmk/pro/rev1/ansi/keymaps/gourdo1
            - Fixed EEPROM reset function [FN][ESC] (QMK Q2 update fix)
    May  24 - Completed a refactor of RGB background effects:
            - There are now 24 effect modes accessible by hitting Fn-Up or Down arrow keys
            - RGB backlight effects expanded to include framebuffer effects and reactive keypress modes
            - Effect mode and custom background HSV values are now stored in EEPROM so they persist after power off
    May  17 - Numpad layer now uses Spacebar as Enter for rapid number entry
            - Added single-handed shortcut for WinKey-L (lock Windows): [FN]L
    May  14 - Added Single-handed shortcut for Ctrl-Alt-Delete: [FN]/
    May  14 - Added shortcut: [FN][Encoder press] puts PC to Sleep
    May   5 - Added paddle game; Accessible via [FN]P; Hit [FN]P again or double tap [ESC] to exit
    Apr  11 - Added multi-monitor app moving shortcuts: [FN] ],[ (square brackets) to move current app window to next monitor
            - Added [FN][ESC] to clear EEPROM
            - Added [FN]R to toggle N-key Rollover
    Apr   7 - Added some domain shortcuts: [FN]. for .com, [FN]O for outlook.com, [FN]Y for yahoo.com, [FN]H for hotmail.com, [FN]G for gmail.com
    Mar  16 - VIA support enabled. See: https://www.caniusevia.com/
    Mar  15 - Added Mouse Keys to numpad layer. Mouse Keys allow you to control the mouse without taking your hand off the keyboard
    Feb  26 - Added double tap [ESC] to revert to base layer
    Feb  25 - Caps Word enabled: To capitalize the next word only, press and release left and right shift at the same time
    Feb  17 - Added exponential encoder - quick repeated volume up doubles increase; quick repeated volume down triples decrease
    Feb   4 - Added RGB backlight saturation: [FN]Q & [FN]E
    Feb   1 - Tweaks to Numpad layer keymap
    Jan  27 - Tweaks to keymap affecting Del, Ins, Home, Print, Scroll, Pause
    Jan  24 - Turned off modded spacebar keys (CTRL- & SHIFT-space act like space)
    Jan  20 - Enabled LTO to reduce firmware size
    Jan  18 - Completed first set of tweaks to RGB backlighting effects and FN layer
    Jan   4 - First build uploaded to GitHub based on Jonavin's ANSI GMMK Pro layout
