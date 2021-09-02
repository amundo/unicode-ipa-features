# unicode-ipa-features

Experimenting with creating a database of default phonetic features for all IPA characters.

These databases are incomplete: there are no features for diacritics yet, for instance.

There are two data files in this repo:

1. `ipa-unicode.json` 

For each character which is part of the IPA, default features and a little metadata are provided. Sometimes characters correspond to a “complete” phone (a “grapheme”), but sometimes they are diacritics or modifier letters.

2. `ipa.json`

This is the bigger beast, which will be an ongoing project. It contains a sample inventory of phones (speech sounds) with Unicode representations and phonetic features.
