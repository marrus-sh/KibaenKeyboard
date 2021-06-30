# Kibben Keyboard for macOS

This repository contains a handwritten macOS Keyboard Bundle for the input of English text, with support for a wide variety of special characters and diacritics.

## Installation

01. Clone this repository, or download it as a ZIP and unzip its contents.

02. In Finder, click `Go > Go to Folder…` and type `~/Library`, then press Return to navigate to your user library folder.

03. Create the `Keyboard Layouts` directory if it doesn't already exist in this location.

04. Drag `Kibben.bundle` (from this repository) into the `Keyboard Layouts` folder.

05. Restart your computer.

## Usage

Open System Preferences, click on Keyboard, and then Input Sources.
Use the + button to add a new input source.
The Kibben keyboard will be available (as “Kybn”) under the English category.

## Notes

+ Caps Lock switches the keyboard into numeral input.
Alphabetic characters are replaced with Greek, numbers are replaced with counting rod numerals, and other punctuation is replaced with Roman numerals.

+ The keyboard is the same as a typical US keyboard layout when Caps Lock is active and the Option key is held down.

+ To output a standalone (spacing) diacritics, type the corresponding dead key and press space.

+ Option+Space produces a nonbreaking thin space, for use when padding punctuation.
Shift+Option+Space produces an ordinary nonbreaking space.
So, be sure to release Option if your intent is to type a breaking interword space.

## Changelog

+ **4.0:**
Removes most IPA letters, as well as Runic characters (which never got much use).
Adds additional symbols and numerals (including Greek) in their place.

+ **3.6:**
Replaces duplicate pound sign with missing double vertical bar.

+ **3.5:**
Replaces duplicate reverse empty set with missing dotted cross.

+ **3.4:**
Adds dagger as the Latin equivalent of Runic cross.

+ **3.3:**
Fixes missing underbar.
Rearranges number row symbols for ease of use.
Removes bars with quill, and adds registered and copyright signs instead.

+ **3.2:**
Adds missing numpad period.
Swaps single anglequotes and quotation dash.
Numbers are now shifted, with 0 appearing at QWERTY 1, and some rearrangement of special characters to match.

+ **3.1:**
Replaces forward‐emptyset with ounce sign, usable as an indicator of dozenal numbers.
This is not a maths layout and reverse‐emptyset is more suitable for Kibben.

+ **3.0:**
New updated Kibben keyboard layout, with a great deal many more diacritics and fewer obscure Latin characters.
More complete IPA support and repositioning of symbols.

+ **2.2:**
Fixes tilde behaviour.
Adds missing Open E characters with a slight rearrangement of the keyboard.
Removes automatic insertion of narrow spaces around punctuation.
Replaces raised omission brackets with dead keys for grave and acute accents.

+ **2.1:**
Provides remaining ASCII characters in the non‐capslocked keyboard and moves around some characters for easier access.

+ **2.0:**
Rename to “Kibben”/“Kybn”.
Basically an entirely new keyboard layout, with full support for the Kibben character set, including runes.
The vast majority of diacritic support has been dropped, as have most alternate or historical glyphs.
The former can typically be accessed through the macOS press‐and‐hold system, and the latter are unlikely to see enough use to justify a position in the keyboard.

+ **1.1:**
Bugfix for capital KRA.

+ **1.0:**
Initial release.
