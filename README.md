# Kibæn Keyboard for macOS

This repository contains a handwritten macOS Keyboard Bundle for the input of English text, featuring a large number of niche and archaïc characters.

## Installation

01. Clone this repository, or download it as a ZIP and unzip its contents.

02. In Finder, click `Go > Go to Folder…` and type `~/Library`, then press Return to navigate to your user library folder.

03. Create the `Keyboard Layouts` directory if it doesn't already exist in this folder.

04. Drag `Kibaen.bundle` (from this repository) into the `Keyboard Layouts` folder.

## Usage

Open System Preferences, click on Keyboard, and then Input Sources.
Use the + button to add a new input source.
The Kibæn keyboard will be available under the English category.

## Notes

+ The keyboard is the same as a typical US keyboard layout when the Option key is not held down.

+ Dead keys are located in the top row, assigned to the backtick and the digits `1–8` when the Option (but not Shift) key is held down.
These apply a variëty of diacritics: `` ` ``→`` ` ``; `1`→`˜`; `2`→`˚`; `3`→`´`; `4`→`ˇ`; `5`→`¨`; `6`→`^`; `7`→`¸`; `8`→`˙`.
Diacritics can be combined, although not all combinations are possible and not every diacritic can be applied to every letter.

+ To output a standalone accent, type the corresponding dead key and press space.
The accent produced by the tilde dead key will be `˜`, not `~`.

+ The “ring” dead key only actually produces a ring on a few characters (A and O).
For all other characters, it is used to select an alternate form (for example, an insular variant) and can be treated like another level of Option/Alt.

+ Option+Space produces a nonbreaking thin space, for use when padding punctuation (for example, in the French tradition).
Shift+Option+Space produces an ordinary nonbreaking space.
So, be sure to release Option if your intent is to type a breaking interword space.
Option+`,` produces a (breaking) enspace, and Option+`.` produces a (breaking) emspace.

+ The letters KRA `ĸ` and LONG S `ſ` have uppercase forms of `Kʼ` and `Sʼ`, respectively.
This is an ordinary Latin `K` and `S` followed by a MODIFIER LETTER APOSTROPHE.
When using a MODIFIER LETTER APOSTROPHE for other means (for example, normal English contractions), you *should* insert a U+034F COMBINING GRAPHEME JOINER between the two characters whenever the MODIFIER LETTER APOSTROPHE follows a `K` or `S` (possibly with diacritics), to keep these usages separate.
For example, “Sʼmores” should be written as `S`\<CGJ>`ʼmores`, to prevent the `Sʼ` from collating as LONG S.
Of course, making this distinction is only important in text which might make use of an uppercase LONG S or KRA.

+ At time of publication, not all characters output by this keyboard are formally in the Unicode Standard.
The spurious characters are:

	+ U+A7F1, which is hoped to be assigned as LATIN SMALL LETTER MIDDLE SCOTS S in a future Unicode version.
	+ U+A7F2, which is hoped to be assigned as LATIN CAPITAL LETTER MIDDLE SCOTS S in a future Unicode version.

Be cautious when typing these characters prior to their formal addition.
They are included here as mere placeholders.

## Changelog

+ **1.1:**
Bugfix for capital KRA.

+ **1.0:**
Initial release.
