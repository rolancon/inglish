# Inglish

Phonetic English

Version: 0.1

Datetime: 2016-03-30T21:36:15Z

## Overview

Inglish is a way to spell English phonetically while at the same time keeping the current spelling conventions. It does this by adorning the 26 letters of the Latin alphabet with various punctuation symbols and formatting markup.

Inglish adheres to the following principles:
- Keep the current spelling conventions for English as its basis
- However, only use lowercase letters for dictionary words
- Do not spell names phonetically: keep uppercase letters
- Use the semicolon (;) to separate sentences instead of the full stop (.)
- Use extended characters from the Unicode Latin code charts to express variations in pronunciation for the same base character
- This means the same character can have multiple renderings, each with a different punctuation, that symbolize 1 distinct sound per punctuated character
- Only use extended characters with punctuation that appears on top or under base Latin characters, in other words that do not modify the glyph of the base character
- The only minor exception is for extended characters that replace the dot on top of the 'i' and 'j' characters
- Characters that are not pronounced are formatted with del markup
- Sounds that do not appear in the spelling of the word are shown as characters that are formatted with inserted markup
- For words that have at least syllables the primary stress is shown with bold (strong) markup
- For words with more than two syllables the secondary stress is shown with italic (emphasized) markup
- The aspirated unvoiced stop is shown as a Unicode character U+00B4 (&#x00B4;) appended to the 't', 'p' or 'k' character
- The glottal stop is shown as Unicode character U+00B7 (&#x00B7;)

## Charts

### Closed vowels
|English|Inglish|IPA|
|:-----:|:-----:|:-:|
|bad|b&#x00E0;d||
|bed|b&#x00E8;d||
|did|d&#x00EC;d||
|nod|n&#x00F2;d||
|bud|b&#x00F9;d||
|hymn|h&#x1EF3;m<del>n</del>||

### Open vowels
|English|Inglish|IPA|
|:-----:|:-----:|:-:|
|ate|&#x00E1;t<del>e</del>||
|me|m&#x00E9;||
|hi|h&#x00ED;||
|no|n&#x00F3;||
|sue|s&#x00FA;<del>e</del>||
|why|w<del>h</del>&#x00FD;||
