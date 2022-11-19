# EtheirysTomestoneMaru
An FFXIV fan TrueType font

## History:
The original Eorzean script created by Square Enix for Final Fantasy XIV is a set of glyphs which are direct representations of Latin alphabetic and numeric characters.

According to Tom (Dachoutom) of [dachoutom.org](https://dachoutom.org/), now defunct and archived on the [Wayback Machine](https://web.archive.org/web/20191021195711/http://dachoutom.org/.ffxiv/fonts.html), in-game examples of the characters were traced by two fans (possibly Tristis and AaronDMorgan) and released as a font file. This was later extended by Tom to include missing numerals, puntuation, and ligatures, and given the name Eorzean Extended.

When Square Enix released the FFXIV expansion Stormblood, a new script was included called Hingan, a direct rep-resentation of Japanese kana, with some omissions and extensions. Specifically, this is a single set of kana to represent both katakana and hiragana, and 25 ligatures are added which do not exist in Japanese. There are also 4 kanji and a set of stylized numerals which very strongly reflect the numerals of Eorzean. A community broadcast on 2017-10-31 showed off the character set and talked about their use.

Twitter user [@dol_z_dreams](https://twitter.com/dol_z_dreams) made a character set based on the contents of the comunity broadcast, which was then used to create a [web tool](ff14moomoo.com/kugane_font.html) where one could enter kana in a text box and get back an image of the same text in Hingashi script.

Reddit user [u/bulletbill4l](https://www.reddit.com/user/bulletbill4l) ([@Bwin4L on Twitter](https://twitter.com/Bwin4L)) took the extended Eorzean file and extended it again with traces of these characters, releasing it under the name Hingashi Extended.

I have extended this further by adding a set of special glyphs provided in the FFXIV Companion App which includes such things as job class symbols, player activity status symbols, and a variety of other in-game things, and released as Etheirys Tomestone. Etheirys is the canonical name of the world on which the events of FFXIV take place and tomestone is an in-game term for a variety of electronic relics which resemble memory cards, compact discs, and modern hand-held computers such as mobile phones. Some work was done to correct vector paths to eliminate self-intersections, correct path drawing directions, and align points to integers, making them useful for 3D printing and digital cutting tools. Em width was changed from 1000 points to 2048 points, both to match TTF best practices and to increase accuracy for very large representations. This file is hosted in the /origins directory as EtheirysTomestone.ttf along with it's source .sdf file.

I have now started the process of redrawing the entire font set in a maru style.

## Tips
In order to make use of the special in-game symbols which are in a private use Unicode range, I recommend the FOSS tool [WinCompose](https://github.com/samhocevar/wincompose) which allows Windows users to designate a key (right Alt by default) as a compose key. This is a special kind of key called a dead key which by itself does nothing and allows you to follow it with a series of keystrokes meant to be a mnemonic representation of the symbol you wish to type. This program allows not only the input of arbitraty Unicode characters (Compose u <4 or 5 digit Unicode hex number> Enter), but also allows you to define your own combo to generate any arbitrary character. For example, rather than Compose u f 0 3 6 Enter for the Blue Mage symbol, you could define it as Compose B L U. Linux users will likely already have a compose key function as well as a method of Unicode input.

## Progress:
- Basic Latin alphabet
- Numerals
- Punctuation
- Some mathematic symbols
- Some accented characters
- Some ligatures of Latin characters
- Some kana

## To do:
- Finish redrawing additional special characters
- Finish arranging Latin characters with accents and ligatures
- Finish redrawing mathematical symbols
- Finish redrawing kana
- Begin redrawing game symbols
- Learn to implement in-font kerning.
- Consider omission of unnecessary Companion App symbols and remap others to their matching codepoints for in-game use
