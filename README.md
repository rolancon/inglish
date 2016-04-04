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
- Do not spell foreign words phonetically: keep vowels and consonants as-is
- Use the semicolon (;) to separate sentences instead of the full stop (.)
- Use extended characters from the Unicode Latin code charts to express variations in pronunciation for the same base character
- This means the same character can have multiple renderings, each with different punctuation, which symbolizes 1 distinct sound per punctuated character
- Only use extended characters with punctuation that appears on top or under base Latin characters, in other words that do not modify the glyph of the base character
- The only minor exception is for extended characters that replace the dot on top of the 'i' and 'j' characters
- Characters that are not pronounced are formatted with italic markup
- Sounds that do not appear in the spelling of the word are shown as characters that are formatted with inserted markup
- The primary stress is shown with bold (strong) markup
- The aspirated unvoiced stop is shown as a Unicode character U+00B4 acute accent (&#x00B4;) appended to the 't', 'p', 'k' or 'q' character
- A compound noun is shown with a Unicode character U+00B7 middle dot (&#x00B7;) in between

## Charts

### Closed vowels
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|bad|b<b>&#x00E0;</b>d||
|e|bed|b<b>&#x00E8;</b>d||
|i|did|d<b>&#x00EC;</b>d||
|o|nod|n<b>&#x00F2;</b>d||
|u|bud|b<b>&#x00F9;</b>d||
|y|hymn|h<b>&#x1EF3;</b>m<i>n</i>||

### Open vowels
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|a|ate|<b>&#x00E1;</b>t<i>e</i>||
|e|me|m<b>&#x00E9;</b>||
|i|hi|h<b>&#x00ED;</b>||
|o|no|n<b>&#x00F3;</b>||
|u|sue|s<b>&#x00FA;</b><i>e</i>||
|y|why|w<i>h</i><b>&#x00FD;</b>||

### Basic consonants
||English|Inglish|IPA|
|:-:|:-----:|:-----:|:-:|
|b|bad|b<b>&#x00E0;</b>d||
|c|can|c<b>&#x00E0;</b>n||
|d|did|d<b>&#x00EC;</b>d||
|f|far|f<b>&#x00E2;</b>r||
|g|gun|g<b>&#x00F9;</b>n||
|h|hi|h<b>&#x00ED;</b>||
|j|jar|j<b>&#x00E2;</b>r||
|k|keep|k<b>&#x00B4;&#x00E9;</b><i>e</i>p||
|l|lid|l<b>&#x00EC;</b>d||
|m|me|m<b>&#x00E9;</b>||
|n|no|n<b>&#x00F3;</b>||
|p||<b>&#x00B4;&#x00;</b>||
|q||<b>&#x00B4;&#x00;</b>||
|r||<b>&#x00;</b>||
|s||<b>&#x00;</b>||
|t||<b>&#x00B4;&#x00;</b>||
|v||<b>&#x00;</b>||
|w||<b>&#x00;</b>||
|x||<b>&#x00;</b>||
|y||<b>&#x00;</b>||
|z||<b>&#x00;</b>||
